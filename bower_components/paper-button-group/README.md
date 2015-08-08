# paper-button-group

This web component is a direct clone from the <a href="https://github.com/PolymerElements/paper-radio-group">PolymerElements/paper-radio-group</a> 
element. Minor code parts where changed to work with paper-buttons instead of
paper-radio-buttons.

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

See <a href="https://github.com/PolymerElements/paper-button">paper-button</a> for more
information about `paper-button`.
