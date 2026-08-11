✈️ Flight Price Analysis & Exploratory Data Analysis

📌 Overview
  This project performs **Exploratory Data Analysis (EDA)** on an airline flight dataset to understand flight patterns and the factors associated with airline ticket prices.
  The analysis uses Python and popular data analysis and visualization libraries to explore airlines, flight routes, departure and arrival times, travel class, stops, flight duration, days left before departure, and ticket prices.

🎯 Objectives

The main objectives of this project are:
  * Analyze the distribution of flights across different airlines.
  * Identify the number of flights from different source cities.
  * Identify the number of flights to different destination cities.
  * Compare source and destination flight counts for each city.
  * Analyze average ticket prices for different airlines.
  * Compare ticket prices across different travel classes.
  * Analyze the relationship between flight duration and ticket price.
  * Study the effect of stops on ticket prices.
  * Analyze flight duration distributions for different airlines.
  * Identify potential outliers in numerical variables.
  * Analyze relationships between numerical variables using correlation.
  * Create meaningful visualizations to understand the dataset.

📂 Dataset
The project uses the following dataset:
  * airlines_flights_data.csv
      The dataset contains information about airline flights, their routes, timings, duration, travel class, and ticket prices.

Dataset Features :-

  | Column           | Description                               |
  | ---------------- | ----------------------------------------- |
  | airline          | Name of the airline                       |
  | flight           | Flight number                             |
  | source_city      | City from which the flight departs        |
  | departure_time   | Departure time category                   |
  | stops            | Number/type of stops                      |
  | arrival_time     | Arrival time category                     |
  | destination_city | Destination city                          |
  | class            | Travel class                              |
  | duration         | Flight duration                           |
  | days_left        | Number of days remaining before departure |
  | price            | Ticket price                              |


🛠️ Technologies Used
Programming Language
  * Python

Libraries
  * Pandas — Data manipulation and analysis
  * NumPy — Numerical operations
  * Matplotlib — Data visualization
  * Seaborn — Statistical data visualization

Tools
  * Jupyter Notebook
  * Git
  * GitHub

🔍 EDA Performed

1. Airline Flight Count
  A count plot was used to analyze the number of flights operated by each airline.
  This helps identify which airlines have the highest and lowest number of flights in the dataset.

2. Source and Destination City Analysis
  The number of flights associated with each city was analyzed as both:
    * Source city
    * Destination city
  A grouped bar chart was used to compare source and destination flight counts for each city.

3. Average Ticket Price by Airline
  A bar plot was used to analyze the average ticket price for each airline.
  The airlines were also ordered according to their average ticket prices to make the comparison easier.

4. Flight Class Analysis
  The distribution of flights between different travel classes was analyzed using categorical visualization.
  The project also examines how ticket prices vary between different classes.

5. Flight Duration Analysis : 
A box plot was used to compare flight duration across different airlines.
The box plot helps identify:
    * Median flight duration
    * Distribution spread
    * Interquartile range
    * Variability
    * Potential outliers

6. Flight Price Distribution :
  The distribution of ticket prices was analyzed using statistical visualization techniques.
  This helps understand how flight prices are distributed throughout the dataset.

7. Outlier Analysis :
Box plots were used to identify unusual values in numerical columns such as:
    * duration
    * price
    * days_left
Potential outliers were investigated before deciding whether they represented valid observations or data-quality issues.

8. Correlation Analysis :
A correlation heatmap was created for numerical variables to understand relationships between features.
The analysis focuses particularly on relationships involving:
    * price
    * duration
    * days_left
Correlation values range from **-1 to +1**:
    * +1 → Strong positive relationship
    * 0 → Little or no linear relationship
    * -1 → Strong negative relationship

📊 Visualizations

The project includes several types of visualizations:

  * 📊 Bar Chart
  * 📊 Grouped Bar Chart
  * 📊 Count Plot
  * 🥧 Pie Chart
  * 📦 Box Plot
  * 📈 KDE Plot
  * 📉 Histogram
  * 🔥 Correlation Heatmap

These visualizations are used to identify patterns, distributions, relationships, and unusual observations in the dataset.

🧠 Key Questions Explored

The analysis attempts to answer questions such as:
  1. Which airline has the highest number of flights?
  2. Which airline has the lowest number of flights?
  3. Which cities have the highest number of flights?
  4. How do source and destination flight counts differ by city?
  5. Which airline has the highest average ticket price?
  6. Which airline has the lowest average ticket price?
  7. How does flight duration vary between airlines?
  8. Which airlines have greater variation in flight duration?
  9. Are there significant outliers in flight duration?
  10. How does travel class affect ticket price?
  11. How do stops affect ticket price?
  12. Is there a relationship between flight duration and ticket price?
  13. Which numerical features have the strongest relationship with price?
  

📈 EDA Workflow

`
                    Dataset
                       ↓
                Data Loading
                       ↓
              Data Understanding
                       ↓
                 Data Cleaning
                       ↓
            Missing Value Analysis
                       ↓
          Categorical Data Analysis
                       ↓
           Numerical Data Analysis
                       ↓
           Exploratory Visualization
                       ↓
              Outlier Analysis
                       ↓
             Correlation Analysis
                       ↓
                Key Insights

📁 Project Structure

  Flight-Price-EDA-project/
  │
  ├── airline.ipynb
  ├── airlines_flights_data.csv
  ├── image.png
  ├── Screenshot 2026-08-05 145035.png
  └── readme.md

Main Files
  airline.ipynb
    Contains the complete Python-based exploratory data analysis, including data exploration, calculations, visualizations, and observations.
  
  airlines_flights_data.csv
    Contains the flight dataset used for the analysis.

🚀 How to Run the Project

  1. Clone the repository
    git clone https://github.com/siddesai2405/Flight-Price-EDA-project.git
  
  2. Navigate to the project
    cd Flight-Price-EDA-project
  
  3. Install the required libraries
    pip install pandas numpy matplotlib seaborn jupyter
  
  4. Start Jupyter Notebook
    jupyter notebook
  
  5. Open the notebook
    Open:
    text
    airline.ipynb
    Run the cells sequentially to reproduce the analysis.

💡 Learning Outcomes
Through this project, I practiced :
* Working with real-world datasets
* Pandas DataFrame operations
* Data cleaning and exploration
    * value_counts()
    * nunique()
    * groupby()
    * sort_values()
    * reset_index()
    * concat()
* Data filtering
* Statistical analysis
* Outlier detection
* Correlation analysis
* Data visualization with Matplotlib
* Data visualization with Seaborn
* Creating professional EDA visualizations
* Using Git and GitHub for version control

---

## 🔮 Future Improvements

The project can be extended by:

* Building an interactive dashboard using Power BI or Streamlit
* Performing deeper statistical analysis
* Applying feature engineering
* Building a flight price prediction model
* Comparing different machine learning algorithms
* Performing hyperparameter tuning
* Deploying the prediction model as a web application

👨‍💻 Author
Siddhesh Desai
B.Tech Student | Python | Data Analysis | Machine Learning

🔗 Repository :-
[View the Flight Price EDA Project on GitHub](https://github.com/siddesai2405/Flight-Price-EDA-project)

⭐ If You Like This Project >>
If you found this project useful or interesting, consider giving the repository a ⭐ on GitHub.
