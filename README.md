# Child-Selector
# CSS Styling and Layout Examples

This repository contains various examples of CSS styling and layout techniques, including the use of `nth-child`, `display` properties, and `background-color` manipulation for dynamic styling of HTML elements.

## Example 1: Zig-Zag Boxes

In this example, multiple `div` elements are styled to create a zig-zag pattern with alternating background colors.

- Even-numbered `div` elements are given a green background and moved down using `transform: translateY(30px)`.
- Odd-numbered `div` elements are yellow.

### HTML and CSS Overview:
- Each `div` is styled to be an inline block with a fixed width and height.
- The `nth-child(even)` selector targets even-numbered divs for styling.
- A specific transformation is applied to even `div` elements for the zig-zag effect.

## Example 2: Hide Even Numbers from 1 to 10

This example demonstrates how to hide even numbers from a list of numbers (1 through 10) using CSS.

- Each `span` element represents a number from 1 to 10.
- The `nth-child(even)` selector hides even-numbered spans by setting `display: none`.

### HTML and CSS Overview:
- A simple list of `span` elements is created for numbers 1 to 10.
- The even-numbered spans are hidden by the CSS rule.

## Example 3: Different Color Scheme Based on Child Position

This example contains several `div` elements, each styled differently based on their position using `nth-child`.

### HTML Structure:
- Multiple `div` elements are created in a sequence, each styled with a different color depending on its position in the sequence.

### CSS Rules:
- The `nth-child(6n+1)` rule targets every 6th `div` starting from the first, and applies a green background.
- The `nth-child(6n+4)` rule targets the next 3 `div` elements in the sequence and applies a blue background.

## Example 4: Multiple Div Groups with Conditional Styling

This example contains multiple groups of `div` elements, each styled according to specific child positioning rules.

- Div elements in group `c1` are styled differently for the 1st to 5th child.
- Div elements in group `c2` have different styling for the 1st to 5th child, and so on for other groups.

### HTML Structure:
- Each group of `div` elements is wrapped in its respective class (`c1`, `c2`, etc.), with CSS rules targeting specific children to apply different background colors.

### CSS Rules:
- Each group has specific child `div` elements that are styled with either orange or other colors based on their positions using `nth-child` selectors.

## Example 5: Color-Coded Divs with Row Grouping

This example shows `div` elements grouped into rows and color-coded based on their position within each row.

### HTML Structure:
- The `div` elements are structured in groups, each group containing 6 `div` elements.

### CSS Rules:
- Divs in positions 1 to 3 within each row are given a green background.
- Divs in positions 4 to 6 within each row are given a blue background.
- This pattern is achieved using `nth-child` and simple `background-color` rules.
