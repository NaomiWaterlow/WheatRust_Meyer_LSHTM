# WheatRust_Meyer_LSHTM
This repo contains a susbet of the Wheat Rust geolocation data from Meyer et al 2021, as well as corresponding Satelite data.

## Disease data
Data from Meyer et al. ([link](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0245697)) was subsetted to only include October-November 2017, and an ID was attached to each datapoint. This ID corresponds to the IDs in the Satelite data discussed below. This date is stored in file wheat_survey_2017.csv.

## Satelite data
The dataset contains point-level samples of Sentinel-2 Level-1C (TOA) optical bands and Sentinel-1 radar (VV/VH) over Ethiopia for October–November 2017. Sentinel-2 images were filtered by date, cloud coverage (<60%), and clipped to the study area, with clouds masked using the QA60 band; all bands were resampled to 10 m resolution. Values from each image were extracted at survey point locations, and only points with valid data were kept. For points with multiple samples on the same date, values were averaged per ID and date. The resulting tables provide cleaned, aggregated time series of optical and radar observations ready for analysis. This data is stored in files sentinel1_time.csv and sentinel2_time.csv. 
