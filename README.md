## **Movie Recommendation System**

### **Project Overview**

This project develops a hybrid movie recommendation system using a combination of **content-based filtering** and **collaborative filtering**. The system utilizes data from **IMDb** (scraped via Python-BeautifulSoup) and **Kaggle** datasets to provide personalized movie recommendations based on user preferences and content similarities. Additionally, we analyzed the **feature importance** influencing **movie revenue** to understand which aspects contribute the most to a movie’s success.

### **Datasets**

1. **IMDb Dataset**:

   * **Source**: Scraped from [IMDb website](https://www.imdb.com/list/ls098063263/)
   * **Updated**: 2023
   * **Description**: Contains information about movies, including titles, genres, descriptions, and revenue. Stored in `imdb.csv` (1,000 rows).

2. **Kaggle Keywords Dataset**:

   * **Source**: Kaggle.com
   * **Updated**: 2017
   * **Description**: Provides keywords for each movie, which enriches the movie metadata. Stored in `keywordsmovie.csv`.

### **Installation**

### Prerequisites:

Ensure that you have Python 3.x installed, and then install the required libraries using pip:

```bash
pip install pandas numpy scikit-learn beautifulsoup4
```

### **How It Works**

* **Data Collection**:

  * IMDb data is scraped using **Python** and **BeautifulSoup**.
  * The Kaggle dataset is downloaded directly and merged with IMDb data to enrich movie metadata.

* **Data Preprocessing**:

  * The collected data is cleaned and processed, including feature extraction and vectorization for use in the recommendation system.

* **Recommendation Engine**:

  * A **hybrid recommendation model** is built, combining content-based filtering (cosine similarity) with filtering logic to provide recommendations based on both movie content and user preferences.

* **Feature Importance Analysis**:

  * We performed an analysis of **feature importance** to identify which attributes (such as genre, director, cast, budget) most influence **movie revenue**. This analysis helps understand what factors contribute to a movie's success.

* **Evaluation**:

  * The system's accuracy is measured based on user-item relevance, ensuring meaningful and relevant movie recommendations.

### **Main Responsibilities**

* Collected and preprocessed movie data from IMDb using **Python** and **BeautifulSoup**.
* Merged the IMDb dataset with the **Kaggle keywords dataset** to enrich movie metadata.
* Performed data cleaning, feature extraction, and vectorization.
* Built a hybrid recommendation engine using **cosine similarity** and **filtering logic**.
* Analyzed **feature importance** to assess the impact of different attributes on **movie revenue**.
* Evaluated system accuracy using **user-item relevance**.

### **GitHub Repository**

* **Link to GitHub Repository**: [MovieRecommendationSystem]([https://github.com/yourusername/MovieRecommendationSystem](https://github.com/Quaangg/Recommendation-movie-system/))

### **Project Duration**

6 weeks

### **Conclusion**

This project demonstrates the application of hybrid recommendation systems in real-world scenarios, leveraging movie metadata from IMDb and Kaggle datasets to deliver accurate recommendations. Additionally, the feature importance analysis provides valuable insights into the factors that drive movie revenue.

