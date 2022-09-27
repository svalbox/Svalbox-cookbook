# Read-access to Svalbox resources

Access to the Svalbox resources is provided through multiple ways, not all of which possible beyond the UNIS network.
We differentiate between the following access points:

````{card}
Svalbox file database
^^^
Accessible from within the UNIS network. Credential-based file browser access through:
```
\\svalbox\
```
````

````{card}
Svalbox PostgreSQL/GIS Server
^^^
Accessible from within the UNIS network. Credential-based access through:
```
svalbox:5433
```
````


````{card}
Svalbox ArcGIS REST API
^^^
Accessible from the internet, only part of the data visible. Access does not require credentials. Accessible through:
```
http://svalbox.unis.no/arcgis/rest/services/
```
````

The access points can be readily accessed through either file-browser (i.e., the file database) and more specialised toolsets.
In particular, the two server points require either access through scripts or GIS applications (preferably with GUI).
Connecting to the databases through ArcGIS and QGIS is described below.

## ArcGIS

ArcGIS Pro is available for use at UNIS.
Accounts can be requested from the UNIS AG GIS admin.

### PostgreSQL/GIS connection

```{figure} ./assets/arcgis_pro_postgis_connection.gif
---
height: 600px
name: arcgispro_postgis_connection
---
Connecting to the Svalbox DB using the PostGIS connection in ArcGIS Pro.
please ask the Svalbox admin for the credentials.
```

### ArcGIS REST API connection

```{figure} ./assets/arcgis_pro_server_connection.gif
---
height: 600px
name: arcgispro_server_connection
---
Connecting to the Svalbox DB using the ArcGIS server connection in ArcGIS Pro.
please ask the Svalbox admin for the credentials.
```

## QGIS

### PostgreSQL/GIS connection

```{figure} ./assets/qgis_postgis_connection.gif
---
height: 600px
name: qgis_postgis_connection
---
Connecting to the Svalbox DB using the PostGIS connection in QGIS.
please ask the Svalbox admin for the credentials.
```

### ArcGIS REST API connection

```{figure} ./assets/qgis_server_connection.gif
---
height: 600px
name: qgis_server_connection
---
Connecting to the Svalbox DB using the ArcGIS server connection in QGIS.
please ask the Svalbox admin for the credentials.
```
