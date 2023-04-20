# Setup

## Steps

1. To setup, first initialise a Conda environment and activate it.
2. Run `conda install -c conda-forge pandas geopandas folium numpy matplotlib`
3. Download the relevant datasets. Only the additional dataset listed is needed:<br/>
  Boundaries District - City of Philadelphia Police Districts - City of Philadelphia, ArcGIS
    - Link: [https://hub.arcgis.com/datasets/phl::boundaries-district](https://hub.arcgis.com/datasets/phl::boundaries-district)

    <br/>

4. Modify the import paths to the CSV files at the top of each notebook.
5. Click "Run All" to run the cells and generate the diagrams.

## Guide to Documents

Here's the filetree:

```sh
.
├── bicycles.ipynb      # III. Vehicular Makeup - Bicycles
├── crime.ipynb         # IV. Crime
├── heavy_vehicles.ipynb # III. Vehicular Makeup - Heavy Vehicles
├── infrastructure.ipynb # II. Infrastructure
├── pedestrians.ipynb # III. Vehicular Makeup - Pedestrians
├── small_vehicles.ipynb # III. Vehicular Makeup - Small Vehicles
└── summary_stats.ipynb #I. Intro Stats
```

In each file, you'll find the necessary diagram code for each sections.
