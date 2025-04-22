# Kalp Üfürümü Tespiti Projesi (CirCor)

Bu proje, kalp sesi kayıtlarından kalp üfürümü tespiti yapmak için çeşitli önceden eğitilmiş ses modellerini kullanmayı amaçlamaktadır.

## Başlangıç

Bu projeyi çalıştırmak için adım adım ilerleyin:

### 1. Kurulum

Gerekli kütüphaneleri kurmak için:

```bash
pip install -r requirements.txt
```

### 2. Notebooks

Projeyi çalıştırmak için sırasıyla şu notebook'ları kullanabilirsiniz:

1. `1-Veri-Hazırlama.ipynb` - Verisetini indirir ve hazırlar
2. `2-Model-Eğitimi.ipynb` - Modeli eğitir ve değerlendirir
3. `3-Sonuçları-Görselleştirme.ipynb` - Sonuçları görselleştirir

## Veri Hakkında

Bu proje, PhysioNet/CirCor verisetini kullanmaktadır. Bu veriseti, kalp seslerinin kaydedildiği bir koleksiyondur ve kalp üfürümü olan ve olmayan kayıtları içerir.

## Modeller

Proje içerisinde şu modellerle çalışabilirsiniz:
- M2D (Ses analizi için önceden eğitilmiş görsel dönüştürücü model)
- AST (Audio Spectrogram Transformer)
- BYOL-A (Bootstrap Your Own Latent for Audio)
- CNN14 (PANNs'tan önce eğitilmiş model)

## Referanslar

Bu çalışma, "Exploring Pre-trained General-purpose Audio Representations for Heart Murmur Detection" (2024) makalesine dayanmaktadır. 