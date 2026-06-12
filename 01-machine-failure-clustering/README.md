# Machine Failure Sensor Clustering

Unsupervised learning case study based on sensor measurements collected from industrial machines.

## Objective

The objective of this project is to identify operational patterns in machine sensor data and compare different clustering approaches without using the available failure label during model training.

## Dataset

The dataset contains 944 machine sensor observations, including variables related to machine activity, air quality, ultrasonic measurements, electrical current, volatile organic compounds, rotational position, input pressure and operating temperature.

Source: [Machine Failure Prediction Using Sensor Data](https://www.kaggle.com/datasets/umerrtx/machine-failure-prediction-using-sensor-data)

## Methodology

The analysis includes:

* Exploratory data analysis
* Missing-value and duplicate detection
* Outlier analysis
* Feature transformation and scaling
* K-Means clustering
* DBSCAN clustering
* Hierarchical clustering
* PCA and t-SNE visualisation
* Internal cluster validation
* Comparison with the available machine failure label
* Review of scientific clustering applications

## Algorithms

* K-Means
* DBSCAN
* Agglomerative hierarchical clustering

## Evaluation Metrics

* Silhouette score
* Calinski-Harabasz index
* Davies-Bouldin index

## Main Result

Hierarchical clustering produced the most consistent internal validation results for this dataset. DBSCAN was also explored using different parameter configurations, but the density structure of the observations limited its performance.

## Project Files

The documented Jupyter notebook will contain the complete exploratory analysis, preprocessing, clustering experiments, visualisations and conclusions.

## Academic Context

This project was originally completed as part of the Unsupervised Machine Learning course of the MSc in Artificial Intelligence and received the highest possible grade.

The portfolio version preserves the original methodology, analysis and conclusions. Changes are limited mainly to documentation, organisation and presentation.
