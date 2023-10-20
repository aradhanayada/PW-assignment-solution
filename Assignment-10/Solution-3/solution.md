# SOLUTION-1

#### `grid-auto-row`

`grid-auto-row` specifies the size of rows that are implicitly created within the grid. You can set its value to any valid CSS size or use the `fr` unit to define the size relative to available space.

```css
.grid-container {
  display: grid;
  grid-template-columns: 1fr 1fr;
  grid-auto-rows: 100px; /* Implicit rows will have a height of 100px */
}

.grid-item {
  background-color: lightblue;
}
```

In this example, we have a grid with two explicit columns (`1fr` each), and any rows that are created implicitly will have a height of 100px. The grid items within this grid will take up space in these implicit rows.

#### `grid-auto-column`

`grid-auto-column` specifies the size of columns that are implicitly created within the grid. Like `grid-auto-row`, you can set its value to any valid CSS size or use the `fr` unit.

```css
.grid-container {
  display: grid;
  grid-template-rows: 1fr 1fr;
  grid-auto-columns: 150px; /* Implicit columns will have a width of 150px */
}

.grid-item {
  background-color: lightblue;
}
```

In this example, we have a grid with two explicit rows (`1fr` each), and any columns that are created implicitly will have a width of 150px. The grid items within this grid will occupy space in these implicit columns.

Both `grid-auto-row` and `grid-auto-column` help in managing the sizing of rows and columns that are not explicitly defined within a CSS Grid layout. They are particularly useful when you want to have consistent sizing for implicitly generated grid areas.
