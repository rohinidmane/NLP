# 🧠 Word Embeddings using Word2Vec, GloVe, and FastText

This project explores pre-trained word embedding models using Python and Gensim. It demonstrates how words are represented as numerical vectors and how different embedding models capture semantic relationships between words. The project covers Word2Vec, GloVe, and FastText along with similarity, distance, and word analogy operations.

## 📊 What This Project Does

- Installs and imports the Gensim library.
- Explores available pre-trained embedding models.
- Loads Word2Vec, GloVe, and FastText models.
- Finds similar words using pre-trained embeddings.
- Calculates semantic similarity between words.
- Measures the distance between word vectors.
- Performs word analogy operations.
- Compares the characteristics of different embedding models.

## 🔄 Word Embeddings Workflow

Install Gensim  
        ⬇  
Import Gensim Downloader  
        ⬇  
Explore Available Pre-trained Models  
        ⬇  
Load Word2Vec, GloVe, and FastText  
        ⬇  
Find Similar Words  
        ⬇  
Calculate Word Similarity and Distance  
        ⬇  
Perform Word Analogies  
        ⬇ 
Compare Embedding Models

## 📊 Model Information

This project uses three pre-trained word embedding models:

| Model    | Pre-trained Model Name            | Vector Dimensions |
|----------|-----------------------------------|-------------------|
| Word2Vec | `word2vec-google-news-300`        | 300               |
| GloVe    | `glove-twitter-50`                | 50                |
| FastText | `fasttext-wiki-news-subwords-300` | 300               |

**Models Overview:**

- **Word2Vec:** Learns word representations by predicting words from their surrounding context.
- **GloVe:** Learns word representations using global word co-occurrence statistics.
- **FastText:** Represents words using character-level n-grams, helping it handle unseen and misspelled words.

## 🧠 Key Concepts Covered

### 1. Gensim Library
- Installing and upgrading Gensim.
- Importing `gensim.downloader`.
- Exploring available pre-trained models using `api.info()`.
- Displaying model names, record counts, and descriptions.

### 2. Loading Pre-trained Models
- Loading Word2Vec using `api.load()`.
- Loading GloVe using `api.load()`.
- Loading FastText using `api.load()`.
- Understanding pre-trained word embedding models.

### 3. Word2Vec
- Understanding how Word2Vec learns word meanings from surrounding context.
- Finding similar words using `most_similar()`.
- Calculating similarity between words using `similarity()`.
- Exploring semantic relationships between words.
- Understanding the limitation of Word2Vec with unseen words.

### 4. GloVe
- Understanding how GloVe captures semantic relationships using word co-occurrence statistics.
- Finding similar words using `most_similar()`.
- Calculating word distance using `distance()`.
- Exploring relationships between words such as tea and pea.

### 5. FastText
- Understanding character-level n-grams.
- Learning how FastText represents words using subword information.
- Finding similar words using `most_similar()`.
- Calculating distance between word vectors.
- Understanding how FastText handles unseen words and variations.

### 6. Word Similarity
- Calculating semantic similarity using `similarity()`.
- Understanding how similarity scores indicate relationships between word vectors.
- Comparing words such as Python and Java or coffee and tea.

### 7. Word Distance
- Calculating the distance between word vectors using `distance()`.
- Understanding how vector distance represents differences between word embeddings.

### 8. Word Analogies
- Exploring relationships between words using positive and negative word combinations.
- Using `most_similar()` for word analogy tasks.
- Using `most_similar_cosmul()` for analogy-based similarity calculations.
- Practicing examples such as king, woman, and man.

## 🛠️ Tech Stack

- **Python** – Programming language
- **Gensim** – Word embedding models
- **Word2Vec** – Context-based word embeddings
- **GloVe** – Global word co-occurrence embeddings
- **FastText** – Subword-based word embeddings

## 📈 NLP Operations Performed

| Operation                     | Function               | Purpose                                  |
|-------------------------------|------------------------|------------------------------------------|
| Model Exploration             | `api.info()`           | Displays available pre-trained models    |
| Model Loading                 | `api.load()`           | Loads pre-trained embeddings             |
| Similar Words                 | `most_similar()`       | Finds semantically related words         |
| Word Similarity               | `similarity()`         | Calculates similarity between two words  |
| Word Distance                 | `distance()`           | Calculates distance between word vectors |
| Word Analogies                | `most_similar()`       | Performs word relationship operations    |
| Cosine Multiplicative Analogy | `most_similar_cosmul()`| Finds words based on positive and negative relationships |

## 💡 Key Learnings

1. Learned the basics of word embeddings in NLP.
2. Understood how words are represented as numerical vectors.
3. Explored pre-trained Word2Vec, GloVe, and FastText models.
4. Learned how Word2Vec captures word relationships using surrounding context.
5. Understood how GloVe uses global word co-occurrence statistics.
6. Learned how FastText uses character n-grams to represent words.
7. Practiced finding similar words using `most_similar()`.
8. Calculated word similarity and distance between embeddings.
9. Explored word analogies using positive and negative word combinations.
10. Understood the differences and applications of different word embedding models.

## 📁 Project Structure

```
Word_Embeddings/
│
├── Word_Embeddings.ipynb
└── README.md
```

## 🚀 Future Improvements

- Train a custom Word2Vec model on a text dataset.
- Compare CBOW and Skip-gram architectures.
- Visualize word embeddings using PCA and t-SNE.
- Explore sentence embeddings.
- Apply word embeddings to sentiment analysis.
- Compare pre-trained embeddings on real-world NLP tasks.