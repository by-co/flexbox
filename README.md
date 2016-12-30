
### Default line alignment
- **main axis** is a row
 -- **start** on left, **end** on right
- **cross axis** is a column
--  **top** on top, **bottom** on bottom

###`justify-content`
main axis alignment

- `flex-start`: Items align to the **start** of the main axis.
- `flex-end`: Items align to the **end** of the main axis.
- `center`: Items align at the **center** of the main axis.
- `space-between`: Items display with equal spacing **between** them.
- `space-around`: Items display with equal spacing **around** them (includes outer edges).

### `align-items`
cross axis alignment

NOTE: *use* `align-self` *for aligning individual items*

- `flex-start`: Items align to the **top** of the cross axis.
- `flex-end`: Items align to the **bottom** of the cross axis.
- `center`: Items align at the **center** of the container.
- `baseline`: Items display at the **baseline** of the container.

### `flex-direction`
direction within a line

- `row`: Default order. Items display in a row.
- `row-reverse`: Items display in row in reverse order (from end to start). Also reverses **start** / **end**.
- `column`: Items display in a column. Sets main axis to column.
- `column-reverse`: Items display in a column in reverse order (bottom to top). Also reverses **top** / **bottom**.

### `flex-wrap`
line wrapping

- `nowrap`: Every item is fit to a single line.
- `wrap`: Items wrap around to additional lines.
- `wrap-reverse`: Items wrap around to additional lines in reverse.

#### Shortcut: `flex-flow`
- `<flex-direction>` `<flex-wrap>`
 - e.g. `flex-flow: row wrap`

### `align-content`
spacing between lines

- `flex-start`: Lines are pushed at the **top** of the container.
- `flex-end`: Lines are pushed at the **bottom** of the container.
- `center`: Lines display at the **center** of the container.
- `space-between`: Lines display with equal spacing **between** them.
- `space-around`: Lines display with equal spacing **around** them.
- `stretch`: Lines are **stretched** to fit the container.

### `order`
manual ordering

- `<integer>`: Weighted rank that determines display order

> Written with [StackEdit](https://stackedit.io/).
> Slightly modified content from [Flexbox Froggy](http://flexboxfroggy.com/).
