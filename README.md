# Exploring-Customer-Feedback-Sentiment-and-Service-Quality-in-Indian-Airlines

Project Overview
This project analyzes customer sentiment from airline reviews using Natural Language Processing (NLP) techniques. The analysis focuses on extracting insights from the textual data and understanding the factors influencing customer satisfaction and dissatisfaction.

This involves scraping airline customer reviews from the Skytrax website, preprocessing the collected data, performing text mining, and conducting sentiment analysis to gain insights into customer sentiments. Visualizations were also generated to present the findings in an easy-to-understand manner. Using SmartPLS, we performed a PLS-SEM (Partial Least Squares Structural Equation Modeling) analysis to test the cause-effect relationship between different variables, employing a serial mediation model.

The analysis is focused on India for the decade (2014-2024). The 4 major airlines studied are Air India, Indigo, Vistara, and Spice Jet resulting in a combined 3745 reviews or data points for analysis.

Reason for Analysis:
Understanding customer sentiment is crucial for the airline industry, where customer satisfaction directly influences brand loyalty and market share. By combining sentiment analysis with a serial mediation model, this project not only uncovers key drivers of customer sentiment but also provides insights into the mediating factors that shape the overall customer experience. This analysis empowers airlines to improve customer satisfaction and retention through data-driven decision-making.

Tools & Libraries Used:
Python - 
BeautifulSoup for web scraping
pandas for data manipulation
NLTK for text preprocessing
VADER for sentiment analysis
matplotlib, seaborn, and plotnine for data visualization

SmartPLS-
For the PLS-SEM analysis to model and test the relationships between latent variables.

How to Use
Data Scraping: You can scrape data using the 'Web_Scraping_Skytrax_Reviews.ipynb' file, which collects airline reviews from the Skytrax website airlinequality.com.
Preprocessing: The preprocessed data is stored in a .csv file for further analysis. Run the preprocessing script 'Data_Preprocessing_Cleaning.ipynb' to clean the data.
Sentiment Analysis: Execute the 'NLP_Airline_Reviews_Text_Mining.ipynb' file to run the sentiment analysis and generate results.
Visualizations: To generate graphs and visualizations, run the 'Visualization_of_Ratings.ipynb' file.

Authors:
Kanak Joshi : LinkedIn - http://www.linkedin.com/in/kanak-joshi-85838a2b7
             Portfolio - https://kanak-joshi11.github.io/
Surbi Mantri : LinkedIn - https://www.linkedin.com/in/surbi-mantri/ 
              Portfolio - https://surbimantri.github.io/
