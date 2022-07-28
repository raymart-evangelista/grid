- How do you create several grid tracks of the same size without manually typing each one out?
  - use repeat()

- What is the difference between a static and dynamic size value? 
  - dynamic size values are responsive when the container window changes sizes while static values are not responsive when the container window changes

- How can you assign a grid track a flexible value that changes depending on the remaining space available in the grid?
  - use fractional units (fr)

- How can you assign grid tracks an uneven distribution of the remaining space in a grid?
  - divide grid tracks and use fractional units (fr) instead of static size units

- Which CSS functions will return the smallest or largest value supplied to them?
  -  min() returns the smallest value supplied
  - max() returns the largest value supplied

- Which CSS Grid-only function allows you to supply a minimum and maximum track size that is calculated in realtime?
  - minmax()

- Which global CSS function allows you to supply a minimum, ideal, and maximum value that is calculated in realtime?
  - clamp()

- What attribute of repeat() can be used to fill in as many grid tracks as possible, given certain constraints?
  - auto-fill and auto-fit

- What is the difference between auto-fit and auto-fill?
  - in most cases, the two will work the same
  - auto-fit will keep grid items at max size
  - auto-fill will snap grid items back to their min size once space is available to add another grid item, even if another gird item isn't rendered