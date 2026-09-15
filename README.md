# Flight metrics for Iberian steppe birds

This repository contains the R code used to process GPS tracking data and derive the flight-metric products described in the Data Descriptor:

A curated and standardised dataset of flight metrics for Iberian steppe birds

The workflow was developed for five Iberian steppe bird species:

Little Bustard (Tetrax tetrax)

Great Bustard (Otis tarda)

Stone-curlew (Burhinus oedicnemus)

Pin-tailed Sandgrouse (Pterocles alchata)

Black-bellied Sandgrouse (Pterocles orientalis)

Repository contents

Each species is represented by an R Markdown (.Rmd) file and a rendered HTML (.html) version documenting the analytical workflow.

Repository structure:

.
├── README.md
├── LICENSE
├── Little_Bustard/
│   ├── Flight_metrics_Data_Paper_Tetrax_tetrax.Rmd
│   └── Flight_metrics_Data_Paper_Tetrax_tetrax.html
├── Great_Bustard/
│   ├── Flight_metrics_Data_Paper_Otis_tarda.Rmd
│   └── Flight_metrics_Data_Paper_Otis_tarda.html
├── Stone_Curlew/
│   ├── Flight_metrics_Data_Paper_Burhinus_oedicnemus.Rmd
│   └── Flight_metrics_Data_Paper_Burhinus_oedicnemus.html
├── Pin_tailed_Sandgrouse/
│   ├── Flight_metrics_Data_Paper_Pterocles_alchata.Rmd
│   └── Flight_metrics_Data_Paper_Pterocles_alchata.html
└── Black_bellied_Sandgrouse/
    ├── Flight_metrics_Data_Paper_Pterocles_orientalis.Rmd
    └── Flight_metrics_Data_Paper_Pterocles_orientalis.html


Input data and reproducibility

The repository documents the complete species-specific processing workflow, but it does not contain the raw GPS tracking data or geographic coordinates used in the analyses. These data are excluded because the locations of tracked birds are sensitive and are not part of the public data release.

Consequently, the scripts are not intended to reproduce the analysis directly from publicly available raw tracking data without access to the original source files. Users with appropriate source data can adapt the input paths and metadata fields described in the R Markdown files to apply the workflow to other tracking datasets.

Flight-height calculations additionally require the Spanish MDT02-cob2 2 m digital terrain model and the corresponding spatial indexing layer used to identify terrain tiles.

Published dataset

The processed data products associated with this repository are archived in Zenodo:

Crispim-Mendes, T. et al. (2026). A curated and standardised dataset of flight metrics for Iberian steppe birds. Zenodo.
https://doi.org/10.5281/zenodo.22767894

The Zenodo archive contains harmonised multi-species summary tables and species-level movement, boost-flight and flight-height products. Geographic coordinates are not included in the public archive.

Data Descriptor

This repository accompanies the manuscript:

Crispim-Mendes, T. et al. A curated and standardised dataset of flight metrics for Iberian steppe birds.
Scientific Data (manuscript in preparation/submission).

The final article citation and DOI will be added here after publication.
