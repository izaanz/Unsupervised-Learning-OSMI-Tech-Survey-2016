
# Mental Health in Tech - Clustering Analysis

## Introduction  
Mental health is a significant concern in the workplace, especially in the technology sector, where stress and burnout are prevalent. Ensuring employees' mental well-being not only enhances productivity but also fosters a healthier work environment. This project analyzes the OSMI mental health survey dataset, which includes over 1,400 responses, to identify patterns and trends in mental health attitudes and prevalence within the tech industry. Using unsupervised machine learning techniques, the study aims to cluster participants based on their survey responses, enabling organizations to design targeted mental health programs for their employees.

## Objectives  
1. **Understand the dataset**: Gain insights into survey responses and their implications.
2. **Preprocess the data**: Handle challenges like missing values, high dimensionality, and unstructured inputs.
3. **Cluster participants**: Use unsupervised learning techniques to reveal patterns and group individuals meaningfully.
4. **Extract actionable insights**: Help organizations create targeted mental health improvement programs.

## Dataset  
- **Source**: [OSMI Mental Health in Tech Survey (2016)](https://www.kaggle.com/datasets/osmi/mental-health-in-tech-2016)  
- **Description**: Contains survey responses about mental health attitudes, workplace mental health support, and individual experiences with mental health disorders.

## Methodology  
To prepare and analyze the dataset, the following steps were undertaken: 
1. **Data Understanding**: Explore the dataset structure, key columns, and target attributes for clustering. 
2. **Data Cleaning**: Handle outliers in numerical columns. Impute missing values using advanced techniques like `KNNImputer`. 
3. **Feature Engineering**: Encode categorical columns using manual and automatic techniques like `LabelEncoder`. 
4. **Scaling and Dimensionality Reduction**: Standardize numerical columns for consistent scaling. Apply `PCA` to reduce dimensionality while preserving 80% variance. 
5. **Clustering**: Use `KMeans` clustering to group participants based on their survey responses. Determine the optimal number of clusters using methods like the elbow method, silhouette score, and Davies-Bouldin index. 
6. **Insights and Visualization**: Interpret the clusters and visualize the results to derive meaningful insights.

## Requirements  
Install the following Python libraries before running the code:  
```python
pandas
numpy
seaborn
matplotlib
lightgbm
scikit-learn
```

## Results
Cluster Analysis: The survey participants were grouped into meaningful clusters, revealing varying mental health profiles and workplace attitudes.
Key Insights: Organizations can use these insights to implement targeted mental health support programs, address stigma, and foster healthier work environments.
## Clone this repository:
```bash
git clone https://github.com/your-username/mental-health-clustering.git
```
Install the required libraries:
```bash
pip install -r requirements.txt
```
## Contributing
Contributions are welcome! Feel free to open issues or submit pull requests to enhance the project.


