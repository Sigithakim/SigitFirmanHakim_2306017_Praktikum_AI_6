# Tugas-CF-Fuzzy_Logic

## Certainty Factor (CF)

Certainty Factor adalah metode yang digunakan untuk menangani **ketidakpastian dalam sistem pakar**. CF mengukur tingkat keyakinan terhadap suatu kesimpulan berdasarkan gejala-gejala yang diamati.

Nilai CF berada dalam rentang -1 hingga +1:
- `+1` : sangat yakin bahwa fakta **benar**  
- `0` : **netral** atau tidak tahu  
- `-1` : sangat yakin bahwa fakta **salah**

🔍 Dalam studi kasus ini, sistem pakar digunakan untuk **mendiagnosis penyakit** berdasarkan input gejala dari pengguna. Sistem kemudian memberikan hasil diagnosis **beserta tingkat keyakinannya**

---

##  Fuzzy Logic

Fuzzy Logic adalah pendekatan logika yang mampu menangani nilai **ambiguitas atau ketidakpastian**, sangat cocok ketika data tidak bisa dinyatakan secara tegas sebagai benar (1) atau salah (0). Dalam fuzzy logic, kita menggunakan **derajat keanggotaan** antara 0 sampai 1 untuk mewakili tingkat kebenaran suatu kondisi.

###  Komponen utama Fuzzy Logic:
- **Fuzzy Set**: Himpunan kabur (contoh: *suhu tinggi*, *kelembaban sedang*)
- **Membership Function**: Menentukan seberapa besar suatu nilai masuk dalam kategori tertentu  
- **Fuzzification**: Mengubah nilai numerik ke dalam bentuk fuzzy
- **Inference (Aturan IF-THEN)**: Menyusun aksi berdasarkan kombinasi kondisi fuzzy
- **Defuzzification**: Mengubah hasil fuzzy menjadi angka pasti
  
📌 Dalam studi kasus ini, sistem fuzzy digunakan untuk **mengatur kecepatan kipas** berdasarkan suhu 🌡️ dan kelembaban 💧. Aturan fuzzy yang kamu buat memungkinkan sistem bekerja **secara fleksibel dan adaptif terhadap perubahan lingkungan**.
