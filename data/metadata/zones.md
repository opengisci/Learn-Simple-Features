- `Title`: Zones of Central Falls
- `Abstract`: Fabricated data on four administrative zones of Central Falls with socio-economic data.
- `Spatial Coverage`: Central Falls, RI
- `Spatial Resolution`: 250 meters
- `Spatial Reference System`: EPSG:6567 NAD83(2011) / Rhode Island
- `Spatial Representation Type`: vector polygons
- `Temporal Coverage`: N/A
- `Temporal Resolution`: N/A there is no temporal dimension to the data
- `Lineage`: Data fabricated by Joseph Holler using QGIS.
- `Distribution`: Contact Professor Holler.
- `Constraints`: Legal constraints for *access* or *use* to protect *privacy* or *intellectual property rights*
- `Data Quality`: Data is fabricated and not fit for use in any real applications.
- `Variables`: For each variable, enter the following information. If you have two or more variables per data source, you may want to present this information in table form (shown below)
  - `Label`: variable name as used in the data or code
  - `Alias`: intuitive natural language name
  - `Definition`: Short description or definition of the variable. Include measurement units in description.
  - `Type`: data type, e.g. character string, integer, real
  - `Accuracy`: e.g. uncertainty of measurements
  - `Domain`: Expected range of Maximum and Minimum of numerical data, or codes or categories of nominal data, or reference to a standard codebook
  - `Missing Data Value(s)`: Values used to represent missing data and frequency of missing data observations
  - `Missing Data Frequency`: Frequency of missing data observations: not yet known for data to be collected

| Label | Alias | Definition | Type | Accuracy | Domain | Missing Data Value(s) | Missing Data Frequency |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| id | id | unique identificaion number (primary key) | integer | n/a | nominal integer ID's | none | none |
| zone | zone | Zone name | Text string | n/a | nominal zone names | none | none |
| pop | population | Total population | integer | +/-49 | integer counts ranging from 4400 to 5300  | none | none |
