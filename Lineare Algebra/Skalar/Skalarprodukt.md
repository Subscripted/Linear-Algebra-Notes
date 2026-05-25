### Definition:
Das Skalarprodukt (auch inneres Produkt oder Dot Product genannt) ist eine mathematische Verknüpfung zweier Vektoren, deren Ergebnis eine reelle Zahl (ein [[Skalare|Skalar]]) ist, nicht ein Vektor. Es dient zentral dazu, Winkel zwischen Vektoren zu berechnen, [[Vektorlange|Längen]] zu bestimmen oder Orthogonalität (90°-Winkel) zu prüfen.

# Berechnung des Skalarprodukts:

Das Skalarprodukt zweier Vektoren $\vec{a}$ und $\vec{b}$ wird berechnet durch die Summe der Produkte entsprechender Komponenten:

$$\vec{a} \cdot \vec{b} = \sum_{i=1}^{n} a_i b_i$$

oder ausgeschrieben:

$$\vec{a} \cdot \vec{b} = (a_1 \cdot b_1) + (a_2 \cdot b_2) + (a_3 \cdot b_3) + \ldots + (a_n \cdot b_n)$$

# Praktisches Beispiel:

$$\vec{a} = \begin{pmatrix} 2 \\ 3 \\ 1 \end{pmatrix}, \quad \vec{b} = \begin{pmatrix} 4 \\ 1 \\ 5 \end{pmatrix}$$

$$\vec{a} \cdot \vec{b} = (2 \cdot 4) + (3 \cdot 1) + (1 \cdot 5) = 8 + 3 + 5 = 16$$

# Interpretation des Skalarprodukts:

Das Skalarprodukt sagt aus: **Wie stark zeigen zwei Vektoren in eine bzw. dieselbe Richtung.**

- ### Positives Skalarprodukt ($\vec{a} \cdot \vec{b} > 0$):
  - Die Vektoren zeigen in eine ähnliche Richtung
  - Sie bilden einen **spitzen Winkel** (< 90°)

- ### Skalarprodukt gleich Null ($\vec{a} \cdot \vec{b} = 0$):
  - Die Vektoren stehen **senkrecht aufeinander** (orthogonal)
  - Der Winkel beträgt genau 90°

- ### Negatives Skalarprodukt ($\vec{a} \cdot \vec{b} < 0$):
  - Die Vektoren zeigen in entgegengesetzte Richtungen
  - Sie bilden einen **stumpfen Winkel** (> 90°)

# Winkel zwischen zwei Vektoren berechnen:

Um den Winkel $\theta$ zwischen zwei Vektoren zu berechnen, nutzen wir die Formel:

$$\cos(\theta) = \frac{\vec{a} \cdot \vec{b}}{|\vec{a}| \cdot |\vec{b}|}$$

Auflösen nach dem Winkel:

$$\theta = \cos^{-1}\left(\frac{\vec{a} \cdot \vec{b}}{|\vec{a}| \cdot |\vec{b}|}\right)$$

# Schritt-für-Schritt Anleitung:

**Schritt 1 – Skalarprodukt ausrechnen:**
$$\vec{a} \cdot \vec{b} = (a_1 \cdot b_1) + (a_2 \cdot b_2) + (a_3 \cdot b_3)$$

**Schritt 2 – Längen berechnen (siehe [[Vektorlange|Vektorlänge]]):**
$$|\vec{a}| = \sqrt{a_1^2 + a_2^2 + a_3^2}$$
$$|\vec{b}| = \sqrt{b_1^2 + b_2^2 + b_3^2}$$

**Schritt 3 – Winkel isolieren:**
$$\theta = \cos^{-1}\left(\frac{\vec{a} \cdot \vec{b}}{|\vec{a}| \cdot |\vec{b}|}\right)$$

# <mark style="color: red; background: none;">⚠️ Wichtiger Hinweis!</mark>

In der Formel $\cos^{-1}\left(\frac{\vec{a} \cdot \vec{b}}{|\vec{a}| \cdot |\vec{b}|}\right)$ bedeutet der Punkt ($\cdot$) im **Zähler** das **Skalarprodukt**, nicht normale Multiplikation!

Die Punkte im **Nenner** sind auch **Multiplikation** (Längen werden multipliziert).

# Rechenregeln des Skalarprodukts:

- ### Kommutativ:
  - $\vec{a} \cdot \vec{b} = \vec{b} \cdot \vec{a}$

- ### Distributiv:
  - $\vec{a} \cdot (\vec{b} + \vec{c}) = \vec{a} \cdot \vec{b} + \vec{a} \cdot \vec{c}$

- ### Mit Skalaren:
  - $(s \cdot \vec{a}) \cdot \vec{b} = s \cdot (\vec{a} \cdot \vec{b})$

- ### Selbstskalarprodukt:
  - $\vec{a} \cdot \vec{a} = |\vec{a}|^2$ (also die Länge zum Quadrat)