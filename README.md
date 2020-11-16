# SAP Oracle VM deployments using Azure Marketplace images

[![Deploy To Azure](https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazure.svg?sanitize=true)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fobringw%2Fazuresapdeploy%2Fmain%2Fazuredeploy.json) 

This template takes a minimum amount of parameters and deploys a VM that is customized for use with SAP NetWeaver and Oracle DB, using the latest patched version of the selected operating system. This is a template for a 2-tier configuration and it deploys 1 server on Premium Storage with Managed Disks.  Filesystems are created via custom script. Where multiple disks are used for the filesystem the logical volume is setup with striping for optimal performance.

<table>
	<tr>
		<th>Size</th>
		<th>Oracle VM</th>
		<th>Oracle VM Storage (ORACLE + LogA + LogB + SAPDATA + ORAARCH + SAPEXE)</th>
	</tr>
	<tr>
		<th>Small</th>
		<td>D8s_v3 (8CPU/32GB)</td>
		<td>1xP6(64GB) + 1xP6(64GB) + 1xP6(64GB) + 2xP10(128GB) + 1xP6(64GB) + 1xP6(64GB)</td>
	</tr>
	<tr>
		<th>Medium</th>
		<td>D32s_v3 (32CPU/128GB)</td>
		<td>1xP6(64GB) + 1xP6(64GB) + 1xP6(64GB) + 2xP15(256GB) + 1xP10(128GB) + 1xP6(64GB)</td>
	</tr>
	<tr>
		<th>Large</th>
		<td>D64s_v3 (64CPU/256GB)</td>
		<td>1xP6(64GB) + 1xP6(64GB) + 1xP6(64GB) + 2xP20(512GB) + 1xP20(256GB) + 1xP6(64GB)</td>
	</tr>
</table>				


