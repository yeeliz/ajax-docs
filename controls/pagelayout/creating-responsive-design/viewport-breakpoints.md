---
title: Viewport Breakpoints
page_title: Viewport Breakpoints | UI for ASP.NET AJAX Documentation
description: Viewport Breakpoints
slug: pagelayout/creating-responsive-design/viewport-breakpoints
tags: viewport,breakpoints
published: True
position: 2
---

# Viewport Breakpoints



The following article describes the meaning of the __viewport breakpoints__ for __RadPageLayout__ and their usage.

## Viewport Breakpoints

In responsive web design, __viewport breakpoints__ are browser dimensions (usually just widths) that set the active range of a given media query. Once the browser dimensions are within that range, the styles associated with that media query will apply. In other words, without the breakpoints (and media queries) sites could be just fluid, but with breakpoints (and media queries), we can change the actual layout.

__RadPageLayout__ uses the following 5 breakpoints:

* extra small resolutions (or xs)

* small resolutions (or sm)

* medium resolutions (or md)

* large resolutions (or lg)

* extra large resolutions (or xl)

The notion of __viewport breakpoints__ is not just within the media queries, but is used throughout the control. All responsive properties have a suffix that's actually the media query it applies for: __SpanXS__ means the span for extra small resolutions; __HiddenLG__ means hidden on large resolutions and so on.

The following table describes the resolutions and the corresponding viewport breakpoints.


| Resolution | Screen size | Device type |
| ------ | ------ | ------ |
|max-width: 360px|extra small resolutions (or xs)|mobile phone (viewed in portrait)|
|min-width: 361pxmax-width: 768px|small resolutions (or sm)|mobile phone (viewed in landscape)tablet (viewed in portrait)|
|min-width: 769pxmax-width: 1024px|medium resolutions (or md)|tablet (viewed in landscape)|
|min-width: 1025pxmax-width: 1366px|large resolutions (or lg)|laptop|
|min-width: 1367px|extra large resolutions (or xl)|desktop|

>note The described devices types for the corresponding resolutions and screen size are approximate.
>
