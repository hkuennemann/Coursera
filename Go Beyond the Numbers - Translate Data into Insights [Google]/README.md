# Go Beyond the Numbers: Translate Data into Insights [Google]
Description: In this course, I learned how to uncover stories within data and present them compellingly. Guided by Google professionals, I practiced exploratory data analysis, created effective visualizations, and applied real-world data storytelling techniques. I used Python to examine, clean, and transform data, validated datasets, and made decisions about missing data and outliers. Additionally, I learned to create accessible visualizations with Tableau and manipulate date strings for better data organization. Completing this program equipped me with the skills needed for advanced data analytics and data science roles.<br/>

**Skills gained in this course**: `Python Programming`, `Effective Communication`, `Tableau Software`, `Data Visualization`, `Exploratory Data Analysis (EDA)`.

## Course Content and Notebooks

### Module 1 - Find and share stroies using data
Description: I learned how to find stories within data and share them with my audience. I explored the methods and benefits of data cleaning, understanding how it helps uncover those stories. I also went through the steps of the EDA process, gaining insight into how EDA can quickly reveal patterns in data. Finally, I explored various ways to visualize data to effectively communicate key insights.</br>
Submodules:
- Use PACE and inform EDA and data visualizations
- Find and share stories using data


### Module 2 - Explore raw data
Description: In this module, I focused on organizing and interpreting raw data to uncover stories using Exploratory Data Analysis (EDA). I learned how to leverage Python to efficiently perform EDA practices, including discovering patterns and refining data to reveal meaningful insights.</br>
Submodules:
- "Discovering" is the beginning of an investigation
- Understand the data format
- Create structure from raw data
- Explore raw data

#### Notebooks
2.1.EDA using basic data functions with Python
- Description: In this notebook, I performed an Exploratory Data Analysis (EDA) on the <<eda_using_basic_data_functions_in_python_dataset1.csv>> file, derived from the BigQuery public dataset <<noaa_lightning.lightning_strikes>>. The dataset contains aggregated cloud-to-ground lightning strike data from Vaisala's National Lightning Detection Network (NLDN), organized into 0.1° latitude by 0.1° longitude tiles, with each tile's strikes summed and assigned to central geographic coordinates.<br/>
- Main Topics:
  - EDA on lightning strike data
  - Data aggregation and interpretation
  - Geographic data analysis
  - Python data functions


2.2.EDA_unicornCompanies-1
- Description: This notebook was about exploring a dataset of unicorn companies to gain insights into their characteristics and valuations. I performed an Exploratory Data Analysis (EDA) using Python to discover trends and patterns within the data. I visualized key metrics such as the time it took companies to reach unicorn status and the maximum valuation of companies by industry.<br/>
- Main Topics:
  - Data exploration and analysis
  - Dataset characteristics and structure
  - Data visualization using Python


2.3.Date string manipulations with Python
- Description: This notebook was focused on practicing date string manipulations in Python. I worked with a dataset of lightning strikes from 2016 to 2018, converting date strings to datetime objects, and creating new time-related columns. I then used this data to calculate and visualize weekly and quarterly lightning strike totals. The process involved formatting dates, creating bar graphs, and adding labels to visualize trends in lightning strike data over time.<br/>
- Main Topics:
  - Date string conversion
  - Time column creation
  - Data grouping and summarization
  - Data formatting and labeling
  - Data visualization


2.4.EDA structuring with Python
- Description: In this notebook, I practiced structuring and analyzing lightning strike data in Python, focusing on data from the National Oceanic and Atmospheric Association (NOAA) for 2018. The notebook guided me through various data manipulation techniques, including sorting, grouping, and calculating percentages, and culminated in visualizing data patterns over time.<br/>
- Main Topics
  - Datetime Conversion
  - Duplicate Check
  - Data Sorting
  - Grouping & Aggregation
  - Plotting & Visualization
  - Data Concatenation


2.5.EDA_unicornCompanies-2
- Desription: This notebook detailed an exploratory data analysis (EDA) activity focused on structuring and analyzing a dataset of unicorn companies — those valued at over one billion dollars. The objective was to gain insights into the dataset by performing various datetime transformations, structuring the data, and using visualizations. I worked with Python libraries such as `pandas`, `numpy`, `seaborn`, and `matplotlib.pyplot` to import, explore, and visualize the data, ultimately uncovering trends and patterns related to the unicorn companies' founding years and valuation over time.<br/>
- Main Topics
  - Data Exploration**
  - Sorting
  - Datetime Conversion
  - Trend Analysis
  - Visualization
  - Results and Evaluation


### Module 3 - Clean your data
Description: In this module, I explored three additional EDA practices: cleaning, joining, and validating. I learned about the importance of these practices for data analysis and used Python to clean, validate, and join data.</br>
Submodules:
- The challenge of missing or duplicate data
- The ins and outs of outliers
- Change categorical to numerical data
- Input validation
- Clean your data

