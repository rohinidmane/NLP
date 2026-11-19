# 🎬 IMDB Movie Reviews – Text Preprocessing in NLP

This project focuses on text preprocessing techniques using the IMDB Dataset of 50K Movie Reviews. It demonstrates how to clean raw movie reviews and prepare textual data for Natural Language Processing (NLP) and Machine Learning tasks using Python.

## 📊 What This Project Does

- Downloads the IMDB Movie Reviews dataset using KaggleHub.
- Loads the dataset into a Pandas DataFrame.
- Explores dataset information and dimensions.
- Converts reviews into lowercase.
- Identifies and removes duplicate records.
- Removes HTML tags from reviews.
- Removes URLs from text.
- Removes punctuation marks.
- Expands common chat words and abbreviations.
- Explores spelling correction using TextBlob.
- Removes English stopwords using NLTK.

## 🔄 NLP Text Preprocessing Workflow

Download Dataset  
        ⬇  
Load Dataset using Pandas  
        ⬇  
Dataset Exploration  
        ⬇  
Convert Text to Lowercase  
        ⬇  
Remove Duplicate Records  
        ⬇ 
Remove HTML Tags  
        ⬇  
Remove URLs  
        ⬇ 
Remove Punctuation  
        ⬇  
Chat Words Conversion  
        ⬇
Spelling Correction  
        ⬇  
Stopwords Removal  
        ⬇ 
Cleaned Movie Reviews

## 📊 Dataset Information

- **Dataset Name:** IMDB Dataset of 50K Movie Reviews
- **Source:** Kaggle
- **Dataset ID:** `lakshmi25npathi/imdb-dataset-of-50k-movie-reviews`
- **File Name:** `IMDB Dataset.csv`
- **Main Text Column:** `review`

The dataset contains movie reviews that are used to practice different text preprocessing techniques.

## 🧠 Key Concepts Covered

### 1. Dataset Download and Loading
- Downloading the IMDB dataset using `kagglehub.dataset_download()`.
- Loading CSV files using `pd.read_csv()`.
- Exploring data using `head()`, `info()`, and `shape`.
- Accessing individual movie reviews.

### 2. Lowercase Conversion
- Converting all reviews into lowercase using `str.lower()`.
- Maintaining consistency in textual data.

### 3. Duplicate Removal
- Identifying duplicate records using `duplicated().sum()`.
- Removing duplicate rows using `drop_duplicates()`.

### 4. HTML Tags Removal
- Using Regular Expressions to identify HTML tags.
- Creating a reusable `remove_html_tags()` function.
- Removing HTML tags using `re.sub()`.

### 5. URL Removal
- Identifying URLs beginning with `http`, `https`, or `www`.
- Creating a reusable `remove_url()` function.
- Removing URLs using Regex.

### 6. Punctuation Removal
- Using Python's `string` module.
- Accessing punctuation characters using `string.punctuation`.
- Creating a reusable `remove_punc()` function.
- Removing punctuation marks using string replacement.

### 7. Chat Words Removal / Conversion
- Understanding common chat abbreviations such as LOL, IDK, BRB, ASAP, and FYI.
- Creating a dictionary containing chat words and their expanded forms.
- Converting abbreviations into meaningful full forms using `chat_conv()`.

### 8. Incorrect Spelling Correction
- Exploring spelling correction using the TextBlob library.
- Using `TextBlob` to identify and correct incorrectly spelled words.

### 9. Stopwords Removal
- Understanding common English stopwords.
- Importing stopwords from `nltk.corpus`.
- Downloading the required NLTK stopwords resource.
- Practicing stopword removal using a custom function.

## 🛠️ Tech Stack

- **Python** – Programming language
- **Pandas** – Dataset loading and manipulation
- **KaggleHub** – Dataset downloading
- **NLTK** – Stopwords processing
- **Regex (re)** – HTML tags and URL removal
- **TextBlob** – Spelling correction
- **String** – Punctuation handling

## 📈 NLP Operations Performed

| Operation             | Function / Library             | Purpose                          |
|-----------------------|--------------------------------|----------------------------------|
| Dataset Download      | `kagglehub.dataset_download()` | Downloads the IMDB dataset       |
| Dataset Loading       | `pd.read_csv()`                | Loads CSV data                   |
| Dataset Information   | `df.info()`                    | Displays dataset information     |
| Dataset Shape         | `df.shape`                     | Returns rows and columns         |
| Lowercase Conversion  | `str.lower()`                  | Converts reviews to lowercase    |
| Duplicate Detection   | `duplicated()`                 | Identifies duplicate records     |
| Duplicate Removal     | `drop_duplicates()`            | Removes duplicate rows           |
| HTML Removal          | `re.sub()`                     | Removes HTML tags                |
| URL Removal           | `re.sub()`                     | Removes URLs                     |
| Punctuation Removal   | `string.punctuation`           | Removes punctuation marks        |
| Chat Words Conversion | `chat_conv()`                  | Expands chat abbreviations       |
| Spelling Correction   | `TextBlob()`                   | Corrects spelling mistakes       |
| Stopwords Removal     | `stopwords.words()`            | Removes common English stopwords |

## 💡 Key Learnings

1. Learned how to download datasets using KaggleHub.
2. Practiced loading and exploring datasets using Pandas.
3. Understood the importance of lowercase conversion and duplicate removal.
4. Learned how to remove HTML tags and URLs using Regex.
5. Practiced punctuation removal using Python's String module.
6. Learned how to expand common chat abbreviations.
7. Explored spelling correction using TextBlob.
8. Understood stopwords and their removal using NLTK.
9. Learned how text preprocessing helps prepare movie reviews for NLP tasks.

## 📁 Project Structure

```text
IMDB_Text_Preprocessing/
│
├── IMDB_Text_Preprocessing.ipynb
└── README.md
```

## 🚀 Future Improvements

- Apply tokenization to cleaned movie reviews.
- Perform stemming and lemmatization.
- Explore Bag of Words and TF-IDF.
- Perform sentiment analysis on movie reviews.
- Build a Machine Learning model to classify positive and negative reviews.