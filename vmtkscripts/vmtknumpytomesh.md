---
layout: page-full-width
---
<h1>vmtkNumpyToMesh</h1>
<h2>Description</h2>
Takes a nested python dictionary containing numpy arrays specifying Points, PointData, Cells,CellData, and CellPointIds describing connectivity and returns a VMTK mesh (VTK Unstructured Grid) object 
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
<tr><td>i</td><td>ArrayDict</td><td>dict</td><td>1</td><td></td><td></td><td>the input array dictionary</td>
</tr>
<tr><td>ifile</td><td>ArrayDictInputFileName</td><td>str</td><td>1</td><td></td><td></td><td>filename for the default ArrayDict reader</td>
</tr>
<tr><td>flatten</td><td>FlattenListOfCells</td><td></td><td></td><td></td><td></td><td>enable to convert cells which are formated as a list of numpy arrays to the default flat structure</td>
</tr>
<tr><td>ofile</td><td>MeshOutputFileName</td><td>str</td><td>1</td><td></td><td></td><td>filename for the default Mesh writer</td>
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
<tr><td>o</td><td>Mesh</td><td>vtkUnstructuredGrid</td><td>1</td><td></td><td></td><td>the output mesh</td>
</tr>
</table>

