# Sentiment Analysis of ChatGPT Feedback Data

## Project Overview

This project focuses on analyzing the sentiment of ChatGPT feedback data using Natural Language Processing (NLP) techniques. By processing 100,000 tweets, the project aimed to identify and reduce negative sentiment through various NLP approaches, including tokenization and sentiment analysis using the VADER library. The result was a significant reduction in negative sentiment and an increase in favorable responses.

## Objectives

- **Analyze Sentiment**: Conduct sentiment analysis on 100,000 tweets related to ChatGPT feedback.
- **Reduce Negative Sentiment**: Employ NLP techniques to reduce negative sentiment from 90% to 16%.
- **Achieve Favorable Response**: Improve overall sentiment, achieving an 84% favorable response rate.

## Technologies Used

- **Programming Language**: Python
- **Libraries**:
  - Pandas: For data manipulation and analysis.
  - Scikit-learn: For machine learning and model evaluation.
  - Seaborn: For data visualization.
  - VADER: For sentiment analysis using lexicon-based methods.

## Methodology

1. **Data Collection**: Extracted 100,000 tweets related to ChatGPT feedback for sentiment analysis.
2. **Data Preprocessing**:
   - **Tokenization**: Breaking down text data into individual tokens to analyze sentiment.
   - **Sentiment Analysis**: Applied VADER (Valence Aware Dictionary and sEntiment Reasoner) for lexicon-based sentiment analysis.
3. **Sentiment Reduction**:
   - Identified key patterns contributing to negative sentiment.
   - Implemented strategies to reduce negative sentiment from 90% to 16%.
4. **Evaluation**:
   - Measured the success of sentiment reduction techniques.
   - Achieved an 84% favorable response in ChatGPT evaluations.

## Results

- **Reduction in Negative Sentiment**: Successfully reduced negative sentiment from 90% to 16% through effective use of NLP techniques.
- **Favorable Response**: Improved overall sentiment, achieving an 84% favorable response rate.

## Visualizations

Visualizations created using Seaborn include:
- Distribution of sentiment scores before and after applying NLP techniques.
- Comparison of negative, neutral, and positive sentiments.

## How to Run the Project

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/sentiment-analysis-chatgpt.git
   cd sentiment-analysis-chatgpt
   ```

2. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Analysis**:
   ```bash
   python sentiment_analysis.py
   ```

4. **View Results**:
   - Sentiment analysis results will be displayed in the console.
   - Visualizations will be saved in the `output` directory.

## Conclusion

This project demonstrated the effectiveness of NLP techniques in analyzing and improving sentiment in ChatGPT feedback data. The significant reduction in negative sentiment and the high favorable response rate highlight the value of using tools like VADER for sentiment analysis.

## Future Work

- Explore additional NLP techniques, such as deep learning models for sentiment analysis.
- Extend the analysis to other forms of user feedback and interaction data.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

