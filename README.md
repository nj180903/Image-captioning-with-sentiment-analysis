# Image-captioning-with-sentiment-analysis

This project leverages the Flickr8k dataset to generate image captions enriched with sentiment analysis. Using DenseNet201 for feature extraction and LSTM for sequence generation, the model generates human-like descriptions of images. Additionally, it integrates sentiment analysis to produce sentiment-rich captions that reflect the emotional tone of the scene. The project combines the power of deep learning for image captioning with Natural Language Processing (NLP) tools like TextBlob for sentiment analysis.

Features:
Image Captioning: DenseNet201 extracts features from images, while LSTM generates descriptive captions.
Sentiment Analysis: Integrates NLP techniques with TextBlob to provide sentiment-based insights for each image caption.
End-to-End Model: A complete pipeline from image input to caption generation and sentiment analysis.
Tech Stack:
Python
TensorFlow
Keras
DenseNet201 (for feature extraction)
LSTM (for sequence generation)
TextBlob (for sentiment analysis)
NLP (Natural Language Processing)
Dataset:
The Flickr8k dataset contains over 8,000 images, each paired with multiple captions. This project uses the dataset for training and testing the model.
