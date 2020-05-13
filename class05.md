# IMAGES

## Where to Place Images in Your Code

1. before a paragraph

The paragraph starts on a new
line after the image.

2. inside the start of a paragraph

The first row of text aligns with
the bottom of the image.

3. in the middle of a paragraph

The image is placed between the
words of the paragraph that it
appears in.

## Three Rules for Creating Images

1. Save images in
the right format
2. Save images at
the right size
`You should save the image at
the same width and height it will
appear on the website`

3. Use the correct
resolution


## HTML5: Figure and Figure Caption

`<figure>`
Images often come with
captions. HTML5 has introduced
a new <figure> element to
contain images and their caption
so that the two are associated.
You can have more than one
image inside the <figure>
element as long as they all share
the same caption.
  
  
  `<figcaption>`
The <figcaption> element has
been added to HTML5 in order
to allow web page authors to add
a caption to an image.
Before these elements were
created there was no way to
associate an <img> element with
its caption.
  
  
  ```html


<figure>
<img src="images/otters.jpg" alt="Photograph of
 two sea otters floating in water">
<br />
 <figcaption>Sea otters hold hands when they
 sleep so they don't drift away from each
 other.</figcaption>
</figure>
```


# Color 

## Foreground Color

The color property allows you
to specify the color of text inside
an element. You can specify any
color in CSS in one of three ways:

   1. [RGB values](https://www.w3schools.com/colors/colors_rgb.asp)
   2. [HEX CODES](https://www.rapidtables.com/web/color/html-color-codes.html)
   3. [COLOR Names](http://www.colors.commutercreative.com/grid/)
   
### There is also a good color picking tool at:[ colorschemedesigner.com](colorschemedesigner.com)

## HUE
Hue is near to the colloquial idea
of color. Technically speaking
however, a color can also have
saturation and brightness as
well as hue.


## Saturation

Saturation refers to the amount
of gray in a color. At maximum
saturation, there would be no
gray in the color. At minimum
saturation, the color would be
mostly gray.


## Brightness

Brightness (or "value") refers
to how much black is in a color.
At maximum brightness, there
would be no black in the color.
At minimum brightness, the
color would be very dark.

![Saturation!](https://purple11.com/static/fed42130c194b0c240a4ec10408adf97/8282f/hsl-cover-2.png)

## Contrast
+ Text is harder to read when
there is low contrast between
background and foreground
colors.
+ Text is easier to read when
there is higher contrast between
background and foreground
colors.
+ For long spans of text, reducing
the contrast a little bit improves
readability

[![contrast!](https://accessibility.colostate.edu/media/sites/128/2017/09/text-on-page-diff-contrasts-01.png)](https://snook.ca/technical/colour_contrast/colour.html#fg=33FF33,bg=333333)


# CSS3: Opacity
 ### opacity 

CSS3 introduces the opacity
property which allows you to
specify the opacity of an element
and any of its child elements.
The value is a number between
0.0 and 1.0 (so a value of 0.5
is 50% opacity and 0.15 is 15%
opacity).

### rgba

The CSS3 rgba property allows
you to specify a color, just like
you would with an RGB value,
but adds a fourth value to
indicate opacity. This value is
known as an __alpha__ value and is
a number between 0.0 and 1.0
(so a value of 0.5 is 50% opacity
and 0.15 is 15% opacity). The
rgba value will only affect the
element on which it is applied
(not child elements).

### hsl
The hsl color property has
been introduced in CSS3 as an
alternative way to specify colors.
The value of the property starts
with the letters hsl, followed
by individual values inside
parentheses for: *hue, saturation, lightness*

### hsla

The hsla color property allows
you to specify color properties
using hue, saturation, and
lightness as above, and adds a
fourth value which represents
transparency (just like the rgba
property). The a stands for: __Alpha__

# Text

## Typeface Terminology
fonts:
Serif,Sans-Serif,Monospace


featurees:

Weight  |   Style   |  Stretch
------  |--------- | --------
Light  |   Normal   |  Condensed
Medium  |   Italic   |  Regular
Bold  |   Oblique   |  Extended
Black  |      |  


# Choosing a Typeface for your Website

When choosing
a typeface, it
is important to
understand that a
browser will usually
only display it if it's
installed on that
user's computer.

**Serif**
Serif fonts have extra details on
the end of the main strokes of
the letters.


**Sans-Serif**
Sans-serif fonts have straight
ends to letters and therefore
have a much cleaner design.


## Units of Type Size

Pixels, Percentages and Ems


## More Font Choice
`@font-face`

 this technique allows
a version of the font to be
downloaded to the user's
computer