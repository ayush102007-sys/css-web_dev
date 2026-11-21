## Class_7 - CSS Grid & Media Queries 

> A CSS grid can be initialised using -

```html
<style>
    .container{
        display: grid;
    }
    </style>
```

All direct children automatically becomes **grid itmes** .

### A. The grid-column-gap property -

> Used to adjust the space btw the columns of a CSS grid .

### B. The grid-row-gap property -

> Used to adjust the space btw the rows of a CSS grid .

### C. The grid-gap property -

> Shorthand property for grid-row-gap & grid-column-gap .

```html
<style>
    .container{
        display: grid;
        grid-gap: 40px (row) 100px (column);
    }
    </style>
```

**NOTE** :- ` For a single value of grid-gap, both row & column gaps can be set in one value . `


<hr>

**Following are the properties for grid container :**

- > The **grid-template-columns** property can be used to specify the width of columns :

```html
<style>
    .container{
            display: grid;
            grid-template-columns: 80px 100px auto ;
        }
    </style>
```

- > The **grid-template-rows** property can be used to specify the height of each row :

```html
<style>
    .container{
            display: grid;
            grid-template-rows: 70px 150px ;
        }
    </style>
```

- > The **justify-content property** is used to align the whole grid inside the container .

- > The **align-content property** is used to vertically align the whole grid inside the container .

**Following are the properties for grid item :**

- > The **grid-column** property defines how many columns an item will span .

```html
<style>
    .grid-item{
        grid-column: 1 / 3;
    }
    </style>
```

- > The **grid-row** property defines how many row an item will span .

```html
<style>
    .grid-item{
        grid-row: 1 / 3;
    }
    </style>
```

- > We can make an item to start on column 1 & span 3 columns like this :

```html
<style>
    .grid-item{
        grid-column: 1 / span 3;
    }
    </style>
```


### <ins>CSS Media Queries :-

> Used to apply CSS only when a certain condition is true.

```html

```