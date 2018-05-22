# ipm package: searchable-data-table

## Overview

Using DataTable.net framework to visualize, search, and filter ClearBlade Collections.

This is an ipm package, which contains one or more reusable assets within the ipm Community. The 'package.json' in this repo is a ipm spec's package.json, [here](https://docs.clearblade.com/v/3/6-ipm/spec), which is a superset of npm's package.json spec, [here](https://docs.npmjs.com/files/package.json).

[Browse ipm Packages](https://ipm.clearblade.com)

## Setup

_No setup required_

## Usage

To customize, edit the Data Table widget in the `DataTableDemo` Portal:

### HTML

Update HTML Headers for each column

~~~html
<tr>
	<th>Item ID</th>
	<th>Route Name</th>
	<th>My Custom Column</th>
</tr>
~~~

### JS

Define which columns to display in `COLUMN_MAP`:

```js
var COLUMN_MAP = [{
        "data": "item_id",
        "visible": false,
        "searchable": false
    },
    {
        "data": "<YOUR_CUSTOMIZED_COLUMN_NAME>",
        "searchable": true
    },
```

## Assets

### Portals

- `DataTableDemo` - Visualizing a Collection using the Data Table 

### Collections

- `routes` - Example data for bus routes

## API

[https://datatables.net/](https://datatables.net/)
