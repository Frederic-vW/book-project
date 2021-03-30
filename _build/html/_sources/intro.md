Interactive Jupyter Book Project
=================================

Interactive books combine text and code.

# What can you find in this book?

Notes:
```{note}
Here is a note!
```

Warnings:
```{warning}
careful, you shouldn't ...
```

:::{note}
This text is **standard** _Markdown_
:::

More notes:
```{note}
Another note...
```

... and even panels:
````{panels}
Content of the left panel.

{badge}`example-badge,badge-primary`

---

```{link-button} content/panels
:text: Clickable right panel
:type: ref
:classes: stretched-link
```

````

Clickable:
:::{admonition} Click here!
:class: tip, dropdown
Here's what's inside!
:::


## Introduction
this is going to be interactive!

This book contains information about the planet Jupiter - the fifth planet from
the sun and the largest planet in the solar system! {numref}`jupiter-figure`
below shows an image of Jupiter captured by the Hubble Space Telescope on
June 27, 2019.

```{figure} https://solarsystem.nasa.gov/system/resources/detail_files/2486_stsci-h-p1936a_1800.jpg
---
height: 300px
name: jupiter-figure
---
The beautiful planet Jupiter! Source: [NASA](https://solarsystem.nasa.gov/resources/2486/hubbles-new-portrait-of-jupiter/?category=planets_jupiter).
```

Here's something else:
```{hint}
NASA provides a lot more information about the physical characteristics of Jupiter [here](https://solarsystem.nasa.gov/planets/jupiter/by-the-numbers/).
```
