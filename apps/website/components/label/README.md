---
title: Overview
toc: true
---

# Labels

Labels show concise metadata in a compact format.

[//]: # 'DEMO - John and James'

<doc-demo src="/demos/label/demo1-ng.html" demo="/demos/label/demo1-css.html" toggle="false" />

## Usage

Use a label to show the metadata when the space is limited or when you want to catch user’s attention. It is commonly used for tags, or fiter items.
The distinctive visual style of labels deliberately deviates from buttons. This prevents users from confusing labels with buttons and allows labels to co-exist with other components without competing for a user's attention with primary and secondary buttons on the screen.

<doc-demo src="/demos/label/food-ng.html" demo="/demos/label/food-css.html" />

## Anatomy

Labels are visually styled to differentiate them from buttons.

### Color

The Clarity color palette and the colors you are using throughout your application should guide which colors you choose for your labels. We recommend reserving stoplight colors (red, yellow, and green) to display state or status.

If the intent is to use colors as a way to have groups of labels be visually distinct from one another, keep in mind that there may be accessibility issues around using color as your sole differentiator.

Avoid using too many colors within the same context, displaying too many colors may distract the user from the core of your application and the information it presents.

<doc-demo src="/demos/label/color-ng.html" demo="/demos/label/color-css.html" />

### Labels and Badges

<ClrRow>
<ClrCol>
<div style="height: 100px">
<div>Labels and badges can be used together to show a count relating to the metadata displayed in the label.</div>
<div style="padding-top: 0.5rem">Documentation for Badges is available <a href="/components/badge">here</a>.</div>
</div>
</ClrCol>
<ClrCol>
<DocInset height="100">
<div>
<span class="label label-light-blue">Production<span class="badge badge-light-blue">12</span></span>
<span class="label label-light-blue">Dev/Test<span class="badge badge-light-blue">99+</span></span>
</div>
</DocInset>
</ClrCol>
</ClrRow>

### Additional Metadata

Differentiate labels from buttons.

::: do Describe additional information with parenthesis
<DocInset height="100">

<div>
<span class="label label-orange">London (Location)</span>
</div>

</DocInset>
:::

::: dont Use use all capitialization or multi-lines
<DocInset height="100">

<div>
<span class="label label-purple">LONDON (LOCATION)</span>
<span style="padding: 15px; text-align: center" class="label label-purple">LONDON <br>(LOCATION)</span>
</div>

</DocInset>
:::

## Behavior

### Clicking Labels

<ClrRow>
<ClrCol>
<div style="height: 100px">
Labels may be clickable. In this case, clicking on a label should perform an action related to that label. Clicking on a location label used as a tag, for example, could serve to filter the results in a nearby list by that location. Clicking a label could also display more information about the metadata described by that label.
</div>
</ClrCol>
<ClrCol>
<DocInset height="100">
<div>
<a href="javascript://" class="label label-purple clickable">Chocolate</a>
<a href="javascript://" class="label label-purple clickable">Vanilla</a>
<a href="javascript://" class="label label-purple clickable">Mixed</a>
</div>
</DocInset>
</ClrCol>
</ClrRow>

### Dismissing Labels

<ClrRow>
<ClrCol>
<div style="height: 100px">
A label can be dismissed. Use a close icon at the right-most side of a label to dismiss it.
</div>
</ClrCol>
<ClrCol>
<DocInset height="100">
<div>
<a href="javascript://" class="label label-blue clickable">james@test.com <clr-icon shape="close"></clr-icon></a>
<a href="javascript://" class="label label-blue clickable">jimmy@test.com <clr-icon shape="close"></clr-icon></a>
</div>
</DocInset>
</ClrCol>
</ClrRow>

[//]: # 'DEMO - James and Jimmy'

[//]: # Placement

## Content

### Status

<doc-demo src="/demos/label/status-ng.html" demo="/demos/label/status-css.html" />

### Labels with badges

<doc-demo src="/demos/label/badges-ng.html" demo="/demos/label/badges-css.html" />
