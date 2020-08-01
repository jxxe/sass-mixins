# Sass Mixins
A collection of [Sass Mixins](https://sass-lang.com/documentation/at-rules/mixin) that create features I wish were real CSS features.

### ``gridBorder($position, $gap, $color)``

<img src="https://i.imgur.com/iA5CP8c.png" align="left">
I absolutely love CSS grid, however it makes it a pain to add borders. To so so, you have to use a complicated combination of padding and margins to replicate the built-in `grid-gap` feature *and* make sure that the borders are aligned properly. This mixin uses `::after` pseudo elements to create a border and position it properly in a grid based on its gap.
