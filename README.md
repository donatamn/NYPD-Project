# NYPD Shooting Incident Data Report (Historic)

**Author:** Damlanur Onat  
**Render:** Knit `NYPD_final.Rmd` → HTML (or PDF)

## What’s here
- `NYPD_final.Rmd` — fully reproducible report
- `NYPD_final.html` — knitted output
- Minimal dependencies: `tidyverse`, `lubridate`

## Data source
NYPD Shooting Incident Data (Historic):  
https://data.cityofnewyork.us/api/views/833y-fsy8/rows.csv?accessType=DOWNLOAD

The report fetches the CSV at knit time; no data files are stored in this repo.

## How to knit
In RStudio: **Knit** → HTML.  
Or from R:
```r
rmarkdown::render("NYPD_final.Rmd", output_format = "html_document")
