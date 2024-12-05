# ⚽ FIFA 2022: Data Analysis and Insights

![FIFA 2022](fifa2022_logo.jpeg)

🏆 **Dive into the world of FIFA 2022 with data!**  
This project uncovers valuable insights about the world's most popular sport, focusing on player statistics, market values, contract details, and much more. Through data cleaning, exploratory data analysis (EDA), and powerful visualizations, this project provides a comprehensive analysis of the FIFA 2022 dataset.

---

## 📂 Project Overview  

🎯 **Objective**: Analyze the FIFA 2022 dataset to extract meaningful insights about players, teams, market values, and contracts.  

🗂 **Dataset**: The dataset contains detailed information about FIFA 2022 players, including their attributes (speed, strength, skills), market values, contract data, and more.  

🔧 **Tools Used**:  
- **Python** 🐍  
- **pandas** for data manipulation 🧹  
- **matplotlib**, **seaborn** for data visualization 📊  

---

## 🛠️ Data Cleaning Process  

To ensure a clean and insightful analysis, we first performed several data cleaning steps:  
1. **Removed Irrelevant Columns**: We dropped columns that didn’t contribute to our analysis, such as player photos and player URLs.  
2. **Handled Missing Data**: We addressed missing values by either imputing or dropping the rows depending on their significance.  
3. **Standardized Columns**: We renamed columns to maintain consistency, making them more readable for further analysis.  
4. **Outlier Detection and Removal**: We identified and removed outliers (such as players outside a reasonable age range) to ensure the quality of analysis.  
5. **Data Type Conversion**: We converted market values, contract dates, and other relevant fields into their appropriate data types (e.g., converting market values to numerical format).

---

## 📊 Key Insights and Visualizations  

### 1. **Top 10 Players by Market Value**  
- A bar plot showing the top 10 highest market value players in FIFA 2022. This highlights the elite players based on their financial worth.  

### 2. **Age Distribution of Players**  
- A box plot illustrating the distribution of players’ ages, along with the identification of outliers (players who are unusually young or old for professional soccer).  

### 3. **Contract Length vs Market Value**  
- A scatter plot visualizing the correlation between players’ contract length and their market value, revealing trends in long-term contracts and high-value players.

### 4. **Average Player Rating by Nationality**  
- A bar chart depicting the average ratings of players from different countries. This gives insights into which nations have the highest-rated players on average.  

### 5. **Players with the Longest Contracts**  
- A bar chart listing the top players with the longest contracts in the FIFA 2022 dataset, highlighting those who are committed to their teams for extended periods.

---

## 🎯 Key Takeaways  

- **Top Market Value Players**: The highest-valued players in FIFA 2022 are typically the ones with the best skill ratings and highest overall potential.  
- **Age Factor**: Younger players tend to have lower market values, but those who perform exceptionally well, like Mbappé and Haaland, break this pattern.  
- **Contract Analysis**: The length of a player’s contract correlates with their value, but not always—some long-term contracts involve players who aren’t in the top 10 for market value.  

---

## 🔄 Future Work and Improvements  

- **In-depth Player Role Analysis**: Analyzing the performance of different player positions and how it impacts market value and ratings.  
- **Team Performance Insights**: Extending the analysis to include team dynamics, including how well players perform in their teams versus individually.  
- **Player Transfer Market Trends**: Studying the historical market value changes for players and how transfers affect their value.

---

## 🚀 How to Run the Project  

1. Clone the repository:  
    ```bash
    git clone https://github.com/your-username/fifa-2022-analysis.git
    ```

2. Install the necessary packages:  
    ```bash
    pip install -r requirements.txt
    ```

3. Run the Jupyter Notebook to start exploring the data:  
    ```bash
    jupyter notebook FIFA_2022_EDA.ipynb
    ```

---

## 📬 Contact  
Feel free to reach out if you have any questions or suggestions.  

- [LinkedIn Profile](https://www.linkedin.com/in/yourprofile)  
- [GitHub Repository](https://github.com/your-username)  
