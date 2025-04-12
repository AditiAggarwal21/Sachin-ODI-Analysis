# 🏏 Sachin Tendulkar's ODI Career Analysis

This project is a deep-dive data analysis and visualization of **Sachin Tendulkar's ODI performance**.  
The dataset includes his batting scores, wickets, match conditions, and opposition details across his career.  
Using Python and libraries like **Pandas, Seaborn, Matplotlib, Plotly**, and tools like **BeautifulSoup** and **Requests**, this project aims to extract insights from raw cricket data and present them visually.

![](Images/Sachin_Tendulkar.jpg)

---

## 📊 Graphs & Visualizations

###  Distribution of Batting Scores

Shows the frequency of Sachin's scores across all ODI innings.

![](Images/Distribution_Of_Batting_Score.png)

**Insights**:
- The distribution is **right-skewed**, with most scores falling **under 50 runs**.
- **Scores below 10** are very common, highlighting the challenge of consistency even for greats.
- There are **peaks around 50 and 100**, showing frequent half-centuries and centuries.
- A **sharp decline** is seen after 100, with only a few innings crossing **150+**.
- This plot emphasizes the **rarity of big scores** and the importance of converting starts.

### Count of Centuries and Half-Centuries

Total Centuries: 49  
Total Half Centuries: 96

### Wickets Distribution

Displays the distribution of wickets taken by Sachin Tendulkar in ODI matches.

![](Images/Wickets_Distribution.png)

**Insights**:
- The **median number of wickets** per match is 0, indicating that he didn't bowl in many games or went wicketless.
- The **interquartile range (IQR)** lies between 0 and 2 wickets.
- A few **outliers** are visible, where he took **3 to 5 wickets** — showing occasional standout bowling performances.
- This visual reflects that while bowling wasn’t his primary role, he made key contributions when needed.

### Runs Conceded Distribution

Shows how many runs Sachin Tendulkar conceded in the ODI matches where he bowled.

![](Images/Runs_Conceded_Distribution.png)

**Insights**:
- The distribution is **slightly right-skewed**, meaning he more frequently conceded **lower to mid-range runs**.
- Most bowling spells resulted in conceding **between 10 to 35 runs**.
- Very few instances where he gave away **50+ runs**, showing that expensive spells were rare.
- The **peak lies around 20–25 runs**, indicating that his bowling was often economical.
- This visualization supports Sachin’s role as a **part-time bowler** who usually bowled short, tidy spells.

###  Number of Catches per Match

Represents the frequency of matches based on how many catches Sachin Tendulkar took.

![](Images/Number_of_catches_per_match.png)

**Insights**:
- In the **majority of matches**, Sachin took **no catches** — common for players not constantly fielding in high-catch zones.
- He took **1 catch** in over **100 matches**, showing steady contributions in the field.
- Very few instances of **2 or more catches** in a single game.
- Reflects his **occasional but important role as a fielder**, supporting the team in non-bowling and non-batting capacities.

### Matches Played vs Each Opposition

Bar plot showing the number of ODI matches Sachin Tendulkar played against each opposing team.

![](Images/Matches_played_VS_each_opposition.png)

**Insights**:
- Sachin played the **most matches against Sri Lanka**, followed by **Australia** and **Pakistan** — key cricketing rivals during his era.
- Regularly featured against **South Africa** and **New Zealand**, showing consistent participation in bilateral series and tournaments.
- Played fewer matches against **associate nations** like Namibia, Bermuda, and UAE.
- This distribution reflects India's **frequent fixtures with top-tier teams**, especially in Asia and ICC events.

### Top 10 Grounds Sachin Played At

Horizontal bar chart displaying the stadiums where Sachin Tendulkar played the most ODI matches.

![](Images/Top_10_Grounds_Sachin_Played_At.png)

**Insights**:
- **Sharjah** tops the list with the most number of matches, indicating his dominance in tournaments hosted in the UAE.
- Multiple grounds in **Sri Lanka (Colombo RPS, Colombo SSC)** and **India (Mumbai, Kolkata, Bangalore)** appear in the top 10, showing regional importance.
- Played frequently at **neutral venues** like **Toronto**, highlighting India's participation in international series outside the subcontinent.
- The list represents grounds where he had both iconic performances and consistent appearances.

### Toss Results

**Bar chart** showing the number of matches where the toss was **won** or **lost**.

![](Images/Toss_Results.png)

**Insights**:
- The number of matches where the toss was **won** is slightly higher than those where it was **lost**, suggesting a near-even split.
- This balance indicates that toss outcomes were not heavily skewed during Sachin Tendulkar’s career.
- Given the close numbers, it implies that the **match result or performance wasn’t heavily dependent on toss advantage**.
- The data reflects a large sample size, emphasizing Sachin’s long tenure and participation in a wide variety of match conditions.



## 📋 Tables

### 🗂 Match Outcome Table by Opposition

Shows number of matches won, lost, tied or with no result against each opposition.

| Opposition | Won | Lost | No Result | Tied |
|------------|-----|------|-----------|------|
| Australia  | 20  | 28   | 1         | 0    |
| Pakistan   | 23  | 26   | 2         | 1    |
| England    | 15  | 12   | 1         | 0    |
| ...        | ... | ...  | ...       | ...  |

_📌 This was created using Pandas `pd.crosstab` and `pivot_table`._

---

## 🏁 Conclusion

- Sachin Tendulkar's ODI career is rich with insights across batting, bowling, and match conditions.
- Visualizations helped bring out patterns in performance based on opposition, match results, and conditions.
- Tools like **Seaborn**, **Plotly**, and **Matplotlib** made the data exploration intuitive and appealing.
- This analysis can be extended further into:
  - Venue-based performance
  - Match-winning contributions
  - Comparisons with peers like Dravid, Sehwag, etc.

---

## 🔖 Notes

- All graphs are saved as `.png` files using the **same name as the graph title**, e.g., `toss_results.png`, `Wickets_vs_Opposition.png`, etc.
- All code and notebooks are available in the repo.
