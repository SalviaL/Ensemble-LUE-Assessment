The released gpkg file, which is the polygons of statistical units, contains thousands of fields and could be mainly summarized into the following categories (fields that exist in GADM are not listed here).

Tab. 1 Field for geospatial and administrative information
| Field names | Description |
|-------------|-------------|
| UID | Unique ID for each polygon |
| RID_Regions | Economic region defined by the World Bank and its ID<br><br>1→Northern Africa<br>2→Sub-Saharan Africa<br>3→Northern America<br>4→Caribbean<br>5→Central America<br>6→South America<br>7→Central Asia<br>8→Eastern Asia | 9→South-eastern Asia<br>10→Southern Asia<br>11→Western Asia<br>12→Eastern Europe<br>13→Northern Europe<br>14→Southern Europe<br>15→Western Europe<br>16→Oceania |
| NRID_NRegions | Merged economic regions and their IDs<br><br>1→Asia-Pacific<br>2→N. America & Europe<br>3→Latin America | 4→N. Africa & W. Asia<br>5→Sub-Saharan Africa<br>6→Central & S. Asia |
| MergeID | Merged Unit GID_0 |

| Item | Description |
|------|-------------|
| interval | Statistical period interval (e.g., 5, 10, or 15 years) |
| year | Statistical year or statistical period together with <interval> (e.g. <interval>_<year> stands for period from <interval> years before to <year>) |
| prod | Data source or index statistical from Sometimes, <prod1>&<prod2> stands for a combination of datasets |
| index | Index of interest (igi) |
| | **Uc** - Built-up area |
| | **POP** - Total population |
| | **LCR** - Land consumption rate |
| | **PGR** - Population growth rate |
| | **LCRPGR** - LCR/PGR |
| | **IG** - Income group |
| | **HDI** - Human Development Index |
| | **BpC** - Built-up area per capita |
| | **BpCR** - BpC rate |
| | **mean<index>** - Average of igi |
| | **std<index>** - Standard variance of igi |
| | **cv<index>** - Coefficient of the variable of igi |
| | **cat<index>** - Classification of igi |
| | **trend<index>** - Trend classification of igi |
| | **WS<index>** - Weighted summary of igi |
