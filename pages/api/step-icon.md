---
filename: /packages/material-ui/src/StepIcon/StepIcon.js
title: StepIcon API
---

<!--- This documentation is automatically generated, do not try to edit it. -->

# StepIcon

<p class="description">The API documentation of the StepIcon React component.</p>



## Props

| Name | Type | Default | Description |
|:-----|:-----|:--------|:------------|
| <span class="prop-name">active</span> | <span class="prop-type">bool | <span class="prop-default">false</span> | Whether this step is active. |
| <span class="prop-name">classes</span> | <span class="prop-type">object |   | Override or extend the styles applied to the component. See [CSS API](#css-api) below for more details. |
| <span class="prop-name">completed</span> | <span class="prop-type">bool | <span class="prop-default">false</span> | Mark the step as completed. Is passed to child components. |
| <span class="prop-name">error</span> | <span class="prop-type">bool | <span class="prop-default">false</span> | Mark the step as failed. |
| <span class="prop-name required">icon *</span> | <span class="prop-type">node |   | The icon displayed by the step label. |

Any other properties supplied will be spread to the root element (native element).

## CSS API

You can override all the class names injected by Material-UI thanks to the `classes` property.
This property accepts the following keys:
- `root`
- `active`
- `completed`
- `error`

Have a look at [overriding with classes](/customization/overrides#overriding-with-classes) section
and the [implementation of the component](https://github.com/mui-org/material-ui/tree/master/packages/material-ui/src/StepIcon/StepIcon.js)
for more detail.

If using the `overrides` key of the theme as documented
[here](/customization/themes#customizing-all-instances-of-a-component-type),
you need to use the following style sheet name: `MuiStepIcon`.

## Demos

- [Steppers](/demos/steppers)

