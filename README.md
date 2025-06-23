# Soil Moisture Prediction using Transformer and Clustering

This project focuses on predicting soil moisture values from irrigation input using deep learning and clustering techniques.

## Dataset

The dataset contains two columns:
- **Irrigation**: Amount of water supplied
- **SoilMoisture**: Measured soil moisture content

## Project Steps

1. **Initial Modeling**  
   - Built a Transformer model on the complete dataset.  
   - Achieved excellent results with R² Score of **99.99%**.

2. **Clustering**  
   - Applied K-Means clustering to segment data into 3 clusters based on patterns in irrigation and moisture.  
   - Trained separate Transformer models on each cluster to better fit local behaviors.

3. **Cluster-wise Results**
   - **Cluster 0**: R² Score = **0.9976**
   - **Cluster 1**: R² Score = **0.9689**
   - **Cluster 2**: R² Score = **0.9888**

## Technologies Used

- Python
- PyTorch
- Scikit-learn
- KMeans Clustering
- Transformer Architecture
- Matplotlib
- NumPy, Pandas

## Key Takeaways

- Transformers are powerful for sequence modeling and regression tasks.
- Clustering improved localized prediction performance.
- Achieved high R² scores across all models, showing model robustness.

