# DOM Manipulation

This is a simple web application that demonstrates DOM manipulation using HTML, CSS, and JavaScript. It provides a user interface with five dropdown menus, each of which can change various properties of a target `<div>` element, such as its color, background color, padding, font size, and font weight.

## How It Works

### HTML Structure

- The HTML file (`index.html`) contains a `<div>` element with the id "targetDiv," which represents the target for style changes.
- Five dropdown menus are created using `<select>` elements, each with its own id and a set of `<option>` elements to choose from.
- Event listeners are added to each dropdown to detect changes in their values.

### JavaScript Functionality

- The JavaScript code in the `<script>` section at the end of `index.html` provides the functionality to update the style of the target `<div>` in real-time.
- The `updateStyle` function is defined to read the selected values from the dropdowns and apply them as styles to the target `<div>`.
- Event listeners are attached to each dropdown, so when their values change, the `updateStyle` function is called to update the style properties of the target `<div>`.
- When the user opens the web page, the `updateStyle` function is initially called to set the initial style based on the dropdowns' default values.

### Example Usage

1. Clone or download this repository to your local machine.

2. Open the `index.html` file in your web browser.

3. You'll see the user interface with the dropdown menus and a target `<div>`.

4. Use the dropdown menus to select different styles for the target `<div>`. The styles will be applied in real-time as you make selections.

5. Experiment with changing the styles to see how the DOM manipulation works.

## Customization

Feel free to customize the styles, layout, or add additional features to this example to suit your needs. You can modify the CSS styles in the `<style>` section of the HTML file to change the appearance of the page.

## JavaScript Functionality

The key JavaScript functionality used in this project includes:

- **DOM Manipulation**: The ability to select and modify HTML elements in real-time based on user interactions with dropdown menus.

- **Event Handling**: Event listeners are used to detect changes in the dropdown values and trigger the `updateStyle` function.

- **CSS Styling**: JavaScript is used to modify CSS properties of the target `<div>` element, including `color`, `background-color`, `padding`, `font-size`, and `font-weight`.

