# Oyuncu Dizüstü Bilgisayarları Fiyat Tahmin Sistemi

## Problem
Farklı işlemci, RAM, ekran kartı ve depolama kombinasyonlarına sahip bilgisayarların fiyatlarının manuel olarak analiz edilmesinin ve tahmin edilmesinin zorluğu.

## Araştırma Sorusu ve Hipotez
RAM, işlemci modeli ve ekran kartı özellikleri kullanılarak laptop fiyatları makine öğrenmesiyle tahmin edilebilir mi? 
**Hipotez:** Çoklu Doğrusal Regresyon modeli, temizlenmiş donanım özellikleri üzerinden fiyatları anlamlı bir hata oranıyla (MSE) tahmin edecektir.

## Literatür Taraması
1. "Price Prediction of Laptops using Machine Learning Algorithms": Veri temizleme ve temel tahminleme algoritmalarının karşılaştırmasını sunar.
2. "Machine Learning based Price Prediction for Electronic Goods": Donanım bileşenlerinin (CPU, GPU, RAM) fiyat üzerindeki ağırlıklı etkisini analiz eder.
3. "Laptop Price Prediction using Random Forest and Regression": Regresyon modellerinin fiyat tahmin başarımını inceler.

## Veri Seti
Kaggle - Gaming Laptop Dataset (Uncleaned). Proje kapsamında ham veriler üzerinde Python ile veri temizleme işlemleri (Data Cleaning) gerçekleştirilecektir.

## İlk Yöntem
Python (Pandas, Scikit-learn) ile Keşifsel Veri Analizi (EDA) ve Çoklu Doğrusal Regresyon (Multiple Linear Regression).

## UML Diyagramları
Projenin tasarım aşamasına ait Use Case, Activity ve Class diyagramları depo kök dizinine PNG formatında eklenmiştir. Bu diyagramlar veri işleme sürecini ve regresyon modelinin kavramsal yapısını temsil etmektedir.
