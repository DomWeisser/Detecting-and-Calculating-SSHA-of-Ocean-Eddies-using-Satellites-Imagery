# Detecting and Calculating SSHA of Ocean Eddies Using Satellite Imagery

# Project Description
This project shows how to leverage Sentinel-3 altimetry data to detect ocean eddies in the Arctic. The detection is achieved by calculating Sea Surface Height Anomalies (SSHA) and 
applying optimal interpolation via GPSat to resolve the target eddy structure.

* **Notebook 1: Selection and Acquisition**
  * Utilises the Mesoscale Eddy Trajectory Atlas to identify candidate eddies
  * Automates the download of satellite imagery intersecting the target region

* **Notebook 2: Processing and Interpolation**
  * Computes the SSHA from the raw Sentinel-3 altimetry data
  * Uses GPSat to optimally interpolate the SSHA, allowing for the identification and analysis of the ocean eddies within the region of interest

# Getting Started
### Required Packages
The `GPSat` source code is included directly in this repository, so you do not need to download it separately. The notebooks are configured to automatically detect the `GPSat` folder.

However, you must install the required Python libraries for the project to run.
```bash
pip install -r requirements.txt
```

### Sentinel Data
The Sentinel-3 altimetry data is sourced from the Copernicus browser via https://browser.dataspace.copernicus.eu/. An account is needed before you can download any images.


# Acknowledgements
This project formed part of the module 'AI4EO' at UCL run by Dr Michel Tsamados. 
