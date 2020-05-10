# CH2


 Tag                 | Disc
-----------           |--------------
`<h1>`to`<h6>`        | Headings
`<p>`                 | Paragraphs
`<b>`               | Bold
`<i>`               | Italic
`<sup>`                 |Superscript
`<sub>`                    | Subscript
`<br />`           | Line Break
`<hr />`                | Horizontal Rules
`<strong>`                |Strong
`<em>`              | Emphasis
`<blockquote>`              | Quotation
`<q>`               | Quotation
`<abbr>`               | Abbreviations
`<cite>`              | Citations
`<dfn>`               | Definitions
`<address>`               | Author Details
`<ins>`               | show inserted content
`<del>`               |  show deleted text
`<s>`               | no longer accurate text 

### Superscript & Subscript
#### `<sup>`

The` <sup>` element is used
to contain characters that
should be superscript such
as the suffixes of dates or
mathematical concepts like
raising a number to a power such
as 22

#### `<sub>`

The `<sub>` element is used to
contain characters that should
be subscript. It is commonly
used with foot notes or chemical
formulas such as H20.

### White Space

When the browser comes across
two or more spaces next to each
other, it only displays one space.
Similarly if it comes across a line
break, it treats that as a single
space too. This is known as **white space collapsing**.

### Strong

#### `<strong>`
The use of the` <strong>`
element indicates that its
content has strong importance.

### Emphasis

#### `<em>`
The` <em>` element indicates
emphasis that subtly changes
the meaning of a sentence

### Quotations

#### `<blockquote>`

The `<blockquote>` element is
used for longer quotes that take
up an entire paragraph. Note
how the` <p> `element is still
used inside the` <blockquote>`
element. 

#### `<q>`

The` <q>` element is used for
shorter quotes that sit within
a paragraph. Browsers are
supposed to put quotes around
the `<q>` element, however
Internet Explorer does not —
therefore many people avoid
using the `<q>` element.


```html
<blockquote cite="http://en.wikipedia.org/wiki/
Winnie-the-Pooh">
 <p>Did you ever stop to think, and forget to start
 again?</p>
</blockquote>
<p>As A.A. Milne said, <q>Some people talk to
 animals. Not many listen though. That's the
 problem.</q></p>

```
### Abbreviations & Acronyms

#### `<abbr>` `<acronym> `
If you use an abbreviation or
an acronym, then the `<abbr>`
element can be used. A title
attribute on the opening tag is
used to specify the full term.

```html

<p><abbr title="Professor">Prof</abbr> Stephen
 Hawking is a theoretical physicist and
 cosmologist.</p>
<p><acronym title="National Aeronautics and Space
 Administration">NASA</acronym> do some crazy
 space stuff.</p>
```

### Citations & Definitions
#### `<cite>`
The`<cite>` element can be used
to indicate where the citation is
from.

```html
<p><cite>A Brief History of Time</cite> by Stephen
 Hawking has sold over ten million copies
 worldwide.</p>
```


#### `<dfn>`
The` <dfn>` element is used to
indicate the defining instance of
a new term
```html
<p>A <dfn>black hole</dfn> is a region of space from
 which nothing, not even light, can escape.</p>
```

### Author Details
#### `<address>` 

The ` <address>` element has
quite a specific use: to contain
contact details for the author of
the page
 
```html
<address>
<p><a href="mailto:homer@example.org">
 homer@example.org</a></p>
<p>742 Evergreen Terrace, Springfield.</p>
</address>
```

