# CSS3 Program

This folder contains a collection of HTML demonstration projects for learning and practicing CSS3. Each file is a focused example covering selectors, box model, layout, typography, transforms, transitions, animations, and UI effects.

## How to use this folder

- Open any `.html` file in your browser to see the example in action.
- Use the file name and section in this README to understand the primary CSS concept being demonstrated.
- The subfolders contain dedicated demos for pseudo-classes, pseudo-elements, and exercise tasks.

---

## 1. Selectors and Pseudo-class demos

- `01-pseudo-class.html` — introductory pseudo-class demo, likely showing common selectors such as `:hover`, `:active`, `:focus`, and others.
- `combinator-selector.html` — demonstrates combinator selectors such as descendant, child, adjacent sibling, and general sibling selectors.
- `psuedo-class.html` — likely a general overview of pseudo-classes with practical examples.
- `pseudo-class/active.html` — demonstrates the `:active` pseudo-class for buttons or interactive elements.
- `pseudo-class/checked.html` — shows styling form inputs when they are checked using `:checked`.
- `pseudo-class/empty.html` — uses `:empty` to style elements that contain no children or text.
- `pseudo-class/first-last-child.html` — covers `:first-child` and `:last-child` selectors.
- `pseudo-class/firstlast-of-type.html` — covers `:first-of-type` and `:last-of-type` within sibling groups.
- `pseudo-class/focus.html` — shows styling focused inputs and interactive controls using `:focus`.
- `pseudo-class/not.html` — demonstrates the negation pseudo-class `:not()`.
- `pseudo-class/nth-child.html` — shows positional selection using `:nth-child()` patterns.
- `pseudo-class/visited.html` — demonstrates styling visited links with `:visited`.

## 2. Pseudo-elements demos

- `psuedo-elements/before-after.html` — shows `::before` and `::after` to insert generated content and decorative shapes.
- `psuedo-elements/first-line.html` — demonstrates `::first-line` styling for paragraphs or text blocks.

## 3. Typography and text layout

- `08-external-fonts.html` — demonstrates using `@font-face` or external font services to import custom fonts.
- `09-box-sizing.html` — explains `box-sizing` with examples of content-box and border-box calculation.
- `13-word-wrap.html` — shows `word-wrap` / `overflow-wrap` and text breaking behavior.
- `icon fonts.html` — likely demonstrates icon fonts and how to style them with CSS.
- `Pro5-font.html` — exercises on font properties, font families, font weights, and sizes.
- `Pro7-text effect.html` — text styling with shadows, gradients, or decorative effects.
- `var.html` — demonstrates CSS variables (`--custom-property`) and how to use them in text or layout styling.
- `auto-select.html` — covers `user-select` control to enable or disable text selection.
- `Pro12-Userinterface outline.html` — explores focus outlines and accessibility styling.

## 4. Box model, overflow, and UI controls

- `overflow.html` — demonstrates CSS overflow behavior, scrollbars, and clipping.
- `Pro2-Borders.html` — examples of border styles, widths, radii, and border-image effects.
- `Pro3-Backgrounds.html` — demonstrates background colors, images, and gradients.
- `Pro4-Backgroud.html` — likely a second background exercise with advanced background properties.
- `Pro6-Multiple Columns.html` — multi-column layout styling using CSS columns.
- `pro21-table.html` — table styling and layout using CSS properties.
- `dropdown.html` — CSS-only dropdown menu styling and interaction.
- `pageloader.html` — a page-loading animation or spinner UI component.
- `scroll top icon.html` — styling a scroll-to-top icon or button.
- `task.html` — a general task example, likely a small UI component or challenge.
- `class-task.html` — demonstrates class-based CSS styling and task-oriented exercises.
- `task1.html` — a single exercise file inside `tasks/` for CSS practice.

## 5. Flexbox layout demos

- `flex.html` — basic flexbox container and item alignment demo.
- `flex direction.html` — shows `flex-direction` variations: row, column, row-reverse, column-reverse.
- `flex wrap.html` — demonstrates wrapping flex items with `flex-wrap`.
- `flex-basic.html` — introductory flexbox example with core container properties.
- `flex-grow.html` — explains `flex-grow` and how items expand within a row.
- `flex-shrink.html` — shows `flex-shrink` and how items contract in limited space.
- `flex-order.html` — demonstrates reordering flex items with the `order` property.
- `align-item.html` — explains `align-items` for cross-axis alignment inside flex containers.
- `align-content.html` — demonstrates `align-content` for flex lines distribution.
- `align-self.html` — shows how individual flex items override alignment with `align-self`.
- `flex wrap.html` — likely a second flex-wrap example focusing on responsive behavior.
- `blankflex.html` — a blank flex playground for testing flexbox layouts.
- `fiex-direction.html` — probably a typo file focused on `flex-direction` as a second example.
- `flex (2).html` — another flexbox example or advanced flex layout.

## 6. Grid layout demos

