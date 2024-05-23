# Clustering

This project is part of the Applied Machine Learning course at NYU Abu Dhabi. The project focuses on implementing k-means clustering and hierarchical clustering algorithms. The main goal is to classify data into clusters and demonstrate clustering on synthetic data and an image for k-means, and on a customer dataset for hierarchical clustering.

## Project Overview

The project consists of two main parts:
1. K-means Clustering
2. Hierarchical Clustering

## Project Structure

- **Data**: Directory containing the dataset files.
- **Notebooks**: Jupyter notebooks for data exploration, clustering implementation, and visualization.
- **README.md**: Project documentation.

## Getting Started

### Prerequisites

Ensure you have the following Python libraries installed:
- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn
- scipy

You can install these libraries using pip:

```sh
pip install numpy pandas matplotlib seaborn scikit-learn scipy
```

## Dataset
- Synthetic Data: Generated using the make_blobs function from sklearn.
- Image Data: An RGB image used for clustering RGB values.
- Mall Customer Data: The Mall Customer dataset (Mall_Customers.csv).

## Running the Project

Clone the repository:

```
git clone https://github.com/your-username/aml-mini-project.git
cd aml-mini-project
```

Navigate to the notebooks directory and open the Jupyter notebook AML_mini_project_4.ipynb to explore the data, implement the clustering algorithms, and visualize the results.

## Project Details
### K-Means Clustering
Introduction
K-means is a widely used unsupervised learning algorithm for clustering. It classifies a dataset into a predefined number of clusters by defining cluster centers and assigning data points to the nearest cluster.

## Dataset
### Synthetic Data: 
Generated using the make_blobs function from sklearn with 300 instances, 4 centers, and a standard deviation of 0.6.
### Image Data: 
An RGB image used for clustering RGB values into K clusters to demonstrate image compression.
### Mall Customer dataset (Mall_Customers.csv): 
For clustering customer data.

## Project Includes
Comparison of results from different seeds and initializations including standard k-means and k++

## Hierarchical Clustering
Hierarchical clustering creates clusters in a predetermined hierarchical order. It is useful for organizing data in nested clusters.


## Requirements
Implement a hierarchical clustering model using Ward distance.
Plot the dendrogram to visualize the hierarchical clustering.

## Evaluation and Visualization
The project includes:
Plotting the generated synthetic data.
Visualizing the clustered image before and after compression.
Plotting dendrograms for hierarchical clustering.
Comparing different clustering results and discussing observations.

## Contributing
If you would like to contribute to this project, please fork the repository and submit a pull request.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.

## Acknowledgements
This project is part of the Applied Machine Learning course at NYU Abu Dhabi.
The dataset for hierarchical clustering is sourced from Mall Customers Dataset.
