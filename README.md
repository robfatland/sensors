# sensors

This [repository](https://github.com/robfatland/sensors) is repurposed (2024) to ***sensors*** from its
original purpose of oceanographic data science. The objective now is to provide clear explanations
of sensors and to support construction of good datasets from these sensors. 


- [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/robfatland/sensors/HEAD)


- To work on a clone of this repository
    - Establish a stable Jupyter notebook server environment
    - `git clone https://github.com/robfatland/sensor`
    - run notebooks and be prepared to install packages as needed (`xarray`, `matplotlib` and so on)


# 2024 rebuild left off here

- das
- sp
- und so weiter


The work here centers on **shallow profilers** located in the
[Regional Cabled Array (RCA)](https://interactiveoceans.washington.edu); 
in turn a large component of NSF's Ocean Observatories Initiative (OOI). 
Additional datasets are featured that originate in other programs 
([RCA cruise data](https://alfresco.oceanobservatories.org/), 
ARGO, 
MODIS and so on).


An RCA shallow profiler rests at a depth of 200 meters below the surface and transits the upper 
water column nine times per day. These nine excursions include two 
intervallic ('with pauses') profiles that accommodate equilibration of a pH sensor. 


<img src="https://github.com/robfatland/ocean/blob/main/Images/rca/shallow%20profiler%20platform%202%20OSB%20pool.png" alt="drawing" width="500"/>



## Structure of this Repository

- Overview: This **`README.md`** markdown file
- Primary BioOptics narrative: **`BioOptics.ipynb`** Jupyter notebook
- Subdirectories
    - **`Images`** are images from the project organized into categories
    - **`RepositoryData`** contains (smaller-sized) datasets
        - Contrasted with an external **`../data`** directory for larger datasets
    - **`Profiles`** contains metadata on the timing of shallow profiler ascent/descent/rest intervals
    - **`binder`** contains information on building sandbox versions of this repository using the [**binder**](https://mybinder.org) service


## Additional Notes


### Python and related libraries


The Jupyter notebooks in this repository include Python 3 code and refer to a set of common geospatial analysis libraries. These include
`dask`, `XArray`, `pandas`, `matplotlib`, and `numpy`. Timing is managed using the (**numpy**) datatime64 utility.



### How to create the binder feature for a GitHub repository


- Reduce the source data to a few Megabytes so it can reside in the repository
- Add a subfolder `binder` and an `environment.yml` file as shown given below
- Add a binder badge linking to this repo

Binder link: 

```
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/robfatland/ocean/HEAD)
```


Within the `binder` folder the `environment.yml` file reflects necessary libraries / packages: 


```
channels:
  - conda-forge
dependencies:
  - python=3
  - numpy
  - pandas
  - matplotlib
  - netcdf4
  - xarray
  - ffmpeg
```


### Configuration notes

* One may be obliged to `conda install dask`

