# Lists


## Ordered Lists

## `<ol>`  
The Ordered Lists contains list of items each item in the list is placed
between an opening `<li>` tag
and a closing `</li>` tag. 

```html

<!--Browsers indent lists by default.-->
<ol>
  
<li>item1</li>
<li>item2</li>
<li>item3</li>
<li>item4</li>

</ol>


```




## Unordered Lists


## `<ul>`  
The unordered Lists contains list of items each item in the list is placed
between an opening `<li>` tag
and a closing `</li>` tag. 

```html

<!--Browsers indent lists by default.-->
<ul>
  
<li>item1</li>
<li>item2</li>
<li>item3</li>
<li>item4</li>

</ul>


```




## Definition Lists

## `<dl>`  
The definition list is created with
the `<dl>` element and usually
consists of a series of terms and
their definitions.

Inside the `<dl>` element you will
usually see pairs of `<dt>` and
`<dd>` elements.

## `<dt>`
This is used to contain the **term
being defined** (the *definition
term*).



## `<dd>`
This is used to contain the
**definition**.



```html

<!--Browsers indent lists by default.-->
<dl>
  <dt>Coffee</dt>
  <dd>Black hot drink</dd>
  <dt>Milk</dt>
  <dd>White cold drink</dd>
</dl>


```


## Nested Lists

You can put a second list inside
an `<li>` element to create a sublist or nested list.
```html

<ul>
  <li>Coffee</li>
  <li>Tea
    <ul>
      <li>Black tea</li>
      <li>Green tea</li>
    </ul>
  </li>
  <li>Milk</li>
</ul>



```


<!-- CSS    VIP CHAPTER -->

# Boxes

## Box Dimensions

You can use `width` and `height` properties to set your own dimentions.

The most popular ways to
specify the size of a box are
to use __pixels, percentages, or
ems__. Traditionally, *__pixels__* have
been the most popular method
because they allow designers to
accurately control their size.

When you use **percentages**,
the size of the *box* is relative to
the size of the *browser window*
or, *if the box is encased within
another box, it is a percentage of
the size of the containing box*.


When you use **ems**, the size
of the *box* is based on the size
of *text within it*.

Designers
have recently started to use
percentages and ems more for
measurements as they try to
create designs that are flexible
across devices which have
different-sized screens.



## Limiting Width

### `min-width`, `max-width`
The `max-width` property defines the maximum width of an element.

If the content is **larger** than the *maximum width*, it will automatically change the *height* of the element.

If the content is **smaller** than the *maximum width*, the max-width property has *no effect*.


These are very helpful properties
to ensure that the content of
pages are legible (especially on
the smaller screens of handheld
devices).




## Limiting Height


### `min-height`, `max-height`

The `max-height` property defines the maximum height of an element.

