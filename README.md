# IoT-MPP-Azure-ME120296
This repo houses an IoT solution for a company with a woldwide windfarm and weather station operation.

It is a sample solution deployed on Microsoft Azure Cloud. It is meant to be as a "Proof of Concept" & "Proof of Value" for a full scale solution. 

The folder labelled lab1 implies "test lab 1" and contains solution experimentation result for the weather station along with results using proprietary source code. 
The folder contains
- Architecture design on power point
- Security threat analysis on MS Thrreat Modeling tool
- Exported Zip folder of created resources automation template. This can be used with Azure deployment manager to recreate the resources on the Azure cloud.
- And sample result dataset (in CSV format) from applying *Data engineering* algorithms to input data stream using Azure data lake analytics.

The folder labelled lab 2 contains solution experimentation result for the wind farm scenario. It contains
- Updated architecture design on PowerPoint
- Security threat modelling on MS Threat modeling tool
- Screenshot of using power BI for business reporting
- Screenshot of using MS Time Series Insight(TSI) for time stream analysis to Identify a faulty turbine
- Exported Zip folder of created resources automation template. This can be used with Azure deployment manager to recreate the resources on the Azure cloud.

The solution can be used to test the viability of a scalable IoT setup. It is featured with 
- both Horizontal and Vertical scalability(Number of computers, and computing resources per unit respectively), 
- World wide redundancy(data replication in datacenters worldwide) enabling low latency, 
- a 99.999999999% services level agreements(SLAs) guaranteeing data availability and durability 24/7 with less than 10 milliseconds migration time in the event of datacenter downtime.
