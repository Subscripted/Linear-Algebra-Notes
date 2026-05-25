### Definition:
- Die Transponierung (oder Transposition) ist eine grundlegende Operation in der linearen Algebra, bei der die Zeilen und Spalten einer Matrix vertauscht werden. Aus einer $mXn$- Matrix wird eine $nXm$-Matrix, wobei die erste Zeile zur ersten Spalte wird. Das Symbol für die transponierte Matrix A ist $A^T$.

# Wichtige Aspekte der Transponierung:
- ### Vorgehensweise:
	- Zeilen werden zu Spalten, Spalten zu Zeilen. Anschaulich entspricht dies einer Spiegelung an der Hauptdiagonalen.
		- #### Beispiel:
			- $$\begin{pmatrix} 1 & 2  \\ 3 & 4 \\ 5 & 6 \end{pmatrix} = \begin{pmatrix} 1 & 3 & 5 \\ 2 & 4 & 6 \end{pmatrix}$$
- ### Rechenregel:
	- $(A^T)^T$ = $A$ (Selbstinvers).
	- $(A + B)^2 = A^T + B^T$
	- $(AB)^T = B^T A^T$ 
- ### Eigenschaften:
	- Determinante, Rang und Spur einer Matrix bleiben bei der Transponierung unverändert.
- ### Symetrische Matrix:
	- Eine quadratische Matrix ist symmetrisch, wenn $A^T = A$ gilt.
- ### Vektoren:
	- Ein Spaltenvektor wird durch Transponierung zu einem Zeilenvektor und umgekehrt.