## Class_6 - The CSS Flexbox

> Aims at providing a better way to layout align and distribute space among items in a container . 

```html
<style>
.container{
            display: flex;
        }
    </style>
```

### A. flex-direction property -

> Defines the direction towards which items are laid . Can be `row` (default) ,`row-reverse`, `column`, `column-reverse`

### B. flex properties for parent ( flex container ) -

following are the properties for the flex parent -

1. `flex-wrap` - can be wrap , nowrap , wrap-reverse . Wrap items as needed with this property .

2. `justify-content` - Defines alignment along main axis .

3. `align-items` - Defines alignment along cross-axis .

4. `align-content` - Aligns flex container's lines when there is extra space in the cross-axis .


### C. flex properties for the children (flex items) -

following are the properties for the flex children -

1. `order` : controls the order in which the items appear in the flex container .

2. `align-self` : Allows default alignment to be overridden for the individual flex items .

3. `flex-grow` : Defines the ability for a flex item to grow .

4. `flex-shrink` : Specifies how much a flex item will shrink relative to the rest of the flex items .
