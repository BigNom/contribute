---
title: Media Queries
---
## Media Queries

The @media rule is used to allow different style rules to be applied based on the device the request is being made from.

Media queries look at the capability of the device and can be used to check things such as:
* width and height of the viewport
* width and height of the device
* orientation (is the device in landscape or portrait mode?)
* resolution



Examples:
```html
<h1 class="test">This is a heading 1</h1>
<p class="test">This is a paragraph 1</p>
<h2 class="test">This is a heading 2</h2>
<p class="test">This is a paragraph 2</p>
<div class="test2 test3">This is a div 1</div>
```
Since class name is not unique, the HTML class attribute makes it possible to define equal styles for elements with the same class name. **Here is how you can select class in a CSS file to style elements (notice the . notation):**    

**All elements of class `test` will be applied with this style:**    
```css
.test {
  color: green;
}
```
**All `<p>` elements of class `test` will be applied with this style:**  
```css
p.test {
  border: 1px solid black;
  color: red;
}
```
**All `<h1>` and `<h2>` elements of class `test` will be applied with this style:**  
```css
h1.test, h2.test {
  color: blue;
}
```
**All elements which have both class `test2` and `test3` will be applied with this style:**
```css
.test2.test3 {
  color: green;
}
```
**Tips: No space between multiple classes.**
#### More Information:
CSS Syntax and Selectors: <a href='https://www.w3schools.com/css/css_syntax.asp' target='_blank' rel='nofollow'>w3school</a>
