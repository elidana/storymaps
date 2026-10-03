# GeoNet test storymap

A test project to demo a possible storymap showing GeoNet data in the Ruapehu rohe.

Use GeoNet API and LINZ data service.

To view: [https://elidana.github.io/storymaps/](https://elidana.github.io/storymaps/)

## Data and software Sources
stations and data: GeoNet

basemap: LINZ Basemaps hosted DEM hillshade tiles

The map loads LINZ hillshade tiles directly from the LINZ Basemaps service; no
basemap tiles are downloaded or stored in this project. The included API key is
the one shown in LINZ's public Leaflet example. Replace it in `app.js` with a
registered key for a deployed site if required.

software: QGIS and **QStoryMap** QGIS plugin: [github.com/amanchry/QStoryMap](https://github.com/amanchry/QStoryMap)

### To run locally
```
python3 -m http.server 8000
```

and then open [http://localhost:8000/](http://localhost:8000/) on your browser


