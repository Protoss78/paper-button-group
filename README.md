[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/Protoss78/paper-button-group)

# paper-button-group

`paper-button-group` allows user to select only one button from a set.
Checking one button that belongs to a group unchecks any
previously checked button within the same group. Use
`selected` to get or set the selected button.

Example:

<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="paper-button-group.html">
    <link rel="import" href="../paper-button/paper-button.html">
    <link rel="import" href="../paper-styles/paper-styles.html">
    <style>
        paper-button {
            transition: background-color 0.3s;
        }

        paper-button[active] {
            color: white;
            background-color: var(--paper-green-500);
            --paper-button-flat-focus-color: var(--paper-green-50);
        }

        paper-button:hover {
            background: #eee;
        }
    </style>
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<paper-button-group selected="2">
    <paper-button>Oxygen</paper-button>
    <paper-button>Carbon</paper-button>
    <paper-button>Hydrogen</paper-button>
    <paper-button>Nitrogen</paper-button>
    <paper-button>Calcium</paper-button>
</paper-button-group>
```
