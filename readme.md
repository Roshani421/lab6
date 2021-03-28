# Lab 6


## Classes and Objects

A class is a template for objects, and an object is an instance of class. A class is defined by using the class keyword, followed by the name of the class and a pair of curly braces ({}). All its properties and methods go inside the braces:

```
<?php 

class Class_name
{
  //code ...
}

?>
```
We can create multiple objects from a class. Each object has all the properties and methods defined in the class, but they will have different property values. Objects of a class is created using the new keyword.
```
$object_name = new Class_name;
```

## Associative Array
Associative arrays are used to store key value pairs. The associative arrays are very similar to numeric arrays in term of functionality but they are different in terms of their index. Associative array will have their index as string so that you can establish a strong association between key and values.
```
$age = array("ABC"=>"3", "DEFG"=>"4", "HJIKL"=>"5");
```
## Foreach Loop
The foreach loop works only on arrays and objects, and is used to loop through each key/value pair in an array.
```
foreach( $array as $key => $element) {
    // PHP Code
}
```
## Array Functions and String Functions
### Array Functions
The array functions allow you to access and manipulate arrays. Simple and multi-dimensional arrays are supported.

Function &nbsp;  &nbsp;  &nbsp;  &nbsp;  &nbsp;  &nbsp;  &nbsp;	 Usage

array() &nbsp;  &nbsp;  &nbsp;  &nbsp;  &nbsp;  &nbsp;  &nbsp;	used to create a new array

array_pop() &nbsp;  &nbsp;  &nbsp;  	deletes the last element of an array

array_push() &nbsp;  &nbsp;  insert new element to the end of an array

sort()	 &nbsp;  &nbsp;  &nbsp;  &nbsp;  &nbsp;  &nbsp;  &nbsp;  &nbsp; sort the elements of the array in ascending alphabetical order

### String Functions
The string functions allows you to access and manipulate strings.

Function &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; 	Uses

echo()	&nbsp; &nbsp;  &nbsp; &nbsp;     &nbsp; &nbsp;     outputs one or more strings

strcmp() &nbsp; &nbsp; &nbsp; &nbsp; 	compares two strings

strlen()	&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; returns the length of a string

strtolower()  &nbsp;  converts string to lower case

## Array Sort
The elements in an array can be sorted in alphabetical or numerical order, descending or ascending.

Function &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; 	Usage

sort() &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; 	sort arrays in ascending order

rsort() &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; 	sort arrays in descending order

asort() &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; 	sort associative arrays in ascending order, according to the value

ksort() &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; 	sort associative arrays in ascending order, according to the key

