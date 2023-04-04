# Convert lng,lat to timezone names in DataFrame

|                    | timezonefinder | tzfpy  |
| ------------------ | -------------- | ------ |
| Pandas             | 11.3 s         | 2.51 s |
| Pandas(Vectorized) | 8.1 s          | 507 ms |
| Polars             | 8.19 s         | 790 ms |

View it here:
[showcase.ipynb](https://nbviewer.org/github/ringsaturn/df-lng-lat-timezones/blob/main/showcase.ipynb)
