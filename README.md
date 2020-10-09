# HDInsight (custom Ambari + Hive Metastore DB with existing SQL Sever, storage account, vnet)

[![Deploy To Azure](https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazure.svg?sanitize=true)](https://portal.azure.com/#create/Microsoft.Template/uri/https://raw.githubusercontent.com/anellis/hdinisght/main/azuredeploy.json) 

This template allows you to create an HDInsight cluster in an existing virtual network with a new S2 SQL DB that serves as both a custom Ambari DB and Hive Metastore. This assumes you have an exising SQL Sever, storage account, and VNET.
