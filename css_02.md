## CSS Classes

In the previous section we talked about how CSS selectors let the browser know what part of the file to apply your styles to. In that example we just used simple tags from html as the selectors (for example, `p`, `a`, and `h1`).  However, you can actually do a lot more with selectors using `ID`s and `Classes`.


### IDs
Sometimes you want to format one particular part of a web page, but not the whole thing. For example, you might have a certain paragraph of text that you want to be red, but you want the rest of the paragraphs to be black.  You can use an `ID` to solve this problem. First, you just add the `id` attribute the paragraph you want to single out:

```html
<p id="superSpecial"> This is my special paragraph </p>
<p> Boring Normal paragraph </p>
<p> Boring Normal Paragraph</p>
```

Next, you can create an `ID selector` in your css file by using the `#` symbol followed by the id name. This lets the browser know you want to apply a style to *only* the item with the matching id attribute.

```css
/* Format my special paragraph */
#superSpecial {
	color: red;
}
/* Format all the normal paragraphs like this */
p {
	color: black;
}
```


### Classes
`Classes` work almost the same way as IDs, with one main difference: You can re-use classes in multiple tags. This is great for times when you want to format some tags one way, but others a different way. Instead of using the `id` html attribute, you use the `class` attribute:

```html
<p class="dankRedText"> This is my red paragraph </p>
<p class="dankRedText"> This is my next red paragraph </p>
<p> This is my boring normal Paragraph</p>
```
Then you can use the `.` character followed by the class name in your css file:
```css
/* Format my special paragraphs */
.dankRedText {
	color: red;
}
/* Format all the normal paragraphs like this */
p {
	color: black;
}
```
One neat thing about classes is that you can have multiple classes *per tag*. For example, you could say something like this:

```html
<p class="bigText redText"> This is big and red </p>
<p class="bigText"> This is just big </p>
<p class="redText"> This is just red</p>
```

### Combining Multiple Selectors
If you want to get really fancy, you can save yourself some time by using multiple selectors at once. For example, what if you had a CSS file like this:

```css
p {
	color: red;
}
h1 {
	color: red;
}
a {
	color: red;
}
```
You could just combine the selectors and rewrite this as:
```css
p, h1, a {
	color: red;
}
```
There's actually many ways to combine CSS selectors, but it's not too important for now. If you're interested in knowing more, take a look at the links below.

### Recommended Reading

[Advanced CSS Groupings](https://www.w3schools.com/css/css_combinators.asp)
