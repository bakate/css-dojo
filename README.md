## Colors

Don't get mad, all these properties create the same result.

```
  color: white;
  color: #fff;
  color: #FFFFFF;
  color: #FFFFFFFF;
  color: rgb(255,255,255);
  color: rgb(100%,100%,100%);
  color: rgba(255,255,255,1);
  color: rgba(100%,100%,100%, 1);
  color: hsl(0, 100%, 100%);
  color: hsla(0, 100%, 100%, 1);
  color: transparent;
  color: currentColor;

```

## Display properties
 ```
 inline | block | list-item | inline-list-item | inline-block | flex | inline-flex | grid | inline-grid | table | inline-table | table-row-group | table-header-group | table-footer-group | table-row | table-cell | table-column-group | table-column | table-caption | ruby | ruby-base | ruby-text | ruby-base-container | ruby-text-container 
 | contents | none | flow | flow-root

 ```

## Flexbox


    1. Creation: display
    2. Direction: flex-flow (flex-direction, flex-wrap)
    3. Alignment: justify-content, align-items, align-self, align-content
    4. Ordering: order
    5. Flexibility: flex (flex-grow, flex-shrink, flex-basis)

### Steps

    Add display: flex; to the parent of the elements to be flexed.
    Set flex-direction to horizontal or vertical
    Set flex-wrap to control wrap direction

#### Parent/container properties
1. **justify-content property**

    flex-start
    flex-end
    center
    space-between
    space-around
    space-evenly

aligns flex items along the main axis


2. **align-items**

    flex-start
    flex-end
    center
    baseline
    stretch

aligns flex items along the cross axis


3. **align-content**

    flex-start
    flex-end
    center
    space-between
    space-around
    stretch
    space-evenly

Only applies to multi-line flex containers.

4. **flex-direction** 

    row
    row-reverse
    column
    column-reverse

5. **flex-wrap**

    nowrap
    wrap
    wrap-reverse


#### Child/item properties
1. **flex**

- flex-grow: How to divide the extra space. Non-negative number. default: 1.

- flex-shrink: How to shrink if there's not enough room. Non-negative number. default: 1.

- flex-basis: the starting size before free space is distributed. length value, content or auto . If set to auto, sets to flex item’s main size property.

2. **align-self**
- auto
- flex-start
- flex-end
- center
- baseline
- stretch

3. **order**

## Grid 

#### Properties declared on the parent element
 ```
 display
grid-template-columns
grid-template-rows
grid-template-areas
grid-template (shorthand)
grid-column-gap
grid-row-gap
grid-gap

 ```
alignment of grid items
```
justify-items
align-items
justify-content
align-content
grid-auto-columns
grid-auto-rows
grid-auto-flow
grid

```

fr and repeat()



**fr**
Fraction Unit
describes a fraction of the available space

**repeat()**
repeat notation:
repeat(# of repeats, length)

#### Properties declared on the child element (grid-area)
```
grid-column-start
grid-column-end
grid-column
grid-row-start
grid-row-end
grid-row
grid-area

```
alignment of grid items
```
justify-self
align-self
```

