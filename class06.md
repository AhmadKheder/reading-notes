# Creating Object


```javascript
var hotel = {
    name: 'Quay',
    rooms: '40',
    booked: 25,
    checkAvailability: function(){
        return this.rooms - this.booked;
        }
};

```
# Accessing Object with DOT notation & sqaure barackets
*Dot is called period OR member operator*

the property on the right of the member operator is the member of the  object

```javascript
var hotelName = hotel.name;// assign the string name Quay

var roomsFree = hotel.checkAvailability();//assign 15

```

you can access the propertes of an object by sqaure brackets but *NOT its METHODS*



```javascript
var hotelName = hotel['name'];// assign the string name Quay
```

Update data on website from the object

```javascript
var el Name = document .getElementByld('hotelName');
elName.textContent =hotel .name;
var elRooms = document.getElementByid{'rooms');
elRooms.textContent = hotel .checkAvailability();

```

# DOM

The Document Object Model (DOM) specifies how browsers should create a model of an HTML page and how JavaScript can access and update the contents of a web page while it is in the browser window. 

Each node is an object with methods and properties. Scripts access and update this DOM tree (not the source HTML file). Any changes made to the DOM tree are reflected in the browser. 

Accessing and updating the DOM tree involves two steps: 
- Locate the node that represents the element you want to work with. 
- Use its text content, child elements, and attributes. 
STEP 

The terms elements and element nodes are used interchangeably but when people say the DOM is working with an element, it is actually working with a node that represents that element 

DOM queries may return one element, or they may return a Nodelist, which is a collection of node

There are two ways to select an element from a Nodelist: The item() method and array syntax. Both require the index number of the element you want. 

