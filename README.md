[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/acoiman/mapping_earthquakes/master)

# Title

Retrieving, Analyzing and Visualizing georeferenced data of earthquakes near [Fiji](https://es.wikipedia.org/wiki/Fiyi) since 1964

## Introduction

These set of notebooks will show you how to map earthquakes from a database using standard ***Python*** and ***Folium*** libraries. The database was filled out from  a CSV file obtained from the [Rdatasets](https://vincentarelbundock.github.io/Rdatasets/).

`Rdatasets` is a collection of over 1300 datasets that were originally distributed alongside the statistical software environment R and some of its add-on packages. 

### Prerequisites

See [requirements.txt](requirements.txt) and [runtime.txt](runtime.txt) for details about the required packages to deploy the notebooks.


## Deployment

This repository contains three notebooks:

1. [reading_dataset.ipynb](reading_dataset.ipynb): contains the code to read through the `Rdatasers` and look for dataset links containing the terms ***latitude*** and ***longitude***.

2. [db_earthquakes.ipynb](db_earthquakes.ipynb) creates a database from the [selected dataset](https://vincentarelbundock.github.io/Rdatasets/csv/datasets/quakes.csv)  and computes some spatial statistics.

3. [map_earthquakes.ipynb](map_earthquakes.ipynb) takes the database data and creates a web map using the [Folium](https://pypi.org/project/folium/) package.

To reproduce the results run the above notebooks in the same order on [Binder](https://mybinder.org/).

Additionally, there is a file named [map.html](https://acoiman.github.io/maps/map.html) showing the final result.


## Author

* **Abraham Coiman** - [acoiman](https://acoiman.github.io/)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Thanks to [Coursera](https://www.coursera.org/)'s financial aid I could complete the Python Specialization [Python for Everybody](https://www.coursera.org/specializations/python)  that allowed me to obtain the essentials insights to write the above-mentioned notebooks.
