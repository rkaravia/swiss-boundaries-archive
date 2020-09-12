# swiss-boundaries-archive

The goal of this repository is to collect annual releases of the swissBOUNDARIES3D dataset.

## License

[Open use. Must provide the source.](https://opendata.swiss/en/terms-of-use/#terms_by)

- You may use this dataset for non-commercial purposes.
- You may use this dataset for commercial purposes.
- You must provide the source (author, title and link to the dataset).

Source: [Swiss Federal Office of Topography](https://shop.swisstopo.admin.ch/en/products/landscape/boundaries3D)

## Available Data

The following years are currently available for download:

- 2020: [2020.0](https://github.com/rkaravia/swiss-boundaries-archive/releases/download/2020.0/swissBOUNDARIES3D-2020.0.zip)
- 2019: [2019.0](https://github.com/rkaravia/swiss-boundaries-archive/releases/download/2019.0/swissBOUNDARIES3D-2019.0.zip)
- 2018: [2018.0](https://github.com/rkaravia/swiss-boundaries-archive/releases/download/2018.0/swissBOUNDARIES3D-2018.0.zip)

## Versioning

Each archived release is versioned as `{year}.{revision}`. Usually there is only a single revision per year. A once archived version will never change.

## Predictable Structure

The official download URL for the swissBOUNDARIES3D dataset is not versioned and the data does not have a predictable machine-readable structure, it is provided as several shapefiles inside a zip archive inside another zip archive, with somewhat arbitrary names.

The releases collected here allow permalinking to a revision with a known data structure.

## swiss-boundaries-geojson

The datasets collected here are available in the GeoJSON format in the [swiss-boundaries-geojson](https://labs.karavia.ch/swiss-boundaries-geojson/) project.
