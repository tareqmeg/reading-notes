# Read: 11 - EJS

> What is EJS?

EJS simply stands for Embedded Javascript. It is a simple templating language/engine that lets its user generate HTML with plain javascript.Apr 30, 2020

...https://www.codementor.io ›

> What is the difference between EJS and HTML?

EJS simply stands for Embedded JavaScript. It is a simple template language or engine. EJS has its own defined syntax and tags. It offers an easier way to generate HTML dynamically.

> Is EJS a framework?

EJS is a tool for generating web pages that can include dynamic data and can share templated pieces with other web pages (such as common headers/footers). It is not a front-end framework.Oct 1, 2020

What is Ejs , What is the use of EJS? - Stack Overflow
https://stackoverflow.com

> ## Features

- Fast compilation and rendering
- Simple template tags: <% %>
- Custom delimiters (e.g., use [? ?] instead of <% %>)
- Sub-template includes
- Ships with CLI
- Both server JS and browser support
- Static caching of intermediate JavaScript
- Static caching of templates
- Complies with the Express view system
---

> Install

It's easy to install EJS with NPM.

`$ npm install ejs`

> Use

Pass EJS a template string and some data. BOOM, you've got some HTML.

`let ejs = require('ejs');`
`let people = ['geddy', 'neil', 'alex'];`
`let html = ejs.render('<%= people.join(", "); %>', {people: people});`




## Working with volumes

Performing a search

You can perform a volumes search by sending an HTTP GET request to the following URI:


https://www.googleapis.com/books/v1/volumes?q=search+terms

This request has a single required parameter:

q - Search for volumes that contain this text string. There are special keywords you can specify in the search terms to search in particular fields, such as:

intitle: Returns results where the text following this keyword is found in the title.

inauthor: Returns results where the text following this keyword is found in the author.

inpublisher: Returns results where the text following this keyword is found in the publisher.

subject: Returns results where the text following this keyword is listed in the category list of the volume.

isbn: Returns results where the text following this keyword is the ISBN number.

lccn: Returns results where the text following this keyword is the Library of Congress Control Number.

oclc: Returns results where the text following this keyword is the Online Computer Library Center number.


[Click here to read more](lab02b.md)