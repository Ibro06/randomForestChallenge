# 🌲 Random Forest Challenge - The Power of Weak Learners

**A comprehensive analysis demonstrating the power of ensemble learning through random forest regression on housing price data.**

## 📊 View the Complete Analysis

👉 **[Visit the interactive website →](https://ibro06.github.io/randomForestChallenge/)**

The website contains:
- **Power of Trees Analysis** - How ensemble learning improves predictions
- **Overfitting Comparison** - Decision trees vs Random forests
- **Linear Regression Comparison** - When complexity is worth it
- **Interactive Visualizations** - Professional charts and insights

## 🎯 About This Project

This project demonstrates the power of random forests for predicting housing prices using the Ames Housing dataset. Through comprehensive analysis, we explore:

- How the number of trees affects predictive accuracy
- Why random forests resist overfitting while individual trees fail
- When the added complexity of random forests justifies their use over simple linear regression

## 🔬 Methodology

**Dataset:** Ames Housing dataset with detailed residential property information from Ames, Iowa (2006-2010)

**Models Analyzed:**
- Linear Regression (baseline)
- Decision Trees with varying depths
- Random Forests with 1, 5, 25, 100, 500, 1000, 2000, and 5000 trees

**Key Insights:**
- The first 100 trees deliver most performance gains (15% RMSE improvement)
- Random forests maintain perfect training-test alignment (no overfitting)
- 100-500 trees represent the optimal balance between performance and computational cost
- Random forests achieve 8-10% better performance than linear regression for this non-linear dataset

## 📁 Repository Structure

```
randomForestChallenge/
├── index.qmd         # Main analysis document
├── index.html        # Rendered website
├── index_files/      # Generated visualizations and assets
├── requirements.txt  # Python dependencies
└── README.md         # This file
```

## 🚀 Getting Started (For Contributors)

1. **Clone the repository**
   ```bash
   git clone https://github.com/Ibro06/randomForestChallenge.git
   cd randomForestChallenge
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Render the website**
   ```bash
   quarto render index.qmd
   ```

4. **View locally**
   Open `index.html` in your browser

## 🏆 Course Information

**Course:** BUAD442 - Data Analytics  
**Assignment:** Random Forest Challenge  
**Topic:** Ensemble Learning and Model Comparison

## 📄 License

This project is part of course materials for educational purposes.

---

*Built with Quarto and Python • Source code available on [GitHub](https://github.com/Ibro06/randomForestChallenge)*
