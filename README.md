# 📊 Amazon Food Reviews - Big Data Analysis

## 📝 Project Overview
This project focuses on analyzing approximately **500,000** Amazon food reviews using **efficient data processing techniques**. The primary objective is to extract valuable insights, perform sentiment analysis, and understand customer feedback trends through advanced data manipulation and visualization.

The dataset consists of customer reviews of various food products, including information such as ratings, review text, and timestamps. Given its large size, optimized Pandas and NumPy techniques were used for efficient data handling.

## 🎯 Objectives
The project aims to:
- **Clean and preprocess** the dataset by handling missing values, removing duplicates, and normalizing text.
- **Perform Exploratory Data Analysis (EDA)** to uncover trends, customer sentiments, and frequently mentioned keywords.
- **Conduct Sentiment Analysis** to classify reviews as **positive, neutral, or negative**.
- **Visualize trends** through word clouds, bar plots, and time-series graphs.
- **Optimize data processing** using **Pandas and NumPy** for large-scale analysis.

## 🔧 Technologies Used
The following technologies and tools were used in this analysis:
- **Python 3.x** (Primary programming language)
- **Jupyter Notebook** (For interactive data exploration)
- **Pandas & NumPy** (For efficient data manipulation and optimization)
- **NLTK & TextBlob** (For sentiment analysis and natural language processing)
- **Matplotlib & Seaborn** (For data visualization)
- **WordCloud** (For generating keyword frequency visualizations)
- **Scikit-learn** (For machine learning-based sentiment classification)

## 📂 Dataset Details
- **Source:** [Amazon Fine Food Reviews Dataset](https://www.kaggle.com/snap/amazon-fine-food-reviews)
- **Total Reviews:** ~500,000
- **Key Fields:**
  - `User ID` - Unique identifier for the reviewer
  - `Profile Name` - Name of the reviewer
  - `Review Text` - Detailed customer feedback
  - `Summary` - Brief summary of the review
  - `Score` - Rating given by the customer (1-5 scale)
  - `Time` - Timestamp of the review

## 📊 Analysis Performed
### 1️⃣ Data Cleaning & Preprocessing
- Removed duplicate reviews and missing values.
- Tokenized text and converted it to lowercase.
- Removed stopwords and special characters to enhance text analysis.
- Applied lemmatization to standardize words.

### 2️⃣ Exploratory Data Analysis (EDA)
- **Distribution of Ratings:** Analyzed the proportion of 1-star to 5-star reviews.
- **Most Reviewed Products:** Identified food products with the highest number of reviews.
- **Frequent Words:** Extracted the most commonly used words in reviews.
- **Time-based Trends:** Visualized changes in customer sentiment over time.

### 3️⃣ Sentiment Analysis
- Used **VADER** and **TextBlob** to determine the polarity of review text.
- Classified reviews into **positive, negative, and neutral** categories.
- Compared results with actual user ratings.

### 4️⃣ Word Cloud & N-gram Analysis
- Generated **word clouds** to highlight commonly mentioned words.
- Conducted **bigram and trigram analysis** to identify frequent word pairs and phrases.

### 5️⃣ Data Optimization with Pandas & NumPy
- Used **Pandas DataFrames** for structured data handling.
- Applied **NumPy operations** to improve numerical processing efficiency.
- Optimized grouping, filtering, and transformation functions to handle large datasets effectively.

## 📌 Implementation Steps
### Prerequisites
Ensure you have the following installed:
- Python 3.x
- Jupyter Notebook
- Required Python libraries (`pandas`, `numpy`, `nltk`, `textblob`, `matplotlib`, `seaborn`, `wordcloud`)

### Steps to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/amazon-food-reviews-analysis.git
   cd amazon-food-reviews-analysis
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Start Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
4. Open the `bda-miniproject.ipynb` file and execute the cells.

## 📈 Results & Insights
- **Sentiment Breakdown:**
  - Positive: **XX%**
  - Neutral: **XX%**
  - Negative: **XX%**
- **Most Reviewed Products:** List of top products with high review counts.
- **Frequent Words in Reviews:** Commonly used words indicating customer preferences.
- **Temporal Trends:** Variations in sentiment over different years.
- **Optimized Processing:** Efficient use of Pandas and NumPy reduced data processing time.

## 🚀 Future Enhancements
- Implement **deep learning models (LSTMs, Transformers)** for better sentiment classification.
- Develop an **interactive dashboard** for real-time visualization of review trends.
- Improve **topic modeling** using **Latent Dirichlet Allocation (LDA)**.
- Apply **aspect-based sentiment analysis** to analyze customer sentiment towards specific product attributes.

## 📜 License
This project is licensed under the **MIT License**.

## 🤝 Contributing
We welcome contributions! Feel free to fork this repository, raise issues, and submit pull requests.

## 📞 Contact
For queries or collaboration, reach out via **[your email]** or open an issue in this repository.

---
⭐ If you found this project useful, please consider **starring** this repository!
