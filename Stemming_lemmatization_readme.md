# 📝 Text Preprocessing in NLP

This project covers basic Natural Language Processing (NLP) text preprocessing techniques using Python. It demonstrates tokenization, stemming, lemmatization, and text cleaning using Regular Expressions (Regex).

## 📊 What This Project Does

- Tokenizes sentences into individual words.
- Performs stemming using Porter Stemmer.
- Performs lemmatization using WordNet Lemmatizer.
- Understands Part-of-Speech (POS) concepts.
- Converts text into lowercase.
- Removes special characters, numbers, and punctuation using Regex.
- Removes extra spaces from cleaned text.

## 🔄 NLP Text Preprocessing Workflow

Input Text  
    ⬇
Tokenization  
    ⬇  
Stemming  
    ⬇  
Lemmatization  
    ⬇  
Lowercase Conversion  
    ⬇  
Special Character Removal  
    ⬇  
Whitespace Cleaning  
    ⬇  
Cleaned Text

## 📊 Dataset Information

- **Input:** Sample English sentences.
- **Text Example:** "The runners were running in a race and they ran very fast."
- **Dataset:** No external dataset used. Sample text is directly provided in the code.

## 🧠 Key Concepts Covered

### 1. Tokenization
- Splitting sentences into individual words using `word_tokenize()`.
- Converting text into smaller units called tokens.
- Downloading the required NLTK tokenizer resources.

### 2. Stemming
- Reducing words to their root or stem form.
- Using `PorterStemmer()` from NLTK.
- Applying stemming to each word using list comprehension.
- Using `stemmer.stem()` to obtain the stem of a word.

### 3. Lemmatization
- Reducing words to their meaningful dictionary base forms.
- Using `WordNetLemmatizer()` from NLTK.
- Applying lemmatization with the verb (`v`) POS parameter.
- Downloading WordNet and other required NLTK resources.

### 4. Part-of-Speech (POS) Tagging
- Understanding grammatical categories assigned to words.
- Learning about nouns, verbs, adjectives, and other parts of speech.
- Understanding how POS information helps in lemmatization.

### 5. Handling Special Characters
- Using Python's `re` module for text cleaning.
- Removing special characters, numbers, and punctuation.
- Keeping lowercase English letters and spaces.

### 6. Lowercase Conversion
- Converting text into lowercase using `lower()`.
- Maintaining consistency in text data.

### 7. Whitespace Cleaning
- Removing leading and trailing spaces using `strip()`.
- Replacing multiple spaces with a single space using Regex.

## 🛠️ Tech Stack

- **Python** – Programming language
- **NLTK** – Tokenization, stemming, and lemmatization
- **Regex (re)** – Text cleaning

## 📈 NLP Operations Performed

| Operation | Function / Library | Purpose |
|---|---|---|
| Tokenization | `word_tokenize()` | Splits text into individual words |
| Stemming | `PorterStemmer()` | Reduces words to stems |
| Lemmatization | `WordNetLemmatizer()` | Converts words into dictionary base forms |
| POS Parameter | `pos='v'` | Specifies verb-based lemmatization |
| Lowercase Conversion | `lower()` | Converts text into lowercase |
| Special Character Removal | `re.sub()` | Removes unwanted characters |
| Whitespace Removal | `strip()` | Removes leading and trailing spaces |
| Extra Space Removal | `re.sub(r'\s+', ' ', text)` | Replaces multiple spaces with one |

## 💡 Key Learnings

1. Learned the basics of text preprocessing in NLP.
2. Understood how tokenization splits sentences into words.
3. Practiced stemming using Porter Stemmer.
4. Learned lemmatization using WordNet Lemmatizer.
5. Understood the role of POS information in lemmatization.
6. Practiced lowercase conversion and special character removal.
7. Learned how to clean text using Regular Expressions.
8. Understood how text preprocessing prepares data for further NLP tasks.

## 📁 Project Structure

```
NLP_Text_Preprocessing/
│
├── NLP_Text_Preprocessing.ipynb
└── README.md
```

## 🚀 Future Improvements

- Explore different stemming algorithms.
- Perform POS tagging using NLTK.
- Remove stopwords from text.
- Apply text preprocessing to a real-world dataset.
- Explore Bag of Words and TF-IDF techniques.