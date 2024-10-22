# CSS Layout Properties Reference

### **Flexbox Properties Table**

| **Property**            | **Description**                                                  | **Values**                                                                                                                                                   |
|-------------------------|------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `display`               | Defines a flex container.                                        | `flex`, `inline-flex`                                                                                                                                        |
| `flex-direction`         | Defines the direction of flex items in the container.            | `row` (default), `row-reverse`, `column`, `column-reverse`                                                                                                   |
| `flex-wrap`             | Controls whether flex items wrap onto multiple lines.            | `nowrap` (default), `wrap`, `wrap-reverse`                                                                                                                   |
| `justify-content`        | Aligns flex items along the main axis (horizontally in row).     | `flex-start`, `flex-end`, `center`, `space-between`, `space-around`, `space-evenly`                                                                          |
| `align-items`            | Aligns flex items along the cross axis (vertically in row).      | `stretch` (default), `flex-start`, `flex-end`, `center`, `baseline`                                                                                          |
| `align-self`             | Overrides `align-items` for a single item.                      | `auto`, `flex-start`, `flex-end`, `center`, `baseline`, `stretch`                                                                                            |
| `align-content`          | Aligns multiple lines of flex items.                            | `stretch` (default), `flex-start`, `flex-end`, `center`, `space-between`, `space-around`                                                                     |
| `order`                 | Changes the order of flex items.                                | Any integer (default is 0)                                                                                                                                   |
| `flex-grow`             | Defines the ability for a flex item to grow.                    | Any number (default is 0)                                                                                                                                    |
| `flex-shrink`           | Defines the ability for a flex item to shrink.                  | Any number (default is 1)                                                                                                                                    |
| `flex-basis`            | Defines the initial size of a flex item.                        | `auto` (default), length (e.g., `20%`, `300px`)                                                                                                              |
| `gap`                   | Specifies the spacing between flex items.                       | Length value (e.g., `10px`, `1rem`)                                                                                                                          |

---

### **CSS Grid Properties Table**

| **Property**                | **Description**                                                  | **Values**                                                                                                                           |
|-----------------------------|------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------|
| `display`                   | Defines a grid container.                                        | `grid`, `inline-grid`                                                                                                                |
| `grid-template-columns`      | Defines the number and size of columns in the grid.              | Length (e.g., `1fr`, `100px`), `repeat()`, `auto-fill`, `auto-fit`, `minmax()`                                                       |
| `grid-template-rows`         | Defines the number and size of rows in the grid.                 | Length (e.g., `1fr`, `100px`), `repeat()`, `minmax()`                                                                                |
| `grid-template-areas`        | Defines named grid areas.                                        | Custom named areas (e.g., `"header header header" "sidebar content content"`)                                                        |
| `grid-column`                | Shorthand for `grid-column-start` and `grid-column-end`.         | Span across columns (e.g., `span 2`)                                                                                                |
| `grid-row`                   | Shorthand for `grid-row-start` and `grid-row-end`.               | Span across rows (e.g., `span 2`)                                                                                                    |
| `grid-area`                  | Shorthand for positioning an item in a grid.                     | `grid-row-start / grid-column-start / grid-row-end / grid-column-end`                                                                |
| `grid-auto-flow`             | Controls how auto-placed items are inserted.                     | `row` (default), `column`, `row dense`, `column dense`                                                                               |
| `grid-auto-columns`          | Defines the size of implicitly created columns.                  | Length (e.g., `100px`, `min-content`, `max-content`, `minmax()`)                                                                     |
| `grid-auto-rows`             | Defines the size of implicitly created rows.                     | Length (e.g., `100px`, `min-content`, `max-content`, `minmax()`)                                                                     |
| `gap`                        | Specifies the space between grid items.                         | Length (e.g., `10px`, `1rem`)                                                                                                        |
| `justify-items`              | Aligns grid items along the inline (horizontal) axis.            | `stretch` (default), `start`, `end`, `center`                                                                                        |
| `align-items`                | Aligns grid items along the block (vertical) axis.               | `stretch` (default), `start`, `end`, `center`                                                                                        |
| `justify-content`            | Aligns the entire grid along the inline (horizontal) axis.       | `start`, `end`, `center`, `stretch`, `space-between`, `space-around`, `space-evenly`                                                 |
| `align-content`              | Aligns the entire grid along the block (vertical) axis.          | `start`, `end`, `center`, `stretch`, `space-between`, `space-around`, `space-evenly`                                                 |
| `place-items`                | Shorthand for `align-items` and `justify-items`.                 | Combines both properties (e.g., `place-items: center stretch`)                                                                       |
| `place-content`              | Shorthand for `align-content` and `justify-content`.             | Combines both properties (e.g., `place-content: center stretch`)                                                                     |