# Kuzushiji-MNIST-CNN

Convolutional Neural Network for recognizing handwritten Japanese characters from the Kuzushiji dataset family (KMNIST, K49, Kanji).  
Includes automated dataset download, preprocessing, training, and model export for easy experimentation.


##  Features:
- **Automatic dataset download** (Kuzushiji-MNIST by default)
- **Data preprocessing** (normalization, reshaping, one-hot encoding)
- **Deep CNN architecture** with Dropout and EarlyStopping
- **Train & Evaluate** models with a single command
- **Model export** to .h5 format for later use
  

## Datasets Supported:
1. **Kuzushiji-MNIST** – 10 Hiragana classes, 28×28 images  
2. **Kuzushiji-49** – 49 Hiragana and Kanji classes, 28×28 images *(optional)*  
3. **Kuzushiji-Kanji** – 3832 Kanji classes, 64×64 images *(optional, heavy)*  



###  Clone the Repository:
```bash
git clone https://github.com/yourusername/kuzushiji-cnn.git
cd kuzushiji-cnn
