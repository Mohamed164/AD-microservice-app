# Synthetic Time Series for Anomaly Detection in Cloud Microservices

This repository contains open-source datasets published alongside the paper "Synthetic Time Series for Anomaly Detection in Cloud Microservices." The datasets are designed to support research and development in the field of anomaly detection for microservice applications.

## Contents

The repository includes two datasets named after their respective dates of generation: `13-05-2024` and `20-05-2024`. Each dataset contains the following files:

### 1. Metrics Data
Each dataset contains a metrics CSV file named `<date>_metrics.csv`, which includes the following metrics and ground truth labels:

| Entity Type         | Metrics | #Entities | Total |
|---------------------|---------|-----------|-------|
| Node                | 25      | 5         | 125   |
| Pod                 | 18      | 14        | 252   |
| Service             | 9       | 10        | 90    |
| Load anomaly G.T.   | 1       | -         | 1     |
| FIS anomaly G.T.    | 1       | -         | 1     |
| Anomaly G.T.        | 1       | -         | 1     |
| **Total**           |         |           | **470** |

The metrics cover various performance indicators for nodes, pods, and services within a microservice architecture. The ground truth (G.T.) labels provide information on load anomalies and FIS (AWS Fault Injection Service) anomalies.

### 2. FIS Experiment Actions Data
Each dataset also includes a CSV file named `<date>_FIS_Experiment_Actions.csv`, which contains information about the injected FIS anomalies, including their types, targets (pod/node), and start and end timestamps. This file is crucial for understanding the specific anomalies injected during the experiments.

## Contact

For any questions or issues, please contact [mohamedallam164@gmail.com](mailto:mohamedallam164@gmail.com).

