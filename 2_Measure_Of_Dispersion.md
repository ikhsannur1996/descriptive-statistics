## 📊 Measure of Dispersion (Ukuran Penyebaran Data)

### 📌 Pengertian

Dalam statistik deskriptif, **Measure of Dispersion** atau **Ukuran Penyebaran Data** adalah metode untuk mengukur **sejauh mana data tersebar** atau **bervariasi** dari nilai pusatnya (seperti mean atau median).

Ukuran ini membantu kita memahami:

> “Seberapa jauh nilai-nilai dalam data menyimpang dari nilai rata-ratanya?”

Dengan kata lain, dua kumpulan data bisa memiliki **mean yang sama**, tetapi **penyebaran yang sangat berbeda**. Oleh karena itu, ukuran penyebaran sangat penting untuk memperoleh gambaran yang lengkap tentang karakteristik data.

---

## 📘 Jenis-jenis Measure of Dispersion

### 1. **Range (Jangkauan)**

**Definisi:**  
Range adalah **selisih antara nilai maksimum dan minimum** dalam data.

**Rumus:**  
\[
\text{Range} = \text{Nilai Maksimum} - \text{Nilai Minimum}
\]

**Contoh:**  
Data: 3, 7, 8, 10, 15  
\[
\text{Range} = 15 - 3 = 12
\]

**Kelebihan:**  
- Mudah dihitung  
**Kekurangan:**  
- Sangat sensitif terhadap **outlier**

---

### 2. **Interquartile Range (IQR)**

**Definisi:**  
IQR adalah **selisih antara kuartil ketiga (Q3) dan kuartil pertama (Q1)**, yang menunjukkan rentang tengah 50% data.

**Rumus:**  
\[
\text{IQR} = Q3 - Q1
\]

**Contoh:**  
Jika Q1 = 4 dan Q3 = 12, maka:
\[
\text{IQR} = 12 - 4 = 8
\]

**Keunggulan:**  
- Tidak terpengaruh oleh outlier  
- Lebih representatif dibanding Range

---

### 3. **Variance (Simpangan Kuadrat Rata-rata)**

**Definisi:**  
Variance mengukur rata-rata dari kuadrat selisih antara setiap nilai data dan mean-nya.

**Rumus untuk sampel:**

\[
s^2 = \frac{\sum (x_i - \bar{x})^2}{n - 1}
\]

di mana:  
- \(x_i\) = nilai data ke-i  
- \(\bar{x}\) = mean  
- \(n\) = jumlah data  

**Contoh sederhana:**  
Jika data = 2, 4, 6 (mean = 4):  
\[
s^2 = \frac{(2 - 4)^2 + (4 - 4)^2 + (6 - 4)^2}{3 - 1} = \frac{4 + 0 + 2^2}{2} = \frac{8}{2} = 4
\]

**Kelemahan:**  
- Nilainya dalam satuan **kuadrat**, sehingga sulit diinterpretasikan secara langsung

---

### 4. **Standard Deviation (Simpangan Baku)**

**Definisi:**  
Standard deviation adalah **akar kuadrat dari variance**. Ukuran ini menunjukkan **seberapa besar penyimpangan rata-rata data terhadap mean**.

**Rumus:**

\[
s = \sqrt{s^2} = \sqrt{\frac{\sum (x_i - \bar{x})^2}{n - 1}}
\]

**Contoh:**  
Dari variance sebelumnya \(s^2 = 4\), maka:
\[
s = \sqrt{4} = 2
\]

**Keunggulan:**  
- Satuan sama dengan data asli  
- Banyak digunakan dalam analisis statistik lanjutan

---

## 📊 Perbandingan Singkat

| Ukuran             | Mengukur Apa?                           | Keunggulan                             | Kekurangan                       |
|--------------------|------------------------------------------|----------------------------------------|----------------------------------|
| **Range**          | Jarak nilai terbesar dan terkecil        | Mudah dihitung                         | Sangat sensitif terhadap outlier |
| **Interquartile Range** | Rentang tengah 50% data           | Stabil terhadap outlier                | Tidak menggunakan seluruh data   |
| **Variance**       | Penyimpangan kuadrat rata-rata dari mean | Dasar untuk analisis statistik lanjut  | Sulit diinterpretasikan langsung |
| **Standard Deviation** | Penyimpangan rata-rata dari mean   | Mudah diinterpretasikan, umum digunakan | Perlu perhitungan lebih lanjut   |

---

## ✅ Kesimpulan

Ukuran penyebaran sangat penting untuk melengkapi informasi yang diberikan oleh ukuran pemusatan. Dua set data bisa memiliki nilai rata-rata yang sama, tetapi tingkat penyebarannya bisa sangat berbeda. Oleh karena itu, **measure of dispersion** diperlukan untuk mengetahui **variabilitas atau keragaman data** secara lebih menyeluruh.

Dalam praktik, **range dan IQR** cocok digunakan untuk analisis awal dan data yang memiliki outlier, sedangkan **variance dan standard deviation** lebih cocok untuk analisis statistik lanjut dan inferensial.

---

## 📚 Referensi

1. Triola, M. F. (2018). *Elementary Statistics* (13th ed.). Pearson.  
2. Rumsey, D. J. (2016). *Statistics For Dummies* (2nd ed.). Wiley.  
3. Khan Academy. “Variance and Standard Deviation.”  
   [https://www.khanacademy.org](https://www.khanacademy.org)  
4. Laerd Statistics. “Descriptive Statistics: Measures of Dispersion.”  
   [https://statistics.laerd.com](https://statistics.laerd.com)
