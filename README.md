
# About CloudMonitor 
CloudMonitor is a revolutionary FinOps tool that enables companies to automate cost governance and proactively reduces cloud consumption and costs.  
CloudMonitor consists of 4 seperate reporting areas:
1. FinOps - Monitor your cloud spend.
2. Microsoft 365 Analytics - Keep a centralised view of your 365 tenant and users (under development).
3. Security and Compliance - How well does your organisation adhere to cloud security best practices (under development).
4. Sustainability - What is your organisations cloud impact from an environmental sustainability and energy consumption perspective (under development).


The CloudMonitor reports are available in this GitHub repository as an open-source resource for you and your organisation to adapt to your specific requirements.
## What is FinOps?
FinOps is an operational framework and cultural practice which maximizes the business value of cloud, enables timely data-driven decision making, and creates financial accountability through collaboration between engineering, finance, and business teams.  

Learn more at: [FinOps Foundation](https://www.finops.org)

## Looking for CloudMonitor Enterprise?
Click the following link to visit the CloudMonitor website: [CloudMonitor](https://cloudmonitor.ai)


# How to connect the CloudMonitor Dataset and Reports
Example using the Power BI FinOps Reports for CloudMonitor.

1. Download the dataset file "CloudMonitor FinOps Dataset.pbix"  
2. Download required report files e.g. "Executive Summary.pbix" or "Costs.pbix"  

## Connecting the Dataset in Power BI Service

1. Open the dataset file and publish it to your target workspace.  
2. In Power BI Service, navigate to the recently published dataset file and go to the dataset settings.  
![Service Dataset Setting Dialogue](https://github.com/CloudMonitorFinOps/reporting/assets/104886947/66714eab-ca2b-46f8-942b-dff045cdac29)  
3. Under the parameters section, enter the customer ID which was provided to you and apply.  
![Service Dataset Settings](https://github.com/CloudMonitorFinOps/reporting/assets/104886947/3e42e599-83c0-4aa2-96c8-5890fd22bd3c)  
![Service Connection Parameter](https://github.com/CloudMonitorFinOps/reporting/assets/104886947/540dac8a-9e34-4732-bc3d-5d2609bb464f)  
4. Under the data source credentials section, click on edit credentials and enter the username and password provided to you.  
![Service Edit Credentials](https://github.com/CloudMonitorFinOps/reporting/assets/104886947/44f3a5db-0e9c-46e6-8167-de24fd1c4dde)  
![Service Username and Password](https://github.com/CloudMonitorFinOps/reporting/assets/104886947/f55ff0a4-aa18-433b-a1b5-a0fc21dad61a)  
5. Ensure that you have selected Organizational under the Privacy level settings.  
6. Repeat steps 4-5 for the remaining datasource.  

## Connecting the Dataset in Power BI Desktop

1. Open the CloudMonitor FinOps Dataset.pbix file and in the top menu, select Edit Parameters under the Transform Data menu.  
![Desktop Edit Parameters](https://github.com/CloudMonitorFinOps/reporting/assets/104886947/ceb36276-466f-44fb-b318-ce8ac7838883)  
2. In the dialogue which opens, enter the customer ID which was provided to you and click OK.  
![Desktop Parameter Dialogue](https://github.com/CloudMonitorFinOps/reporting/assets/104886947/2de7b61c-ab79-4fb2-b110-134695f1d173)  
3. From the options and settings menu in the file dialogue, select Data source settings.  
![Desktop Options and Settings](https://github.com/CloudMonitorFinOps/reporting/assets/104886947/898b5cdc-f28a-4707-accf-acc360e67dba)  
4. In the window which pops up, select one of the datasources and click Edit Permissions.  
![Desktop Data Source Settings](https://github.com/CloudMonitorFinOps/reporting/assets/104886947/ce04ccf7-9ad8-4a04-bff8-567bb97ed5c0)  
5. In the next window, make sure that Organizational is selected for the Privacy Level.  
![Desktop Edit Permission Window](https://github.com/CloudMonitorFinOps/reporting/assets/104886947/876f970a-21d8-429e-baa2-5131d6e559a5)  
6. Click on edit under the credentials section and in the following window select the Database option in the left hand menu and then enter the username and password which was provided to you.  
![Desktop Credential Window](https://github.com/CloudMonitorFinOps/reporting/assets/104886947/49700650-7bf8-48ee-8711-657f29b1be77)  
7. Repeate steps 4-6 for the remaining datasource.  
8. Once done you may close the datasource settings window.  

## Connecting the Report Files to the Dataset
**Before connecting the report files, you must first publish the Dataset to a Power BI Workspace.**

1. When you open a report file, you will see the following popup mentioning that the report could not connect to a dataset.  
![Desktop Unable to Connect](https://github.com/CloudMonitorFinOps/reporting/assets/104886947/0ee0c013-5556-49a9-9306-21120cd05e8f)  
2. Click on edit, and from the next window select the dataset file which you published to the Power BI Service.  
![Desktop Select Dataset](https://github.com/CloudMonitorFinOps/reporting/assets/104886947/78f2a81a-fc33-433d-a5a5-52cd6705da0f)  
3. The report will now load and display the following detail in the lower right of the Power BI window, showing which dataset and workspace you have connected to.    
![Desktop Connected Live](https://github.com/CloudMonitorFinOps/reporting/assets/104886947/ff010ed7-c2c3-484e-82c0-a5bc715ce4c7)  
