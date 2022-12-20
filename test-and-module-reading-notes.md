# Testing and Modules

## In Tests We Trust — TDD with Python

This post is based on a talk that I did during Python Nordeste 2017. I hope you enjoy! Please don’t forget to give me some feedback.

Some time ago, when I was beginning my career as a programmer, I heard other programmers talking about two things: refactoring and unit tests. To be honest, they just talk about refactoring to explain why this practice should be avoided (and how scared they were to do it) and about unit tests to say they are too expensive to begin with, that they spend a lot of time, etc. Unit tests did sound like a utopian dream.

**Unit tests and TDD?**

Probably there are million of blog posts about this subject. But let’s talk just a bit about it on my point of view! 😅

Unit tests are some pieces of code to exercise the input, the output and the behaviour of your code. You can write them anytime you want.

**The freela**

Imagine that a client has a website and through it he receives a lot of contacts from potential customers. After a while he realized that it is important for the business to identify the profile of consumer: age, gender, job and so on. But the website just receive the name and the email.


There are some details to pay attention. The first one is the test name. The tests can be considered as your alive documentation. We need to be descriptive about it and to say what is expected and what we are testing. In this case we explicitly said: should return female when the name is from a female.

The test file name should follow the same name of module name. For instance, if our module is gender.py, our test name should be test_gender.py. It’s ideal to separate the tests folder from production code (the implementation) and to have something like this:

mymodule/

 — module.py

 — another_folder/

 — — another_module.py

tests/

 — test_module.py

 — another_folder/

 — — test_another_module.py

 **The Cycle**

I hope at this time you didn’t give up of this text because this is an example of an important thing about TDD: the cycle.

The cycle is made by three steps:

- 🆘 Write a unit test and make it fail (it needs to fail because the feature isn’t there, right? If this test passes, call the Ghostbusters, really)
- ✅ Write the feature and make the test pass! (you can dance after that)
- 🔵 Refactor the code — the first version doesn’t need to be the beautiful one (don’t be shy)
Using baby steps you can go through this cycle every time you add or modify a new feature in your code.

**TDD is not about the money/tests**

More than any checking, we need to think about our **software design first.**

One of the things that amaze me about TDD is how we can grow our software design consciously and well, just building what is needed to make the test pass. When we are writing tests we are forced to think about the design first and how we can break it into small pieces.

def test_should_return_male_when_the_name_is_from_male_gender():

    detector = GenderDetector()
    expected_gender = detector.run(‘Pedro’)
    assert expected_gender == ‘male’

    import requests

def run(self, name):

    result = requests.get('https://api.genderize.io/?name{}'

.format(name))

    return result['gender']
    

![](img/test%20and%20module.webp.png)    