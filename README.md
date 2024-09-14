


# 1. Data Loading and Preprocessing
The datasets used for analysis include:

Play Store Data (apps_df)
User Reviews Data (reviews_df)
Missing data was handled effectively:
Dropping rows with missing values in critical columns (e.g., Rating).
Filling missing values in other columns with the mode.
Removing duplicate entries.
Ensuring that the Rating values were capped at 5.
Transformation of data included converting Installs and Price to numerical formats and computing log-transformed versions of these features.

Highlights:
Proper handling of missing data ensures a clean dataset.
Data types were adjusted accordingly, ensuring smooth processing for further analysis.


# 2. Feature Engineering
Created a Revenue column based on the formula Price * Installs.
Applied sentiment analysis on the Translated_Review using the VADER lexicon to compute sentiment polarity scores for the reviews.
Extracted the year from the Last Updated column to understand trends over time.

Highlights:
Creation of a new Revenue metric adds business insights.
Sentiment analysis of user reviews helps in understanding customer feedback.

# 3. Exploratory Data Analysis (EDA)
Various visualizations were created using Plotly to explore app categories, types, reviews, and ratings. Key plots include:

Category Analysis: Bar chart showing top categories by app count.

App Type Distribution: Pie chart demonstrating the distribution of free vs paid apps.

Rating Distribution: Histogram showing the skewness towards higher ratings.

Sentiment Distribution: Bar chart visualizing the sentiment scores from user reviews.

Installs by Category: Horizontal bar chart showing installs by app category.

Revenue by Category: Bar chart showing revenue across app categories.

Highlights:
The visualizations are clean and informative, with clear titles and insights.
The EDA covers multiple aspects, including app type, rating, installs, and sentiments, providing a comprehensive overview of the data.

# 4. Key Insights from Visualizations

Top Categories: Tools, entertainment, and productivity apps dominate the Play Store.

App Type: Most apps are free, indicating a strategy to attract users and monetize through ads or in-app purchases.

Rating Trends: Ratings are skewed towards higher values, showing a general satisfaction from users.

Sentiment: User sentiments are slightly inclined towards positive feedback.

Installs and Revenue: Categories like social and communication apps have the highest installs, while business and productivity apps generate the most revenue.

Highlights:
The insights generated from the analysis provide a clear understanding of user behavior and app performance in different categories.

# 5. Web Dashboard Creation
A dynamic HTML dashboard was generated using Plotly, allowing the plots to be displayed interactively.
The dashboard includes all the key visualizations, with the functionality to view insights by clicking on the plot containers.

Highlights:
The creation of a web-based dashboard offers an engaging way to present the findings.
The dashboard provides an interactive experience, enhancing the usability of the analysis.


# 7. Technical Strengths
Efficient use of Python libraries such as pandas, NumPy, Plotly, and scikit-learn.
Application of NLP techniques for sentiment analysis using the VADER lexicon.
Visual aesthetics in the plots are maintained with consistent colors, fonts, and background themes.
The automation of dashboard creation using HTML templates demonstrates good coding practices and makes it easier to share the results.

# Conclusion:
This project effectively analyzes Google Play Store data, delivering meaningful insights through data cleaning, feature engineering, exploratory analysis, and visualization. The combination of sentiment analysis, revenue calculation, and a dashboard presentation makes it a well-rounded project. 

## DASHBOARD

![ss-1](https://github.com/user-attachments/assets/9f09770f-f3d1-4600-994f-08dd26ffca51)

![ss-2](https://github.com/user-attachments/assets/14c25d13-1108-48f7-95f1-b3356efe296a)
