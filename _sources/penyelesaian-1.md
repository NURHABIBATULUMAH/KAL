# Sistem Penyelesaian Tunggal

Sistem persamaan linier dikatakan memiliki penyelesaian tunggal jika semua persamaan berpotongan pada satu titik.

Sistem ini memiliki satu solusi unik yang memenuhi semua persamaan dan tidak ada persamaan yang bergantungan satu sama lain.

contoh :
<center> 2x + 3y = 5 </center>
<center> 4x - y = 6 </center>

<iframe scrolling="no" title="Simultaneous Equations:Elimination" src="https://www.geogebra.org/material/iframe/id/MXa3HKy3/width/977/height/574/border/888888/sfsb/true/smb/false/stb/false/stbh/false/ai/false/asb/false/sri/true/rc/false/ld/false/sdz/true/ctl/false" width="977px" height="574px" style="border:0px;"> </iframe>

```python
import numpy as np
import matplotlib.pyplot as plt

# Membuat rentang nilai x dari -5 sampai 5
x = np.linspace(-5, 5, 100)

# Membuat grafik dan axes
fig, ax = plt.subplots()

# Persamaan pertama: 2x + 3y = 5, diselesaikan untuk y
ax.plot(x, (5 - 2*x) / 3, label='$2x + 3y = 5$')

# Persamaan kedua: 4x - y = 6, diselesaikan untuk y
ax.plot(x, 4*x - 6, label='$4x - y = 6$')

# Menambahkan teks untuk memberi label pada persamaan
ax.text(1, 1, '$2x + 3y = 5$', fontsize=12)
ax.text(-4, -2, '$4x - y = 6$', fontsize=12)

# Mengatur batas sumbu x dan y
ax.set_xlim(-5, 5)
ax.set_ylim(-5, 5)

# Menambahkan garis horizontal dan vertikal (sumbu x dan y)
ax.axhline(0, color='black', linewidth=1)  # Garis horizontal
ax.axvline(0, color='black', linewidth=1)  # Garis vertikal

# Mengatur tampilan grid
ax.grid(True, linestyle=':')

# Menambahkan label dan legend
ax.set_xlabel('$x$')
ax.set_ylabel('$y$')
ax.legend()

# Menampilkan plot
plt.show()

```

Dalam persamaan pertama dan persamaan kedua mewakili dua garis yang berpotongan dalam satu titik.