- `grid.html` — basic CSS Grid container and item placement.
- `grid position.html` — demonstrates explicit grid positioning and naming grid cells.
- `grid-area.html` — shows `grid-area` for named grid item placement.
- `grid-area (2).html` — a second example of using `grid-area` for layouts.
- `grid (2).html` — another grid layout demo, likely a distinct pattern or design.
- `pro27-grid spanning.html` — demonstrates spanning items across multiple rows/columns.
- `pro28-grid lines.html` — shows explicit line placement using grid line numbers.
- `pro30-minmax function grid.html` — explains the `minmax()` function for responsive grid tracks.
- `pro31-Implict & explict.html` — compares implicit and explicit grid tracks.
- `pro33-Aligning tricks grid items.html` — advanced alignment techniques for grid items.
- `grid basic diagram.png` — a reference diagram image used by grid demos.

## 7. Transforms, transitions, and animation

- `transform.html` — basic `transform` examples such as translate, rotate, scale, skew.
- `translate.html` — specific demo of `translate()` transform behavior.
- `scale.html` — specific demo of `scale()` transform behavior.
- `skew.html` — specific demo of `skew()` transform behavior.
- `matrix.html` — demonstrates `matrix()` transform for combined transforms.
- `perspective.html` — demos 3D perspective and how perspective affects nested elements.
- `animation.html` — introduces CSS animations with `@keyframes` and animation properties.
- `Animation-fill-mode.html` — demonstrates the `animation-fill-mode` property to preserve end state.
- `animation heart.html` — a themed animation example that animates a heart shape or icon.
- `heart animation.html` — a second heart animation demonstration.
- `heart-beats.html` — uses animation timing and scaling to simulate a heartbeat effect.
- `Dancing Animation.html` — a creative animation example with dancing or motion effects.
- `pro20-Animation2.html` — another animation exercise focusing on keyframes and timing.
- `Pro1_Animation.html` — a primary animation exercise, likely the first project in a series.
- `pro22-filter.html` — shows CSS filter effects that can be animated for visual transitions.
- `progress bar using animation.html` — animated progress bar UI using CSS keyframes.
- `overlay image.html` — combines overlays and subtle animation effects over images.
- `parallax effect.html` — a scrolling parallax effect using CSS and perhaps background attachment or transforms.
- `parallax effect with contect.html` — a parallax example with content overlay integrated into the effect.

## 8. Filter, visual effects, and images

- `filter.html` — demonstrates CSS filter properties such as blur, brightness, contrast, and drop-shadow.
- `pro22-filter.html` — additional filter-related exercises or advanced filter combinations.
- `image-rendering.html` — shows the `image-rendering` property and how browser scaling affects images.
- `overlay.html` — creates overlay effects, likely with translucent layers and blend modes.
- `overlay image.html` — overlays applied directly to images for caption or effects.
- `svg.html` — CSS styling applied to inline SVG or SVG image elements.
- `googlemap.html` — likely a styled map embed or a Google Maps-like layout effect using CSS.

## 9. Advanced and interface properties

- `Pro10-userInterface resize properties.html` — demonstrates UI resize controls and `resize` property behavior.
- `Pro10-userInterface.html` — general user interface styling and form controls.
- `Pro11-userInterface box sizing.html` — likely focused on UI layout with `box-sizing` in form elements.
- `Pro12-Userinterface.html` — more interface styling exercises, possibly with buttons, inputs, and menu examples.
- `Pro13-2D Transform.html` — 2D transform examples and interactions.
- `Pro14-2D Transform.html` — second 2D transform exercise.
- `Pro15-2D Transform.html` — another example of 2D transform composition.
- `Pro16-2D Transform.html` — advanced 2D transformation patterns.
- `Pro17-2D Transform.html` — additional transform and design practice.
- `Pro18-3D Transform.html` — 3D transform example for depth and rotation.
- `Pro19-3D Transform.html` — another 3D transform demonstration.
- `Pro23-Userselect.html` — example using `user-select` property to enable or disable text selection.
- `justify-content.html` — demonstrates `justify-content` for main-axis spacing in flex containers.
- `justify and align content.html` — combined layout example showing both `justify-content` and `align-content`.
- `image/` — contains image assets used by the demos; not a code example folder.

## 10. Practice and assessment tasks

- `tasks/task1.html` — a dedicated exercise file for completing a CSS task or challenge.
- `task.html` — likely a broader practice task or mini-project requiring CSS layout and styling.

## Notes on file naming and organization

- Files with `Pro` or `pro` prefixes are likely course projects or structured exercises.
- Files with spaces in names are actual demo pages; opening them in a browser works the same as any `.html` file.
- The `pseudo-class`, `psuedo-elements`, and `tasks` subfolders are focused areas for interactive selectors and exercises.

## Recommended learning path

1. Start with selector and pseudo-class demos.
2. Move into typography, box model, and text layout examples.
3. Explore flexbox and grid layout pages for responsive design practice.
4. Study transforms, transitions, and animation pages for motion design.
5. Finish with UI effects, filters, and problem-solving tasks.

---

## Contact

If you want to extend this collection, add a short description at the top of each HTML file or create a second README inside the relevant subfolder.
