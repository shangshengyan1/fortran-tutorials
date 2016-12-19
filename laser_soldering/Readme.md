# In this tutorial, the modules 
1. calcdiam.f90
2. interpolate.f90 
are utilized to calculate respectively:
1. diameter of an imc from the measured numbers of IMCs per sq. micrometers area (numratio) with the assumption that the IMC morphology 
is scalloped and has spherical top. 
# d = sqrt(4/(pi*numratio))
Also, do loop is utilized to get an array of diameters for given values of numratio.
2. interpolated values of diameter for a given point of laser scan speed provided that measured values of two laser speeds 
and corresponding diameters of IMCs are given.