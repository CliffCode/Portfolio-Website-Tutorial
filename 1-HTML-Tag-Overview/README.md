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

```
<!DOCTYPE html>
<html>
    <head></head>
    <body></body>
</html>
```

In the example above, you can see that it is indeed possible to put HTML elements inside of other HTML elements.
Let's break down the HTML document above.

At the top of the HTML document is this weird looking DOCTYPE tag. What that does is specify to the web browser what kind
of document is contained in the file. In this case, it is an HTML document. This tag puts the web browser in [Standards Mode.]
(https://developer.mozilla.org/en-US/docs/Quirks_Mode_and_Standards_Mode)
