# HTML

11.8.22

 #What we learning today

* What is HTML
* Document Structure
* Basic HTML Tags
* Absolute and Relative Paths
* Link Different Pages
* Semantic Tags

HTML: Hyper Text Markup Language

* not a programming language
* is a markup language
* tells the browser how and where to display content on the web page

## HTML TAGS

* Tags are the way we markup our content

* Tags tell the browser how to position content on the browser and most HTML elements have an opening and closing tag

<tag>content</tag>

* A forward slash indicate a closing tag

* Note: Not all tags need a closing tag.

## DOCUMENT STRUCTURE

### DOCTYPE DECLARATION

* All HTML documents must start with a <!DOCTYPE> declaration
* It is "information" to a browser about what type of document is expected.
* in HTML5, declaration is a simple:
* <html><head><body> are three main component tags in a HTML document.

## BASIC HTML TAGS

### DOCTYPE

* Headings <h1>Largest Headings<h1> to h6
* Paragraphs <p>Paragraph</p>
* Line Break <br?>
* Image <img src="weblink">
* Anchor(Link)<a href="weblink">Google</a>
* List <ul>/<ol> + li (unordered / ordered)

* ! typing this hot key is a shortcut to building a html shortcut.
  
 #ABSOLUTE VS RELATIVE

## ABSOLUTE PATH

* Points to the complete path, could be any link from the internet or for a local file, path all the way from the root directory (Ex: C folder)
e.g. <img src="http://placekitten.com/400/400">
  
## RELATIVE PATH

* Points to another file location wrt current file.
e.g. with reference to current html file e.g. picture is in the img folder/same folder.

## LINKS

 #ID: used to anchor to different section of same page

 #Relative Paths: Used to link different html pages

* target="_blank" attribute in <a> tag makes link opens a new tab

 #SEMANTIC ELEMENTS

* clearly describes a meaning to both browser and developer
* examples of non semantic elements: <div> and <span> - tells us nothing about its content.
* Examples of semantic: <form>, <table> and <article> Clearly defines its content.
* semantic: conveys a meaning
* non semantic: no meaning.

* </article>: defines independent, self contained content. </article>
* </aside> defines content aside from the page content </aside>
* </details> defines additional details that the user can view or hide. </details>
* </figcaption> defines a caption for a <figure> element </figure></figurecaption>
* </figure> specifies self contained content e.g. illustrations, diagrams, photos, code listings, etc. </figure>
* </footer> defines a footer for the document or a section </footer>
* </header> specifies a header for document or section </header>
* </main> specifies main content of a document </main>
* </mark>:defines mark/highlighted text<mark>
* <nav> navigation
* </section>: defines a section in the document
* </summary>
* </time>
  
 #CSS

* Stands for Cascading Style Sheets
* Style sheet language to style different HTML elements
* Helps web developers separate the style from content
* Style of element is defined once and applied everywhere
* Cascading implies, the latest style overrrides the previous definition.

* Style Tag
  * goes into HTML as a <style> </style> same as css

* Selectors
  * Type Selector: Select all elements that have a given node name: h1,p,img, input etc

  * Class Selector: Selects all the elements that have the given class attribute

  * ID Selector: Selects all the elements that have given a id attribute

  * Pseudo Classes: Selects elements based on state information
  *CSS Selectors are how we apply style to different HTML elements
* Declaration: one line (property: value;)
* Declaration format:kebab case: lower case words separated by hyphens.
* selector example h1 { color:blue }` h1 would be the selector, attribute would be color followed by a colon : and the color choice we have.
* Class has higher priority than element class

## Specificity

-the way the browser calculates which style it should apply by assigning a value system to the different types of selectors.

* inline style: 1000 points
* id - 100 points
* class & pseudo class: 10 points
* element - 1 point
* Hence inline styles holds highest priority over id followed by class and pseudo class then the element

 #Types of style sheets
*Inline styling: Style an element inline with the html tag
*Internal style sheet: Style elements in the same html document, requires a style tag
*External style sheet: Styles elements in a separate css file and link to the html document.

## linking css

-'<link rel="stylesheet" href="stylesheet.css">
-rel is relationship to let the browser know what you're linking to, in this case a css. and href is a literal link into the css.

Absolute vs relative units
*Absolute Unit: refers to a fixed size.
-ex: px,cm,mm
*Relative Unit: Changes wrt to a size of the parent element or screen size
-ex:%,em,vw,vh
*<Https://www.w3schools.com/cssref/css_units.asp>
