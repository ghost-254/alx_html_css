Learning Objectives
At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

General
What is HTML
How to create an HTML page
What is a markup language
What is the DOM
What is an element / tag
What is an attribute
How does the browser load a webpage
Requirements
General
Recommended editors: Visual studio code
All your files should end with a new line
A README.md file, at the root of the folder of the project is mandatory
You are not allowed to install, import or use external libraries. This website must be build with only HTML/CSS/JavaScript. No NodeJS, React, VueJS, Bootstrap, etc.
Your code should be W3C compliant and validate with W3C-Validator

Tasks
0. Structure
mandatory
Create the most basic, simple and valid HTML file called base_index.html

The page should contain:

a DOCTYPE
a head:
with a title
a body
Tips: don’t forget to read all concept pages…

Test the webpage with the official HTML Validator. You will see that it is not happy!

First things first, fix the code in base_index.html so that it is valid.

You will see that the validator then becomes much happier!

Repo:

GitHub repository: alx_html_css
Directory: html_basic
File: base_index.html
0/7 pts
1. Make a cool first webpage
mandatory
Copy your file base_index.html to index.html

Add in the body of the page:

at least 4 paragraphs;
headings (titles) of level 1, 2 and 3, which are represented by <h1>, <h2> and <h3> tags;
a clickable image of your choice (you can use the https://www.holbertonschool.com/holberton-logo.png image, or another one you find on the internet by using its full URL); and it may link to any URL online that you want.
Repo:

GitHub repository: alx_html_css
Directory: html_basic
File: index.html
0/7 pts
2. Make a cool other webpage
mandatory
Copy your file base_index.html to tweets.html

Add in the body of the page:

embed at least one tweet (Here’s the official documentation from Twitter about embedding single tweets in a webpage’s HTML code.)
contain a link to your index.html webpage, for users who may go back to your homepage
In index.html, add a link to tweets.html, for users landing on your homepage, who want to see your tweets!

Repo:

GitHub repository: alx_html_css
Directory: html_basic
File: index.html, tweets.html
0/6 pts
3. Make a cool website
mandatory
However, in order to start getting consistency throughout the website, all of the HTML files (index.html and tweets.html) must now have the same structure:

The <body> tag of all of your webpages must contain exactly three direct sub-tags in that order: <header>, <main> and <footer>
The <header> tag must contain an unordered list (the <ul> and <li> tags) of links (the <a> tag) to each of your webpages. As you may have understood, this will serve as a navigation for your website.
The <footer> tag must contain one paragraph with the sentence Made by <YOUR NAME> - <a href="<ANY LINK>" target="_blank">here</a>.
The <main> tag must contain two direct sub-tags in that order: <article> and <aside>:
<article> contains the content of your webpage: texts, links, images, tweets, … This is the part of index.html and tweets.html that you have already written.
<aside> contains a single paragraph, just reading for now “placeholder to add comment thread later”.
Repo:

GitHub repository: alx_html_css
Directory: html_basic
File: index.html, tweets.html
0/16 pts
4. Add some level of creativity
mandatory
Update your index.html to add a table with information about some of the learners.

On a new line after the last </aside> tag, introduce an <article> element which will serve as a container for the table of learners.

The <article> tag should contain a table <table> with the following structure:

Use the <thead> tag to define the table header row.
Use the <tbody> tag to contain the table data rows.
Populate the table with the following data:
Name	Age	Country
John	25	USA
Emily	28	Canada
Michael	32	Australia
Sophia	21	UK
Repo:

GitHub repository: alx_html_css
Directory: html_basic
File: index.html