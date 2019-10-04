# geodata
A repository to store useful maps in different formats.

## Useful tools

- [QGIS](https://qgis.org/en/site/) - load geodata from WFS/WMS services, process, analyze, combine with other data..
- [mapshaper](https://mapshaper.org/) - optimize and convert geodata files to other formats. Good for creating  production ready geojson or topojson files.

With mapshaper you can also easily convert geodata to different projections. To get a good transverse mercator projection for Finland, use the following command:

`proj +proj=tmerc +lat_0=0 +lon_0=27 +k=1 +x_0=3500000 +y_0=0 +ellps=intl +towgs84=-96.062,-82.428,-121.753,4.801,0.345,-1.376,1.496 +units=m +no_defs`
