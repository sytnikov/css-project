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
  - Icon and emoji styling
  - Adding font awesome icons + styling