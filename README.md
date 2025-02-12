[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.14860960.svg)](https://doi.org/10.5281/zenodo.14860960)


# Sentinel-1 Data Retrieval and Analysis

## Overview
This repository contains a Jupyter Notebook that retrieves and analyzes **Sentinel-1 SAR data** over a specified scene using the **Copernicus Open Access Hub API**. The workflow includes data discovery, downloading, and preliminary analysis of Sentinel-1 imagery for remote sensing applications. It also the data avilbility of two pre-defined locations. The naming convention of S1 data was used to group them according to different categories such as orbit direction, poralisation, acquisition time. 

## Features
- Query Sentinel-1 scenes based on **time, location, and sensor mode**  
- Download Sentinel-1 **GRD/SLC** products via Copernicus API  


## Data Sources
- **Sentinel-1 SAR Data**: Retrieved via **Copernicus Open Access Hub**  

## Software & Dependencies 

To install dependencies, run:  
```bash
pip install -r requirements.txt
