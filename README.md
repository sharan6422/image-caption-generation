# Image Caption Generation using CNN + LSTM

## Overview
An image captioning project that combines Convolutional Neural Networks (CNNs) and Long Short-Term Memory (LSTM) networks to generate natural-language descriptions of images.

## Architecture
- **CNN Encoder:** ResNet50 extracts visual features from input images.
- **LSTM Decoder:** Generates captions sequentially using extracted image features.

## Dataset
Flickr8k — approximately 8,000 images with five human-written captions per image.

## Technologies
- Python
- PyTorch
- Torchvision
- NumPy
- Pandas
- NLTK
- Matplotlib

## Project Structure

```text
image-caption-generation/
├── data/
├── models/
├── utils/
├── requirements.txt
└── README.md
```

## Planned Implementation
- Dataset exploration and preprocessing
- Caption tokenisation and vocabulary creation
- ResNet50 CNN encoder
- LSTM caption decoder
- Model training and inference
- BLEU score evaluation

## Project Status
Initial project setup. Implementation and experimentation are planned.

## Future Improvements
- Attention mechanism
- Beam search decoding
- Improved caption generation quality
- Model evaluation and visualisation