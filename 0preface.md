## Preface
---
Scalable Vector Graphics (SVG to its friends) has many applications. It is used by graphic designers and by technical drafters. But this book is specifically about its use in web design and development.

Using SVG with CSS3 and HTML5 is, essentially, using SVG on the web. But more than that, it’s about using SVG in complex web applications. This is SVG not only as illustrations, but as graphical documents that can be integrated in HTML web pages, and styled with custom CSS. Many chapters will be useful to designers creating images for the web, but the focus is on developers who are adapting designs to add data-based graphics, dynamic styles, interaction, or animation.

### A Winding Path

This book traces its origins to 2011, when Kurt started work on a book called HTML5 Graphics with SVG and CSS3. At the time, HTML5 and CSS3 were brand new, and SVG was just starting to get decent support in web browsers.

But life, as it often does, got in the way. The book took much longer than planned to complete. And time introduced its own complications.

When Kurt handed off the manuscript to Amelia in late 2014, the state of graphics on the web had changed considerably since when he’d started it. HTML had acquired competely new graphics formats (the Canvas2D API and WebGL), which were completely separate from SVG and CSS. And CSS3 was becoming a bigger and bigger topic every year, quickly outgrowing the one chapter planned for it.

So the decision was made to focus on SVG. However, this book is still all about the intersection of the three web languages—and JavaScript, too! The driving goal for the rewrite was to create a practical guide to using SVG on the web, in complex web pages, with full awareness of the need for cross-browser, multidevice support.

That turned out to be easier said than done. It’s taken a few more years (and one more coauthor, Dudley) to complete this manuscript. It’s also a considerably larger book than initially planned. We hope it was worth the wait.

### The Road Ahead

SVG is a complex topic, but we have tried to arrange this book in a logical progression. Part I begins with the wide view, discussing how—and why—you use SVG in web design:

- The possibilities of SVG as an independent image format, in Chapter 1

- SVG on the web, with a focus on how it interacts with other coding languages, in Chapter 2

- How CSS can be used to style your SVG, and how SVG graphics can be used with CSS to style other documents, in Chapter 3

- Useful software for creating and testing SVG images, as well as some sources of ready-to-use SVG for less artistically inclined web developers, in Chapter 4

The remainder of the book will narrow in on each of the main features of SVG one chapter at a time. Part II concentrates on the core drawing elements in SVG, and how to control their geometry and layout:

- Sizing and positioning basic shapes, in Chapter 5
- Defining custom shapes and lines, in Chapter 6
- Text layout, in Chapter 7

Part III dives into the technical details of how SVG documents are constructed and how vector shapes are positioned:

- Establishing coordinate systems and scale, in Chapter 8

- Redefining coordinate systems when embedding graphics in web pages, in Chapter 9

- Reusing content and embedding images, in Chapter 10

- Transforming coordinate systems to reposition and distort graphics, in Chapter 11

Part IV focuses more on the graphical side of the language:

Filling the area of shapes and text, including gradients and patterns, in Chapter 12

- Drawing outlines around shapes and text, in Chapter 13

- Adding line markers (repeated symbols on the ends or corners of custom shapes), in Chapter 14

- Clipping and masking of graphics, in Chapter 15

- Filter effects and blend modes, in Chapter 16

Part V looks at how the basic structure of SVG images can be enhanced to create complete web applications, focusing on three main areas:

- Accessibility and metadata, in Chapter 17

- Interactive SVG, links, and event handling, in Chapter 18

- Animation using CSS, XML, or JavaScript, in Chapter 19

Once you have all the pieces in place, Chapter 20 returns to the big picture, discussing best practices for working with SVG.

### Before You Begin
This book focuses on “using SVG” in web pages. It assumes that you, the reader, are already familiar with creating web pages using HTML, CSS, and a little bit of JavaScript. When the examples use relatively new features of CSS3 and HTML5, we’ll explain them briefly, but we’ll assume you know a \<div\> from a \<li\>, and a font-family from a font-style.

You’ll get the most out of the book by working through the code samples as you go. It will help if you have a good code editor that recognizes SVG syntax, and if you know how to use the developer tools in your web browser to inspect the document structure and styles that create the visible result.