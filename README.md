Silverstripe Gridfield Summary Row
==================================

Adds a summary row to a gridfield, providing totals for numeric and columns (including Money).



Usage
=

You can add this component like any other component. You will need to define a component to insert it before, usually a 'GridFieldPaginator'.

```php
		$grid->getConfig()->addComponent(new GridFieldSummaryRow(), 'GridFieldPaginator');
```

Todo
=

 - Provide totals for relations' fields.
 - Correctly display Money and other formatted/composite db fields.
