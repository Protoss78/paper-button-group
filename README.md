# paper-button-group
=================

`paper-button-group` allows user to select only one button from a set.
Checking one button that belongs to a group unchecks any
previously checked button within the same group. Use
`selected` to get or set the selected button.

Example:

```html
<paper-button-group selected="small">
  <paper-button toggles name="small">Small</paper-button>
  <paper-button toggles name="medium">Medium</paper-button>
  <paper-button toggles name="large">Large</paper-button>
</paper-button-group>
```

See <a href="paper-button.html">paper-button</a> for more
information about `paper-button`.
