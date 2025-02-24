###Contoh soal eliminasi gauss
 soal no 3:

$2x_1+2x_2=4$

$x_1+x_2$

\[
\begin{bmatrix}
2 & 2 & | & 4 \\
1 & 1 & | & 2
\end{bmatrix}
\]

Langkah pertama adalah membuat elemen di bawah pivot menjadi nol. Kita lakukan operasi berikut:

\[
R_1 \leftarrow R_1 - 2R_2
\]

Setelah melakukan perhitungan, kita mendapatkan:

\[
R_1: \quad 2 - 2 \cdot 1 = 0 \\
2 - 2 \cdot 1 = 0 \\
4 - 2 \cdot 2 = 0
\]

Sehingga, matriks augmented menjadi:

\[
\begin{bmatrix}
0 & 0 & | & 0 \\
1 & 1 & | & 2
\end{bmatrix}
\]

Dari baris kedua, kita dapat mengekspresikan \(x_1\) dalam bentuk \(x_2\):

\[
x_1 + x_2 = 2 \implies x_1 = 2 - x_2
\]

Karena kita memiliki satu persamaan dengan dua variabel, kita dapat menyatakan solusi dalam bentuk parameter. Misalkan \(x_2 = t\), maka:

\[
x_1 = 2 - t
\]

Jadi, solusi umum dari sistem persamaan ini adalah:

\[
\begin{cases}
x_1 = 2 - t \\
x_2 = t
\end{cases}
\]

di mana \(t\) adalah parameter bebas.

