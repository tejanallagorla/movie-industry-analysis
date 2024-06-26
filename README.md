# movie-industry-analysis

## Data/Technologies Used
**Data** - Movie data (1980-2020) with over 7,500 records from Kaggle.<br>
**Data Cleaning & Analysis** - Jupyter Notebook, Libraries: pandas, numpy, statsmodels, matplotlib, seaborn<be>

## Question
What factors have an effect on a movie's gross revenue, and how strong are those effects?

## Predictions
1) The budget for the movie's production and its gross revenue will be correlated.
2) The score of the movie and its gross revenue will be correlated.
3) The company that produces the movie will have an effect on its gross revenue.
4) The star of the movie will have an effect on its gross revenue.

## Results
* Budget and gross revenue had a strong positive correlation (r-value of 0.74).
* Score and gross revenue had a positive correlation, but it was weak (r-value of 0.22).
* Production company had a strong effect on gross revenue (p-value < 0.05 and eta-squared value of 0.36).
* Movie star had a strong effect on gross revenue (p-value < 0.05 and eta-squared value of 0.41).
* Votes and gross revenue had a strong positive correlation (r-value of 0.61).
* Genre had an effect on gross revenue (p-value < 0.05 and eta-squared value of 0.12).

## Limitations
* Some records had missing values in one or more columns, so they were excluded during the analysis (2247 records). Only complete records were used (5421 records).
