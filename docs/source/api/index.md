---
title: API
---

## Global config

### autoplay

Flag to enable autoplay

* **Type**: `Boolean`
* **Default**: `false`

### autoplayTimeout

Time elapsed before advancing slide

* **Type**: `Number`
* **Default**: `2000`

### autoplayHoverPause

Flag to pause autoplay on hover

* **Type**: `Boolean`
* **Default**: `false`

### controlsEnabled

Enable controls

* **Type**: `Boolean`
* **Default**: `false`

### perspective

Slides perspective position

* **Type**: `Number`
* **Default**: `35`

### display

Number of slides displayed on each page

* **Type**: `Number`
* **Default**: `5`

### loop

Enable carousel infinite loop

* **Type**: `Boolean`
* **Default**: `true`

### animationSpeed

Animation between slides in milliseconds

* **Type**: `Number`
* **Default**: `500`

### dir

Animation direction 

* **Type**: `String`
* **Default**: `rtl`

### width

Slide width displayed in center of carousel

* **Type**: `Number`
* **Default**: `360`

### width

Slide height displayed in center of carousel

* **Type**: `Number`
* **Default**: `270`

### border

Slide border size in pixels

* **Type**: `Number`
* **Default**: `1`

### space

Space between slides in pixels

* **Type**: `Number`
* **Default**: `auto`

### startIndex

Start slide index. First slide has 0 index

* **Type**: `Number`
* **Default**: `0`

### clickable

Enable navigation by clicking on slide

* **Type**: `Boolean`
* **Default**: `true`

### minSwipeDistance

Minimum distance in pixels to swipe before a slide advance is triggered

* **Type**: `Number`
* **Default**: `10`

### inverseScaling

Slide inverse scaling

* **Type**: `Number`
* **Default**: `300`

### onLastSlide

Callback triggered on last slide

* **Type**: `Function`
* **param**: `index`

### onSlideChange

Callback triggered on slide changed

* **Type**: `Function`
* **param**: `index`
