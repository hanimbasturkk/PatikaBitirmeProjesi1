# Customer Experience Data Analysis

Bu proje, müşteri deneyimi verilerini analiz etmek ve müşteri memnuniyetine etki eden önemli faktörleri keşfetmek amacıyla yapılmıştır. Veri ön işleme, keşifsel veri analizi ve temel görselleştirme adımları uygulanarak veri, makine öğrenmesi modellerine uygun hale getirilmiştir.

## 🔍 Proje Amacı

- Müşteri deneyimiyle ilgili değişkenleri analiz etmek
- Eksik ve aykırı değerleri incelemek
- Veriyi modeller için uygun forma dönüştürmek

## 🗂️ Kullanılan Veri Seti

- **Customer Experience Dataset**
- İçerik: Ürün kalitesi, çözüm hızı, destek memnuniyeti, tekrar satın alma isteği, vb.
- Format: `.csv`

## 🧰 Kullanılan Kütüphaneler

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `sklearn.preprocessing` (LabelEncoder)

## 📌 Uygulanan Adımlar

### 1. Veri Yükleme ve Genel İnceleme
- Veri seti pandas ile yüklendi.
- Sütun adları ve veri türleri incelendi.
- Gereken sütunlar `category` tipine dönüştürüldü.

### 2. Eksik Değer Analizi
- Hangi sütunlarda eksik veri olduğu belirlendi.
- Eksik değerlerin dağılımı grafiklerle gösterildi.

### 3. Aykırı Değer Analizi
- Sayısal değişkenlerde kutu grafikleri (boxplot) kullanıldı.
- Uç değerler belirlendi.

### 4. Korelasyon Analizi
- Sayısal sütunlar arasındaki ilişki `heatmap` ile görselleştirildi.
- Pozitif ve negatif ilişkiler yorumlandı.

### 5. Kategorik Verilerin Kodlanması
- Kategorik veriler `LabelEncoder` ile sayısal hale getirildi.
- Bu sayede veri, makine öğrenmesi modellerine uygun hale geldi.

## 🎯 Sonuç ve Gelecek Planı

Bu proje kapsamında veri seti detaylı olarak analiz edildi ve ön işleme adımları başarıyla tamamlandı.  
Sonraki aşamada bu veriler kullanılarak müşteri memnuniyetini tahmin etmeye yönelik sınıflandırma modelleri geliştirilecektir.


---

