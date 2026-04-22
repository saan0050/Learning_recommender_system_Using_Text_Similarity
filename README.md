#  Learning Recommender System Using Text Similarity  

A Python-based intelligent recommendation system that retrieves relevant learning content from predefined modules and recommends the top **3 most suitable modules** based on user input.

It leverages **Natural Language Processing (NLP)** and **text similarity techniques** to match user interests with the most appropriate learning resources.

---

##  Features  

- **Smart Course Recommendations**  
  Suggests relevant courses based on user input using text similarity  

- **NLP-Based Processing**  
  Includes tokenization, stopword removal, lemmatization, and POS tagging  

- **TF-IDF Vectorization**  
  Converts text data into numerical form for similarity comparison  

- **Cosine Similarity Matching**  
  Finds the most relevant courses based on similarity scores  

- **Predefined Course Dataset**  
  Includes curated AI, ML, and NLP-related courses  

---

## Technologies Used  

- Python  
- NLTK (Natural Language Toolkit)  
- spaCy  
- Scikit-learn  
- NumPy  
- Pandas  

---
## Project Structure  
learning-recommender/
│
├── learning_recommender.py # Main Python script
└── README.md # Project documentation

---

## How It Works  

1. User provides input (skills, interests, or query text)  
2. Text is preprocessed using NLP techniques  
3. TF-IDF converts text into vectors  
4. Cosine similarity compares user input with course descriptions  
5. Top 3 matching courses are recommended  

---
## Example Use Case  

**Input:**  
I want to learn deep learning and neural networks

**Output:**  
Recommended Courses:

Deep Learning and Neural Networks
Machine Learning Basics
Introduction to AI

---

## Note  

- Ensure NLTK datasets are downloaded during execution  
- Internet may be required initially for model downloads  

---

##  License  

This project is open-source and free to use for educational purposes.
