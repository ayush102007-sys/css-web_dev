# CSS Learning Repository

A hands-on collection of CSS lessons, examples, and practice files for learning modern webpage styling.

This repository follows a progressive learning path from writing the first CSS rule to building layouts with Flexbox. Each class contains explanation notes and small HTML demos that can be opened directly in a browser.

## Topics Covered

- Adding CSS with external stylesheets, the `<style>` element, and inline styles
- IDs, classes, element selectors, grouped selectors, and the universal selector
- RGB, HEX, and HSL color values
- Background colors, images, repeat, size, position, attachment, and shorthand
- The CSS box model: content, padding, border, and margin
- Margin shorthand and margin collapse
- `border-radius` and `box-sizing`
- Inline, block, and inline-block elements
- Text alignment, decoration, transformation, and line height
- Font families, font size, style, variant, and weight
- Google Fonts
- Relative units such as `em`, `rem`, `vw`, `vh`, and `%`
- Minimum and maximum dimensions
- Static, relative, absolute, fixed, and sticky positioning
- `z-index` and list styles
- Flex containers and flex items
- Flex direction, wrapping, alignment, growth, shrink, and order

## Repository Structure

```text
CSS/
├── class_0/
│   ├── index.html
│   └── style.css
├── class_1/
│   ├── class1.md
│   ├── cssSelectors.html
│   ├── index.html
│   ├── practice_1.html
│   └── style.css
├── class_2/
│   ├── Moon.jpg
│   ├── background.html
│   ├── class2.md
│   ├── color.html
│   ├── github.webp
│   ├── practice_2.html
│   └── style.css
├── class_3/
│   ├── box-sizing.html
│   ├── class_3.md
│   ├── index.html
│   └── practice_3.html
├── class_4/
│   ├── class_4.md
│   ├── index.html
│   ├── otherFontProps.html
│   ├── prac.html
│   ├── practice_4.html
│   └── textProp.html
├── class_5/
│   ├── class_5.md
│   ├── list-style.html
│   ├── min-max-height-width.html
│   ├── position.html
│   └── units.html
└── class_6/
    ├── class_6.md
    └── flex.html
```

## Lesson Guide

| Lesson | Topic | Files |
| --- | --- | --- |
| Class 0 | First CSS stylesheet | [index.html](class_0/index.html), [style.css](class_0/style.css) |
| Class 1 | CSS introduction, methods, selectors, IDs, and classes | [class1.md](class_1/class1.md), [cssSelectors.html](class_1/cssSelectors.html), [practice_1.html](class_1/practice_1.html) |
| Class 2 | Colors and background properties | [class2.md](class_2/class2.md), [color.html](class_2/color.html), [background.html](class_2/background.html), [practice_2.html](class_2/practice_2.html) |
| Class 3 | Box model, margin, border, border radius, and box sizing | [class_3.md](class_3/class_3.md), [index.html](class_3/index.html), [box-sizing.html](class_3/box-sizing.html), [practice_3.html](class_3/practice_3.html) |
| Class 4 | Display, text properties, fonts, and Google Fonts | [class_4.md](class_4/class_4.md), [index.html](class_4/index.html), [textProp.html](class_4/textProp.html), [otherFontProps.html](class_4/otherFontProps.html), [practice_4.html](class_4/practice_4.html) |
| Class 5 | CSS units, dimensions, positioning, z-index, and list styles | [class_5.md](class_5/class_5.md), [units.html](class_5/units.html), [min-max-height-width.html](class_5/min-max-height-width.html), [position.html](class_5/position.html), [list-style.html](class_5/list-style.html) |
| Class 6 | Flexbox containers and flex items | [class_6.md](class_6/class_6.md), [flex.html](class_6/flex.html) |

## How to Use This Repository

1. Clone the repository:

   ```bash
   git clone https://github.com/ayush102007-sys/css-web_dev.git
   cd css-web_dev
   ```

2. Open a lesson folder and double-click any `.html` file to view it in your browser.

3. Use browser developer tools to inspect elements and experiment with the CSS.

4. Read the matching `.md` file for explanations, syntax, and examples.

5. Change values in the examples and reload the page to see the result.

Firefox is especially useful for learning CSS because of its strong developer tools and CSS layout inspection features.

## Practice Workflow

- **Read the notes** before opening the example.
- **Study the HTML structure** and identify the elements being styled.
- **Locate the selector** that targets each element.
- **Change one property at a time** and observe the effect.
- **Use the browser DevTools** to inspect box sizes, margins, padding, and layout behavior.
- **Experiment after completing each lesson** rather than only copying examples.

## Key CSS Concepts

### Three Ways to Add CSS

```html
<!-- Inline CSS -->
<p style="color: red;">Styled text</p>

<!-- Internal CSS -->
<style>
  p {
    color: blue;
  }
</style>

<!-- External CSS -->
<link rel="stylesheet" href="style.css">
```

### The Box Model

```text
Margin
└── Border
    └── Padding
        └── Content
```

```css
.box {
  width: 500px;
  margin: 10px;
  padding: 8px;
  border: 4px solid black;
  box-sizing: border-box;
}
```

### Flexbox

```css
.container {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  align-items: center;
}

.item {
  order: 1;
  flex-grow: 1;
  flex-shrink: 1;
  align-self: flex-end;
}
```

## Recommended Learning Order

1. Add CSS to HTML
2. Learn selectors and the cascade
3. Work with colors and backgrounds
4. Understand the box model
5. Practice display and text properties
6. Learn font styling and Google Fonts
7. Explore units and positioning
8. Build layouts with Flexbox

## Contributing

This repository is primarily intended for personal learning, but improvements are welcome:

- Add comments or clearer examples
- Fix incorrect CSS or HTML
- Add a focused practice exercise
- Improve an explanation in a lesson note

Before submitting a contribution, open and test the affected HTML file in a browser.

## Author

Created by [Ayush](https://github.com/ayush102007-sys).
