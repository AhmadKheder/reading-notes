# Forms

- The `<form>` Element
- The `<input> `Element
- The `<label>` Element



### Text Fields
`<input type="text"> `defines a single-line input field for text input.


```html

<form>
  <label for="fname">First name:</label><br>
  <input type="text" id="fname" name="fname"><br>
  <label for="lname">Last name:</label><br>
  <input type="text" id="lname" name="lname">
</form>
```

### The Submit Button

`<input type="submit"> `defines a button for submitting the form data to a form-handler.

```html

<form action="/action_page.php">
  <label for="fname">First name:</label><br>
  <input type="text" id="fname" name="fname" value="John"><br>
  <label for="lname">Last name:</label><br>
  <input type="text" id="lname" name="lname" value="Doe"><br><br>
  <input type="submit" value="Submit">
</form> 



```



## HTML Lists

**An unordered HTML list:**

+ Item
+ Item
+ Item
+ Item

**An onordered HTML list:**

1. Item
1. Item
1. Item
1. Item



```html

<ol>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ol>

```




## Table
Defining an HTML Table
An HTML table is defined with the `<table> `tag.

Each table row is defined with the `<tr>` tag. A table header is defined with the `<th>` tag. By default, table headings are bold and centered. A table data/cell is defined with the `<td> `tag.


```html
<table style="width:100%">
  <tr>
    <th>Firstname</th>
    <th>Lastname</th>
    <th>Age</th>
  </tr>
  <tr>
    <td>Jill</td>
    <td>Smith</td>
    <td>50</td>
  </tr>
  <tr>
    <td>Eve</td>
    <td>Jackson</td>
    <td>94</td>
  </tr>
</table>
```
