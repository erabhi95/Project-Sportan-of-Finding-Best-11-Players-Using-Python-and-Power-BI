# Project Sportan (Finding Best 11 Players)

### Table of Contents
- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [KPIs Considered](#kpis-considered)
- [Data Cleaning](#data-cleaning)
- [Data Transformation](data-transformation)
- [Data Visualisation](#data-visualisation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Results](#results)
- [Insights and Recommendations](#insights-and-recommendations)

### Project Overview
This is a data analysis project which aims at finding the best 11 players based on certain criteria, as provided by the Subject Matter Experts (SMEs) of the game, to select the best playing 11 team.

**Final Report**

![Openers](https://github.com/erabhi95/Project-Sportan-of-Finding-Best-11-Players-Using-Python-and-Power-BI/assets/159037337/71cc7eaa-f87c-4e75-9bc6-7e7719fdddf7)
![Anchors](https://github.com/erabhi95/Project-Sportan-of-Finding-Best-11-Players-Using-Python-and-Power-BI/assets/159037337/41102510-ee5d-46d3-a8cf-6b34c088113a)
![Finishers](https://github.com/erabhi95/Project-Sportan-of-Finding-Best-11-Players-Using-Python-and-Power-BI/assets/159037337/b031ee5f-e99b-4f04-89a5-413d847c9269)
![All Rounders](https://github.com/erabhi95/Project-Sportan-of-Finding-Best-11-Players-Using-Python-and-Power-BI/assets/159037337/356512bf-f5d4-4dc6-97e1-0c67f92820bd)
![Specialist Fast Bowlers](https://github.com/erabhi95/Project-Sportan-of-Finding-Best-11-Players-Using-Python-and-Power-BI/assets/159037337/2a14f850-50a4-462f-9438-6cbefe0c3d32)
![Player Details](https://github.com/erabhi95/Project-Sportan-of-Finding-Best-11-Players-Using-Python-and-Power-BI/assets/159037337/9c5db11f-53ee-45a6-a546-1ae9c8edefbf)
![Final 11](https://github.com/erabhi95/Project-Sportan-of-Finding-Best-11-Players-Using-Python-and-Power-BI/assets/159037337/fb968b5a-472e-44ce-b4fc-749daffb0e0a)

### Data Sources
The primary dataset used for this analysis are the following JSON files-
1. 't20_wc_player_info'-- Carrying player information
2. 't20_wc_match_results'-- Carrying Match results
3. 't20_wc_batting_summary'-- Carrying Batmen match summary
4. 't20_wc_bowling_summary'-- Carrying Bowlers match summary

### Tools
1. **Python Libraries (Numpy, Pandas, DataFrames)** - For conversion of unstructured data into structured form
2. **Microsoft Power BI** - For Data Visualisation and Anaysis

### KPIs Considered
Player details were the KPI's like 
- Batting Average
- Strike Rate
- Innings Batted
- Batting Position
- Average Balls Faced
- Bowling Economy
- Bowling Strike Rate
- Innings Bowled etc

### Data Cleaning
1. JSON Data files were loaded and inspected in python.
2. Python Libraries (numpy, pandas, dataframes) were used to convert data from unstructured to structured form.
3. Erroneous data removed.
4. New columns created for joining different tables.
5. Files were converted from JSON to CSV format.
7. CSV Data files were loaded into Power BI.
8. Checked for correct data type and formating.
9. Removed blank rows and duplicates from the data. 

### Data Transformation
1. Created links between all the tables.
2. Created new columns and measures using DAX queries for each of the KPIs to get insights out of the available data which were further used during dashboard creation. 
   
### Data Visualisation
1. Created an interactive dashboards for each of the 5 categories of players (Openers, Anchors, Finishers, All Rounders, Specialist Fast bowlers) based on the criteria given.
2. Added 'player details' as tool tip on each of the page for more detais.
3. Added navigation buttons across pages.
4. Created a Final 11 players report for each selection and analysis by the concerned user.

### Exploratory Data Analysis
- EDA is performed on the players data to find the best playing 11 for the team based on the given criteria. 

### Results
- As per the **Daily order trends, the Orders are Maximum on weekend evenings i.e. on Saturday & Sunday**. Strangely, there are even more daily orders on Monday.
- As per **Monthly order trends, the orders are maximum from January to July** months of the year.
- **'Classic' pizza category contributes maximum** to the Total Sales and Total number of Orders.
- **'Large' size pizza contributes maximum** to the Total Sales.
- In terms of **Revenue, 'The Thai Chicken pizza' has the maximum** revenue while **'The Brie Carre Pizza' has the minimum**.
- In terms of **Quantity Sold, 'The Classic Delux pizza' has the maximum** value while **'The Brie Carre Pizza' has the minimum**.
- In terms of **Total Orders, 'The Classic Delux pizza' has the maximum** value while **'The Brie Carre Pizza' has the minimum**.
  

### Insights and Recommendations
Inorder to improve “Dominos” Sales & Profits :
- Since **maximum orders are on Monday indepth analysis should be done** to figure out the possible root cause and further strategy should be made.
- For the **weekends i.e. Saturday & Sunday more offers should be rolled out** to further increase the sales of pizza.
- Since **'Classic' category & 'Large' size are the most preffered** customer choice, special attention should be given to them with **100% stock availability**, in order to maintain customer satisfaction with Dominos store.
- Similarly **'The Thai Chicken Pizza' & 'The Classic Delux Pizza' are the most preffered** customer choice, therefore **special attention** should be given to them with **100% stock availability**.
- **'The Brie Carre Pizza' is the least preffered choice** of customers, therefore **customer feedbacks** can be taken for this to know the root cause (if any).  
