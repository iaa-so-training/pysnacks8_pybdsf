# PySnacks 8: PyBDSF

This repository is for the workshop materials. For details on the event visit the [PySnacks 8: PyBDSF](https://indico.iaa.csic.es/event/17/) event webpage.

## PySnacks
Within the  Severo Ochoa Training Initiative of the IAA-CSIC we are offering short introductory practical courses about Python packages for astrophysical applications (PySnacks). We invite you to participate in the 1h course PySnacks 8: PyBDSF

This workshop is lead by Miguel Cano (IAA-CSIC). 

## Abstract

The Python Blob Detector and Source Finder (PyBDSF) is a CASA-based software designed for source detection in radio-interferometric images. Originally developed for the Low Frequency Array (LOFAR), PyBDSF is designed to work on a wide range of scales, cataloguing different types of sources and allowing post-extraction filtering depending on the user’s scientific purposes. PyBDSF works on images produced by any radio-interferometer. In short, PyBDSF loads the image in fits or CASA format, computes some basic image statistics (rms and mean), and calculates a threshold to separate source from noise pixels with different algorithms that can be chosen by the user. Then, the program identifies islands of emission which are fitted with one or multiple Gaussians. The resulting source catalogue, which can be written into different formats (ascii, fits, txt,…) for subsequent analysis, provides key source properties such as astrometry, integrated and peak fluxes, source geometry, etc. In addition, internally derived images (rms noise maps, Gaussian residual and models, etc) are written in commonly used formats (fits or CASA) if specified by the user. It is possible to work with PyBDSF interactively in a terminal, or via Python scripts or notebooks. PyBDSF can work with all Stokes parameters and compute the polarisation percentage and angle for each source. Also, PyBDSF can compute the spectral indices of both extended and unresolved sources provided a frequency cube is input. Finally, PyBDSF can estimate the PSF spatial variation across the image and correct it. This is of special interest for low frequency observations (such as those of LOFAR) which are more prominently affected by ionospheric effects.

## Workshop materials
The main tutorial for the workshop can be found here:

- [tutorials/PyBDSF_basic.ipynb](tutorials/PyBDSF_basic.ipynb)

--- 
This event is supported by the "Center of Excellence Severo Ochoa" award to the Instituto de Astrofísica de Andalucía. We acknowledge financial support from the Severo Ochoa grant CEX2021-001131-S funded by MCIN/AEI/ 10.13039/501100011033 from the Instituto de Astrofísica de Andalucía.

