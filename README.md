Skin Cancer Image Processing Project

Yüksek Lisans – Sayısal Görüntü İşleme Projesi

Bu proje, ISIC (International Skin Imaging Collaboration) veri seti kullanılarak cilt lezyonu görüntüleri üzerinde görüntü analizi, görüntü iyileştirme, gürültü azaltma, histogram analizleri, frekans alanı dönüşümleri ve keskinleştirme işlemlerinin uygulanmasını içerir.

Amaç: Görüntü işleme temel tekniklerini uygulamak, her adımı deneysel olarak incelemek ve görsel çıktılar ile birlikte analiz etmektir.

Proje İçeriği
1. Veri Yükleme ve İnceleme

ISIC veri setinden görüntülerin yüklenmesi

Çözünürlük, kanal sayısı ve dosya boyutu analizleri

Değişikliklerin DataFrame üzerinde saklanması

Veri istatistiklerinin özetlenmesi

2. Görselleştirme

Rastgele seçilen 9 görüntünün RGB ve Grayscale halleri

Her görüntü için:

RGB histogramı (R, G, B kanalları ayrı)

Grayscale histogramı

Piksel değerlerinin minimum–maksimum, ortalama ve standart sapma karşılaştırmaları

3. Görüntü İyileştirme

Kontrast Germe (Stretching)

Histogram Eşitleme (RGB & Grayscale)

Gamma Düzeltme (0.5, 1.0, 2.0)

4. Gürültü Azaltma

Median Blur

Gaussian Blur

Kenar koruma ve detay kaybı karşılaştırması

5. Geometrik Dönüşümler

0–10 derece arası rastgele döndürme

Yatay ayna çevirme (Flipping)

6. Frekans Alanında Analiz (FFT)

Fourier dönüşümü

Frekans spektrumu görselleştirme

Alçak geçiren filtre

Ters FFT ile görüntü elde etme

7. Keskinleştirme ve Enterpolasyon

Unsharp Masking ile keskinleştirme (RGB & Grayscale)

Bicubic enterpolasyon ile 2 kat büyütme

Büyütülen görüntü kalitesinin değerlendirilmesi

Kullanılan Teknolojiler

Python 3.10+	: Ana programlama dili
OpenCV (cv2) : Görüntü işleme fonksiyonları
NumPy	: Matris işlemleri
Pandas : Veri analizi
Matplotlib / Seaborn : Görselleştirme
Jupyter Notebook : Tüm analizlerin adım adım yürütüldüğü ortam

Proje Sahibi:
Arzu Koçhan
Yüksek Lisans – Bilgisayar Mühendisliği
Sayısal Görüntü İşleme Projesi
2025
