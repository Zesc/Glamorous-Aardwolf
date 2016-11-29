# Array.prototype.shift

*JavaScript method*

Array is a global object that holds a group of values in a list format. The prototype aspect of the array, is used to add methods to the particular Array. The .shift is a method that removes the first element of the selected array and returns it as a value. 

## Syntax

The syntax of this method is in two parts. The first part uses the .prototype in order to add the .shift() method to an array that is corrected:

```
        Array.prototype.shift(); //is the global aspect
        arr.shift(); // the method applied to a particular array
```

### arr.

This portion of the command, tells the browser you will be accessing an Array.

#### .shift()

This is a built in method/function that commands the browser to select the first element of the array and return its value.The array arr inherited it since it was created using the Array constructor.

## Example 1

Here's a simple example of the use of Array.prototype.shift()

```
        var arr = ["A",2,"C3",4,5];
        arr.shift()// Will return the letter A
```

## Example 2

This method can also be used if you wanted to print out the whole array minus the first element as in below :

```
       var arr = ["A",2,"C3",4,5];
       arr.shift();
        console.log(arr);//Will print out array minus the letter "A" 
```

## Special Notes

This method is compatible with all known browsers both desktop and mobile.
