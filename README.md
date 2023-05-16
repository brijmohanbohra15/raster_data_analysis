# Raster data analysis

## Radiometric Calibration
Jupyter notebook that will:
1) Read a band of Landsat-9 or Landsat-8 data
2) Mask the border values (zeros) to NaN
3) Display a histogram of DN values of the band
4) Calibrate the DN to Radiance using constants provided in the MTL file (manual inputs)
5) Convert radiance to Top-of-Atmosphere reflectance using constants provided in MTL file
6) Display the histogram of the radiance and reflectance values of the calibrated band
Function to
7) Display the images
8) Make a function to do the calibration
9) Make a function to read from MTL file

## Detect and Drop ==> Line drop out
Python program to detect a line drop-out – the output  show the line number (row number) of the line drop-out
Python program to replace the line drop-out by the average of the nearest two lines (top and bottom)
