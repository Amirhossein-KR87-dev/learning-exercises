# HODA Digit Classification

A simple Deep Learning practice using TensorFlow/Keras for handwritten digit classification.

## Model

14x14 → Flatten → Dense(64) → Dropout(0.2) → Dense(10)

## Dataset

HODA handwritten Persian digit dataset.

I used 5000 samples and resized the images to 14x14.

## Requirements

```bash
pip install -r requirements.txt