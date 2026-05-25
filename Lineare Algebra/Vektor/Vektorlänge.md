Hier sind die zwei überarbeiteten Dateien:
markdown# 02-vektoroperationen/vektorlange.md

### Definition:
Die Länge (auch Norm oder Betrag genannt) eines Vektors ist die Distanz vom Ursprung zum Endpunkt des Vektors. Sie wird mit $|\vec{a}|$ oder $\|\vec{a}\|$ notiert und ist immer eine positive reelle Zahl (oder 0 für den Nullvektor).

# Berechnung (Euklidische Norm / L2-Norm):

Die Länge eines Vektors $\vec{a} = \begin{pmatrix} a_1 \\ a_2 \\ a_3 \end{pmatrix}$ berechnet sich durch:

$$|\vec{a}| = \sqrt{a_1^2 + a_2^2 + a_3^2}$$

Allgemein für n-dimensionale Vektoren:
$$|\vec{a}| = \sqrt{\sum_{i=1}^{n} a_i^2}$$

# Praktische Beispiele:

### 2D Vektor:
$$\vec{a} = \begin{pmatrix} 3 \\ 4 \end{pmatrix}$$
$$|\vec{a}| = \sqrt{3^2 + 4^2} = \sqrt{9 + 16} = \sqrt{25} = 5$$

### 3D Vektor:
$$\vec{b} = \begin{pmatrix} 1 \\ 2 \\ 2 \end{pmatrix}$$
$$|\vec{b}| = \sqrt{1^2 + 2^2 + 2^2} = \sqrt{1 + 4 + 4} = \sqrt{9} = 3$$

# Eigenschaften:

- ### Nicht-Negativität:
    - $|\vec{a}| \geq 0$ für alle Vektoren
    - $|\vec{a}| = 0$ nur wenn $\vec{a} = \vec{0}$ (Nullvektor)

- ### Skalarmultiplikation:
    - $|s \cdot \vec{a}| = |s| \cdot |\vec{a}|$ (Länge wird um Faktor gestreckt)

- ### Dreiecksungleichung:
    - $|\vec{a} + \vec{b}| \leq |\vec{a}| + |\vec{b}|$

# Verbindung zum Skalarprodukt:

Die Länge eines Vektors kann auch über das [[Skalarprodukt]] ausgedrückt werden:
$$|\vec{a}| = \sqrt{\vec{a} \cdot \vec{a}}$$