# Football-Analytics-Project

## 1. Project Overview
This project provides informative insights into whether a country's yearly Domestic Football League's position in the 'https://www.teamform.com/' ranking has any correlation with the yearly Countries International Football team's performance through an interactive visualisation.
The goal is achieved through web scrapping, data cleaning, manipulation, and visualisation using Python programming language and its libraries. 

The project includes two Jupyter notebooks: one for preparing the data and another for visualising the data.  
- **`Data_Aquisition_&_Cleaning .ipynb`** 
  - Performs Web Scrapping, initial Data Exploration, Analytics, grouping, aggregating, combining and saving the data.
  - Libraries used in this notebook: pandas, numpy, plotly.express, BeautifulSoup, requests, base64.
    
- **`Football_Data_Notebook.ipynb`** 
  - Loads the saved data and creates the bar chart that displays the Countries International Performance & their National Football League Rankings.
  - Libraries used in this notebook: pandas, plotly.express, base64, plotly.graph_objects.

## 2. Features

- **WebScrapping & Data Cleaning**  
  Obtain the required data from the website through webscrapping and creating the dataset. Cleaning the acquired data by handling missing values, filtering irrelevant data, and transforming it into a suitable format for analysis using the relevent libraries.

- **Data Transformation**  
  Apply data manipulation techniques to create derived features that illustrate key performance metrics of football teams like win %, perform aggregations and filter the data to get the Top 10 National Leagues for the years 2015 - 2023 and the Top 10 International Football Teams based on win % 2015 - 2023.

- **Interactive Visualizations**  
  Use Plotly Express and base64 to create interactive bar charts that allow users to explore and compare in detail the standings of the Nation Leagues and their respective country's team performance based on Year also enabling the viewer to highlight the country's footballing region.

- **Exploratory Data Analysis, Grouping and Aggrigating**  
  Visualize key metrics and relationships in the data to understand underlying patterns. Grouping and aggregating the data to get the top 10 Leagues and Country teams based on TeamForm's rating and overall win% for each year.

## 3. Installation

To run the project locally, follow these steps:

  1. Download the `Data_Aquisition_&_Cleaning.ipynb` and `Football_Data_Notebook.ipynb` files.
  2. Ensure you have Jupyter Notebook installed on your device.
  3. Install the required libraries:
     ```bash
     pip install pandas numpy plotly.express beautifulsoup4 requests base64 plotly.graph_objects
  4. Open the notebooks using Jypyter Notebook.
   
## 4. Files Included

### 1. `Data_Aquisition_&_Cleaning .ipynb`
  - Performs Web Scrapping to get the data from the Data Sources 'https://www.teamform.com/' and 'https://raw.githubusercontent.com/martj42/international_results/master/results.csv'.
  - Performs initial Data Exploration, Analytics. Further grouping, aggregating, combining and saving the data.
  - Producing and adding respective League Logo and saving the initial bar plots visualisation.
  - Libraries used in this notebook: pandas, numpy, plotly.express, BeautifulSoup, requests, base64.
    
### 2. `Football_Data_Notebook.ipynb`
  - Loads the saved data and creates the bar chart that displays the Countries International Performance & their National Football League Rankings.
  - Adds interactive features like sliders and buttons to change the year and highlight country based on footballing region.
  - Libraries used in this notebook: pandas, plotly.express, base64, plotly.graph_objects.


## 5. Data Sources

### Source 1: 'https://www.teamform.com/'
A website containing data on each national league's quarterly rankings for each year which contains various fields (e.g., League, Country, Rank, TeamFormRating).

### Source 2: 'https://raw.githubusercontent.com/martj42/international_results/master/results.csv'  
A website containing data on each Country's Internation Football Match for each year which contains various fields (e.g. date, home_team, away_team, home_score, away_score, tournament, city, country).

## 6. Libraries Used

This project uses the following Python libraries:

1. **pandas** – For data manipulation and cleaning.  
2. **numpy** – For numerical operations and transformations.  
3. **plotly.express** – For creating interactive visualizations with Plotly.
4. **beautifulsoup4** - For performing web scrapping and retieving the dataset from the html.
5. **base64** – Storing and retrieving the initial bar charts and logos as images to add to the visualisation.
6. **plotly.graph_objects** – For creating and adding interactive features to the visualisations with Plotly.


## 7. How to Use

### Running the Notebooks:

1. **Data Cleaning and Extraction**:
   - Open `Data_Aquisition_&_Cleaning .ipynb` in Jupyter Notebook.
   - Follow the steps to extract, clean and transform the data.
   - After which the dataset is saved as `'int_results.csv'`.

2. **Data Visualization**:
   - Open `Football_Data_Notebook.ipynb` in Jupyter Notebook.
   - Use the cleaned dataset (`'int_results.csv'`) to create interactive visualization.
   - Explore trends, correlations, and insights within the plots that shows the Countries International Performance & their National Football League Rankings for each year.

## 8. License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

