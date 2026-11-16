# ☝️ YOLOv8 ile Parmak İzi Sınıflandırma (Fingerprint Classification)

Bu proje, Biyometrik Sistemler dersi kapsamında YOLOv8 (`yolov8n-cls`) derin öğrenme modeli kullanılarak parmak izi tiplerinin (whorl, loop, arch vb.) otomatik olarak sınıflandırılması amacıyla geliştirilmiştir.

## 🚀 Proje Detayları
* **Model:** Ultralytics YOLOv8 (Nano Classification - `yolov8n-cls.pt`)
* **Eğitim (Fine-tuning):** Google Colab üzerinden 200 epoch ile özel bir veri seti üzerinde eğitilmiştir.
* **Tahmin Aşaması:** Eğitilen model ile test görselleri üzerinde sınıflandırma ve güven skoru (confidence score) tespiti yapılarak sonuçlar OpenCV ile görselleştirilmiştir.
## 🛠️ Kullanılan Teknolojiler
* Python 3.x
* Ultralytics YOLO
* OpenCV (Görüntü işleme ve görselleştirme)
* NumPy

## 📂 Dosya Yapısı
* `parmak_izi_siniflandirma.ipynb`: Veri setinin yüklenmesi, modelin eğitilmesi, fine-tuning işlemleri ve tahmin (predict) adımlarını içeren ana Google Colab çalışma dosyası.
