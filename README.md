# Bay Area Bubble Tea Analysis Using Tableau
A Tableau based Report made using a Kaggle data-set for the bubble tea places around bay area. The dataset itself comes with very limited number of attributes:

1. id - identifier for each bubble tea shop
2. Name - Name of each bubble tea shop
3. Rating - Rating given by bubble tea consumers
4. Address - Address of the outlet
5. City - city in the bay area where the outlet in the row is present
6. lat - Latitude of the corresponding outlet
7. long - Longitude of the corresponding outlet

As an avid consumer of bubble tea myself, I could not help but do something about this dataset i found on Kaggle. Although due to the lack of attributes and data being static, there aren't many inferences that could be drawn from this data But I did my best to make a small report out of it using Tableau that could be used or perhaps extended (If i am able to find more data, I would love to)

## Tableau Report:

Link to the report: https://public.tableau.com/views/bubbleteaanalysis/Dashboard1?:language=en-US&:display_count=n&:origin=viz_share_link:showVizHome=no&:embed=true

### Top 10 cities in the bay area based on number of bubble tea shops:
This plot shows top 10 cities within the bay area with largest number of bubble tea spots. Because of less data, I had put a filter so the visual only shows areas with 10 or more shops. 

![image](https://github.com/yumnazia/BayAreaBubbleTeaAnalysis/assets/12965968/76b4da96-045f-414b-a242-a24dbad373f8)

As indicated by the visual, San Francisco and San Jose have the highest number of shops. 

### Top Bubble tea stores around the Bay area:
This plot shows top rated bubble tea stores across the bay area. I have used average of rating here. However, a challenge in the data set is less number of ratings because of which average rating becomes nonreliable. To cater for this, I only selected the stores that had been rated 10 or more time.  
![image](https://github.com/yumnazia/BayAreaBubbleTeaAnalysis/assets/12965968/8d47d57f-b2f4-4a1e-a36b-77e5d1d060e2)

### Distribution of bubble-tea spots using classifier 
This plot shows how bubble tea spots are distributed across Bay area. Additionally, the size of the bubbles indicates the number of places in a certain area and the colors are indicative of how good or bad the places are on an overall level, within the Bay area. 
![image](https://github.com/yumnazia/BayAreaBubbleTeaAnalysis/assets/12965968/d6660aae-0ca0-4de0-8143-c56fb9882ce5)

### Top 3 bubble-tea spots in each city within the Bay Area
This plot shows Top 3 bubble-tea spots in each city in the Bay area. 
![image](https://github.com/yumnazia/BayAreaBubbleTeaAnalysis/assets/12965968/ec16414f-374e-479f-b16a-7052dfdc25b8)
