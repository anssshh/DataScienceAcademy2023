# Analisis hubungan antara tingkat pendidikan penduduk dan frekuensi kejadian banjir di Jakarta
Model yang digunakan dalam penelitian ini adalah regresi linier, dengan mean squared error (MSE) sebagai metrik evaluasi. Hasil evaluasi model menunjukkan nilai MSE sebesar 1.93. Mengingat bahwa dalam MSE, semakin kecil nilainya maka semakin baik performa model, maka nilai ini mengindikasikan bahwa model yang dibangun memiliki performa yang cukup baik dalam memprediksi variabel target.

Selain menggunakan pendekatan regresi, kami juga melakukan pengujian hipotesis untuk mengetahui pengaruh tingkat pendidikan terhadap tingkat banjir di Jakarta. Terdapat dua variabel bebas yang digunakan, yaitu:

- X₁: Tingkat pendidikan "Tidak Bersekolah – Tamat SD"
- X₂: Tingkat pendidikan "SLTP – Strata III" Pada persamaan regresi yang dihasilkan, nilai koefisien untuk variabel X₂ (SLTP – Strata III) adalah negatif. Hal ini mengindikasikan bahwa peningkatan tingkat pendidikan hingga level SLTP ke atas tidak menunjukkan pengaruh positif yang signifikan terhadap penurunan atau peningkatan tingkat banjir. Hasil pengujian menunjukkan nilai:
- F hitung = 2,07146293
- F tabel = 3,49 (F{(0,95)(2), (20)}) Karena F hitung < F tabel, maka keputusan yang diambil adalah menerima H₀ dan menolak Hₐ, sehingga dapat disimpulkan bahwa tingkat pendidikan tidak memiliki pengaruh yang signifikan terhadap tingkat banjir di Jakarta.

Berdasarkan hasil analisis regresi dan pengujian hipotesis, dapat disimpulkan bahwa tidak terdapat hubungan yang signifikan antara tingkat pendidikan masyarakat dan tingkat kejadian banjir di Jakarta.
