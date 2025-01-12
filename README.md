README: Analyzing Radiation Intensity in Communication Sites 

## Project Overview  
This project analyzes radiation intensity from communication sites in Israel, utilizing supervised classification and unsupervised clustering techniques to extract insights about site types and radiation patterns.  

## Features of the Dataset  
The dataset includes over 8,000 entries with key features such as:  
- **Geographic Data**: City, coordinates (X_ITM, Y_ITM).  
- **Technical Parameters**: Maximum theoretical radiation intensity, related intensity (%).  
- **Site Types**: Different categories of communication sites (e.g., roof antennas, ground towers).  

## Objectives  
1. Predict site categories based on radiation and geographic factors.  
2. Cluster communication sites to uncover patterns or anomalies, such as high-radiation areas.  

## Methodology  
### Supervised Learning  
- Preprocessing: StandardScaler and OneHotEncoder for feature engineering.  
- Models: Decision Tree, Random Forest, Logistic Regression, SVM, KNN.  
- Evaluation: Metrics like precision, recall, and F1-score were used to assess model performance.  

### Unsupervised Learning  
- Algorithms: K-Means and DBSCAN for clustering.  
- Analysis: Radiation intensity distribution by geographic coordinates and identification of high-radiation cities.  

## Results  
- **Best Model**: Random Forest achieved the highest accuracy with 69%.  
- **Clustering Insights**: K-Means identified notable clusters, and DBSCAN highlighted potential anomalies.  

## Conclusion  
This project demonstrates the ability to classify communication site types and uncover insights into radiation patterns, which can inform public safety and infrastructure planning.  

## How to Run the Project  
1.Before running the notebook, ensure that the dataset file (Data ML2.csv) is accessible on your computer.
Open the Jupyter Notebook file (project_notebook.ipynb) and locate the cell where the dataset is loaded, Replace 'C:\\Users\\EyalK\\Desktop\\ML2\\Data ML2.csv' with the actual path of the dataset on your computer .


Acknowledgments

Special thanks to Dr. Chen Hagag for guidance throughout the course on Advanced Topics in Machine Learning.
