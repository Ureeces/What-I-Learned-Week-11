# What I Learned Week 11

## Methods

Objects are capable of holding functions as elements. These are known as methods. This has a wide variety of uses, some of which are:
* Object Templates
* Data organization
* Calculations
* Object Manipulation

... and more.

#### On a side note: Arrays

Arrays are pretty much pre-made objects that use indexes as keys for each value. 

## .Filter

Arrays in Javascript can be filtered out using the .filter method:
* `array.filter()` - This will create a new array, and will only push the elements from the master array that match the criteria of the function/condition specified.

You can call functions created outside of the arguments, but you may also create the function within the arguments:
`array.filter(premadeFunction(element));`

`array.filter(function(params) {//do stuff});`

## .Map

Arrays in Javascript can also be manipulated without mutating the original array: 
* `array.map()` - This will create a new array, and cycle through the each element in the master array, applying changes/searches for each element.
  
Like the filter method, you can call functions created outside of the arguments, but you may also create the function within the arguments:

`array.map(premadeFunction(element));`

`array.map(function(params) {//do stuff});`