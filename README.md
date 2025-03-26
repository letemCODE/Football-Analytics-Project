# Football-Analytics-Project

## 1. Project Overview
This project provides informative insights into whether a country's yearly Domestic Football League's position in the 'https://www.teamform.com/' ranking has any correlation with the yearly Countries International Football team's performance through an interactive visualisation.
The goal is achieved through web scrapping, data cleaning, manipulation, and visualisation using Python programming language and its libraries. 

The project includes two Jupyter notebooks: one for preparing the data and another for visualising the data.  
- ###**Data_Aquisition_&_Cleaning .ipynb** 
  - Performs Web Scrapping to get the data from the Data Sources 'https://www.teamform.com/' and 'https://raw.githubusercontent.com/martj42/international_results/master/results.csv'.
  - Performs initial Data Exploration, Analytics. Further grouping, aggregating, combining and saving the data.
  - Producing and adding respective League Logo and saving the initial bar plots visualisation.
  - Libraries used in this notebook: pandas, numpy, plotly.express, BeautifulSoup, requests, base64.
    
- ###**Football_Data_Notebook.ipynb** 
  - Loads the saved data and creates the bar chart that displays the Countries International Performance & their National Football League Rankings.
  - Adds interactive features like sliders and buttons to change the year and highlight country based on footballing region.
  - Libraries used in this notebook: pandas, plotly.express, base64, plotly.graph_objects.

## 2. Features

- **Data Cleaning and Extraction**  
  Clean the dataset by handling missing values, filtering irrelevant data, and transforming it into a suitable format for analysis.

- **Data Transformation**  
  Apply data manipulation techniques to create derived features and perform aggregations.

- **Interactive Visualizations**  
  Use Plotly Express to create interactive charts that allow users to explore data in detail (e.g., line plots, bar charts, scatter plots).

- **Exploratory Data Analysis (EDA)**  
  Visualize key metrics and relationships in the data to understand underlying patterns.

- **Exporting Cleaned Data**  
  Save the cleaned dataset for further analysis or reporting.

---

## 3. Installation

To run the project locally, follow these steps:

1. Clone this repository to your local machine.
2. Install the required libraries:

## 4. Files Included

### 1. `data_cleaning_and_extraction.ipynb`  
This notebook covers the following steps:
- Loading raw data.
- Cleaning data by handling missing values, duplicates, and irrelevant columns.
- Extracting necessary features for analysis.
- Saving the cleaned dataset as a new CSV file.

### 2. `data_visualization.ipynb`  
This notebook covers:
- Visualizing key data trends and patterns using Plotly Express.
- Creating interactive plots to explore different aspects of the data.
- Generating visual reports to support decision-making.

### 3. `data/`  
This directory contains the raw dataset for analysis (e.g., `raw_data.csv`).

---

## 5. Data Sources

### Source 1: `raw_data.csv`  
A sample dataset used for the project, which contains various fields (e.g., customer information, sales data, product details).

---

## 6. Libraries Used

This project uses the following Python libraries:

1. **pandas** – For data manipulation and cleaning.  
2. **numpy** – For numerical operations and transformations.  
3. **plotly** – For creating interactive visualizations with Plotly Express.  
4. **jupyter** – For running and managing Jupyter notebooks.

---

## 7. How to Use

### Running the Notebooks:

1. **Data Cleaning and Extraction**:
   - Open `data_cleaning_and_extraction.ipynb` in Jupyter Notebook.
   - Follow the steps to clean and transform the dataset.
   - After cleaning, the dataset is saved as `cleaned_data.csv`.

2. **Data Visualization**:
   - Open `data_visualization.ipynb` in Jupyter Notebook.
   - Use the cleaned dataset (`cleaned_data.csv`) to create interactive visualizations.
   - Explore trends, correlations, and insights with various plot types (e.g., bar charts, scatter plots, line plots).

---

## 8. Customization

You can customize this project by:

1. **Adding New Data**:  
   - Replace the raw dataset with your own CSV file.
   - Modify the data cleaning steps as necessary.

2. **Enhancing Visualizations**:  
   - Add new visualizations or modify existing ones by adjusting Plotly Express settings (e.g., chart types, colors, hover data).

3. **Adding New Analysis**:  
   - Perform additional data analysis in the notebooks, such as calculating new metrics or performing statistical tests.

---

## 9. Troubleshooting

1. **Data Import Issues**: Ensure the dataset is correctly formatted (e.g., CSV) and located in the appropriate directory.
2. **Plotly Visualization Errors**: If visualizations don’t render, ensure that you have the latest version of Plotly installed. Run `pip install plotly --upgrade`.
3. **Missing Libraries**: If you encounter missing libraries, install them using `pip install <library_name>`.

---

## 10. Contributions

Contributions are welcome! Feel free to:

- Open an issue for bug reports or feature requests.
- Submit a pull request with enhancements.

---

## 11. License

This project is licensed under the **MIT License**. See [LICENSE](LICENSE) for details.
