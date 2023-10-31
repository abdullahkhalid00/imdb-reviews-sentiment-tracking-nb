# Sentiment Analysis with Naive Bayes

Sentiment Analysis on IMDb movie reviews dataset using Naive Bayes classifiers (GaussianNB, MultinomialNB, and BernoulliNB). This code preprocesses the text data, trains Naive Bayes models, and visualizes the performance.

## Description

This code performs Sentiment Analysis on the IMDb movie reviews dataset using Naive Bayes classifiers. It covers the following key steps:

1. Data Preprocessing: 
   - Removing HTML tags from text.
   - Removing special characters.
   - Converting text to lowercase.
   - Removing stop words.
   - Stemming the words.
   - Vectorization using CountVectorizer.

2. Model Training:
   - Training three Naive Bayes models: GaussianNB, MultinomialNB, and BernoulliNB.

3. Evaluation:
   - Computing accuracy scores for each model on the test data.

4. Hyperparameter Tuning:
   - Experimenting with different values for the 'max_features' hyperparameter of the CountVectorizer to increase accuracy.

5. Visualization:
   - Visualizing the accuracy scores of the Multinomial Naive Bayes model for different 'max_features' values.

## Installation

- Ensure you have Python installed on your system.
- Install the required libraries by running `pip install pandas numpy matplotlib seaborn nltk scikit-learn`.

## Usage

1. Clone the repository or download the script.

2. Place your IMDb movie reviews dataset (CSV file) in the same directory as the script.

3. Run the script using the following command:


4. The script will preprocess the data, train the models, and display accuracy scores.

5. It will also perform hyperparameter tuning and visualize the performance of the Multinomial Naive Bayes model for different 'max_features' values.

6. You can customize the dataset, hyperparameter values, and other parameters as needed.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- IMDb movie reviews dataset: [IMDb Dataset](https://www.kaggle.com/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)
- Inspiration and guidance from online tutorials and educational resources.