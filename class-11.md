# Images

Images can improve the design and the appearance of a web page.


### Image HTML code
```html

<img src="images/magnolia-large.jpg"
 class="large" alt="Magnolia" /> 
```
### Controlling size of Image  in CSS

```css
img.large {
width: 500px;
height: 500px;} 

```

### AligNing images Using CSS

```html

<p><img src="images/magnolia-medium.jpg"
 alt="Magnolia" class="align-left medium" />
 <b><i>Magnolia</i></b> is a large genus that
 contains over 200 flowering plant species...</p>
```



```css
img.align-left {
float: left;
margin-right: 10px;}


```
### Centering images Using CSS
```html
<img src="images/magnolia-medium.jpg"
 alt="Magnolia" class="align-center medium" />
```


```css
img.align-center {
display: block;
margin: 0px auto;}
img.medium {
width: 250px;
height: 250px;}

```


### Background Images

### `background-image`
The background-image
property allows you to place
an image behind any HTML
element. This could be the entire
page or just part of the page. By
default, a background image will
repeat to fill the entire box.
```css
body {
background-image: url("images/pattern.gif");
}
```


### Repeating Images

#### `background-repeat` ,`background-attachment`
The background-repeat
property can have four values:

1. **repeat**
      
        The background image is
        repeated both horizontally and
         vertically 
          
2. **repeat-x :** The image is repeated horizontally only
3. **repeat-y :** The image is repeated vertically only
4. **no-repeat :** The image is only shown once.
```css
body {
background-image: url("images/header.gif");
background-repeat: repeat-x;}
```


The `background-attachment`
property specifies whether a
background image should stay in
one position or move as the user
scrolls up and down the page. It
can have one of two values:

1. **fixed** The background image stays in the same position on the page .

2. **scroll** The background image moves up and down as the user scrolls up and down the page.

```css
body {
background-image: url("images/tulip.gif");
background-repeat: no-repeat;
background-attachment: fixed;}
```

### Background Position
 ### `background-position `
 This property usually has a pair
of values. The first represents
the __horizontal__ position and the
second represents the __vertical__.
 **If you only specify one value,
the second value will default to
center.**

`left top`
 `left center`
 `left bottom`
 `center top`
 `center center`
 `center bottom`
` right top`
` right center`
` right bottom`
You can also use a pair of pixels 
 ` 0% 0%` : equall to `top left`
 ` 50% 50%` : center
 
 
 ### shorthand
` background`

1. `background-color`
2. `background-image`
3. `background-repeat`
4.` background-attachment`
5.` background-position`



### Image Rollovers & Sprites
Using CSS, it is possible to create
a link or button that changes to a
second style when a user moves
their mouse over it (known as a
rollover) and a third style when
they click on it. 


```html
<a class="button" id="add-to-basket">
Add to basket</a>
```

```css
a.button {
height: 36px;
background-image: url("images/button-sprite.jpg");
text-indent: -9999px;
display: inline-block;}
a#add-to-basket {
width: 174px;
background-position: 0px 0px;}
a#add-to-basket:hover {
background-position: 0px -40px;}

a#add-to-basket:active {
background-position: 0px -80px;}
```
Rollovers are basically involve changing one thing to another 
thing when the cursor hovers over it.
f you use an image for a link, for example, you could swap that image with another one when it is hovered over. Here are some methods for achieving this goal, including some CSS3 effects that have expanded the possibilities of modern rollovers..


## Image swapping

The earliest rollovers used JavaScript to swap one img element with another. Then CSS came along and, using :hover, we could more easily change a background image used in place of a text link. Cleaner, simpler, more semantic, and nice and accessible.


An obvious solution for achieving this would be to do something like this:
```css
a {
    display: block;
    width: 200px;
    height: 63px;
    background-image: url(images/toucanfade.jpg);
    text-indent: -999em;
}

a:hover {
    background-image: url(images/toucan.jpg);
}
```


## Image Sprites
An image sprite is a collection of images put into a single image.

A web page with many images can take a long time to load and generates multiple server requests.

Using image sprites will reduce the number of server requests and save bandwidth.


### CSS3: Gradients
### `background-image`

CSS gradients let you display smooth transitions between two or more specified colors.

#### CSS Linear Gradients
To create a linear gradient you must define *at least two color stops*. 
**Color stops:** are the colors you want to render smooth transitions among.
You can also set a starting point and a direction (or an angle) along with the gradient effect.

##### Syntax:
`background-image: linear-gradient(direction, color-stop1, color-stop2, ...);`

```css
#grad {
  background-image: linear-gradient(red, yellow);
}

```

```css
#grad {
  background-image: linear-gradient(to right, red , yellow);
}

```
```css
#grad {
  background-image: linear-gradient(to bottom right, red, yellow);
}

```

 
### Contrast of background images

If you want to overlay text on a background image, the image must be low
contrast in order for the text to be legible

+ High Contrast 
+ Low Contrast 
+ Screen


# Practical Information

## Search Engine Optimization (SEO)

