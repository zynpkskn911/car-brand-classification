# car-brand-classification
Car Brand Classification using Deep Learning (Akbank Bootcamp Project)

Bu proje, **araba markalarını görüntülerden otomatik olarak sınıflandırmayı** amaçlamaktadır. Proje, **Akbank Derin Öğrenme Bootcamp** kapsamında hazırlanmıştır.

---

## Projenin Amacı
Araba görsellerinden marka tahmini yapan bir derin öğrenme modeli geliştirmek.  
Hedef: 33 farklı araba markasını (Audi, BMW, Ford, Mercedes, Tesla vb.) doğru sınıflandırmak.

---

## Veri Seti
- **Kaynak:** [Kaggle Car Brand Classification Dataset](https://www.kaggle.com/datasets/ahmedelsany/car-brand-classification-dataset )  
- **Boyut:** ~16.000 görüntü  
- **Sınıf Sayısı:** 33  
- Görseller marka klasörleri altında organize edilmiştir.

---

## Kullanılan Yöntemler
- **Veri Önişleme:**  
  - Train / Validation split (%80 / %20)  
  - Data Augmentation (rotation, zoom, horizontal flip)  
- **Modelleme:**  
  - Transfer Learning (EfficientNetB0, ImageNet ağırlıklarıyla)  
  - Fine-tuning ile performans artırma  
- **Değerlendirme:**  
  - Accuracy, Top-3 Accuracy  
  - Confusion Matrix  
  - Classification Report  
- **Açıklanabilirlik:**  
  - Grad-CAM ile modelin karar bölgelerini görselleştirme

---

## Sonuçlar
- **Validation Accuracy:** %XX (kendi sonucunu buraya yaz)  
- **Top-3 Accuracy:** %XX  
- **Confusion Matrix:**  
  ![Confusion Matrix](confusion_matrix.png)  
- **Grad-CAM Örnekleri:**  
  ![Grad-CAM](gradcam_example.png)  

---

## Proje Yapısı
car-brand-classification/
│
├── notebooks/
│ └── car_brand_classification.ipynb # Kaggle notebook
├── images/
│ ├── confusion_matrix.png
│ └── gradcam_example.png
├── README.md
└── requirements.txt

---

## Kullanım
1. Kaggle Notebook’u aç ve GPU seç: [Notebook Linki](https://www.kaggle.com/code/zeynepkskn4/car-brand-classification)  
2. Notebook’u çalıştırarak modeli eğit.  
3. Eğitilmiş modeli test verileri üzerinde değerlendir.

---

## Kaynaklar
- [Akbank Derin Öğrenme Bootcamp PDF]( https://drive.google.com/file/d/1qiJUWsfR1JOjv-5fTflfBpcdrL916ibf/view?usp=sharing)  
- [Kaggle Dataset]((https://www.kaggle.com/datasets/ahmedelsany/car-brand-classification-dataset )

---

## Not
Bu proje sadece **eğitim amaçlıdır**.  

