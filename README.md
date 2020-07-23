# Merchiston Community Council Boundaries

The Jupyter notebook illustrates a technique for extracting Community Council (CC) boundary data from [the City of Edinburgh Council Mapping Portal](http://data.edinburghcouncilmaps.info/datasets/da44854d46c44a76b9b1160fc609738a_25). 

The relevant polygons are indexed by the name of the CC which allows us to extract the boundary of a specific CC. 

This has then been ingested into a WordPress site via the excellent [Leaflet Map](https://en-gb.wordpress.org/plugins/leaflet-map/) plugin. The result is illustrated on the [Merchiston Community Council website](https://merchistoncc.org.uk/about-us/council-boundaries/).

The shortcode used is as follows:
```
[leaflet-map lat="55.933333" lng="-3.213889" zoom=15 height=800 zoomcontrol=1]
[leaflet-geojson src="https://raw.githubusercontent.com/ewan-klein/mcc-boundaries/master/mcc_boundaries.json"]
```
