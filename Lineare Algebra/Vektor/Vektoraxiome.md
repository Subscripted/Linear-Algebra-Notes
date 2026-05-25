#Beenden
### Definition:
- Die Vektoraxiome definieren die Eigenschaften, die eine Menge $V$ (die [[Vektore|Vektoren]]) zusammen mit einem Körper $K$ (die [[Skalare|Skalare]], meist $R$) erfüllen muss, um als [[Vektorraum|Vektorraum]] zu gelten.
- Dabei müssen zwei Verknüpfungen definiert sein: die [[Vektoraddition|Vektoraddition]] ($+:VxV->V$) und die [[Skalarmultiplikation|Skalarmultiplikation]] ($*: KxV->V$).


# Axiome der Vektoraddition
- Die Menge $V$ bildet bezüglich der Addition eine **abelsche Gruppe**. Das bedeutet für alle $u$, $v$, $w \in V$:
	- ### Assoziativgesetz: 
		- $u + (v + w) = (u + v) + w$
	- ### Kommutativgesetz:
		- $u + v = v + u$
	- ### Existenz des neutralen Elements:
		- Es gibt einen Nullvektor $0 \in V$, sodass $v + 0 = v$.
	- ### Existenz des inversen Elements:
		- Zu jedem $v \in V$ existiert ein $-v \in V$, sodass $v + (-v) = 0$.

# Axiome der Skalarmultiplikation
- Diese Regeln verknüpfen [[Skalare]], $a,ß \in K$ mit [[Vektore|Vektoren]] $u, v \in V$: 
	- ### Distributivgesetz I:
		- $a * (u + v) = a * u + a * v$
	- ### Distributivgesetz II:
		- $(a + ß) * v = a * v + ß * v$
	- ### Assoziativgesetz der Skalare:
		- $a * (ß * v) = (a * ß) * v$
	- ### Neutralität des Elements:
		- $1* v = v$ (wobei 1 das Einselement des Körpers $K$ ist).
