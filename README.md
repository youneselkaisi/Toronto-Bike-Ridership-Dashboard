# Toronto Bike Ridership Dashboard (2024 Q1–Q3)

## Project Objective  
The objective of this project is to provide an interactive dashboard for Toronto Bike Share ridership data covering Q1 to Q3 of 2024. It is designed for city planners, transportation analysts, and stakeholders to better understand usage trends, peak times, and rider demographics. These insights help optimize bike distribution, improve infrastructure planning, and enhance user experience.  

## Dataset Used  
[Dataset](https://open.toronto.ca/dataset/bike-share-toronto-ridership-data/2024/) from the City of Toronto Open Data portal  

## Questions  
- What are the busiest start hours for bike rides?  
- Which are the busiest and least busy days of the week?  
- Which months had the highest and lowest ridership?  
- Is there a difference in ridership patterns between casual riders and annual members?  
- What are the busiest and least busy stations in the city?  

## Process  
- Collected dataset from the City of Toronto Open Data website (over 1M+ rows).  
- Loaded data into Power Query for extensive cleaning and transformation.  
- Removed nulls and standardized column names.  
- Removed outliers in trip duration using the IQR method.  
- Added calculated columns and standardized date/time formats.  
- Created interactive visuals in Power BI to highlight ridership KPIs and patterns.  

## Dashboard  
[View Dashboard](https://github.com/youneselkaisi/Toronto-Bike-Ridership-Dashboard/blob/main/Bike%20Share%20Dashboard%20screenshot.png)  

## Project Insights  
- Total rides from Q1–Q3 2024: 256.38k.  
- Average trip duration: 12.38 minutes.  
- Saturday is the busiest day of the week for rides.  
- Trip activity by start hour peaks at 5 PM, stays steady until midnight, and drops to the lowest at 5 AM.  
- September, July, and August are the top months (50k, 48k, and 48k rides respectively), while January had the lowest ridership (~10k).  
- Major stations like Union Station, York St, Bay St, and College St appear in both top start and end locations.  
- Casual riders make up 89% of users; annual members ride for about 2 minutes less per trip on average.  
- Regular bikes dominate usage, while e-bikes remain unpopular despite being more expensive.  

## Conclusion  
The Toronto Bike Ridership Dashboard reveals strong seasonal and daily patterns in bike share usage. Casual riders dominate overall usage, with weekends and late afternoons being peak times. Summer and early fall months consistently show higher ridership, while winter months lag behind. Stations around downtown hubs such as Union Station remain the busiest. These findings can help the City of Toronto and Bike Share operators optimize station placements, allocate bikes more efficiently, and target initiatives that improve both member engagement and infrastructure planning.  
