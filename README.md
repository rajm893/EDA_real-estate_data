# Data Cleaning and EDA on Real-estate data

In this project, a detailed exploratory data analysis and cleaning process was conducted on a real estate dataset, aimed at preparing it for advanced analytical modeling. The dataset, comprising key variables such as 'MLS', 'sold_price', and 'sqrt_ft', along with extensive property features, was meticulously processed to ensure data integrity and utility for predictive modeling.

- Employed Python and Pandas library for efficient DataFrame construction and data manipulation.
- Addressed missing values in 'lot_acres', 'fireplaces', and 'sqrt_ft' using median values and zeros for strategic imputation.
- Transformed non-numeric entries in columns like 'sqrt_ft', 'HOA', 'bathrooms', and 'garage' into numeric formats, ensuring data consistency.
- Leveraged feature engineering techniques to introduce 'years_since_built', providing insights into the age of properties.
- Utilized Word2Vec modeling and KMeans clustering for enhancing 'kitchen_features', categorizing complex attributes into interpretable clusters.
- Applied similar Word2Vec and clustering techniques to transform 'floor_covering' features, effectively summarizing diverse flooring types.
- Conducted histograms and box plots for visual analysis of data distribution and outlier identification, alongside creating a correlation matrix to understand relationships between key variables.
