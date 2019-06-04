# Project-1-Build-a-Portfolio-Site

FEWD: Project 1: Build a Portfolio Site v1

#Background

V2 two of the porfolio project makes use of Flexbox CSS to produce a custom site that includes about, contact and news pages.

##CSS

Version 1 is build using CSS Grid which I later found very cumbersome for such a small site.  Also, using the approach of mobile first lends itself to taking advantage of the the CSS Flexbox's ability to switch direction based (column too row) in order to accomodate larger screens. when using CSS Flexbox for a mobile orientated design the idea is that the entire content, i.e. the body is setup to present the content in one column and then each main element which is an item of the body Flexbox, for example the navigation and header can be setup as Flexboxs as well to deliver their content in rows.  Margins and are best achieved by setting this at parent level using:
```
margin: auto;
```
##Images

I managed to find fantastic free images on  [Pixabay](https://pixabay.com/) so many thanks to the generous photographers and designers on Pixabay.  I did try referencing each image but ran into a problem trying to add such content to a ```<picture>``` HTML element.

##HTML

All the templates, including news, contact and about were built using vanilla HTML5.  No frameworks were used as I wanted to try use the basic tools and better understand how they work.  The contact page has a contact form which will need to be hooked up using Javascript and i'll do this once the site is ready to go live.

##JavaScript

When I decided to add a navigation menu, I initially worked on integrating the Javascript to make the menu work.  However, I evently ran into the issue that is commonly know and that is once you like on a menu item you are directed to a new page so how do you update the contact on the new page.  There are JQuery and many other solutions, including vanilla JavaScript but I decided to just keep it simple for now by adding the ```"class="active"``` and ```class="noactive"``` to each of the navigation items on each page.

FEWD: Project 1: Build a Portfolio Site v1

**CSS**

Worked on trying to build a CSS Grid system that can work with a CSS Flexbox.  

**Status**

Submitted for first review.  Still need to work on the spacing more.
