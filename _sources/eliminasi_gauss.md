## Penyelesaian Sistem Persamaan Linear

### soal no 3 sistem persamaan:

$$
2x_1 + 2x_2 = 4
$$
$$
x_1 + x_2 = 2
$$

buat sistem ini dalam bentuk matriks augmented:

$$
\begin{bmatrix}
2 & 2 & | & 4 \\
1 & 1 & | & 2
\end{bmatrix}
$$

1. membuat elemen di bawah pivot menjadi nol. 

$$
R_1 \leftarrow R_1 - 2R_2
$$

2. Setelah melakukan perhitungan, kita mendapatkan:

$$
R_1: \quad 2 - 2 \cdot 1 = 0 \\
2 - 2 \cdot 1 = 0 \\
4 - 2 \cdot 2 = 0
$$

Sehingga, matriks augmented menjadi:

$$
\begin{bmatrix}
1 & 1 & | & 2 \\
0 & 0 & | & 0
\end{bmatrix}
$$

Dari baris kedua, kita dapat mengekspresikan \(x_1\) dalam bentuk \(x_2\):

$$
x_1 + x_2 = 2 \implies x_1 = 2 - x_2
$$

Karena kita memiliki satu persamaan dengan dua variabel, kita dapat menyatakan solusi dalam bentuk parameter. Misalkan \(x_2 = t\), maka:

$$
x_1 = 2 - t
$$

Jadi, solusi umum dari sistem persamaan ini adalah:

$$
\begin{cases}
x_1 = 2 - p \\
x_2 = p
\end{cases}
$$

di mana \(p\) adalah parameter bebas.


### soal no 4 sistem persamaan:

$$
x_1 + x_2 = 5
$$
$$
x_1 + 2x_3 = 6
$$

Kita akan menyelesaikannya menggunakan metode eliminasi Gauss. Pertama, kita tuliskan sistem ini dalam bentuk matriks augmented:

$$
\begin{bmatrix}
1 & 1 & 0 & | & 5 \\
1 & 0 & 2 & | & 6
\end{bmatrix}
$$

Langkah pertama adalah membuat elemen di bawah pivot (elemen pertama di kolom pertama) menjadi nol. Kita lakukan operasi berikut:

$$
R_2 \leftarrow R_2 - R_1
$$

Setelah melakukan perhitungan, kita mendapatkan:

$$
R_2: \quad 1 - 1 = 0 \\
0 - 1 = -1 \\
2 - 0 = 2 \\
6 - 5 = 1
$$

Sehingga, matriks augmented menjadi:

$$
\begin{bmatrix}
1 & 1 & 0 & | & 5 \\
0 & -1 & 2 & | & 1
\end{bmatrix}
$$

Selanjutnya, kita dapat menyelesaikan baris kedua untuk mengekspresikan \(x_2\) dalam bentuk \(x_3\):

$$
-1x_2 + 2x_3 = 1 \implies x_2 = 2x_3 - 1
$$

Sekarang kita substitusi \(x_2\) ke dalam persamaan pertama:

$$
x_1 + (2x_3 - 1) = 5
$$

Maka kita dapatkan:

$$
x_1 + 2x_3 - 1 = 5 \implies x_1 = 6 - 2x_3
$$

Karena kita memiliki dua persamaan dengan tiga variabel, kita dapat menyatakan solusi dalam bentuk parameter. Misalkan \(x_3 = p\), maka:

$$
x_1 = 6 - 2p
$$
$$
x_2 = 2p - 1
$$
$$
x_3 = p
$$

Jadi, solusi umum dari sistem persamaan ini adalah:

$$
\begin{cases}
x_1 = 6 - 2p \\
x_2 = 2p - 1 \\
x_3 = p
\end{cases}
$$

di mana \(p\) adalah parameter bebas.


### soal no 1 sistem persamaan:


Contoh Soal 1

\begin{aligned}
x_1 + 2x_2 + 3x_3 &= 6 \\
2x_1 + 4x_2 + 6x_3 &= 12 \\
x_3 - x_2 &= 2
\end{aligned}

Matriks augmented:

\begin{bmatrix}
1 & 2 & 3 & | 6 \\
2 & 4 & 6 & | 12 \\
0 & -1 & 1 & | 2
\end{bmatrix}

Baris kedua dikurangi 2 kali baris pertama:

\begin{bmatrix}
1 & 2 & 3 & | 6 \\
0 & 0 & 0 & | 0 \\
0 & -1 & 1 & | 2
\end{bmatrix}

Baris kedua menjadi nol, menunjukkan bahwa sistem memiliki solusi tak hingga.
Variabel bebas: , maka

x_2 = t - 2, \quad x_1 = -2x_2 - 3x_3 + 6 = -2(t-2) - 3t + 6 = -5t + 10.

\begin{aligned}
x_1 &= -5t + 10, \\
x_2 &= t - 2, \\
x_3 &= t, \quad t \in \mathbb{R}.
\end{aligned}


---

Contoh Soal 2

\begin{aligned}
x_1 + x_2 + x_3 &= 3 \\
2x_1 + 0x_2 + x_3 &= 5 \\
x_1 - 2x_2 + 0x_3 &= 3
\end{aligned}

Matriks augmented:

\begin{bmatrix}
1 & 1 & 1 & | 3 \\
2 & 0 & 1 & | 5 \\
1 & -2 & 0 & | 3
\end{bmatrix}

Eliminasi dengan mengurangi baris kedua dengan 2 kali baris pertama:

\begin{bmatrix}
1 & 1 & 1 & | 3 \\
0 & -2 & -1 & | -1 \\
1 & -2 & 0 & | 3
\end{bmatrix}

\begin{bmatrix}
1 & 1 & 1 & | 3 \\
0 & -2 & -1 & | -1 \\
0 & -3 & -1 & | 0
\end{bmatrix}

Eliminasi dengan mengubah baris ketiga:

B_3 = B_3 - \frac{3}{2} B_2

\begin{bmatrix} 1 & 1 & 1 & | 3 \ 0 & -2 & -1 & | -1 \ 0 & 0 & \frac{1}{2} & | -\frac{3}{2} \end{bmatrix} ]

Dari baris ketiga:

x_3 = -3.

-2x_2 -1(-3) = -1 \Rightarrow -2x_2 +3 = -1 \Rightarrow -2x_2 = -4 \Rightarrow x_2 = 2.

x_1 + 2 + (-3) = 3 \Rightarrow x_1 -1 = 3 \Rightarrow x_1 = 4.

(x_1, x_2, x_3) = (4, 2, -3).


---

Contoh Soal 3

\begin{aligned}
2x_1 + 2x_2 &= Y \\
x_1 + x_2 &= 2
\end{aligned}

Matriks augmented:

\begin{bmatrix}
2 & 2 & | Y \\
1 & 1 & | 2
\end{bmatrix}

Eliminasi dengan membagi baris pertama dengan 2:

\begin{bmatrix}
1 & 1 & | \frac{Y}{2} \\
1 & 1 & | 2
\end{bmatrix}

Kurangi baris kedua dengan baris pertama:

\begin{bmatrix}
1 & 1 & | \frac{Y}{2} \\
0 & 0 & | 2 - \frac{Y}{2}
\end{bmatrix}

Jika , baris kedua menjadi , sehingga ada solusi tak hingga:

x_1 = 2 - x_2.