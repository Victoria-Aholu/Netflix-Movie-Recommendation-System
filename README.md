# Netflix-Movie-Recommendation-System

A content-based movie recommender using TF-IDF and cosine similarity, built in Python and runnable on Google Colab.

## Try it on Google Colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1YUrY3KMrxW4gjJogMQazLIDfo4_3n15-#scrollTo=viqvehltY2ru)

## Files

- `netflix_recommender.ipynb`: Colab notebook
- `netflix_titles.csv`: Movie metadata (from Kaggle)

## How It Works

1. Load movie descriptions.
2. Convert text to numerical vectors with TF-IDF.
3. Measure movie similarity using cosine similarity.
4. Return top 5 similar titles.

## Sample Output

```python
Recommendations for 'Sherlock Holmes':
0    Jack Taylor
1    Midsomer Murders
2         Marcella
3         River
4    Hinterland
