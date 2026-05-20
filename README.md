# 🧾 MÜŞTERİ SIRA SİSTEMİ SİMÜLASYONU

👨‍🎓 Dorukhan Perdeci  
🎓 Okul No: 21430070029  

---

## 📌 HAKKINDA

Bu proje, Python programlama dili ve özellikle **SimPy kütüphanesi** kullanılarak geliştirilmiş bir **ayrık olay simülasyonu (Discrete Event Simulation)** projesidir. SimPy'nin olay tabanlı yapısından yararlanılarak gerçek hayatta karşılaşılan müşteri kuyruk ve hizmet süreçleri modellenmiştir.

Simülasyon; müşterilerin sisteme gelişini, hizmet noktasına yönlendirilmesini, yoğunluk durumunda kuyrukta beklemesini, hizmet almasını ve ardından sistemden ayrılmasını gerçekçi biçimde taklit etmektedir.

Proje ayrıca müşteri bekleme sürelerinin görselleştirilmesini ve sistem performansına ilişkin istatistiksel analiz yapılmasını sağlamaktadır. Böylece kullanıcı, bir sıra sisteminin çalışma mantığını ve SimPy'nin simülasyon gücünü uygulamalı şekilde gözlemleyebilmektedir.

---

## 📌 PROJENİN AMACI

Bu proje ile:

- SimPy kütüphanesinin kullanımını öğrenmek
- Ayrık olay simülasyonu mantığını anlamak
- Müşteri kuyruk sistemlerini modellemek
- Hizmet süreçlerinin işleyişini incelemek
- Müşteri bekleme sürelerini analiz etmek
- Sistem performansını değerlendirmek
- Gerçek hayat problemlerini simülasyon yöntemiyle çözmek

---

## ⚙️ KULLANILAN TEKNOLOJİLER

- Python
- SimPy (Ayrık Olay Simülasyonu)
- Tkinter (Grafiksel Kullanıcı Arayüzü)
- Random (Rastgele müşteri oluşturma)
- Matplotlib (Veri görselleştirme)

---

## 🧠 SİMÜLASYON MANTIĞI

Bu sistem SimPy'nin olay tabanlı simülasyon yapısı ile çalışmaktadır:

- Müşteriler belirli zaman aralıklarında sisteme giriş yapar
- Gelen müşteriler hizmet kaynağına erişmeye çalışır
- Hizmet noktası doluysa müşteri sıraya alınır
- Müşteri uygun kaynak oluşana kadar bekler
- Hizmet süreci başlatılır
- İşlem tamamlandıktan sonra müşteri sistemden çıkar
- Tüm süreçler SimPy zaman yönetimi ile simüle edilir

---

## 🔄 SÜREÇ AKIŞI

1️⃣ Müşteri sisteme gelir  

2️⃣ Hizmet noktası kontrol edilir  

3️⃣ Yoğunluk varsa müşteri kuyruğa alınır  

4️⃣ Müşteri sırasını bekler  

5️⃣ Hizmet süreci başlatılır  

6️⃣ Hizmet tamamlanır  

7️⃣ Müşteri sistemden ayrılır  

---

## 📊 ELDE EDİLEBİLECEK ÇIKTILAR

- Ortalama bekleme süresi
- Maksimum bekleme süresi
- Müşteri yoğunluğu
- Hizmet kullanım oranı
- Kuyruk uzunluğu
- Sistem performans istatistikleri
- Bekleme sürelerinin görselleştirilmesi

---

## ▶️ NASIL ÇALIŞTIRILIR?

### 1️⃣ Gerekli kütüphaneleri yükleyin:

```bash
pip install simpy
```

Ek kütüphaneler:

```bash
pip install matplotlib
```

### 2️⃣ Programı çalıştırın:

```bash
python randomsimulation.py
```

---

## 📁 PROJE YAPISI

```bash
Musterisirasistemi/
│
├── randomsimulation.py
├── README.md
└── diğer proje dosyaları
```

---

## 🚀 GELECEK GELİŞTİRMELER

- Çoklu hizmet noktası desteği
- Öncelikli müşteri sistemi
- Gerçek zamanlı grafikler
- Daha ayrıntılı istatistiksel analizler
- Gelişmiş kullanıcı arayüzü

---

## 📝 NOT

Bu proje eğitim amaçlı geliştirilmiş olup SimPy kullanılarak ayrık olay simülasyonu mantığını öğretmek ve müşteri sıra sistemlerinin çalışma yapısını modellemek amacıyla hazırlanmıştır.
