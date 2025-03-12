# README

My presentation at the [CUGOS 2023 Spring Fling](https://cugos.org/2023-spring-fling/), 2023-04-21.

**TODO:** Add conda environment file used with the notebook.

## Abstract

**Title:** Cloud-optimized geo data formats and the Python ecosystem

Nowadays there are gobs of very large geospatial data of all sorts accessible in one form or another online. Many of us are both producers and consumers ourselves. But online accessibility alone doesn't necessarily translate to convenient, scalable access to data subsets; or fully leverage the potential of cloud-based processing. Also, data producers and distributors may face challenges in generating and hosting data in scalable and accessible formats, or even choosing such formats without having to adopt fully new tool sets. I will review the ecosystem of "cloud optimized" (or cloud native) geospatial formats that are gaining ground or have already done so, and discuss some of their common features that leverage web and cloud architectures. I will focus on data formats for analysis purposes rather than cartographic rendering proper, though  they're not mutually exclusive, strictly speaking. Finally, to make this much more tangible and because Python is what I do, I will discuss these formats in the context of Python libraries that support them, using live Jupyter notebook demos.

## Presentation

The presentation was created in [this Jupyter notebook](cugos-presentation.ipynb) using [RISE](https://github.com/damianavila/RISE). It's [available here as an HTML presentation](https://emiliom.github.io/CUGOS2023-CloudGeodataPython/cugos-presentation.slides.html)
