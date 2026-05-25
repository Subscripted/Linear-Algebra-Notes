### Definition:
- Das Tensorprodukt (Symbol: $\otimes$) ist eine grundlegende mathematische Operation, mit der man neue mathematische Räume (wie [[Vektorraum|Vektorräume]] oder Moduln) sowie neue Objekte (Tesnoren) aus bestehenden konstruiert. Sein primärer Zweck in der linearen Algebra ist es, bilineare oder multilineare Abbildungen in gewöhnliche lineare Abbildungen umzuwandeln (auch bekannt als Linearisierung).

# Das Tensorprodukt von Vektoren
Wenn man das Tensorprodukt zweier endlicher Standard-Vektoren entspricht dies im Wesentlichen dem dydischen Produkt. Das Ergebnis ist eine Matrix.

Seien $v \in \mathbb{R}^3$ und $w \in \mathbb{R}^2$ zweier Vektoren:
- $$v = \begin{pmatrix} 1 \\ 2 \\ 3 \end{pmatrix}, w = \begin{pmatrix} 4 \\ 5 \end{pmatrix}$$
  Das Tensorprodukt $v \otimes w$ berechnet sich, indem man jede Komponente des ersten Vektors mit jeder Komponente des zweiten Vektors multipliziert.
- $$v \otimes$ w = v * w^T = \begin{pmatrix} 1 \\ 2 \\ 3 \end{pmatrix} \begin{pmatrix}4&5\end{pmatrix} = \begin{pmatrix} 1*4&1*5 \\ 2*4&2*5 \\ 3*4&3*5 \end{pmatrix} = \begin{pmatrix}4&5 \\ 8&10 \\ 12&15 \end{pmatrix}$$

# Weitere Formeln:
//////// Kronecker Produkt ////////