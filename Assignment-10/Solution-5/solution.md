# SOLUTION

#### `justify-items`

- `justify-items` sets the alignment for all items within a grid or flex container.
- The property is applied to the container, and all items within the container will be aligned according to the specified value.

Example:

```css
.grid-container {
  display: grid;
  justify-items: center; /* Center-aligns all grid items horizontally */
}

.grid-item {
  background-color: lightblue;
}
```

In this example, all grid items within the `.grid-container` will be horizontally centered because of the `justify-items: center` property. This alignment applies to all items uniformly.

#### `justify-self`

- `justify-self` sets the alignment for an individual grid or flex item within a container.
- The property is applied to each item individually, allowing different items within the same container to have different horizontal alignments.

Example:

```css
.grid-container {
  display: grid;
}

.grid-item {
  background-color: lightblue;
  justify-self: end; /* Right-aligns this specific grid item */
}
```

In this example, the `justify-self: end` property is applied to a specific `.grid-item`, causing it to be right-aligned within the `.grid-container`. Other grid items within the same container can have different alignment values if desired.

In summary, `justify-items` affects the horizontal alignment for all items in a container, while `justify-self` allows you to set individual alignment for each item within the same container.
