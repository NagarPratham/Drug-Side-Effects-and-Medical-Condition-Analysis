# Drug Side Effects Analysis Project

## 📌 Project Overview
A comprehensive analysis of drug side effects and their impact on medication ratings using advanced data science techniques.

### Key Objectives:
- **Exploratory Data Analysis** of side effects patterns
- **Sentiment Analysis** of side effect descriptions
- **Machine Learning Models** to predict drug ratings
- **Clustering** to identify drug safety groups

### Key Questions Answered:
- Which side effects most negatively impact drug ratings?
- Can we predict a drug's rating based on its side effects?
- What clusters of drugs emerge based on safety profiles?

---

## 🛠️ Tech Stack

| Category           | Technologies                   |
|-------------------|--------------------------------|
| Core             | Python 3.8+, Jupyter Notebooks |
| Data Processing  | Pandas, NumPy                  |
| Visualization    | Matplotlib, Seaborn, Plotly    |
| Machine Learning | Scikit-learn, TextBlob (NLP)   |
| Deployment      | GitHub, Google Colab           |

---

## 📂 Repository Structure
```
drug-side-effects/
├── data/
│   ├── raw/               # Original datasets
│   └── processed/         # Cleaned data
├── notebooks/
│   ├── 1_EDA.ipynb        # Exploratory Analysis
│   ├── 2_ML_Models.ipynb  # Predictive Modeling
│   └── 3_Clustering.ipynb # Drug Grouping
├── reports/
│   ├── figures/           # Visualizations
│   └── findings.pdf       # Key insights
├── .gitignore
├── requirements.txt
└── README.md
```

---

## 🚀 Getting Started

### Prerequisites
- Python 3.8+
- Jupyter Lab
- Git

### Installation
Clone the repository:
```bash
git clone https://github.com/your-username/drug-side-effects.git
cd drug-side-effects
```
Create a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows
```
Install dependencies:
```bash
pip install -r requirements.txt
```

---

## 🔍 Key Findings

### Side Effect Impact:
- Drugs with "difficulty breathing" side effects had **32% lower ratings**
- Topical medications showed **15% better sentiment scores** than oral drugs

### Prediction Model:
- **Random Forest** achieved **0.78 R²** score in rating prediction
- Most important features: **side effect sentiment, drug class, review count**

### Drug Clusters:
| Cluster | Characteristics |
|---------|----------------|
| 0       | High-rated, mild side effects |
| 1       | Moderate ratings, some severe effects |
| 2       | Low-rated, dangerous side effects |

---

## 📊 Sample Visualizations
<div align="center"> 
  <img src="C:\Users\Shell\Pictures\Screenshots\Screenshot 2025-04-02 010233.png" width="45%"> 
  <img src="C:\Users\Shell\Pictures\Screenshots\Screenshot 2025-04-02 015121.png" width="45%"> 
  <p><em>Left: Most common side effects | Right: Drug rating distribution</em></p>
</div>

---

## 🤝 Contributing
We welcome contributions! Please follow these steps:

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📜 License
Distributed under the **MIT License**. See `LICENSE` for more information.

---

## 📧 Contact
- **Project Lead:** Pratham Nagar
- **Project Link:** [GitHub Repository](https://github.com/your-username/drug-side-effects)

