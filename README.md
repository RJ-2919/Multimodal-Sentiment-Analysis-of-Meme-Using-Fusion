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

### Dataset
This project uses a subset of the **Facebook Hateful Meme Dataset** (600 samples for feasibility in Colab). Ensure the following:
- Meme images are stored in a folder (e.g., `images/`).
- Text labels and captions are in a structured `.csv` file.
- Update file paths in the notebook as needed to match your local directory structure.

### Steps in the Notebook
1. **Image Preprocessing**:
   - Load, resize, and normalize images for model input.
2. **Text Preprocessing**:
   - Tokenize text.
   - Convert to GloVe embeddings.
3. **Fusion Techniques**:
   - Implement **early**, **late**, and **hybrid fusion** directly within the notebook.
4. **Model Training**:
   - Train models using fusion approaches.
   - Evaluate the models using metrics like accuracy, precision, recall, and F1-score.

### Results
The **hybrid fusion model** outperformed other methods:
- **Accuracy**: 92.08%
- **F1-Score**: 0.92

This approach effectively balances the strengths of text and image modalities for sentiment analysis.

### Usage
To run the project:
1. Open the notebook in Colab or Jupyter.
2. Update dataset paths to point to your local dataset.
3. Execute the cells sequentially to preprocess data, train the models, and visualize results.

### Limitations
- Limited to a small dataset subset due to resource constraints.
- Requires further generalization to unseen data.

### Future Work
- Expanding the dataset for better model performance.
- Exploring transformer-based architectures like **CLIP** or **VisualBERT** for advanced multimodal sentiment analysis.
- Incorporating additional modalities like audio for enriched sentiment understanding.

