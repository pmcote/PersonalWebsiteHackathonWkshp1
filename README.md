##Workshop 1: Getting Set Up
####Git and Github
* Download a toolkit for your command line
* Make your github account/Log in to your account and set up your command line

####Navigating from the Command Line
Do we need this?

####Github Pages
Creating your very own github pages site!
* Create a new repository on Github. You can do this by clicking the little plus in the top right hand corner of the github website.
* Name this repository *username*.github.io, where username is your username on github. No need to initialize the repository with a README. Just click create.
* Go to your terminal and navigate to your directory that you want to keep your rad website codee in. Then type `git clone https://github.com/username/username.github.io.git`, replacing `username` with your username. This will create a local directory that is linked to your remote github repository. When you commit your changes locally and push to the remote master branch, they will magically be accessable if you point your browser to http://username.github.io! So exciting! So easy! Hooray!

####A Text Editor
We'll be using the free trial of a text editor called Sublime Text. There are many other options for Text editors, but Sublime is really nice to start out with, and you can add lots of fancy extensions to make it fit your development style.

Download and install sublime text [here](http://www.sublimetext.com/).

####Looking at Your Website
`cd` to your `*username*.github.io` directory on your computer, and type `python -m SimpleHTTPServer` into the commandline. This starts a simple HTTP server that allows you to use a browser to view files in that directory. 

Go to your browser and enter http://localhost:8000/ into a new tab.

####HTML basics
To get started with your personal website, you need to make an HTML page. HTML is like the skeleton of your website.
It lets you add stuff like words and images of cats and maybe even do a little formating.
Now to make one for yourself!

* Open Sublime Text and create a new file. Save that file as `index.html` in username.gihub.io directory you cloned from github.
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
*`<h1>I am a large header!</h1>` Any text that is surrounded with h1 elements will show up on your website as large bold text.
* `<h3>I am a large header!</h3>` Any text that is surrounded with h3 elements will show up on your website as slightly smaller bold heading text.
* See what happens if you make more headers with `<h5` or `<h6>` tags.
* `<p>I'm a paragraph of text</p>` Any text that is surrounded with p elements will show up on your website as a paragraph of text.
* Now save your `index.html` page in sublime text, go to your browser, and refresh `localhost:8000` to see your work.

####CSS basics

####customize.css

##If you already know all about the above stuff. . .
####Work on your HTML
Even if you're already a web design wizard, you will still need to come up with ideas for what you want to have on your web page, and discribe all of that information in HTML format.
* What information do you want to display on your website?
* How many pages do you want to have? Some ideas include: Portfolio/Projects, Resume, About me, etc. 
* What do you want the text on those pages to say?
* What photos do you want on your webpage? Get those photos in your directory and then link them in your html.

####Register a custom domain and set up forwarding from Github pages

