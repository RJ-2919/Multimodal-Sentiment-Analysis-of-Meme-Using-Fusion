# Multimodal Sentiment Analysis of Memes Using Fusion

## Overview
This project explores **Multimodal Sentiment Analysis (MMA)** by combining textual and visual data from memes to improve sentiment classification. The fusion of these modalities (image and text) enhances the model's ability to capture sentiment nuances.

Key components of the project:
- **Image Preprocessing**: Extract features from meme images.
- **Text Embeddings**: Obtain text embeddings using **GloVe**.
- **Fusion Models**: Evaluate early, late, and hybrid fusion strategies for sentiment analysis.

## Features
- Combines **image** and **text** modalities for multimodal learning.
- Implements preprocessing pipelines directly within the notebook.
- Uses GloVe for text representation and custom techniques for image processing.
- Achieves high accuracy using hybrid fusion methods.

## Project Workflow

### Prerequisites
Ensure the following libraries are installed:
- **NumPy**
- **Pandas**
- **TensorFlow** or **PyTorch** (depending on your fusion implementation)
- **Matplotlib**
- **spaCy**

Install them using:
```bash
pip install numpy pandas matplotlib spacy tensorflow
