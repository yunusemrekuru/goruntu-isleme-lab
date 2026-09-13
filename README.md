<div align="center">

# 🖼️ Görüntü İşleme Lab · Computer Vision Lab

**OpenCV ile Bilgisayarlı Görü Ders Notları ve Uygulamaları**
<br/>
*Computer Vision course notes & hands-on tutorials with OpenCV*

---

[![Language](https://img.shields.io/badge/language-Python-blue.svg)](https://www.python.org/)
[![OpenCV](https://img.shields.io/badge/OpenCV-4.x-green.svg)](https://opencv.org/)
[![Notebooks](https://img.shields.io/badge/Notebooks-48-orange.svg)](#içindekiler--table-of-contents)
[![License](https://img.shields.io/badge/license-MIT-lightgrey.svg)](LICENSE)

</div>

---

## 🇹🇷 Türkçe

Bu repo, **OpenCV** kullanarak **bilgisayarlı görü (Computer Vision)** alanını sıfırdan ileri seviyeye kadar anlatan **Jupyter Notebook** ders notlarını ve uygulamalarını içerir.

Temel görüntü işlemeden (yükleme, renk uzayları, eşikleme, konturlar) derin öğrenme tabanlı yöntemlere (YOLO, SSD, yüz tanıma, Neural Style Transfer, OCR) kadar **48 ders** Türkçe anlatımlı ve çalıştırılabilir notebook formatındadır. Her dersin başlığında İngilizce karşılığı da bulunur.

### ✨ İçerik Özellikleri

- 🔢 40 numaralı ders + 7 video işleme dersi + renklendirme uygulaması
- 🧠 Hazır (pretrained) model dosyaları: YOLOv3, SSD, Haar Cascade, dlib, Neural Style Transfer, renklendirme (Caffe)
- 🎥 Gerçek video, görüntü ve veri seti dosyaları
- 📦 Çalıştırılmaya hazır, adım adım açıklamalı notebook'lar
- 🌍 Türkçe + İngilizce başlıklar

### 📋 İçindekiler · Table of Contents

| # | Türkçe | English |
|---|--------|---------|
| 00 | Bilgisayarlı Görü Nedir | What is Computer Vision |
| 01 | Başlangıç: Yükleme, Görüntüleme, Kaydetme | Loading, Displaying, Saving & Dimensions |
| 02 | Resimleri Gri Tona Çevirme | Grayscaling Images |
| 03 | Renk Uzayları | Color Spaces |
| 04 | Resimlerin Üzerine Yazma | Drawing on Images |
| 05 | Dönüşümler: Kaydırma ve Çevirme | Transformations: Translations & Rotations |
| 06 | Ölçekleme, Yeniden Boyutlandırma, Enterpolasyon, Kırpma | Scaling, Re-sizing, Interpolations & Cropping |
| 07 | Aritmetik ve Bitsel İşlemler | Arithmetic & Bitwise Operations |
| 08 | Konvolüsyonlar, Bulanıklaştırma ve Keskinleştirme | Convolutions, Blurring & Sharpening |
| 09 | Eşikleme, İkili Sisteme Dönüştürme, Uyarlanabilir Eşikleme | Thresholding, Binarization & Adaptive Thresholding |
| 10 | Dilatasyon, Erozyon ve Kenar Algılama | Dilation, Erosion & Edge Detection |
| 11 | Konturlar: Çizim, Hiyerarşi ve Modlar | Contours: Drawing, Hierarchy & Modes |
| 12 | Moment, Sıralama, Yaklaşıklaştırma ve Kontur Eşleştirme | Moments, Sorting, Approximating & Matching Contours |
| 13 | Çizgi, Daire ve Blob Algılama | Line, Circle & Blob Detection |
| 14 | Daireleri/Elipsleri Sayma ve Waldo'yu Bulma | Counting Circles/Ellipses & Template Matching |
| 15 | Köşeleri Bulmak | Finding Corners |
| 16 | Haar Cascade ile Yüz ve Göz Algılama | Face & Eye Detection with Haar Cascade |
| 17 | Araç ve Yaya Algılama | Vehicle & Pedestrian Detection |
| 18 | Perspektif Dönüşümler | Perspective Transforms |
| 19 | Histogramlar ve K-Means Kümeleme (Baskın Renkler) | Histograms & K-Means Clustering |
| 20 | Resimlerin Karşılaştırılması (MSE & SSIM) | Comparing Images (MSE & SSIM) |
| 21 | Renkleri Filtreleme | Filtering Colors |
| 22 | Watershed Algoritması ile Segmentasyon | Watershed Marker-Based Segmentation |
| 23 | Arka Plan ve Ön Plan Çıkarma | Background & Foreground Subtraction |
| 24 | Meanshift ve CAMSHIFT ile Hareket Takibi | Motion Tracking with Mean Shift & CAMSHIFT |
| 25 | Optik Akış ile Nesne Takibi | Object Tracking with Optical Flow |
| 26 | Renge Göre Basit Nesne Takibi | Simple Object Tracking by Color |
| 27 | dlib ile Yüz Noktaları Algılama | Facial Landmark Detection with dlib |
| 28 | dlib ile Yüz Değiştirme | Face Swapping with dlib |
| 29 | Tilt Shift Efekti | Tilt Shift Effects |
| 30 | GrabCut ile Arka Plan Kaldırma | GrabCut for Background Removal |
| 31 | PyTesseract ve EasyOCR ile Karakter Tanıma | OCR with PyTesseract & EasyOCR |
| 32 | Barkod ve QR Oluşturma ve Okuma | Barcode & QR Generation & Reading |
| 33 | YOLOv3 ile Nesne Algılama | YOLOv3 in OpenCV |
| 34 | Neural Style Transfer | Neural Style Transfer |
| 35 | Tek Atış Dedektörleri (SSD) | SSDs in OpenCV |
| 36 | Siyah Beyaz Fotoğrafları Renklendirme (Caffe) | Colorize B&W Photos (Caffe) |
| 37 | Inpainting ile Hasarlı Fotoğraf Onarımı | Inpainting to Restore Photos |
| 38 | Gürültü Ekleme/Kaldırma ve Histogram Eşitleme | Noise & Histogram Equalization |
| 39 | Bulanıklık Algılama | Detect Blur in Images |
| 40 | Yüz Tanıma | Facial Recognition |

**🎥 Video İşleme · Working with Video**

| # | Türkçe | English |
|---|--------|---------|
| 1 | Web Kamerası ile Canlı Görüntü ve Eskiz | Webcam & Live Sketch |
| 2 | Video Dosyalarını Açma | Opening Video Files |
| 3 | Video Kaydetme | Saving/Recording Videos |
| 4 | RTSP ve IP Kamera (CCTV) | Video Streams & CCTV (RTSP/IP) |
| 5 | Video Akışına Otomatik Yeniden Bağlanma | Auto Reconnect to Video Streams |
| 6 | Ekran Görüntüleri ile Video Yakalama | Capturing Video via Screenshots |
| 7 | YouTube Videolarını OpenCV'ye Aktarma | Import YouTube Video into OpenCV |

### 📁 Klasör Yapısı

```
.
├── OpenCV/                 # 00-40 numaralı ders notebook'ları
│   └── Working with Video/ # Video işleme dersleri
├── files/
│   ├── Haarcascades/       # Haar Cascade XML dosyaları
│   ├── YOLO/               # YOLOv3 ağırlık, config ve COCO sınıfları
│   ├── SSDs/               # SSD (MobileNet) model dosyaları
│   ├── NeuralStyleTransfer/# Stil aktarımı modelleri (.t7)
│   ├── colorize/           # Siyah-beyaz renklendirme modeli
│   ├── images/             # Örnek görüntüler
│   └── videos/             # Örnek videolar
└── README.md
```

### ⚙️ Gereksinimler ve Kurulum

**Python 3.8+** önerilir.

```bash
pip install opencv-python opencv-contrib-python numpy matplotlib
pip install dlib face_recognition imutils
pip install pytesseract easyocr
pip install pyzbar qrcode scikit-image scikit-learn pandas
pip install torch torchvision
```

> Not: `dlib` kurulumu için CMake gerekebilir. `pytesseract` için ayrıca [Tesseract OCR](https://github.com/tesseract-ocr/tesseract) motoru kurulmalıdır.

### 🚀 Kullanım

1. Repoyu klonlayın:
   ```bash
   git clone https://github.com/yunusemrekuru/goruntu-isleme-lab.git
   cd goruntu-isleme-lab
   ```
2. Büyük model dosyaları **Git LFS** ile tutulur, klonlama sırasında otomatik iner:
   ```bash
   git lfs pull
   ```
3. Jupyter Notebook'u başlatın:
   ```bash
   jupyter notebook
   ```
4. `OpenCV/` klasöründeki dersleri sırasıyla açın ve çalıştırın.

### 📦 Model Dosyaları (Git LFS)

Büyük önceden eğitilmiş modeller **Git LFS** ile saklanır:

- `yolov3.weights` (~237 MB)
- `colorization_release_v2.caffemodel` (~123 MB)
- `shape_predictor_68_face_landmarks.dat` (~95 MB)
- Neural Style Transfer modelleri (`.t7`)
- SSD `frozen_inference_graph.pb`

> LFS dosyalarını indirmek için `git lfs install` ve `git lfs pull` yeterlidir.

---

## 🇬🇧 English

This repository contains **Jupyter Notebook** course notes and hands-on applications that teach **Computer Vision** with **OpenCV**, from scratch to advanced level.

From basic image processing (loading, color spaces, thresholding, contours) to deep learning based methods (YOLO, SSD, face recognition, Neural Style Transfer, OCR) — **48 lessons** in runnable notebook format. Each lesson title also includes its English equivalent.

### ✨ Features

- 🔢 40 numbered lessons + 7 video lessons + a colorization application
- 🧠 Pretrained model files: YOLOv3, SSD, Haar Cascade, dlib, Neural Style Transfer, colorization (Caffe)
- 🎥 Real video, image and dataset files
- 📦 Ready-to-run notebooks with step-by-step explanations
- 🌍 Turkish + English titles

### ⚙️ Requirements & Setup

**Python 3.8+** recommended.

```bash
pip install opencv-python opencv-contrib-python numpy matplotlib
pip install dlib face_recognition imutils
pip install pytesseract easyocr
pip install pyzbar qrcode scikit-image scikit-learn pandas
pip install torch torchvision
```

> Note: `dlib` may require CMake to install. `pytesseract` also requires the [Tesseract OCR](https://github.com/tesseract-ocr/tesseract) engine.

### 🚀 Usage

```bash
git clone https://github.com/yunusemrekuru/goruntu-isleme-lab.git
cd goruntu-isleme-lab
git lfs pull     # downloads the large model files
jupyter notebook
```

### 📦 Model Files (Git LFS)

Large pretrained models are stored via **Git LFS** (see the list above). Run `git lfs pull` to download them.

---

## 📄 Lisans · License

Bu proje [MIT License](LICENSE) ile lisanslanmıştır. · This project is licensed under the [MIT License](LICENSE).
