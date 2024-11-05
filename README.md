# Machine-Learning
This repository contains the following projects:
1. Fruit Classifier

### 1. Fruit Classifier
This project is in `train_fruit.ipynb`. A small convolutional neural network (MobileNetV3) was fine-tuned to perform fruit classification. Quantization is used to keep the model size small. The fine-tuned model is exported to `tflite` format to be small and easily implemented into a mobile app. Similar model was trained on a diffeent dataset to perform ripeness classification for certain fruits as well.
