# practice-css

## BASIC NATOURS OF THE PAGE WITHOUT NPM OR CSS PREPROCESSOR

[GIT🌲](https://github.com/iamfrank3en/practice-css/commit/c24614da0432ee92f11caa2299fb61c04161b9d8)

## INTRODUCTION TO SCSS(SASS)

basic usage of scss, which contains variables, nesting, functions, mixins and extends. And the practice link in codepen is [here](https://codepen.io/frankisss/pen/dyOdrqz?editors=1100)

## WRITE AND COMPILE SASS LOCALLY

## CONVERT THE LENGTH UNIT TO REM

[GIT🌲](https://github.com/iamfrank3en/practice-css/commit/cd16eae667c8eaaf8f1525c1c32d665e0cc97a5e)

## CONVERT CSS TO SCSS WHILE USING BEM(BLOCK ELEMENT MODIFIER)

## CSS ARCHITECTURE

## FRESH KNOWLEDGE

### NAVIGATION-PART

`transform-origin` -> default to center.

`+ selector` direct sibling element

`~ selector` general sibling element might not be the next to it.

==hijack the checkbox== or ==checkbox hack==?

`checkbox:check` and `display:none`

**solid-gradient animation**

`background-position`

`background-size`

**cubic-bezier function**

[bezier function](https://easings.net/)

### POPUP PART

**An anchor is the elements' id, use `<a href="#id"/>` can route to the correspond anchor**

`anchor -> anchor-element:target`

**some attributes can not be animated**

e.g `display:none` --> instead --> `opacity:0; visibility:hidden`;

**Same element can only have ONE `transform` attribute**

use last `transform` overwrite the former one.

**`display:table` can be used to make sibling elements have the same HEIGHT**

```
    parent-element{display:table}

    siblings
        {
            display:table-cell;
            vertical-align:middle;
        }
```

**`column` attribute which can separate a paragraph in to specified columns**

```
    column-count:2; (numbers)
    column-gap: 4rem (space between gaps)
```

**`hyphens` use with <html lang='LANGUAGE'></html>**

add `-` to a word at the end of line.
