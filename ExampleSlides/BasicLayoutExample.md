---
title: Grid Solves This!
hide_toc: true
---

1. Cells in a grid are ARIA structures.
2. That it is, they are containers that may contain anything.
3. Implementations of the grid pattern provide 2-dimensional navigation.
4. Grids support posinset and setsize and screen readers already announce row/column position information.

## The ARIA 1.1grid

1. ARIA 1.0 grid pattern was modeled after spreadsheet-like applications.
2. ARIA 1.1 grid is also a flexible grouping container widget.

## New: Arrow keys may focus contained interactive elements like links and buttons

If a cell contains:
* A single interactive element,
* and the element does not consume arrow keys,
* Place focus on the element instead of the cell, making it directly operable.
