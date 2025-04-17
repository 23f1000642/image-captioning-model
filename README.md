# Image Captioning Model

This repository contains:
- `my_caption_model.h5`: Trained Keras model for image captioning
- `tokenizer.pkl`: Tokenizer for preprocessing captions

## How to use

These files can be loaded in a Python environment for inference or further development.

## Example

import tensorflow as tf
import pickle

model = tf.keras.models.load_model('my_caption_model.h5')
with open('tokenizer.pkl', 'rb') as f:
tokenizer = pickle.load(f)