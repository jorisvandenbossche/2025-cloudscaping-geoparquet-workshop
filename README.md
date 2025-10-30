# 2025-cloudscaping-geoparquet-workshop

Workshop about GeoParquet at the Cloudscaping Geo Symposium in Delft

https://www.geonovum.nl/agenda/cloudscaping-geo

In the context of cloud native geospatial workflows, the usage of standardized
file formats that are optimized for usage in the cloud, is a crucial aspect.
Especially when data grows larger, it is important to have efficient access to
(subsets of) your data. On the vector side of geospatial, GeoParquet is one of
the available formats. GeoParquet defines how to store geospatial vector data in
Apache Parquet, which is a widely used columnar storage format. This workshop
will give a brief overview of what makes file formats cloud optimized and the
different options for vector data, and then dive deeper specifically into
GeoParquet, illustrating it with practical examples using Python.

Slides: https://jorisvandenbossche.github.io/2025-cloudscaping-geoparquet-workshop

## Run the code yourself

First, download this repository (click the green button above, or use `git clone`).

Then, install pixi (a cross-platform package manager that allows us to easily
set up reproducible environments, building on top of conda):
https://pixi.sh/latest/installation/

Finally, open a terminal (command prompt) at this location and run:

```
pixi run jupyter lab
```

That will ensure to install all required packages and spin up a [Jupyter Lab](https://jupyter.org/)
(notebook) application in your browser.
