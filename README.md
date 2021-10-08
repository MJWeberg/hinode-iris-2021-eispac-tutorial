# EISPAC Tutorial at the Hinode-14/IRIS-11 Meeting
Notebooks for the EISPAC tutorial at the Hinode-14/IRIS-11 Meeting

## Outline
* Introduction
  * Links to github repo and User's guide
  * General overview of the package and hdf5 files
* Data discovery and download
  * Search for data with `eis_catalog` GUI tool
  * Reference online tools? (e.g. EIS Mapper)
  * Download files for 2020-11-09 03:09:12
* Reading and exploring EIS data
  * Using `read_wininfo()` and `read_cube()`
  * Short intro to `NDCube` and `EISCube`
  * Printing metadata
  * Slicing data
  * Making quick example plots with `EISCube.plot()`
* Fitting spectra
  * Viewing and copying templates with `eis_browse_templates` GUI tool
  * Select and copy fe_12_195_119.2c.template.h5
  * Load with `read_template()`
  * Using `fit_spectra()`
  * `EISFitResult` objects and methods
  * Saving and reading results with `save_fit()` and `read_fit()`
* FITS files and SunPy Maps
  * Exporting resultant observables with `export_fits()`
  * Loading FITS files into an EISMap
  * Display a quick-look plot with `.peek()`
* Advanced topics?
  * Batch processing
