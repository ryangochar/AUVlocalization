# About The Project 
This project seeks to create a dead reckoning algorithm for AUV localization using an IMU, also exploring into the performance with the integration of other inputs, position and velocity updates with GPS and DVL.  The dataset is simulated IMU data using the parameters of the Bosch BNO055 9 degrees-of-freedom (DOF) MEMS IMU.

[AUV Localization: Open Loop DR Implementation](https://github.com/ryangochar/AUVlocalization/blob/main/AUV_OpenLoopDR_Final.ipynb)

[Matlab Code](matlab/)

[Final Report](https://github.com/ryangochar/AUVlocalization/blob/main/AUVlocalization%20-%20Final%20Report%20-%20DavisB%20GocharR.pdf)

[Final Presentation](https://github.com/ryangochar/AUVlocalization/blob/main/AUV%20Localization%20Presentation.pdf)


# Getting Started
```
conda env create -f environment.yml
```

## Install Required Packages: 
- `numpy`
- `pandas`
- `matplotlib`
- `pykalman`
- `utm`

## Open-Source Libraries

### Matlab
https://github.com/cybergalactic/MSS

### Python
https://github.com/Aceinna/gnss-ins-sim

### pykalman
https://pykalman.github.io/#

# Usage
Excecute code [here](https://github.com/ryangochar/AUVlocalization/blob/main/AUV_OpenLoopDR_Final.ipynb)

Dataset: [Bosch BNO055 IMU Data](https://github.com/ryangochar/AUVlocalization/tree/main/2023-11-17-15-11-06)

Project can be run exactly as is. All sections are labeled. 

# License 
Distributed under the University of Florida licinse. 

# Authors
Ryan Gochar - ryangochar@ufl.edu

Brandon Davis - brandon.davis1@ufl.edu

### Thank You! 
