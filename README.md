# Measured-solid-state-and-sub-cooled-liquid-vapour-pressures-of-nitroaromatics-using-KEMS-Data-Set

This repository contains the raw data used to calculate the saturation vapour pressures of various nitroaromatic compounds.

This is the corrosponding data set to (TO BE PUBLISHED).

This project is licensed under the terms of the GNU General Public License v3.0, as provided with this repository.

The KEMS_data_files folder contains the files for all of the raw mass spectra used in the calculations. the format for the file names follows: date of experiment, electron impact multiplication factor, compound name (followed by _run2 if multiple measurements of the same compound were done on the same day), the pinhole size of the Knudsen cell, the background pressure of the mass spec chamber of the KEMS, and the temperature at which the measurement was taken. Gate closed was when the mass spectrometer was isolated from all sample and used to check the mass spectrometer chamber was clean. Gate open was used as the background measurement for the further calculations.

The KEMS_python_scripts show how the solid state saturation vapour pressure  at 298 K was calculated using jupyter notebooks. The folders are named reference compound sample compound with the dates corrosponding to the raw files the from KEMS_data_files. There is also a brief example script available.

TA_DSC_2500_data_files contains the raw DSC data that is used in the sub-cooled correction calculations.

KEMS_MOPAC2016_files contains MOPAC files that were used to estimate the partial charges of the atoms within the molecules of the studied compounds as well as their dipole moments.

The Excel spreadsheet contains all calculated solid state and sub-cooled saturation vapour pressures.

[![DOI](https://zenodo.org/badge/234338938.svg)](https://zenodo.org/badge/latestdoi/234338938) Citation: Shelley et al., (2020) Measured-solid-state-and-sub-cooled-liquid-vapour-pressures-of-nitroaromatics-using-KEMS-Data-Set, Zenodo, https://doi.org/10.5281/ZENODO.3613581
