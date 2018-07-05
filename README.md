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
	<ul><li><a href="https://github.com/CopernicusMarineInsitu/INSTACTraining-Phase2UPDATE/blob/master/PythonNotebooks/In_Situ_products_list.ipynb" target="_blank">In Situ products list</a> - NRT and REP </li>
	<li><a href="https://github.com/CopernicusMarineInsitu/INSTACTraining-Phase2UPDATE/blob/master/PythonNotebooks/In_Situ_index_files.ipynb" target="_blank">In Situ index files</a> - shorcut for data discovery</li>
	<li><a href="https://github.com/CopernicusMarineInsitu/INSTACTraining-Phase2UPDATE/blob/master/PythonNotebooks/In_Situ_product_spatial_coverage.ipynb" target="_blank">In Situ product's spatial coverage</a> (heatmap)</li>
	<li><a href="https://github.com/CopernicusMarineInsitu/INSTACTraining-Phase2UPDATE/blob/master/PythonNotebooks/In_Situ_data_sources_breakdown.ipynb" target="_blank">In Situ product's data sources breakdown</a></li>
	<li><a href="https://github.com/CopernicusMarineInsitu/INSTACTraining-Phase2UPDATE/blob/master/PythonNotebooks/In_Situ_providers_breakdown.ipynb" target="_blank">In Situ product's providers breakdown</a></li>
	<li><a href="https://github.com/CopernicusMarineInsitu/INSTACTraining-Phase2UPDATE/blob/master/PythonNotebooks/In_Situ_parameters_breakdown.ipynb" target="_blank">In Situ product's parameters breakdown</a></li>
	</ul>
<br>
<br>
- How do I find and download In Situ platforms-data? Index files as cheatsheets:
<br>
<img align="left" src="https://github.com/CopernicusMarineInsitu/INSTACTraining-Phase2UPDATE/blob/master/images/data_sources.png" width="400">
	<ul><li><a href="https://github.com/CopernicusMarineInsitu/INSTACTraining-Phase2UPDATE/blob/master/PythonNotebooks/Download_In_Situ_data_tips.ipynb" target="_blank">In Situ data download - tips</a></li>
	<li><a href="https://github.com/CopernicusMarineInsitu/INSTACTraining-Phase2UPDATE/blob/master/PythonNotebooks/In_Situ_data_download_by_boundingbox.ipynb" target="_blank">Targeting a specific area (bounding-box)</a> </li>
	<li><a href="https://github.com/CopernicusMarineInsitu/INSTACTraining-Phase2UPDATE/blob/master/PythonNotebooks/In_Situ_data_download_by_timerange.ipynb" target="_blank">Targeting a specific time range</a></li>
	<li><a href="https://github.com/CopernicusMarineInsitu/INSTACTraining-Phase2UPDATE/blob/master/PythonNotebooks/In_Situ_data_download_by_timeupdate.ipynb" target="_blank">Targeting a specific update date</a></li>
	<li><a href="https://github.com/CopernicusMarineInsitu/INSTACTraining-Phase2UPDATE/blob/master/PythonNotebooks/In_Situ_data_download_by_provider.ipynb" target="_blank">Targeting a specific provider</a></li>
	<li><a href="https://github.com/CopernicusMarineInsitu/INSTACTraining-Phase2UPDATE/blob/master/PythonNotebooks/In_Situ_data_download_by_parameter.ipynb" target="_blank">Targeting a specific parameter</a></li>
	<li><a href="https://github.com/CopernicusMarineInsitu/INSTACTraining-Phase2UPDATE/blob/master/PythonNotebooks/In_Situ_data_download_by_platform_data_source.ipynb" target="_blank">Targeting a specific platform data source</a></li>
	<li><a href="https://github.com/CopernicusMarineInsitu/INSTACTraining-Phase2UPDATE/blob/master/PythonNotebooks/In_Situ_data_download_by_platform_category.ipynb" target="_blank">Targeting a specific platform category</a></li>
	<li><a href="https://github.com/CopernicusMarineInsitu/INSTACTraining-Phase2UPDATE/blob/master/PythonNotebooks/In_Situ_data_download_by_timestamp.ipynb" target="_blank">Targeting a specific timestamp</a></li>
	</ul>
