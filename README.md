# AI Project Template / Yapay Zeka Proje Şablonu

![Python Version](https://img.shields.io/badge/python-3.8%2B-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Docker](https://img.shields.io/badge/docker-supported-blue)

### Proje Hakkında
Bu depo, yapay zeka ve veri bilimi projeleri için geliştirilmiş modüler bir başlangıç şablonudur. Projelerinizi daha düzenli, ölçeklenebilir ve sürdürülebilir kılmak amacıyla standartlaştırılmış bir klasör yapısı ve gerekli yapılandırma dosyalarını içerir.

### Özellikler
- **Modüler Yapı:** Kaynak kod, konfigürasyonlar ve testler ayrıştırılmıştır.
- **Docker Desteği:** Projenin her ortamda aynı şekilde çalışması için `Dockerfile` hazırdır.
- **Konfigürasyon Yönetimi:** Hiperparametreler ve ayarlar `configs/` altında yönetilir.
- **Deneysel Çalışmalar:** Jupyter notebook çalışmaları için `notebooks/` klasörü bulunur.

### Proje Yapısı
```bash
.
├── configs/        # Model ve eğitim konfigürasyon dosyaları (yaml, json vb.)
├── notebooks/      # Deneysel analizler ve Jupyter Notebook dosyaları
├── src/            # Kaynak kodlar (veri işleme, modelleme, utils)
├── tests/          # Birim testler (Unit tests)
├── Dockerfile      # Konteynerizasyon için Docker yapılandırması
├── main.py         # Projenin ana çalışma dosyası (Entry point)
└── requirements.txt # Proje bağımlılıkları
