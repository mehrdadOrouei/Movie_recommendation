# Movie Recommendation NLP Project

This Python project utilizes Natural Language Processing (NLP) techniques to recommend movies based on user input. The system analyzes user preferences and suggests relevant movies from a dataset.

## Requirements

- Python 3.x
- Libraries:
  - NLTK (Natural Language Toolkit)
  - Pandas
  - Scikit-learn

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/mehrdadOrouei/Movie_recommendation/.git
   ```

2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

3. Download NLTK data:
   ```
   python -m nltk.downloader stopwords
   python -m nltk.downloader punkt
   ```

## Usage

1. Run the main script:
   ```
   python main.py
   ```

2. Follow the prompts to enter your preferences and get movie recommendations.

## Dataset

The project uses a dataset of movies with features such as title, genre, plot, etc. The dataset is preprocessed to extract relevant information for recommendation.

## Approach

1. **Data Preprocessing**: Clean and preprocess the dataset, extract features like genre, plot summary, etc.

2. **Text Vectorization**: Utilize techniques like TF-IDF to convert text data into numerical vectors.

3. **Recommendation Model**: Build a recommendation model using techniques such as cosine similarity or collaborative filtering to suggest movies based on user preferences.

## Contributors


- Mehrdad Orouei



 
