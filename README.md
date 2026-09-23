# Analisis Data Pemutusan Hubungan Kerja (PHK) Global dengan MySQL

## Deskripsi Proyek
Proyek ini adalah portofolio analisis data menggunakan MySQL untuk menggali informasi dari dataset PHK global (`layoffs.csv`). 
Proyek ini dibagi menjadi dua tahap utama:
1. **Data Cleaning:** Membersihkan data mentah dari nilai NULL dan duplikat.
2. **Exploratory Data Analysis (EDA):** Menganalisis data yang sudah bersih untuk menemukan tren PHK berdasarkan perusahaan, industri, dan negara.

Dalam tahap EDA, saya menerapkan teknik SQL tingkat menengah ke atas, termasuk penggunaan **Common Table Expressions (CTE)** dan **Window Functions (seperti DENSE_RANK)** untuk analisis data runtun waktu dan pemeringkatan.

## File yang Tersedia
* `layoffs.csv` : Dataset mentah.
* `Project Data Cleaning.sql` : Skrip SQL untuk membersihkan dan menstandardisasi data.
* `Project Exploratory Data.sql` : Skrip SQL untuk menggali *insight* dari data yang sudah bersih.

## Hasil Analisis (Insight)

Berdasarkan *Exploratory Data Analysis (EDA)* yang dilakukan, ditemukan tren menarik tentang perusahaan dengan jumlah Pemutusan Hubungan Kerja (PHK) tertinggi pada setiap tahunnya:

*   **Tahun 2020:** **Uber** menduduki peringkat pertama dengan total PHK mencapai **7.525 orang**.
*   **Tahun 2021:** **ByteDance** menempati posisi teratas dengan memberhentikan **3.600 karyawannya**.
*   **Tahun 2022:** Badai PHK meningkat drastis, dipimpin oleh **Meta** yang memangkas **11.000 pekerjaan**.
*   **Tahun 2023 (Puncak Tertinggi):** **Google** mencatatkan rekor PHK terbanyak dengan total **12.000 orang**, menjadi angka tertinggi dibandingkan tahun-tahun sebelumnya.

**Kesimpulan:**
Tren PHK massal ini menunjukkan dampak jangka panjang dari ketidakstabilan ekonomi global. PHK pada tahun 2020 kemungkinan besar merupakan dampak langsung dari pandemi COVID-19 di mana perusahaan memangkas biaya untuk menghindari kebangkrutan. Sementara itu, lonjakan tajam pada tahun 2022 dan 2023 (terutama pada raksasa teknologi seperti Meta dan Google) mengindikasikan adanya koreksi bisnis besar-besaran setelah sebelumnya melakukan perekrutan yang terlalu agresif (over-hiring) selama masa pandemi.
