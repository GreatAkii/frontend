# Grid

## Grid container properties

- `grid-template-columns` - defines the number of columns in the grid, and their size
- `grid-template-rows` - defines the number of rows in the grid, and their size
- `grid-auto-columns` - defines the size of the columns that are not explicitly defined
- `grid-auto-rows` - defines the size of the rows that are not explicitly defined
- `justify-content` - aligns the entire grid along the row axis
- `justify-items` - aligns the grid items along the row axis
- `align-content` - aligns the entire grid along the column axis
- `align-items` - aligns the grid items along the column axis

### grid-template-columns

`grid-template-columns: <track-size> | <line-name> | <track-size> <line-name> | ...`

### grid-template-rows

`grid-template-rows: <track-size> | <line-name> | <track-size> <line-name> | ...`

### grid-auto-columns

`grid-auto-columns: <track-size>;`

### grid-auto-rows

`grid-auto-rows: <track-size>;`

### justify-content

`justify-content: start | end | center | stretch | space-around | space-between | space-evenly;`

### justify-items

`justify-items: start | end | center | stretch;`

### align-content

`align-content: start | end | center | stretch | space-around | space-between | space-evenly;`

### align-items

`align-items: start | end | center | stretch;`

## Grid item properties

- `justify-self` - aligns the item along the row axis
- `align-self` - aligns the item along the column axis
- `grid-column-start` - specifies the start position of the item in the grid
- `grid-column-end` - specifies the end position of the item in the grid
- `grid-column` - specifies the start and end position of the item in the grid
- `grid-row-start` - specifies the start position of the item in the grid
- `grid-row-end` - specifies the end position of the item in the grid
- `grid-row` - specifies the start and end position of the item in the grid
- `grid-area` - specifies the start and end position of the item in the grid
- `grid-template-areas` - defines the layout of the grid

### justify-self

`justify-self: start | end | center | stretch;`

### align-self

`align-self: start | end | center | stretch;`

### grid-column-start

`grid-column-start: <line>;`

### grid-column-end

`grid-column-end: <line>;`

### grid-column

`grid-column: <start-line> / <end-line>;`

### grid-row-start

`grid-row-start: <line>;`

### grid-row-end

`grid-row-end: <line>;`

### grid-row

`grid-row: <start-line> / <end-line>;`

### grid-area

`grid-area: <row-start> / <column-start> / <row-end> / <column-end>;`

### grid-template-areas

`grid-template-areas: "<name1> <name2> <name3>" "<name4> <name5> <name6>";`
