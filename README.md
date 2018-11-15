# CDN_File_Creation
This program will read netCDF files present in directory "input" and find 5 min average of atmos_pressure and temp_mean from file which has met in the file name. The names of the "atmos_pressure" and "temp_mean" is changed to "atmospheric_pressure" and "mean_temperature" respectively. The average value in saved in the "output" directory with file name same as input except the met is changed to metavg. Along with "mean_temperature" and "atmospheric_pressure", time is saved in the output file. 

Two pytest functions are mentioned for testing python. 

Note: 
1. Change the rootdir according to place where files are saved and please create input and output directory.
2. Packages to be installed are numpy, pip, netCDF4, Cyton, os, 
