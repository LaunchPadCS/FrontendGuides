## Some Important Tags
There's a *lot* of html tags you can use (here's the [full list](https://www.w3schools.com/tags/default.asp) if you want to see). A lot of them aren't used much, but there's a few that you'll use pretty often.  Here's the basics:

headers, paragraph, div, links, images

| Tag  | Description                              |
| ---- | ---------------------------------------- |
| p    | Use this to wrap a chunk of text that you want to treat as a single paragraph |
| img  | This tag lets you place an image in the page |
| a    | This tag creates a link to a different page |
| h1   | Use this tag to mark some text as a header |
| h2   | Use this tag to mark some text as a smaller header |
| h3   | Use this tag to mark some text as an even smaller header |
| h4   | Use this tag to mark some text as an even SMALLER header |
| h5   | Use this tag to mark some text as a tiny header |
| ul   | Use this tag to create an unordered list (bullet points) |
| ol   | Use this tag to create an ordered list (numbered points) |
| li   | Use this tag to create an item inside a list of either type |

### Image Basics
The `img` tag lets the browser know to draw an image. It must contain the `src` attribute to say where the image file is located. Although it's not required, you should include the `alt` attribute as well. This just contains some text that will be shown if the image cannot load (or if the user is handicapped and using special software). Finally, note that the `img`  tag does **not** need a closing `</tag>` after it!

```html
<img src="https://pbs.twimg.com/media/CiGKLjsWwAEpJ5h.jpg" alt="An adorable cat">
```

### Link Basics
The `a` tag contains an `href` attribute that has the target of the link. Whatever text is inside the two `a` tags will become the clickable link. Here's an example of what a link to google would look like:

```html
<a href="https://www.google.com/"> Go To Google </a>
```

### Header Basics
You probably noticed there's a lot of header tags, going all the way from `h1` to `h5`. Headers will look different depending on a lot of factors, but the general idea is that `h1` represents the "main" header, and `h5` is the smallest "sub-header". You can think of these like bullet points nested underneath eachother.

```html
<h1>Header Basics<h1>
Here I'm going to talk about some header basics.
<h2> My first main point </h2>
<h3> A sub-point </h3>
Now I'm talking about my sub point! I just love headers so much!
<h2> My second main point </h2>

```

### List Basics  
Lists are pretty simple to make in html. There's two types. An unordered list `ul`, and an ordered list `ol`.  Inside either of those tags you can use the `li` tag to create a list item.

```html
A bullet point list:
<ul>
<li> Cats </li>
<li> Dogs </li>
<li> Monkeys </li>
</ul>

A numberedlist:
<ol>
<li> My First Item </li>
<li> My Next Item </li>
<li> My Last Item </li>
</ol>
```

###Recommended Reading
[The complete list of HTML tags](https://www.w3schools.com/tags/default.asp)
