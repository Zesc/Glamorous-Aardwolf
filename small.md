# Small


*Html tag for decreasing size of text.*


The <small>  element tag is a special tag used to style text for specific situations. The way it works is that it reduces the size of the selected text down to the next level. If it's large, it will make the text medium, if it is medium it will make the text small. This tag is usually used in documents where you want to make the print smaller than the surrounding text. Purposes include : copyright information, legal text and even side comments.


## Syntax
The syntax for this tag is simple, its : <small></small> and is used right inside of the html document.
You can also use it in CSS to shrink the text smaller than usual. 
```
small {
	font-size : 8px;
}
```
In the example above, font-size is a property that determines the height of text, and setting it to 8px, tells the browser to make the text surrounded by the small tag 8 pixels high.


## Example 1


In this example we will use small in order to indicate copyright information for a text.
```
<p> memoryCraft - The world's first online School for Ancient Memory Training</p>
<p><small>Copyright 1981-2016 by Anthony Osei-Tutu</small></p>
```

## Example 2


The above is a simple method of using the <small> tag in order to reduce the size of the by 1. Another bit more complex method is to wrap only a portion of text in the small tag, and add a style attribute to it :


```
       <p> Hello my name is <small style=”font-size : 20px> Anthony Osei-Tutu</small>
```
The above example will change the height of the text between the <small> tags to be 20px high, regardless of the font-size of the regular text.


## Special Notes
This tag has no individual attributes but inherits all the global Attributes like class, id etc …..

This tag is also compatible with Chrome, Internet Explorer, Firefox, Opera, and Safari

