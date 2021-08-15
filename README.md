# CSS

## Normal Flow
- **block:** uses the whole line. The next element will go to the next line.
- **inline:** uses only the required width for the the component in the line. The next element will keep in the same line.


## Table
```html
<table>
  <tr>
    <td>A</td>
    <td>B</td>
  </tr>
  <tr>
    <td>1</td>
    <td>2</td>
  </tr>
</table>  
```

## Tableless
- **float:** left, right.
- **clear:** both.

## [Flex-box](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
- **Flex Container:** parent element.
  - **display:** flex
  - **justify-content**: flex-start | flex-end | center | space-around | space-between | space-evenly.
  - **align-items**: stretch | flex-start | flex-end | center.
  - **flex-direction**: row | row-reverse | column | column-reverse.
  - **flex-wrap:** nowrap | wrap | wrap-reverse.
  - **flex-flow** (flex-direction + flex-wrap): can use 1 or 2 properties.
  - **gap**: 2px | 2pt | 2em  | 2rem | 2%.

- **Flex Item:** child element.
  - **flex-basis:**  auto | 25px | 25% | 0.
  - **flex-grow:** 0 | 1 | 2 | 3.
  - **flex-shrink:** 1 | 0 | 2 | 3.
  - **flex** (grow + shrink + basis): 1.
  - **order:** 1, 2, 3.

- **Nesting:** set one element (div) inside the other.

- **Axis:** 
  - main (justify-content): start, end
  - cross (align-items): start, end  

- **Flex-sizing:**
  - flex: 1
  - 


# Equivalents
```
<DIV></DIV>
```
```
<View></View>
```

```
<Text>Texto</Text>
```
