# lakefetch: Calculate Fetch and Wave Exposure for Lake Sampling Points

The lakefetch package provides tools for calculating fetch (open water
distance) and wave exposure metrics for lake sampling points. It
downloads lake boundaries from OpenStreetMap, calculates directional
fetch using ray-casting, and optionally integrates with NHD for
hydrological context.

## Main Functions

- [`fetch_calculate`](https://docs.ropensci.org/lakefetch/reference/fetch_calculate.md):

  Main entry point for fetch calculation

- [`load_sites`](https://docs.ropensci.org/lakefetch/reference/load_sites.md):

  Load and validate site data

- [`get_lake_boundary`](https://docs.ropensci.org/lakefetch/reference/get_lake_boundary.md):

  Get lake boundary from OSM or file

- [`add_lake_context`](https://docs.ropensci.org/lakefetch/reference/add_lake_context.md):

  Add NHD hydrological context

- [`fetch_app`](https://docs.ropensci.org/lakefetch/reference/fetch_app.md):

  Launch interactive Shiny app

## Visualization

- [`plot_fetch_map`](https://docs.ropensci.org/lakefetch/reference/plot_fetch_map.md):

  Map of sites colored by exposure

- [`plot_fetch_bars`](https://docs.ropensci.org/lakefetch/reference/plot_fetch_bars.md):

  Bar chart of effective fetch

- [`plot_fetch_rose`](https://docs.ropensci.org/lakefetch/reference/plot_fetch_rose.md):

  Rose diagram for single site

- [`create_ray_geometries`](https://docs.ropensci.org/lakefetch/reference/create_ray_geometries.md):

  Create ray lines for mapping

## Configuration

- [`lakefetch_options`](https://docs.ropensci.org/lakefetch/reference/lakefetch_options.md):

  Get/set package options

- [`lakefetch_reset_options`](https://docs.ropensci.org/lakefetch/reference/lakefetch_reset_options.md):

  Reset options to defaults

## See also

Useful links:

- <https://docs.ropensci.org/lakefetch/>

- <https://github.com/ropensci/lakefetch>

- Report bugs at <https://github.com/ropensci/lakefetch/issues>

## Author

**Maintainer**: Jeremy Lynch Farrell <farrej2@rpi.edu>
