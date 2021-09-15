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

## 14 - flex-direction basics

When we declare `flex-direction` as row, each flex items will be columns.The main idea here is the flex-container itself is one row and therefore, it's child will be columns for one row. Default `flex-direction` is row.

## 15 - collapsing margins

By default, when we are not in the world of flex, margin collapses so that we don't have double space. Margin doesn't collapse in flex.

## 16 - flex-direction part 2

It is suggested to wrap images inside div. It is also easier to add more content afterwards. `flex-direction` is used to change the order of content. HTML structure is most important. Only use row-reverse or column-reverse if it is atmost necessary.

## 17 - the order property

Only use order if it is atmost necessary. It is possible to change individual order of flex-items. Order property will only work on flex-items. By default order is `zero`. If two items have same order, they will be in the order of their HTML.

## 18 - flex-grow

Only applied to flex-items. Default value of flex-grow is `zero`. Because even though there is space, flex-items won't expand to fill up the leftover space. Negative value in flex-grow property defaults to 1.

## 19 - flex-shrink

Only applies to flex-items. Default value of flex-shrink is `one`. The combination of `width` and `flex-shrink` can be super useful.

## 26 - the basics of flex-basis

The default of flex-basis is `auto`. If flex-basis is not declared or if it's set as auto, flex-items will look at `width` property. If flex-direction property is row, then flex-basis behaves same as width. Flex-basis doesn't look at the width of element, it looks at the size of main axis of it's flex parent.

## 30 - justification-basics

The default value of justify-content is `flex-start`. justify-content is relative to main axis. `space-around` takes all the space and evenly distribute around each items. `space-between` leaves the end item to far left and fat right and distributes the spaces between each item. `space-evenly` distributes the space evenly around each items.
