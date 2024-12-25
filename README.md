# gestureRecognitionCNN
This project is a gesture recognition model that classifies English alphabets using sign language. The model is implemented using a Convolutional Neural Network (CNN) on Google Colab. The dataset used for training and evaluation was sourced from Kaggle, and both the dataset and the trained model are stored in Google Drive.
# Requirements

Google Colab account

Google Drive access

Python 3.x

TensorFlow

Keras

OpenCV

NumPy

Matplotlib

Pandas

Seaborn

# How to Run

Clone this repository:

```ruby
git clone https://github.com/yourusername/gesture-recognition
```

Open Google Colab and upload the notebook.

Mount Google Drive in Colab:

from google.colab import drive
drive.mount('/content/drive')

Load the trained model:

import pickle
with open('/content/drive/MyDrive/path_to_model/cnn_model.pkl', 'rb') as f:
    model = pickle.load(f)

