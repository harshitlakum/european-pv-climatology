# PV Potential and Climatology Changes Across Europe (1950–2010)

This repository provides an analysis and visualization of potential vorticity (PV pot) changes across Europe for the periods 1950–1960 and 2000–2010. It also estimates the land area required to meet all of Europe’s energy demand using photovoltaic (PV) panels.

## Key Questions

1. How has PV potential changed across Europe from 1950–1960 to 2000–2010?
2. How much European land area would be needed to satisfy all energy demand with PV?

## Repository Structure

- data/  
  Dataset info and metadata (see data/README.md)
- scripts/  
  Python and Bash scripts for data processing and plotting
- gifs/  
  Animated GIFs for all major results and comparisons
- requirements.txt  
  Python dependencies
- README.md  
  This file

## Data & Preprocessing

- Uses ERA5/ERA5-Land reanalysis data (not included here).
- For dataset details and download instructions, see data/README.md.
- Data is processed for all years and months using custom Python and Bash scripts.
- The European area is defined by latitude 35°N–71°N and longitude 25°W–40°E, with longitudes converted from 0–360° to -180–180°.

## Workflow

1. Download and prepare data (see data/README.md).
2. Run preprocessing and analysis scripts (located in scripts/) to calculate PV potential and create monthly climatology maps.
3. Generate PNG images and GIFs for visualization.
4. Visualize and interpret results using the GIFs below.

## Main Visualizations

### PV Changes Across Europe: 1950–1960
![PV Changes 1950–1960](gifs/pv_changes_1950_1960.gif)

### PV Changes Across Europe: 2000–2010
![PV Changes 2000–2010](gifs/pv_changes_2000_2010.gif)

### Comparison: 1950–1960 vs. 2000–2010
![PV Changes Comparison](gifs/comparison_1950_2010.gif)

### Estimated PV Area Needed for Europe’s Energy Needs
![PV Area Needed](gifs/pv_area_needed.gif)

## How to Reproduce

1. Place required data files in the data/ folder as described in data/README.md.
2. Install dependencies:
    pip install -r requirements.txt
3. Run analysis and plotting scripts from the scripts/ folder, for example:
    python scripts/calc_pvpot.py
    python scripts/create_gif.py
4. View the output GIFs in the gifs/ folder.

## Related Files

- data/README.md: Dataset and metadata details  
- scripts/: Data processing and plotting scripts  
- gifs/: Output GIF animations  
- requirements.txt: Python dependencies

## Credits

- ERA5/ERA5-Land datasets (Copernicus Climate Data Store)
- Code and analysis by Harshit Lakum

## Contact

For questions, suggestions, or collaboration, please open an issue or contact [harshitlakum2012@gmail.com].
