Text Emotion Detection Application

This project is a web-based application that detects emotions from textual input using a machine learning model. The application is built with Streamlit and provides predictions along with confidence scores and visual representation.

Live Application: https://erenemotion.streamlit.app

Features
Predicts emotion from user-provided text
Displays predicted emotion with an emoji
Shows confidence score of the prediction
Visualizes probability distribution of emotions
Technologies Used
Python
Streamlit
pandas
numpy
altair
scikit-learn
Project Structure
emotion_dataset_raw.csv #data
app.py                # Main application file
text_emotion.pkl     # Trained machine learning model
README.md            # Documentation
Installation and Setup
Clone the repository:
git clone https://github.com/your-username/emotion-detector.git
cd emotion-detector
Install required dependencies:
pip install -r requirements.txt
Run the application:
streamlit run app.py
Working Principle
The user inputs text into the application
The trained model processes the text
The application returns:
Predicted emotion
Confidence score
Probability distribution chart
Supported Emotions
Anger
Disgust
Fear
Happy
Joy
Neutral
Sad / Sadness
Shame
Surprise
Author

Navadeep Chunchu
B.Tech Data Science
