## An introduction to CSS

`CSS` is the second basic building block of every web page. It's not required to make a simple webpage, but all real websites will use CSS. CSS allows you to stylize pages with things like fonts, colors, and spacing. Like HTML, CSS is *not* a programming language; it just provides a list of items and how you want them to appear.

CSS is made up of three parts: `Selectors`, `Properties`, and `Values`. It sounds like a lot, but it's actually pretty easy to pick up.

### A simple example
A simple CSS file might look like this:

```css
p {
	color: red;
	font-size: 30pt;
}
```

Let's break it down. In this example, the selector is the `p`. It's letting the browser know that we want to apply these styles to any html content which is wrapped inside a `<p>` tag. You could put any html tag here (for example `h1`, `b`, or `a`).

Inside the curly braces, we place pairs of properties and values. There's a *lot* of different properties you can pick from, and each property has a set of allowed values. [This](http://cssreference.io) page has a great visual guide for most common properties if you're interested.

We can combine many different styles in a single css document by just placing the selectors one after another. This means that just one css file is enough to style the entire website. Here's an example:

```css
/* You can add comments like this */
p {
	color: red;
	font-size: 30pt;
}

a {
	color: blue;
	font-size: 10pt;
}

h1 {
	font-family: sans-serif;
	font-size: 100pt;
}
```


### Some common properties
There's a lot of CSS properties, but here's some of the more common ones:

| Property         | Description                              |
| ---------------- | ---------------------------------------- |
| font-color       | The color of the text                    |
| font-family      | The font of the text                     |
| background-color | The color of the background of a section |
| text-align       | The alignment of the text (left, center, right) |
| margin           | The amount of margin to leave around a section of content |
| width            | The width of a particular piece of content |
| height           | The height of a particular piece of content |

### Using a CSS file in our HTML
To let the browser know we want to use a css file, we need to link to it inside our html. To do this, you can just add a `<link>` tag to the `<head>` section of the file. Be sure to includes the `rel` and `type` attributes shown below so the browser knows what you want.

```html
<html>
<head>
  <link rel="stylesheet" type="text/css" href="myStyles.css"/>
</head>
<body>
	This text will be formatted using the css file!
</body>
</html>
```




### Recommended Reading

[CSS Visual Reference](http://cssreference.io)
