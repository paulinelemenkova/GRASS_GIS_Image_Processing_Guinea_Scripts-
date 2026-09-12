# GRASS GIS Scripts — Automated Land-Cover Classification of Guinea, West Africa

GRASS GIS shell scripts used to produce the figures in the peer-reviewed article by Polina Lemenkova. The scripts implement an automated algorithm to retrieve land-cover types in Guinea, West Africa, from a Landsat-8 OLI/TIRS time series (2014, 2018, 2023).

**Published in:** *Ovidius University Annals of Constanta – Series: Civil Engineering* **2025**, *25*(1), 19–36
**DOI:** https://doi.org/10.2478/ouacsce-2025-0005
**Journal (open access):** https://revista-constructii.univ-ovidius.ro/2024/02/16/an-automated-algorithm-of-grass-gis-to-retrieve-the-data-on-land-cover-types-in-guinea-west-africa-from-landsat-8-oli-tirs-images/
**HAL:** https://hal.science/hal-04463330
**Zenodo:** https://doi.org/10.5281/zenodo.10673287
**SSRN:** https://ssrn.com/abstract=4729742

## Contents
One script per year (2014, 2018, 2023), each calling GRASS GIS modules for raster import, band grouping (i.group), unsupervised clustering (i.cluster, k-means, 10 classes), maximum-likelihood classification (i.maxlik), rejection-probability mapping and cartographic display, with per-year clustering reports.

## Citation
Lemenkova, P. An automated algorithm of GRASS GIS to retrieve the data on land cover types in Guinea, West Africa, from Landsat-8 OLI/TIRS images. *Ovidius University Annals of Constanta – Series: Civil Engineering* **2025**, *25*(1), 19–36. https://doi.org/10.2478/ouacsce-2025-0005
