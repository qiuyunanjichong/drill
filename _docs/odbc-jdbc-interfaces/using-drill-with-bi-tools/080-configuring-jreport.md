---
title: "Configuring JReport with Drill"
parent: "Using Drill with BI Tools"
---

JReport is an embeddable BI solution that empowers users to analyze data and create reports and dashboards. JReport accesses data from Hadoop systems, such as the MapR Distribution through Apache Drill, as well as other big data and transactional data sources. By visualizing data through Drill, users can perform their own reporting and data discovery for agile, on-the-fly decision-making.



### Step 1: Install the Drill JDBC Driver with JReport

Drill provides standard JDBC connectivity to easily integrate with JReport. JReport 13.1 requires Drill 1.0 or later.




   For example, on Windows, copy the Drill JDBC driver jar file into:
   
        C:\JReport\Designer\lib\drill-jdbc-all-1.0.0.jar


----------

### Step 2: Create a New JReport Catalog to Manage the Drill Connection

1.	Click Create **New -> Catalog…**


### Step 3: Use JReport Designer

1.	In the Catalog Browser, right-click **Queries** and select **Add Query…**


