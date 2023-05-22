# CSS Project

## Course plan

- A. Fundamental

  1. Intrducution to CSS

  - What is CSS (Cascading Style Sheet)? Why CSS?
  - CSS Rules syntax
  elementSelector {
    propertyName: propertyValue
  }
  - Adding CSS: Inline CSS (in the opening tag, style attribute), Internal CSS (style TAG inside head tag), External CSS (create a .css file with styles and link it using link tag in the head tag)

  2. Selectors & Combinators

  - Element/Tag, Grouping (h1, p), Nested selectors (ul li a), Universal (*)
  - ID selector (#id)
  - Class selector (.className)
  - Attribute (element[attribute="value"])
  - Pseudo class (element:) & Pseudo element (::) selector
  - Child, descendant (all descendants will inherit styles, if you want only a child: #id > element), 
    adjacent (if you want to change the style of one next element: #id + element),
    general (if you want to change the style of all next elements: #id ~ element) sibling selector

  3. Typography

  - Font properties: font-size (1 rem = 16px = 100%), font-weight (400 - normal), font-style, font-family
  - How to use Goole font
  - color: colorName, RGB, Hexa, Important color tool: color picker, flat ui colors, colorhunt
  - Text properties: text-transform, text-decoration, text-indent, letter-spacing, text-shadow, line-height
  - Icon and emoji styling: fontawesome cdn to link the page with fa -> go to fa website and copy the code of the icon, you can create a class and add it to css file
  - Adding font awesome icons + styling

  4. Box model:
  - content, padding, border, margin
  - box-sizing: border-box (to have fixed width, padding and border takes the width from the inside, but not margin)
  - display: inline / block / inline-block (especially useful if you don't margin for inline elements)
  - width (not responsive) vs max-width (responsive)
  - opacity [0, 1], overflow: visible (by default), hidden (overflow part iss invisible), scroll, auto
  - background properties: background-image, background-repeat, background-position, background-attachment, background-size


- B. Advanced

  - Variables (can be used when the styles are the same for different elements; declaring -> :root {--variable: value}; calling color: var(--variable)), filter (for example picture saturation [0, 1] using element:hover pseudo class)
  - Shadow: text and box shadow. box-shadow: x-axis y-axis blur color
  - Layouts
  
  float: make a row in HTML file (.row class) -> float property: left or right, after using it use ::after pseudo element to clear float, content = "", display: table, clear: both
  
  positioning: 'static' is default, if you want to move a child in the parent use 'relative', 'fixed' the spacing is related to the screen, 'absolute' is for the child and parent should have 'relative'-> then you can set child's position

  z-index: to make an order of blocks, for using z-index you need to set position for the element

  flex -> property display: flex; flex-direction: row (by default) / column; gap property for the flex layout; you need to declare flex in a parent section to apply properties for a child; justify-content (left - right), align-items (top - bottom); it's also important to add height property to use align-items
