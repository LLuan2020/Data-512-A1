# Human Centered Data Science-A1: Data Curation

### **Goals of the project**

The goal of this assignment is to construct, analyze, and publish a dataset of monthly traffic on English Wikipedia from January 1, 2008, through August 30, 2021. All the analysis is performed in the Jupyter notebook. The raw data fetching from the Wikimedia REST API endpoints is saved in 5 separate . json source data files.

Then, I have combined data about Wikipedia page traffic from two Wikimedia REST API endpoints (page views and page counts) into a single dataset, performed some simple data processing steps on the data, and then visualized the dataset by creating a time series graph.


### **APIs Used for Data Collection**

- Wikimedia Legacy Pagecounts API : https://wikitech.wikimedia.org/wiki/Analytics/AQS/Legacy_Pagecounts
- Wikimedia Pageviews API : https://wikitech.wikimedia.org/wiki/Analytics/AQS/Pageviews


### **CSV Data Description**

| Column  | Description |
| ------------- | ------------- |
| year  | The year of the data point  |
| month  | The month of the data point. The year-month pair serve as a key  |
| pageview_mobile_views  | The number of views as recorded by mobile (app + web) visits  |
| pageview_desktop_views  | The number of views as recorded by desktop site (web) visits  |	
| pagecount_mobile_views  | The number of views as recorded by mobile visits by the legacy API  |
| pagecount_desktop_views  | The number of views as recorded by desktop site visits  |	
| pageview_all_views  | The total number of views as recorded by the PageView API  |
| pagecount_all_views  | The total number of views as recorded by the Page Count API  |	


### **Visualization**
<img width="720" alt="wikipedia_monthly_views_analysis" src="https://user-images.githubusercontent.com/3502870/136106832-773f0e54-e326-4355-80f3-975e3cdab8b1.png">


### **License**

This code is available under the MIT License

Wikimedia Terms of Use
	
