## 📊 Persentil dan Kuartil dalam Statistik Deskriptif

### 📌 Pengantar

Dalam statistik deskriptif, **persentil** dan **kuartil** termasuk dalam kelompok ukuran **letak** (measures of position). Ukuran ini digunakan untuk mengetahui **posisi suatu data** dalam kumpulan data secara keseluruhan.

> Mereka membantu kita menjawab pertanyaan:  
> “Di bagian mana posisi nilai tertentu dalam distribusi data?”

---

## 🧮 Apa itu Persentil?

### 🎯 Pengertian

**Persentil** membagi data yang sudah diurutkan menjadi **100 bagian yang sama besar**. Setiap persentil menunjukkan **prosentase** data yang berada **di bawah** nilai tersebut.

- **Persentil ke-25 (P25)** → 25% data berada di bawah nilai ini  
- **Persentil ke-50 (P50)** → 50% data (sama dengan median)  
- **Persentil ke-90 (P90)** → 90% data berada di bawah nilai ini  

### 📘 Contoh

Misalkan terdapat 100 nilai ujian yang sudah diurutkan, dan nilai pada posisi ke-75 adalah 88. Maka:

> Nilai **88** adalah **persentil ke-75**, artinya **75% siswa mendapat nilai 88 atau kurang.**

---

## 🧮 Apa itu Kuartil?

### 🎯 Pengertian

**Kuartil** membagi data menjadi **empat bagian yang sama besar**. Kuartil adalah **jenis khusus dari persentil**:

- **Kuartil 1 (Q1)** = Persentil ke-25 (P25)  
- **Kuartil 2 (Q2)** = Persentil ke-50 (P50) = Median  
- **Kuartil 3 (Q3)** = Persentil ke-75 (P75)

### 📘 Fungsi Kuartil

Kuartil berguna untuk:
- Mengukur **penyebaran data**
- Menghitung **Interquartile Range (IQR)**:  
  \[
  \text{IQR} = Q3 - Q1
  \]
- Mengidentifikasi **outlier** (nilai pencilan)

---

## 🔢 Ilustrasi Data

Misalkan data berikut sudah diurutkan:

`50, 55, 60, 65, 70, 75, 80, 85, 90, 95`

- **Q1 (Kuartil 1)** = 60  
- **Q2 (Median)** = 72.5  
- **Q3 (Kuartil 3)** = 85  

Artinya:
- 25% data bernilai kurang dari atau sama dengan 60  
- 50% data bernilai kurang dari atau sama dengan 72.5  
- 75% data bernilai kurang dari atau sama dengan 85

---

## 📊 Perbandingan: Persentil vs Kuartil

| Aspek         | Persentil                          | Kuartil                        |
|---------------|-------------------------------------|--------------------------------|
| Pembagian     | Membagi data menjadi 100 bagian     | Membagi data menjadi 4 bagian |
| Notasi        | P1, P2, ..., P99                   | Q1, Q2, Q3                     |
| Hubungan      | Q1 = P25, Q2 = P50, Q3 = P75       | Bagian dari persentil         |
| Fungsi Umum   | Menentukan posisi relatif dalam data| Mengukur penyebaran data       |

---

## ✅ Kesimpulan

**Persentil** dan **kuartil** membantu menggambarkan **sebaran data** dan **posisi nilai** dalam suatu distribusi.  
- **Kuartil** lebih sering digunakan dalam visualisasi seperti **boxplot**  
- **Persentil** umum digunakan dalam **penilaian pendidikan**, **kesehatan**, dan **analisis performa**

Keduanya memberikan informasi penting yang **tidak bisa disampaikan hanya dengan mean atau median saja**.

---

## 📚 Referensi

1. Triola, M. F. (2018). *Elementary Statistics* (13th ed.). Pearson.  
2. Rumsey, D. J. (2016). *Statistics For Dummies* (2nd ed.). Wiley.  
3. Khan Academy. “Percentiles and Quartiles.”  
   [https://www.khanacademy.org](https://www.khanacademy.org)  
4. Laerd Statistics. “Descriptive Statistics: Percentiles and Quartiles.”  
   [https://statistics.laerd.com](https://statistics.laerd.com)
