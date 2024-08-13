# Exploratory Data Analysis Project
 This project, undertaken as the first assignment for the Data Science & AI course with the Institute of Data and Auckland University of Technology, focuses on analysing the intrinsic properties of stars within the Milky Way using data sourced from the AT-HYG database. The goal was to translate a broad astronomical problem into a data science problem by selecting and processing a relevant dataset.  The analysis began by identifying and excluding 60,745 entries with missing positional and distance data, resulting in a final sample of 2,491,418 stars. Key features such as absolute magnitude, luminosity, mass, radius, and temperature were engineered from the dataset. Initial descriptive statistics suggested potential skewness in the data, which was further examined using the Shapiro-Wilk test along with measures of skewness and kurtosis. Despite Box-Cox transformations aimed at normalising the data, non-normal distributions persisted across all variables.  Visual inspections through histograms, Q-Q plots, and box plots corroborated these findings. Additionally, a bar chart of spectral class frequencies indicated a distribution aligned with known astronomical patterns, supporting the dataset’s representativeness. Correlation analysis uncovered significant relationships among intrinsic stellar properties, highlighting potential avenues for further research.  The spatial distribution of these properties across the Milky Way was also explored, providing insights into their variability within the galaxy.  Overall, this exploratory data analysis offers a robust foundation for understanding the distribution and interrelationships of stellar properties, setting the stage for future research into stellar dynamics and galactic structure. The assignment demonstrated the application of data wrangling, feature engineering, and exploratory data analysis techniques acquired throughout the course.
