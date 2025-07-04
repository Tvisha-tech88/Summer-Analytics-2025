# 📊 Summer Analytics 2025 – Projects Repository
### Author: Tvisha Bansal
📖 Program Overview
The Summer Analytics 2025 program, organized by the Consulting & Analytics Club × Pathway, is a structured learning initiative aimed at solving real-world analytics problems using Python, machine learning, and real-time processing.

This repository contains all projects completed during the program, covering dynamic pricing, classification, customer segmentation, and real-time data streaming.

🛠️ Tech Stack Used
Technology	Purpose
Python	Primary programming language
Pandas	Data manipulation and preprocessing
Numpy	Numerical computations
Bokeh	Real-time visualization
Pathway	Real-time data ingestion and processing
Scikit-learn	Machine learning models (for some projects)
Google Colab	Cloud-based development environment

⚙️ Architecture Flow
The projects follow a standardized architecture flow:

General Workflow:
Data Ingestion:

Load dataset from CSV or simulate streaming using Pathway.

Data Preprocessing:

Clean missing values, encode categorical variables, normalize features.

Feature Engineering:

Calculate occupancy rates, vehicle weights, traffic scores, NDVI indices (for other projects).

Modeling:

Pricing models (Linear, Demand-based, Competitive)

Classification models (Logistic Regression)

Clustering models (K-Means)

Real-Time Processing (Dynamic Pricing Project):

Stream data using Pathway’s real-time pipeline.

Continuously update pricing based on incoming data.

Visualization:

Plot real-time price updates using Bokeh.

Cluster analysis and classification visualizations for other projects.

Insights & Reporting:

Interpret pricing trends, clustering patterns, and model performance.

Summarize results in a project-specific PDF report.

🌐 Architecture Flow Diagram (Text-Based)

+-----------------+      +-------------------+      +-----------------+      +-------------------+
|                 |      |                   |      |                 |      |                   |
|  Data Source    +----->+  Preprocessing    +----->+   Feature        +----->+   Model            |
| (CSV/Streaming) |      | (Cleaning,        |      |  Engineering    |      |  (Pricing,         |
|                 |      | Normalization)    |      |                 |      |  Classification,   |
+-----------------+      +-------------------+      +-----------------+      |  Clustering)       |
                                                                           +-------------------+
                                                                                    |
                                                                                    v
                                                               +--------------------------+
                                                               | Real-Time Visualization  |
                                                               |      (Bokeh)             |
                                                               +--------------------------+
                                                                                    |
                                                                                    v
                                                               +--------------------------+
                                                               |    Reporting & Insights  |
                                                               +--------------------------+



