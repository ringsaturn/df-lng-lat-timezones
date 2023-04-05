# Convert lng,lat to timezone names in DataFrame

|                    | timezonefinder | tzfpy  |
| ------------------ | -------------- | ------ |
| Pandas             | 8.48 s         | 1.89 s |
| Pandas(Vectorized) | 6.09 s         | 396 ms |
| Polars             | 7 s            | 664 ms |
| NumPy              | 7.9 s          | 397 ms |

View it here:
[showcase.ipynb](https://nbviewer.org/github/ringsaturn/df-lng-lat-timezones/blob/main/showcase.ipynb)
