# Customer Segmentation Project

This project focuses on customer segmentation using unsupervised machine learning algorithms. The goal is to group customers based on their purchasing behavior and other features, which can help businesses tailor marketing strategies and improve customer experiences. The project uses **K-Means** and **Agglomerative Clustering** methods for segmentation.

## Table of Contents

- [Project Description](#project-description)
- [Technologies Used](#technologies-used)
- [Setup and Installation](#setup-and-installation)
- [Usage](#usage)
- [Data Description](#data-description)
- [Algorithms Used](#algorithms-used)
- [Results](#results)
- [Contributors](#contributors)

## Project Description

Customer segmentation is an important process for businesses to understand their customer base. By grouping customers with similar behavior and characteristics, businesses can create targeted campaigns, optimize their product offerings, and improve customer satisfaction. In this project, **K-Means** and **Agglomerative Clustering** are used to segment customers into distinct groups based on their purchasing behavior.

### Key Steps:
1. **Data Preprocessing**: Handle missing values, scale numerical features, and encode categorical variables.
2. **Clustering**: Apply K-Means and Agglomerative Clustering algorithms to segment customers.
3. **Visualization**: Visualize the clusters using 2D plots and interpret the results.

## Technologies Used

- **Python**: The primary language for implementing the machine learning models.
- **Libraries**:
  - `pandas` for data manipulation.
  - `numpy` for numerical operations.
  - `matplotlib` / `seaborn` for data visualization.
  - `scikit-learn` and `scipy` for machine learning algorithms (K-Means and Agglomerative Clustering).

## Setup and Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/wajahath-ali/customer_segmentation.git
   cd customer_segmentation
   ```
2. **Install the required libraries**: 
   ```bash
   pip install -r requirements.txt
   ```
## Usage

   The project is contained in a single Jupyter Notebook file **(customer_segmentation.ipynb)**. This file includes all the steps
   from data preprocessing to clustering and evaluation.
1. **To run the notebook:**
  Install Jupyter Notebook if you don't have it:
   ```bash
   pip install notebook
   ```
2. **Start the notebook server:**
    ```bash
   jupyter notebook
   ```
3. Open **customer_segmentation.ipynb** in the browser and follow the instructions in the notebook to run the project.


## Data Description

   The dataset used in this project consists of customer-related features, such as:
 **Demographic Data** 
 **Purchase History**
 **Behavioral Data**
  The dataset is loaded from a CSV file, which is  in the same directory as the notebook.

## Algorithms Used

 **K-Means Clustering:

   A centroid-based algorithm that assigns customers to a predefined number of clusters based on their feature similarities.

 **Agglomerative Clustering:

   A hierarchical clustering method that builds a tree-like structure (dendrogram) to represent the nested grouping of customers.

**Both algorithms are applied and compared in the notebook to evaluate the best clustering approach.**

## Results

  The results of the customer segmentation are visualized in the notebook using 3D scatter plots. The clusters from K-Means and Agglomerative Clustering are compared based on:

**Cluster Visualization:** Visualizes the clusters to understand patterns and insights.

  The clustering results are available directly in the **customer_segmentation.ipynb** notebook.

## Contributors

**Wajahath Ali**

Feel free to fork the repository, open issues, or submit pull requests for improvements.

## License

  This project is licensed under the **MIT License** 
