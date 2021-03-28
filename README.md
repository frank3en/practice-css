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

```css
parent-element {
  display: table;
}

siblings {
  display: table-cell;
  vertical-align: middle;
}
```

**`column` attribute which can separate a paragraph in to specified columns**

```css
column-count: 2; // numbers
column-gap: 4rem; // space between gaps
column-rule: 1px solid $color-grey-light-2;
```

**`hyphens` use with <html lang='LANGUAGE'></html>**

add `-` to a word at the end of line.

### MEDIA QUERY

#### BRIEF

- `@media(max-width:xxx)` and `@media(min-width:xxx)` diffs.
- sass mixin to write media query.
- 3 ways to write media query : bad\good\perfect.
- content of `_typography.scss` and `_base.scss`.
- `height:auto` means why card\_\_back not show?

#### DIFF with `max-width` and `min-width`

#### art direction

some key words: `<img srcset />` `<source media srcset />`, desity descriptor, resolution switching.

#### responsive image

key words: `<img> sizes`, `<srcset>`, `width` descriptor.

#### MEDIA (min-resolution) TO load different pics
