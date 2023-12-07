# <ins> About The Project </ins>
This project seeks to create a dead reckoning algorithm for AUV localization using an IMU, also exploring into the performance with the integration of other inputs, position and velocity updates with GPS and DVL.  The dataset is simulated IMU data using the parameters of the Bosch BNO055 9 degrees-of-freedom (DOF) MEMS IMU.

[AUV Localization: Open Loop DR Implementation](https://github.com/ryangochar/AUVlocalization/blob/main/AUV_OpenLoopDR_Final.ipynb)

[Matlab Code](matlab/)

[Final Report](https://github.com/ryangochar/AUVlocalization/blob/main/AUVlocalization%20-%20Final%20Report%20-%20DavisB%20GocharR.pdf)

[Final Presentation](https://github.com/ryangochar/AUVlocalization/blob/main/AUV%20Localization%20Presentation.pdf)


# <ins> Getting Started </ins>
```
conda env create -f environment.yml
```

# <ins> Install Required Packages: </ins>
- `numpy`
- `pandas`
- `matplotlib`
- `pykalman`
- `utm`

# <ins> Open-Source Libraries </ins>

### Matlab

https://github.com/cybergalactic/MSS

### Python

https://github.com/Aceinna/gnss-ins-sim

[pykalman](https://pykalman.github.io/#)

# <ins> Usage </ins>
Excecute code [here](https://github.com/ryangochar/AUVlocalization/blob/main/AUV_OpenLoopDR_Final.ipynb)

Dataset: [Bosch BNO055 IMU Data](https://github.com/ryangochar/AUVlocalization/tree/main/2023-11-17-15-11-06)

Project can be run exactly as is. All sections are labeled. 

# <ins> License </ins>
Distributed under the University of Florida licinse. 

# <ins> Authors </ins>
Ryan Gochar - ryangochar@ufl.edu

Brandon Davis - brandon.davis1@ufl.edu

# <ins> References </ins> 

[Accurate indoor positioning with ultra-wide band sensors](https://journals.tubitak.gov.tr/cgi/viewcontent.cgi?article=1398&context=elektrik)
[Improved Dead Reckoning Localization using IMU Sensor](https://ieeexplore.ieee.org/document/10010239)
[A New Approach to Linear Filtering and Prediction Problems](https://asmedigitalcollection.asme.org/fluidsengineering/article-abstract/82/1/35/397706/A-New-Approach-to-Linear-Filtering-and-Prediction?redirectedFrom=fulltext)
[Accuracy analysis of DVL/IMU/magnetometer integrated navigation system using different IMUs in AUV](https://ieeexplore.ieee.org/document/5524143)
T. I. Fossen, Handbook of Marine Craft Hydrodynamics and Motion Control

# Thank You! 
