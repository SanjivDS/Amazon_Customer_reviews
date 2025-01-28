# Sentiment Analysis - Amazon Customer Reviews

## Description
This project performs sentiment analysis on Amazon customer reviews to understand customer feedback and product insights. The project uses a dataset of Amazon customer reviews and employs natural language processing techniques to classify reviews into positive, neutral, and negative sentiments. It also extracts key phrases to identify important topics and trends in customer feedback. The analysis provides valuable insights into customer satisfaction, product strengths and weaknesses, and overall sentiment trends. These insights can be used to improve products, enhance customer experiences, and make informed business decisions.

## Installation
1.  Clone the repository: `git clone https://github.com/your-username/your-repository.git`
2.  Install dependencies: `pip install -r requirements.txt` (Make sure to create a requirements.txt file listing all your project's dependencies)
3.  Download the dataset from Kaggle: [https://www.kaggle.com/datasets/datafiniti/consumer-reviews-of-amazon-products](https://www.kaggle.com/datasets/datafiniti/consumer-reviews-of-amazon-products) and place it in the appropriate directory within your project.

## Usage
1.  Load the dataset into a PySpark DataFrame.
2.  Preprocess the data by cleaning the text, converting to lowercase, removing punctuation, tokenizing into words, and filtering out stop words.
3.  Perform sentiment analysis based on star ratings and extract key phrases using a CountVectorizer.
4.  Summarize feedback for each sentiment by selecting and displaying key phrases from positive and negative reviews.
5.  Aggregate insights by product category and sentiment, providing an overview of sentiment trends across categories.
6.  Visualize the results through word clouds, bar charts, and heatmaps to gain actionable insights.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change. Make sure to follow the existing coding style and conventions.

## License
MIT
