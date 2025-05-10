# 🧠 Jaringan Syaraf Tiruan (218315-23) 

![Badge](https://img.shields.io/badge/Subject-Artificial_Neural_Network-9cf) 
![Badge](https://img.shields.io/badge/SKS-3-blue) 
![Badge](https://img.shields.io/badge/Status-Baru-brightgreen)
![Badge](https://img.shields.io/badge/Labs-RapidMiner-orange)

**Dosen**: Dr. Ir. Arief Hermawan, MT. IPU.  
**Jadwal**: Rabu | 12.50 - 15.20 WIB | K1 - E.1.1  

## 📚 Deskripsi Mata Kuliah
Repository ini berisi materi, latihan soal, dan proyek untuk mata kuliah Jaringan Syaraf Tiruan (ANN). Fokus pembelajaran meliputi:
- Model matematis ANN
- Fungsi aktivasi dan perceptron
- Algoritma backpropagation
- Implementasi praktis menggunakan RapidMiner

📦 ANN-218315-23
├── 📂 00_Pengantar
│   ├── 📜 Silabus.md
│   ├── 📜 Kontrak_Kuliah.pdf
│   └── 📜 Referensi.txt
├── 📂 01_Dasar_Teori
│   ├── 📜 1.1_Konsep_ANN.md
│   ├── 📜 1.2_Model_Matematis.ipynb
│   └── 📜 1.3_Fungsi_Aktivasi.pdf
├── 📂 02_Perceptron
│   ├── 📂 Latihan
│   │   ├── 📜 Soal_Perceptron.md
│   │   └── 📜 Pembahasan_Perceptron.py
│   └── 📜 Kuis_1_Solusi.ipynb
├── 📂 03_Backpropagation
│   ├── 📜 3.1_Teori_Backprop.md
│   ├── 📜 3.2_Implementasi_RapidMiner.rmp
│   └── 📂 Dataset
│       └── 📜 data_latihan.csv
├── 📂 04_Praktikum
│   ├── 📂 Modul_1
│   │   ├── 📜 Panduan_Praktikum.pdf
│   │   └── 📜 Screenshot_Hasil.png
│   └── 📂 Modul_2
│       ├── 📜 Laporan_Praktikum.docx
│       └── 📜 Hasil_Export.rmp
├── 📂 05_Ujian
│   ├── 📜 Bank_Soal_UTS.pdf
│   └── 📜 Panduan_UAS_Take_Home.md
├── 📂 06_Tugas_Besar
│   ├── 📜 Proposal_Tugas_Akhir.md
│   ├── 📂 Dataset
│   │   └── 📜 data_akhir.csv
│   └── 📂 Code
│       ├── 📜 ann_model.py
│       └── 📜 preprocessing.ipynb
└── 📜 README.md

## 🗓️ Agenda Pembelajaran
| Minggu | Topik | Status |
|--------|-------|--------|
| 1 | Pengenalan ANN | ✅ |
| 2 | Model Matematis ANN | ✅ |
| 3-4 | Fungsi Aktivasi & Latihan Soal | ✅ |
| 5 | Konsep SSE | 📝 |
| 6 | Perhitungan Perceptron | 🚧 |
| 7 | Kuis Perceptron | ❌ |
| 8 | Persiapan UTS | ❌ |
| 9-11 | Backpropagation & Dataset | ❌ |
| 12-14 | Praktikum RapidMiner & UAS | ❌ |

## 🛠️ Tools & Referensi
- **Software**: 
  ![RapidMiner](https://img.shields.io/badge/-RapidMiner-00b4d8?logo=rapidminer)
  ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python)
- **Buku**:
  - *Neural Networks and Deep Learning* - Michael Nielsen
  - *Pattern Recognition* - Christopher Bishop

## 💡 Contoh Implementasi
```python
# Contoh sederhana perceptron
import numpy as np

def perceptron(inputs, weights, bias):
    return 1 if np.dot(inputs, weights) + bias > 0 else 0
📝 Kontribusi
Fork repository

Buat branch baru (git checkout -b fitur-baru)

Commit perubahan (git commit -m "Tambahkan materi minggu X")

Push ke branch (git push origin fitur-baru)

Buat Pull Request

© Nama Anda | 2024 | GitHub


**Fitur Khusus:**
✅ Progress tracker dengan emoji (✅📝🚧❌)  
✅ Syntax highlighting untuk kode Python  
✅ Badges untuk tools dan status  
✅ Struktur folder yang terorganisir  
✅ Tabel agenda pembelajaran interaktif  

Tips:  
- Ganti `username` di footer dengan GitHub Anda  
- Tambahkan screenshot hasil praktikum di folder terkait  
- Update status progres tiap minggu  

Mau ada penyesuaian? Bisa request tambahan fitur! 🚀
