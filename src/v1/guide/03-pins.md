---
title: Pins
type: guide
order: 3
---

## Simple 

Simple pinning allows to pin a layer to its parent with the following:

* Top
* Right
* Bottom
* Left
* Center Horizontally
* Center Vertically

When selecting a pin, Auto-Layout will set the pin constant value as the current pixel value.  

*For example if a layer is 20px from the right and you select `Pin to Right`, the `right` pin constant value will be set to 20px.*

Once a pin is set, Auto-Layout will enforce the pin value when the artboard is resized.  

*For example if you pinned a layer to the right by 20px, you can resize the artboard by dragging its right side and you'll notice the layer always stays 20px from the right.*

![](https://cl.ly/3h0m151x0N1R/download/Screen%20Recording%202017-01-29%20at%2002.22%20PM.gif)

### Pin to Parent

* **A `Layer` is always pinned to its `Parent`**
* **A parent can be either an `Artboard` or a `Group`**
* **Pinning a `Layer` to a `Sibling` layer is currently not supported**

![](/docs/images/pins1.png)
![](/docs/images/pins2.png)


## Advanced 

### Pinning by Pixels

### Pinning by Percent
