# Operasi Baris Elementer

Sebelumnya, kita mengetahui terlebih dahulu **Konsep Dasar Matriks**.

**Matriks** adalah kumpulan bilangan yang disusun dalam baris dan kolom.

contoh: 

$$
\begin{bmatrix}
1 & 3 & 5 \\
2 & 4 & 6 \\
7 & 8 & 9
\end{bmatrix}
$$

Note:

$ R_1, R_2, R_3  $, untuk baris pertama, kedua, ketiga.

### Tiga Jenis Operasi Baris Elementer

#### 1. Menukar dua baris

Notasi: $R_i \leftrightarrow R_j$

contoh: Menukar baris pertama $R_1$ dengan baris kedua $R_2$.

#### 2. Mengalikan baris dengan skala non-nol

Notasi: $R_i \rightarrow k . R_i$ dimana k $\neq 0$ 

contoh: Mengalikan baris pertama dengan 3 ($R_1 \rightarrow 3R_1$)

#### 3. Menambahkan kelipatan satu baris ke baris lain

Notasi: $R_i \rightarrow R_i +  k . R_j$

contoh: Menambahkan dua kali baris kedua ke baris pertama $(R_1 \rightarrow R_1 + 2R_2)$

### Contoh Operasi Baris Elementer

Matriks Awal: 

$$
\begin{bmatrix}
2 & 4 & 6 \\
8 & 10 & 12 \\
5 & 3 & 1
\end{bmatrix}
$$

Langkah 1: Menukar $R_1$ dan $R_2$

$$
\begin{bmatrix}
8 & 10 & 12 \\
2 & 4 & 6 \\
5 & 3 & 1
\end{bmatrix}
$$

Langkah 2: Mengalikan $R_3$ dengan $2$:

$$
\begin{bmatrix}
8 & 10 & 12 \\
2 & 4 & 6 \\
10 & 6 & 2
\end{bmatrix}
$$

Langkah 3: Menambahkan $-3R_1$ ke $R_3$:

$$
\begin{bmatrix}
8 & 10 & 12 \\
2 & 4 & 6 \\
-14 & -24 & -34
\end{bmatrix}
$$

### Bentuk Eselon Baris dan Eselon Baris Tereduksi

#### a. Bentuk Eselon Baris: 
- Baris nol berada di bawah baris non-nol
- Elemen pivot (elemen pertama non-nol pada suatu baris) berada di kanan elemen pivot baris Sebelumnya

#### b. Bentuk Eselon Baris Tereduksi:
- Memenuhi semua syarat bentuk eselon baris
- Setiap elemen pivot bernilai 1
- Kolom yang mengandung elemen pivot hanya memiliki satu elemen non-nol (yaitu pivot)

### Aplikasi Baris Elementer

#### 1. Menyelesaikan Sistem Persamaan Linier
- Menggunakan eliminasi gauss atau gauss-jordan
#### 2. Mencari Invers Matriks 
- Menggabungkan matriks dengan matriks identitas dan melakukan OBE hingga diperoleh invers

#### 3. Menghitung Determinan 
- Menggunakan reduksi baris untuk menyederhanakan perhitungan determinan 

### Contoh Soal:
Selesaikan sistem persamaan berikut menggunakan OBE:

$$x+2y-3z=8$$
$$2x-y+2z=6$$
$$x-y+z=4$$

Penyelesaiam:
1. Ubah ke bentuk matriks augmentasi
2. Lakukan OBE hingga memperoleh bentuk eselon baris Tereduksi
3. Interprestasikan hasilnya

### Jawaban:
Pada soal di atas terdiri dari beberapa persamaan linier yang disebut dengan sistem persamaan linier 