# Padding-top 

*CSS property*

`padding-top` is a property that each html element has as an option. The padding area is the space between the content of 
the element and its border. Padding adds space in all sides of the target element content. Padding-top will only add space on the 
the top side of the element and it only takes one value.

![Box model diagram](https://s20.postimg.org/tyq8ve2jh/padding_top.png)

## Syntax

Introduction to the syntax/usage. A example of `padding-top` syntax is below:

```css
div{
    /*padding: 10px;  add space in all sides of target element*/
    padding-top: 10px;  /*add space on the top side of target element*/
}
```

### Values

`padding-top` takes only one value. It can be of any length unit(px, em, pc, in, mm, …) or porcentage with reference to the
width of the parent element.

## Example 1

Following example set padding-top to 10px for a div element.

```css
  div{
    padding-top: 10px;
  }  
```

## Example 2

Following example `p` element use half of the parent `div` element width for its `pading-top` value.

```css
div{
  background: black;
  width: 200px;
  height: 200px;
}

p{
  background: red;  padding-top: 50%; /*100px*/
}
```

[Link](https://codepen.io/Zesc/pen/ObORLG) for a more visual example.

### Support

Desktop support:

  * Chrome 1.0
  * Firefox 1.0
  * IE 4.0
  * Opera 3.5
  * Safary 1.0(85)
  
Mobile support for mobile is unknown.