<br>
<br>
<br>
<br>
<br>
- How do I process In Situ data?:
<br>
<br>
	* folium animations: 
<br>
<img align="left" src="https://github.com/CopernicusMarineInsitu/INSTACTraining-Phase2UPDATE/blob/master/images/vessels.png" width="400">
<br>
<ul><li><a href="https://github.com/CopernicusMarineInsitu/INSTACTraining-Phase2UPDATE/blob/master/PythonNotebooks/folium_In_Situ_drifters.ipynb" target="_blank">drifters</a></li> 
<li><a href="https://github.com/CopernicusMarineInsitu/INSTACTraining-Phase2UPDATE/blob/master/PythonNotebooks/folium_In_Situ_vessels.ipynb" target="_blank">vesselss</a></li>
<li><a href="https://github.com/CopernicusMarineInsitu/INSTACTraining-Phase2UPDATE/blob/master/PythonNotebooks/folium_In_Situ_gliders.ipynb" target="_blank">gliders</a></li>
<li><a href="https://github.com/CopernicusMarineInsitu/INSTACTraining-Phase2UPDATE/blob/master/PythonNotebooks/folium_In_Situ_profilers.ipynb" target="_blank">profilers</a></li>
</ul>
<br>
<br>
<br>
<br>
	* map plots:
<br>
<img align="left" src="https://github.com/CopernicusMarineInsitu/INSTACTraining-Phase2UPDATE/blob/master/images/vessels2.png" width="400">
<br>
<ul><li><a href="https://github.com/CopernicusMarineInsitu/INSTACTraining-Phase2UPDATE/blob/master/PythonNotebooks/In_Situ_drifters_on_map.ipynb" target="_blank">drifters</a></li>
<li><a href="https://github.com/CopernicusMarineInsitu/INSTACTraining-Phase2UPDATE/blob/master/PythonNotebooks/map_In_Situ_vessels.ipynb" target="_blank">vessels</a></li>
</ul>
<br>
<br>
	* 2D plots:
<br>
<img align="left" src="https://github.com/CopernicusMarineInsitu/INSTACTraining-Phase2UPDATE/blob/master/images/profiler.png" width="400">
<br>
<ul><li><a href="https://github.com/CopernicusMarineInsitu/INSTACTraining-Phase2UPDATE/blob/master/PythonNotebooks/2d_In_Situ_moorings.ipynb" target="_blank"> moorings</a></li>
<li><a href="https://github.com/CopernicusMarineInsitu/INSTACTraining-Phase2UPDATE/blob/master/PythonNotebooks/2d_In_Situ_profilers.ipynb"  target="_blank"> profilers</a></li>
<li><a href="https://github.com/CopernicusMarineInsitu/INSTACTraining-Phase2UPDATE/blob/master/PythonNotebooks/2d_In_Situ_gliders.ipynb" target="_blank"> gliders</a></li>
<li><a href="https://github.com/CopernicusMarineInsitu/INSTACTraining-Phase2UPDATE/blob/master/PythonNotebooks/2d_In_Situ_vessels.ipynb" target="_blank"> vessels</a></li>
</ul>
<br>
<br>
	* 3D plot:
<br>
<img align="left" src="https://github.com/CopernicusMarineInsitu/INSTACTraining-Phase2UPDATE/blob/master/images/gliders.png" width="400">
<br>
<ul><li><a href="https://github.com/CopernicusMarineInsitu/INSTACTraining-Phase2UPDATE/blob/master/PythonNotebooks/3d_In_Situ_profilers.ipynb"  target="_blank">profilers</a></li>
<li><a href="https://github.com/CopernicusMarineInsitu/INSTACTraining-Phase2UPDATE/blob/master/PythonNotebooks/3d_In_Situ_gliders.ipynb"  target="_blank">gliders</a></li>
<li><a href="https://github.com/CopernicusMarineInsitu/INSTACTraining-Phase2UPDATE/blob/master/PythonNotebooks/3d_In_Situ_vessels.ipynb"  target="_blank">vessels</a></li>
</ul>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>

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
