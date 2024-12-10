# Fake News Detection AI Project

## Summary
This project focuses on detecting fake news using machine learning models. The following models were utilized:

- **Logistic Regression**
- **Support Vector Classifier**
- **Naive Bayes**

### Performance Scores (after pre-processing with TF-IDF Vectorizer):
- **Logistic Regression**: 99% Accuracy  
- **Support Vector Classifier**: 100% Accuracy  
- **Naive Bayes Classifier**: 94% Accuracy  

---

## Libraries Used
The following Python libraries were used in this project:

- **NLTK**: For text pre-processing and stopwords removal.
- **Scikit-learn**: For building and evaluating machine learning models.
- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical computations.
- **Matplotlib/Seaborn**: For data visualization.

---

## Datasets
The project uses datasets containing labeled articles classified as real or fake news.  
Ensure you have the dataset file(s) in the same directory or provide a proper path in the Colab notebook.

---

## Installation and Setup

1. **Clone the Repository**  
   Clone the repository to your local machine using the following command:
   ```bash
   git clone https://github.com/your-username/Fake_News_Detection_AI_Project.git
   cd Fake_News_Detection_AI_Project
2. Set Up Python Environment
Ensure you have Python 3.8 or higher installed on your machine.

3. Install Required Libraries
Install the required Python libraries by running:
   pip install -r requirements.txt
  (Create a requirements.txt file in your repository with all required dependencies.) 
4. Open the Notebook
Open the Colab notebook file Fake_News_Detection_AI_Project.ipynb in Google Colab.
5. Run the Code

Upload your dataset or link the dataset path as required in the notebook.
Execute the notebook cells step-by-step to preprocess data, train the models, and view performance metrics.

## Usage Instructions
 -Modify the dataset path in the notebook if your dataset is stored locally or on Google Drive.
 -Fine-tune the hyperparameters in the code if needed to explore further improvements.
 -Use the visualizations provided in the notebook to interpret the results better.

## Results
The models demonstrated excellent performance with high accuracy, indicating their effectiveness in identifying fake news.

## Future Work
-Incorporate deep learning models such as LSTMs and Transformers for comparison.
-Experiment with additional feature engineering techniques for improved accuracy.

## Acknowledgments
-This project uses publicly available datasets for machine learning experiments.
-Special thanks to the developers of libraries like NLTK, Scikit-learn, and Pandas for making this project possible.

 
