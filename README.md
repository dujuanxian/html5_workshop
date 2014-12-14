##HTML5 New Features

###HTML5 Benefit
  - Semantic
  - Full CSS3 support
  - Local storage
  - Local DB
  - Audio，Video
  - 2D/3D graphics
  - SEO

###HTML5 Element
  - Doctype
  - Meta declaration
  - Script tag
  - Link tag

####Doctype
```sh
<!DOCTYPE html>
```
####Meta
```sh
<meta charset="UTF-8">
```
####Script
```sh
<script src="script.js"></script>
```
####Link
```sh
<link rel="stylesheet" href="style.css">
```

##HTML5 Tag

  - Section
  - Header
  - Footer
  - Nav
  - Main
  - Aside
  - Article
  - Figure/figcaption
  - Time
  
####Section
thematic grouping of content. The theme of each section should be identified, typically by including a heading (h1-h6 element) as a child of the section element

####Header
introductory content for its nearest ancestor sectioning content or sectioning root element. A header typically contains a group of introductory or navigational aids.

####Footer
similar as Header. A footer typically contains information about its section such as who wrote it, links to related documents, copyright data, and the like.

####Nav
links to other pages or to parts within the page

####Main
to wrap the main content of the page, usually all content other than header and footer

####Aside
tangentially related to the content around the aside element, separate from that content

####Article
a complete, or self-contained, composition in a page and that is, in principle, independently distributable or reusable

####Figure/figcaption
a unit of content, optionally with a caption, that is self-contained, that is typically referenced as a single unit from main flow of the document
```sh
<figure>
  <img src="image.jpg">
  <figcaption>my image</figcaption>
</figure>
```

####Time
```sh
<time itemprop="datePublished" datetime="2009-10-09">3 days ago</time>
```

##Tips

####div & section
  - div has no semantic meaning, section does
  - div usually is used as a wrapper for styling
section help construct a document outline, usually contains a heading

####section & article
  - section forms part of something else, article is its own thing
  - A general rule is that section is appropriate only if the element's contents would be listed explicitly in the document's outline

####aside
  - aside within article, aside should be related to that article
  - aside outside article, aside should be specifically related to aside

####header
  - don't overuse header, if your header element only contains a single heading element, leave out the header

####figure
  - not every image is figure, figure is typically referenced as a single unit from the main flow of the document
  - figure can be more than an image

##Reference
  * [w3](http://www.w3.org/TR/2014/REC-html5-20141028/sections.html)
  * [html5doctor](http://html5doctor.com/)
