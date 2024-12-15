# Socrata Open Data API Tutorial with Python and NYC Open Data 
Author: Mark Bauer

# Table of Contents
* [Introduction](#Introduction)
* [Tutorials](#Tutorials)
* [Data](#Data)
* [Additional Resources](#Additional-Resources)
    * [Socrata Open Data API](#Socrata-Open-Data-API)
    * [Sodapy](#Sodapy)
* [Say Hello!](#Say-Hello)

![cover photo](figures/datasets-download.png)  

![cover photo](figures/agency-downloads.png)  

![cover photo](figures/descriptor-type.png)  

![cover photo](figures/day-line.png)

# Introduction  

This project demonstrates how to:  
- Use the Socrata Open Data API
- Use sodapy (i.e. the python client for the Socrata API)  

And provides:
- Examples of the Socrata Query Language (also known as SoQL)  
- A sample analysis notebook using datasets from NYC Open Data

Inspiration for this project came from the [sodapy GitHub page](https://github.com/xmunoz/sodapy). Much of what I learned about sodapy, as well as working with the Socrata API, came from these developers. I encourage you to review the official Sodapy GitHub page to have a better and more complete understanding of sodapy (e.g. installation, requirements, available methods, basic SoQL queries, etc.). This tutorial is meant to complement the official Sodapy docs.

Here are some additional projects I've developed that make use of the Socrata API:
- [Data Analysis Using Python: A Beginner’s Guide Featuring NYC Open Data](https://github.com/mebauer/data-analysis-using-python): A beginner-friendly guide to data analysis using Python, featuring real-world datasets from NYC Open Data.
- [Analyzing NYC's 311 Street Flooding Complaints from 2010 to 2020](https://github.com/mebauer/nyc-311-street-flooding): A detailed analysis of NYC's 311 Street Flooding Complaints from 2010 to 2020, with insights on trends and patterns in the data.
- [Flood Data Catalog for NYC: A Comprehensive Inventory on NYC Open Data](https://github.com/mebauer/nyc-flood-data): A curated catalog of flood-related datasets available on NYC Open Data, designed to provide a comprehensive resource for researchers and policymakers.
- [MTA Subway Origin-Destination Ridership Estimate for 2023](https://github.com/mebauer/mta-data): An analysis of subway ridership data to estimate origin-destination patterns for the MTA in 2023.
- [Big Data on NYC Open Data](https://github.com/mebauer/nyc-open-bigdata): Exploring the intersection of big data and NYC Open Data, focusing on large-scale datasets and techniques for handling and analyzing them.

# Tutorials  
- Socrata API Basics: [socrata-api-basics.ipynb](https://github.com/mebauer/sodapy-tutorial-nyc-opendata/blob/main/socrata-api-basics.ipynb) Get started with the Socrata Open Data API and the sodapy Python client. This tutorial introduces you to the basics of connecting to Socrata, retrieving data, and working with the API.
- The Socrata Query Language (SoQL): [socrata-query-language.ipynb](https://github.com/mebauer/sodapy-tutorial-nyc-opendata/blob/main/socrata-query-language.ipynb) Learn how to craft powerful queries using the Socrata Query Language (SoQL). This guide covers various methods and techniques for querying data effectively through the Socrata API.
- A sample analysis notebook: [sample-analysis.ipynb](https://github.com/mebauer/sodapy-tutorial-nyc-opendata/blob/main/sample-analysis.ipynb) Explore a sample analysis that highlights popular NYC Open Data datasets. This notebook also includes a quick exploratory data analysis (EDA) of NYC 311 Street Flooding Complaints.

# Data  
- [311 Service Requests from 2010 to Present](https://nycopendata.socrata.com/Social-Services/311-Service-Requests-from-2010-to-Present/erm2-nwe9): All 311 Service Requests from 2010 to present. This information is automatically updated daily.
- [DEP Green Infrastructure](https://data.cityofnewyork.us/Environment/DEP-Green-Infrastructure/spjh-pz7h): NYC Green Infrastructure Program initiatives. Green infrastructure (GI) collects stormwater from streets, sidewalks, and other hard surfaces before it can enter the sewer system or cause local flooding. The GI practice data contained in this dataset includes the location, program area, status, and type of GI. Please visit nyc.gov/dep/gimap to view the DEP Green Infrastructure Map.

# Additional Resources 

## Socrata Open Data API  
- The official Socrata Open Data API documentation: https://dev.socrata.com/  
- Queries using SODA: https://dev.socrata.com/docs/queries/

## Sodapy  
- The official Sodapy documentation: https://github.com/xmunoz/sodapy  
- SoQL inspiration for this project: https://github.com/xmunoz/sodapy/blob/master/examples/soql_queries.ipynb

# Say Hello!
Feel free to reach out for further discussions.
- LinkedIn: [markebauer](https://www.linkedin.com/in/markebauer/)  
- GitHub: [mebauer](https://github.com/mebauer)  
- Portfolio: [mebauer.github.io](https://mebauer.github.io/)
