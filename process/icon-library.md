#Icons
  - An icon is a composition of one or more symbols and zero or more frames, and is built using the icon library built in both javascript and ruby.
  - Because icons are rendered as inline svg markup, they can be targeted with css, and so are styled that way.

##Symbol 'rules'
- All symbols should be 24x24, but no points in the icon should be any closer than 0.5 from the edge (ie. all points' x and y coordinates should fall between 0.5 and 23.5)
- If an icon is square, it should be as large as possible while satisfying the above rule
- If an icon is not square, it should fill the available space on its long axis, and be centered in the space along its smaller axis.
- Symbol code should contain no transformations - tranformations should be 'expanded' to alter the actual attributes of the sub-symbol elements
- The icon scss will apply the defaults of `stroke-linejoin: round;` & `stroke-miterlimit: 10;`, so these attributes should be excluded unless you'd like to apply something different than the default.
- Symbols should have no stroke, fill, or stroke-width attributes. These will be applied by the icon scss.
- Every element in a symbol must have one of three classes applied to it: 'line', 'outline', or 'shape'.
  - the 'line' class should be applied to elements that should never have a fill. 
  - the 'outline' class should be applied to elements that may be displayed as either a simple outline, or with a fill of the same or a different color.
  - the 'shape' class should be applied to elements that should always be filled.
  - a good example is the 'lock-closed' icon. The box of the padlock is an outline, the bolt is a line, and the keyhole is a shape.
- If there is more than one element in an icon, each should have a unique id class beginning with 'shape' 'line' or 'outline'. For example, in the lock icon, the classes will be 'shape shape-keyhole', 'outline outline-pad', 'line line-bolt'. 
  This ensures that individual elements can be targeted with css.

##Adding a symbol
- Create the svg code you'd like to use (you only want the 'guts' of the svg, so do not include the <svg> and </svg> tags)
- Add your code to a file in source/components/icons/symbols/ and name it for the concept that the icon is intended to represent, _not_ what the icon looks like.
- Add the name of your icon to icons.json in the source/styleguide/components.
- Clear the symbol or symbols you'd like to add with Jun.

##Adding a frame
- Ask Kara.
