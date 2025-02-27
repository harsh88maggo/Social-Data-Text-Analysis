## Overview

This project explores **text analysis techniques** applied to a dataset (`acq.csv`). The assignment focuses on:
- **Visualizing word and sentence structures** to uncover patterns in the data.
- **Comparing frequent words** before and after preprocessing to evaluate the effectiveness of data cleaning.
- **Extracting and visualizing the most common word pairs (bigrams)** and triplets (trigrams) to understand relationships between terms.

Through this analysis, we gain insights into social data, its inherent structures, and the significance of effective data preprocessing techniques.

## Preprocessing

The preprocessing pipeline enhances data quality and prepares it for meaningful analysis. The steps include:
- **Converting all text to lowercase** to standardize the data.
- **Removing tweet-specific elements** such as mentions, hashtags, and retweets.
- **Stripping out hyperlinks, punctuation, and newlines** to focus on meaningful words.
- **Eliminating common stopwords** using NLTK's stopword list to reduce noise and improve analysis.

## Visualizations

The following visualizations provide a clear picture of the text data's structure and frequency patterns:

1. **Histogram of Word Lengths:**  
   This histogram illustrates the distribution of word lengths, shedding light on the text's verbosity and structure.
   
2. **Histogram of Sentence Lengths:**  
   This visualization highlights how sentence lengths vary across the dataset, potentially revealing patterns in sentence complexity.

3. **Top Frequent Words (Before and After Preprocessing):**  
   Bar charts comparing the most frequent words before and after data cleaning help us understand the impact of preprocessing on the text's content.

4. **Top Frequent Bigrams:**  
   A bar chart visualizing the most common pairs of consecutive words, providing insights into common phrases or expressions.

5. **Top Frequent Trigrams:**  
   A bar chart of the most frequent triplets of consecutive words, helping to identify recurring word groupings or themes.

## Requirements

- **Python 3.x**  
- Libraries: `pandas`, `matplotlib`, `nltk`, `re`

To install the required dependencies, run the following command:
```bash
pip install pandas matplotlib nltk
```

## Prerequisites

Before running the notebook or script, ensure you have the necessary NLTK resources installed:

```python
import nltk
nltk.download('stopwords')
nltk.download('punkt')
```

## Running the Code

1. Place the dataset (`acq.csv`) in the project directory.
2. Open the provided Jupyter Notebook or run the Python script in your Python environment.

### What the Code Does:
- Reads and preprocesses the dataset to clean the text.
- Generates the required visualizations.
- Displays histograms and bar charts to analyze the dataset.

## Conclusion

This project demonstrates the power of text mining techniques in social data analysis. By effectively cleaning the dataset and visualizing key patterns, the project uncovers meaningful insights into word usage, sentence structure, and frequent term pairings. It emphasizes the importance of data preprocessing in extracting useful information from raw text data. The results highlight how simple yet powerful techniques can enhance the quality of text analysis and help derive actionable insights.
