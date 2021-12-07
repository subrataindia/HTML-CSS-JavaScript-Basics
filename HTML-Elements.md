# HTML Elements

## HTML Headings
There are six types of heading elements in HTML. They are `h1` to `h6`. `h1` displays the largest text size on web browser and `h6` smallest. But we are not using these only to display larger text sizes because that can be achieved using font-size property when we read CSS. Remember `h1` is the most important tag in a web page. Generally this is used to write the main heading. For sub heading we can use `h2` and so on. These tags play important role in search engine optimisation. 

So use these tags wisely at appropriate places. So that when any search engine visits your website they know it better, which is the heading of your web page, which is sub heading and which is paragraph.

## HTML Paragraphs
`p` element is used to write a paragraph. It ignores the white spaces written with in it. To use new line with in a paragraph we can use `<br>` tag.

`pre` element can be used to write pre-formatted text. It preserves all the white space characters like tab, enter etc.

## HTML Formatting text elements
- `<b>` : This element is used to bold the wrapped content.
- `<strong>` : This element also displays the wrapped content bold. But it tells browser that this text is important.
- `<i>` : This element is used to italisize the wrapped text.
- `<em>` : This element is used to emphasize the wrapped text.
- `<mark>` : This element is used to mark the wrapped text.
- `<small>` : This element is used to smaller the size of the wrapped text.
- `<del>` : This element is used to mark the wrapped text as deleted.
- `<sub>` : This element is used to display the wrapped text as subscript.
- `<sup>` : This element is used to display the wrapped text as superscript.

You can nest one element with in another. Look at the below example.

```
<!DOCTYPE html>
<html>
   <head>
   </head>
   <body>
      <p>Cost of the Shirt : <mark><del>Rs.5000.00</del> Rs.500.00</mark> only for today.</p>
   </body>
</html>
```

## Nesting and Indentation
Look at the above example. `body` element is nested with in `html` element and `p` element is nested with in `body` element. So we can say `p` is children of `body` and `body` is children of `html`. Similarly `html` is parent of `body` and `head` and `body` is parent of `p`.

In the above example we have indented the children elements. It is not compulsery but is treated as a best practice because it makes the level of nesting clear and readable for programmer.

## HTML Comments
In real world when you are writting any program, it may have thousands of lines. Suppose you want to debug it or want to modify it, Then definitely you will get confuse. To make it simple and easy we can write comments in our program. Comments are ignored by browsers. 

- comment opening tag : `<!--`
- comment closing tag : `-->`

All text lines written with in these two tags are treated as comment and ignored by browser.

## HTML Lists
There are two types of lists in HTML as 1.`ul` (unordered list) and 2. `ol` (ordered list)

The lists are used to display menu items, list of shopping items, steps of a process etc. If you want to display bullets then use `ul` and If you want to display numbers or letters in list then use `ol`.

a number of `li`s nested with in `ul` or `ol` to specify list items.

Example : 
```
<ul>
   <li>Item 1</li>
   <li>Item 2</li>
   <li>Item 3</li>
</ul>
```
## Anchor Elements
To create a link in same page or to another page `a` tag is used.

- `<a href="https://mywebsite.com/mypage">Click to go to my website</a> `  : This redirects you to a new website. The address of website is mentioned as a value of `href` attribute. This website address can be absolute or relative. The address mentioned in this example is absolute address.
   - `<a href="mypage.html">Click to go to my website</a> `  : This will redirect you to the mypage.html only if it exists in the same directory.

- `<a href="#mySection">Click to go to a section</a>` : This redirects you to a portion of the same page where an element with `id` attribute of `mySection` exist. Remember the value of `id` attribute is case sensitive.

- `<a href="#">Click Here</a> `  : This will redirect you no where. This is called empty anchor tag.

## HTML Images
To make our website eye caching and interesting we have to use images in our website. This can be done using `img` tag.

Example :
```
<img src="logo.jpg" >
```
Remember `img` tag don't have a closing tag. `src` attribute specifies the address of the image file. This address can be relative as well as absolute.

## [Check Your Progress](https://docs.google.com/forms/d/e/1FAIpQLSewPAwFWNASUglWy-ct3SNLpArERKJxiFJdTcVW6Ox6hQdYrg/viewform)


<p align="center" width="100%">
    <a href="https://github.com/subratsir/HTML-CSS-JavaScript-Basics/blob/main/HTML-Project-1.md">
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
