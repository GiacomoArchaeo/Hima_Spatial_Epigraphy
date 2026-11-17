# Spatial Epigraphy at Ḥimā: analysis code

Analysis for Fontana, G. and Prioletta, A., "Spatial Epigraphy at Ḥimā: Two Scales of Mobility Revealed by 18,904 Rock Inscriptions in Ancient Arabia".

-   `Full_Analysis.qmd`: the analysis notebook (R and Quarto). Run `quarto render Full_Analysis.qmd` from this folder; figures are written to `figures/`.
-   `Full_Analysis.html`, `figures/`: the rendered report and figures, from a run with the full data.
-   `input/`: study area, Copernicus GLO-30 DEM and the landscape covariates (EPSG:32636).

Not included: the inscription records (`hima_db.gpkg`, Saudi-French Archaeological and Epigraphic Mission to Najran, available on request from A. Prioletta), the bedrock polygons (`rock_outcrops.gpkg`, Saudi Geological Survey; Greenwood 1985) and the satellite background (`satellite.tif`, Esri World Imagery).

Copernicus WorldDEM-30 © DLR e.V. 2010–2014 and © Airbus Defence and Space GmbH 2014–2018, provided under COPERNICUS by the European Union and ESA. Imagery: Esri, Vantor, Earthstar Geographics, and the GIS User Community.

License: MIT (see `LICENSE`).

Contact: Giacomo Fontana ([giacomo.fontana\@ttu.edu](mailto:giacomo.fontana@ttu.edu))
