# Flexbox Cheat Sheet
 *Sometimes, it can be tricky to remember all the different possibilites that Flexbox has to offer. I decided to create this sheet that will allow you to quickly reference different terms and techniques.*

## `justify-content`
`justify-content` allows you to move items *horizontally* across the container. Here are a few specific commands. To use them,
type `justify-content:<INSERT COMMAND HERE>;`. 

- `flex-start`: Places items on the left side of the container. This is usually the starting position.
- `flex-end`: Place items on the right side of the container. 
- `center`: Places items in the center.
- `space-between`: Items are placed equidistant from each other. (NOTE: The space in-between the items is the same.)
- `space-around:`: Items are spaced with the same distance around each other. (NOTE: The space on the outside of the items is the same.)

## `align-items`
`align-items` allows you to move items *vertically* across the container. Here are specific commands. Follow the same syntax as `justify-content`
when entering these commands in.

- `flex-start`: Places items at the top of the container. This is usually the starting position.
- `flex-end`: Places items at the bottom of the container.
- `center`: Aligns items at the vertical center of the container.
- `baseline`: Items are aligned along the baseline of the container.
- `stretch`: Items get stretched apart to fill the container.

## `flex-direction`
`flex-direction` allows you to change the direction that items are placed in. Same syntax as the previous two terms.

- `row`: Items are placed in a row.
- `row-reverse`: Items are placed in the opposite direction in a row.
- `column`: Items are placed top to bottom.
- `column-reverse`: Items are placed from bottom to top.

## `order`
This command allows you to specify the order that items should be placed in. You enter `order: <INTEGER>;` to specify order. This command
is usually used in item-specific classes. The integer provided can be positive or negative. Items have a default order of 0 to begin.

## `align-self`
This command accepts the same values as `align-items` but is used in item-specific classes to specify a specific items position, as opposed to
all items.

## `flex-wrap`
This command defines how items wrap around the container (if at all.) Follow the same syntax structure as before.

- `nowrap`: Items are placed on a single line.
- `wrap`: Items wrap to multiple lines.
- `wrap-reverse`: Items wrap to multiple lines in the opposite order.

## `flex-flow`
This command combines both `flex-direction` and `flex-wrap` into one command. The syntax is `flex-flow: <ROW> <WRAP>`.

## `align-content`
This command allows you to specify how rows are placed in the container. Follow same syntax style.

- `flex-start`: Rows are placed at the top of the container.
- `flex-end`: Lines are placed at the end of the container.
- `center`: Lines are placed at the vertical center of the container.
- `space-between`: Lines are placed with equal spacing between them.
- `space-around`: Lines are placed with equal spacing around them.
- `stretch`: Lines are placed to fill the container.

### And that's flexbox!
