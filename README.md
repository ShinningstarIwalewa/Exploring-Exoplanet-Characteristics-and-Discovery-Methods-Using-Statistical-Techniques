# Exploring Exoplanet Characteristics and Discovery Methods Using Statistical Techniques

### Aim
The aim of this project is to explore the characteristics and discovery methods of exoplanets using a dataset of exoplanets. This involves data cleaning, statistical analysis, visualization, clustering, and machine learning techniques to gain insights into the exoplanets' properties and their discovery methods.

### Project Structure

1) Data Import and Preparation: Import the dataset exo data.csv and convert columns to appropriate data types.
2) Data Cleaning: Exclude exoplanets with unknown discovery methods.
3) Statistical Analysis and Visualization:Create and analyze graphics illustrating relationships between exoplanet properties and discovery methods.
4) Data Transformation and Feature Engineering: Rename columns and create new feature columns to facilitate analysis.
5) Cluster Analysis: Perform clustering on selected features and visualize the clusters.
6) Coordinate Transformation: Transform celestial coordinates for mapping purposes.
7) Interactive Visualization with Shiny: Develop an interactive Shiny app for exploring exoplanet data.
8) Machine Learning - Gaussian Process Regression: Implement and apply a Gaussian process regression model to predict exoplanet characteristics.

### Findings
1) Relationship Between Log-Distances and Methods of Discovery:
   - Transit Method: Distribution is positively skewed with a mean log-distance of approximately 6.2, slightly less than the median of 6.4, indicating a right tail.
   - Radial Velocity (RV) Method: Slightly positively skewed, with the mean slightly less than the median. The distribution is spread and has outliers on both ends.
   - Microlensing: Appears approximately symmetric, with the mean close to the median, suggesting centered data.
   - Imaging: Positively skewed with the mean higher than the median and no outliers.
   - Timing: Approximately symmetric and not heavily skewed, with no significant spread or outliers.
     
2) Clustering Analysis:Four clusters were identified: 'rocky', 'hot jupiters', 'cold gas giants', and 'others'. These clusters help categorize exoplanets based on their log-earth radius and log-period.
3) Violin Plot Analysis:The clusters ('cold gas giants', 'hot jupiters', and 'rocky') show a well-spread distribution of data points in terms of log-mass.
4) Celestial Map:Exoplanets were mapped using transformed right ascension and declination coordinates.
5) Interactive Visualization:
6) The Shiny app allows users to interactively explore exoplanet data based on discovery year and type, providing a dynamic tool for data analysis.
7) Gaussian Process Regression:The Gaussian process regression fairly predicted the log-mass variable using log-radius as the covariate. 

### Conclusion
This project successfully utilized a combination of data cleaning, statistical analysis, visualization, clustering, and machine learning to explore the properties and discovery methods of exoplanets. The findings provide valuable insights into the distribution and characteristics of exoplanets, as well as the effectiveness of different discovery methods. The interactive Shiny app and the Gaussian process regression model further enhance the analytical capabilities, making this project a comprehensive tool for exoplanet data analysis.
