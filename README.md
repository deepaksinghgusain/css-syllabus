# CSS SYLLABUS

## Basic CSS 

### CSS Elements
- The CSS element Selector
- The CSS id Selector
- The CSS class Selector
- The CSS Universal Selector
- The CSS Grouping Selector

### How To Add CSS
- External CSS
- Internal CSS
- Inline CSS

### CSS Comments
- A CSS comment is placed inside the <style> element, and starts with /* and ends with */:

### CSS Color
- by name
- by rgb
- by hsl
- by hex

### CSS Backgrounds
- background-color
- background-image
- background-repeat
- background-attachment
- background-position
- background (shorthand for background)

### CSS Borders
- border-style ( dotted / dashed / solid / double / groove / ridge / inset / outset / none / hidden )
- border-width
- border-color
- border
- border-radius

### CSS Margins
- margin-top
- margin-right
- margin-bottom
- margin-left
- values ( auto /length / % / inherit )
- margin (shorthand)

### CSS Padding
- padding-top
- padding-right
- padding-bottom
- padding-left
- values ( length / % / inherit )
- padding (shorthand)

### CSS Height, Width and Max-width
- height
- width
- max-height
- max-width
- min-width
- min-height
- values ( auto /length / % / inherit / initial)

### The CSS Box Model

### CSS Outline
- outline-style ( dotted / dashed / solid / double / groove / ridge / inset / outset / none / hidden )
- outline-color
- outline-width
- outline-offset
- outline (shorthand)

### CSS Text
- color 
- background-color 
- text-align
- text-align-last
- direction
- unicode-bidi
- vertical-align
- text-decoration-line
- text-decoration-color
- text-decoration-style
- text-decoration-thickness
- text-decoration
- text-transform
- text-indent
- letter-spacing
- line-height
- word-spacing
- white-space
- text-shadow

### CSS Fonts
- font-style
- font-variant
- font-weight
- font-size/line-height
- font-family

### CSS Icons

### CSS Links
- a:link - a normal, unvisited link
- a:visited - a link the user has visited
- a:hover - a link when the user mouses over it
- a:active - a link the moment it is clicked

### CSS Pseudo-elements
- ::first-line
- ::first-letter
- ::before
- ::after
- ::marker
- ::selection

### CSS Lists
- list-style-type
- list-style-image
- list-style-position
- list-style (shorthand)

### CSS Tables
- border 
- border-collapse
- height
- width
- text-align
- padding 
- tr:nth-child(odd/even) 

### CSS Responsive Table
- overflow-x:auto

### CSS Layout - The display Property
- display (none, inline, block, inline-block)

### CSS visibility Property
- visibility(hidden/ visible)

### CSS Layout - The position Property
- position ( static, relative, fixed, absolute, sticky)

### CSS Layout - The z-index Property
- z-index

### CSS Layout - Overflow
- overflow (visible ,hidden , scroll , auto)
- overflow-x and overflow-y

### CSS Layout - float and clear
- float (left , right , none , inherit)
- clear (left , right , none , inherit, both)

### CSS Combinators
- descendant selector (space)
- child selector (>)
- adjacent sibling selector (+)
- general sibling selector (~)

### CSS Opacity / Transparency
- opacity

### CSS Attribute Selectors
- [attribute]
- [attribute~="value"]
- [attribute|="value"] 
- [attribute^="value"]
- [attribute$="value"]
- [attribute*="value"] 

### CSS Units
- cm	centimeters
- mm	millimeters
- in	inches (1in = 96px = 2.54cm)
- px *	pixels (1px = 1/96th of 1in)
- pt	points (1pt = 1/72 of 1in)
- pc	picas (1pc = 12 pt)
- em	Relative to the font-size of the element (2em means 2 times the size of the current font)	
- ex	Relative to the x-height of the current font (rarely used)	
- ch	Relative to width of the "0" (zero)	
- rem	Relative to font-size of the root element	
- vw	Relative to 1% of the width of the viewport*	
- vh	Relative to 1% of the height of the viewport*	
- vmin	Relative to 1% of viewport's* smaller dimension	
- vmax	Relative to 1% of viewport's* larger dimension	
- %	Relative to the parent element

### CSS The !important Rule
- !important

### CSS Math Functions
- calc()
- max()
- min()

## Advanced CSS

### CSS Rounded Corners
- border-radius	
- border-top-left-radius	
- border-top-right-radius	
- border-bottom-right-radius	
- border-bottom-left-radiuss

### CSS Border Images
- border-image	
- border-image-source	
- border-image-slice	
- border-image-width	
- border-image-outset	
- border-image-repeat

### CSS Multiple Backgrounds
- background	
- background-clip	
- background-image	
- background-origin	
- background-size

### CSS Colors
- RGBA Colors
- HSLA Colors

### CSS Gradients
- background-image: linear-gradient(direction, color-stop1, color-stop2, ...)
- background-image: radial-gradient(shape size at position, start-color, ..., last-color)
- background-image: conic-gradient([from angle] [at position,] color [degree], color [degree], ...)

### CSS Shadow
- CSS Shadow Effects ( text-shadow, box-shadow )

### CSS Text Effects
- text-overflow
- word-wrap
- word-break
- writing-mode

### CSS 2D Transforms
- transform (translate() / rotate() / scaleX() / scaleY() / scale() / skewX() / skewY() / skew() / matrix())

### CSS 3D Transforms
- transform  (rotateX() / rotateY() /rotateZ())

### CSS Transitions
- transition
- transition-delay
- transition-duration
- transition-property
- transition-timing-function ( ease linear ease-in ease-out ease-in-out cubic-bezier(n,n,n,n))

### CSS Animations
- @keyframes
- animation-name
- animation-duration
- animation-delay
- animation-iteration-count
- animation-direction
- animation-timing-function
- animation-fill-mode
- animation

### CSS The object-fit Property
- object-fit (fill / contain / cover / none / scale-down) 
- object-position

### CSS Box Sizing
- box-sizing (border-box)

### CSS Media Queries
- @media not|only mediatype and (expressions) {
-   CSS-Code;
- }

- @media screen and (min-width: 480px) {
-   body {
-     background-color: lightgreen;
-   }
- }

### CSS Flexbox
- flex

### CSS Flex Container
- flex-direction
- flex-wrap
- flex-flow
- justify-content
- align-items
- align-content

### CSS Flexbox item
- order
- flex-grow
- flex-shrink
- flex-basis
- flex
- align-self

### CSS Flex Responsive
-  flex

## CSS Grid Layout Module

### CSS Grid Container
- grid 
- inline-grid.
- grid-template-columns
- grid-template-rows
- justify-content
- align-content

### CSS Grid Item
- grid-column
- grid-row
- grid-area (grid-row-start, grid-column-start, grid-row-end , grid-column-end)






