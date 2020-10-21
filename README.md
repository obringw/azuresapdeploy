# SAP Oracle VM compatible template using a Marketplace image

[![Deploy To Azure](https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazure.svg?sanitize=true)](https://portal.azure.com/#create/Microsoft.Template/uri/https://github.com/mimergel/sap-oracle-vm/blob/main/azuredeploy.json)

This template takes a minimum amount of parameters and deploys a VM that is customized for use with SAP NetWeaver, using the latest patched version of the selected operating system. 
This is a template for a 2-tier configuration. It deploys 1 server on Premium Storage.
This template uses Managed Disks.

<table>
	<tr>
		<th>Size</th>
		<th>Premium Storage (Data + Log)</th>
	</tr>
	<tr>
		<td>Small VM: E2s_v3</td>
		<td>2xP20 + 1xP10</td>
	</tr>
	<tr>
		<td>Medium VM: E8s_v3</td>
		<td>3xP20 + 1xP10</td>
	</tr>
	<tr>
		<td>Large VM: E16s_v3</td>
		<td>3xP30 + 1xP20</td>
	</tr>
</table>				


