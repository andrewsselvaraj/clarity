---
title: Overview
toc: true
---

# Labels

Labels show concise metadata in a compact format.

[//]: # 'DEMO - John and James'

## Usage

Use a label to show the metadata when the space is limited or when you want to catch user’s attention. It is commonly used for tags, or fiter items.
The distinctive visual style of labels deliberately deviates from buttons. This prevents users from confusing labels with buttons and allows labels to co-exist with other components without competing for a user's attention with primary and secondary buttons on the screen.

[//]: # 'DEMO - Fruit drink meat vegetable'

[//]: ## Types

## Anatomy

Labels are visually styled to differentiate them from buttons.

### Color

The Clarity color palette and the colors you are using throughout your application should guide which colors you choose for your labels. We recommend reserving stoplight colors (red, yellow, and green) to display state or status.

If the intent is to use colors as a way to have groups of labels be visually distinct from one another, keep in mind that there may be accessibility issues around using color as your sole differentiator.

Avoid using too many colors within the same context, displaying too many colors may distract the user from the core of your application and the information it presents.

[//]: # 'IMAGE - red yellow green blue / border fill text'

### Labels and Badges

Labels and badges can be used together to show a count relating to the metadata displayed in the label.

[//]: # 'DEMO - Production / dev test'

Documentation for Badges is available [here](https://clarity.design/documentation/badges).

### Additional Metadata

Describe additional information or metadata in parenthesis if necessary.

[//]: # 'DEMO - London (location'

_Do_
Use parenthesis for additional metadata displayed in the same label.

### Multiline Text

Keep labels to one line of concise text. The use case for labels is to showcase information in a compact format.

[//]: # 'DEMO - multiline text'

_Don't_
Use multiple lines of text within a single label.

## Behavior

### Clicking Labels

Labels may be clickable. In this case, clicking on a label should perform an action related to that label. Clicking on a location label used as a tag, for example, could serve to filter the results in a nearby list by that location. Clicking a label could also display more information about the metadata described by that label.

[//]: # 'DEMO - chocolate, vanilla, mixed'

### Dismissing Labels

A label can be dismissed. Use a close icon at the right-most side of a label to dismiss it.

[//]: # 'DEMO - James and Jimmy'

[//]: # Placement

## Content

### Capitalization

To differentiate from buttons, it is recommended that you avoid using all caps for labels. Using all caps might make the user think the label is a button and conflates the use case for labels with actions and buttons.

[//]: # 'DEMO - ALL CAPS'

_Don't_
Use all caps in labels
