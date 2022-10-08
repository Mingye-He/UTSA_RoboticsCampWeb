<center>
# Attributes
</center>
- attributes are code inside HTMl elements that gives more information about the specific elements

## `SRC` Attribute
- `src` specifies the path to something
- for example: in `<img>` tag, src specifies the path to find the image

		<img src = " image link " >

## alt Attribute
- `alt` attribute is the alternate text that will show up if something fails
- for example: if the link of an image in the src attribute doesn't working or exist, instead the text written in the alt attribute will show up. Normally, the text in the alt attribute would be put there to describe what the image is supposed to be.
- It is used as a backup

		<img src = " image link " alt = " describes the image " >

## rel Attribute
- used for specifying the relationship between current document and other linked documents
- must be use with the `href` attribute
- attribute can be used in `<link>`, `<a>`, `<area>`, `<form>`

		<a rel = "value">

<img src = "https://www.dropbox.com/s/3zu84anr8p7oyhe/rel%20attribute%20values%20.png?raw=1">

		<a rel = "stylesheet" href = "style.css">
- stylesheet value specifics that the stylesheet file will be loaded into the current page.


## ID Attribute
- id is only used to identify one single element
- cannot be used to identify two of element as the same
		<div id = "specific id">

## The Class Attribute
- used to specifies more than one class names of an elements
- Class name cannot start with number
- allows for CSS and Javascript to reference a specific elements
- difference HTML elements can have the same class name

		<div class = "class name">
