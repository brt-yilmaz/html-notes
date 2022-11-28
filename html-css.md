# The Notes from HTML & CSS Design and Build Websites Jon DuCkeTT  

The contents of the `<title>` element are either shown in the top of the browser.

``` html
<html> 
  <head> 
    <title>This is the Title of the Page</title> 
  </head> 
  <body> 
    <h1>This is the Body of the Page</h1> 
    <p>Anything within the body of a web page is displayed in the main browser window.</p> 
  </body> 
</html>
```  

By enclosing words in the tags `<b>` and `</b>` we can make characters appear bold.  

By enclosing words in the tags `<i>` and `</i>` we can make characters appear italic.  

`<p> 28 <sup>th</sup> </p>` 28 <sup>th</sup>  

`<p> H<sub>2</sub>O</p>` H<sub>2</sub>O  

if it comes across a line break, it treats that as a single space too. This is known as **white space collapsing**.  

if you wanted to add a line break inside the middle of a paragraph you can use the line break tag `<br />`.  

you can add a horizontal rule between sections using the `<hr />` tag.  

you are going to meet the `<em>` element that allows you to indicate where emphasis should be placed on selected words and the `<blockquote>` element which indicates that a block of text is a quotation. But you should not use them to change the way that your text looks. 

The use of the `<strong>` element indicates that its content has strong importance.  

`<p>I <em>think</em> Ivy was the first.</p>`  

The `<q>` element is used for shorter quotes that sit within a paragraph.  

```html
<blockquote cite="http://en.wikipedia.org/wiki/ Winnie-the-Pooh"> 
  <p>Did you ever stop to think, and forget to start  again?</p> 
</blockquote> 
<p>As A.A. Milne said, <q>Some people talk to  animals. Not many listen though. That's the  problem.</q></p>
```
Result: 

<blockquote cite="http://en.wikipedia.org/wiki/ Winnie-the-Pooh"> 
  <p>Did you ever stop to think, and forget to start  again?</p> 
</blockquote> 
<p>As A.A. Milne said, <q>Some people talk to  animals. Not many listen though. That's the  problem.</q></p>

If you use an abbreviation or an acronym, then the `<abbr>` element can be used.  

```html
<p><abbr title="Professor">Prof</abbr> Stephen  Hawking is a theoretical physicist and  cosmologist.</p> 

<p><acronym title="National Aeronautics and Space  Administration">NASA</acronym> do some crazy  space stuff.</p>
```
Result: 
<p><abbr title="Professor">Prof</abbr> Stephen  Hawking is a theoretical physicist and  cosmologist.</p> <p><acronym title="National Aeronautics and Space  Administration">NASA</acronym> do some crazy  space stuff.</p>  

When you are referencing a piece of work such as a book, f ilm or research paper, the  `<cite>` element can be used to indicate where the citation is from.  

The first time you explain some new terminology (perhaps an academic concept or some jargon) in a document, it is known as the defining instance of it.  

```html
<p>A <dfn>black hole</dfn> is a region of space from  which nothing, not even light, can escape.</p>
```
Result:
<p>A <dfn>black hole</dfn> is a region of space from  which nothing, not even light, can escape.</p>  

The `<address>` element has quite a specific use: to contain contact details for the author of the page.  

```html
<adress> 
  <p> <a href="mailto:beratyilmaz3102@gmail.com"> beratyilmaz3102@gmail.com</a> </p>
  <p> 1234 Street, köln </p>
</adress>
```

<adress> 
  <p> <a href="mailto:beratyilmaz3102@gmail.com"> beratyilmaz3102@gmail.com</a> </p>
  <p> 1234 Street, köln </p>
</adress>

> You can find out more about hCards on the websites.  

```html
<p>It was the <del>worst</del> <ins>best</ins> idea  she had ever had.</p>
```
<p>It was the <del>worst</del> <ins>best</ins> idea  she had ever had.</p>

The `<s>` element indicates something that is no longer accurate or relevant (but that should not be deleted).  

```html
<p>Laptop computer:</p> <p><s>Was $995</s></p> <p>Now only $375</p>
```
Result:
<p>Laptop computer:</p> <p><s>Was $995</s></p> <p>Now only $375</p>

The definition list is created with the `<dl>` element and usually consists of a series of terms and their definitions. Inside the `<dl>` element you will usually see pairs of `<dt>` and `<dd>` elements. Definition lists are used to define terminology.   

```html
<dl> 
  <dt>Sashimi</dt> 
  <dd>Sliced raw fish that is served with condiments such as shredded daikon radish or ginger root, wasabi and soy sauce</dd> 
  <dt>Scale</dt> 
  <dd>A device used to accurately measure the weight of ingredients</dd> 
  <dd>A technique by which the scales are removed from the skin of a fish</dd> 
</dl>
```
Result:
<dl> 
  <dt>Sashimi</dt> 
  <dd>Sliced raw fish that is served with condiments such as shredded daikon radish or ginger root, wasabi and soy sauce</dd> 
  <dt>Scale</dt> 
  <dd>A device used to accurately measure the weight of ingredients</dd> 
  <dd>A technique by which the scales are removed from the skin of a fish</dd> 
</dl>

To reach parent folder `<a href="../index.html">Home</a>`  

If you want a link to open in a new window, you can use the `target` attribute on the opening `<a>` tag. The value of this attribute should be `_blank.`

`<a href="http://www.imdb.com" target="_blank"> Internet Movie Database</a>`  

Before you can link to a specific part of a page, you need to identify the points in the page that the link will go to.  

`<p><a href="#top">Top</a></p>`  

For example, to link to the bottom of the homepage of the website you would write: `<a href="http:/www.beratyilmaz.com/#top">`  

You can also use the `title` attribute with the `<img>` element to provide additional information about the image.  

eine
zwei
drei