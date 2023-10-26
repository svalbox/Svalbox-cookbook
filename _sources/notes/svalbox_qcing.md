# Svalbox quality control check-list

Prior to submission of data to the curated Svalbox databases, several steps need to be gone through.
These include:

- Data inspection and processing (*processed* checkbox in SBL)
- Quality control and metadata extraction (*qced* checkbox in SBL)
- Submission to Svalbox (*uploaded_to_db* checkbox in SBL)

The respective checkboxes should only be checked once the steps have been completed.
Keep in mind that this is not a linear progression - if the quality control step shows that more processing is needed, the *processed* checkbox will likely be set to *False* once more.
The SBL is regularly checked for data sets that have been submitted to Svalbox.
Said data are automatically removed from the SBL following archiving.

## Processing

Various guidelines have been established for the standardized processing of data sets.
Data type-specific tutorials are linked to below.

````{tab-set}
```{tab-item} Digital models
[Geo-SfM guidelines and tutorial](https://unisvalbard.github.io/Geo-SfM/content/lessons/l1/tutorial.html)
```

```{tab-item} TBD
TBD.
```
````

## Quality control

The quality control check is needed for quality assurance and standardisation of the data prior to submission to Svalbox.
Both the data and the metadata need to follow established guidelines.

```{warning}
Work in progress - more to be added soon.
```

`````{tab-set}
````{tab-item} Digital models
*Datapackage requirements*

- One model per project
- Followed the file structure
- Input material only for this project
- Can you identify people? If so prosess again.
- Processing report, both html and pdf
- Max files size 50 gigabytes, if more contact admin.
- Package must include exported model

*Model requirements*

- One chunk
- One deth map
- One dense cloud
- One 3D model with textures  

The following data products are optional:
- Tiled model
- Orthomosaic 	
- DEM

```{warning}
Do not include annotations, back up project and remove from the to-be-uploaded dataset.
```

*Metadata requirements*

- A metadata file needs to be filled out for each data set.
The metadata file is used to populate the Svalbox database with.

````
`````
