<!--- This documentation is automatically generated, do not try to edit it. -->

---
filename: /src/Table/Table.js
---

# Table



## Props

| Name | Type | Default | Description |
|:-----|:-----|:--------|:------------|
| children | Node |  | The content of the table, normally `TableHeader` and `TableBody`. |
| classes | Object |  | Useful to extend the style applied to components. |
| component | ElementType | 'table' | The component used for the root node. Either a string to use a DOM element or a component. |

Any other properties supplied will be [spread to the root element](/customization/api#spread).

## CSS API

You can override all the class names injected by Material-UI thanks to the `classes` property.
This property accepts the following keys:
- `root`

Have a look at [overriding with classes](/customization/overrides#overriding-with-classes) section
and the [implementation of the component](https://github.com/callemall/material-ui/tree/v1-beta/src/Table/Table.js)
for more detail.

If using the `overrides` key of the theme as documented
[here](/customization/themes#customizing-all-instances-of-a-component-type),
you need to use the following style sheet name: `MuiTable`.

## Demos

- [Tables](/demos/tables)

