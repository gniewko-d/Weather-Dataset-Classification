# 🌦️ Weather Dataset Classification using CNN

This project implements a Convolutional Neural Network (CNN) using TensorFlow and Keras to classify weather conditions from images. It is designed to recognize categories such as **cloudy**, **foggy**, **rainy**, and **sunny** based on image input.

## 📁 Dataset Structure

The dataset should be organized into training and testing directories, with each class in its own subfolder:

dataset/
│
├── train/
│ ├── cloudy/
│ ├── foggy/
│ ├── rainy/
│ └── sunny/
│
└── test/
├── cloudy/
├── foggy/
├── rainy/
└── sunny/

markdown
Kopiuj
Edytuj

## 🧠 Model Overview

The CNN architecture consists of:

- Convolutional layers with ReLU activation
- MaxPooling layers to reduce spatial dimensions
- Fully connected (Dense) layers
- A final Softmax layer for multi-class classification

The model is trained using categorical cross-entropy loss and the Adam optimizer.

## 🔧 Features

- ✅ Custom CNN architecture for image classification
- ✅ Image augmentation using `ImageDataGenerator`
- ✅ Real-time training and validation accuracy/loss visualization
- ✅ Evaluation on unseen test data
- ✅ Easily extendable for additional weather categories

## 📊 Results

The model demonstrates effective performance in distinguishing between different weather conditions. Accuracy and loss curves are plotted to monitor training progress and detect overfitting.

## 🚀 Getting Started

### Prerequisites

Install required packages using pip:

```bash
pip install tensorflow matplotlib numpy
Running the Notebook
Clone this repository:

bash
git clone https://github.com/your-username/weather-classification-cnn.git
cd weather-classification-cnn
Place your dataset inside the dataset/ folder.

Open and run the Weather_Dataset_Classification.ipynb notebook:

bash
jupyter notebook Weather_Dataset_Classification.ipynb
📌 Future Improvements
Incorporate transfer learning with pretrained models (e.g., ResNet, VGG)

Deploy model using a web interface (e.g., Streamlit or Flask)

Add support for more diverse weather categories

📄 License
This project is open-source and available under the MIT License.

👤 Author
Gniewosz Drwięga -
gniewko4@gmail.com
