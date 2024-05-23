# PRODIGY_ML_02
# Customer Segmentation using K-means Clustering

## Project Overview

This project is the second task of my machine learning internship, where I implemented a K-means clustering algorithm to group customers of a retail store based on their purchase history. The goal is to identify distinct customer segments to enable targeted marketing strategies.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Features](#features)
- [Algorithm](#algorithm)
- [Results](#results)
- [Conclusion](#conclusion)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)

## Dataset

The dataset used in this project consists of customer purchase history from a retail store. Each record represents a customer's purchases, including details such as the frequency and monetary value of purchases.

## Features

The features used for clustering include:

- **Customer ID**: Unique identifier for each customer.
- **Frequency**: Number of purchases made by the customer.
- **Monetary Value**: Total monetary value of the customer's purchases.
- **Recency**: Time since the last purchase made by the customer.

## Algorithm

The K-means clustering algorithm was used to segment customers into distinct groups based on their purchase history. The steps involved were:

1. **Data Preprocessing**: Cleaning the dataset and normalizing features.
2. **Feature Selection**: Selecting relevant features for clustering.
3. **Model Training**: Applying the K-means algorithm to cluster the customers.
4. **Evaluation**: Evaluating the quality of the clusters and interpreting the results.

## Results

The K-means clustering algorithm successfully grouped customers into distinct segments. The identified clusters provide insights into different customer behaviors, which can be used for targeted marketing strategies. Key metrics include:

- **Cluster Centroids**: Representing the average values of features in each cluster.
- **Inertia**: Sum of squared distances of samples to their closest cluster center.
- **Silhouette Score**: Measure of how similar an object is to its own cluster compared to other clusters.

## Conclusion

This project demonstrated the effectiveness of K-means clustering in customer segmentation. By analyzing purchase history, we can identify distinct customer segments and tailor marketing efforts accordingly. This task has enhanced my understanding of clustering algorithms and their applications in retail analytics.

## Installation

To run this project locally, please follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/customer-segmentation.git
   ```
2. Navigate to the project directory:
   ```bash
   cd customer-segmentation
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

To perform customer segmentation, run the following command:
```bash
python segment_customers.py
```

Ensure that you have the dataset in the correct format and location as specified in the code.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
