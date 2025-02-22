# Sistem Penyelesaian Tak Terhingga

Sistem penyelesaian tak terhingga artinya ada banyak nilai untuk variabel yang dapat memenuhi semua persamaan dalam sistem tersebut. Persamaan persamaan ini bergantung satu sama lain, sehingga penyelesaiannya tak terbatas pada satu titik saja.

contoh :
$$ x + y = 3 $$
$$ 2x + 2y = 6 $$

- Penyelesaian :

<iframe scrolling="no" title="Simultaneous Equations:Elimination" src="https://www.geogebra.org/material/iframe/id/MXa3HKy3/width/977/height/574/border/888888/sfsb/true/smb/false/stb/false/stbh/false/ai/false/asb/false/sri/true/rc/false/ld/false/sdz/true/ctl/false" width="977px" height="574px" style="border:0px;"> </iframe>


```
%matplotlib inline
import numpy as np
import matplotlib.pyplot as plt

fig, ax = plt.subplots()
ax.plot(x,(3-x)/1)
ax.plot(x,(3-x)/1)

ax.text(1,1.6,'$x+y = 3$')
ax.text(0.3,-1.4,'$2x+2y = 6$')

ax.set_xlim(-4,4)
ax.set_ylim(-2,6)
ax.axvline(color='k',linewidth = 1)
ax.axhline(color='k',linewidth = 1)

## This options specifies the ticks based the list of numbers provided.
ax.set_xticks(list(range(-4,5)))
ax.set_aspect('equal')
ax.grid(True,ls=':')
```

![plot](gambar/plot3.png)


Dalam kasus ini persmaan pertama dan persamaan kedua saling berkaitan maka akan menghasilkan garis yang sama. Dalam hal ini, semua titik pada garis tersebut adalah solusi dari sistem persamaan linier tersebut, yang berarti sistem ini memiliki solusi yang tak terhingga banyaknya.


