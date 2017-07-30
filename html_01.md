## An introduction to HTML

`HTML` is the most basic building block of every web page. In fact, the content of every single website is made from HTML files. One important thing to note is that HTML is *not* a programming language. You can't use HTML to solve a math problem. Instead, it just states what content should be in a page.

HTML is made up of two parts: `Tags` and `Attributes`. You'll need both to build a simple webpage.

### HTML Tags
HTML tags begin with a `<` and end with a `>`. Each tag represents a different part of the page. Most tags come in pairs, but not always.

There's a handful of different tags you can use, and put together they can be used to build a web page. If you need a paragraph, you might use the `<p>` tag. If you need bold text, you might use the `<b>` tag. Each tag represents something different.

Normally, you'll place a pair of tags around some content. Here's an example of a paragraph tag and a bold-text tag. Notice how the closing tag has a `/` in it so we can tell the difference.

```html
<p>My Paragraph Here </p>
<b>My Bold Text Here </b>
```

One feature of tags is that they can be `nested`. That means you can place tags inside of other tags.  If you want a paragraph that's also bold, you can just nest the tags like this:  

```html
<p> <b> My Bold Paragraph Here </b> </p>
```

### Attributes
`Attributes` are extra bits of information that we can place inside tags.
Almost all HTML tags allow you to provide them attributes. In paired tags, attributes are always placed inside the opening tag.

Here's an example of a `<p>` tag with some fake attributes:
```html
<p style='Cool' color='red'>My Cool Red Paragraph Here </p>
```

Pretty cool, right? There's hundreds of tags and attributes out there, so you don't need to worry about memorizing them all. You can easily look up the list of attributes for any tag.


Now that you have the basics, you're ready to build your own web page!

### Recommended Reading

[Basic HTML Tags](https://www.tutorialspoint.com/html/html_basic_tags.htm)

[Common HTML Attributes](https://www.w3schools.com/html/html_attributes.asp)
