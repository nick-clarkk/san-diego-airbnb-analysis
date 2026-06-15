# San Diego Airbnb Market Analysis

An exploratory analysis of San Diego Airbnb listings using data from 
[Inside Airbnb](http://insideairbnb.com) (scraped September 2025).

## Key Findings
- San Diego is an entire-home market — 87% of listings are entire homes averaging $276/night
- Price is strongly driven by coastal proximity, with La Jolla and Mission Bay commanding significant premiums over inland areas
- Superhost status is a weak differentiator — price differences are negligible and review scores are inflated platform-wide
- Occupancy peaks in July (~48%) and bottoms out in December (~26%), confirming a summer beach-driven demand pattern

## Tools & Libraries
Python, DuckDB, pandas, matplotlib, seaborn, folium

## Data
Source: [Inside Airbnb](http://insideairbnb.com) — San Diego, September 2025  
~11,000 listings after cleaning, one year of forward-looking calendar data

## How to Run
1. Clone the repository
2. Create the conda environment: `conda env create -f environment.yml`
3. Open `notebooks/ExplorationAirbnb.ipynb` in Jupyter
