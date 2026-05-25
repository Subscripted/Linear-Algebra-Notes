### Definition:
- Die Matrizenmultiplikation verknüpft zwei Matrizen, wobei die Spaltenanzahl der ersten Matrix der Zeilenanzahl der zweiten entsprechen muss (Regel: **Zeile mal Spalte**). Das Ergebnis ist eine neue Matrix, deren Einträge durch Summen von Produkten der Zeilen und Spaltenelemente berechnet werden.
- Die Operation ist nicht kommutativ ($A * B  != B * A$), aber assoziativ.


# Kernpunkte der Matrixmultiplikation:
- ### Voraussetzung:
	- Anzahl Spalten Matrix A = Anzahl Zeilen Matrix B
- ### Dimension: 
	- Eine ($n X m$)-Matrix multiplizieret mit einer ($m X k$)-Matrix ergibt eine ($n X k$)-Matrix.
- ### Berechnung:
	- Das Element $c_{ji}$ der Ergebnismatrix entsteht durch das [[Skalare|Skalarprodukt]] der $i$-ten Zeile von A und der $j$-ten Spalte von B.
- ### Falk-Schema: 
	- Eine hilfreiche Tabelle zur strukturierten Berechnung bei der die erste Matrix links und die zweite oben platziert wird.


# Rechenregeln:
- ### Nicht kommutativ:
	- $A * B$ ist im Allgemeinen nicht gleich $B * A$.
- ### Assoziativ:
	- $(A * B) * C = A * (B * C)$.
- ### Distributiv:
	- $A * (B + C) = A * B + A * C$.
- ### Einheitsmatrix:
	- $A * E = A$ (Multiplikation mit der Einheitsmatrix ändert die Matrix nicht).
- 