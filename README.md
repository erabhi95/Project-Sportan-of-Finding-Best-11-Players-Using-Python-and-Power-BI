# Project Sportan (Finding Best 11 Players)
# Power BI Dashboard Link
https://app.powerbi.com/view?r=eyJrIjoiZmRlNTc2ODMtYzAxNy00OWQ5LTkyNDItODhjMDRhZTE3NjUzIiwidCI6ImRmODY3OWNkLWE4MGUtNDVkOC05OWFjLWM4M2VkN2ZmOTVhMCJ9
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

### Project Overview
This is a data analysis project which aims at finding the best 11 players based on certain criteria, as provided by the Subject Matter Experts (SMEs) of the game, to select the best playing 11 team.

**Final Report**

![Openers](https://github.com/erabhi95/Project-Sportan-of-Finding-Best-11-Players-Using-Python-and-Power-BI/assets/159037337/1a827b50-cbb4-4d76-babb-b890d7187ead)
![Anchors](https://github.com/erabhi95/Project-Sportan-of-Finding-Best-11-Players-Using-Python-and-Power-BI/assets/159037337/9b7621c6-5afa-4929-acd9-cbf2aae8968c)
![Finishers](https://github.com/erabhi95/Project-Sportan-of-Finding-Best-11-Players-Using-Python-and-Power-BI/assets/159037337/e47bb85e-e607-4c5d-a0c2-16855cd3a0ca)
![All Rounders](https://github.com/erabhi95/Project-Sportan-of-Finding-Best-11-Players-Using-Python-and-Power-BI/assets/159037337/40b0197a-5889-4417-99d8-fdb6fd1d575e)
![Specialist Fast Bowlers](https://github.com/erabhi95/Project-Sportan-of-Finding-Best-11-Players-Using-Python-and-Power-BI/assets/159037337/104d8e54-6adb-49d8-ba86-17ea9001e1d6)
![Player Details](https://github.com/erabhi95/Project-Sportan-of-Finding-Best-11-Players-Using-Python-and-Power-BI/assets/159037337/9bcd1135-c5dc-430e-9d0a-e9e2a148565b)
![Final 11](https://github.com/erabhi95/Project-Sportan-of-Finding-Best-11-Players-Using-Python-and-Power-BI/assets/159037337/2e146917-76f5-4db0-a436-3d80b66c6cc1)

### Data Sources
The primary dataset used for this analysis are the following JSON files-
1. 't20_wc_player_info'-- Carrying player information
2. 't20_wc_match_results'-- Carrying Match results
3. 't20_wc_batting_summary'-- Carrying Batmen match summary
4. 't20_wc_bowling_summary'-- Carrying Bowlers match summary

### Tools
1. **Python Libraries (Numpy, Pandas, DataFrames)** - For conversion of unstructured data into structured form
2. **Microsoft Power BI** - For Data Visualisation and Analysis

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
2. Added 'player details' as tool tip on each of the page for more detaiLs.
3. Added navigation buttons across pages.
4. Created a Final 11 players report for each selection and analysis by the concerned user.

### Exploratory Data Analysis
- EDA is performed on the players data to find the best playing 11 for the team based on the given criteria. 

### Results
Five dashboards were created for each of the categories of players (Openers, Anchors, Finishers, All Rounders, Specialist Fast bowlers) based on the criteria given. Below are the shortlisted ones. 
- **Openers** - Rilee Rossouw, Quiton de Kock, Alex Hales, Kusal Mendis, Jos Buttler
- **Anchors** - Suryakumar Yadav, Glenn Phillips, Virat Kohli, Lorcan Tucker
- **Finishers** - Curtis Campher, Marcus Stoinis, Glenn Maxwell, Sikandar Raza, Hardik Pandya
- **All Rounders** - Rashid Khan, Shadab Khan, Mitchell Santner, Sikandar Raza
- **Specialist Fast Bowler** - Tim Southee, Sam Curran, Shaheen Shan Afridi, Anrich Nortje
