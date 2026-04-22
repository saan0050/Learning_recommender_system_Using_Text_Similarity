# Learning_recommender_system_Using_Text_Similarity
Helps to retrieve the content required by user from the listed modules and recommend 3 modules.
Using Text Similarity & NLP.

It isPython-based intelligent recommendation system that suggests relevant learning content based on user input. It leverages Natural Language Processing (NLP) and text similarity techniques to match user interests with the most suitable courses.

# Features
Smart Course Recommendations
   Suggests relevant courses based on user input using text similarity
NLP-Based Processing
   Includes tokenization, stopword removal, lemmatization, and POS tagging
TF-IDF Vectorization
   Converts text data into numerical form for similarity comparison
Cosine Similarity Matching
   Finds the most relevant courses based on similarity scores
Predefined Course Dataset
   Includes curated AI, ML, and NLP-related courses

#Technologies Used
Python
NLTK (Natural Language Toolkit)
spaCy
Scikit-learn
NumPy & Pandas

#Project Structure
learning-recommender/
│
├── learning_recommender.py   # Main Python script
└── README.md                 # Project documentation

#How It Works
User provides input (skills, interests, or query text)
Text is preprocessed using NLP techniques
TF-IDF converts text into vectors
Cosine similarity compares user input with course descriptions
Top matching courses are recommended

#Example Use Case

Input:
"I want to learn deep learning and neural networks"

Output:
Recommended Courses:
- Deep Learning and Neural Networks
- Machine Learning Basics
Note
Make sure NLTK datasets are downloaded automatically during execution
Internet may be required initially for model downloads
📜 License

This project is open-source and free to use for educational purposes.
