# E-Commerce-Customer-Segmentation-

## Project Overview
This project applies unsupervised machine learning techniques to segment e-commerce customers based on their Recency, Frequency, and Monetary (RFM) values.

## Objectives
- Perform data cleaning and preprocessing.
- Build customer-level RFM features.
- Apply K-Means and DBSCAN clustering.
- Use PCA and t-SNE to visualize customer segments.
- Develop actionable marketing personas based on cluster characteristics.

## Dataset
The project uses the Online Retail transaction dataset.

Source: [Kaggle — Online Retail Dataset](https://www.kaggle.com/datasets/vijayuv/onlineretail)

The dataset contains transaction details such as invoice number, quantity, invoice date, unit price, customer ID, and country.

## Technologies Used
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Jupyter Notebook

## Methodology
1. Data cleaning and preprocessing.
2. RFM feature engineering.
3. Log transformation and feature scaling.
4. K-Means clustering with silhouette score evaluation.
5. DBSCAN clustering and noise-point analysis.
6. PCA and t-SNE visualizations.
7. Cluster profiling and marketing persona development.

## Results
The notebook generates customer cluster assignments and a cluster summary. PCA and t-SNE plots help visualize the resulting customer segments.

See the `results/` directory for exported cluster data and visualizations.

## How to Run
1. Clone this repository.
2. Install dependencies using `pip install -r requirements.txt`.
3. Place the downloaded dataset in the `Dataset/` directory.
4. Open `Customer_Segmentation.ipynb` in Jupyter Notebook or VS Code.
5. Run the notebook cells in order.

## Future Improvements
- Tune DBSCAN parameters systematically.
- Compare clustering quality using appropriate evaluation metrics.
- Refine customer personas using cluster profiles.
- Develop targeted marketing strategies for each segment.
