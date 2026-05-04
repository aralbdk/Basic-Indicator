# Basit SMA İndikatörü (Simple SMA Indicator)

Bu proje, TradingView platformu için Pine Script (v6) kullanılarak yazılmış temel bir Basit Hareketli Ortalama (SMA - Simple Moving Average) indikatörüdür. 

Piyasa trendlerini analiz etmek ve potansiyel alım-satım sinyallerini yakalamak amacıyla kısa ve uzun vadeli hareketli ortalamaları aynı grafik üzerinde görselleştirir.

## 🚀 Özellikler

* **Kısa Vadeli Ortalama (Mavi Çizgi):** Fiyatın son 14 periyotluk kapanış değerlerinin ortalamasını alır (`kisa_sma`). Fiyat hareketlerine daha hızlı tepki verir.
* **Uzun Vadeli Ortalama (Kırmızı Çizgi):** Fiyatın son 50 periyotluk kapanış değerlerinin ortalamasını alır (`uzun_sma`). Ana trendin yönünü belirlemekte kullanılır.
* **Trend Kesişimleri:** Bu iki çizginin birbirini yukarı veya aşağı yönlü kesmesi (Golden Cross / Death Cross mantığı) teknik analizde trend dönüşüm sinyalleri olarak yorumlanabilir.

## 🛠️ Kurulum ve Kullanım

Bu indikatörü TradingView üzerinde çalıştırmak için aşağıdaki adımları izleyebilirsiniz:

1. [TradingView](https://www.tradingview.com/) üzerinde herhangi bir finansal varlığın grafiğini açın.
2. Ekranın alt kısmında bulunan **Pine Editor** sekmesine tıklayın.
3. Editördeki mevcut kodları silip, bu repodaki kodları yapıştırın.
4. Sağ üstteki **Grafiğe Ekle (Add to Chart)** butonuna tıklayın.
5. İndikatör, fiyat grafiğinizin üzerinde anında belirecektir.

## 💻 Kullanılan Teknolojiler

* Pine Script v6
* TradingView

---
*Not: Bu kod, teknik analize ve Pine Script'e giriş niteliğinde bir eğitim projesidir. Herhangi bir yatırım tavsiyesi içermez.*
