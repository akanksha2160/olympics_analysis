# Olympics Analysis Web Page

This project is an Olympics analysis web page that utilizes machine learning to provide insights into the Summer Olympics dataset spanning 124 years. The web page is deployed on Streamlit, and users can access it via the provided link [here](https://olympicsanalysis.streamlit.app/). It allows users to find interesting insights with just a click. The analysis is conducted on four bases: Medal Tally, Country-wise Analysis over the years, and for a specific year, Overall Analysis - Top Finds, and Athlete-wise Analysis.

## Web Page Features

### 1. Medal Tally
Users can select a specific year and country to view the medal tally for that year or country. The web page displays a table with the count of Gold, Silver, Bronze, and total medals won.

### 2. Overall Analysis - Top Finds
This section provides an overview of the Olympics data. It includes the number of editions, host cities, sports, events, athletes, and participating nations over the years. A heatmap is shown to illustrate the number of events for each sport over time. Users can select a specific sport to see the top successful athletes in that sport.

### 3. Country-wise Analysis
Users can choose a specific country to view its medal tally over the years. The web page displays a line chart showing the number of medals won by the selected country each year. A heatmap is also provided, displaying the number of events in which the country excels. The top 10 athletes from the selected country are listed.

### 4. Athlete-wise Analysis
This section includes distributions of the age of athletes, with separate plots for all athletes and gold medalists. It also provides a line chart showing the participation of men and women over the years.

## Dataset Link
The dataset used for analysis can be accessed from Kaggle. The link to the dataset is [here](https://www.kaggle.com/datasets/nitishsharma01/olympics-124-years-datasettill-2020).

## Requirements
To run the code on your local machine, make sure to install the following libraries:
- Streamlit
- Pandas
- Plotly Express
- Matplotlib
- Seaborn
- Plotly Figure Factory

To run the code on Streamlit, open the terminal and execute the following command:
```
streamlit run app.py
```

Feel free to explore the web page and find interesting insights from the Summer Olympics data spanning 124 years! You can access the web page [here](https://olympicsanalysis.streamlit.app/).
