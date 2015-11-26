# Get Adjacent Row : a DataTable plugin

This simple plugin works with the new API of the jQuery [DataTables](http://datatables.net) table enhancer (API introduce in version 1.10).

It permits to get the previous or the next row of the selected one.

Could be chained to the DataTable Rows API, see examples below : 

### Example

var table = jQuery('#example_table').DataTable();

// Get prev row
    
    table.row( '#current_row_example' ).prev(); // Return a DataTable row() object

// Get prev row
    
    table.row( '#current_row_example' ).prev(); // Return a DataTable row() object


### Other

See [row().show() plugin](https://github.com/edouardl/datatable-show-row) to build a row by row navigation.

### Changelog

Version 1.0
* Initial
