# Spam-NonSpam-Email-Prediction--Classification

## Objective
The objective of this project is to classify emails as **Spam** or **Not Spam** based on historical data. The model aims to assist in automating email categorization, improving efficiency and filtering accuracy.

## Methodology

### Data Exploration and Preprocessing
- **Data Overview**: The dataset consists of email text labeled as either spam or not spam.
- **Text Vectorization**: Utilized **CountVectorizer** to convert textual data into numerical format for model training.

### Model Development
- **Algorithm Used**: Implemented **Naive Bayes** classifier, a probabilistic machine learning algorithm well-suited for text classification tasks.
- **Training**: The model was trained on vectorized data to learn patterns distinguishing spam from non-spam emails.
- **Prediction**: After training, the model was used to classify new email data.

## Results
- The project demonstrated the effectiveness of Naive Bayes in handling spam email classification tasks.
- The simplicity of CountVectorizer and Naive Bayes provided a straightforward yet robust solution for text classification.

## Conclusion
The Spam/Not Spam Email Prediction project successfully implemented a classification pipeline using CountVectorizer and Naive Bayes. While no formal evaluation metrics were applied in this version, future improvements could include:
- Adding evaluation metrics such as Accuracy, Precision, Recall, and F1-score.
- Exploring alternative vectorization techniques like TF-IDF.
- Comparing performance with other classification algorithms such as Logistic Regression or SVM.

---

## How to Run
1. Clone the repository: `git clone https://github.com/yourusername/spam-classification.git`
2. Open the Jupyter Notebook: `jupyter notebook Spam_Not_Spam_Email_Prediction.ipynb`
3. Run the notebook cells sequentially to reproduce results.

## Files in the Repository
- **Spam_Not_Spam_Email_Prediction.ipynb**: Contains the code and analysis for the project.
- **ham.zip**: Folder containing input datasets Non-Spam mails.
- **spam.zip**: Folder containing input datasets Spam mails.

## References
- Spam email datasets from public repositories
- Documentation for scikit-learn and related libraries used in the project.

Feel free to explore the repository and provide feedback or contributions!

