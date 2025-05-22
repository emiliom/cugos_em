# README

My presentation at the [CUGOS 2023 Spring Fling](https://cugos.org/2023-spring-fling/), 2023-04-21.

## Abstract

**Title:** Cloud-optimized geo data formats and the Python ecosystem

Nowadays there are gobs of very large geospatial data of all sorts accessible in one form or another online. Many of us are both producers and consumers ourselves. But online accessibility alone doesn't necessarily translate to convenient, scalable access to data subsets; or fully leverage the potential of cloud-based processing. Also, data producers and distributors may face challenges in generating and hosting data in scalable and accessible formats, or even choosing such formats without having to adopt fully new tool sets. I will review the ecosystem of "cloud optimized" (or cloud native) geospatial formats that are gaining ground or have already done so, and discuss some of their common features that leverage web and cloud architectures. I will focus on data formats for analysis purposes rather than cartographic rendering proper, though  they're not mutually exclusive, strictly speaking. Finally, to make this much more tangible and because Python is what I do, I will discuss these formats in the context of Python libraries that support them, using live Jupyter notebook demos.

## Presentation

The presentation was created in [this Jupyter notebook](cugos-presentation.ipynb) using [RISE](https://github.com/damianavila/RISE). It's [available here as an HTML presentation](https://emiliom.github.io/cugos_em/cugos-presentation-2023springfling.html).

## conda environments

*Bear in mind that this was from Spring 2023. Exact versions and dependency versions may be different now (May 2025). Some things are probably simpler these days.*

Created an environment named **rise** for running the presentation as a Jupyter notebook in slides/presentation mode using [RISE](https://github.com/damianavila/RISE):
```bash
mamba create -c conda-forge -n rise rise webcolors uri-template jsonpointer isoduration fqdn jupyter_contrib_nbextensions aiohttp aiobotocore s3fs fsspec geopandas rasterio xarray dask pystac matplotlib zarr pyarrow fastparquet python-snappy
```

Created the QGIS environment **qgis-geoparquet**  to run QGIS with GeoParquet support:
```bash
mamba create -n qgis-geoparquet -c conda-forge qgis libgdal-arrow-parquet pandas scipy scikit-learn pillow matplotlib ocl-icd-system
```
