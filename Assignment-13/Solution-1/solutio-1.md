## Purpose of `var()` Function in CSS

The `var()` function in CSS serves several key purposes:

1. **Reusable Values**: Custom CSS variables, defined with `--variable-name`, enable you to store values (such as colors, font sizes, or margins) for later reuse. This promotes consistency and allows you to make global style changes by modifying variable values in one place.

2. **Dynamic Styling**: CSS variables can be changed dynamically using JavaScript. This feature is valuable for creating interactive themes or implementing features that require style adjustments based on user input.

3. **Scoped Variables**: CSS variables can be defined at different levels in your styles. When defined at the root level (often within the `:root` pseudo-class), variables are accessible globally. However, you can also define variables within specific rules or selectors, limiting their scope to that context.

4. **Fallback Values**: The `var()` function supports fallback values. This means you can specify a default value that is used when a variable is undefined or not supported by a particular browser, ensuring graceful degradation and compatibility.

Here's an example demonstrating the use of the `var()` function:

```css
:root {
  --primary-color: #3498db;
}

.button {
  background-color: var(--primary-color, #007bff); <!-- Fallback to #007bff if --primary-color is undefined -->
  color: white;
  padding: 10px 20px;
}