If the content is **larger** than the *maximum height*, it will  *__overflow.__*  How the container will handle the overflowing content is defined by the [overflow ](https://www.w3schools.com/cssref/pr_pos_overflow.asp)property.

If the content is **smaller** than the *maximum height*, the `max-height` property has **no effect**.



## Overflowing Content



### `overflow`

The [overflow](https://www.w3schools.com/cssref/pr_pos_overflow.asp) property tells the
browser what to do if the content
contained within a box is larger
than the box itself. It can have
one of two values:

   + hidden      
    
            This property simply hides any
           extra content that does not fit in
           the box.
           
  + scroll      
    
           This property adds a scrollbar to
            the box so that users can scroll
            to see the missing content.

*we will discover more values later*

## Border, Margin & Padding

Every box has three available properties that
can be adjusted to control its appearance:
1. BORDER

        The border
         separates the edge of one box
          from another.
          in other word
        Is the OUTSIDE line that cover the box

2. MARGIN

        Margins sit outside the edge
        of the border.
        So, it is the OUTSIDE gap around the BORDER
        
3. PADDING

        Padding is the space between
        the border of a box and any
          content contained within it. 
          
          
          
# **I WANNA ASK ABOUT THIS**          
`If you specify a width
for a box, then the
borders, margin, and
padding are added to
its width and height.`

![](https://espezua.github.io/blog/imgs/boxmodel.png)




# White space & Vertical Margin

The padding and
margin properties
are very helpful
in adding space
between various
items on the page.

*So, you can control the spaces between boxes or ither items*



# Border Width

The border-width property
is used to control the width
of a border. The value of this
property can either be given
in __`pixel`s__ or using one of the
following values: __`thin, medium or thick`__

*(You cannot use percentages
with this property.)*

You can  specify different
widths for the *four border values*
in one property, like so:
```css
x{
border-width: 2px 1px 1px
2px;
}
/*
border-width: top right bottom left;
*/
```
# Border Style

## `border-style`
You can control the style of a
border using the border-style
property. with the following values:

- `solid`
- `dotted`
- `dashed`
- `double`
-` groove`
- `ridge`
- `inset`
- `outset`
- `hidden or none`
![](https://flaviocopes.com/css-border/Screen%20Shot%202019-04-07%20at%2016.43.10.png)
You can individually change the
styles of different borders using:
1. `border-top-style`
2.`border-left-style`
3. `border-right-style`
4. `border-bottom-style`


# Border Color

## `border-color`
You can specify the color of a
border using either*RGB values,
hex codes or CSS color names* 

It is  possible to use a
shorthand to control all four
border colors in the one
property:
```css
x{
border-color: darkcyan deeppink darkcyan deeppink;

/*
border-color: top right bottom left;


*/
}
```

![](https://www.formget.com/wp-content/uploads/2014/09/border-color-example.png)



# Shorthand 

## `border`
The border property allows you
to specify the width, style and
color of a border in one property
(and the values should be coded
in that specific order).

```css
p {
width: 250px;
border: 3px dotted #0088dd;

}
```

# Padding

## `padding`

The padding property allows
you to specify how much space
should appear between the
content of an element and its
border

```css
padding: 10px 5px 3px 1px;
```


# MARGIN

## `margin`

The margin property controls
the gap between boxes. Its value
is commonly given in pixels,
although you may also use
percentages or ems

```css
margin: 1px 2px 3px 4px;```
```




# Centering Content


```CSS

p.example {
margin: 10px auto 10px auto;
text-align: left;
}
```

When you set the left-margin and
right-margin to auto the box going to be in the center of the page the any container element  (otherwise it will takeup the full width of the page)..



# IE6 Box Model
# *page 316 Get back to understand then ask *


# Change Inline/Block
## `display`
the vakues of this property are:

* inline
    
        This causes a block-level
        element to act like an inline
        element.
* block
    
        This causes an inline element to
        act like a block-level element.   
        
* inline-block
    
        This causes a block-level
        element to flow like an inline
        element, while retaining other
        features of a block-level element.
        
        
* none
         
         It hides the element
        the user could
        only see the content of the box if
        they used the view source option
        in their browser    
        
    
   If you use this property, it is
important to note that inline
boxes are **not** supposed to create
block-level elements 



# Hiding Boxes

## `visibility`

This property can take two values:
`hidden`
This hides the element.
`visible`
This shows the element 



# CSS3: Border Images


## `border-image`

The CSS `border-image` property allows you to specify an image to be used instead of the normal border around an element.

The property has three parts:

1. The image to use as the border( URL )
2. Where to slice the image
3. What to do with the straight edges




```css

#borderimg {
  border: 10px solid transparent;
  padding: 15px;
  border-image: url(border.png) 30 round;
}
/*
the possible values of the edges are:
 stretch, repeat or round 
*/

```

# CSS3: Box Shadows

The box-shadow property
allows you to add a drop shadow
around a box. It must
use at least the first of these two
values as well as a color:

`Horizontal offset`
Negative values position the
shadow to the left of the box.

`Vertical offset`
Negative values position the
shadow to the top of the box.


`Blur distance`
If omitted, the shadow is a solid
line like a border.

`Spread of shadow`
If used, a positive value will
cause the shadow to expand in
all directions, and a negative
value will make it contract.

```css
p.one {
-moz-box-shadow: -5px -5px #777777;
-webkit-box-shadow: -5px -5px #777777;
box-shadow: -5px -5px #777777;}
p.two {
-moz-box-shadow: 5px 5px 5px #777777;
-webkit-box-shadow: 5px 5px 5px #777777;
box-shadow: 5px 5px 5px #777777;} 
```


# CSS3: Rounded Corners

## `border-radius`

With the CSS `border-radius` property, you can give any element "rounded corners".


You can use a shorthand
of these four properties

For example:
```css
border-radius: 5px, 10px,
5px, 10px;
/* 
border-radius: topRight, bottomRight,
bottomLeft, topLeft;
*/

```


# CSS3: Elliptical Shapes

## `border-radius`

To create more complex shapes,
you can specify different
distances for the horizontal and
the vertical parts of the rounded
corners.

You can target just one corner
using the individual properties
for that corner:

```css
border-top-left-radius:
80px 50px;

```
<!-- JS -->

# Comoarrison Operators: *Evaluating Conditions*


## It is going to be LOGIC (T/F) so, Focus

- Is Equal : `==`
    + which compares the VALUE.
- Is NOT Equal:` !=`
- Strict Equal To: `===`
    + which compares the VALUE and DATA TYPE.
- Strict NOT Equal To: `!==`
- Greater Than:` >`
- Less Than:` <`
- Greater than or Equal: `>=`
- Less than or Equal:`<=`


# Logical Operators

- Logical AND: `&&` *where both sides of the condition must be True then,the result is True*
- Logical OR: `||` *where both sides of the condition must be False then,the result is False*
- Logical NOT: `!` *This operator takes a single boolean value and inverts it*



# LOOP



Loops are handy, if you want to run the same code over and over again, each time with a different value.
*we have three Loop types, each on with a diffrent structure and  PURPOSE.*

## For loop
A for loop enables a particular set of conditions to be executed repeatedly until a condition is satisfied. Imagine a situation where you would have to print numbers from 1 to 100. What would you do? Will you type in the printf command a hundred times or try to copy/paste it? This simple task would take an eternity. Using a for loop you can perform this action in three statements. This is the most basic example of the for loop. It can also be used in many advanced scenarios depending on the problem statement.
![forLoop!](https://media.geeksforgeeks.org/wp-content/uploads/20191108131134/For-Loop.jpg)

Note:  you should use a for loop when you know how many times the loop should run

## While loop
A while loop is one of the most common types of loop. The main characteristic of a while loop is that it will repeat a set of instructions based on a condition. As far as the loop returns a boolean value of TRUE, the code inside it will keep repeating. We use this kind of loop when we don't know the exact number of times a code needs to be executed.

![whileloop!](https://media.geeksforgeeks.org/wp-content/uploads/20191118164726/While-Loop-GeeksforGeeks.jpg)

Note: While loop is used in situations where we do not know how many times loop needs to be excuted beforehand.


## Do While loop
If you recall the way the for and while loops work, you will remember that these loop types check for the loop condition at the beginning of the loop. Unless the condition is satisfied the loop will not be executed.
The do while loop checks the condition at the end of the loop. This means that the statements inside the loop body will be executed at least once even if the condition is never true.
![doWhileLoop1](https://media.geeksforgeeks.org/wp-content/uploads/20191118154342/do-while-Loop-GeeksforGeeks2.jpg)

Note: A while loop is normally used in a scenario where you don't know how many times a loop will actually execute at runtime. A do-while loop is used where your loop should execute at least one time

### while loop example 

```javascript
let count = 1;
while (count < 10) {
    console.log(count);
    count +=2;
}
```

