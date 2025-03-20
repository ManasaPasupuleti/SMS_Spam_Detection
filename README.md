# SMS SPAM DETECTION 
SMS SPAM DETECTION is a machine learning project for SMS spam detection in multiple languages. The project includes models for English, German, and French SMS messages. The models are trained using neural networks with natural language processing techniques.

# Introduction
This project aims to create an SMS spam detection model that supports three languages: English, French, and German. The model uses an Artificial Neural Network (ANN) to classify messages as spam or ham. A Flask-based web interface allows users to input messages and get instant classification results. The project highlights the importance of handling multilingual data and ensuring accurate classification.

# Technologies Used
The project is built using Python for the backend, with the ANN model developed using TensorFlow/Keras. For natural language processing tasks like tokenization and text cleaning, NLTK and Scikit-learn are used. The model is deployed using Flask, and the interface is designed using HTML/CSS.

# Model Architecture
The ANN model consists of an input layer for text embeddings, multiple hidden layers with ReLU activation, and a sigmoid output layer for binary classification. The architecture is optimized for quick processing and high accuracy across different languages.

# Features
The project supports spam detection in three languages and provides a clean, responsive interface for user interaction. The model processes input messages in real time and returns classification results instantly. Error handling and input validation are integrated for a smooth user experience.

# Results
The model achieves around 95% accuracy with strong performance in precision, recall, and F1-score. The results indicate that the model can generalize well across different languages and handle variations in spam message patterns.

🔍 Challenges & Solutions
Handling multilingual data was challenging due to language-specific variations. This was addressed by language-based tokenization and encoding. Reducing false positives was another issue, tackled by adjusting the learning rate and adding dropout layers to prevent overfitting.

🔮 Future Improvements
Future work includes adding support for more languages, improving accuracy with transformer models, and building a mobile-friendly interface. Enhancing the model’s ability to handle slang and abbreviations is also a key improvement area.

📝 License
This project is licensed under the MIT License, allowing open-source contributions and modifications.
