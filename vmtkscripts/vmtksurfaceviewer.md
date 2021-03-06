---
layout: page-full-width
---
<h1>vmtksurfaceviewer</h1>
<h2>Description</h2>
display a surface
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
<tr><td>i</td><td>Surface</td><td>vtkPolyData</td><td>1</td><td></td><td></td><td>the input surface</td>
</tr>
<tr><td>ifile</td><td>SurfaceInputFileName</td><td>str</td><td>1</td><td></td><td></td><td>filename for the default Surface reader</td>
</tr>
<tr><td>renderer</td><td>vmtkRenderer</td><td>vmtkRenderer</td><td>1</td><td></td><td></td><td>external renderer</td>
</tr>
<tr><td>display</td><td>Display</td><td>bool</td><td>1</td><td></td><td>1</td><td>toggle rendering</td>
</tr>
<tr><td>representation</td><td>Representation</td><td>str</td><td>1</td><td>["surface","wireframe","edges"]</td><td>surface</td><td>change surface representation</td>
</tr>
<tr><td>opacity</td><td>Opacity</td><td>float</td><td>1</td><td>(0.0,1.0)</td><td>1.0</td><td>object opacity in the scene</td>
</tr>
<tr><td>array</td><td>ArrayName</td><td>str</td><td>1</td><td></td><td></td><td>name of the array where the scalars to be displayed are stored</td>
</tr>
<tr><td>scalarrange</td><td>ScalarRange</td><td>float</td><td>2</td><td></td><td>[0.0, 0.0]</td><td>range of the scalar map</td>
</tr>
<tr><td>colormap</td><td>ColorMap</td><td>str</td><td>1</td><td>["rainbow","blackbody","cooltowarm","grayscale"]</td><td>cooltowarm</td><td>choose the color map</td>
</tr>
<tr><td>numberofcolors</td><td>NumberOfColors</td><td>int</td><td>1</td><td></td><td>256</td><td>number of colors in the color map</td>
</tr>
<tr><td>legend</td><td>Legend</td><td>bool</td><td>1</td><td></td><td>0</td><td>toggle scalar bar</td>
</tr>
<tr><td>flat</td><td>FlatInterpolation</td><td>bool</td><td>1</td><td></td><td>0</td><td>toggle flat or shaded surface display</td>
</tr>
<tr><td>celldata</td><td>DisplayCellData</td><td>bool</td><td>1</td><td></td><td>0</td><td>toggle display of point or cell data</td>
</tr>
<tr><td>displaytag</td><td>DisplayTag</td><td>bool</td><td>1</td><td></td><td>False</td><td>toggle rendering of tag</td>
</tr>
<tr><td>regiontagarray</td><td>RegionTagArrayName</td><td>str</td><td>1</td><td></td><td>RegionTagArray</td><td>name of the array where the tags to be displayed are stored</td>
</tr>
<tr><td>color</td><td>Color</td><td>float</td><td>3</td><td></td><td>[-1.0, -1.0, -1.0]</td><td>RGB color of the object in the scene</td>
</tr>
<tr><td>linewidth</td><td>LineWidth</td><td>int</td><td>1</td><td>(0.0,)</td><td>1</td><td>width of line objects in the scene</td>
</tr>
<tr><td>legendtitle</td><td>LegendTitle</td><td>str</td><td>1</td><td></td><td></td><td>title of the scalar bar</td>
</tr>
<tr><td>ofile</td><td>SurfaceOutputFileName</td><td>str</td><td>1</td><td></td><td></td><td>filename for the default Surface writer</td>
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
<tr><td>o</td><td>Surface</td><td>vtkPolyData</td><td>1</td><td></td><td></td><td>the output surface</td>
</tr>
<tr><td>oactor</td><td>Actor</td><td>vtkActor</td><td>1</td><td></td><td></td><td>the output actor</td>
</tr>
</table>

