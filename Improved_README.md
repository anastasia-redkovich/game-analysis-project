# Video Game Industry Analysis (2000–2013)

## Project Goal

The goal of this project is to analyze the video game industry from 2000 to 2013 using historical data on sales, platforms, genres, and user and critic ratings.

The analysis aims to identify key market trends and understand factors influencing game success.

---

## Dataset Description

The dataset `/datasets/new_games.csv` contains information about video games, including:

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

---

## Project Workflow

The analysis includes the following steps:

- Data loading and initial inspection  
- Data cleaning (handling missing values, fixing data types, removing duplicates)  
- Filtering data for the period 2000–2013  
- Exploratory data analysis (platforms, genres, regional sales, ratings)  
- Correlation analysis between ratings and sales  
- Visualization of key trends  

---

## Key Insights

- The North American and European markets show similar patterns and dominate global sales, while Japan behaves differently.
- Action and Sports are the most popular genres in Western markets, while Role-Playing games dominate in Japan.
- A small number of platforms account for most game releases, indicating a concentrated market structure.
- Sales peaked around 2007–2008 and then declined.
- Critic scores show a weak positive correlation with sales, while user scores have almost no significant relationship.

---

## Conclusion

The video game market between 2000 and 2013 was strongly influenced by regional preferences, platform dominance, and genre popularity.

While critic scores have a slight impact on sales, they are not a strong predictor of commercial success. Overall, market performance is driven more by platform and genre trends than by user or critic ratings.

---

## Tools Used

- Python  
- pandas  
- matplotlib  