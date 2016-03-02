# r-table

An element to wrap around reportal WYSIWYG Aggregated Table component.
It can:
** accept unlimited levels of nested headers,
** make columns: sortable, hidable/hidden, filterable;
** limit the amount of records to be displayed;
** allow row(s) selection;
** autocreate row index column;
** override column headers.

It's based off [`vaadin-grid`](https://github.com/vaadin/vaadin-grid) element by Vaadin team ([Apache 2.0 license](https://github.com/vaadin/vaadin-grid/blob/master/LICENSE)) and extends it.
See `vaadin-grid` [API docs](https://cdn.vaadin.com/vaadin-core-elements/latest/vaadin-grid/index.html) and [Code Examples](https://cdn.vaadin.com/vaadin-elements/latest/vaadin-grid/demo/) to get a deeper insight into its functionality, if you want to modify or extend it.

Example:

    <r-aggregated-table >
      <confirmit:wysiwygcomponent type="AggregatedTable" id="cdde7f88-9718-4694-a97c-161fe8fc4292" />
    </r-aggregated-table>
