Case: BPJS Hackaton

Repo ini bertujuan untuk sarana pembelajaran bagi pengembang untuk mengasah kemampuan pada bidang penambangan data dengan mengambil case dari BPJS Hackaton.

Case and Cost Prediction (Regression Problem)
Mengembangkan sebuah model data mining untuk melakukan prediksi jumlah kasus dan unit cost pada sebuah daerah akibat penambahan Rumah Sakit kerja sama berdasarkan dataset train yang terdiri atas 57971 observasi
dan 36 variable yaitu:
- row_id : id
- tglpelayanan : periode bulan pelayanan di rumah sakit
- kddati2 = Kode kabupaten/kota
- tkp = tingkat pelayanan; 30:rawat jalan; 40:rawat inap
- peserta = jumlah peserta aktif pada kabupaten/kota periode tersebut
- a,b,c, ... ,sd = tipe rumah sakit yang melayani peserta JKN-KIS
- case : jumlah kunjungan rumah sakit
- unit_cost = jumlah biaya pelayanan rumah sakit

Dengan requirement sebagai berikut.
Kedua kategori tersebut harus dibagi menjadi data training dan data validation berbeda.

Hasil Evaluasi Regression problem:
- Kasus kunjungan: MAE < 900, MAPE < 90%
- Biaya: MAE < 97000, MAPE < 70


Lebih lanjut repo ini akan membandingkan kinerja dari algoritma decision tree dan random forest untuk menentukan evaluasi dari algoritma mana yang lebih baik.
