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

### CSS Height, Width and Max-width, Max-height
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
- position ( relative, fixed, absolute, sticky)

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
- [attribute] have attribute
- [attribute~="value"] selector is used to select elements with an attribute value containing a specified word
- [attribute|="value"] selector is used to select elements with the specified attribute, whose value can be exactly the specified value, or the specified value followed by a hyphen (-).
- [attribute^="value"] selector is used to select elements with the specified attribute, whose value starts with the specified value.
- [attribute$="value"] selector is used to select elements whose attribute value ends with a specified value.
- [attribute*="value"]  selector is used to select elements whose attribute value contains a specified value.

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
- %	    Relative to the parent element

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
- border-bottom-left-radius

### CSS Border Images
- border-image-source	The border-image-source CSS property sets the source image used to create an element's border image.
- border-image-slice	 The border-image-slice CSS property divides the image specified by border-image-source into regions. These regions form the components of an element's border image.
- border-image-width	The border-image-width CSS property sets the width of an element's border image.
- border-image-outset The border-image-outset CSS property sets the distance by which an element's border image is set out from its border box.	
- border-image-repeat (stretch , repeat , round,  space,  round stretch)

### CSS Multiple Backgrounds
- background	
- background-image	
- background-clip	
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

- matrix(n,n,n,n,n,n)	Defines a 2D transformation, using a matrix of six values
- matrix(scaleX(), skewY(), skewX(), scaleY(), translateX(), translateY())
- translate(x,y)	Defines a 2D translation, moving the element along the X- and the Y-axis
- translateX(n)	Defines a 2D translation, moving the element along the X-axis
- translateY(n)	Defines a 2D translation, moving the element along the Y-axis
- scale(x,y)	Defines a 2D scale transformation, changing the elements width and height
- scaleX(n)	Defines a 2D scale transformation, changing the element's width
- scaleY(n)	Defines a 2D scale transformation, changing the element's height
- rotate(angle)	Defines a 2D rotation, the angle is specified in the parameter
- skew(x-angle,y-angle)	Defines a 2D skew transformation along the X- and the Y-axis
- skewX(angle)	Defines a 2D skew transformation along the X-axis
- skewY(angle)	Defines a 2D skew transformation along the Y-axis

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
- align-content

<!-- ### CSS Grid Item
- grid-column
- grid-row
- grid-area (grid-row-start, grid-column-start, grid-row-end , grid-column-end) -->






