---
layout: page-full-width
---
<h1>vmtkimagesmoothing</h1>
<h2>Description</h2>
smooth an image with a Gaussian kernel or anisotropic diffusion
<h3>Input arguments</h3>
<table class="vmtkscripts">
<tr>
<th>Argument</th><th>Variable</th><th>Type</th><th>Length</th><th>Range</th><th>Default</th><th>Description</th>
</tr>
<tr><td>id</td><td>Id</td><td>str</td><td>1</td><td></td><td>0</td><td>script id</td>
</tr>
<tr><td>handle</td><td>Self</td><td>self</td><td>1</td><td></td><td></td><td>handle to self</td>
</tr>
<tr><td>disabled</td><td>Disabled</td><td>bool</td><td>1</td><td></td><td>0</td><td>disable execution and piping</td>
</tr>
<tr><td>i</td><td>Image</td><td>vtkImageData</td><td>1</td><td></td><td></td><td>the input image</td>
</tr>
<tr><td>ifile</td><td>ImageInputFileName</td><td>str</td><td>1</td><td></td><td></td><td>filename for the default Image reader</td>
</tr>
<tr><td>method</td><td>Method</td><td>str</td><td>1</td><td>["gauss","anisotropic"]</td><td>gauss</td><td></td>
</tr>
<tr><td>sigma</td><td>StandardDeviation</td><td>float</td><td>1</td><td>(0.0,)</td><td>1.0</td><td>the standard deviation of the Gaussian in real space units (gauss)</td>
</tr>
<tr><td>radiusfactor</td><td>RadiusFactor</td><td>float</td><td>1</td><td>(0.0,)</td><td>5.0</td><td>the factor specifing the width of the discrete Gaussian kernel (gauss)</td>
</tr>
<tr><td>dimensionality</td><td>Dimensionality</td><td>int</td><td>1</td><td>(2,3)</td><td>3</td><td>the dimensionality of the Aconvolution (gauss)</td>
</tr>
<tr><td>conductance</td><td>Conductance</td><td>float</td><td>1</td><td>(0.0,)</td><td>1.0</td><td>anisotropic diffustion coefficients (anisotropic)</td>
</tr>
<tr><td>iterations</td><td>NumberOfIterations</td><td>int</td><td>1</td><td>(5,)</td><td>5</td><td> number of anisotropic diffusion iterationsl (anisotropic)</td>
</tr>
<tr><td>timestep</td><td>TimeStep</td><td>float</td><td>1</td><td>(1.0E-16,1.0e16)</td><td>0.0625</td><td>time step of anisotropic diffusion (anisotropic)</td>
</tr>
<tr><td>autocalculatetimestep</td><td>AutoCalculateTimeStep</td><td>bool</td><td>1</td><td></td><td>1</td><td>auto calculate minimum time step (anisotropic)</td>
</tr>
<tr><td>ofile</td><td>ImageOutputFileName</td><td>str</td><td>1</td><td></td><td></td><td>filename for the default Image writer</td>
</tr>
</table>
<h3>Output arguments</h3>
<table class="vmtkscripts">
<tr>
<th>Argument</th><th>Variable</th><th>Type</th><th>Length</th><th>Range</th><th>Default</th><th>Description</th>
</tr>
<tr><td>id</td><td>Id</td><td>str</td><td>1</td><td></td><td>0</td><td>script id</td>
</tr>
<tr><td>handle</td><td>Self</td><td>self</td><td>1</td><td></td><td></td><td>handle to self</td>
</tr>
<tr><td>o</td><td>Image</td><td>vtkImageData</td><td>1</td><td></td><td></td><td>the output image</td>
</tr>
<tr><td>timestep</td><td>TimeStep</td><td>float</td><td>1</td><td></td><td>0.0625</td><td></td>
</tr>
</table>

