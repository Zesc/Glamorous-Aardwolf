# Box-decoration-break


*CSS Property*


The CSS property box-decoration-break dictates what happens to an element boxes (padding, border, and margin) when there is a situation that the element is broken apart into various different lines. This separating of an element into different lines is called fragmentation. This is like when you take a grenade blows apart and separate its various parts to different areas. The same apply for elements, though less explosively. There are times when the parts of an element are meant to run together but then they get moved to another line or column 
Write a description here. Provide an overview of what the reference entry is, how it's used, it's significance, or how it's commonly used.




## Syntax


Introduction to the syntax/usage. A example of CSS syntax is below:


```
       box-decoration-break: slice | clone
```


### Values


slice | clone


#### Slice


An explanation of the "color" value belongs here.


#### Clone


When the clone value is added to box-decoration-break, the margin, border, and padding is applied to each fragment as if it was an isolated complete element instead of a fragment. For example if the element 


## Example 1


In this simple example, we will simulate what it looks like to have a line fo text broken up into multilines and the effect it has before and after box-decoration-break is applied:


```
<style>
.text{
border : 2px solid red;
border-radius : 13px;
margin-left: 10px;-webkit-box-decoration-break: clone;
}
</style>
<body> <span class=”text”>Hello<br>what is your<br>name?</span></body>
```
This is how the above text will display before you add box-decoration-break :clone;

![](Books.MD_UI_Assets/clone2.png)

After you add box-decoration-break : clone;

![](Books.MD_UI_Assets/clone1.png)

```
<style>
.text{
border : 2px solid red;
border-radius : 13px;
margin-left: 10px;-webkit-box-decoration-break: clone;
}
</style>
<body> <span class=”text”>Hello<br>what is your<br>name?</span></body>
```



## Example 2


In this example we will use a bit more complex situation and show the use of the clone value, when columns are added..

Let’s stay you begin with an element that looks like this : 


```
       .text{
border : 2px solid red;
border-radius : 13px;
margin-left: 10px;-webkit-box-decoration-break: clone;
display : block;
Width 30%;
}
</style>
```




## Special Notes


This property is not yet available in all browsers. Currently it is supported by Chrome, Firefox, and Opera. This means you will have to include multiple properties in your rule-set for it to work with different browsers.


