Tugas yang di berikan membuktikan bahwa transformasi linier rotasi di bidang 2 dimensi rotasi dalam $R^2$ dengan matriks :

$$A = \begin{bmatrix}
\cos \theta & -\sin \theta \\
\sin \theta & \cos \theta
\end{bmatrix}$$

merupakan transformasi rotasi berlawanan arah jarum jam sebesar sudut $\theta$

pembuktian

Misalkan suatu vektor $V=(x,y)$ dalam koordinat kartesian. Kita dapat menyatakannya dalam koordinat polar sebagai:

$$
\mathbf{v} = (x, y) = (r \cos \alpha, r \sin \alpha)
$$

dengan 

$r = \left\| V \right\|$ (panjang vektor)

$\alpha$ adalah sudut antara vektor $v$ dengan sumbu-x positif

Transformasi $A$ bertindak pada $V$ sebagai berikut:

$$\mathbf{A} \cdot \mathbf{v} = 
\begin{bmatrix}
\cos \theta & -\sin \theta \\
\sin \theta & \cos \theta
\end{bmatrix}
\begin{bmatrix}
r \cos \alpha \\
r \sin \alpha
\end{bmatrix} 
= r \begin{bmatrix}
\cos \theta \cos \alpha - \sin \theta \sin \alpha \\
\sin \theta \cos \alpha + \cos \theta \sin \alpha
\end{bmatrix}$$

Gunakan identitas trigonometri:

$$\begin{align*}
\cos(\alpha + \theta) & = \cos \alpha \cos \theta - \sin \alpha \sin \theta \\
\sin(\alpha + \theta) & = \sin \alpha \cos \theta + \cos \alpha \sin \theta
\end{align*}$$

Sehingga:

$$
A \cdot \mathbf{v} = r \left( \cos(\alpha + \theta), \sin(\alpha + \theta) \right)
$$

Artinya, vektor hasil adalah vektor dengan panjang yang sama (karena rotasi mempertahankan panjang), dan sudut terhadap sumbu-x sebesar $\alpha + \theta$, yaitu berputar berlawanan arah jarum jam sebesar $\theta$

jadi transformasi linier dengan matriks rotasi $A$ tersebut memang merepresentasikan rotasi sebesar sudut $\theta$ berlawanan arah jarum jam di bidang $R^2$