# world-json
Multiple JSON files contains all world cities with names, longitude & latitude, country, and timezone. Those file are based on [GeoNames](https://www.geonames.org/) and [Wikipedia](https://www.wikipedia.org/) databases.

# Structure
```ssh
n              <- name
cc             <- country code
a3             <- ISO CODE ALPHA 3
i              <- Info (State etc..)
t              <- timezone
geometry       <- object contains a point (long and lat)
```
# Files
```
geo_data_compressed.json    <- all cities with < 1000 population
```

# Notes
- This data provided as "is"
- Please let me know if i missed a resource or dependency
- Do not forget to check GeoNames and Wikipedia for the full db
