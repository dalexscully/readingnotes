reading-note-class-01
Reading Introduction for 201
How the Web Works.
Website Design and Process.
JavaScript Basics:
Compose a short poem describing how HTTP sends data between computers. The browser sends an HTTP request message to the server, asking it to send a copy of the website to the client. This message, and all other data sent between the client and the server, is sent across your internet connection using TCP/IP.

Describe how HTML, CSS, and JS files are “parsed” in the browser. When browsers send requests to servers for HTML files, those HTML files often contain link elements referencing external CSS stylesheets and script elements referencing external JavaScript scripts. It's important to know the order in which those files are parsed by the browser as the browser loads the page:

How can you find images to add to a Website? The HTML img tag is used to embed an image in a web page. Images are not technically inserted into a web page; images are linked to web pages

How do you create a String vs a Number in JavaScript? A string is a sequence of text known as a string. To signify that the value is a string, enclose it in single quote marks. A This is a number. Numbers don't have quotes around them.

What is a Variable and why are they important in JavaScript? Variables are containers that store values. You start by declaring a variable with the let keyword, followed by the name you give to the variable.

Introduction to HTML
What is an HTML attribute? HTML (HyperText Markup Language) is a markup language that tells web browsers how to structure the web pages you visit. It can be as complicated or as simple as the web developer wants it to be. HTML consists of a series of elements, which you use to enclose, wrap, or mark up different parts of content to make it appear or act in a certain way. The enclosing tags can make content into a hyperlink to connect to another page, italicize words, and so on. For example, consider the following line of text:

Describe the Anatomy of an HTMl element. The anatomy of our element is: The opening tag: This consists of the name of the element (in this example, p for paragraph), wrapped in opening and closing angle brackets. This opening tag marks where the element begins or starts to take effect. In this example, it precedes the start of the paragraph text. The content: This is the content of the element. In this example, it is the paragraph text. The closing tag: This is the same as the opening tag, except that it includes a forward slash before the element name. This marks where the element ends. Failing to include a closing tag is a common beginner error that can produce peculiar results.

What is the Difference between article and section element tags? The section tag defines a section in a document. The article tag specifies independent, self-contained content.

What Elements does a “typical” website include? It's good to understand the overall meaning of all the HTML sectioning elements in detail — this is something you'll work on gradually as you start to get more experience with web development. You can find a lot of detail by reading our HTML element reference. For now, these are the main definitions that you should try to understand:

main is for content unique to this page. Use main only once per page, and put it directly inside . Ideally this shouldn't be nested within other elements. article encloses a block of related content that makes sense on its own without the rest of the page (e.g., a single blog post). section is similar to article, but it is more for grouping together a single part of the page that constitutes one single piece of functionality (e.g., a mini map, or a set of article headlines and summaries), or a theme. It's considered best practice to begin each section with a heading; also note that you can break article up into different section, or section up into different article, depending on the context.

contains content that is not directly related to the main content but can provide additional information indirectly related to it (glossary entries, author biography, related links, etc.). header represents a group of introductory content. If it is a child of body it defines the global header of a webpage, but if it's a child of an article or section it defines a specific header for that section (try not to confuse this with titles and headings). nav contains the main navigation functionality for the page. Secondary links, etc., would not go in the navigation. footer represents a group of end content for a page.
How does metadata influence Search Engine Optimization? Using metadata boosts your SEO efforts because it's written in the search engine's language. This helps search engines better understand the topic of your webpages and content. It also helps them display more relevant results to searchers

How is the meta HTML tag used when specifying metadata? Metadata is data that describes data, and HTML has an "official" way of adding metadata to a document — the meta element. Of course, the other stuff we are talking about in this article could also be thought of as metadata too. There are a lot of different types of meta elements that can be included in your page's head, but we won't try to explain them all at this stage, as it would just get too confusing. Instead, we'll explain a few things that you might commonly see, just to give you an idea.

How to start to design a Website.
What is the first step to designing a Website? The first step to designing a website is get an idea and want to turn it into a website, there are a few questions you should answer before anything else: What exactly do I want to accomplish? How will a website help me reach my goals? What needs to be done, and in what order, to reach my goals? All of this is called project ideation and is a necessary first step to reach your goal, whether you are a beginner or an experienced developer.

What is the most important question to answer when designing a Website? This is the most important question to answer, since it drives everything else. List all the goals you want to reach. It can be anything: selling goods to make money, expressing political opinions, meeting new friends, gigging with musicians, collecting cat pictures, or whatever you want.

Semantics.
Why should you use an h1 element over a span element to display a top level heading? In HTML, for example, the h1 element is a semantic element, which gives the text it wraps around the role (or meaning) of "a top level heading on your page." The h1 This is a top level heading h1. The span style not a top-level heading span.

What are the benefits of using semantic tags in our HTML? Some of the benefits from writing semantic markup are as follows: Search engines will consider its contents as important keywords to influence the page's search rankings (see SEO) Screen readers can use it as a signpost to help visually impaired users navigate a page Finding blocks of meaningful code is significantly easier than searching through endless divs with or without semantic or namespaced classes Suggests to the developer the type of data that will be populated Semantic naming mirrors proper custom element/component naming

What is JavaScript?
Describe 2 things that require JavaScript in the Browser? The two things that requires JavaScript in the brower first will be HTML for it is the markup language that we use to structure and give meaning to our web content, for example defining paragraphs, headings, and data tables, or embedding images and videos in the page. Second, CSS is a language of style rules that we use to apply styling to our HTML content, for example setting background colors and fonts, and laying out our content in multiple columns.

How can you add JavaScript to an HTML document? HTML, JavaScript only needs one friend in the world of HTML — the <script> element.

Things I want to know more about
I want to submerge deeper into all the main components of HTML, CSS and JavaScript so I have a complete understanding.