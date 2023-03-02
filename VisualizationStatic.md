---
name: VisualizationStatic
topic: Static Graphics
maintainer: Dianne Cook, Sherry Zhang
email: dicook@monash.edu
version: 2023-02-23
source: https://github.com/cran-task-views/VisualizationStatic/
---

One of the strengths of R is the wealth of data plotting packages. This CRAN Task View maintains a list of static graphics packages, and links to web resources on plotting data.

Note that some of these packages are on CRAN and others are on GitHub, Bioconductor, or R-Forge.

If you think that a package is missing from this list, please let us know through issues or pull requests in the [GitHub repository](https://github.com/cran-task-views/VisualizationStatic).

### The underlying grid system

- `r pkg("grid", priority = "core")` | Implements the primitive graphical functions.
- `r pkg("gtable", priority = "core")`
- `r pkg("graphics", priority = "core")` (base) | The original graphics engine.
- `r pkg("gridExtra")`
- `r pkg("gridGraphics")` | Redraw Base Graphics Using 'grid' Graphics.


### Lattice graphics

- `r pkg("lattice")` | Create data visualisations using the trellis method. Built on the `grid` system.
- `r pkg("latticeExtra")` | Extra graphical utilities based on lattice.
- `r pkg("adegraphics")` | Lattice-based package for the representation of multivariate data.
- `r pkg("loa")` | Lattice options and add-ons.
- `r pkg("stripless")` | Structured trellis displays without strips for lattice graphics.
- `r pkg("tactile")` | New and extended plots, methods, and panel functions for `r pkg("lattice")`


### The ggplot2 ecosystem

- `r pkg("ggplot2", priority = "core")` | Create elegant data visualisations using the grammar of graphics. Built on the `grid` system.
- `r pkg("GGally")`
- `r pkg("cowplot")`
- `r pkg("ggh4x")`
- `r pkg("ggraph")` | An Implementation of Grammar of Graphics for Graphs and Networks
- `r pkg("egg")`
- `r pkg("ggforce")`


*stats/ geoms*

- `r pkg("ggbeeswarm")`
- `r pkg("ggpointdensity")`
- `r pkg("ggimg")`
- `r pkg("geomtextpath")`
- `r pkg("ggrepel")`
- `r pkg("ggridges")`
- `r pkg("ggalluvial")`
- `r pkg("ggdensity")`
- `r pkg("gghalves")`
- `r pkg("ggHoriPlot")`
- `r pkg("ggip")`
- `r pkg("gglorenz")`

*scales* 

- `r pkg("scales")`
- `r pkg("ggnewscale")`
ggfocus

*arrange facet/panel/composition*

- `r pkg("patchwork", priority = "core")`
- `r pkg("sugrrants")`
- `r pkg("geofacet")`
- `r pkg("geogrid")`
- `r pkg("ggside")`
- `r pkg("DHBins")`

*theme*

- `r pkg("basetheme")` | Themes for base graphics plots.
- `r pkg("ggthemes")` | Extra themes, scales and geoms for `r pkg("ggplot2")`.
- `r pkg("hrbrthemes")`
- `r pkg("tvthemes")` | TV show themes and color palettes for `r pkg("ggplot2")` graphics
- `r pkg("thematic")` | Unified and automatic theming of `r pkg("ggplot2")`, `r pkg("lattice")`, and `r pkg("base")` R Graphics

*making ggplot2 easy*

- `r pkg("ggpubr")`
- `r pkg("ggeasy")`
- `r pkg("esquisse")`
- `r pkg("ggedit")`
- `r pkg("ggcharts")`

*annotation*
  
- `r pkg("gghighlight")`


*test and programming with ggplot2*

- `r pkg("vdiffr")`
- `r pkg("ggtrace")`
- `r pkg("ggghost")`
- `r pkg("gginnards")`

### Other aspects not included in this Task view

- color: to the color task view
- dynamic: to the dynamic task view 

### Graphics resources and advice web sites

- [ggplot2: Elegant Graphics for Data Analysis](https://ggplot2-book.org)
- [Data Visualization: A practical introduction](https://socviz.co)
- [Fundamentals of Data Visualization](https://clauswilke.com/dataviz/)
- [Graphical Data Analysis with R](http://www.gradaanwr.net)
- [The R Graph Gallery](https://www.r-graph-gallery.com)
- [ggplot2 extensions - gallery](https://exts.ggplot2.tidyverse.org/gallery/)


