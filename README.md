##Workshop 1: Getting Set Up
####Git and Github
Create an account on [Github](https://github.com/) and follow the steps under [Setting Up Git](https://help.github.com/articles/set-up-git/) if you don't have Git on your computer already. Come talk to me if you have not used Git before.

####Github Pages
Creating your very own github pages site!
* Create a new repository on Github. You can do this by clicking the little plus in the top right hand corner of the github website.
* Name this repository *username*.github.io, where username is your username on github. No need to initialize the repository with a README. Just click create.

####Looking at Your Website While Developing
After you commit the changes you are making on your text editor or in the github editor, you will be able to navigte to username.github.io in your browser and see what your website looks like.

If you are developing with a text editor and the command line, you can use [python's simple HTTP server}(http://www.linuxjournal.com/content/tech-tip-really-simple-http-server-python) to serve your website so you don't need to commit and push every time to see your changes. Let me know if you have questions about useing this.

####HTML basics
To get started with your personal website, you need to make an HTML page. HTML is like the skeleton of your website.
It lets you add stuff like words and images of cats and maybe even do a little formating.
Now to make one for yourself!

* Create a new file by clicking the plus sign after the name of your directory on github. Save that file as `index.html`.
* Copy and paste the text under index.html below into your index.html file. This is a starting template that you can use to build the HTML of your website.
* Each of the words in between `<>` are a type of element. When the name of an element like `head` is inside brackets like `<head>`, that is called a tag.
* If you want to know more about basic HTML stucture and tags as you work on the hackathon this weekend, this [link](http://www.w3schools.com/html/html_intro.asp) and the following pages are a good place to start.
* The important tag for creating your website in this workshop is the `<body>` tag.

####index.html
```html
<!doctype html>
<html>
  <head>
  </head>
  <body>
  </body>
</html>
```
HTML tags are opened when you type `<body>` and closed when you type `</body>`. All the text between those two tags will be classified as the element you selected when you made the tag. Now let's see how that works!

To start working with HTML, there are a few useful elements that you need to know. Cut and paste each of these elements into the body of your `index.html` to try them out:

|`<h1>I am a large header!</h1>` Any text that is surrounded with h1 elements will show up on your website as large bold text.|

* `<h3>I am a large header!</h3>` Any text that is surrounded with h3 elements will show up on your website as slightly smaller bold heading text.
* See what happens if you make more headers with `<h5>` or `<h6>` tags.
* `<p>I'm a paragraph of text</p>` Any text that is surrounded with p elements will show up on your website as a paragraph of text.
* `<a href="https://github.com/">Click me!</a>` This tag is called anchor, it creates a clickable link to another web page. Try changing the link.
* Next we will introduce the `img` element, which confusingly does not have a closing tag.
* `<img src="http://www.shareably.net/wp-content/uploads/2015/01/unique_cat_fur_1.jpg">` This will add an image of a cat to your web page. You can replace the source with a link to any photo on the web. You can also add a photo to your website directory on your computer and replace the current src with `src="yourphoto.jpg"`.
* Now save your `index.html` page in sublime text, go to your browser, and refresh `localhost:8000` to see your work.

Wow! So beautiful! Feel free to play with this a little bit.

There are many more elements avaliable in HTML, but these are the basics you should need to make a personal website. To learn more, there are lots of free courses and references on the web. I would recommend [Codecademy](https://www.codecademy.com/tracks/web) for interactive learning and [HTMLDog](http://htmldog.com/) for reference. But there are literally thousands of good options. Both of these resources can also help you learn CSS, which I will go over breifly below!

####CSS basics
CSS (Cascading Style Sheets) is the magic tool that allows you to turn your website into something that looks like more than some text and images. 

Basic CSS Template  
```css
selector {
    property: value;
    property: value;
    ...
}
```

**Selectors** are how you *select* the HTML element you are going to style. You can select elements by name (`body`) or you can give your HTML elements classes (`.classname`) or ids(`#idname`) and select a very specific HTML element to style.

**Properties** allow you to change the style of a part of the selected element like the `font`, `font-size`, or `color`. There are [many properties](http://htmldog.com/reference/cssproperties/) that you can style.

**Values** are the styles that you give to each property, setting `font` to `arial`, for example.

Values are often **units**, like when you want to discribe the width of a photo. 

| Unit  | Discription |
|----------|-------------|
| px |  Usually a single pixel on the client's screen (a line of width 1px is guaranteed to be "sharp and visible")|
| em | Relative to the font-size of the element (0.5em is half of the current font-size) |
| rem | Relative to the font-size of the <html> or "root" element (0.5em is half of the root font-size) |
| % | Percent of the parent element along the relevant dimension (horizontally or vertically) |

Make a customize.css file and past the following body selector in to get started with CSS.

####customize.css
```css
body {
    font: arial;
    font-size: 14px;
    color: red;
}
```

Now that you have created your CSS file, you need to link the CSS styles to the HTML in your webpage. This means that the styles you add in your CSS will be applied to your HTML.

Go back to your html file and inside the `<head>` element, add `<link rel="stylesheet" href="customize.css">`. Now if you save your HTML and refresh your browser tab, you should see the changes.

With this basic knowledge, you're ready to start playing around with CSS. Try using different slectors to play around with the properties of different types of html elements.

####Building your website
Even if you're already a web design wizard, you will still need to come up with ideas for what you want to have on your web page, and discribe all of that information in HTML format.
* What information do you want to display on your website?
* How many pages do you want to have? Some ideas include: Portfolio/Projects, Resume, About me, etc. 
* What do you want the text on those pages to say?
* What photos do you want on your webpage? Get those photos in your directory and then link them in your html.

####Filling in the Gaps
This tutorial was meant to be basic, and the main goal was to enable you to use bootstrap to make your personal website with minimal confusion. Because we want to get you up and running as quickly as possible, there were a few gaps. Here are some suggusted tutorials to help with that.
* Intro to sizing things and making layouts in CSS with the [Box Model](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Box_Model/Introduction_to_the_CSS_box_model).
* I reccomend Codecademy's HTML and CSS tutorial for their through explaination and projects about the Box Model.

####Extra Links That You Can Use To Play with Web Design Stuff
* [Mozilla Tools and Web Dev Games](https://teach.mozilla.org/tools/)
* [HTMLDog](http://htmldog.com/)
* [Codecademy](https://www.codecademy.com/tracks/web)

