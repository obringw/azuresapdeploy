# SAP Oracle VM compatible template using a Marketplace image

[![Deploy To Azure](https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazure.svg?sanitize=true)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fmimergel%2Fsap-oracle-vm%2Fmain%2Fazuredeploy.json) [![Visualize](https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/visualizebutton.svg?sanitize=true)](http://armviz.io/#/?load=https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fmimergel%2Fsap-oracle-vm%2Fmain%2Fazuredeploy.json)

This template takes a minimum amount of parameters and deploys a VM that is customized for use with SAP NetWeaver, using the latest patched version of the selected operating system. 
This is a template for a 2-tier configuration. It deploys 1 server on Premium Storage.
This template uses Managed Disks.

<table>
	<tr>
		<th>Size</th>
		<th>Oracle VM</th>
		<th>HANA VM</th>
		<th>SAP APP VM</th>
		<th>Storage HANA</th>
		<th>Storage Oracle</th>
		<th>Storage SAP APP</th>
	</tr>
	<tr>
		<td>Small</td>
		<th>D8s_v3</th>
		<th>M32ls</th>
		<th>E8s_v3</th>
		<td>2xP20 + 1xP10</td>
		<td>2xP20 + 1xP10</td>
	</tr>
	<tr>
		<td>Medium</td>
		<th>D32s_v3</th>
		<th>M64ls</th>
		<th>E16s_v3</th>
		<td> tbd. </td>
		<td> tbd. </td>
	</tr>
	<tr>
		<td>Large</td>
		<th>D64s_v3</th>
		<th>M64s</th>
		<th>E32s_v3</th>
		<td> tbd. </td>
		<td> tbd. </td>
	</tr>
</table>				


