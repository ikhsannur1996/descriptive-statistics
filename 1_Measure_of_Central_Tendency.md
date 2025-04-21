# 📊 Measure of Central Tendency (Ukuran Pemusatan Data)

## 📌 Pengertian

Dalam statistik deskriptif, **Measure of Central Tendency** atau **Ukuran Pemusatan Data** adalah sekumpulan metode yang digunakan untuk menggambarkan nilai tengah dari suatu kumpulan data. Tujuannya adalah memberikan gambaran umum tentang "nilai tipikal" atau pusat dari data tersebut.

Dengan kata lain, ukuran pemusatan membantu menjawab pertanyaan:

> “Berapa nilai yang paling mewakili data ini?”

---

## 📘 Jenis-jenis Measure of Central Tendency

### 1. 📈 Mean (Rata-rata Hitung)

**Definisi:**  
Mean adalah jumlah seluruh nilai dalam data dibagi dengan jumlah data.

**Rumus:**

\[
\text{Mean} = \frac{\sum x_i}{n}
\]

di mana:
- \( x_i \) = nilai data ke-i  
- \( n \) = jumlah total data

**Contoh:**

Jika lima orang memiliki penghasilan: 3, 4, 5, 6, dan 7 juta:

\[
\text{Mean} = \frac{3 + 4 + 5 + 6 + 7}{5} = \frac{25}{5} = 5 \text{ juta}
\]

**Catatan:**  
Mean sangat **sensitif terhadap outlier** (nilai yang sangat tinggi atau sangat rendah).

---

### 2. 📉 Median (Nilai Tengah)

**Definisi:**  
Median adalah nilai yang berada tepat di tengah data setelah diurutkan.

**Langkah-langkah:**
1. Urutkan data dari terkecil ke terbesar.
2. Jika jumlah data ganjil, median adalah nilai tengah.
3. Jika genap, median adalah rata-rata dari dua nilai tengah.

**Contoh:**
- Data: 2, 4, 6 → Median = 4  
- Data: 2, 4, 6, 8 → Median = (4 + 6) / 2 = 5

**Keunggulan:**  
Median **tidak terpengaruh oleh nilai ekstrem**, sehingga cocok digunakan ketika terdapat outlier.

---

### 3. 📊 Mode (Modus)

**Definisi:**  
Modus adalah nilai yang **paling sering muncul** dalam sekumpulan data.

**Contoh:**

Data: 3, 4, 4, 4, 5, 6 → Modus = 4

**Catatan:**
- Data bisa memiliki **lebih dari satu modus**.
- Bisa juga **tidak memiliki modus** jika semua nilai muncul dengan frekuensi yang sama.

---

## 🔁 Perbandingan Singkat

| Ukuran  | Cocok untuk Data                     | Kelebihan                                       | Kelemahan                                 |
|---------|--------------------------------------|------------------------------------------------|-------------------------------------------|
| **Mean**   | Data normal, tanpa outlier            | Mudah dihitung, berguna dalam analisis statistik lanjutan | Sensitif terhadap nilai ekstrem (outlier) |
| **Median** | Data dengan outlier atau distribusi miring | Stabil terhadap outlier                        | Tidak memanfaatkan semua nilai data       |
| **Mode**   | Data kategori atau diskrit            | Menunjukkan nilai yang paling umum             | Bisa tidak unik atau tidak ada            |

---

## ✅ Kesimpulan

Ukuran pemusatan sangat penting dalam memahami dan menyederhanakan data. Pemilihan metode yang tepat tergantung pada **jenis data** dan **tujuan analisis**. Dalam praktiknya, ketiga ukuran ini sering digunakan **bersama-sama** untuk memberikan gambaran distribusi data yang lebih lengkap.

---

## 📚 Referensi

1. Triola, M. F. (2018). *Elementary Statistics* (13th ed.). Pearson.  
2. Rumsey, D. J. (2016). *Statistics For Dummies* (2nd ed.). Wiley.  
3. Khan Academy. “Mean, Median and Mode.”  
   [https://www.khanacademy.org](https://www.khanacademy.org)  
4. Laerd Statistics. “Descriptive Statistics: Measures of Central Tendency.”  
   [https://statistics.laerd.com](https://statistics.laerd.com)
