# CSS Introduction
CSS stands for Cascading Style Sheets. Basically it is used to stylise HTML page. These stylings decide how how HTML elements are to be displayed on screen or print.

## Ways to add CSS to HTML
There are [3 ways to add CSS to any HTML program](https://www.w3schools.com/css/css_howto.asp) :

1. Inline CSS : Add style attribute to the desired HTML element with proper CSS property and value pair.
2. Internal CSS : Define CSS rules with in `style` element inside head section.
3. External CSS : Write an external CSS file and link it to the desired HTML file in head section.

## CSS Rule
<img src="https://raw.githubusercontent.com/subratsir/project1-with-subrat-sir/main/img/css_rule.png" alt="css rule" />

We use CSS rules in Internal as well as External CSS.

## Types of CSS Selectors
CSS selector is a way to select HTML element(s) on which we want to apply the style. 

- Universal selector : selects elements of all types.

```
* {
  color: red;
}
```
Text color of all elements will be red.

- Type Selector or Element Selector : Selects all elements of the mentioned name.

```
p {
  color: green;
}
```
Text color of all paragraph elements become green.

- Class Selector : selects all the elements whose `class` attribute contains the specified class name

```
.redText {
  color: red;
}
```
Style will be applied to all the elements those have class name `redText` . Remember, Class names are case sensitive. Class attribute of any element can contain more then one class name separated by spaces.

- ID Selector : applies style to a single element whose `ID` attribute value is same as mentioned in CSS.
```
#container {
  background-color: grey;
}
```
Remember ID is unique in an HTML file. Means you can use same class name for more then one elements but ID name for only one element.

- Grouping Selector : If we want to apply same style to more then one elements then we can group those selectors using comma.

```
h1, h2, h3, p {
  text-align: center;
}
```
- descendant selector (space) : selects all the elements that are descendants of the specified element.
- child selector (>) : selects all elements that are the children of the specified element. But descendent selector can select children of children.
- adjacent sibling selector (+) : select an element that is directly after another specified element.
- general sibling selector (~) : selects all elements those are directly after another specified element.

```
<!DOCTYPE html>
<html>
<head>
<style>
.container h1 {
  text-align: center;
  color: red;
}
.child1 > p {
  text-align: center;
  color: red;
}
.subcontainer p {
	color:green;
}
h2 +p {
	background-color:green;
}
h2 ~p {
	color:yellow;
}
</style>
</head>
<body>
<div class="container">
  <div class="child1">
    <h1>Hello World!</h1>
    <h2>Smaller heading!</h2>
    <p>Paragraph inside container</p>
    <p>Second Paragraph inside container</p>    
  </div>
  <div class="child2">
    <h1>Hello World!</h1>
    <h2>Smaller heading!</h2>
    <p>Paragraph inside container</p>
    <p>Second Paragraph inside container</p>    
    <p>Third Paragraph inside container</p>
  </div>
</div>
<div class="subcontainer">
	<p>This is a paragraph.</p>
</div>
</body>
</html>
```


<p align="center" width="100%">
    <a href="#">
        <img width="33%" src="https://github.com/subratsir/HTML-CSS-JavaScript-Basics/blob/main/img/next-lesson1.png" width="250px" height="auto" /> 
    </a>
</p>

<p align="center" width="100%">
<h1>Have a question ?</h1>
<p>Chat with our friendly community in our Discord Chatrooms!</p>
<a href="https://discord.gg/KYYWfcVU"><img src="https://quoramarketing.com/wp-content/uploads/2021/08/Fix-Discord-Error-Code-96.jpg" alt="Open Discord" width="150px" height="auto" /></a>
</p>

## Hey <img src="https://github.com/TheDudeThatCode/TheDudeThatCode/blob/master/Assets/Hi.gif" width="29px">, Follow [Subrat Sir!](https://github.com/subratsir) 

<a href="https://in.linkedin.com/in/subratsir">
  <img align="left" width="24px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/linkedin.svg"  />
</a>
<a href="https://twitter.com/SubratSirIndia">
  <img align="left" width="26px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/twitter.svg" />
</a>
<a href="mailto:subrat.ku.dash@gmail.com">
  <img align="left" width="26px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/gmail.svg" />
</a>
<a href="https://www.youtube.com/channel/UCTCmj3TOBxI_5f1J-n7kN5A">
  <img align="left" width="26px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/youtube.svg" />
</a>
<a href="https://discord.gg/KYYWfcVU">
  <img align="left" width="26px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/discord.svg" />
</a>

<br />
