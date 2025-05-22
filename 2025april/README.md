# README

My presentation at the [April 2025 CUGOS meeting](https://cugos.org/meetings/2025-04-16/), 2025-04-16.

## Abstract

**Title:** HoloViz Python dashboards for ocean data  from diving, autonomous floats

I describe and demonstrate the use of the Python [HoloViz stack](https://holoviz.org) to create custom online dashboards (including [this one](https://squid-test1.azurewebsites.net)) that allow multi-faceted exploration of data from autonomous, depth-profiling platforms in the ocean. The [Argo program](https://argo.ucsd.edu) is the best example of these data. 

This presentation is an expanded follow-up to my [March CUGOS meeting](https://cugos.org/meetings/2025-03-19/) presentation.

## Presentation

The presentation was created in [this Jupyter notebook](cugos-presentation.ipynb) using [RISE](https://github.com/damianavila/RISE). It's [available here as an HTML presentation](https://emiliom.github.io/cugos_em/cugos-presentation-2025april.html).

## conda environment

I created a conda environment for this presentation using this statement:

```bash
conda create -c conda-forge -n cugos_202504_mayorga jupyter rise webcolors uri-template jsonpointer isoduration fqdn jupyter_contrib_nbextensions requests aiohttp pooch geopandas xarray dask matplotlib zarr pyarrow fastparquet python-snappy holoviews geoviews hvplot datashader panel param jupyter_bokeh
```

Note that some of the low-level packages listed above may not actually be needed to be specified explicitly. I was being lazy and carried them over from the conda env for my CUGOS Spring Fling 2023 presentation.