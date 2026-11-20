## Class_3 - CSS Box Model

The CSS box model looks at all the HTML element as boxes.

The box model looks like this-> 

`Content`->`Padding`->`Border`->`Margin`

### Setting with height & width

> We can set width & height in CSS as follows-

```html
<style>
.box{
    height: 400px;
    width: 500px;
}
    </style>
```

**NOTE :-** The total width/height in CSS as follows-

`Total height = height (content) + top/bottom padding + top/bottom border + top/bottom margin`

```html
<style>
    .box{
            height: 400px;
            width: 500px;
            margin: 10px;
            padding: 8px;
            border: 4px solid black;
        }
    </style>
```

TOTAL HEIGHT = 422px (effective height)

- margin: 10px
- padding: 8px
- border: 4px
- content height: 400px

### Margin shorthand-

1. First method-
```html
<style>
    .box{
        margin: 7px 4px 3px 1px;
    }
    </style>
```
**SEQUENCE** `top`->`right`->`bottom`->`left`

2. Second Method-

```html
<style>
    .box{
        margin: 3px 1px;
    }
    </style>
```

**SEQUENCE** `top & bottom`->`right & left`

### Border Shorthand-

```html
<style>
    .box{
        border: 3px solid black;
    }
    </style>
```

**SEQUENCE** `width`->`style`->`color`

### Border radius-

> We can set border radius to create rounded borders

```html
<style>
    .box{
        border-radius: 40px;
    }
    </style>
```

### Margin Collapse-

When two margins from different elements overlap, the eqv. margin is the greater of the two. This is called **Margin Collapse**.

### Box Sizing-

Determines what out of padding and border is included in elements width and height. Can be-
1. content-box
2. border-box

```html
<style>
    .box2{
        border: 3px solid black;
        box-sizing: border-box; 
    }
    </style>
```