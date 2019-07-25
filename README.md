# Project 0

Web Programming with Python and JavaScript

I am Hans and this is my project0.

This webpage meets all the requirements for project0 as indicated in:
	https://docs.cs50.net/web/2018/x/projects/0/project0.html


It contains four different .html pages:  
* index.html
	+ Navigation bar, three columns in bootstrap system, one imagen (photo taken by me), jumbotron.  
	+ It just invites you to check the other webpages with more info about "me".  
* bio.html
	+ Navigation bar, two columns in bootstrap system, one image (photo taken by me), one list that change color for the CSS property.
* likes.html  
	+ Navigation bar, table, unordered list, change color when hover in odd-elements.
* articles.html  
	+ 2x2 square with 4 "articles" (al least attemp to look like articles). I wrote them, so no quotation is included in any of them.  
	+ The last article with a French phrase links you to Google Translate.  

It is possible to get from any page on your website to any other page by following one or more hyperlinks in the navigation bar.  

It includes:  
* two lists (different to navigation bar): bio.html and likes.html  
* two image: index.html and bio.html  
* one table: likes.html  

It has one stylesheet file called "styles.css" aditional to bootstrap 4. You can find there:  
* different properties (margin, border, color, text-aling, padding, content).
* id selector (#naranja - background-color = orange)
* .class selectors (.bio, .biography)
* mobile-response query (change the word Biography to bio in smaller screens)
* one Bootstrap component: Jumbotron
* Bootstrap columns for layout purposes using Bootstrap’s grid model.
	+ In bio.html is used to put in two columns my info and "my picture".
	+ In articles.hmtml is used to make a 2x2 square in order to put the "articles" in their places.
The stylesheets styles0.scss uses:
* two SCSS variable ($colorcito - "literally little color in Spanish", and $naranjita - "literally little orange in Spanish")
* one example of SCSS nesting (several elements inside div)  
* one use of SCSS inheritance (the font-family is extended)
