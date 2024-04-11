# Fake-news-detection-using-ML
This code implements a machine learning-based system for classifying news articles as fake or real using text classification techniques.
**README**

**Description:**
This program implements a text classification system using machine learning algorithms to identify fake news articles. It loads a dataset containing labeled news articles (fake or real), preprocesses the text data, trains three classifiers (Multinomial Naive Bayes, Logistic Regression, and Random Forest Classifier) using TF-IDF vectorization, evaluates their accuracies, and visualizes the results using bar plots and confusion matrices. Additionally, it provides a function to classify input sentences and generates a classification report.

**Dependencies:**
- pandas
- scikit-learn
- matplotlib
- seaborn

**Setup:**
1. Install the required dependencies using `pip install pandas scikit-learn matplotlib seaborn`.
2. Ensure that the dataset file `fake_news.csv` is in the same directory as the program file.
3. Run the program using Python.

**Usage:**
1. The program will load the dataset and display the first 5 rows of the data.
2. It then splits the dataset into training and testing sets, preprocesses the text data using TF-IDF vectorization, and trains multiple classifiers.
3. The accuracies of each classifier are printed, and a bar plot displaying the accuracies is shown.
4. Confusion matrices for each classifier are displayed to visualize the performance.
5. You can input a sentence to classify as fake or real news, and the predictions from each classifier will be printed.
6. Finally, a classification report is generated, providing a detailed evaluation of the classifiers' performance.

**Notes:**
- Ensure that the dataset file `fake_news.csv` is properly formatted with columns for text and labels.
- This program serves as a demonstration of text classification techniques and should be used for educational purposes only.
- Experiment with different classifiers and parameters for improved performance on your dataset.

**Disclaimer:**
This program is for educational and demonstration purposes only. It should not be used for making real-world decisions without further validation and analysis.
