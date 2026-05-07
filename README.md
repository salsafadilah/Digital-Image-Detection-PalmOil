# Digital-Image-Detection-PalmOil
Proyek deteksi kesehatan pohon kelapa sawit menggunakan algoritma YOLOv8
# 🌴 Deteksi Kesehatan Pohon Kelapa Sawit menggunakan YOLO26s

![YOLO26](https://img.shields.io/badge/Model-YOLO26s-blue)
![Python](https://img.shields.io/badge/Python-3.12-green)
![Ultralytics](https://img.shields.io/badge/Library-Ultralytics-orange)

## 📌 Deskripsi Proyek
Proyek ini bertujuan untuk mengotomatisasi pemantauan kesehatan pohon kelapa sawit melalui citra udara menggunakan algoritma **Computer Vision**. Dengan memanfaatkan arsitektur **YOLO26s** (rilis terbaru Ultralytics 2026), model ini mampu mengklasifikasikan kondisi pohon ke dalam dua kategori: **Healthy** (Sehat) dan **Unhealthy** (Sakit).

Sistem ini dirancang untuk membantu efisiensi operasional di perkebunan sawit skala luas, memungkinkan deteksi dini terhadap pohon yang mengalami anomali nutrisi atau serangan hama.

## 🚀 Fitur Utama
- **Real-time Detection:** Menggunakan varian *Small* (s) untuk kecepatan inferensi tinggi (~5.7ms).
- **High Accuracy:** Mencapai tingkat akurasi rata-rata (mAP50) sebesar **75.3%**.
- **Automated Management:** Integrasi dataset langsung dari Roboflow dengan teknik *Data Augmentation*.

## 📊 Hasil Pelatihan (Performance)
Setelah dilakukan pelatihan selama **50 Epoch**, model menunjukkan hasil evaluasi sebagai berikut:

| Metric | Value |
| :--- | :--- |
| **mAP50 (All Classes)** | **0.753 (75.3%)** |
| **mAP50 (Healthy)** | **0.922 (92.2%)** |
| **mAP50 (Unhealthy)** | **0.584 (58.4%)** |
| **Inference Speed** | **5.7ms per image** |

### Visualisasi Performa
- **Training Results:** Menunjukkan penurunan *loss* yang stabil dan kenaikan akurasi yang konsisten.
- **Confusion Matrix:** Menunjukkan kemampuan model dalam membedakan kelas objek secara detail.

## 🛠️ Teknologi yang Digunakan
- **Programming Language:** Python
- **Environment:** Google Colab (GPU Tesla T4)
- **Architecture:** YOLO26s by Ultralytics
- **Dataset Management:** Roboflow

## 📂 Struktur Folder
- `/train`: Data untuk pelatihan model.
- `/valid`: Data untuk validasi selama proses training.
- `/test`: Data untuk pengujian akhir model.
- `best.pt`: Bobot model terbaik hasil pelatihan.

## 📖 Artikel Medium
Untuk penjelasan lebih mendalam mengenai teori, proses *preprocessing*, dan analisis mendalam dari proyek ini, silakan baca artikel saya di Medium:
👉 [**Link Artikel Medium Kamu di Sini**]

---
**Kontak & Kontribusi**
Dibuat oleh **Salsabila Gusti Padilah** sebagai bagian dari studi Informatika. Jika ada saran atau pertanyaan, silakan hubungi saya melalui GitHub.
