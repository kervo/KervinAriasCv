User Centric Milestone project for the Code Institute
============================

This project is designed to accomplish the concepts learned up to the User Centric module for the Code Institute.

My name is Kervin Arias and I’m presenting here my personal portfolio with recent work samples and also my vision about design and art in a little mockup for a blog section. The name of my site is Kervo Solutions as this has been my title as a freelance graphic designer for over 10 years.

This how the project began (https://github.com/kervo/user-centric/blob/master/img/brainstroming.png)

UX
============================

The main goal of my site is to have an easy route for potential recruiters/employers to download my cv and browse samples of my work.

After some feedback from users, I decided to change the colour scheme based on this useful link (https://coolors.co/fcf59e-b7dbe2-7c9cac-a2c5ac-b7c4ca)

* `#DBCA13`
* `#652A7D1`
* `#528199`
* `#519364`

Image gallery with samples of my work can be find at the bottom close to the footer. I decided to showcase my work in the home page, first to fill up the bottom space with something useful and secondly to attract the traffic to my work or skills sections.
(https://github.com/kervo/user-centric/blob/master/docs/Copy%20of%20Copy%20of%20milestone-project-prototype.pdf)

> The aim of my blog is to ask the questions: Why design and art are important for me?, How can I be a better graphic designer? this is an external link to my wordpress blog.

*Skills Page*
This page shows the areas of graphic design that I can work on.

> Images in here are hidden on the mobile version to keep it clean andf for the user to read at a quick glance the information.

*CV/Work**
Further information about my CV and roles in companies. Font Awesome is used to illustrate the type of industries that I've worked for.

*Contact page**
With a form to send me an email.

Features
==========

* Hamburger menu: I wanted to keep my heading clean and most users are familiar with this triagram icon to navigate through the page.

* CV download: Easy way to access my cv and download a PDF file.

## Work/Skills Timeline

My class timeline is contains a slideshow with a selection of designs.

I customised the decoration of my `ul` list items by using a svg graphic from this source (hhttps://www.flaticon.com/)



Technologies
=============================

Visual Studio Code
Boostrap
Github
Google Chrome
Adobe XD
Adobe Illustrator
Adobe Photoshop

Testing
===========

Google Chrome to verify that the site is responsive and to fix margings or paddings. My first section was causing horizontal scroll and the simple answer was to place my `row` into a `conatiner` to discover and debug the problem I used (https://blog.wernull.com/2013/04/debug-ghost-css-elements-causing-unwanted-scrolling/)

>Fixing footer links: I had a problem with the alignment of my footer because I wanted to divide it in 3 sections. When I stood back and see that two sections were built with `ul` I decided to leave them in one section with a `col-4` width and the copyright on the left as it's a longer line `col-8` then another problem came; links on the right don't look well.

Finally after this problem arrived I understood the use of `float: right;`

Another good way of testing was by sharing the link, people see the content on different devices, browsers, etc. Specially mobile phones. 

### Contact Page

During my testing `textarea` not showing correctly so I added `cols` attribute to change the default size to 30. It didn't work but I found some useful information here (https://stackoverflow.com/questions/30164301/css-width100-textarea-for-comment-responsive/30164488) by keepping the width to 100%, `textarea` takes all the space available for the contact form.

### Skills Page

When I switched to mobile mode to see the sections, `<i> icons` were showing big and pushing `<p>` to a narrow space, I added a breaking point for mobile ```@media screen and (max-width:567px)``` 


Deployment
=================

I created a repository on Github and use the guide to set up a branch by adding the origin master.

After that, I used the terminal on Visual Studio Code to link the two folders with the following steps:

* Stablish a connection in between the two folders `git init` 

* Adding all files that have been changed `git add .` and to verify what I was sending `git status`

* Ready to send the files `git commit -m "message"`

* Open the remote connection in between the two folders `git pull origin master`

* Update the files on the repository `git push origin master`






Credits
===

_HTML and CSS tag guides, colour codes_ [W3Schools] (https://www.w3schools.com) 


_CV Page_ wording based on https://www.peopleperhour.com/hire-freelancers/design 

_Boostrap_ cheat sheet for layout css styling https://getbootstrap.com/docs/4.3/layout/grid/#equal-width-multi-row

Guide to use _SVG images_ on your website https://svgontheweb.com/#preparation

_CSS generator_ https://html-css-js.com/css/generator/transform

_Inspiration_ from design portfolios and blogs https://www.shillingtoneducation.com/blog/50-best-design-blogs/

_Timeline_ for the layout (http://bestjquery.com/tutorial/timeline/demo72/#)



