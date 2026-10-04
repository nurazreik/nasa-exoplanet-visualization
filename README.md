# NASA Exoplanet Visualization Project

### By Nur Azreik

This project analyses and visualizes data from the **NASA Exoplanet Archive** as part of the Visualization examination at the University of Göttingen.

The project explores how confirmed exoplanets were discovered, which facilities and discovery methods contributed to their detection, how discoveries developed over time, and how planetary and host-star properties are distributed and related to one another.

The analysis includes topics such as:

- Exoplanet discovery methods
- Discovery facilities
- Development of discoveries over time
- Galactic latitude and longitude of discoveries
- Planet radius and system distance
- Performance of different discovery methods
- Distributions of planetary and stellar parameters
- Joint relationships between selected parameters
- Pearson and Spearman correlations

The main analysis is contained in:

`NASA_Exoplanet_Archive_Analysis.ipynb`

## Data Source

The original data is provided by the **NASA Exoplanet Archive**:

[NASA Planetary Systems Composite Parameters](https://exoplanetarchive.ipac.caltech.edu/cgi-bin/TblView/nph-tblView?app=ExoTbls&config=PSCompPars)

The dataset used for the examination was processed and simplified from the original archive. Only selected parameters are included, and measurement uncertainties are not considered.

The CSV dataset is encoded in UTF-8 and uses a semicolon (`;`) as the column separator.

Definitions of the NASA Exoplanet Archive columns are available here:

[NASA Exoplanet Archive Column Definitions](https://exoplanetarchive.ipac.caltech.edu/docs/API_PS_columns.html)

## Technologies

The analysis was created in Python using Jupyter Notebook and common data-analysis and visualization libraries.

See `requirements.txt` for the required Python packages.
