---
title: Research Products
layout: menu_der
use_fontawesome: true
use_math: true
---

<!-- Research -->
<h1 class="section-title">3-D Shear Wave Velocity Model of Mexico and South US</h1>

<div class="row content-row">
<div class="col-12 col-sm-5 image-wrapper">
    <img src="{{ site.baseurl }}/images/mexsections.png">
</div>
<div class="col-12 col-sm-7">
<a href="https://academic.oup.com/gji/article-abstract/206/3/1795/2583531" target="_blank">This work</a> presents the results obtained from the surface wave tomography for a region covering Mexico and the southern United States with a resolution of 0.4° on a square grid.<br />
The tomography is obtained by using an innovative strategy to enhance the resolution obtained from ambient noise cross-correlation (C1) by bridging asynchronous seismic networks through the correlation of coda of correlations (C3). Rayleigh wave group dispersion curves show consistent results between synchronous and asynchronous stations.<br />
Rayleigh wave travel times are inverted to construct group velocity maps at different periods.<br />
The resulting period maps are then used to regionalize dispersion curves in order to obtain local 1-D shear velocity models (VS) of the crust and uppermost mantle in every cell of the geographical grid. The 1-D structures are obtained by iteratively adding layers until reaching a given misfit, and a global tomography model is considered as an input for depths below 150 km. The latter allow to deal with the low-velocity zone of the upper mantle and improve the misfit at long period. Finally, a high-resolution 3-D VS model is obtained from these inversions.<br />
The major structures observed in the 3-D model are in agreement with the tectonic-geodynamic features and with previous regional and local studies. It also offers new insights to understand the present and past tectonic evolution of the region. <a href="https://drive.google.com/open?id=1VpnLGRPXc2c2VhYlfmyeVx0nQOv0lvJG" target="_blank"><i class="fa fa-file"></i> Paper</a>
</div>

<div>
<h1> Products </h1>
<h4><u>Raw profiles</u></h4>
<div class="row content-row">

<div class="col-12 col-sm-12"><ul>
<li>The 3-D model resulting from the inversion can be downloaded as a MATLAB <a href="https://github.com/zackspica/zackspica.github.io/releases/tag/Models" target="_blank"><i class="fa fa-save"></i> file </a>. It contains the positions of the center of the grid cells and the tensors Mh, Mrho, MVp, MVs which correspond respectively to the thickness, density, compressional and shear velocities at the cells location for the several layers considered.</li>
<li>The 1st dimension is related to latitudes.</li>
<li>The 2nd dimension is related to longitudes.</li>
<li>The 3rd dimension is related to the layer number (1 is for the top layer).</li></ul>


<h4><u>Viewer </u></h4>
A viewer allows interacting with the 3-D model. It is a compiled MATLAB executable for <a href="https://github.com/zackspica/zackspica.github.io/releases/tag/final" target="_blank"><i class="fa Windows"></i>Windows</a>, Linux and <a href="https://github.com/zackspica/zackspica.github.io/releases/tag/finalMac" target="_blank"><i class="fa Apple"></i>Mac</a>, which will install both the MATLAB runtime (if required) and the viewer software. It allows viewing and extracting: <ul>
<li>Period maps</li> 
<li>Local 1D profile on any point of the grid along with the associated dispersion curves (target and best-fit) as well as the dispersion curves obtained from a previous study (Gaite et al., 2015).</li>
<li>Vs velocity model. Both depth maps and cross-section between two points of the grid are extractable. 3D box of the Vs model. Draw a box on the map and extract this part of the model.</li>
<li>Map of the misfit.</li></ul>
If you have any issue with the installation or with the programs, don’t hesitate to write <a href="mailto:mathieuperton@gmail.com;zspica@stanford.edu;"> <i class="far fa-envelope"></i> us an Email</a>, we will be happy to collaborate if more assitance is needed. Please refer to our work as:
<pre class="code">
<span><code>Spica, Z., Perton, M., Calò, M., Legrand, D., Córdoba-Montiel, F. and Iglesias, A., 2016. 3-D shear wave velocity model of 
Mexico and South US: bridging seismic networks with ambient noise cross-correlations (C1) and correlation of coda of 
correlations (C3). Geophysical Journal International, 206(3), pp.1795-1813, doi:10.1093/gji/ggw240</code></span>
</pre>

<div class="col-12 col-sm-12 image-wrapper">
    <img src="{{ site.baseurl }}/images/vidsures.gif">
</div>
</div>


<div>
<h5> Participants </h5>
Zack Spica, <a href="http://www.igum.unam.mx/mperton/" target="_blank">Mathieu Perton</a>, 
<a href="http://marcocalo.weebly.com/" target="_blank">Marco Calò</a>, <a href="https://scholar.google.es/citations?user=8GVIsq8AAAAJ&hl=es" target="_blank">Denis Legrand</a>, Francisco Córdoba Montiel and  <a href="http://www.geofisica.unam.mx/sismologia/index.php/users/view/6" target="_blank">Arturo Iglesias</a>
</div>





