# SAP Oracle VM compatible template using a Marketplace image

[![Deploy To Azure](https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazure.svg?sanitize=true)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fmimergel%2Fsap-oracle-vm%2Fmain%2Fazuredeploy.json) [![Visualize](https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/visualizebutton.svg?sanitize=true)](http://armviz.io/#/?load=https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fmimergel%2Fsap-oracle-vm%2Fmain%2Fazuredeploy.json)

This template takes a minimum amount of parameters and deploys a VM that is customized for use with SAP NetWeaver, using the latest patched version of the selected operating system. 
This is a template for a 2-tier configuration. It deploys 1 server on Premium Storage.
This template uses Managed Disks.

<table>
	<tr>
		<th>Size</th>
		<th>Oracle VM</th>
		<th>Oracle VM Storage</th>
		<th>HANA VM</th>
		<th>HANA VM Storage (DATA+LOG+SHARE+SAP)</th>
		<th>SAP APP VM</th>
		<th>SAP APP VM Storage</th>
	</tr>
	<tr>
		<th>Small</th>
		<td>D8s_v3</td>
		<td>2xP10 + 3xP10</td>
		<td>M32ls</td>
		<td>2xP10+3xP10+1xP20+1xP10</td>
		<td>E8s_v3</td>
		<td>1xP10</td>
	</tr>
	<tr>
		<th>Medium</th>
		<td>D32s_v3</td>
		<td>M64ls</td>
		<td>E16s_v3</td>
		<td> tbd. </td>
		<td> tbd. </td>
		<td>1xP10</td>
	</tr>
	<tr>
		<th>Large</th>
		<td>D64s_v3</td>
		<td>M64s</td>
		<td>E32s_v3</td>
		<td> tbd. </td>
		<td> tbd. </td>
		<td>1xP10</td>
	</tr>
</table>				


