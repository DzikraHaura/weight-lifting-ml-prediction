# Weight Lifting Exercise Quality Prediction using Machine Learning

## 🎯 Project Overview
This project uses machine learning algorithms to predict the quality of weight lifting exercises using accelerometer data from wearable devices worn by 6 participants.

## 📊 Key Results
- **Best Algorithm:** Random Forest
- **Accuracy:** 99.2%
- **Out-of-sample Error:** ~0.8%
- **Cross-validation:** 3-fold CV
- **Prediction Confidence:** 99.4% average

## 📁 Project Files
- `weight_lifting_analysis.Rmd` - Complete R Markdown analysis
- `weight_lifting_analysis.html` - Rendered HTML report ([View Online](https://githubusername.github.io/weight-lifting-ml-prediction/weight_lifting_analysis.html))
- `final_predictions.csv` - Predictions for 20 test cases
- `best_model_rf.rds` - Trained Random Forest model

## 🔬 Analysis Highlights
- **Dataset:** 19,622 observations, 160 variables
- **Classes:** 5 exercise quality levels (A-E)
- **Sensors:** Belt, forearm, arm, and dumbbell accelerometers
- **Models Compared:** Decision Tree, Random Forest, GBM
- **Feature Engineering:** Removed high missing values, near-zero variance

## 📈 Model Performance
| Model | Accuracy | Kappa | Out-of-Sample Error |
|-------|----------|--------|-------------------|
| Decision Tree | 74.9% | 0.678 | 25.1% |
| Random Forest | **99.2%** | **0.990** | **0.8%** |
| GBM | 96.1% | 0.951 | 3.9% |

## 🚀 How to Run
1. Open `weight_lifting_analysis.Rmd` in RStudio
2. Required packages will be loaded automatically
3. Knit document to HTML
4. Analysis will run and generate predictions

## 📊 View Results
- **HTML Report:** [Click here to view analysis](weight_lifting_analysis.html)
- **Model Predictions:** Check `final_predictions.csv`

## 🔗 Data Source
Velloso, E.; Bulling, A.; Gellersen, H.; Ugulino, W.; Fuks, H. *Qualitative Activity Recognition of Weight Lifting Exercises.* Proceedings of 4th International Conference in Cooperation with SIGCHI (Augmented Human '13). Stuttgart, Germany: ACM SIGCHI, 2013.

## 📝 License
This project is open source and available under the MIT License.

---
**Created using Coursera Lab Sandbox RStudio Environment**