[what is hCard?](http://www.htmlandcssbook.com/extras/introduction-to-hcard/)




### Ch10

# CSS Associates Style rules with HTML elements

CSS works by associating rules with HTML elements. These rules govern
how the content of specified elements should be displayed. A CSS rule
contains two parts: a selector and a declaration.


# CSS Properties Affect How Elements Are Displayed

CSS declarations sit inside curly brackets and each is made up of two
parts: a property and a value, separated by a colon. You can specify
several properties in one declaration, each separated by a semi-colon

![](https://3wga6448744j404mpt11pbx4-wpengine.netdna-ssl.com/wp-content/uploads/2012/10/css-rule.jpg)

# Using External CSS
```html
<head>
 <title>Using External CSS</title>
 <link href="cssFolder/styleFile.css" type="text/css"
 rel="stylesheet" />
</head>
```


# Using Internal CSS

```html
<head>
 <title>Using Internal CSS</title>
 <style type="text/css">
 body {
 font-family: arial;
 background-color: rgb(185,179,175);}
 h1 {
 color: rgb(255,255,255);}
 </style>
</head>
```



# CSS Selectors


 Selectors                 | Disc
-----------           |--------------
Universal Selector    |* {}  Targets all elements on the page
Type Selector                | h1, h2, h3 {} Targets the `<h1>`, `<h2>` and `<h3>`elements
Class Selector       |p.note {}Targets only `<p>` elements whose class attribute has avalue of note
ID Selector               | #introduction {}Targets the element whose id attribute has a value of introduction
Child Selector       |li>a {}Targets any`<a>` elements that are children of an `<li>`element(but not other `<a> `elements in the page)
Descendant Selector                    | p a {}Targets any `<a>` elements that sit inside a `<p>` element, even if there are other elements nested between them
Adjacent Sibling Selector           | h1+p {} Targets the first `<p>` element after any`<h1>` element (but not other `<p>` elements)
General Sibling Selector                | h1~p {}If you had two `<p>` elements that are siblings of an `<h1> `element, this rule would apply to both




<!-- JAVASCRIPT -->

# BASIC JAVASCRIPT INSTRUCTIONS


#### STATEMENTS

STATEMENTS ARE INSTRUCTIONS AND EACH ONE STARTS ON A NEW LINE 


STATEMENTS CAN BE ORGANIZED INTO __CODE BLOCKS__ `statment{ statment}`



#### COMMENTS 
##### Two types of comment:
- MULTI-LINE COMM ENTS 
- SINGLE-LINE COMMENTS 


```javascript
/* Th i s script displays a greeting to the user based upon the current time.
It is an example from JavaScript & jQuer y book */
var today= new Date();
var hour Now = today.getHours();
var greeting;
// Create a ne1~ dat e object
II Fi nd the current hour
JI Display the appropriate greeti ng based on the current time
if (hourNow > 18) {
greet ing = 'Good evening ' ;
else if (hourNow > 12) {
greeting = 'Good afternoon';
else if (hourNow > 0) {
greeting= ' Good morning';
else {
gr eeting = 'Welcome';
}
document.write(greeting) ; 
```


# Declaring & Assigning Values to Variables 

![](https://tutorial.techaltum.com/images/js-variables.jpg)

# three data types 

+ **boolean**
+ (string , char) called **string** in JS
+ (int , double, float) called **number** in JS
+ **Array**

# Arrays

An array is a special type of variable. It doesn't
just store one value; it stores a list of values. 


### CREATING AN ARRAY 


```javascript

var colors1;
colors ['white', 'black', ' custom']; 

var colors2 = new Array('white ' ,
                          'black',
                        '  custom'); 
// both are correct
```


__It is important to know that the
numbering of this list starts at*zero (not one)* __


## ACCESSING & CHANGING VALUES IN AN ARRAY

```javascript

// Create the array
var colors = ['white',
'black' ,
'custom'];

// Update the third item in the array
colors[2] = 'beige ' ;
// Get the element with an id of col ors
var el = document .getElementByid(' colors') ;
// Replace with third item from the array
el .textContent = colors[2]; 

```

# JAVASCRIPT OPERATORS 



![](https://lh3.googleusercontent.com/proxy/lyyQf2nQjhyg9JJ6mIBfZnr8d4hH7AL8NcCMi4EsIYy2i2Y-QfUh7eJFRAMZ_brN82JelzakiLGCNYU4Amd0OUy2Ff0xu038NZJxjfmK)





#### CH4

# DECISIONS & LOOPS

## Desicion Making


Very often while writing code, there is a need for performing different actions for different decisions. Conditional statements are used to meet those needs. Javascript offers the following conditional statements
if condition to decide to execute a block of code when the specified condition is true.
else condition to decide to execute a block of code when the condition specified in if is false.
else if  to specify a new condition to execute a new block when the first condition is false
switch to jump between many alternative blocks of code based on the requirement
 
 ![](https://www.bookofnetwork.com/images/javascript-images/JS_condition-img_24Feb17_1749.png)
 
 
 # Evaluating conditions & Condetional statements
 
Conditional statements are used to return different actions/performances based on given condition.E.x: you made a cup of coffee if it tastes good to drink the coffee or tastes weird throw it. That's all that a conditional Statement in Js doing things based on particular condition.

![](https://image.slidesharecdn.com/004typesstatements-190503052744/95/javascript-chapter-4-types-and-statements-61-638.jpg?cb=1556862808)


# Operators

![](https://lh3.googleusercontent.com/proxy/lyyQf2nQjhyg9JJ6mIBfZnr8d4hH7AL8NcCMi4EsIYy2i2Y-QfUh7eJFRAMZ_brN82JelzakiLGCNYU4Amd0OUy2Ff0xu038NZJxjfmK)


# Using Expressions with comparison operators

Use this article as a reference sheet for JavaScript comparison and logical operators.

Comparison operators — operators that compare values and return true or false. The operators include: `>`,` <`, `>=`, `<=`, `===`, and `!==`.
Logical operators — operators that combine multiple boolean expressions or values and provide a single boolean output. The operators include: `&&`, `||`, and` !`.


```javascript

var isTrue = ('yellow' === 'green') && (4 >= 4);
```



# Conditional Statements
Very often when you write code, you want to perform different actions for different decisions.

You can use conditional statements in your code to do this.

In JavaScript we have the following conditional statements:

+ Use `if` to specify a block of code to be executed, if a specified condition is true
+ Use `else` to specify a block of code to be executed, if the same condition is false
+ Use `else if` to specify a new condition to test, if the first condition is false


```javascript

if (hour < 18) {
  greeting = "Good day";
} else {
  greeting = "Good evening";
}
```