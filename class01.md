

# ch1 
## web page structure
![web page structure](https://i.pinimg.com/originals/01/4b/64/014b646fe38773b055174d1172c4632e.png)


##  HTML Uses Elements to Describe the Structure of Pages



There are several different elements. Each
element has an opening tag and a closing tag

![](https://worldntech.weebly.com/uploads/9/1/8/9/91898570/published/screen-shot-2017-04-14-at-8-38-30-am.png?1492139484)





## Description
Tags act like containers. They tell you
something about the information that lies
between their opening and closing tags.


![](https://worldntech.weebly.com/uploads/9/1/8/9/91898570/published/screen-shot-2017-04-14-at-8-38-58-am.png?1492139520)




## Attributes Tell Us More About Elements


Attributes provide additional information
about the contents of an element. They appear
on the opening tag of the element and are
made up of two parts: a name and a value,
separated by an equals sign.

![](https://4.bp.blogspot.com/-n2L2hlnBCB4/VPQ5yfwVvCI/AAAAAAAAAwo/C8eyZ2ANu_I/s1600/4.png)



# Body, Head & Title

`<body>`
You met the <body> element
in the first example we created.
Everything inside this element is
shown inside the main browser
window.
  
 ` <head>`
Before the `<body> `element you
will often see a `<head>` element.
This contains information
about the page (rather than
information that is shown within
the main part of the browser
window that is highlighted in
blue on the opposite page).
You will usually find a `<title>`
element inside the `<head>`
element.
`<title>`
The contents of the `<title>`
element are either shown in the
top of the browser, above where
you usually type in the URL of
the page you want to visit, or
on the tab for that page (if your
browser uses tabs to allow you
to view multiple pages at the
same time)
```html

<html>
<head>
 <title>This is the Title of the Page</title>
</head>
<body>
 <h1>This is the Body of the Page</h1>
 <p>Anything within the body of a web page is
 displayed in the main browser window.</p>
</body>
</html>

```
# Ch8

### HTML4

This version of HTML, created in 1999, included cascading style sheets (css) which allowed aspects such as text, colour, font and backgrounds to be easily altered. Instead of these aspects being included directly within the webpage, they are now separated, making it much more trouble-free.

#### DOCTYPE
```
<!DOCTYPE html PUBLIC
"-//W3C//DTD HTML 4.01 Transitional//EN"
"http://www.w3.org/TR/html4/loose.dtd">
```

### HTML 1.0
In 1998, a language called XML
was published. Its purpose
was to allow people to write
new markup languages. Since
HTML was the most widely used
markup language around, it was
decided that HTML 4 should be
reformulated to follow the rules
of XML and it was renamed
XHTML. This meant that
authors had to follow some new,
more strict rules about writing
markup. 

HTML 1.0 was the first version of HTML, used from 1989 to 1994. It was a very limited version and included only 20 elements. There wasn’t much that could be done with it and therefore most webpages ended up looking very similar due to the inability to do things such as; alter the page background, determine fonts and use tables and forms.

 
 
#### DOCTYPE
```
<!DOCTYPE html PUBLIC
"-//W3C//DTD XHTML 1.0 Strict//EN"
"http://www.w3.org/TR/xhtml1/DTD/
 xhtml1-strict.dtd">
``` 

###  HTML5

HTML 5 is the current version of HTML which is used. “We’ve come a long way since HTML could barely handle a simple page layout. HTML5 can be used to write web applications that still work when you’re not connected to the net; to tell websites where you are physically located; to handle high definition video; and to deliver extraordinary graphics.” (Marshall, 2017). HTML 5 continues to evolve and is supported by all of the biggest browsers such as Firefox, Chrome, Safari, Internet Explorer, Opera and Edge.

HTML has come very far since the first version (HTML 1.0), which only offered simple features meaning most webpages looked very similar. Since then the W3 Consortium has been established, css has been created, more features are supported by browsers and in general, more can be done with HTML. This means there’s less confusion, universal standards and ease of use. HTML is constantly progressing and changing — in a few decades, we can expect that HTML will have advanced even further.


#### DOCTYPE
```
<!DOCTYPE html>
```

### Comments in HTML

```
<!-- your comment-->
<!--
your comments
your comments
your comments
-->
```


### ID Attribute

The id attribute specifies a unique id for an HTML element (the value must be unique within the HTML document).


The id attribute is part of the __Global Attributes__, and can be used on any HTML element.

```html

<p id="pullquote">Every time I view the sea I feel
 a calming sense of security, as if visiting my
 ancestral home; I embark on a voyage of seeing.
</p>
```

###  Class Attribute
- The class is an attribute which specifies one or more class names for an HTML element.
- The class attribute can be used on any HTML element.
- The class name can be used by CSS and JavaScript to perform certain tasks for elements with the specified class name.

```HTML
<p class="important">For a one-year period from
 November 2010, the Marugame Genichiro-Inokuma
 Museum of Contemporary Art (MIMOCA) will host a
 cycle of four Hiroshi Sugimoto exhibitions.</p>
```
### Block Elements
Some elements will always
appear to start on a new line in
the browser window. These are
known as **block level** elements. 

Examples of block elements are [check them](https://www.w3schools.com/html/html_blocks.asp)
```
<h1>, <p>, <ul>, and <li>.
```
### Inline Elements
Some elements will always
appear to continue on the
same line as their neighbouring
elements. These are known as
**inline** elements.

Examples of inline elements are [check them](https://www.w3schools.com/html/html_blocks.asp)

```
<a>, <b>, <em>, and <img>
```

### Grouping Text & Elements In a Block 

There are two important tags which we use very frequently to group various other HTML tags `<div>` tag and `<span>` tag

The `<div>` tag
This is the very important block level tag which plays a big role in grouping various other HTML tags and applying CSS on group of elements. Even now <div> tag can be used to create webpage layout where we define different parts (Left, Right, Top etc.) of the page using <div> tag. This tag does not provide any visual change on the block but this has more meaning when it is used with CSS.

``` HTML
  
  <!DOCTYPE html>
<html>
   
   <head>
      <title>HTML div Tag</title>
   </head>
	
   <body>
      <!-- First group of tags -->
      <div style = "color:red">
         <h4>This is first group</h4>
         <p>Following is a list of vegetables</p>
         
         <ul>
            <li>Beetroot</li>
            <li>Ginger</li>
            <li>Potato</li>
            <li>Radish</li>
         </ul>
      </div>

      <!-- Second group of tags -->
      <div style = "color:green">
         <h4>This is second group</h4>
         <p>Following is a list of fruits</p>
         
         <ul>
            <li>Apple</li>
            <li>Banana</li>
            <li>Mango</li>
            <li>Strawberry</li>
         </ul>
      </div>
   </body>
   
</html>
```

The `<span>` tag
The HTML <span> is an inline element and it can be used to group inline-elements in an HTML document. This tag also does not provide any visual change on the block but has more meaning when it is used with CSS.

The difference between the <span> tag and the <div> tag is that the <span> tag is used with inline elements whereas the <div> tag is used with block-level elements.
  
  ```HTML
<!DOCTYPE html>
<html>

   <head>
      <title>HTML span Tag</title>
   </head>
	
   <body>
      <p>This is <span style = "color:red">red</span> and this is
         <span style = "color:green">green</span></p>
   </body>
	
</html>
```
  ### IFrames
  An IFrame (Inline Frame) is an HTML document embedded inside another HTML document on a website. The IFrame HTML element is often used to insert content from another source, such as an advertisement, into a Web page. Although an IFrame behaves like an inline image, it can be configured with its own scrollbar independent of the surrounding page's scrollbar.
 #### attributes
+ src :

            The src attribute specifies the
        URL of the page to show in the
frame
+ height:

      The height attribute specifies
      the height of the iframe in pixels.
+ width:

           The width attribute specifies
      the width of the iframe in pixels.

+ scrolling:
     
           The scrolling attribute will
      not be supported in HTML5. In
      HTML 4 and XHTML, it indicates
      whether the iframe should
      have scrollbars or not. This is
      important if the page inside the
      iframe is larger than the space
      you have allowed for it (using the
      height and width attributes).
      Scrollbars allow the user to move
      around the frame to see more
      content. It can take one of three
      values: yes (to show scrollbars),
      no (to hide scrollbars) and auto
      (to show them only if needed).

+ frameborder:
    
        The frameborder attribute will
          not be supported in HTML5. In
           HTML 4 and XHTML, it indicates
           whether the frame should have
           a border or not. A value of 0
         indicates that no border should
           be shown. A value of 1 indicates
       that a border should be shown.

+ seamless:

        In HTML5, a new attribute
      called seamless can be applied
      to an iframe where scrollbars
      are not desired. The seamless
      attribute (like some other new
      HTML5 attributes) does not
      need a value, but you will often
      see authors give it a value of
      seamless. Older browsers
      do not support the seamless
      attribute.



### Information About Your Pages

`<meta>`
Metadata is data (information) about data.

`<meta>` tags always go inside the <head> element, and they provide metadata about the HTML document.

`<meta>` tags are typically used to specify character set,  description, 
keywords, author.

Metadata will not be displayed on the page, but is machine parsable.

Metadata is used by browsers (how to display content or reload page), search engines (keywords), and other web services.

 Some defined values for its
*attributes* that are commonly
used are:

**description**
This contains a description
of the page. This description
is commonly used by search
engines to understand what the
page is about and should be a
maximum of 155 characters.
Sometimes it is also displayed in
search engine results.

**keywords**
This contains a list of commaseparated words that a user
might search on to find the page.
In practice, this no longer has
any noticeable effect on how
search engines index your site.


**robots**
This indicates whether search
engines should add this page
to their search results or not. A
value of noindex can be used if
this page should not be added. A
value of nofollow can be used
if search engines should add this
page in their results but not any
pages that it links to.

The `<meta> `element also
uses the http-equiv and
content attributes in pairs.
In our example, you can see
three instances of the httpequiv attribute. Each one has a
different purpose:
**author**
This defines the author of the
web page.
**pragma**
This prevents the browser from
caching the page. (That is,
storing it locally to save time
downloading it on subsequent
visits.)
**expires**
Because browsers often cache
the content of a page, the
expires option can be used
to indicate when the page
should expire (and no longer be
cached). Note that the date must
be specified in the format shown.

### Escape characters

Escape characters are used to include special
characters in your pages such as `<`, `>`, and` ©`



# ch17

# HTML5 layout


## Traditional HTML Layouts

![html layout](https://www.c-sharpcorner.com/UploadFile/b5be7f/working-with-new-semantic-elements-in-html5-along-with-html/Images/Html%20Basic%20Structure%20Image.png)


## New HTML Layouts
![html layout](https://stuyhsdesign.files.wordpress.com/2016/05/yoko-html5.png?w=656)

## Headers & Footers


The `<header> `and`<footer>`
elements can be used for:

* The main header or footer
that appears at the top or
bottom of every page on the
site.

* A header or footer for an
individual `<article>` or
`<section>` within the page
  
 ## Navigation
 The `<nav> `element is used to
contain the major navigational
blocks on the site such as the
primary site navigation.

```HTML
<nav>
<ul>
 <li><a href="" class="current">home</a></li>
 <li><a href="">classes</a></li>
 <li><a href="">catering</a></li>
 <li><a href="">about</a></li>
 <li><a href="">contact</a></li>
</ul>
</nav>
```
 ## Articles
 
 The `<article> `tag specifies independent, self-contained content.

An article should make sense on its own and it should be possible to distribute it independently from the rest of the site.

it acts as
a container for any section of a
page that could stand alone and
potentially be syndicated.

Potential sources for the <`article> `element:

- Forum post
- Blog post
- News story
- Comment


## Asides
The `<aside>` element has two
purposes, depending on whether
it is inside an` <article>`
element or not.
 When the `<aside>` element
is used inside an `<article>`
element, it should contain
information that is related to the
article but not essential to its
overall meaning

# Sections
The` <section> `element groups
related content together, and
typically each section would
have its own heading

The `<section> `tag defines sections in a document, such as chapters, headers, footers, or any other sections of the document.


# Heading Groups

The purpose of the `<hgroup>`
element is to group together a
set of one or more `<h1> `through
`<h6>` elements so that they are
treated as one single heading. 
```html

<hgroup>
<h2>Japanese Vegetarian</h2>
<h3>Five week course in London</h3>
</hgroup>

```
# Figures
Use a `<figure>` element to mark up a photo in a document, and a` <figcaption> `element to define a caption for the photo

```html


<figure>
<img src="images/bok-choi.jpg" alt="Bok Choi" />
<figcaption>Bok Choi</figcaption>
</figure>
```


 note that the
article should still make sense
if the content of the <figure>
element were moved (to another
part of the page, or even to a
different page altogether). 
 

For this reason, it should only be
used when the content simply
references the element (and not
for something that is absolutely
integral to the flow of a page)

Examples of usage include:
* Images
* Videos
* Graphs
* Diagrams
* Code samples
* Text that supports the main body of an article


The `<figure>` element should
also contain a `<figcaption>`
element which provides a text
decription for the content of
the `<figure>` element. In
this example, you can see a
`<figure>` has been added inside
the` <article>` element.


# Sectioning Elements
Where there is no suitable
element to group a set of
elements, the `<div>` element will
still be used. In this example, it is
used as a wrapper for the entire
page.
Some people have asked why
there is no `<content>` element
to contain the main part of
a page. The reason is that
anything that lies outside of the
`<header>`, `<footer>` or` <aside>`
elements can be considered as
the main content.


# Linking Around Block-Level Elements

HTML5 allows web page authors
to place an` <a>` element around
a block level element that
contains child elements. This
allows you to turn an entire block
into a link.

This is not a new element in
HTML5, but it was not seen as a
correct usage of the `<a>` element
in earlier versions of HTML.


# Helping Older Browsers Understand

Older browsers that do not
know the new HTML5 elements
will automatically treat them as
inline elements. Therefore, to
help older browsers, you should
include the line of CSS on the
left which states which new
elements should be rendered as
block-level elements.
Also, IE9 was the first version of
Internet Explorer to allow CSS
rules to be associated with these
new HTML5 layout elements.
In order to style these elements
using earlier versions of IE, you
need to use a simple JavaScript
known as the HTML5 shiv or
HTML5 shim. 





# ch18




# Website Proccess & Design


![img-thinking!](https://cdn5.vectorstock.com/i/1000x1000/75/84/developer-working-with-laptop-and-thinking-vector-22287584.jpg)

1. How to approach building a site
2. Understanding your audience and their needs
3. How to present information visitors want to see

### As a websites developer you shloud have some design thinking skills and some more like
   * Design theory 
   * Design tips      
   * How to organize information 
   * How to understand the audience

when you are almost  to build a website you have to ask **WHAT, WHY,HOW and WHO** many times and everywhere  


# Who is the Site For?
where you have specify the __individuals or Companies Target Audience__ depending on their info



# Why People Visit YOUR Website

These are the triggers making them come to the site no:
+ Key motivations
    - looking for general entertanment
    - looking for a specific goal 
        +  what is it in detail  
    - the value of your website in their opinion

# What Your Visitors are Trying to Achieve
you want to create a list
of reasons **why** people would
be coming to your site.


# What Information Your Visitors Need

 You know who is coming to your site and why
they are coming, so now you need to work out
what information they need in order to achieve
their goals quickly and effectively

*Will they be familiar with the product / service information you are covering or do they need background information on it?* 

*What are the most important features of what you are offering?*


# How Often People Will Visit Your Site
 
This depend on the field your website is about and the updates of its data whatever you are providng GOODS or SERVICES


# Site Maps

![site-map!](https://blog.hubspot.com/hs-fs/hubfs/dyno-mapper-sitemap-generator.png?width=566&name=dyno-mapper-sitemap-generator.png)

# WireFrames

A wireframe is a simple sketch of the key
information that needs to go on each page of a
site. It shows the hierarchy of the information
and how much space it might require

![wireFrame!](https://s3.amazonaws.com/www-inside-design/uploads/2017/11/12-wireframe-examples-from-some-of-our-favorite-UX-designers-feature.jpg)

# Getting your message across using design

The primary aim of any kind of visual design
is to communicate. Organizing and prioritizing
information on a page helps users understand
its importance and what order to read it in.

### CONTENT
Web pages often have a lot of
information to communicate.
For example, the pages of
online newspapers will have
information that does not appear
on every page of the print
equivalent


### Prioritizing

Create something
known as a visual hierarchy
to help users focus on the key
messages that will draw people's
attention, and then guide them
to subsequent messages


### Organizing

Users should be able to
identify the purpose of each
block without processing each
individual item.


*Let's look at an example of how design can be used to effectively communicate the services of a company*

1. visual hierarchy 
    - Attention is immediately drawn
        to a picture that shows the
        service this company offers
        and a headline to explain it. The
        size and colored background
        reinforce that this is the primary
        message on the page
2. Grouping
    - There are several chunks of
       information on this page.
        At the top you can see the logo
        and navigation. Under this is the
        information that introduces the 
        company's services.
        Further down are three distinct     
        groups showing you what the
        services do, the costs involved
        and some of the services' users   

3. Similarity 
    - The four points (at the bottom
        left of the screenshot) are all
        presented in a similar manner
        with consistent headings and
        icons        




# Designing Navigation
Site navigation not only helps people find where they want to go, but also
helps them understand what your site is about and how it is organized.
Good navigation tends to follow these principles.


# Summary

+ It's important to understand who your target audience
is, why they would come to your site, what information
they want to find and when they are likely to return.

+ Site maps allow you to plan the structure of a site.
+ Wireframes allow you to organize the information that
will need to go on each page 
+ Design is about communication. Visual hierarchy helps
visitors understand what you are trying to tell them

+ You can differentiate between pieces of information
using size, color, and style. 
+ You can use grouping and similarity to help simplify
the information you present.
