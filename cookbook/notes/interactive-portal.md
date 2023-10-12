# The Svalbox Interactive Map

## Introduction

The Svalbox Map is designed to provide an interactive interface to discover Svalbard's geology.

To access the Svalbox Map, open your web browser and enter the following URL or click [here](http://www.svalbox.no/map):
```
http://www.svalbox.no/map
```
```{figure} ../assets/svalbox_idex.png
:name: svalbox_idex

Landing portal of the Svalbox interactive map.
```

### Key Features
The Svalbox's interactive map is designed to provide users with a comprehensive and intuitive experience. The key features are:
- A range of data layers that can be interacted with to reveal different aspects of the area. 
- A search functionality  to quickly find specific Digital Outcrop Models (DOMs) and other features of interest. 
- The map includes tools that enable users to measure distances and areas on the map with ease. 


## Getting Started
### Navigating the Map

Use the *scroll wheel* on your mouse to zoom in and out on the map. Left-click to your mouse to move around the map.

```{figure} ../assets/zooming.gif
:name: zooming

Example of zooming in and out and panning across the interactive map.
```

### Changing Map Layers
Located at the top-left corner of the interactive portal is the layer pane. This feature allows you to easily switch and visualize various map layers. The layers available include a variety of datasets stored in the [Svalbox file database](../html/notes/read-access.html), as well as other open databases such as the one provided by the [Norwegian Polar Institute](https://data.npolar.no/dataset).
The layers available to date are:
- Norwegian Polar Institute - satellite
- Norwegian Polar Institute - geology
- Norwegian Polar Institute - basemap
- Seimic
- Sedimentary logs
- Drone footage
- Photo spheres
- Boreholes
- [Virtual outcrop Models](#virtual-outcrop-models)
- Virtual Field Guides

```{figure} ../assets/map_layers.gif
:name: map_layers

When starting, the default layers are the base map from Svalbard provided by the Norwegian Polar Institute database, the Virtual outcrop Models, and the Virtual Field Guides.
```

### Measuring Tools
The measuring tools provided with the Svalbox interactive map are designed to give users the power to measure distances, areas, and other spatial dimensions accurately.

These tools include:
- Distance measurement (for determining the length between two points)
- Area measurement (for calculating the size of a defined region)

These tools aim to help you analyze geographical features and better understand their spatial relationships and dimensions.

```{figure} ../assets/measure.gif
:name: measure

Measuring the transect of Virtual Outcrop Models on the northern coast of Van Keulenfjorden. Steps: 1. Disable base map; 2. Click on measuring tools and edit your vertices; 3. Click finish to get the total distance (in km) in the top-right part of the online interface.
```

```{admonition} Disable basemap layer
:class: important

When using the measurement tools, remember to disable the base map layer from the online interface since the measurements are displayed under this layer.
```

### Search Functionality

The search function allows users to efficiently locate specific Virtual Outcrop Models (VOMs) by applying various filters related to the parameters of each model. These filters include acquisition parameters, camera models used, model location, ground resolution, data authorship, geological aspects, and the total area of each model.

The search functionality enhances the user experience by providing streamlined access to the relevant VOMs within the interactive map interface.

```{admonition} Apply filter
:class: tip
When searching with a filter option, remember to click "Apply filter".
```

```{figure} ../assets/filter_land.gif
:name: filter_land

Example of Virtual Outcrop Models search based on the Land the models are located in Svalbard.
```

## Virtual Outcrop Models

```{admonition} TODO
:class: note
Section to develop
```

````{margin}
```{admonition} Zenodo
:class: tip

[Zenodo](https://zenodo.org) serves as an open repository, providing a platform for researchers across diverse disciplines to freely share and safeguard their research outputs, irrespective of size or format. This general-purpose open-access repository allows researchers to deposit various materials, including research papers, data sets, and research software. For instance, all Virtual Outcrop Models in [Svalbox](http://www.svalbox.no/map) are uploaded to Zenodo, ensuring free access to the data and facilitating its long-term citability, shareability, and discoverability within the scientific community.
```
````


You can download all the information related to the Digital Terrain Models uploaded in [Svalbox](http://www.svalbox.no/outcrops/) from the [Zenodo](https://zenodo.org/) database.

The files needed to plot the models in ArcGIS Pro are in the *export.zip* folder.

```{figure} ../assets/download_zenodo.gif
:name: download_zenodo

Click on the DOI link of the model. A new tab will open linking to the [Zenodo](https://zenodo.org/) database, from where you can download all the data.
```
