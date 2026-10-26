# EarthOS data

City layers built by EarthOS, served by GitHub Pages so a map can read them in pieces
(HTTP range requests):

    https://raghavk31.github.io/earthos-data/<city>/<city>.pmtiles
    https://raghavk31.github.io/earthos-data/<city>/cog/<layer>.tif

Each city folder has a `CREDITS.md`: what every layer is built from and the licence it carries.
There is no single licence for this repo. Each layer keeps its sources' terms, including
share-alike (ODbL) and non-commercial (CC BY-NC-SA) ones.

| city | files |
|---|---|
| Bengaluru | [bengaluru/](bengaluru/CREDITS.md) |

Files are written by `python -m earthos publish <city> <this repo>`; don't edit them by hand.
