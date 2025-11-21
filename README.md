# Perbandingan Model Vision Transformer (ViT) dan Swin Transformer

**Mata Kuliah:** Deep Learning (IF25-40401)  
**Institusi:** Institut Teknologi Sumatera (ITERA)

* **Nama:** Eichal Elphindo Ginting
* **NIM:** 122140165

## Deskripsi Proyek
Repository ini berisi kode implementasi untuk membandingkan performa dua arsitektur Vision Transformer pada dataset CIFAR-10:
1. **Vision Transformer (ViT-Base Patch16)**
2. **Swin Transformer (Swin-Base Patch4 Window7)**

Metode yang digunakan adalah Transfer Learning dengan pre-trained weights dari ImageNet.

## Persyaratan Sistem
Proyek ini dikembangkan menggunakan Python. Disarankan menggunakan Google Colab untuk akses GPU, namun dapat juga dijalankan pada mesin lokal.

Library yang diperlukan:
* torch, torchvision
* timm
* scikit-learn
* pandas, numpy
* matplotlib, seaborn

## Instalasi
Jika menjalankan di lingkungan lokal, install dependensi menggunakan perintah berikut di terminal:

```bash
pip install -r requirements.txt
````

## Cara Penggunaan

### Menggunakan Google Colab (Direkomendasikan)

1.  Unduh file `.ipynb` dari repository ini.
2.  Buka Google Colab dan upload file tersebut.
3.  Ubah runtime ke GPU: Pilih menu **Runtime \> Change runtime type \> T4 GPU**.
4.  Jalankan seluruh sel kode secara berurutan (Run All).

### Menggunakan Lingkungan Lokal

1.  Clone repository ini:
    ```bash
    git clone [https://github.com/Eichal-EG/VisionTransformer-Comparison.git](https://github.com/Eichal-EG/VisionTransformer-Comparison.git)
    ```
2.  Masuk ke direktori folder:
    ```bash
    cd VisionTransformer-Comparison
    ```
3.  Jalankan Jupyter Notebook:
    ```bash
    jupyter notebook
    ```
4.  Buka file notebook yang tersedia dan jalankan semua sel.

## Output

Kode program akan menghasilkan:

  * Model yang telah dilatih (fine-tuned).
  * Metrik evaluasi (Akurasi, Precision, Recall, F1-Score).
  * Visualisasi kurva pembelajaran (Loss & Accuracy).
  * Visualisasi Confusion Matrix.
  * Data waktu inferensi rata-rata.

<!-- end list -->

```
```

