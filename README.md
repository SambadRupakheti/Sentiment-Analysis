# Sentiment-Analysis
# Sentiment Analysis Using VADER

## 📌 Project Overview
This project implements **sentiment analysis** on customer reviews using **VADER (Valence Aware Dictionary and sEntiment Reasoner)**. It processes text data, classifies sentiments as **Positive, Negative, or Neutral**, and visualizes the sentiment distribution.

## 📂 Dataset
- The dataset used is `Reviews.csv`, containing customer reviews.
- The primary column analyzed is **'Text'**, which includes customer feedback.

## 🚀 Features
- **Text Preprocessing**: Converts text to lowercase, removes punctuation, and eliminates stopwords.
- **Sentiment Analysis**: Uses VADER to classify sentiment scores.
- **Visualization**: Generates a bar chart displaying sentiment distribution.
- **Final Processed Data**: Outputs a cleaned dataset with sentiment labels.

## 🔧 Installation & Setup
1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/yourrepository.git
   cd yourrepository
   ```
2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
3. **Download necessary NLTK resources:**
   ```python
   import nltk
   nltk.download('vader_lexicon')
   nltk.download('stopwords')
   ```

## 📜 How to Run the Project
1. **Open Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```
2. **Run each cell step-by-step:**
   - **Step 1:** Import libraries.
   - **Step 2:** Load and check the dataset.
   - **Step 3:** Clean and preprocess text.
   - **Step 4:** Perform sentiment analysis using VADER.
   - **Step 5:** Visualize the sentiment distribution.
   - **Step 6:** Display the final results.

## 📊 Sentiment Classification
- **Positive**: Compound score `≥ 0.05`
- **Negative**: Compound score `≤ -0.05`
- **Neutral**: Compound score between `-0.05` and `0.05`

## 📈 Visualization
- Uses **Seaborn & Matplotlib** to create a bar chart.
- Sentiment categories are color-coded: **Purple, Hot Pink, and Violet**.

## 📎 Output Example
| Cleaned Text | Compound Score | Sentiment |
|-------------|---------------|------------|
| great product works well | 0.78 | Positive |
| not worth the money | -0.55 | Negative |
| it's okay nothing special | 0.02 | Neutral |


## 📜 License
This project is open-source under the **MIT License**.
