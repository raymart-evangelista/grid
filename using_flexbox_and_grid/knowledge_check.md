- When might you use Flexbox over Grid?
  - for Content First Design by working with smallest parts outward, manipulating in one dimension
  - focus on content flow
  - when you want widths/heights of content containers to be determined by the content of the item and shrink and grow according to the inner content and available space
  - when you want to decide how content should behave when there's too much space or not enough space on screen

- WHen might you use Grid over Flexbox?
  - for Layout First Design by working with a specific overall layout and explicit placement of elements in two dimensions
  - Using less media query intervention by using auto layout, minmax(), repeat(), auto-fill, auto-fit
  - focus on precise content placement

- When might you use the two of these tools together?
  - Having an overall Grid layout, and Grid child elements as Flex parents
  - Having an overall Flex layout, and Flex child elements as Grid parents
  - solve complex layouts like a cool card UI