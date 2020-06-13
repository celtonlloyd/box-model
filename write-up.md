# Box Model
### Display Properties
The default display properties of elements can be overwritten using the `display` value. For example, the `p` element which has a block level property can be changed into an inline-block.
`````
  p {
    display: inline;
  }
`````
Other common display properties are block, inline and none, where the latter hides the element.

### The Box Model
According to the box model, every element is a rectangular box and they may include width, height, padding, borders, and margins and they are the key points in understanding the box model.
The actual size of the box can be calculated by adding the padding, border and margin to the given height and width
According to the box model the total width of an element can be calculated using formula:

`marging-left + border-left + padding-left + width + padding-right + border-right + margin-right`

And total height can calculated using the formula:

`marging-top + border-top + padding-top + width + padding-bottom + border-bottom + margin-bottom`