[SEARCH ENGINE OPTIMIZATION
26 SEO statistics for 2020 and what you can learn from them](https://www.impactbnd.com/blog/seo-statistics)
SEO is a huge topic and several books have been written on the subject.
The following pages will help you understand the key concepts so you can
improve your website's visibility on search engines.

#### On-Page SEO
![](https://ultimateseo.org/wp-content/uploads/seo-questions-on-page-730x458.png)


1. Page Title
The page title appears at the top
of the browser window or on the
tab of a browser. It is specified in
the `<title>` element which lives
inside the `<head>` element.

2. URL / Web Address
The name of the file is part of
the URL. Where possible, use
keywords in the file name

3. Headings
If the keywords are in a heading
`<hn> `element then a search
engine will know that this page is
all about that subject and give it
greater weight than other text.

4. Text
Where possible, it helps to
repeat the keywords in the main
body of the text at least 2-3
times. Do not, however, over-use
these terms, because the text
must be easy for a human to
read.

5. Link Text
Use keywords in the text that
create links between pages
(rather than using generic
expressions such as "click here").

6. Image Alt Text
Search engines rely on you
providing accurate descriptions
of images in the alt text. This
will also help your images show
up in the results of image-based
searches.

7. Page Descriptions
The description also lives inside
the `<head>`element and is
specified using a `<meta>` tag.
It should be a sentence that
describes the content of the
page. (These are not shown in
the browser window but they
may be displayed in the results
pages of search engines.)

`Never try to fool search engines!
They will penalize you for it. For
example, never add text in the
same color as the background of
the page as they can detect this.`


### How to Identify Keywords and Phrases

Determining which keywords to use on your site can be one of the
hardest tasks when you start to think about SEO. Here are six steps that
will help you identify the right keywords and phrases for your site.

1. Brainstorm
List down the words that
someone might type into
Google to find your site. Be sure
to include the various topics,
products or services your site is
about.


2. Organize
Group the keywords into
separate lists for the different
sections or categories of your
website

3. Research
There are several tools that let
you enter your keywords and
then they will suggest additional
keywords you might like to
consider.

4. Compare
It is very unlikely that your
site will appear at the top of
the search results for every
keyword. This is especially true
for topics where there is a lot
of competition. The more sites
out there that have already been
optimized for a given keyword,
the harder it will be for you to
rise up the search results whe


5. Refine
Now you need to pick which
keywords you will focus on.
These should always be the ones
that are most relevant to each
section of your site


6. Map
Now that you have a refined list
of keywords, you know which
have the most competition, and
which ones are most relevant,
it is time to start picking which
keywords you will use for each
page



### Analytics: Learning about your Visitors

As soon as people start coming to your site, you can start analyzing
how they found it, what they were looking at and at what point they are
leaving. One of the best tools for doing this is a free service offered by Google called Google Analytics.

### How Many People Are Coming to Your Site?

The overview page gives you a snapshot of the key information you are
likely to want to know. In particular, it tells you how many people are
coming to your site.



### What Are Your Visitors Looking At?

*Pages*
This tells you which pages your
visitors are looking at the most
and also which pages they are
spending the most time on.

*Landing Pages* 
These are the pages that people
arrive on when first visiting your
site. This can be particularly
helpful because you may find
people are not always coming
into your site via the homepage.

*Top Exit Pages*
This shows which pages people
most commonly leave from. If
a lot of people are leaving from
the same page then you might
consider changing that page or
improving it.

### Where Are Your Visitors Coming From?
The traffic sources link on the left hand side
allows you to learn where your visitors are
coming from.


### Domain Names & Hosting

**Domain name** is the address of your website that people type in the browser’s URL bar to visit your website.
In other words, if your website was a house, then your domain name will be its address.
Now let’s get into the detailed explanation.

Internet is basically a giant network of computers connected to each other through cables. To easily identify them, each computer is assigned a series of numbers called IP Address.

This IP address is a combination of numbers separated with dots. Typically, IP addresses look like this:

66.249.66.1

Computers have no problem identifying and remembering these numbers. However, it is impossible for humans to remember and use these numbers to connect to websites on the internet.

To solve this problem, domain names were invented.

A domain name can have words which makes it easy to remember website addresses.



**Web hosting** is the place where all the files of your website live. It is like the home of your website where it actually lives.

A good way to think about this is if the domain name was the address of your house, then web hosting is the actual house that address points to. All websites on the internet, need web hosting.

When someone enters your domain name in a browser, the domain name is translated into the IP address of your web hosting company’s computer. This computer contains your website’s files, and it sends those files back to the users’ browsers.

Web hosting companies specialize in storing and serving websites. They offer different types of hosting plans to their customers. See our article on WordPress hosting to learn more about choosing the right hosting for your website.


### FTP & Third Party Tools
To transfer your code and images from your
computer to your hosting company, you use
something known as File Transfer Protocol.
As the name suggests, File
Transfer Protocol (or FTP) allows
you to transfer files across the
Internet from your computer to
the web server hosting your site.
There are many FTP programs
that offer a simple interface
that shows you the files on your
computer alongside the files that
are on your web server. These
allow you to drag and drop
files from your computer to the
server or vice versa.



