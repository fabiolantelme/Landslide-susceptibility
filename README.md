# Landslide-susceptibility

# Objective
Map landslide susceptibility in the Maira valley in southern Piedmont

# Data
- Piedmont DTM25
- BDTRE 2024 - GeoTopographic Database (for each municipality) 1:5000
- Raster BDTRE 2023 BN 1:10000
- Arpa Piemonte - BDGeo 100 - Instable Areas 1:100000
- Forest fires areas and starting points PIEDMONT 1:10000
- Mean precipitation since 2002

# Method
- Slope identification
- Mean precipitation data interpolation using SAGAGIS to obtain total coverage of the area
- Considration of wildfires of less than 10 years old and more than 0,2 ha
- Soil coverage classification from BDTRE 2024. Coefficient (ranging from 0,1 to 0,8) given at each type of soil coverage
- Road and Building classification using the same methoda as former
- Data normalization and final map calculation

# Tools
- SAGAGIS
- QGIS
- EXCELL

# Result
Landslide suceptibility map
