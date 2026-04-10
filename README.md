# Video Game Industry Analysis (2000–2013)

##  Project Goal

The goal of this project is to analyze the development of the video game industry from 2000 to 2013 based on historical data on game sales, platforms, genres, and user and critic ratings.  

The analysis helps to identify key trends in the gaming industry and understand factors influencing game success.

---

##  Dataset Description

The dataset `/datasets/new_games.csv` contains information about video games, including sales, platforms, genres, and ratings.

Each record represents a single game and includes the following features:

- **Name** — game title  
- **Platform** — platform of release  
- **Year of Release** — release year  
- **Genre** — game genre  
- **NA sales** — sales in North America (millions)  
- **EU sales** — sales in Europe (millions)  
- **JP sales** — sales in Japan (millions)  
- **Other sales** — sales in other regions  
- **Critic Score** — critic rating (0–100)  
- **User Score** — user rating (0–10)  
- **Rating** — ESRB age rating  

---

##  Project Workflow

The project includes the following steps:

- Loading and initial exploration of the dataset  
- Data cleaning and preprocessing:
  - handling missing values  
  - correcting data types  
  - removing duplicates  
  - standardizing column names  
- Filtering data for the period 2000–2013  
- Categorizing games by user and critic ratings  
- Identifying top platforms by number of games  
- Analysis of trends in the gaming industry  

---

## Key Insights

- The dataset required significant preprocessing, including handling missing values, correcting data types, and removing duplicates (~3% of rows were removed)
- Certain platforms (such as PS2, DS, and Wii) dominated the market during 2000–2013
- User and critic scores contain missing values but remain useful for analyzing game performance trends
- The video game market in this period was strongly platform-driven, with clear leaders in terms of game releases

---

## Conclusion

This project provides an overview of the video game industry between 2000 and 2013.  
The analysis highlights key platforms, regional sales distribution, and the relationship between ratings and game popularity.

## Tools Used

- Python  
- pandas  
- matplotlib