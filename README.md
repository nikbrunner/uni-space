# 📐 uni-space

A tiny set Scss | Sass variables for unified box spacing.

This is in very early stage.

## Basic idea

```scss
$space: 5vmax;
$space-expansion: 1;

$space-xxs: calc((#{$space} / 8) * #{$space-expansion});
$space-xs: calc((#{$space} / 4) * #{$space-expansion});
$space-s: calc((#{$space} / 2) * #{$space-expansion});
$space-m: calc((#{$space} * #{$space-expansion}));
$space-l: calc((#{$space} * 2) * #{$space-expansion});
$space-xl: calc((#{$space} * 4) * #{$space-expansion});
$space-xxl: calc((#{$space} * 8) * #{$space-expansion});
```
