# Administrative Regions  

The SSC tool calculates scores for each administrative region, depending on data availability. It currently supports four levels of administrative regions, ranging from ADM0 to ADM3.  

- **ADM0** always represents the country.  
- **ADM1, ADM2, and ADM3** represent progressively smaller administrative divisions, though their specific names vary by country.  

## Administrative Regions in the Tool  

Each administrative level is represented by a separate entity within the tool. While ADM1, ADM2, and ADM3 share a similar structure, ADM0 (the country level) is structured differently. The differences at ADM0 will be explained in detail later.  

## ADM1 to ADM3  

ADM1 to ADM3 follow a similar structure, with only minor differences. This section will primarily focus on ADM2 as a reference point for understanding these administrative levels.  


### Overview:

![image](https://github.com/user-attachments/assets/57f58a64-2acf-4b29-81f8-eb3d3e86311a)

- **Name:** The name of this administrative region. 
- **ADM1:** The name of the ADM1 region that this region belongs to.  
- **Country:** The country where this region is located.  
- **PCODE:** A unique identifier assigned to each administrative region to ensure accurate matching.  
- **Population:** The total population within this administrative region.  
- **Adjusted Severity Score:** The overall shelter vulnerability score, calculated using the decision tree method and adjusted for baseline vulnerability.  
- **Shelter Vulnerability Score:** The shelter vulnerability score derived from the decision tree method before adjustments.  
- **Refresh:** Click this button to refresh the calculations. (Press the small blue pencil icon on the right to unlock it.) The button will reset to an unclicked state once calculations are complete. Be sure to refresh the page to view any updates.  

- **Decision Tree:** The decision tree used to calculate the overall severity score. By default, it is set to the decision tree configured by the Global Shelter Cluster but can be modified as needed.  
- **Threshold:** Defines the percentage of lower administrative regions required at a specific score for it to be displayed at this administrative level. For example, if set to 20% (0.2), the highest cumulative score meeting this threshold will be shown. If 15% of lower regions have a score of 5, 4% have a score of 4, and 2% have a score of 3, then the displayed score will be 3.  

All fields are read-only except for **'Refresh'**, **'Decision Tree'**, and **'Data Timeframe'**.  


### Overall Pillar Themes & Scores

![image](https://github.com/user-attachments/assets/a6567449-e033-494f-a7ef-4c8d366f1a7b)

This page reflects data across all administrative regions. It is divided into the individual pillars, and shows the score in each theme as well as the pillar score. For more information on the definitions of these pillars or themes, see **[here](../general/page1.md)**.

