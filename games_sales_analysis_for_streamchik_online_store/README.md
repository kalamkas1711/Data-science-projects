### Project Description

You are working at "Streamchik," an online store that sells computer games worldwide. Historical data on game sales, user and expert ratings, genres, and platforms (such as Xbox or PlayStation) are available from open sources. Your task is to identify patterns that determine the success of a game. This will help you to bet on a potentially popular product and plan advertising campaigns.

You have data up to 2016. Let's assume it's December 2016, and you are planning a campaign for 2017. You need to work with the data, whether you're forecasting sales for 2017 based on 2016 data or for 2027 based on 2026 data.

The dataset includes the abbreviation ESRB (Entertainment Software Rating Board), an association that determines the age rating of computer games. ESRB evaluates game content and assigns it an appropriate age category, such as "Adults Only," "Early Childhood," or "Teen."

### Project Execution Instructions

**Step 1:** Open the data file and review the general information.
   - File games.csv

**Step 2:** Prepare the data.
   - Rename columns (convert to lowercase).
   - Convert data into appropriate types. Describe which columns had their data types changed and why.
   - Handle missing values if necessary:
      - Explain why certain missing values were filled in a specific way or why they were left as is.
      - Describe reasons that might lead to missing values.
      - Pay attention to the abbreviation 'tbd' in the user score column. Explain how to handle this value.
   - Calculate total sales in all regions and record them in a separate column.

**Step 3:** Conduct exploratory data analysis.
   - Examine the number of games released in different years. Are data from all periods important?
   - Analyze sales trends across platforms. Select platforms with the highest total sales and plot their distribution over the years. How long does it typically take for new platforms to emerge and old ones to fade away?
   - Take data for the corresponding relevant period. Determine the relevant period based on your previous analysis. The key factor is that these data will help forecast sales in 2017.
   - Do not consider data from previous years.
   - Which platforms lead in sales, grow, or decline? Select several potentially profitable platforms.
   - Construct a box plot for global game sales broken down by platform. Describe the result.
   - Examine how user and critic reviews affect sales within a popular platform. Create a scatter plot and calculate the correlation between reviews and sales. Formulate conclusions.
   - Relate the conclusions to game sales on other platforms.
   - Look at the overall distribution of games by genre. What can be said about the most profitable genres? Are there genres with high and low sales?

**Step 4:** Create a profile for users in each region.
   - For users in each region (NA, EU, JP):
      - Identify the most popular platforms (top 5). Describe differences in sales shares.
      - Identify the most popular genres (top 5). Explain the difference.
      - Does the ESRB rating influence sales in a specific region?

**Step 5:** Test hypotheses.
   - Average user ratings for Xbox One and PC platforms are the same.
   - Average user ratings for Action and Sports genres are different.
   - Set your own threshold value for alpha.
   - Explain:
      - How you formulated the null and alternative hypotheses.
      - Which criterion you used to test the hypotheses and why.

**Step 6:** Write a summary.
   - Presentation: Complete the task in a Jupyter Notebook. Fill in code in code cells, textual explanations in markdown cells. Apply formatting and headers.

### Data Description

- **Name:** Game title
- **Platform:** Gaming platform
- **Year_of_Release:** Year of release
- **Genre:** Game genre
- **NA_sales:** Sales in North America (millions of copies sold)
- **EU_sales:** Sales in Europe (millions of copies sold)
- **JP_sales:** Sales in Japan (millions of copies sold)
- **Other_sales:** Sales in other countries (millions of copies sold)
- **Critic_Score:** Critic score (maximum 100)
- **User_Score:** User score (maximum 10)
- **Rating:** ESRB rating. This association determines the rating of computer games and assigns them an appropriate age category.

Note: Data for 2016 may be incomplete.
