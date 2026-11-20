## Class_5 - Size, Position & Lists

> These are mere units for describing size other than `px`. There are `rem`,`cm`, `vw`, `vh` `%` etc.

### Q. What's wrong with pixels?
-> Pixels (px) are relative to the viewing device. For a device with size **1920 X 1080** , 1 px is **1 unit of 1080/1920** .

### A. <ins>Relative lengths-

These units are relative to the other length property. Following are some of the most commonly used **relative lengths** .


1. **em** -> unit relative to the parent font size.

2. **rem** -> unit relative to the root font size (`<HTML>` tag)

3. **vw** -> unit relative to 1 % viewport width .

4. **vh** -> unit relative to 1 % viewport height .

5. **%** -> 

### B. <ins>Min/Max-Height/Width property-

> CSS has a min-height, max-height , min-width & max-width property. If the content is smaller than the min height, min height will be applied.

```html
<style>
    .container{
        background-color: red;
        width: 500px;
        height: 75vh;
        /* min-width: 45vh; */
        /* max-height: 50vh; */
        }
    </style>
```

Similar is the with the other related properties

### C. <ins>Position Properties -

> Used to manipulate the location of an element. Following are the possible values:

- **static** -> The default position: top / bottom / left / right / z-index has ***NO EFFECT*** .

- **relative** -> The top / bottom / left / right / z-index will now work . Otherwise the element is in the flow of document like static .

- **absolute** -> The element is removed from the flow & is relatively positioned to its final no-static ancestor . top / bottom / left / right / z-index works .

- **fixed** -> Just like absolute except the element is positioned relative to the browser window .

- **sticky** -> The element is positioned based on user's scroll position .


### D. <ins>z-index property -

The `z-index` property specifies the stack order of an element .

It defines which layer will be above which in case of overlapping elements .


### E. <ins>List-style property -

The list style property is a shorthand for type , position & image .

```html
<style>
    ul{
        /* list-style: circle; */
        list-style: square inside url('image.jpg');
        }
    </style>
```
