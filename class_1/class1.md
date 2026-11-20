# Introduction to CSS

CSS (Cascading Style Sheets) is a standard stylesheet language used to control the visual presentation, layout, and formatting of documents written in a markup language like HTML. It allows web developers to separate content from design, making it easier to maintain and update websites.

**One Point To Remember** -> Use `Firefox` while learning css.

## Class_0 

1. Created first CSS line 

## Class_1

1.  **IDs must be unique. No such two tags can have same IDs..**

```html
<div id="first">
        First 
    </div>
```

2. **One element can have one class, it belongs to that class. More than one elements can belong to single class but every element must have unique id.**

```html
<section class="yellow">
        This is yellow
    </section>
    <section class="red bg-blue">
        This is red and bg-blue
    </section>
```
This is very important to remember..

3. **Three ways to add CSS to HTML**

* `<style>` tag -
```html
<style>
        #first{
            background-color: orange;
        }
        .bg-blue{
            background-color: brown;
            color: white;
        }
    </style>
```

* Inline `<style>` tags -
```html
<div id="second" style="background-color: green;">
        Second
    </div>
```

* External css -

Adding a stylesheet (CSS) to HTML using `<link>` tag

4. **CSS Selector**

A `CSS selector` is used to select an HTML element(s) for styling..

```html
<style>
    h1{
        color: red;
    }
    p{
        color: rgb(31, 31, 171);
    }
    div{
        background-color: aquamarine;
    }
    </style>
```

`Important Notes` :- 

- We can group selectors like this-

```html
<style>
    h1, h2, div{
        color: red;
    }
    </style>
```

- We can use element.class / element#id as a selector like this-

```html
<style>
    p.red{
        color: red;
    }
    </style>
```

- `*` can be used as a universal selector to select all the elements

```html
<style>
    * {
        margin: 0;
        padding: 0;
    }
    </style>
```
- CSS comments is done by 
```html
<style>
    h1{
        /* The background colour is White */
        background-color: white;
    }
    </style>
```