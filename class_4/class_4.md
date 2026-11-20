## Class_4 - Fonts & Display

### <ins>The Display Property-

> The CSS display property is used determine whether an element is treared as a block/inline element & the layout used for its children.

### 1. display: inline

Takes only the space required by the element. No linebreaks before and after setting (width/height) and (top-bottom margin/padding) not allowed.

### 2. display: block

Takes full space available in width and bears a newline before and after the element.

### 3. display: inline-block

Similar to inline but setting height, width, margin and padding is allowed. Elements can sit next to each other.

### 4. display: none vs visibility: hidden

With **display: none** , the element is removed from the document flow. Its space is not blocked.

With **visibility: hidden** , the element is hidden but its space is reserved.

### <ins>Text Properties-

### 1. text-align property-

Used to sit the horizontal alignment of text.

```html
<style>
    .box1{
        text-align: center;
    }
    </style>
```

### 2. text-decoration property-

Used to decorate the text. Can be **overline**, **line-through**, **none**

### 3. text-transform property-

Used to specify uppercase and lowercase letters in a text.

```html
<style>
    p{
        text-transform: lowercase;
    }
    </style>
```

### 4. line-height property

Used to specify the space btw lines.

```html
<style>
    p{
        line-height: 11px;
    }
    </style>
```

### <ins>Font-

> Font plays a very important role in the look and feel of a website.

### 1. font-family -

font family specifies the font of a text. Can hold multiple values as a **"fallback"** system.

```html
<style>
    p{
        font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    }    /* if fonts have spaces -> use quotes */
    </style>
```

**To get Google Fonts, use this link** -> [Google Fonts](https://fonts.google.com/)

- Select Your Favourite Font
- Tap on **Get Font**
- Then choose **Get embedded Code**
- Copy header link
- Copy CSS style **("font-family")**

### 2. Other Font properties-

> Some of the other font properties are listed below-

I. `font-size` -> Sets the size of the font

II. `font-style` -> Sets font style

III. `font-variant` -> Sets whether the text is displayed in small-caps

IV. `font-weight` -> Sets the weight of the font

### 3. Generic families-

Broad class of similar fonts eg **Serif**, **Sans-Serif** just like when we say fruit, it can be any fruit. When we say Serif it can be any Serif font.
