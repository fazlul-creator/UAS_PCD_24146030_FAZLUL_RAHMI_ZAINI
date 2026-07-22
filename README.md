# Ujian Akhir Semester (UAS) - Pengolahan Citra Digital (SIF202)

## Identitas Mahasiswa
- **Nama Lengkap:** FAZLUL RAHMI ZAINI
- **NIM:** 24146030
- **Mata Kuliah:** Pengolahan Citra Digital (SIF202)
- **Tahun Ajaran:** Genap 2025/2026
- **Dosen Pengampu:** Teuku Rizky Noviandy, S.Kom., M.Kom.

---

## Deskripsi Proyek
Proyek ini merupakan bentuk evaluasi Ujian Akhir Semester untuk mengimplementasikan klasifikasi citra menggunakan algoritma **Multi-Layer Perceptron (MLP)** berdasarkan dataset *Flowers Recognition* dari Kaggle.

## Metodologi
1. **Preprocessing Data**:
   - Memuat citra dari folder kelas.
   - Resizing dimensi gambar ke `64 x 64` piksel.
   - Normalisasi nilai piksel ke skala `[0, 1]`.
   - Flattening gambar 3D menjadi vektor fitur 1D.
2. **Data Splitting**:
   - 80% Data Latih (Training) & 20% Data Uji (Testing).
   - Parameter `random_state = 24146030` (sesuai NIM).
3. **Pemodelan**:
   - Membangun jaringan syaraf tiruan menggunakan `MLPClassifier`.
4. **Evaluasi**:
   - Menghitung nilai Precision, Recall, F1-Score, dan Accuracy menggunakan `classification_report(digits=4)`.
   - Visualisasi hasil prediksi pada sampel gambar uji.

## Berkas Repository
- `UAS_PCD_24146030_FAZLUL_RAHMI_ZAINI.ipynb`: Source code Jupyter Notebook.
- `Laporan_UAS_PCD_24146030_FAZLUL_RAHMI_ZAINI.pdf`: Laporan proyek format PDF.
- `README.md`: Dokumentasi repository.