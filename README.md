# WallSpray
Data repository created for experiments on waves impacting a vertical wall and the droplet sizes produced by them.

This repository contains the results of experiments performed in the wave tank of the Hydrodynamics Laboratory of the University of Oslo.

The data of droplets dynamics after a impact is obtained by means of 3DPTV. The data is stored in the files "particles-section1.csv" and "particles-section2.csv"

This set of data is organized as a Pandas DataFrame containing the next labels:

- time:time where the droplet is presented (in seconds)
- size: droplets equivalent diameter (in mm)
- x: position in x direction along the tank (in meters)
- y: position in y direction along the vertical axis (in meters)
- z: position in z direction perpendicular to the tank direction (in meters)
- u: velocity in the x direction (in m/s)
- v: velocity in the y direction (in m/s)
- w: velocity in the z direction (in m/s)
- acc_x: acceleration in the x direction (in m/s)
- acc_y: acceleration in the y direction (in m/s)
- h: correspond to the non dimensional wave amplitude 
- wall: the wall height for each case (in millimeters)
