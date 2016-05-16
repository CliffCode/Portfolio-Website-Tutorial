# 1 HTML Tag Overview

In this tutorial, you will learn how to create your very first website!
The first thing that you will have to learn about to create a website is
HTML, the Hyper Text Markup Language.

Let's learn about a very simple HTML element, the paragraph element. This element is used
to represent a paragraph of text inside an HTML document.

Here is what a paragraph tag looks like:

``` html
<p>This is my paragraph.</p>
```

Look confusing? Let's break it down. The weird angle bracket looking thing
on the left is called the HTML tag. The leftmost part,
```
<p>
```
is called the opening tag. There are many tags that are defined in the HTML language
specification. You have to follow the rules of the language to make your website work properly.

The stuff in the middle:
```
This is my paragraph
```
is the contents of the HTML element. This is content that you, the programmer are in charge
of defining yourself. The stuff in the middle is the content that you read on most web pages.

The outer part of the HTML tag is the closing tag:
```
</p>
```
This tells the web browser that you are done putting contents inside of the tag. Always remember to close HTML tags.
Failing to do so can cause your web page to look weird and have unexpected behavior depending on which web browser that
you are using.

All together now, here is what the structure of an HTML element looks like:
```
<openingTag>Content goes here.</closingTag>
```

For those of you who aren't new to HTML, there is still more to talk about like attributes! Don't worry
we will get there shortly. Let's go ahead and make our first website!

## 1.1 HTML Document Structure

Paragraph tags are awesome and all, but you probably want to put some more stuff in your website.
This is where the html document structure comes into play.

An HTML document is what specifies the contents of your entire web page.
We will learn shortly about the DOM, or the Document Object Model. To put it simply, the DOM is the way that web browsers
represent the content of a web page in memory. If this sounds confusing, don't worry as we will be covering it during the
intro to JavaScript tutorial.

Let's go ahead nad create our very first HTML document. Something cool about HTML elements is that they can be nested
inside other HTML elements. What does that look like? This:

```html
<!DOCTYPE html>
<html>
    <head>
        <meta charset=UTF-8>
        <title>My First Web Page</title>
    </head>
    <body>
        <h1>Hello World!</h1>
    </body>
</html>
```

In the example above, you can see that it is indeed possible to put HTML elements inside of other HTML elements.
Let's break down the HTML document above. You can also see that it's possible to have the opening and closing tag of an HTML
element on different lines. This allows the document to be easier to read for the programmer. It has no effect on how the web
browser interprets the HTML code.

So what exactly is going on in this HTML document? At the top of the HTML document is this weird looking DOCTYPE tag. What that does is specify to the web browser what kind
of document is contained in the file. In this case, it is an HTML document. This tag puts the web browser in [Standards Mode.]
(https://developer.mozilla.org/en-US/docs/Quirks_Mode_and_Standards_Mode)

The next line is the HTML tag. This is the root element of the html page. The contents of this tag is the contents of your
entire web page. In the example above, the HTML element has two elements inside of it, the head and body elements.

The head element contains information about the web page, or meta data. In our example above, we specify two things, the
character set, and the title of the web page. The character set specifies how the text for the page should be encoded.
This tag is slightly different than the other tags, as it just has an opening tag. Certain tags in HTML allow this. Another
example of a tag like the meta tag is the img tag.

The stuff inside of the html tag (``` charset=UTF-8 ```) is called an attribute. HTML Tags can have attributes
which include more information about the tag. We will be talk about these more in a bit.

Last but not least is the title of the web page. This specifies the text that will appear on the top of the tag in the web
browser.

Finally, we have the body tag which contains the meat of our web page. Most of
the HTML that you write will go inside of the body element. In our body element, we added an h1 tag, which specifies a large heading.
Try adding a paragraph tag on the line below with some text!


