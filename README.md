# CSS GRID

[Youtbe Content](https://www.youtube.com/watch?v=HN1UjzRSdBk)

Studying how to organize HTML elements on my Layout with Grid's properties

## Grid
- Are two-dimensional
- We can split both columns and rows
- We can organize the element where ever we want on that

## Grid or Flexbox
- Grid is two dimensional
- Flexbox is one dimensional
- One can complement the other's functionality
- Check which brower isn't ablet to run grid

## Properties
- Containers and items

### Container
- display: grid;
- grid-template-columns; - It'll split the columns
- grid-template-rows; - It'll split the rows;
- grid-gap; - Spacing
     - grid-row-gap; - Spacing between rows
     - grid-column-gap; - Spacing between coluns
- grid-template-areas; - Delimit areas

... more 4 properties to **align**

### Items
- grid-column; - Where it'll be on our columns
    - grid-column-start;
    - grid-column-end;
- grid-row; - Where it'll be on our rows
    - grid-row-start;
    - grid-row-end;
- grid-area; - Where it'll be on area

... more 2 properties to **align**

## Align

There is 6 properties to align:
`justify-content`
`align-content`
`justify-items`
`align-items`
`justify-self`
`align-self`

We can separate them in two groups:
`justify` and `align`
`content`, `items` and `self`

### Justify and Align

We know that grid is two dimensional, so we have an x -axis and y-axis.

The **x-axis** it's the horizontal position, from left to right.

The **y-axis** it's the vertical position, from up to down


### Content, Items and Self

Joining the `justify`, or `align`, with these elements: `content`, `items and `self`; We get our properties.

### Content

`justify-content` and `align-content` allow us to align the grid itself, relative to grid space.

These properties are rare because it's only useful when the grid is smaller than the area (Like when we use px in the grid size).

We have 7 possibles values:
1. start
2. end
3. center
4. stretch - Will stretch to visible width (default when the rows/columns are 100%)
5. space-between
6. space-around
7. space-evenly

### Items

`justify-items` and `align-items` allow us to align the grid items in any space that is possible, in the cell it is in.

### Self

`justify-self` and `align-self` allow us to align the items themselves. But configured in the item's style.