# Makine Öğrenmesi ile Erken Evre Diyabet Riski Sınıflandırması

Bu proje, **Gazi Üniversitesi Bilgisayar Mühendisliği Bölümü Veri Bilimi** dersi kapsamında bir araştırma ve uygulama çalışması olarak gerçekleştirilmiştir. Çalışmanın temel amacı, semptom temelli veriler kullanarak diyabetin erken evre teşhisinde makine öğrenmesi algoritmalarının etkinliğini karşılaştırmalı olarak analiz etmektir.

##  Proje Özeti
Diyabetin erken teşhisi, hastaların yaşam kalitesini artırmada ve ciddi komplikasyonların önüne geçmede kritik bir rol oynar. Bu çalışmada, klinik testlere gerek kalmadan temel semptomlar üzerinden risk analizi yapabilen modeller geliştirilmiştir:

##  Veri Seti Hakkında
Araştırmada, UCI Machine Learning Repository üzerinde bulunan **"Early Stage Diabetes Risk Prediction Dataset"** kullanılmıştır.
* **Örnek Sayısı:** 520 birey.
* **Özellik Sayısı:** 16 bağımsız değişken (Yaş, Cinsiyet, Poliüri, Polidipsi, Ani kilo kaybı vb.).
* **Hedef Değişken:** Diyabet Riski (Pozitif / Negatif).

##  Kullanılan Teknolojiler ve Yöntemler
* **Programlama Dili:** Python.
* **Kütüphaneler:** Scikit-Learn, TensorFlow/Keras (Yapay Sinir Ağları için), Pandas, NumPy, Matplotlib.
* **Modelleme:** Veri seti %80 eğitim ve %20 test olarak ayrılmıştır: 61. Kategorik veriler binary forma dönüştürülmüştür.

##  Performans Sonuçları
Çalışma kapsamında 7 farklı algoritma test edilmiş ve modellerin başarısı çeşitli metriklerle doğrulanmıştır.

| Model | Doğruluk (Accuracy) | AUC | F1-Skoru |
| :--- | :---: | :---: | :---: |
| **Rastgele Orman (Random Forest)** | **%99** | **1.00** | **0.99** |
| **Karar Ağaçları (Decision Tree)** | %98 | 0.98 | 0.98 |
| **Yapay Sinir Ağları (MLP)** | %97 | 1.00 | 0.97 |
| **K-En Yakın Komşu (K-NN)** | %93 | 0.98 | 0.88 |
| **Lojistik Regresyon** | %92 | 0.97 | 0.91 |
| **Naive Bayes** | %91 | 0.95 | 0.90 |
| **Lineer Regresyon** | %60 | 0.98 | 0.91 |

##  Dosya Yapısı
* `Makale.pdf`: Projenin tüm detaylarını, literatür taramasını ve bulgularını içeren akademik rapor.

##  Yazarlar
* **Kağan Güner** - Gazi Üniversitesi Bilgisayar Mühendisliği Öğrencisi.
* **Davronbek Abdurazzokov** - Gazi Üniversitesi Bilgisayar Mühendisliği Öğrencisi.
