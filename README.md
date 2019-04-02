
**This repository contains all code, scripts and datasets for recreating the evaluating cluster based MEC server placement algorithm**

The work has been published in MECOMM 2018. You can cite our work as follows:

> Nitinder Mohan, Aleksandr Zavodovski, Pengyuan Zhou, and Jussi Kangasharju. 2018. Anveshak: Placing Edge Servers In The Wild. In _Proceedings of the 2018 Workshop on Mobile Edge Communications_ (MECOMM'18). ACM, New York, NY, USA, 7-12. DOI: https://doi.org/10.1145/3229556.3229560

# Requirements
The code requires you to have the following packages installed.

 1. Python v3
 2. GraphLab
 3. R

# Directory Structure

 - **Dataset**: Contains required raw basestation and WiFi AP density, user requests and GPS coordinate data files.
 - **Edge_Server_Clustering**: R-based code files which creates density clusters of users and maps its to a physical location in a polygon og GPS coordinates.
 - **MilanoGridMap.ipynb**: Python code which maps WiFi Access points dataset to Milano grid (area of study in this work).
 - **Map Convert.ipynb**: Tags WiGle dataset of WiFi APs to GPS coordinates

> The code is commented and is self-explanatory. Still if you have any issues, feel free to reach me at nitinder.mohan@helsinki.fi
> 
