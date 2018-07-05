# CMEMS INSTAC

Ocean circulation models need information on the interior of the ocean to be able to generate accurate forecast. This information is only available from in-situ measurements. However this information is acquired by different institutes and not always easily accessible to operational users. Therefore, In Situ Thematic Assembly Centre ([INS-TAC](http://www.marineinsitu.eu/)), by connecting to a lot of regional and international networks, collects, controls and disseminates the relevant in-situ data to operational users and research community. 
<br>
<br>
<img src="images/regions.png " width="500">

In Situ data, along with any other Copernicus Marine Enviroment Monitoring (CMEMS) such as satellite and modelling products, can be downloaded via Web User Interface after [registration](http://marine.copernicus.eu/services-portfolio/register-now/) at [CMEMS product catalogue](http://marine.copernicus.eu/)). See [how to](http://marine.copernicus.eu/services-portfolio/technical-faq/).

For non-interactive download see next PythonNotebooks section. 

[Useful info](./tips/README.md)

## Presentations
Presentations used during the previous training sessions. All presentations include a brief introduction to the CMEMS in situ particularities as CMEMS provider of ON-SITE observations followed by a more detailed presentation of a regional distribution unit (i.e IBI, GLO, MED, BAL, ARC etc). Particulary useful to check different NetCDF tools are La Spezia and Lisboa presentations.
* [Malta](http://www.socib.es/users/protllan/CMEMS/jnsummersch/reveal.js-master/coding/): JERICO-NEXT Malta Summer School 2018: Operational Oceanography for Blue Growth. 09/07/2018 14/07/2018

## PythonNotebooks

Contains the materal for the training courses organised in the frame of the In Situ component of the Copernicus Marine Environment Monitoring Service ([CMEMS](http://marine.copernicus.eu/)). Examples of data downloading and processing with [ipython notebooks](http://ipython.org/notebook.html) (or [Jupyter notebook](http://jupyter.org/)) using [netCDF](http://www.unidata.ucar.edu/software/netcdf/) files:

- In Situ data products overview:

<img align="left" src="https://github.com/CopernicusMarineInsitu/INSTACTraining-Phase2UPDATE/blob/master/images/spatial_coverage.png" width="400">
<br>
	* [In Situ products list](./PythonNotebooks/In_Situ_products_list.ipynb) - NRT and REP 
	* [In Situ index files](./PythonNotebooks/In_Situ_index_files.ipynb) - shorcut for data discovery
	* [In Situ product's spatial coverage](./PythonNotebooks/In_Situ_product_spatial_coverage.ipynb) (heatmap)
	* [In Situ product's data sources breakdown](./PythonNotebooks/In_Situ_data_sources_breakdown.ipynb)
	* [In Situ product's providers breakdown](./PythonNotebooks/In_Situ_providers_breakdown.ipynb)
	* [In Situ product's parameters breakdown](./PythonNotebooks/In_Situ_parameters_breakdown.ipynb)

- How do I find and download In Situ platforms-data? Index files as cheatsheets:

<img align="left" src="https://github.com/CopernicusMarineInsitu/INSTACTraining-Phase2UPDATE/blob/master/images/data_sources.png" width="400">
<br>
	* [In Situ data download - tips ](./PythonNotebooks/Download_In_Situ_data_tips.ipynb)
	* [Targeting a specific area (bounding-box)](/PythonNotebooks/In_Situ_data_download_by_boundingbox.ipynb) 
	* [Targeting a specific time range](./PythonNotebooks/In_Situ_data_download_by_timerange.ipynb)
	* [Targeting a specific update date](./PythonNotebooks/In_Situ_data_download_by_timeupdate.ipynb)
	* [Targeting a specific provider](./PythonNotebooks/In_Situ_data_download_by_provider.ipynb)
	* [Targeting a specific parameter](./PythonNotebooks/In_Situ_data_download_by_parameter.ipynb)
	* [Targeting a specific platform data source](./PythonNotebooks/In_Situ_data_download_by_platform_data_source.ipynb)
	* [Targeting a specific platform category](./PythonNotebooks/In_Situ_data_download_by_platform_category.ipynb)
	* [Targeting a specific timestamp](./PythonNotebooks/In_Situ_data_download_by_timestamp.ipynb)

- How do I process In Situ data?:

<img align="left" src="https://github.com/CopernicusMarineInsitu/INSTACTraining-Phase2UPDATE/blob/master/images/vessels.png" width="400">
<br>
	- folium animations: 
		* [drifter](./PythonNotebooks/folium_In_Situ_drifters.ipynb) 
		* [vesselss](./PythonNotebooks/folium_In_Situ_vessels.ipynb)
		* [gliders](./PythonNotebooks/folium_In_Situ_gliders.ipynb)
		* [profilers](./PythonNotebooks/folium_In_Situ_profilers.ipynb)
<br>
<img align="left" src="https://github.com/CopernicusMarineInsitu/INSTACTraining-Phase2UPDATE/blob/master/images/vessels2.png" width="400">
<br>
	- map plots:
		* [drifters](./PythonNotebooks/In_Situ_drifters_on_map.ipynb)
		* [vessels](./PythonNotebooks/map_In_Situ_vessels.ipynb)
<br>
<img align="left" src="https://github.com/CopernicusMarineInsitu/INSTACTraining-Phase2UPDATE/blob/master/images/profiler.png" width="400">
<br>
	- 2D plots ([moorings](./PythonNotebooks/2d_In_Situ_moorings.ipynb), [profilers](./PythonNotebooks/2d_In_Situ_profilers.ipynb), [gliders](./PythonNotebooks/2d_In_Situ_gliders.ipynb), [vessels](./PythonNotebooks/2d_In_Situ_vessels.ipynb))
<br>
<img align="left" src="https://github.com/CopernicusMarineInsitu/INSTACTraining-Phase2UPDATE/blob/master/images/gliders.png" width="400">
<br>
	- 3D plots ([profilers](./PythonNotebooks/3d_In_Situ_profilers.ipynb), [gliders](./PythonNotebooks/3d_In_Situ_gliders.ipynb), [vessels](./PythonNotebooks/3d_In_Situ_vessels.ipynb))


## Legacy
This material has been developed based on the material developed by [Charles Troupin](https://github.com/ctroupin) for CMEMS In Situ TAC Phase I Communication & Training activities. 
Additional and new material has been build by [Paz Rotllan](https://github.com/pazrg), responsible for In Situ TAC Communication & Training from 2017-onwards. 

## Copyright
Copyright (c) 2017 ICTS SOCIB - Servei d'observació i predicció costaner de les Illes Balears.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
