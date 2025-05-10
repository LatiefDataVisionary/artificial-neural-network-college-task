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

# 🧠 Artificial Neural Network (218315-23) - Repository Structure

```text
📦 ANN-218315-23
├── 📂 00_Administrasi
│   ├── 📜 Silabus.pdf
│   ├── 📜 Kontrak_Kuliah.docx
│   ├── 📜 Jadwal_Perkuliahan.md
│   └── 📜 Daftar_Referensi.bib
├── 📂 01_Materi_Teori
│   ├── 📜 1.1_Pengenalan_ANN.md
│   ├── 📜 1.2_Sejarah_ANN.pdf
│   ├── 📜 1.3_Model_Matematis.ipynb
│   ├── 📜 1.4_Fungsi_Aktivasi.md
│   └── 📂 Supplements
│       ├── 📜 Paper_1.pdf
│       └── 📜 Paper_2.pdf
├── 📂 02_Perceptron
│   ├── 📜 2.1_Teori_Perceptron.md
│   ├── 📜 2.2_Implementasi_Python.ipynb
│   ├── 📂 Latihan
│   │   ├── 📜 Soal_1.md
│   │   └── 📜 Solusi_1.py
│   └── 📜 Kuis_1.pdf
├── 📂 03_Backpropagation
│   ├── 📜 3.1_Konsep_Dasar.md
│   ├── 📜 3.2_Algoritma.pdf
│   ├── 📂 Implementasi
│   │   ├── 📜 RapidMiner_Backprop.rmp
│   │   └── 📜 Python_Backprop.ipynb
│   └── 📂 Dataset
│       ├── 📜 training_set.csv
│       └── 📜 test_set.csv
├── 📂 04_Praktikum
│   ├── 📂 Modul_1
│   │   ├── 📜 Panduan.pdf
│   │   ├── 📜 Laporan_Template.docx
│   │   └── 📂 Hasil
│   │       ├── 📜 Screenshot_1.png
│   │       └── 📜 Model_1.rmp
│   └── 📂 Modul_2
│       ├── 📜 Panduan.pdf
│       └── 📜 Laporan_Contoh.docx
├── 📂 05_Evaluasi
│   ├── 📂 UTS
│   │   ├── 📜 Kisi-kisi.pdf
│   │   ├── 📜 Bank_Soal.md
│   │   └── 📜 Solusi_UTS.ipynb
│   └── 📂 UAS
│       ├── 📜 Panduan_Take_Home.md
│       ├── 📜 Dataset_UAS.csv
│       └── 📂 Contoh_Implementasi
│           ├── 📜 ANN_Model.py
│           └── 📜 Preprocessing.ipynb
├── 📂 06_Tugas_Besar
│   ├── 📜 Panduan.pdf
│   ├── 📂 Proposal
│   │   ├── 📜 Template.docx
│   │   └── 📜 Contoh_Proposal.pdf
│   ├── 📂 Dataset
│   │   ├── 📜 data_utama.csv
│   │   └── 📜 data_pendukung.xlsx
│   └── 📂 Code
│       ├── 📂 Preprocessing
│       │   ├── 📜 cleaning.py
│       │   └── 📜 normalization.ipynb
│       └── 📂 Model
│           ├── 📜 ann_architecture.py
│           └── 📜 training_loop.ipynb
├── 📂 07_Ekstra
│   ├── 📂 Cheatsheet
│   │   ├── 📜 ANN_Cheatsheet.pdf
│   │   └── 📜 RapidMiner_Shortcuts.md
│   └── 📂 Presentasi
│       ├── 📜 Slide_Kelompok_1.pptx
│       └── 📜 Slide_Kelompok_2.pdf
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
