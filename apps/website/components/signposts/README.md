---
title: Overview
toc: true
---

# Signpost

The signpost is a convenient, lightweight way to show contextual help of information without taking the user out of the current context.

<ClrRow>

![Jigglypuff is active nav](/images/components/signpost/basic-and-pie-chart.svg)

</ClrRow>

## Usage

Use a signpost when you want to show a small amount of contextual help of information without taking the user out of the current context. Use sparingly as a supplemental element and not as a primary method of adding details.

Use a signpost:

- When you want to include a header, image or text/image links in the content
- When the information presented needs to stay in view at length (Unlike tooltips, signposts stay in view until the user interacts with another element)

## Anatomy

A signpost displays contextual help or information in a popover dialog. Like a tooltip, it has an arrow/pointer that extends out to the trigger element, but the dialog is larger to fit more content. Signposts are designed to show a relatively small amount of content which may include: a title, images, text links of image links. A vertical scrollbar (browser default) may be used if the content exceeds the maximum height of the dialog.

### Size

Min-width 216px; Min-height 84px
Max-width 360px; Max-height 504px

## Behavior

Clicking the icon triggers the signpost. It remains visible until the user clicks the close icon or clicks anywhere outside of the dialog to dismiss it. To keep the interface uncluttered, only one signpost is displayed at a time. When a dialog is visible, clicking an icon to open another one automatically dismisses the previous dialog.

<ClrRow>

![Jigglypuff is active nav](/images/components/signpost/states.svg)

</ClrRow>

## Placement

[//]: # 'IMAGE - default position'

Default position for the dialog is 6px to the right of the trigger icon.

<ClrRow>

![Jigglypuff is active nav](/images/components/signpost/positioning.svg)

</ClrRow>

[//]: # 'IMAGES x2 - icon position'

<ClrRow>

<div class="clr-col-12 clr-col-md-6">

::: inset Basic
![Basic Vertical Navigation](/images/components/signpost/inline-alignment.svg)
:::
Default position for the dialog is 6px from the end of the text

</div>
<div class="clr-col-12 clr-col-md-6">

::: inset Dividers
![Dividers](/images/components/signpost/column-alignment.svg)
:::
In tables, the icons may be aligned in a column

</div>
</ClrRow>

### Recommendations

- The popover should not be so large that it dominates the screen
- Make sure that the popover doesn't obstruct other important information on the screen
- With the exception of text/image links, don't insert any actionable components, such as buttons, in the dialog
- Don't rely on signposts as a primary method of displaying additional information - i.e. as a way to save space on a page
- Use sparingly as a device to add immediate, relevant information

[//]: # Content
