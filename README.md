# Visualization Final Project

### By Sinan Asav and Nur Azreik

In this project, we analyse and visualize two datasets as part of the Visualization examination at the University of Göttingen.

The first part examines members of the German Bundestag. It studies the composition of parliament over different election periods, including political parties, gender, age, academic titles, membership duration, marital status, and children.

The second part examines confirmed exoplanets from the NASA Exoplanet Archive. It explores how and where exoplanets were discovered, the facilities and discovery methods involved, the development of discoveries over time, and the distributions and relationships between planetary and host-star parameters.

## Data Sources

### German Bundestag

The original data is provided by the German Bundestag and can be found at:

[German Bundestag Open Data](https://www.bundestag.de/services/opendata)

The dataset was processed and simplified for the examination.

The file `mdb-data.xml` is encoded in UTF-8 and structured as an XML tree. A definition of the XML structure is provided in the file `mdb_data.dtd`.

### NASA Exoplanet Archive

The original data is provided by the NASA Exoplanet Archive and can be found at:

[NASA Planetary Systems Composite Parameters](https://exoplanetarchive.ipac.caltech.edu/cgi-bin/TblView/nph-tblView?app=ExoTbls&config=PSCompPars)

The dataset was processed and simplified for the examination. Only selected parameters are included, and measurement uncertainties are not considered.

The CSV file is encoded in UTF-8 and uses a semicolon (`;`) as the column separator.

Definitions of the NASA Exoplanet Archive columns are available at:

[NASA Exoplanet Archive Column Definitions](https://exoplanetarchive.ipac.caltech.edu/docs/API_PS_columns.html)
