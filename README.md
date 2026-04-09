# 📌 AI Tabanlı Yüz Tanıma ve Yoklama Sistemi

Bu proje, kamera üzerinden yüz algılama ve yapay zeka destekli tanıma ile otomatik yoklama almayı sağlayan bir sistemdir. Sistem; frontend, backend, yapay zeka modeli ve veritabanı bileşenlerinden oluşur.

---

##  Özellikler

-  Gerçek zamanlı kamera erişimi
-  Yapay zeka ile yüz tanıma
-  Liveness Detection (canlılık kontrolü)
-  Otomatik yoklama kaydı
-  REST API mimarisi
-  Veritabanı yönetimi
-  CI/CD desteği

---

##  Sistem Bileşenleri

### YZDYS-13 - Kullanıcı Arayüzü ve Kamera Yönetimi
- Kamera erişimi (WebRTC / MediaDevices API)
- Kullanıcıdan görüntü alma
- Gerçek zamanlı görüntü işleme

### YZDYS-14 - Yüz Algılama ve Biyometrik İşleme
- Yüz tespiti
- Landmark çıkarımı
- Görüntü normalize etme

### YZDYS-16 - Yapay Zeka Tanıma Motoru
- Yüz embedding üretimi
- Similarity hesaplama
- Kimlik doğrulama

### YZDYS-17 - Liveness Detection
- Sahte yüz engelleme
- Göz kırpma / hareket kontrolü

### YZDYS-18 - Backend REST API
- Kullanıcı yönetimi
- Tanıma servisleri
- Yoklama endpointleri

### YZDYS-19 - Veritabanı Yönetimi
- Kullanıcı verileri
- Embedding kayıtları
- Yoklama kayıtları

### YZDYS-20 - DevOps ve CI/CD
- Versiyon kontrol (Git)
- Otomatik deploy
- Docker desteği

### YZDYS-23 - Embedding Üretimi ve Karşılaştırma
- Embedding oluşturma
- Veritabanında saklama
- Karşılaştırma işlemleri

### YZDYS-24 - Yoklama Kaydı
- Tanınan kullanıcıyı kaydetme
- Tarih ve saat bilgisi
- Tekrar kayıt kontrolü

---

##  Teknolojiler

- Frontend: React / HTML / CSS / JS
- Backend: Node.js / Flask / Spring Boot
- AI: Python (OpenCV, TensorFlow, PyTorch)
- Database: PostgreSQL / MySQL
- DevOps: Docker, CI/CD




