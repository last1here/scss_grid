scss_grid
=========

A simple scss percentage based grid I use in most projects so thought i'd seperate it into its own repository to allow for easier management.

###Settings###

There is only one configurable option

- `$colunms` - The amount columns.
- `$spacer` - The margin between elements must be a `%` unless `$use_padding` is set to `true`.
- `$prefix` - A prefix to add to all scss_grid classes.
- `$col_prefix` - Basically column label. TODO: rename
- `$prefixes` - Breakpoint prefixes list.
- `$breakpoints` - Mobile first breakpoints list.
- `$use_padding` - Set to `true` to use padding instead of margin for column spacer.
- `$helpers` - List of size helpers default value: `"quarter" 25%, "third" 33.333333%, "half" 50%, "two-thirds" 66.666666%, "three-quarters" 75%, "full" 100%`