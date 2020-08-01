# Sass Mixins
A collection of [Sass Mixins](https://sass-lang.com/documentation/at-rules/mixin) that create features I wish were real CSS features.

### ``gridBorder($position, $gap, $color)`` - Add borders to grid

I live CSS grid, however it is a pain to add borders. To do so, you have to use a complicated combination of padding and margins to replicate the built in `grid-gap` feature *and* make sure that the borders are aligned properly. My mixin uses `::after` pseudo elements to create a border and position it properly in the grid based on its gap.
