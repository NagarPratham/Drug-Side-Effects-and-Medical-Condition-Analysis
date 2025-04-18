# Drug Side Effects & Medical Condition Analysis 🏥💊

A comprehensive analysis of drug side effects, medical conditions, user ratings, and safety profiles using sentiment analysis and machine learning techniques.

## 📌 Table of Contents
- [Project Overview](#-project-overview)
- [Key Features](#-key-features)
- [Methodology](#-methodology)
- [Key Findings](#-key-findings)
- [Installation](#-installation)
- [Usage](#-usage)
- [Contact](#-contact)

## 🌟 Project Overview
This project analyzes drug side effects, medical conditions, and user ratings to:
- Identify top medical conditions and their treatment options
- Evaluate user sentiment about drug side effects
- Predict drug ratings based on various features
- Cluster drugs into safety profile groups
- Analyze pregnancy risk categories

## 🚀 Key Features
- **Sentiment Analysis**: Quantify side effect severity using TextBlob (-1 to +1 polarity)
- **Rating Prediction**: Random Forest model with 0.78 R² score
- **Drug Clustering**: K-Means clustering to group drugs by safety profiles
- **Comprehensive EDA**: Word clouds, distribution plots, and trend analysis
- **Pregnancy Safety**: FDA pregnancy risk category analysis
- **Top Conditions**: Identification of top 10 medical conditions

## 🔬 Methodology
### 📋 Basic Analysis
- Top 10 conditions by drug availability
- Average user ratings per condition
- FDA pregnancy risk code analysis
- Review volume per condition

### 🧠 Advanced Analytics
- **Sentiment Analysis**: TextBlob for side effect severity scoring
- **Machine Learning**: Random Forest for rating prediction
- **Clustering**: K-Means with PCA visualization
- **Data Visualization**: Word clouds, bar plots, distribution analysis

## 📊 Key Findings
| Area | Insight |
|------|---------|
| Side Effects | Drugs with "difficulty breathing" side effects saw 32% lower ratings |
| Sentiment | Topical drugs had ~15% better sentiment than oral |
| Prediction | Most predictive features: side effect sentiment, review count |
| Clusters | 3 distinct safety profile clusters identified |
| Conditions | [Top condition] had the highest number of available treatments |

### Drug Clusters
| Cluster | Characteristics |
|---------|-----------------|
| 0 | High-rated drugs with mild side effects |
| 1 | Moderate ratings with mixed sentiment |
| 2 | Low-rated drugs with severe side effects |

## 💻 Installation
1. Clone the repository:
```bash
git clone https://github.com/NagarPratham/Drug-Side-Effects-and-Medical-Condition-Analysis.git
cd Drug-Side-Effects-and-Medical-Condition-Analysis
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
pip install -r requirements.txt
```

## 🛠 Usage
Run the Jupyter notebooks in this order:
1. `1_data_collection_cleaning.ipynb`
2. `2_eda_analysis.ipynb`
3. `3_sentiment_analysis.ipynb`
4. `4_model_training.ipynb`
5. `5_clustering_analysis.ipynb`

## 📧 Contact
**Project Lead**: Pratham Nagar 
