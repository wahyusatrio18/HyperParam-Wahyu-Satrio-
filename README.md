Penilaian Risiko Stroke melalui Pemahaman Data Kesehatan 
 
Gambaran Umum Proyek: Penekanan khusus dari proyek ini diletakkan pada bahaya stroke, yang diperkirakan berdasarkan informasi perawatan kesehatan yang tersedia. Kumpulan data terdiri dari berbagai atribut kesehatan seperti jenis kelamin, usia, hipertensi, penyakit jantung, kadar glukosa rata-rata, BMI, dan merokok. Tujuannya dalam kasus penulis adalah untuk membuat model yang memperkirakan probabilitas stroke dengan karakteristik ini. 
 
 Dataset: Dataset yang digunakan memiliki panjang catatan 5.110 dengan 12 bidang yang diuji; 
 
- id: Cara untuk mengidentifikasi setiap pasien untuk menghindari kebingungan dan tetap setia pada catatannya. 
- jenis kelamin: Jenis kelamin pasien: 
- usia: Jenis kelamin pasien 
- hipertensi: Bendera yang menunjukkan status hipertensi pasien; 0, tidak ada hipertensi; 1, ada hipertensi 
- penyakit_jantung: Ini adalah nilai biner yang menunjukkan apakah pasien memiliki penyakit jantung atau tidak. 
- pernah_menikah: Lajang atau menikah atau duda atau janda 
- jenis_pekerjaan: Jenis pekerjaan yang dimiliki pasien 
- Jenis_Tempat_Tinggal: Jenis tempat tinggal: Perkotaan / Pedesaan 
- kadar_glukosa_rata-rata: Kadar glukosa darah dalam kasus konsumen dengan diabetes mellitus 
- bmi: Indeks Massa Tubuh 
- status_merokok: Ini bisa berupa tidak pernah, pernah merokok, sedang merokok, atau tidak diketahui oleh pasien. 
- stroke: Kondisi yang menilai pasien pernah mengalami stroke atau tidak yang nilainya dalam bentuk biner dimana 1 adalah ya dan 0 tidak. 
 
 Analisis dan Pemrosesan Data: 
 
- Analisis Data Eksplorasi (EDA): Digunakan untuk memverifikasi distribusi data, untuk memeriksa adanya 'NA' atau nilai yang hilang, dan untuk mengamati tren yang ada dalam kumpulan data. Beberapa plot dan grafik termasuk saat menggunakan alat seperti Seaborn dan Matplotlib. 
- Pembersihan Data: Beberapa kasus nilai yang hilang diamati terutama pada BMI dan ini ditangani dengan baik Normalisasi data: Ini termasuk menstandarkan nilai fitur dengan menghapus mean dan membaginya dengan standar deviasi untuk kinerja model yang lebih baik. 
- Rekayasa Fitur: Memusnahkan prediktor yang efektif yang membantu dalam memprediksi risiko stroke. 
 
 Pengembangan Model: 
 
 Berbagai model pembelajaran mesin dikembangkan menggunakan pustaka scikit-learn dari Python, termasuk: Berbagai model pembelajaran mesin dikembangkan menggunakan pustaka scikit-learn dari Python, termasuk: 
 - Pengklasifikasi DecisionTree
 - Pengklasifikasi RandomForest
 - Model-model yang digunakan dioptimalkan menggunakan GridSearchCV dan RandomizedSearchCV untuk mendapatkan hiperparameter terbaik. 
 
 Hasil: 
Hasilnya, model Random Forest memberikan akurasi, khususnya nilai yang tinggi dalam hal presisi, recall, dan F1-score. Kinerja model yang diusulkan kemudian dinilai dan dievaluasi dengan membuat matriks kebingungan dan dengan menggunakan teknik validasi silang. 
 
Kesimpulan: Proyek ini mampu menunjukkan bagaimana, dengan menggunakan pembelajaran mesin statistik, risiko stroke dapat dinilai berdasarkan beberapa data spesifik tentang kesehatan seseorang. Model di atas akan

 Teknologi yang Digunakan: 
 
 Library Python yaitu:  
- Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib. 
- Notepad Jupyter 

