# SC-FAIR-22
These codes are all for creating graphs using KDEs. 
The file X and Y, plot points (X,Y) at which a radiation level higher than the backgroun radiation was recorded. It then uses the gaussian KDE in order to build an image
The file X and Rad plot X points at which a radiation level higher than the background radiation was recorded. It uses the gaussian KDE in order to build a 2-D image with radiation levels serving as the second "dimension".
The file Y and Rad plot Y points at which a radiation level higher than the background radiation was recorded. It uses the gaussian KDE in order to build a 2-D image with radiation levels serving as the second "dimension".

The values used in the array for the heat map are meant to be replaced by the estimated values in the KDE functions
  For now however, the matrix's values are set at 0
Do also note that constructing an image with the heatmap right now is not automated, meaning that the user must enter each value themselves in the matrix
