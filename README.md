Overview
Forecasting Kualitas Udara Jakarta: Prediksi PM2.5 Harian
Owen, peneliti di Pusat Studi Udara Institut Tanpa Batuk, setiap pagi menerima pertanyaan yang sama dari banyak pihak: bagaimana kualitas udara Jakarta beberapa minggu ke depan? Sekolah ingin tahu kapan kegiatan luar ruang sebaiknya dikurangi, puskesmas ingin menyiapkan stok masker dan obat pernapasan, dan warga ingin tahu kapan aman berolahraga di luar. Owen ingin menjawab berdasarkan data, bukan sekadar perasaan bahwa "langit hari ini kelihatan agak abu-abu".

Data yang ia punya cukup banyak. Ada catatan indeks PM2.5 harian selama lima tahun, laporan ISPU dari lima stasiun pemantau, data suhu dan sinar UV, serta estimasi model atmosfer. Masalahnya, membaca pola dari semua catatan itu secara manual memakan waktu, sementara pertanyaan terus berdatangan. Owen lalu mencoba membangun model forecasting yang dapat memperkirakan indeks PM2.5 harian beberapa bulan ke depan. Prakiraan itu akan menjadi bahan awal bagi tim untuk menyusun imbauan, sedangkan keputusan akhir tetap dibahas bersama para ahli kesehatan lingkungan.

Tugas ini tidak sederhana. Kualitas udara Jakarta naik turun mengikuti musim: lebih bersih ketika hujan turun deras di awal tahun dan memburuk saat kemarau. Namun, pola itu tidak selalu rapi. Libur panjang mengubah arus kendaraan, hujan yang datang terlambat menggeser musim, dan sensor pemantau kadang berhenti mencatat. Untuk periode yang diprediksi, Owen juga hanya memegang kalender hari libur. Model perlu tetap berguna dalam kondisi itu, cukup akurat untuk membantu perencanaan dan cukup stabil untuk tidak panik oleh satu hari yang janggal.

Start

a day ago
Close

a day to go
Description
Dalam kompetisi ini, peserta diminta membangun model forecasting untuk memprediksi indeks PM2.5 harian Jakarta pada 1 Januari 2026 sampai 31 Maret 2026 (90 hari). Data historis yang tersedia mencakup 1 Januari 2021 sampai 31 Desember 2025.

Target pm25 adalah indeks AQI PM2.5 menurut standar US EPA, bukan konsentrasi dalam µg/m³. Nilai ini berasal dari World Air Quality Index Project (aqicn.org) untuk wilayah Jakarta. Sebagai gambaran skalanya:

Rentang AQI	Kategori US EPA
0-50	Good (Baik)
51-100	Moderate (Sedang)
101-150	Unhealthy for Sensitive Groups (Tidak sehat bagi kelompok sensitif)
151-200	Unhealthy (Tidak sehat)
201-300	Very Unhealthy (Sangat tidak sehat)
> 300	Hazardous (Berbahaya)
Selain target, peserta mendapat data pendukung berupa suhu dan indeks UV harian, indikator hari libur nasional dan cuti bersama, ISPU dari lima stasiun pemantau DKI Jakarta, serta estimasi model atmosfer CAMS. Untuk periode prediksi, data yang tersedia hanya kalender hari libur, seperti kondisi memprakirakan masa depan yang sebenarnya.

Data target tidak tercatat pada sumber untuk beberapa tanggal. Pada tanggal-tanggal tersebut kolom pm25 dibiarkan kosong, tetapi data lain tetap dicantumkan.

Prediksi model memberi perkiraan awal untuk membantu penyusunan imbauan kualitas udara. Keputusan akhir tetap ditinjau oleh pihak yang berwenang.

Evaluation
Performa prediksi dinilai menggunakan Mean Absolute Error (MAE), yaitu rata-rata selisih mutlak antara nilai prediksi dan nilai aktual. Nilai yang lebih kecil lebih baik.


di mana n adalah jumlah tanggal yang dinilai, y_i adalah nilai pm25 aktual pada tanggal ke-i, dan ŷ_i adalah nilai pm25 prediksi pada tanggal ke-i.

MAE dibaca langsung dalam satuan poin AQI. Misalnya, MAE 15 berarti prediksi rata-rata meleset 15 poin AQI per hari. Tanggal pada periode uji yang tidak tercatat di sumber tetap wajib diisi pada submission, tetapi tidak ikut dinilai.
