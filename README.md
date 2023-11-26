# Game_Night_Chronicles_Board_Games_in_the_Lens_of_Data_Analysis

# Board Game Data Analysis Summary

## 🎲 Project Overview

### Background
In this board game data analysis project, I explored a dataset containing information on over `20,000` ranked board games from the BoardGameGeek (BGG) website. The goal was to leverage data-driven insights to recommend a game for an enjoyable board game night.

### The Data
The dataset, compiled in `February 2021`, includes details such as game name, publication year, player recommendations, playtime, age appropriateness, user ratings, and more. It originates from the BoardGameGeek website, a vibrant community of board game enthusiasts.

## 📊 Key Findings

### Data Cleaning
- The dataset required meticulous cleaning due to numerous zero and NA missing values. Handling strategies were employed based on the quantity and intended use of the data.

### Temporal Trends
- The `Year Published` data spans from around 3500 BC to the present day, with a surge in board game releases since the 1970s. Recent years have witnessed the launch of over 1000 board games.

### Correlation Insights
- **Heatmap Highlights:**
   - Moderate positive correlations between `Complexity Average` and `Min Age` and `Rating Average`.
   - Negative correlation between `Rating Average` and `BGG Rank`, suggesting higher BGG rankings correspond to higher average ratings.
   - Strong correlation (0.99) between `Owned Users` and `Users Rated`, indicating games with more users receive more ratings.

### Age and Complexity
- `Complexity Average` tends to rise with the minimum recommended age up to 12 years, with fluctuations thereafter. A notable complexity increase is observed between 12-16 years.

### Complexity and Ratings
- A general trend indicates that more complex games tend to receive higher ratings, though with significant variability.

### Players and Ratings
- Weak positive correlation between the number of players and the game's `Rating Average`, with most games falling between 6 and 8.5 in ratings.

### Age Recommendations
- Games are predominantly recommended for ages 10-12, with a smaller percentage designed for older players.

### Popular Game Domains
- `Wargames` and `Strategy Games` emerge as the most common game categories. Games in these genres generally boast higher `Rating Average`, making them recommended choices based on individual interests.

## 🧩 Conclusion
In conclusion, this data-driven analysis provides valuable insights for choosing a board game. Considerations include temporal trends, correlation patterns, age recommendations, and the popularity of game domains. Whether you prefer strategy games or wargames, this analysis equips you to make an informed decision for an entertaining board game night.
