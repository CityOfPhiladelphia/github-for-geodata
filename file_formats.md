# File Formats

This page includes information on the open file formats that will be published to GitHub and issues to consider with each.

### GeoJSON
* **What is it**: geographic features in JavaScript Object Notation (JSON)
* **Primary use**: Web mapping - also arguably the easiest and most widely adopted format for visualization and analysis in most programming languages

### KMZ
* **What is it**: Compressed Keyhole Markup Language, an XML notation
* **Primary use**: Google Earth and Google Maps

### CSV
* **What is it**: Comma separated values
* **Primary use**: Excel and other spreadsheet-based tools; easy parsing and importing into a database
* Only makes sense for point feature classes where lat and lngs are columns in the spreadsheet

### Shapefile
* **What is it**: Esri’s geospatial vector format
* **Primary use**: Esri software and other desktop GIS suites
* Since a shapefile is made up of potentially seven files, it is also a good idea to provide a compressed (.zip) version of the shapefile
* Also, shapefile column names can be only 10 characters max. We should avoid column names getting truncated where possible.

### Markdown
* **What is it**: A plain text formatting syntax for rendering web content
* **Primary use**: native rendering of text on github.com
* Metadata about a dataset should be saved in a `README.md` file that will automatically be displayed on github.com



