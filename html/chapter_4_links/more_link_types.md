MORE LINK TYPES
===============

==== Email:
To create a link that automatically starts up the users mail programme you simply use the same method as you would for a normal web link but instead place the desired address there and 'mailto:' at the beginning. For example, if I wanted anyone who pressed on the link to be able to email the Squirrel Clan, this is what Id do:
```html
<a href="mailto:squirrel.clan@nutty.com">Email Squirrel Clan</a>
```
<a href="mailto:squirrel.clan@nutty.com">Email Squirrel Clan</a>

The only difference is the 'mailto:' at the beginning of the 'href'

==== New Window:
To create a link that will open up in a new page again the target attribute "a" is used as normal, but with the addition of 'target= "_blank"'
```html
<a href="http://www.blaaaaaghablagahbooback.com" target="_blank">Blagaboo Website</a>
```
<a href="http://www.blaaaaaghablagahbooback.com" target="_blank">Blagaboo Website</a>

==== Specific part of the same web page:
Links that go to the same page but a specific part (aka 'go to top' etc) need an ID ELEMENT. Once the area of the page you wish your link to go to has been identified, you can then use it for your link. It is important to note, that Id elements should:
  1. NEVER start with a number
  2. MUST be unique
  3. Are allowed to start with either a LETTER or an UNDERSCORE
The way an ID is linked is via using a '#' within the 'href' tag and once that is completed, it works!
```html
<html>
  <head>
  <title>exciting bloody example</title>
  </head>
  <body>
    <h3 id="Top">Once upon a time...</h3>
    <p>here is some bloody text</p>
    <p><a href="#Top">Go to top</a></p>
  </body>
</html>
```
<html>
  <head>
  <title>exciting bloody example</title>
  </head>
  <body>
    <h3 id="Top">Once upon a time...</h3>
    <p>here is some bloody text</p>
    <p><a href="#Top">Go to top</a></p>
  </body>
</html>

==== Specific part of the another web page:
A similar technique is used for when you want to link to a specific part of another web page, so long as there is an ID for that section then once the URL is written out in full, one need only add the '#ID' to the end.
```html
<html>
  <head>
  <title>god this is dull work</title>
  </head>
    <body>
      <p>what link crap am i thinking up now...how about a link to a logo on the bottom of a page? like <a href="http://www.deviantart.com/#deviantART-loves-you">This</a></p>
    </body>
</html>
```
<html>
  <head>
  <title>god this is dull work</title>
  </head>
    <body>
      <p>what link crap am i thinking up now...how about a link to a logo on the bottom of a page? like <a href="http://www.deviantart.com/#deviantART-loves-you">This</a></p>
    </body>
</html>


















