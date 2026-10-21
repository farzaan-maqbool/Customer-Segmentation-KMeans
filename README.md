Customer Segmentation Using Clustering Algorithms

📌 Project Overview

This project applies unsupervised machine learning techniques to segment customers based on their annual income and spending score. It explores multiple clustering algorithms to identify customer groups and understand purchasing behavior.

🎯 Objectives

- Identify distinct customer segments using machine learning.
- Visualize customer groups based on income and spending patterns.
- Compare different clustering algorithms.
- Generate insights that can support targeted marketing strategies.

🛠️ Technologies Used

- Language: Python
- Libraries: Pandas, Matplotlib, Scikit-learn
- Platform: Google Colab
- Dataset: Mall Customer Segmentation Dataset

📊 Dataset

The dataset contains 200 customer records with the following features:

- Customer ID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1–100)

🤖 Algorithms Implemented

1. K-Means Clustering — Groups customers into clusters based on similarity.
2. Agglomerative Clustering — Builds a hierarchy of customer groups.
3. DBSCAN — Identifies density-based clusters and potential outliers.

⚙️ Methodology

1. Load the dataset using Pandas.
2. Explore the data and inspect its structure.
3. Select annual income and spending score as clustering features.
4. Standardize the selected features using "StandardScaler".
5. Apply the clustering algorithms.
6. Visualize and compare the resulting customer segments.

📈 Results

The notebook generates visualizations to help interpret customer groups and compare clustering approaches. These segments can help businesses understand different spending patterns and develop more targeted marketing strategies.

Note: Actual cluster quality and the number of clusters may vary by algorithm and parameter settings.

🚀 How to Run

1. Open the notebook from this GitHub repository.
2. Click Open in Colab if available, or download the ".ipynb" file and upload it to "Google Colab" (https://colab.research.google.com/).
3. Run the cells sequentially.
4. View the generated clustering plots and outputs.

💡 Applications

- Customer profiling
- Targeted marketing
- Retail analytics
- Spending behavior analysis
- Customer relationship management

🔮 Future Improvements

- Evaluate clustering quality using silhouette scores.
- Use the Elbow Method to select the number of K-Means clusters.
- Compare clustering results using additional features.
- Build an interactive dashboard using Streamlit.

👨‍💻 Author

Farzaan Maqbool

Computer Science Engineering Student

GitHub: "farzaan-maqbool" (https://github.com/farzaan-maqbool)

---

If you find this project useful, consider giving the repository a ⭐.
