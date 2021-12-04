# HTML Introduction

## What is HTML ?
HTML stands for Hyper Text Markup Language. The front end of a web page is written using HTML and CSS gives style to it. The smallest working piece of an HTML page can be called as element. Most of the elements has an open tag and a closing tag. 

Opening tag looks like : `<tag-name>` and a closing tag looks like : `</tag-name >`. The only difference between opening and closing tag is the `/` (forward slash).

Most HTML element looks like : `<tag-name>content</tag-name>`.

Some HTML elements don't have closing tag. These are called empty elements or self closing elements. These elements don't wrap any content.

Some elements has attributes. Those attributes written in opening tag and looks like : `<tag-name attribute="value">`. Example : `<h1 class="heading">`. Attribute may have an optional value. Means some attributes don't have value so they looks like : `<tag-name attribute>`.

## Is HTML a programming language ?
Technically No. HTML is a markup language responsible to present information. HTML is not used to program any logic.

## How to write HTML file ?
We can use any text editor to write a HTML file, because these are simple text files with `htm` or `html` extension.

VSCode (Visual Studio Code) is a free text editor which is used by most programmers. So it is advisable to [install VScode](https://code.visualstudio.com/docs/setup/windows) on your computer. 

## What is HTML boilerplate ?
The basic structure or skeleton of a HTML file is called HTML Boilerplate. When you create any HTML file first write that before writing codes as per your requirement.
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
</html>
```
The first line tells the browser that, this file uses `HTML5` elements. 

The second line contains `<html>` element with language attribute. It says that it uses english language.

The third line `<head>` wraps important meta information about our webpage. It will display nothing on your webpage but these have other important roles that we will discuss later.

After `head` element we have `body` element. It contains all the elements those will be displayed on the web page.

## Assignment.

- Create a text file and rename it to `progam1.html` .
- Write the below code with in that file.
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hello World</title>
</head>
<body>
    <h1>Hello World!</h1
</body>
</html>
```
- Open this file in any web browser and see the output.

## [Check Your Progress](https://docs.google.com/forms/d/e/1FAIpQLSdy3EB70Y_Da8HTBA17tfZh2VIKIey1EJ13re73XoX73QAiIg/viewform)

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







