# HTML - Meta tag
 - stands for metadata
 - always goes inside a <head> elements

		<meta charset = "utf-8">

 - normally used to specified character set.
- charset - character set
- utf- 8 is a specific character

## Meta viewport 
- Tells the browser that the width of the screen should be consider the full width of the page.

		<meta name = "viewport" content = "width=device-width, inital scale=1>

## device-width
- width or height
: controls to width or height of the viewport 
  - Range: Min: 1 Max: 10000
  - Negative Values are ignore

- device-width / device-height
: 100% of the viewport width/height
- initial scale
: controls the zoom level when the page is first loaded
  - Range: o.1- 10
  - Default is 1
- <a href = "https://developer.mozilla.org/en-US/docs/Web/HTML/Viewport_meta_tag#screen_density"> Reference Website</a>