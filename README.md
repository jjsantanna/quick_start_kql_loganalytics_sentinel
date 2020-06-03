# This is a template to facilitate people to access public and private Azure LogAnalytics (Azure Sentinel), to perform queries using Kusto Query Language (KQL), and further process the data using Python libraries (e.g. pandas and numpy).

There are a couple of public data provided by Microsoft to be used as demo:
1. The link https://dataexplorer.azure.com forwards to https://dataexplorer.azure.com/clusters/help/databases/Samples
    * TO LOAD AS KQLMAGIC: `%kql azureDataExplorer://code;cluster='help';database='Samples'`
2. There is a demo of 'Application Insights'
    * TO LOAD AS KQLMAGIC: `%kql appinsights://appid='DEMO_APP';appkey='DEMO_KEY'`
3. There is a link https://aka.ms/lademo and portal.loganalytics.io/demo, both forward to https://portal.azure.com/#blade/Microsoft_Azure_Monitoring_Logs/DemoLogsBlade
    * TO LOAD AS KQLMAGIC: `%kql loganalytics://workspace='DEMO_WORKSPACE';appkey='DEMO_KEY'`