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

