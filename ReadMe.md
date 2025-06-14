# Invisible Breath by Anton Jayakody GSCOMP205

## Commands to run

1. Activating the venv

```
.\gis\Scripts\Activate.ps1
```

** VENV SETUP:
pip install jupyter pandas geopandas pyarrow imageio matplotlib shapely fiona pyproj rtree mapclassify
**

2. jupyter NoteBook Set Up

```
jupyter notebook
```

|     | who_region | iso3 | country_name | city         | year | version                                    | pm10_concentration | pm25_concentration | no2_concentration | pm10_tempcov | no2_tempcov | type_of_stations                 | reference | web_link | population | population_source          | latitude  | longitude | who_ms | geometry                  |
| --- | ---------- | ---- | ------------ | ------------ | ---- | ------------------------------------------ | ------------------ | ------------------ | ----------------- | ------------ | ----------- | -------------------------------- | --------- | -------- | ---------- | -------------------------- | --------- | --------- | ------ | ------------------------- |
| 0   | 4_Eur      | ESP  | Spain        | A Coruna/ESP | 2013 | V4.0 (2018), V4.0 (2018), V4.0 (2018), ... | 23.238             | 11.491             | 28.841            | 87.0         | 93.0        | Urban, Urban, Suburban           | NaN       | NaN      | 246146.0   | manual, manual, manual,... | 43.3679   | -8.418571 | 1.0    | POINT (-8.41857 43.3679)  |
| 1   | 4_Eur      | ESP  | Spain        | A Coruna/ESP | 2014 | V6.0 (2023), V6.0 (2023), V6.0 (2023)      | 27.476             | 15.878             | 19.575            | 96.0         | 95.0        | Urban, Urban, Suburban           | NaN       | NaN      | 247604.0   | NaN                        | 43.368033 | -8.418233 | 1.0    | POINT (-8.41823 43.36803) |
| 2   | 4_Eur      | ESP  | Spain        | A Coruna/ESP | 2015 | V6.0 (2023), V6.0 (2023), V6.0 (2023), ... | 25.515             | 14.004             | 22.731            | 98.0         | 98.0        | Urban, Urban, Suburban, Suburban | NaN       | NaN      | 247604.0   | NaN                        | 43.370375 | -8.4229   | 1.0    | POINT (-8.4229 43.37038)  |
| 3   | 4_Eur      | ESP  | Spain        | A Coruna/ESP | 2016 | V6.0 (2023), V6.0 (2023), V6.0 (2023), ... | 23.057             | 13.160             | 20.204            | 98.0         | 98.0        | Urban, Urban, Suburban, Suburban | NaN       | NaN      | 247604.0   | NaN                        | 43.370375 | -8.4229   | 1.0    | POINT (-8.4229 43.37038)  |
| 4   | 4_Eur      | ESP  | Spain        | A Coruna/ESP | 2017 | V6.0 (2023), V6.0 (2023), V6.0 (2023), ... | 26.849             | 14.114             | 21.543            | 97.0         | 98.0        | Urban, Urban, Suburban, Suburban | NaN       | NaN      | 247604.0   | NaN                        | 43.370375 | -8.4229   | 1.0    | POINT (-8.4229 43.37038)  |

|     | year | CONTINENT     | pm10_concentration |
| --- | ---- | ------------- | ------------------ |
| 0   | 2010 | Africa        | 66.463455          |
| 1   | 2010 | Asia          | 179.332368         |
| 2   | 2010 | Europe        | 25.915942          |
| 3   | 2010 | North America | 22.739640          |
| 4   | 2010 | Oceania       | 19.053400          |
