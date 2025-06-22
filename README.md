# 🌿 AyurZenith: Medicinal Plant Identification Using Image Classification

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-ResNet50-orange)
![Colab](https://img.shields.io/badge/Platform-Google%20Colab-yellow)
![License](https://img.shields.io/badge/License-MIT-green)



## 🔍 Objective

**AyurZenith** leverages deep learning to identify medicinal plants using real-time webcam input or uploaded images. This solution is powered by a **ResNet-50** convolutional neural network model, trained on thousands of medicinal plant images.



## ✨ Features

- ✅ **Pre-trained ResNet-50 Backbone** (on ImageNet)
- 📷 **Live Webcam Support** (via JavaScript + OpenCV in Colab)
- 🧠 **6000+ Images Used for Training**
- 🔄 **Data Augmentation** via `ImageDataGenerator`
- 📊 **Real-time Classification Overlay** on Frames
- ⚙️ Designed to run on **Google Colab**



## 🎯 Target Users

- 👨‍🔬 Scientists & researchers
- 🌿 Botanists & biologists
- 📚 Students & educators
- 💊 Pharmaceutical professionals



## 🛠️ How to Run

### 🔗 [Click here to open in Google Colab](https://colab.research.google.com/)

1. **Clone the repository or upload the `.ipynb` notebook to Colab**  
2. **Upload your dataset folder** (named `Training_dataset11`) containing subfolders for each plant class
3. **Run all cells** — The notebook will:
   - Install dependencies
   - Load and preprocess the dataset
   - Train the model using ResNet-50
   - Launch a webcam interface for real-time predictions




## ⚙️ Model Details

- **Base Model**: ResNet-50 (with ImageNet weights)
- **Image Size**: 128x128
- **Loss Function**: Sparse Categorical Crossentropy
- **Optimizer**: Adam (`lr=0.001`)
- **Epochs**: 5 (configurable)
- **Augmentation**: Rotation, shift, shear, zoom, flip



## 📸 Webcam Output

The webcam captures live frames, preprocesses them to 128x128, runs inference using the trained model, and displays the predicted plant name directly on the frame.





## 🧪 Example Use Cases

- Educational botany fieldwork demo
- Real-time medicinal plant identification in labs
- Assistance for ayurvedic pharmaceutical sourcing



## 📝 License

MIT License – free to use and modify.  
Please attribute the original authors for any public reuse.



