# Sistem Informasi Geografis (SIG) Prediksi Daerah Rawan Banjir

Repository ini berisi proyek Sistem Informasi Geografis (SIG) untuk prediksi daerah rawan banjir menggunakan data spasial dan non-spasial di wilayah Kabupaten Mukomuko, Provinsi Bengkulu.

## Deskripsi Proyek

Proyek ini menggunakan data curah hujan, kemiringan lereng, penggunaan lahan, dan ketinggian wilayah untuk memodelkan prediksi risiko banjir di beberapa kecamatan di Kabupaten Mukomuko. Metode machine learning yang digunakan adalah Random Forest Classifier untuk klasifikasi rawan banjir.

Visualisasi peta interaktif dibuat menggunakan Folium, yang menampilkan wilayah dengan kode warna:  
- **Merah** = Rawan Banjir  
- **Hijau** = Aman

## Struktur Repository

- `data/`  
  Folder berisi file-file data CSV seperti data curah hujan, penggunaan lahan, data non spasial, dan data historis banjir.

- `Prediksi-Banjir-ProvBengkulu.ipynb`  
  Notebook Jupyter yang memuat proses loading data, preprocessing, pelatihan model, evaluasi, dan pembuatan peta interaktif.

- `peta_prediksi_banjir.html`  
  File output peta interaktif dalam format HTML.

- `[geosai.my.id]Bengkulu_Kab.zip`  
  File ZIP berisi data GeoJSON batas wilayah Kabupaten dan kecamatan sebagai data spasial.

- `README.md`  
  Dokumentasi proyek (file ini).

## Cara Menggunakan

1. **Clone repository**  
   ```bash
   git clone https://github.com/BaimMudrik182/UAS-SIG.git
   cd UAS-SIG
## NAMA DAN NPM
NAMA : BAIM MUDRIK AZIZ
NPM  : G1A022071
