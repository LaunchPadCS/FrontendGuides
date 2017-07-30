## Anatomy of an HTML Page

Now that you know about HTML `tags` and `attributes`, you can write your own web page! If you want to try out some of these examples, you can just grab your favorite text editor ([Atom](https://atom.io/) and [Sublime](https://www.sublimetext.com/) are both popular, but anything works) and create a new file called `test.html` somewhere on your computer. Open that file in Chrome (or any other browser), and check out your brand new, empty website!


### Hello World in HTML
HTML files should always start with an `html` tag. Inside the html tag,
you'll have a `head` and `body` tag. The head section can contain some special
information for the browser (the language, a description, some keywords for search engines, etc...). The body tag will contain all the actual content that the user sees.   

A simple page would look like this:
```html
<html>
<head>

</head>
<body>
  Hello World!
</body>
</html>
```
### Viewing an HTML page
Your HTML file doesn't need to actually be on the internet to see what it looks like.  To open a HTML file locally, just right click the file and choose to open it with your browser. You should see a beautiful blank page with just your message to the user.   

If you ever update a html file, but your changes don't appear in the browser, you may need to force-refresh the page. In Chrome, the shortcut is Shift + F5.
This gives the browser a heads-up that you modified the page.

### Adding a title
You may have noticed that the title in the browser tab just says `test.html`. You can change it to say something more interesting by using the `title` tag. It goes in the header section and let's the browser know what you want the page title to be.  With a title, the file would look like this:
```html
<html>
<head>
  <title>My First Page</title>
</head>
<body>
  Hello World!
</body>
</html>
```

If you refresh the page in your browser, you'll see the title has updated.
Nice work!
