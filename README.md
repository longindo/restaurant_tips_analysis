# Restaurant Tips Analysis
This project performs an in-depth data analysis of a restaurant tips dataset from 1987, encompassing 244 individual bills. **Utilizing Python and key data analysis libraries such as Pandas and Matplotlib** the primary goal is to explore the relationships between various variables (like total bill, gender, smoking status, day of the week, time of day, and party size) and the tips customers leave. **This analysis aims to uncover insights into tipping behavior, which could be valuable for restaurant management and customer service strategies.**

## Data
This analysis utilizes the `tips` dataset, which contains information from 244 restaurant bills collected in the US in 1987.

The dataset includes the following variables:
* `total_bill`: Total bill amount (in dollars)
* `tip`: Tip amount (in dollars)
* `sex`: Gender of the person paying the bill (Male/Female)
* `smoker`: Whether the party included smokers (Yes/No)
* `day`: Day of the week (Sun, Sat, Thur, Fri)
* `time`: Time of day (Dinner/Lunch)
* `size`: Size of the party (number of people)

The dataset is publicly available and can be accessed or downloaded from: [https://raw.githubusercontent.com/RusAbk/sca_datasets/main/tips.csv](https://raw.githubusercontent.com/RusAbk/sca_datasets/main/tips.csv)

## Goals
The primary goals of this analysis are to:
* Explore the relationships between various factors (total bill, gender, smoking status, day of the week, time of day, and party size) and the tips customers leave.
* Uncover insights into tipping behavior within the restaurant setting.
* Provide valuable information that can be utilized for restaurant management and improving customer service strategies.

## Results
Based on the analysis of the restaurant tips dataset, several key insights into tipping behavior have been identified:

* **Overall Tipping Behavior:** The average tip across the entire dataset is approximately $3.00, with a median tip of $2.90.

* **Smokers vs. Non-Smokers:** Interestingly, groups with smokers tend to leave slightly higher average tips ($3.05) compared to non-smokers ($2.99). This suggests that smoking status might not be a direct deterrent to tipping generously, or other underlying factors are at play.

* **Gender and Tipping:** Male customers tend to leave a higher average tip ($3.09) than female customers ($2.83), although further statistical analysis would be needed to confirm significance.

* **Day of the Week:** Tips are generally higher on weekends (average $3.12) compared to weekdays (average $2.76), potentially due to different dining habits or larger bill sizes on weekends.

* **Time of Day:** Dinners receive higher average tips ($3.10) than lunches ($2.73), likely reflecting the tendency for dinner bills to be larger.

For detailed analysis, including visualizations and the full code, please refer to the [Jupyter Notebook](https://github.com/longindo/restaurant_tips_analysis/blob/main/B%E1%BA%A2O_LONG_Restaurant_tips_analysis.ipynb) in this repository.
