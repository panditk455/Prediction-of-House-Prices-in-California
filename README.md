
## Predicting House Prices in California

### Overview
This project focuses on predicting house prices in California using machine learning techniques. The associated Shiny app, "Predicting the Prices of the House in the California Area using Machine Learning," offers insights and tools for exploring housing data in California. The dataset used was sourced from Kaggle, containing various numeric variables such as longitude, latitude, housingMedianAge, totalRooms, totalBedrooms, population, households, medianIncome, medianHouseValue, and oceanProximity.

### Features of the Shiny App
The Shiny app provides a user-friendly interface with three main tabs:

1. **Description Tab**: Offers an overview of the dataset and instructions on how to use the app.
   
2. **Exploratory Data Analysis (EDA) Tab**: Allows users to visualize the dataset through:
   - Correlation matrix to understand relationships between variables.
   - Cluster analysis based on mean values of multiple variables across California counties.

3. **Predictive Modeling Tab**: Focuses on machine learning with options for:
   - Decision Tree modeling.
   - Variable Importance analysis to determine influential features.
   
   The app allows users to select models and visualize outputs interactively. The predictive modeling process includes data splitting, preprocessing using recipes, model specification, tuning via cross-validation, and visualization of decision trees using "rpart.plot". Conditional panels ensure that outputs are displayed based on user selections, enhancing user experience.

### Technical Details
- **Libraries Used**: dplyr, tidyverse, janitor, ggplot2, plotly, tidymodels, caret, randomForest, shiny, shinydashboard, shinythemes.
- **Data Preprocessing**: Includes data loading, categorical variable conversion, and spatial joins using the Tigris package.
- **Visualization**: Utilizes ggplot2 and plotly for interactive and static visualizations.
- **Customization**: Custom CSS and HTML were used for layout adjustments and text alignment within the app.

### Repository Structure
- `main.Rmd`: Contains all necessary code for library imports, data processing, UI & server logic, EDA, and predictive modeling.
- `img/`: Folder containing images used within the app.
- `finalApp/`: Folder for deploying the Shiny app.
- `housing.csv`: Original dataset sourced from Kaggle.
- `Report.pdf`: Technical report providing additional insights and details about the project.

### Usage
To explore the Shiny app and its functionalities, visit [Predicting House Prices in California](https://palmy.shinyapps.io/finalApp/).

### Conclusion
This project integrates data preprocessing, exploratory data analysis, and machine learning into an interactive web application. It serves as a valuable resource for understanding the factors influencing housing prices in California and can be adapted for similar analyses in different geographical locations.


