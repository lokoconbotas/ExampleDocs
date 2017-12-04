![UbiqumLogo](https://ubiqum.com/marketing/ubiqum.png)

# Frequently Answered Questions


When something is not working the way you want or if you don’t know how to do something in HTML/CSS one of the first things you should try is Google. Say you don’t know how to make the font larger, google something along the lines of: **`CSS make font larger.`** Or if you can’t put the image in the center of a div google: **`CSS position image center div.`**

Careful word choice is more important here than grammar. If you can’t find the solution try changing words. Usually the answers to the questions about CSS and HTML are answered best on websites like StackOverflow and W3Schools. If you are looking at best answers on StackOverflow make sure you also carefully **`read the question`** as you might try to use the solution for a different problem. 

Another good way to find a solution is to ask your coworkers. It’s very likely that they have encountered the same problem and already have found a solution. Also if somebody asks you for help try to not just give the code to them but rather tell them what to google e.g. If someone doesn’t know how to make buttons in HTML have round corners suggest googling border-radius to them.

Before trying to do something new research it first. In terms of HTML and CSS **https://learn.shayhowe.com** is one of the best places to learn. 

Here are some frequently asked questions.

## I see a blank page in my browser when I open my HTML file.

**Has the HTML been saved after being modified?**

**Are you viewing the correct HTML file (the one you are modifying)?**

Make sure you’ve given at least some visible content to the page. Like:
```html
<p>Hello World!</p>
```
When viewing the HTML file in the browser open dev tools.

Windows: `Ctrl + Shift + I`

Mac: `Command + Option + I`

Or: `right button click >> inspect`

Note that some browsers have different shortcuts.

## How to add check if the css file is added.

In **brackets** make sure you include the link:
```html
<link href="style.css" type="text/css" rel="stylesheet">
````

If it is in the same folder as your html file. It doesn’t to be in the same folder. You can use (between quotes) :
```html
"../path_to_your_file.css"
```
to refer to your css file. For example you have your html file and next to it is a folder named `styles` with your css file then your link would be
```html
<link href="styles/style.css" type="text/css" rel="stylesheet">
```

## I can’t position elements the way I want.
Please refer to

https://learn.shayhowe.com/html-css/positioning-content/

Chapters 4 and 5 to get to know how to position elements.


