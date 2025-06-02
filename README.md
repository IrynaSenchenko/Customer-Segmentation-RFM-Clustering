# 🧠 Customer Segmentation with RFM and Clustering

This project demonstrates how to segment customers based on their behavior using unsupervised machine learning techniques. The dataset is based on real-world e-commerce transactions.

## 📂 Project Structure

- `1_EDA_and_Cleaning.ipynb` — data exploration, cleaning, RFM and customer features engineering
- `2_Clustering_and_Evaluation.ipynb` — clustering with KMeans, Agglomerative, DBSCAN + evaluation
- `3_Business_Insights_and_Segments.ipynb` — segment profiling and business interpretation
- `data/` — raw and cleaned datasets
- `screenshots/` — project visuals
- `requirements.txt` — Python libraries

## 🔍 Techniques Used

- RFM segmentation
- Feature engineering (AvgOrderValue, CustomerLifespan, etc.)
- StandardScaler, PCA
- KMeans, Agglomerative, DBSCAN
- Silhouette, Calinski-Harabasz, Davies-Bouldin
- Profiling segments: VIP, Lost, Passive, Loyal, etc.

## 📊 Sample Outputs

![Clusters PCA](screenshots/clusters_pca.png)
![Segment heatmap](screenshots/cluster_heatmap.png)
![Segment profiles](screenshots/profiles_bar.png)

## 🧩 Dataset

- Kaggle: [Customer Segmentation Dataset](https://www.kaggle.com/datasets/yasserh/customer-segmentation-dataset)

## 🚀 How to Run

```bash
pip install -r requirements.txt


# 🧠 Сегментація клієнтів на основі RFM і кластеризації

Цей проєкт демонструє, як можна сегментувати клієнтів на основі їхньої поведінки, використовуючи машинне навчання без учителя. Дані базуються на реальних e-commerce транзакціях.

## 📂 Структура проєкту

- `1_EDA_and_Cleaning.ipynb` — дослідження, очищення даних, побудова RFM-фіч
- `2_Clustering_and_Evaluation.ipynb` — кластеризація (KMeans, DBSCAN, Agglomerative) та оцінка
- `3_Business_Insights_and_Segments.ipynb` — опис сегментів і бізнес-інтерпретація
- `data/` — сирі та очищені файли
- `screenshots/` — графіки та візуалізації
- `requirements.txt` — список бібліотек

## 🔍 Техніки

- RFM-аналіз
- Генерація ознак: середній чек, тривалість життя клієнта
- Масштабування, PCA
- Кластеризація: KMeans, Agglomerative, DBSCAN
- Метрики якості: Silhouette, Calinski-Harabasz, Davies-Bouldin
- Бізнес-профілі: VIP, Lost, Passive, Loyal тощо

## 📊 Приклади виводу

![Кластери PCA](screenshots/clusters_pca.png)
![Хітмапа сегментів](screenshots/cluster_heatmap.png)
![Профілі сегментів](screenshots/profiles_bar.png)

## 🧩 Джерело даних

- Kaggle: [Customer Segmentation Dataset](https://www.kaggle.com/datasets/yasserh/customer-segmentation-dataset)

## 🚀 Як запустити

```bash
pip install -r requirements.txt