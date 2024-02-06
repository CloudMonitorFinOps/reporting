# reporting
Power BI FinOps Reports for CloudMonitor

1. Download the dataset file and all the report Power BI files
2. Open the CloudMonitor FinOps Dataset.pbix file and go to power query view and go to "Parameters" folder on left side queries pane
3. Select the CustomerId parameter and change it to your relevant CustomerID
     (Ex: if server name is "jlxsh356ljzqc-dbserver.database.windows.net" then CustomerId is jlxsh356ljzqc. Enter that value to the parameter)
4. Then click the data source settings in power query and click each server (with synwspace prefix and without one) and click on "Edit permissions" and select "Edit" update the database name and Password.
   (repeat and do add same details for other source as well. Then refresh all queries and apply the change)
5. After it applies publish the dataset file to you power BI workspace.
6. Then open each report file and from File -> Options and Settings - > Data source settings and pick the online dataset source which you just published. You can either publish theses reports to same workspace or use them in desktop.
