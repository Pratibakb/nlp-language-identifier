🌐 Language Detection using NLP

A Natural Language Processing (NLP) project that detects the language of a given text using Count Vectorization and a Naive Bayes Classifier.

This project demonstrates preprocessing, feature extraction, model training, and evaluation, achieving an accuracy of \~98%.


📌 Features

* Detects the language of text inputs.
* Uses Bag of Words (CountVectorizer) for feature extraction.
* Implements Naive Bayes (MultinomialNB) for classification.
* Provides evaluation metrics: Accuracy, Confusion Matrix, and Classification Report.


⚙️ Tech Stack

* Python 3.x
* Libraries:

  * pandas
  * numpy
  * re
  * seaborn
  * matplotlib
  * scikit-learn


 📊 Workflow

1. Data Preprocessing

   * Load and clean text data.
   * Encode labels using `LabelEncoder`.

2. Feature Extraction

   * Convert text into numerical features using `CountVectorizer`.

3. Model Training

   * Split dataset into training and testing sets (`train_test_split`).
   * Train a Multinomial Naive Bayes classifier.

4. Evaluation

   * Evaluate model using `accuracy_score`, `confusion_matrix`, and `classification_report`.
   * Achieved Accuracy: 98%.


🚀 Usage

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/language-detection-nlp.git
   cd language-detection-nlp
   ```
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Open the notebook in Google Colab or Jupyter Notebook.
4. Run all cells to train and evaluate the model.


📈 Results

* Accuracy: \~98%
* Model generalises well for detecting languages in text data.


📌 Future Improvements

* Add more datasets for wider language coverage.
* Use advanced models like Logistic Regression, Random Forests, or Deep Learning (LSTMs, Transformers).
* Deploy the model as a web app or API.


👩‍💻 Author

Created by Sri Pratiba K B ✨

---

👉 Do you also want me to create a `requirements.txt` file for you so that you can share/run this project easily?

