# Sistem Penyelesaian Tunggal

Sistem persamaan linier dikatakan memiliki penyelesaian tunggal jika semua persamaan berpotongan pada satu titik.

Sistem ini memiliki satu solusi unik yang memenuhi semua persamaan dan tidak ada persamaan yang bergantungan satu sama lain.

contoh :
$$4x + 3y = 10$$
$$2x + 5y = 12$$

- Penyelesaian : 

<iframe scrolling="no" title="Simultaneous Equations:Elimination" src="https://www.geogebra.org/material/iframe/id/MXa3HKy3/width/977/height/574/border/888888/sfsb/true/smb/false/stb/false/stbh/false/ai/false/asb/false/sri/true/rc/false/ld/false/sdz/true/ctl/false" width="977px" height="574px" style="border:0px;"> </iframe>

```
%matplotlib inline
import numpy as np
import matplotlib.pyplot as plt

fig, ax = plt.subplots()
ax.plot(x,(10-4*x)/3)
ax.plot(x,(12-2*x)/5)

ax.text(1,1.6,'$4x+3y = 10$')
ax.text(-3,0.5,'$2x+5y = 12$')

ax.set_xlim(-4,4)
ax.set_ylim(-2,6)
ax.axvline(color='k',linewidth = 1)
ax.axhline(color='k',linewidth = 1)

## This options specifies the ticks based the list of numbers provided.
ax.set_xticks(list(range(-4,5)))
ax.set_aspect('equal')
ax.grid(True,ls=':')
```
![plot](gambar/plot1.png)

Dalam persamaan pertama dan persamaan kedua mewakili dua garis yang berpotongan dalam satu titik.
