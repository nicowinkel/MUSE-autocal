# MUSE-autocal
Self-calibration method for the IFU-to-IFU and slice-to-slice flux varation in products from the ESO VLT/MUSE data reduction pipeline.

## Scope
The optional self-calibration of the VLT/MUSE data reduction pipeline removes the wavelength dependent IFU-to-IFU and slice-to-slice flux varation.
It is designed for deepfield observations where many sources populate the field of view. In many observations, however, a bright point source dominates the IFUs and slices near to the source due to beam-smearing, whereas other IFUs/slices may only be exposed to a faint signal around the source.
In this case the "autocal" method does not produce a reliable result, especially if one is interested in the faint signal around the bright point source.
This script provides an alternative method for the self-calibration. It is developed to robustly the stellar continuum emission in unobscured (type 1) AGN, but may also improve the calibration for science cases that face a similar challenge of a bright point-source.


## Installation instructions
A beta version of the script is currently being developed.
It needs to be implemented in the ESO VLT/MUSE data reduction pipeline. This can either be achieved by executing the esorex commands of the data reduction cookbook one after another, or alternatively by placing a the python script in the EsoReflex GUI for the interface.

*** More information tba soon ***

## Manual for more information on parameter file setup
*** Information tba soon ***
