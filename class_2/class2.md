## Class_2

CSS rules -> key:pair with a selector.

We can write CSS rules to change color and set backgrounds..
```html
<style>
    .red{
    background: red;
    color: white;
}

.green{
    background: green;
    color: antiquewhite;
}
    </style>
```

### Types of Color Values-

> Following types most commonly used values in css

1. **RGB** -> specify color using red, green, blue values e.g. (200,98,70)

2. **HEX Code** -> specify color using hex code. e.g. `#ff7180`

3. **HSL(Hue,Saturation,Lightness)** -> specify the color using hsl values e.g. `hsl(8, 90%,63%)`


### The background-color property-

> The CSS background-color property specifies the background color of a container.

```html
<style>
        .brown{
            background-color: rgb(171, 76, 76);
        }
    </style>
```

### The background-image property-

> Used to set an image as the background

```html
<style>
    body{
        background-image: url('github.webp');
    }
    </style>
```
The image may be repeated in X & Y directions.

### The background-repeat property-

> Can be any of- 

1. **repeat-x** -> repeat in _horizontal_ direction
2. **repeat-y** -> repeat in _vertical_ direction
3. **no-repeat** -> image not _repeat_
4. **space** -> repeat without clipping

### The background-size property-

1. **cover** -> fits & no empty space remains
2. **contain** -> fits & image is fully visible
3. **auto** -> display in original size
4. **{{width}}** -> set width & height automatically
5. **{{width}} {{height}}** -> set width & height

### The background-position property-

> Sets the starting position of the background image.

```html
<style>
    body{
        background-position: left top ;
    }
    </style>
```

### The background-attachment property-

> Defines a scrollable/ non-scrollable character of a background img

```html
<style>
    body{
        background-attachment: fixed;
    }
```

### The background shorthand-

> A single property to set multiple background properties.

**SEQUENCE** -> `color` `image` `repeat` `attachment` `position`

```html
<style>
    body{
        background: red url('image.jpg') no-repeat fixed right top;
    }
    </style>
```