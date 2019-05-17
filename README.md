# swissBOUNDARIES3D Archive

The goal of this repository is to collect annual releases of the [swissBOUNDARIES3D](https://opendata.swiss/en/dataset/swissboundaries3d-landesgrenzen) dataset.

## License / Attribution

Conditions for the swissBOUNDARIES3D dataset:
> Open use. Must provide the source. Use for commercial purposes requires permission of the data owner.

Source: Swiss Federal Office of Topography, see [swissBOUNDARIES3D national boundaries](https://opendata.swiss/en/dataset/swissboundaries3d-landesgrenzen) for more information.

## Available Data

The following years are currently available for download:

- 2018: [2018.0](https://github.com/rzoller/swissBOUNDARIES3D-archive/releases/download/2018.0/swissBOUNDARIES3D-2018.0.zip)
- 2019: [2019.0](https://github.com/rzoller/swissBOUNDARIES3D-archive/releases/download/2019.0/swissBOUNDARIES3D-2019.0.zip)

## Versioning

Each release is versioned as `{year}.{revision}`, usually there is only a single revision, but you never know... The point is that a once released version will never change.

## Predictable Structure

The [official download URL](http://data.geo.admin.ch/ch.swisstopo.swissboundaries3d-land-flaeche.fill/data.zip) is not versioned and the data does not have a predictable machine-readable structure, it is provided as several shapefiles inside a zip archive inside another zip archive, with somewhat arbitrary names.

The releases collected here allow permalinking to a revision with a known data structure.