#### Notebooks
3.1.Dealing with missing data in Python
- Description: In this notebook, I analyzed and processed lightning strike data provided by the National Oceanic and Atmospheric Association (NOAA). The main focus was to handle missing data, identify and address outliers, and perform label encoding on the dataset. The data covered different time periods and locations, requiring merging datasets, visualizing missing data, and encoding categorical variables for better analysis. I also demonstrated how to create meaningful visualizations, such as scatter plots and boxplots, to interpret the data effectively.<br/>
- Main Topics
  - Data Merging
  - Missing Data Analysis
  - Outlier Detection
  - Data Visualization
  - Label Encoding
  - Data Cleaning
  - Categorical Data Handling


3.2.Address missing data
- Description: In this notebook, I addressed missing data and performed exploratory data analysis (EDA) on a dataset of unicorn companies. I acted as a financial data consultant to identify potential business opportunities for an investor. The analysis involved cleaning the data, handling missing values, and filtering specific company information to meet the investor's requirements. I also generated visualizations to present the findings effectively<br/>
- Main Topics:
  - Data Exploration
  - Data Cleaning
  - Handling Missing Values
  - Data Filtering
  - Data Visualization


3.3.Validate and clean your data.ipynb
- Description: In this notebook, I focused on validating and cleaning a dataset containing information about unicorn companies. My task involved several steps to prepare the data for analysis, including handling incorrect data types, correcting data entry errors, dealing with duplicates, and converting categorical data into numerical form.<br/>
Main Topics: 
  - Data Type Conversion
  - Data Cleaning
  - Input Validation
  - Handling Duplicates
  - Categorical to Numerical Conversion


### Module 4 - Data Visualizations and Presentations
Description: I practiced creating and presenting data stories in an ethical, accessible, and professional way. I also explored advanced data visualization techniques in Tableau.</br>
Submodules:
- Present a story
- Advanced Tableau

#### Tableau Workbooks
Lightning_Strikes_US2018
- Introduction to Tableau


Seoul Avg bike rentals 2018 
- Introduction to Tableau


Craft_compeling_stories
- Description: This task was about creating a data visualization story using Tableau Public. It involved building various visualizations and dashboards that depicted the trend of lightning strikes in the U.S. from 2009 to 2018. I learned Tableau functionalities such as creating worksheets, filtering data, annotating, and designing dashboards, culminating in the construction of a compelling narrative through data visualization.<br/>
- Main Topics:
  - Data Filtering
  - Annotation
  - Data Visualization Types (Line Graph, Map)
  - Geographic Data Configuration
  - Dashboard Design
  - Storytelling with Data
  - Data Filtering and Setting
  - Color-Coding and Styling


Present like a pro
- Description: This task was about creating an interactive geographic dashboard using Tableau Public to present data on lightning strikes in the U.S. from 2009 to 2018. It involved building multiple worksheets, calculating metrics, and designing an interactive dashboard that allows users to filter and explore data dynamically. I used Tableau's functionalities like creating calculated fields, setting up geographic roles, and configuring dashboard actions to enhance the data presentation.<br/>
- Main Topics:
  - Data visualization
  - Tableau worksheets
  - Geographic roles
  - Calculated fields
  - Dashboard actions
  - Interactive filtering
  - Data storytelling


### Module 5 - 
Descripton: In this end-of-course project, I practiced using Python to perform EDA on a workplace scenario dataset. Then, I used Python and Tableau to visualize the data.<br/>

#### Notebooks
5.1.Automatidata_project:
- Description: This notebook focuses on Exploratory Data Analysis (EDA) and data visualization using Python. As a data professional at the fictional consulting firm Automatidata, I was tasked with analyzing New York City Taxi and Limousine Commission (TLC) data to understand taxi ridership patterns. The goal was to perform data cleaning, outlier analysis, and create visualizations that help convey insights about taxi trips in New York City.<br/>
- Main Topics:
  - Data Cleaning
  - Exploratory Data Analysis (EDA)
  - Outlier Detection
  - Data Visualization with Python (Matplotlib/Seaborn)
  - Reporting and Insights Communication


5.2.TikTok_project:
- Description: This notebook is about conducting Exploratory Data Analysis (EDA) on a TikTok dataset. It guided me through data cleaning, visualization, and identifying key insights to inform data-driven decisions. The analysis included creating visualizations using Python (matplotlib and seaborn) to explore variables such as video views, likes, shares, and author ban status.<br/>
- Main Topics:
  - Data Cleaning
  - Data Exploration
  - Data Visualization
  - Outlier Detection
  - Insights and Summary


5.3.Waze_project:
- Description: This notebook focused on conducting an exploratory data analysis (EDA) on a dataset from Waze. The goal was to investigate user behavior patterns and visualize key metrics to understand user churn, which will aid in making data-driven decisions. The notebook includes steps for data cleaning, analysis, visualization, and summarizing insights.<br/>
- Main Topic:
  - Data Cleaning
  - Missing Data Analysis
  - Outlier Detection
  - Statistical Summary
  - Data Visualization
  - User Behavior Analysis
  - Churn Analysis
  - Visualization Interpretation
  - Insights Communication


## Disclaimer
This project notebook is part of the coursework for "Go Beyond the Numbers: Translate Data into Insights" on Coursera (🔗 [Go to course](https://www.coursera.org/learn/go-beyond-the-numbers-translate-data-into-insight)). It is intended for educational purposes only. For official content and certification, please refer to the Coursera course page.
