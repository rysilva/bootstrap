
Dropdown is a simple directive which will toggle a dropdown menu on click or programmatically.
You can either use `is-open` to toggle or add inside a `<a dropdown-toggle>` element to toggle it when is clicked.
There is also the `on-toggle(open)` optional expression fired when dropdown changes state.

Add `dropdown-append-to-body` to the `dropdown` element to append to the containing `.dropdown-menu` on the body.
This is useful when the dropdown button is inside a div with `overflow: hidden`.