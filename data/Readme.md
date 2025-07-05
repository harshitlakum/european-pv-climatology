# Dataset Information

This folder contains information and metadata related to the datasets used for the analysis of PV potential and climatology changes across Europe.

## Dataset Source

- **ERA5/ERA5-Land reanalysis data**
- Provider: Copernicus Climate Data Store (CDS)
- For full details and access, visit: https://cds.climate.copernicus.eu/

## Data Description

- Variables used: Potential Vorticity (PV), wind speed, and other relevant atmospheric parameters
- Temporal coverage: 1950–1960 and 2000–2010 (monthly data)
- Spatial coverage: Europe (latitude 35°N–71°N, longitude 25°W–40°E)
- File format: NetCDF (.nc)

## Data Preparation

- Data was downloaded from the Copernicus CDS portal
- Longitude coordinates converted from 0–360° to -180–180°
- Subsetting to the European region before analysis
- See scripts in the `/scripts/` folder for data processing steps

## Data Availability

**Note:** The ERA5/ERA5-Land data files are NOT included in this repository due to size and licensing restrictions.  
Users must register and download the data themselves from the [Copernicus CDS portal](https://cds.climate.copernicus.eu/).

## Citation

If you use the ERA5 or ERA5-Land data in your work, please cite as instructed by the Copernicus Climate Data Store:
> Hersbach, H., et al. (2020). The ERA5 global reanalysis. *Quarterly Journal of the Royal Meteorological Society*, 146(730), 1999–2049. https://doi.org/10.1002/qj.3803

## Contact

For questions about data preparation or usage, contact [harshitlakum2012@gmail.com].
