# Sistem Tidak Ada Penyelesaian

Sistem tidak ada penyelesaian artinya tidak ada variable yang bisa memenuhi semua persamaan dalam sistem tersebut.
Persamaan dalam sistem ini selalu bertentangan satu sama lain sehingga tidak mungkin memiliki solusi. Dalam 2 dimensi persamaan tersebut tidak akan memiliki titik potong.

contoh :

$$x + y = 5 $$

$$x + y = 3 $$

- Penyelesaian :

<iframe scrolling="no" title="Simultaneous Equations:Elimination" src="https://www.geogebra.org/material/iframe/id/MXa3HKy3/width/977/height/574/border/888888/sfsb/true/smb/false/stb/false/stbh/false/ai/false/asb/false/sri/true/rc/false/ld/false/sdz/true/ctl/false" width="977px" height="574px" style="border:0px;"> </iframe>


```
%matplotlib inline
import numpy as np
import matplotlib.pyplot as plt

fig, ax = plt.subplots()
ax.plot(x,(5-x)/1)
ax.plot(x,(3-x)/1)

ax.text(1,1.6,'$x+y = 5$')
ax.text(0.3,-1.4,'$x+y = 3$')

ax.set_xlim(-4,4)
ax.set_ylim(-2,6)
ax.axvline(color='k',linewidth = 1)
ax.axhline(color='k',linewidth = 1)

## This options specifies the ticks based the list of numbers provided.
ax.set_xticks(list(range(-4,5)))
ax.set_aspect('equal')
ax.grid(True,ls=':')
```

![plot](gambar/plot2.png)


Dalam kasus tersebut, pada persamaan pertama $x + y = 5$ dan pada persamaan kedua $x + y = 3$. Ini bertentangan karena tidak mungkin $(x+y)$ bernilai dua angka berbeda pada waktu bersamaan. 

Jadi dalam grafik ini dua garis yang mewakili persamaan tersebut tidak akan berpotongan.
