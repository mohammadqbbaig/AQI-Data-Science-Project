48. Project Title
Global Urban Air Quality Index Analysis (2015–2025)
49. Student Name
Mohammad Qayyum Baig

50. Registration Number
2280219

51. Dataset Name
Global Urban Air Quality Index Dataset (2015–2025)

This dataset contains simulated but realistic air quality measurements collected weekly from 2015 to 2025 across 30 major global cities in 26 countries. It includes pollutant concentrations, weather factors, and calculated AQI values.

Total records before cleaning: 14,184
Total records after cleaning: 13,993

52. Problem Statement
Air pollution remains a major environmental and public health concern worldwide. The Air Quality Index (AQI) provides a standardized way to measure air pollution levels and assess health risks.

This project analyzes global urban air quality data from 2015 to 2025 to:

Understand trends in AQI across countries and years
Identify the most influential pollutants affecting air quality
Classify AQI categories using supervised machine learning (KNN and Naive Bayes)
Discover meaningful pollution patterns using unsupervised learning (K-Means and PCA)
The main goal is to determine whether basic data science methods can effectively classify and interpret global air pollution patterns.

53. Tools and Libraries Used
This project was implemented using:

Python
Pandas (data manipulation)
NumPy (numerical computations)
Matplotlib (data visualization)
Seaborn (statistical visualization)
Scikit-learn (machine learning models)
Jupyter Notebook (Google Colab)

54. How to Run the Notebook
To reproduce the results:

Open the file:
text

AQI_Data_Science_Project.ipynb
Ensure the dataset file:
text

global_urban_aqi_dataset.csv
is located in the same repository directory.
Run all notebook cells sequentially from top to bottom.
The notebook will:
Generate all required visualizations
Perform supervised learning (KNN and Naive Bayes)
Perform unsupervised learning (K-Means and PCA)
Save result files (CSV and PNG) in the repository
The notebook runs successfully without errors when executed using Restart & Run All in Google Colab or Jupyter Notebook.

✅ 55. Summary of Main Findings (Correct & Humanized)
Based on the analysis of 13,993 cleaned records, the following conclusions were drawn:

✅ The global average AQI is 120.88, which falls under the category Unhealthy for Sensitive Groups.
✅ Lahore, Pakistan recorded the highest AQI in the dataset.
✅ Cape Town, South Africa recorded the lowest AQI.
✅ PM2.5 is the strongest predictor of AQI, showing a very high correlation (≈ 0.90).
✅ KNN achieved a best accuracy of 74.35% with k = 7.
✅ Naive Bayes achieved a higher accuracy of 75.63%.
✅ Naive Bayes outperformed KNN by 1.29%.
✅ K-Means clustering successfully identified three pollution groups:
Low pollution
Medium pollution
High pollution
✅ PCA reduced dimensionality and helped clearly visualize pollution clusters in two dimensions.
Overall, both supervised and unsupervised learning techniques were effective in analyzing and interpreting global air quality patterns.

✅ 56. Screenshots of Important Charts
All visualizations are saved directly in the repository.

Key visualizations include:

text

01_aqi_category_distribution.png
02_aqi_by_country.png
03_aqi_trend_year.png
04_pm25_vs_aqi.png
05_correlation_heatmap.png
06_knn_confusion_matrix.png
07_nb_confusion_matrix.png
08_pca_visualization.png
These charts demonstrate:

Distribution of AQI categories
Country-wise pollution comparison
AQI trend over years
Relationship between PM2.5 and AQI
Correlation between pollutants
Model performance through confusion matrices
Cluster visualization using PCA
57. Report File Location
The full written report is available in the repository as:


AQI_Data_Science_Project.pdf
(Ensure the file name matches exactly what appears in your GitHub screenshot.)

text
