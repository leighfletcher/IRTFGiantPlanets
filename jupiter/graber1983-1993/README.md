Note: A Antunano JUN 2020. Leicester, UK

* The data in this directory were captured by AT1 at the IRTF between 1983 and 1993. These data were previosuly reduced and mapped by Kevin and Padma (Q-band). 

* Antunano calibrated the data using "abscalib_aa.pro" IDL code. This basically uses the calibration algorithm from DRM and scales the data to Voyager IRIS and/or Cassini CIRS profiles. She did not map the images herself.

** Warning: The calibration should be checked before using these data! We have shown in previous studies that the calibration is not perfect and a scaling of the radiance is necessary. This is because sometimes, multiple observations in a single filter during the same night can show slightly different latitudinal radiance profiles, given the sampling of different jovian longitudes and variable telluric conditions during the night. This can lead to slight differences in the radiometric scaling to the CIRS/IRIS profiles from observation to observation.

A detailed description of the absolute calibration error and scaling uncertainties is given in Antunano et al. (2020, JGR).

** Warning 2: When using ds9 command to visualize the images in the terminal (.fits files), these images show some kind of weird patches at the edge of the planet. However, when reading these files with 'read_fits' function in IDL the images look good. ds9 works perfectly when visualizing the cylindrical maps (cmap.fits) and the corresponding emission angle files (mu.fits).


