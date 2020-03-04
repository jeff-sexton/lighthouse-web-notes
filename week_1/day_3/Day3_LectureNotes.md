# Day 3 Lecture Notes

## Objects

### Primitive Data Types

* undefined
* null
* boolean
* string
* number
* symbol

### Objects and Fundamentals

#### Looping through objects

Three ways:

* For In
  
  ``` javascript
  let dogs = {};
  for (dog in dogs) {

  }
  ```
* For of
  * .entries
  


  * keys
  

  #### Keyword This
  * obj.function() --- this refers to obj
  * Warning: arrow functions => do not treat the this keyword the same as function()




### Memory

* Primitive types are stored directly in variables
  * overwriting a primitive with another primitave does not link them
* reference types are stored elsewhere in memory and the variable stores a pointer to this memory space
  * overwriting a reference type makes them both point to the same memory object.
  * changing the object with either variable will effect them both

* Note: all functions pass a copy of the parameter - either the actual primitave or the memory reference to an object.
  * Acting on the object in the function will change the referenced object in memory but overwritting the pointer reference will not effect the referenced object