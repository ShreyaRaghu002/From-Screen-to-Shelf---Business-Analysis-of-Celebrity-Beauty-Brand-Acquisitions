# From Screen to Shelf - Business Analysis of Celebrity Beauty Brand Acquisitions
This project explores the transition of celebrity beauty brands from online-only to retail, analyzing acquisition patterns, consumer psychology and brand performance. It combines data collection, analysis, and visualization to provide actionable insights into retail strategies and consumer behavior.
# Project Structure:
+ data/: Contains the Celebrity Independent and Acquired Beauty Brands Dataset.
+ notebooks/: Used Jupyter Notebook to perform the analysis using python.
+ src/: Python scripts for data preprocessing, analysing and visulization.
+ README.md/: Project overview and setup instructions.
# Dataset Description:
This dataset contains 450 rows and 17 columns, detailing celebrity-founded beauty brands, their launch and acquisition history, product details, ratings, campaigns, target demographics, and market reach. Each row represents a unique brand-product combination, while columns cover attributes like founder, year, product category, social media following, sentiment score, and retail presence across regions. It integrates both qualitative brand information and quantitative performance metrics scrapped from the web. 
# Data Processing:
+ Imported necessary libraries (pandas, numpy, matplotlib) and loaded the dataset from Excel.
+ Converted columns like Product Launch Year, Sentiment Score, and Acquisition Year to numeric formats, handling errors with coercion.
+ Filled missing values in columns such as Acquired By and Retail Presence, and created new classification columns like Status and Type for independent vs. acquired brands.
+ Filtered the dataset based on specific conditions (e.g., product launch years, excluding "Multiple" retail presence) for focused analysis.
# Data Analysis:
+ Grouped data by Product Launch Year and Status to analyze the number of new products introduced by independent and acquired brands.
+ Aggregated average Sentiment Scores by Retail Presence and brand type to measure customer perception across channels.
+ Categorized acquisitions into “Before 2020” and “After 2020” to identify acquisition trends over time.
+ Created pivot tables to compare metrics side-by-side for easier interpretation.
# Data Visualization and Insights:
+ Line Plot - Product Launch Trends : Compared yearly product launches for independent vs. acquired brands with markers, labels, and gridlines. Independent beauty brands have generally been more consistent in launching new products over the selected years, while acquired brands show more fluctuations.
+ Grouped Bar Chart - Retail Channel Sentiment : Showed average sentiment scores by retail channel, using custom color schemes for brand types. Sentiment scores vary a lot by where products are sold, Independent brands often rate higher than acquired brands on digital-first channels like Amazon and brand websites.
+ Vertical Bar Chart - Channel Performance Patterns : Displayed the count of acquisitions before and after 2020, with value labels above bars. Physical retail channels show a more mixed picture, with acquired brands outperforming in some, but trailing behind in others; digital channels tend to favor independents.
# Conclusion:
Independent brands show steadier product launch activity over time and outperform acquired brands in customer sentiment on digital-first channels like Amazon and brand websites. Acquired brands have mixed results in physical retail, excelling in some channels but lacking the consistent online sentiment advantage of independents.





