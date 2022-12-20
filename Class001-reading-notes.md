# Pain vs. Suffering

## What’s your perspective?

My perspective is to achieve success and growth development in this amazing field of software development. My perspective to achieve greatest in this new career I have chosen so I can provide for my family. My perspective is to make the world better place through technology so everyone can thrive and achieve greatest on their own. My perspective is to leave a positive mark on this world through my work and do so through technology.

## Why are you doing this?

Computter developer was is and will remained to be something I enjoy doing for the foreseeable future. I believe the future is in technology and will be away to assist people far and wide easily through technological advances, and this is the main reason why I am doing this course. I ultimately want to help people and be a major contributor to society be applying my knowledge and expertise.

## Do you want what comes at the end of this journey?

The end of this journey in my opinion doesn't stop with Code Fellows for It is just to begin for me. The learning, the technical skills, the advancement in my career doesn't stop and will not stop. The end of this journey only aid me to go further on my continuation journey of learning computer developer.

## Are you doing this for you?

I am doing this for me, my family, my friends and all the people is this world that I can aid through my technolgical knowledge. In this world, I am only one of a billion plus people that of to contribute to this world in a positive manner.

<hr>

## A beginner's guide to Big O Notation

### O(1)

O(1) describes an algorithm that will always execute in the same time (or space) regardless of the size of the input data set.

bool IsFirstElementNull(IList String elements)

{

    return elements[0] == null;
}

### O(N)

O(N) describes an algorithm whose performance will grow linearly and in direct proportion to the size of the input data set. The example below also demonstrates how Big O favours the worst-case performance scenario; a matching string could be found during any iteration of the for loop and the function would return early, but Big O notation will always assume the upper limit where the algorithm will perform the maximum number of iterations.

bool ContainsValue(IEnumerable string elements, string value)

{

    foreach (var element in elements)
    {
        if (element == value) return true; 
    }     
    return false; 
}

### O(N²)

O(N²) represents an algorithm whose performance is directly proportional to the square of the size of the input data set. This is common with algorithms that involve nested iterations over the data set. Deeper nested iterations will result in O(N³), O(N⁴) etc.

bool ContainsDuplicates(IList string elements)
{

    for (var outer = 0; outer < elements.Count; outer++) 
    {
        for (var inner = 0; inner < elements.Count; inner++) 
        { 
            // Don't compare with self 
            if (outer == inner) continue;             
            
            if (elements[outer] == elements[inner]) return true; 
        }
    }    
    return false;
}

### O(2^N)

O(2^N) denotes an algorithm whose growth doubles with each addition to the input data set. The growth curve of an O(2^N) function is exponential — starting off very shallow, then rising meteorically. An example of an O(2^N) function is the recursive calculation of Fibonacci numbers:

int Fibonacci(int number)

{

    if (number <= 1) return number;
       
    return Fibonacci(number - 2) + Fibonacci(number - 1); 
}

<hr>

## Logarithms

Binary search is a technique used to search sorted data sets. It works by selecting the middle element of the data set, essentially the median, and compares it against a target value. If the values match, it will return success. If the target value is higher than the value of the probe element, it will take the upper half of the data set and perform the same operation against it. Likewise, if the target value is lower than the value of the probe element, it will perform the operation against the lower half. It will continue to halve the data set with each iteration until the value has been found or until it can no longer split the data set.

This type of algorithm is described as O(log N). The iterative halving of data sets described in the binary search example produces a growth curve that peaks at the beginning and slowly flattens out as the size of the data sets increase e.g. an input data set containing 10 items takes one second to complete, a data set containing 100 items takes two seconds, and a data set containing 1,000 items will take three seconds. Doubling the size of the input data set has little effect on its growth as after a single iteration of the algorithm the data set will be halved and therefore on a par with an input data set half the size. This makes algorithms like binary search extremely efficient when dealing with large data sets.

<hr>

## A friendly intro to Big O Notation

[Intro to Big O Notation "Click on link"](https://www.codenewbie.org/basecs/8)

<hr>

## Names and  Values in Python

[Ned Batchelder - Facts and Myths about Python names and values - PyCon 2015 "Click on link"](https://www.youtube.com/watch?v=_AEJHKGk9ns)

In the above video, the author eloquently explained in details how python works and the sequence on how to use python. It was very imformative to me for it seems like python as the same syntax and similar make up as javascript.

<hr>

## Things I want to know more about

I want to learn as much if not all the concepts and detail information about Python.