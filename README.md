# 🌸 Iris Flower Clustering Dashboard

## 📌 Project Overview

The **Iris Flower Clustering Dashboard** is a machine learning project developed using Python and Streamlit.
It uses the K-Means Clustering algorithm to group Iris flowers based on their physical measurements.

The interactive dashboard allows users to explore flower data, visualize clusters, analyze relationships between features, and
predict the cluster of a new flower.

## 🎯 Objectives

- Analyze the Iris flower dataset.
- Apply the K-Means clustering algorithm.
- Visualize flower clusters using interactive graphs.
- Explore relationships between flower measurements.
- Predict the cluster of a new flower using user-provided measurements.

## ✨ Features

- **Cluster Distribution:** Displays the number of flowers in each cluster.
- **Feature Visualization:** Shows relationships between selected flower measurements.
- **PCA Visualization:** Displays clusters in two dimensions using Principal Component Analysis.
- **Cluster Prediction:** Predicts the cluster for a new flower.
- **Interactive Dashboard:** Provides cluster filters and a dataset preview.

## 🛠️ Technologies Used

- Python
- Streamlit
- Pandas
- Plotly
- Scikit-learn
- K-Means Clustering
- Principal Component Analysis (PCA)

## 📂 Project Structure

```text
Iris-Flower-Clustering-Dashboard/
│
├── app.py
├── Iris.csv
├── train_model.py
├── requirements.txt
├── README.md
└── .gitignore
```

The `iris_kmeans_model.pkl` file is generated when the model is trained.

## 📊 Dataset

The project uses the Iris flower dataset.

The following four features are used for clustering:

- Sepal Length (cm)
- Sepal Width (cm)
- Petal Length (cm)
- Petal Width (cm)

The K-Means algorithm groups flowers into three clusters based on these measurements.

**Note:** Cluster numbers represent groups identified by the algorithm and do not directly indicate the actual Iris species.

## ⚙️ Installation and Setup

### Step 1: Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/Iris-Flower-Clustering-Dashboard.git
```

Replace `YOUR-USERNAME` with your GitHub username.

### Step 2: Open the project folder

```bash
cd Iris-Flower-Clustering-Dashboard
```

### Step 3: Install the required libraries

```bash
pip install -r requirements.txt
```

### Step 4: Train the machine learning model

```bash
python train_model.py
```

This generates the `iris_kmeans_model.pkl` file required by the application.

### Step 5: Run the Streamlit application

```bash
streamlit run app.py
```

Open the local URL displayed in the terminal, usually:

`http://localhost:8501`

## 🧠 Machine Learning Algorithm

**K-Means Clustering** is an unsupervised machine learning algorithm that groups similar data points into clusters.

In this project:

1. The four flower measurements are selected.
2. The features are standardized using StandardScaler.
3. K-Means divides the flowers into three clusters.
4. PCA is used to visualize the clusters in two dimensions.
5. The trained model predicts the cluster for new flower measurements.

## 🚀 Future Enhancements

- Deploy the dashboard online using Streamlit Community Cloud.
- Improve cluster visualization and reporting.
- Add more interactive data analysis features.
- Compare clustering results using different algorithms.

## 👩‍💻 Author

**Apeksha Dhokare**

## 📄 License

This project is intended for educational and learning purposes.
