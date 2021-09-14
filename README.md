# Flexbox-Simplified-Learning

## 07 - the flex container

Display `block` and `inline` are outer display values. They change how the elements interacts with the element that are around it i.e their siblings. By setting display property as `flex` it changes the elements in it's children. The element itself will be displayed as block and it's children will be affected. On doing display as `inline-flex` it will change it's outer behaviour as inline and it's children as flex-items.

## 08 - the flex items- part 1

For the flex items, it doesn't matter whether it's display is block element or inline element or inline-block element. The display properties of flex-items are not taken into consideration.

## 09 - the flex items- part 2

When elements are flex items, they will shrink to fill the content which is inside of them. In an ideal world, they(flex-items) want all their content in one line. How will they shrink is difficult to predict and unintuitive.

## 10 - the flex items- part 3

By default, width of flex-item is `auto`. If the width of each of them is 100%, they will try to adjust in way that each of them get's proper equal width. When their size is too big to fit in the container, they will shrink down. They will equally distribute the spacing no matter what the content is. Content inside flex-items will overflow if width is small enough.
Difference between width `auto` and `100%`: https://stackoverflow.com/questions/17468733/difference-between-width-auto-and-width-100-percent and https://www.youtube.com/watch?v=-st14lUQD3U&ab_channel=KevinPowell

## 11 - the flex items- part 4

All the flex-items match in height i.e. their heights are same. If we lower the height of one flex item, only it's height will get lowered. By default, height is `stretched` to match the siblings.
