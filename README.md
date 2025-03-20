# SMS SPAM DETECTION 
SMS SPAM DETECTION is a machine learning project for SMS spam detection in multiple languages. The project includes models for English, German, and French SMS messages. The models are trained using neural networks with natural language processing techniques.

# Introduction
This project focuses on building a "multilingual SMS spam detection model" capable of handling messages in "English, French, and German". Spam messages are a major concern in modern communication, as they can lead to privacy breaches, scams, and unwanted disruptions. The objective of this project is to develop an efficient model using an "Artificial Neural Network (ANN)" to classify messages as spam or ham. The model is designed to work across multiple languages, providing accurate results regardless of language-specific differences. The project includes a "Flask-based web interface" that allows users to input text and receive instant feedback on whether the message is spam. By leveraging advanced natural language processing (NLP) techniques and deep learning, this project demonstrates how AI can enhance communication security.

# Technologies Used
The project is built primarily using "Python". The core model is designed using the "TensorFlow/Keras" framework, which provides flexibility and scalability for building and training neural networks. For text processing, the project relies on "NLTK" for tokenization, stemming, and stopword removal. "Scikit-learn" is used for encoding and model evaluation. Flask serves as the web framework for deploying the model, and the interface is created using "HTML" and "CSS" for a user-friendly experience. The combination of these technologies ensures that the model is accurate, fast, and responsive.

# Model Architecture
The model is designed as a feedforward artificial neural network (ANN) consisting of multiple layers:
1. Input Layer: Accepts tokenized text data as numerical embeddings.
2. Hidden Layers:
   - Dense layers with ReLU activation functions to capture non-linear relationships.
   - Dropout layers to prevent overfitting and improve generalization.
3. Output Layer: A single neuron with a sigmoid activation function that outputs a value between 0 and 1, representing the probability of a message being spam.
The model is compiled using the Adam optimizer with a binary cross-entropy loss function. Early stopping and learning rate adjustments are used to improve training efficiency.

# Features
This project comes with several key features:

- Multilingual Support: The model handles messages in English, French, and German, enhancing its versatility.
- Real-Time Detection: The Flask app allows users to input messages and receive instant classification results.
- User-Friendly Interface: The HTML interface is designed for ease of use, with a clean layout and clear feedback.
- Secure Processing: Input sanitization and secure handling of user data are incorporated to protect user privacy.

# Results
The ANN model achieves impressive results in terms of accuracy and reliability:
Accuracy: ~95%
Precision: ~93%
Recall: ~92%
F1-Score: ~92%
The model performs consistently well across different languages and handles both short and long messages effectively. False positives and false negatives are minimized through data augmentation and fine-tuning of model parameters.
