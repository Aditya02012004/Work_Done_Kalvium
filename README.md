# Work_Done_Kalvium
This repository give a gesture about the data web scrapping
This is project that is being made through the web scraapping where we import the libararies like pandas, matplotlib and requests for extracting and scrapping the data from the web, and pandas to create the data in the dataframe format and also used matplotlib to implement the graph insight of the data 
This Project contains 5 normal insights and 4 Graph insights of the extracted data

# About the Data 
The data is bassed on the current elections of Lok Sabha 2024 of which we have extracted from the website https://results.eci.gov.in/PcResultGenJune2024/index.htm and thus we have web scrapped the data

# Overview of the Project
This data is basically consist of the current elections of Lok Sabha 2024 where we have extracted the data from the following libraries

1. Pandas- To develop the dataframe of the data
2. matplotlib- To develop the insight of the data
3. request- To extract the data from the web through web scrapping

Thus after data extraction we have saved it into the variable extracted_df and run a loop to extract each row from the 'tr' tag into the 'td' tag of HTML. Afterthat, we have print the extracted_df as output as futher steps we have bring up into the basic insights of the data here is the list of insights we have created

Normal Insight without using matplotlib library
1. #Insight 1: Top 5 parties with the most wins
2. #Insight 2: Average number of wins per party
3. #Insight 3: Parties with only 1 win
4. #Insight 4: Top 3 parties with the most leads
5. #Insight 5: Parties with no leads

Graph insight using matplotlib library
1. #Graph Insight 1: Bar chart of the top 5 parties with the most wins
2. #Graph Insight 2: Pie chart of the number of parties with different number of wins
3. #Graph Insight 3: Box plot of the number of wins per party
4. #Graph Insight 4: Bar chart of the top 3 parties with the most leads

# Recommendation to open the project

1. Open .ipynb folder in jupyter Notebook(Recommended IDE) and run the code, whereas this code can also run on other IDE like VSCode, Pycharm and other IDE's

# Future Reference of the Porject

The project can be improved out with many techniqalities and code improvement in the future,The submited code is the basic code of the above task of being that is being asked out by the KALVIUM 

# Task Description

1) Scrape the information of the recently concluded Lok Sabha election from https://results.eci.gov.in 
2) Build a report of 10 key insight that you can derive from the data, and submit that in the repository.
