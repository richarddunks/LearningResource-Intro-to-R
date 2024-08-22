# Introduction to R for Crime Analysts

Welcome to the "Introduction to R for Crime Analysts" book! This resource is designed specifically for crime analysts who are transitioning from SPSS to R. The book is published as a Bookdown project on GitHub and provides a comprehensive guide to getting started with R, including practical examples and tips tailored to crime analysis.

## Table of Contents

1. **Introduction**
   - Overview
   - Why Learn R?
   - Replicating SPSS Functionality in R
   - Transitioning from SPSS to R
   - Conclusion

2. **Getting Started with R**
   - The R Environment
   - Introduction to R Packages and Installing Key Packages
   - Coding Conventions and Best Practices
   - Data Types and Structures
   - Basic Operations and Functions in R
   - Conclusion

3. **Data Management in R**
   - Data Import and Export
   - Data Cleaning and Preparation
   - Working with Categorical Data
   - Conclusion

4. **Connecting to and Accessing a PostgreSQL Database**
   - Introduction
   - Setting Up the Environment
   - Connecting to PostgreSQL (Using RPostgres)
   - Querying Data from PostgreSQL
   - Handling Errors and Troubleshooting
   - Conclusion

5. **Descriptive Statistics and Visualisations**
   - Introduction to Descriptive Statistics
   - Creating Visualisations with ggplot2
   - Descriptive Statistics with dplyr
   - Advanced Visualisation Techniques
   - Conclusion

6. **Survey Analysis in R**
   - Introduction to Survey Data
   - Importing and Preparing Survey Data
   - Descriptive Analysis of Survey Data
   - Weighting Survey Data
   - Conclusion

7. **Inferential Statistics**
   - Hypothesis Testing
   - Correlation Analysis
   - Conclusion
  
8. **Regression Analysis**
   - Introduction to Regression Analysis
   - Simple Linear Regression in R
   - Multiple Linear Regression
   - Checking Model Assumptions
   - Transformations and Interaction Terms
   - Logistic Regression
   - Checking Model Assumptions for Logistic Regression
   - Model Validation and Diagnostics
   - Conclusion

8. **Regression Analysis**
   - Introduction to Regression Analysis
   - Simple Linear Regression in R
   - Multiple Linear Regression
   - Checking Model Assumptions
   - Transformations and Interaction Terms
   - Logistic Regression
   - Checking Model Assumptions for Logistic Regression
   - Model Validation and Diagnostics
   - Conclusion
  
9. **Geographic Mapping and Spatial Analysis**
   - Introduction to Geographic Data in R
   - Geographic Coordinate Systems and Projections
   - Creating Basic Maps
   - Spatial Analysis
   - Conclusion
    
## How to Access

You can access the full book online via the following link: [Introduction to R for Crime Analysts](https://mopac-ds.github.io/LearningResource-Intro-to-R/)

## Installation

To view the book locally, you will need to clone this repository and render the Bookdown project. Follow these steps:

1. **Clone the Repository**

   ```bash
   git clone [https://github.com/MOPAC-DS/LearningResource-Intro-to-R.git](https://github.com/MOPAC-DS/LearningResource-Intro-to-R)
   ```
   
2. **Install Required Packages**

Make sure you have R and the necessary packages installed. You can install them using:

   ```r
install.packages(c("bookdown", "tidyverse", "ggplot2"))
   ```

3. **Render the Book**

Open R or RStudio and set your working directory to the cloned repository. Then run:

   ```r
bookdown::render_book("index.Rmd")
   ```

This will generate the book in various formats (HTML, PDF, etc.).

## Contributing
Contributions are welcome! If you have suggestions for improvements or spot any issues, please open an issue or submit a pull request.

## Contact
For questions or feedback, please contact Daniel Hammocks via email daniel.hammocks@mopac.london.gov.uk.

## License
This book is licensed under the MIT License.

