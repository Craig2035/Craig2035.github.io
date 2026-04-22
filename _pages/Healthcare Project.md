---
permalink: /healthcare-project/
layout: single
title: "Healthcare Project"
clases: wide
---

###### NHS Operational Analytics: 
Service Demand, Missed Appointments & Public Engagement Insights

**Executive summary:**

Using Python (Pandas, Matplotlib, Seaborn) data was ingested, cleaned and transformed before analysis and visualisation of network structure and current utilisation. Additionally, scrapped data from X was processed to determine hashtag word frequency. After identifying face to face GP appointments as those greatest in demand with location, seasonal variation and the impact of missed appointments and related social media interactions considered, I recommended the following adjustments to meet pressures in demand and predicted increases in population growth. 

1.	Target more GP appointments at weekends, Mondays and for 90 days seasonally where shortfall relative to demand are greatest.
2.	Develop ICB infrastructure where capacity demand is greatest
3.	Targeted social media to improve appointment uptake
   
**Business problem:**

The NHS as a service business needs sufficient capacity to meet demand in every ICB across England. Infrastructure and capacity must meet the demand of an increasing population, and an audit of current service is required to determine needs. Estimates suggest around £216 million per year is currently lost in missed GP appointments alone. How can we understand where capacity is failing to meet demand and make adjustments to services and infrastructure to better serve the nation’s health?

**Methodology:**

Using Python, service data was ingested, cleaned and transformed 
Further Python analysis and visualisation utilised to quantify service utilisation and impact of missed appointments. 
Filter scrapped social data from X to quantify count of tagged (#) data to determine opportunities for further targeted social media engagement.

**Skills:**

Python: Ingestion, validation, standardisation and cleaning of csv file data (Pandas)
Visualisation (Matplotlib and Seaborn) of data following feature engineering, aggregations and lambda functions.
Web scrapped data analysis of unstructured data 

**Results and Business Recommendations:**

Graphs of processed data gives visibility to ICB management stakeholders into appointment utilisation, service capacity and appointment non-attendance (DNA) costs. This analysis showed us most appointments are in General Consultation Routine, making more than double of appointments in any other defined National Category, with seasonal and weekly variation. Most appointments were face to face and achieved within one day of request. Service demand by region was also calculated. 

##### General Consultation Route had twice the appointment numbers than any other setting
{% include figure image_path="/assets/images/NHS1.png" alt="NHS1 image" caption="*Note: Data for the smallest groups were collated into a category called ‘Other’ to avoid crowding and line overlap.*" %}
 
Average daily utilisation indicated service capacity was exceeded in most months of the last 12 studied, with seasonal fluctuations and peaks in Winter and Spring months and DNA costs peaking in October each year where demand was at its highest.

##### Most months in the last 12 were above capacity
{% include figure image_path="/assets/images/NHS2.png" alt="NHS2 image" caption="*October 2021 was the busiest month*" %}
 
##### Missed appointment cost the NHS over £350k every October.
 {% include figure image_path="/assets/images/NHS3.png" alt="NHS3 image" caption="*Note: Smallest numbers of DNA occurred during the COVID-19 pandemic in March 2020. Overall there looks to be an upward trend in missed appointments with seasonal variation correlating with count of appointments.*" %}

##### Social media data – What are people talking about?

Scrapped data from X (formerly Twitter) which had been filtered and counted provided information on the most frequent hashtags. The #healthcare was X9 more frequently used than the next nearest hashtag. 

##### #Healthcare was the top trending hashtag, 9X more frequent than any other
 {% include figure image_path="/assets/images/NHS4.png" alt="NHS4 image" caption="*#Healthcare*" %}
 
Because the biggest impact on service utilisation is both seasonal and regional, I recommended the following adjustments: 

1.	Target of 0.2 million more GP appointments on weekends and Mondays using 0.25% of total ICB annual spend.
2.	Target of 18 million more GP appointments seasonally over 90 days of the year (£540m). 
3.	Medium term increase of 3.5% spend in relative budget for development of  infrastructure in regions with highest appointment demand (London, South East and South West). 
4.	Implement targeted autumn social media campaign using **#healthcare** to reduce DNA in 5 target regions (1. Greater Manchester, 2. North East and North Cumbria, 3. Cheshire and Merseyside, 4. North East London, 5. North West London

**Next Steps:**

- Conduct survey work on appointment uptake and satisfaction
- Measure email and text open & click rate for appointment reminders
- Investigate transport service access for the vulnerable and impact on appointment uptake


