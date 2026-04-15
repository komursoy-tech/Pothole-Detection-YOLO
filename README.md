# YOLOv11 ile Çukur (Pothole) Tespiti

Bu proje, otonom araçlar ve altyapı izleme sistemleri için yol üzerindeki hasarları (çukurları) gerçek zamanlı olarak tespit etmek amacıyla geliştirilmiştir.

## 🧠 Proje Detayları
* **Model:** YOLOv11 (You Only Look Once)
* **Veri Seti:** 1,300+ görüntüden oluşan özel etiketlenmiş veri seti.
* **Performans:** Yüksek mAP50 değerleri ile optimize edilmiş eğitim süreci.

## 🛠 Kullanılan Teknolojiler
* **Programlama Dili:** Python
* **Kütüphaneler:** Ultralytics, OpenCV, Matplotlib
* **Donanım:** NVIDIA RTX 4050 GPU ile eğitilmiştir.

## 📊 Sonuçlar
Proje, farklı hava koşullarında ve ışık seviyelerinde stabil bir nesne tespiti performansı sergilemektedir.

## ⚙️ Kullanım
Modeli test etmek için:
1. Gerekli kütüphaneleri kurun: `pip install ultralytics`
2. Test kodunu çalıştırın: `python detect.py --source image.jpg`
