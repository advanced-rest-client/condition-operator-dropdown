[![Build Status](https://travis-ci.org/advanced-rest-client/condition-operator-dropdown.svg?branch=stage)](https://travis-ci.org/advanced-rest-client/condition-operator-dropdown)  

# condition-operator-dropdown

A dropdown with comparison options for logical actions.
It can be used with logic actions editors to display list of possible actions.

The element is simple material design dropdown with predefined set of options.
This element can be used as a for element and works with `iron-form` element.

Currently it supports following actions:
- Equal
- Not equal
- Greater than
- Greater than or equal
- Less than
- Less than or equal
- Contains
- Regular expression

### Example
```
<condition-operator-dropdown value="{{operator}}" required></condition-operator-dropdown>
```

### Styling
`<condition-operator-dropdown>` provides the following custom properties and mixins for styling:

Custom property | Description | Default
----------------|-------------|----------
`--condition-operator-dropdown` | Mixin applied to the element | `{}`
`--condition-operator-dropdown-menu` | Mixin applied to the dropdown menu | `{}`

