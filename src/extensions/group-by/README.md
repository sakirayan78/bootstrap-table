# Table group-by

Use Plugin: [bootstrap-table-group-by](https://github.com/djhvscf/bootstrap-table-group-by) </br>
Dependence: [jquery-treetable](https://github.com/ludo/jquery-treetable/) v3.2.0 </br>
You must include the bootstrap-table-group-by.css file in order to get the appropriate style

## Usage

```html
<script src="extensions/group-by/bootstrap-table-group-by.js"></script>
```

## Options

### groupBy

* type: Boolean
* description: Set true to group the data by the field passed.
* default: `false`

### groupByField

* type: String
* description: Set the field that you want to group the data.
* default: ``

## Known issues

### OnSort

* When sort options are set to True the group by is not working properly, for now if these properties are set to True the group by extension will be disabled.