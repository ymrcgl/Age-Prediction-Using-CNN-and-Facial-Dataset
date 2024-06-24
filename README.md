# Age-Prediction-Using-CNN-and-UTKFace-Dataset


## Overview
This project aims to develop a deep learning model to estimate age from facial images using the UTKFace dataset. It was developed and hosted on Kaggle for easy access and collaboration.

## Project Stages

### Data Preparation
1. **Data Collection**: UTKFace dataset contains 23,678 images with age labels ranging from 0 to 116 years. The dataset can be accessed [here](https://www.kaggle.com/jangedoo/utkface-new).
2. **Preprocessing**: Images are resized and normalized.
3. **Labeling**: Each image is labeled with the corresponding age.

### Model Development
1. **Model Selection**: A Convolutional Neural Network (CNN) is used for its efficiency in image processing tasks.
2. **Network Architecture**: The model includes convolutional layers, pooling layers, fully connected layers, dropout, and activation functions.

### Training
1. **Training Process**: The model is trained with the UTKFace dataset, split into training and validation sets.
2. **Optimization**: Algorithms like Adam or SGD are used to update model parameters.

### Evaluation
1. **Performance Metrics**: The model is evaluated using Mean Absolute Error (MAE).
2. **Visualization**: Predicted vs. actual ages are visualized to assess performance.

## Key Findings
- **Model Accuracy**: Reasonable accuracy is achieved on both training and new images.
- **Epochs and Data Size**: Increasing epochs can improve learning but risks overfitting. More data generally improves accuracy and generalization.

## Conclusion
Balancing epochs and dataset size is crucial. Techniques like early stopping and data augmentation can enhance performance.




# Turkish Version

# UTKFace Veri Seti Kullanarak Yaş Tahmini

## Genel Bakış
Bu proje, UTKFace veri setini kullanarak yüz görüntülerinden yaş tahmini yapabilen bir derin öğrenme modeli geliştirmeyi amaçlamaktadır. Proje, dataya kolay erişim için Kaggle'da geliştirilmiştir

## Proje Aşamaları

### Veri Hazırlama
1. **Veri Toplama**: UTKFace veri seti, 0-116 yaş aralığında etiketlenmiş 23,678 görüntü içermektedir. Veri setine [buradan](https://www.kaggle.com/datasets/jangedoo/utkface-new) ulaşabilirsiniz.
2. **Ön İşleme**: Görüntüler yeniden boyutlandırılır ve normalleştirilir.
3. **Etiketleme**: Her görüntü, karşılık gelen yaş etiketi ile etiketlenir.

### Model Geliştirme
1. **Model Seçimi**: Görüntü işleme görevlerinde verimli olan Konvolüsyonel Sinir Ağı (CNN) kullanılır.
2. **Ağ Mimarisi**: Model, konvolüsyonel katmanlar, pooling katmanları, tam bağlantılı katmanlar, dropout ve aktivasyon fonksiyonlarını içerir.

### Eğitim
1. **Eğitim Süreci**: Model, eğitim ve doğrulama setlerine ayrılmış UTKFace veri seti üzerinde eğitilir.
2. **Optimizasyon**: Adam veya SGD gibi algoritmalar model parametrelerini güncellemek için kullanılır.

### Değerlendirme
1. **Performans Metrikleri**: Model, Ortalama Mutlak Hata (MAE) ile değerlendirilir.
2. **Görselleştirme**: Tahmin edilen yaşlar ile gerçek yaşlar arasındaki farklar görselleştirilir.

## Önemli Bulgular
- **Model Doğruluğu**: Eğitim ve yeni görüntüler üzerinde makul doğruluk elde edilmiştir.
- **Epoch ve Veri Boyutu**: Epoch sayısını artırmak öğrenmeyi geliştirebilir ancak aşırı uyum riskini de taşır. Daha fazla veri genellikle doğruluğu ve genelleme yeteneğini artırır.

## Sonuç
Epoch sayısını ve veri seti boyutunu dengelemek kritiktir. Erken durdurma ve veri genişletme gibi teknikler performansı artırabilir.


