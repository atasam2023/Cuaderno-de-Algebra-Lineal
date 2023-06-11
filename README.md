# Cuaderno-de-Algebra-Lineal
$$ -Matrices-$$

.

$\underline{\text{"Nula"}}$

.


$\bullet{\text{"Matrices que los elementos que son 0"}}$

.

$\blacktriangle{\text{"EJEMPLO:"}}$

.

$$\begin{bmatrix}
0 & 0\\
0 & 0
\end{bmatrix}$$

.

------------------------------------------------------------------------------

.

$\underline{\text{"Matriz Diagonal"}}$

.

$\checkmark{a_{ij}$ = 0 , $\forall_{i} \neq j$}$

.

$\blacktriangle{\text{"EJEMPLO:"}}$

.

\begin{bmatrix}
1 & 0 & 0\\
0 & 2 & 0\\
0 & 0 & 3
\end{bmatrix}

.

------------------------------------------------------------------------------

.

$\underline{\text{"Matriz Triánuglo Superior"}}$

.

$\checkmark{Si a_{ij} = 0, \forall_{i} > j}$

.

$\blacktriangle{\text{"EJEMPLO:"}}$

.

\begin{bmatrix}
1 & 3 & 2\\
0 & 4 & 8\\
0 & 0 & 7\\
\end{bmatrix}

.

------------------------------------------------------------------------------

.

$\underline{\text{"Matriz Triánuglo Inferior"}}$

.

$\checkmark{Si $a_{ij} = 0, \forall_{i} < j}$

.

$\blacktriangle{\text{"EJEMPLO:"}}$

.

\begin{bmatrix}
2 & 0 & 0\\
0 & 9 & 0\\
9 & 8 & 3
\end{bmatrix}

.

------------------------------------------------------------------------------
.

$\underline{\text{"Identidad"}}$

.

$\checkmark{Si $a_{ij}$ = 0 , $\forall_{ij} \neq j \ \land $ $a_{ij}$ = 1 , $\forall_{ij} = j}$

.

$\bullet{\text{"Entonces A se llama I"}}$

.

$\blacktriangle{\text{"EJEMPLO:"}}$

.

\begin{bmatrix}
1 & 0 & 0\\
0 & 1 & 0\\
0 & 0 & 1
\end{bmatrix}

.

------------------------------------------------------------------------------

$\underline{\text{"Matriz Simétrica"}}$

.

$\bullet{\text{"Si $A = A^T$ entonces $A$ se llama simétrica"}}$

.

$\blacktriangle{\text{"EJEMPLO:"}}$

.

$A=$
$\begin{bmatrix}
1 & 2\\
3 & 5
\end{bmatrix}$

.

$A^T=$
$\begin{bmatrix}
1 & 3\\
2 & 5
\end {bmatrix}$

------------------------------------------------------------------------------

$\underline{\text{"Antisimétrica"}}$

.

$\blacktriangle{\text{"EJEMPLO:"}}$

.

$A=$
$\begin{bmatrix}
1 & 3 & 5\\
-3 & -1 & 6\\
-5 & -6 & 2
\end {bmatrix}$

.

$A^T=$
$\begin{bmatrix}
1 & -3 & -5\\
3 & -1 & 6\\
5 & 6 & 2
\end{bmatrix}$

.

$\bullet{\text{"$A \neq A^T$ entonces es antisimétrica"}}$

.

------------------------------------------------------------------------------

.

###$\underline{\text{"Operaciones elementales de fila"}}$

.

$\bullet{\text{"Se enfoca nuestra atención a una matriz $A_{mxn}$"}}$

.

$\Longrightarrow{\text{"Multiplicación de un escalar por una fila"}}$

.

$\Longrightarrow{\text{"Reemplazar la enésima fila de $A$ por la fila $r+c$ veces la fila $s$"}}$

$\underline{\text{"$s \neq r$"}}$

.

$\Longrightarrow{\text{"Intercambio de filas"}}$

.

------------------------------------------------------------------------------

.

$\bullet{\text{"Matemáticamente"}}$

.

$1) e(A)rj = c.Arj$

$\dashv{\forall_{j} = 1, 2, 3,...,n}$

.

$2) e(A)rj = Arj + cAsj$
$\dashv{\forall_{j} = 1, 2, 3,...,n}$

.

$3) e(A)rj = Asj$

$\dashv{e(A)sj = Arj}$

.

$\blacktriangle{\text{"EJEMPLO:"}}$

$A=$
$\begin{bmatrix}
3 & 4 & 1\\
2 & 4 & -1\\
0 & 2 & -3
\end{bmatrix}$

.


$1) A1j = [3, 4, 1]$

$= 3 [3, 4, 1]$

$= [9, 12, 3]$

.

$e(A3j) = 3A3j$

.

$2) e(A2j) = A2j + (-1)A1j$

$e(A2j) = A2j + (-2)[1, -2, 3]$

$= [2, 4, 1] + [-2, 4, -6]$

$= [0, 8, -5]$

.

$3) e(A)rj = Asj$

$e(A)sj = Arj$

.

$\blacktriangle{\text{"EJEMPLO:"}}$

.

$A=$
$\begin{bmatrix}
1 & -2 & 3\\
2 & 4 & 1\\
0 & 3 & 7
\end{bmatrix}$

.

$1)A1j = [1, -2, 3]$

$e(A1j) = 3[1, -2, 3]$

$e(A1j) = [3, -6, 9]$

.

$\blacktriangle{\text{"Realizar:"}}$

$e(A3j) = 3A3j$

.

$2) e(A2j) = A2j + (-1)A1j$

$e(A2j) = A2j + (-2)[1, -2, 3]$

$= [2, 4, 1] + [-2, 4, -6]$

$= [0, 8, -5]$

------------------------------------------------------------------------------

.

$\blacktriangle{\text{"Realizar:"}}$

.

$e(A3j) = A3j + (-1)A2j$

.

$\bullet{\text{"Definicion"}}$


Si tenemos dos matrices A y B de dimensiones mxn compuestas de números reales, podemos decir que la matriz B es equivalente a la matriz A en términos de filas si B se obtiene a través de una serie de operaciones elementales de filas aplicadas a la matriz A.

.
$\dashv{A \simeq B}$


.

$\underline{\text{"Una matriz $R_{mxn}$ se llama reducida de filas si:"}}$

.

$\Longrightarrow{\text{"El primer elemento $\neq$ 0 de cada fila no nula es 1."}}$

.

$\Longrightarrow{\text{"Cada columna de $R$ que tiene este primer elemento 1 tiene sus otros elementos $\neq$ 0"}}$

.

$A \simeq B_1 \simeq B_2 ... \simeq B = R$

.

$\blacktriangle{\text{"EJEMPLO:"}}$

.

$R=$
$\begin{bmatrix}
0 & 1 & 0 & 5\\
1 & 0 & 0 & -1\\
0 & 0 & 1 & 2
\end{bmatrix}$
$\simeq$
$\begin{bmatrix}
1 & 0 & 0 & -1\\
0 & 1 & 0 & 5\\
0 & 0 & 1 & 2
\end{bmatrix}$

.

$2) e(Arj) = Arj + cAsj , \forall{j} = 1, 2,...n$

.

$\blacktriangle{\text{"Fórmula: Fila Nueva = Fila Antigua "}}$

.

------------------------------------------------------------------------------

.

$\bullet{\text{"Ejercicio: Transformar"}}$

.

$A=$
$\begin{bmatrix}
4 & 2 & 1 & 1\\
-1 & 9 & 4 & 2\\
-2 & 3 & 5 & 6
\end{bmatrix}$
$\simeq$
$\begin{bmatrix}
1 & 0 & 0 & r_{14}\\
0 & 1 & 0 & r_{24}\\
0 & 0 & 1 & r_{34}
\end{bmatrix}$

.

------------------------------------------------------------------------------

.
$\bullet{\text{"Matriz Reducida"}}$

.

Definición: Una matriz $R_{mxn}$ se llama matriz reducida, escalón por filas si y solo si:

.

$\Longrightarrow{\text{"$R$ es reducida."}}$

.
$\Longrightarrow{\text{"Toda la fila de $R$ que tiene todos sus elementos ceros (fila nula) está debajo de todas las filas no nulas"}}$

.

$\Longrightarrow{\text{"Si las filas 1, 2,...,r son las filas no nulas de $R$, y si el primer elemento no cero de la fila $i$ esta en la columna $K_i , i = 1,2,...,r$ entonces $K_1 < K_2 < ... < K_r$."}}$

.

$A → B_1 → B_2 → ... → B → R$

.

$\blacktriangle{\text{"EJEMPLO:"}}$

.

$A=$

$\begin{bmatrix}
2 & 4 & 3 & 4 & 2\\
3 & 5 & 4 & 9 & 3\\
3 & 4 & 5 & 6 & 7\\
8 & 6 & 6 & 9 & 3
\end{bmatrix}$
$\simeq$
$\begin{bmatrix}
1 & 1 & 1 & 1 & 1\\
0 & 1 & 1 & 1 & 1\\
0 & 0 & 0 & 0 & 0\\
0 & 0 & 0 & 0 & 0
\end{bmatrix}$

.

$\dashv{\text{Definición: Sea $A_{mxn}$ sobre $K$, si de $A_{mxn}$ obtenemos la $R$ escalonada}}$

.

------------------------------------------------------------------------------

.

1° Rango de $A=$ filas no nulas de $R$

.

$\underline{\text{"Operaciones con matrices"}}$

### SUMA

$$A_{mxn} + B_{mxn} = C_{mxn}$$

$\blacktriangle{\text{"EJEMPLO:"}}$


$A=$
$\begin{bmatrix}
1 & 2 & 3\\
-1 & -2 & 0
\end{bmatrix}$

.

$B=$
$\begin{bmatrix}
0 & 1 & -3\\
3 & 2 & 1
\end{bmatrix}$

.

$A+B=$
$\begin{bmatrix}
1 & 3 & 0\\
2 & 0 & 1
\end{bmatrix}$

.

------------------------------------------------------------------------------

.

$\underline{\text{"Producto de una matriz por un escalar"}}$

.

$C * A_{mn} = D_{mxn}$

.

$\blacktriangle{\text{"EJEMPLO:"}}$

.


$3$
$\begin{bmatrix}
1 & 2 & 3\\
-1 & -2 & 0
\end{bmatrix}$
$=$
$\begin{bmatrix}
3 & 6 & 9\\
-3 & -6 & 0
\end{bmatrix}$

.

------------------------------------------------------------------------------

.

$\underline{\text{"Producto de Matrices"}}$

.

$$A_{mxd} * B_{dxn} = C_{mxn}$$

$\forall{i} = 1,2,3,...,m$

$\forall{j} = 1,2,3,...,d$

$\forall{K} = 1,2,3,...,n$

.

$AB = [a_{2j}][b_{jK}] = [c_{iK}]$

.

$\blacktriangle{\text{"EJEMPLO:"}}$

.

$A=$
$\begin{bmatrix}
2 & 1 & 5\\
1 & 3 & 2
\end{bmatrix}$

.

$B=$
$\begin{bmatrix}
3 & 4\\
-1 & 2\\
2 & 1
\end{bmatrix}$

.

$A$x$B=$
$\begin{bmatrix}
15 & 15\\
4 & 12
\end{bmatrix}$

.

------------------------------------------------------------------------------

.

$\underline{\text{"Inversion de Matrices"}}$

.

$\dashv{\text{Definición: Sea $A_{n}$ una matriz cuadrada que opera sobre los $R$; si existe una matriz $B_{n}$ cuadrada tal que $AB = BA = I$}}$

.

$\dashv{\text{A la matriz $B$ se dice que es inversa de $A$ y $A$ es una matriz inversible; por lo que:}}$
 
.

$$B=A^{-1}$$

.

$\blacktriangle{\text{"Entonces"}}$

.

$$AA^{-1}=A^{-1}A=I$$

.

$\blacktriangle{\text{"Corolario"}}$

.

$A^{-1}$ es la inversa de $A$ y $A$ es la inversa de $A^{-1}$

.

$\blacktriangle{\text{"Teorema"}}$

.

Si $A$ es inversible entonces $(A^{-1})^{-1}=A$

.

$\blacktriangle{\text{"Teorema"}}$


.

$\dashv{\text{Si $A$ y $B$ son inversibles entonces su producto es inversible y además: $(AB)$ también es inversible y además:$$(AB)^{-1}=B^{-1}A^{-1}$$}}$


.

------------------------------------------------------------------------------

.

$\blacktriangle{\text{"Demostración"}}$

.

$$(AB)(AB)^{-1}=ABB^{-1}A^{-1}$$
$$=AIA^{-1}$$
$$=AA^{-1}$$
$$=I$$

.

$\dashv{\text{Si dos matrices son inversibles, el producto es inversible}}$

.

$\blacktriangle{\text{"EJEMPLO:"}}$

.

$A=$
$\begin{bmatrix}
2 & -1\\
1 & 3
\end{bmatrix}$
$\simeq$
$\begin{bmatrix}
2 & -1 & 1 & 0\\
1 & 3 & 0 & 1
\end{bmatrix}$
$\simeq$
$\begin{bmatrix}
1 & 3 & 0 & 1\\
2 & -1 & 1 & 0
\end{bmatrix}$
$\simeq$
$\begin{bmatrix}
1 & 3 & 0 & 1\\
0 & -7 & 1 & -2
\end{bmatrix}$
$\simeq$
$\begin{bmatrix}
1 & 3 & 0 & 1\\
0 & 1 & -1/7 & 2/7
\end{bmatrix}$
$\simeq$
$\begin{bmatrix}
1 & 0 & 3/7 & 1/7\\
0 & 1 & -1/7 & 2/7
\end{bmatrix}$

.

$\blacktriangle{\text{"entonces $A$ es inversible"}}$

.

$\blacktriangle{\text{"Nota: Si $R \neq I$ no ha inversa"}}$

.

------------------------------------------------------------------------------

.

$\underline{\text{"Matriz Ortogonal"}}$

.

Si $AA^{T} = D$

$A$ es Ortogonal

.

------------------------------------------------------------------------------

.

$\underline{\text{"Matriz Ortonormal"}}$

.

Si $AA^{T} = I$

$A$ es Ortonormal

.

------------------------------------------------------------------------------

.

$\underline{\text{"Determinantes"}}$

.

$\dashv{\text{Definición El determinante de una función es definida en la siguiente forma:}}$

.

$$detA \equiv |A|$$

.

$\dashv{\text{El determinante de una matriz $A$ de orden $n^{-1}$ se obtiene al eliminar la fila $i$ y la columna $j$ de la matriz original. Estos determinantes, de dimensiones más pequeñas que la matriz $A$, se conocen como menores. Los elementos $a_{ij}$ pueden corresponder a elementos de una fila o columna en particular.:}}$


.

$\blacktriangle{\text{"EJEMPLO:"}}$

.

$\blacktriangle{\text{"Matriz de Orden 2 (menor orden de todos)"}}$

.

$|A|=$
$\begin{bmatrix}
a_{11} & a_{12}\\
a_{21} & a_{22}
\end{bmatrix}$
$= a_{11} a_{22} - a_{21}a_{12} $

.

$\blacktriangle{\text{"Matriz de Orden 3"}}$


.

$|A_3|=$
$\begin{bmatrix}
a_{11} & a_{12} & a_{13}\\
a_{21} & a_{22} & a_{23}\\
a_{31} & a_{32} & a_{33}
\end{bmatrix}$
$=(-1)^{1+1} a_{11}$
$\begin{bmatrix}
a_{22} & a_{23}\\
a_{32} & a_{33}
\end{bmatrix}$
$+ (-1)^{2+1} a_{21}$
$\begin{bmatrix}
a_{12} & a_{13}\\
a_{32} & a_{33}
\end{bmatrix}$
$+ (-1)^{3+1} a_{31}$
$\begin{bmatrix}
a_{12} & a_{13}\\
a_{22} & a_{23}
\end{bmatrix}$

.

$\blacktriangle{\text{"EJEMPLO:"}}$

.

$A=$
$\begin{bmatrix}
1 & -1 & 1\\
1 & 2 & 1\\
1 & 3 & 2
\end{bmatrix}$
$=1$
$\begin{bmatrix}
2 & 1\\
3 & 2
\end{bmatrix}$
$-1$
$\begin{bmatrix}
-1 & 1\\
3 & 2
\end{bmatrix}$
$+1$
$\begin{bmatrix}
-1 & 1\\
2 & 1
\end{bmatrix}$
$=1-(-5)+(-3)=1+5-3=3$

.

------------------------------------------------------------------------------

.

$\underline{\text{"Sistemas de ecuaciones"}}$

.

$\dashv{\text{Los sistemas de ecuaciones lineales en forma de matrices son una herramienta eficaz para resolver conjuntos de ecuaciones lineales. En este enfoque, las incógnitas y los coeficientes se representan mediante matrices. Por ejemplo, consideremos el siguiente sistema de ecuaciones lineales:}}$

.

\begin{cases}
2x+3y=8\\
4x-2y=2
\end{cases}

.

$\blacktriangle{\text{"Se puede representar matricialmente como:"}}$

.

\begin{bmatrix}
2 & 3 & x & 8\\
4 & -2 & y & 2
\end{bmatrix}

.

------------------------------------------------------------------------------

.

$\underline{\text{"Factorización LU"}}$

.

$\dashv{\text{La factorización LU es un método para descomponer una matriz en el producto de dos matrices: una matriz triangular inferior ($L$) y una matriz triangular superior ($U$).}}$

.

$\blacktriangle{\text{"EJEMPLO:"}}$

.

$A=$
$\begin{bmatrix}
2 & 1 & 3\\
4 & 0 & 2\\
1 & 3 & 1
\end{bmatrix}$

.

$\dashv{\text{La factorización LU de una matriz implica encontrar dos matrices, L y U, de tal manera que la matriz original A se pueda expresar como el producto de L y U, es decir, A = LU. La matriz L es una matriz triangular inferior con unos en la diagonal principal, mientras que la matriz U es una matriz triangular superior.}}$

.

$\blacktriangle{\text{"Después de aplicar el método de factorización LU a la matriz $A$, obtenemos:"}}$

.

$L=$
$\begin{bmatrix}
1 & 0 & 0\\
2 & 1 & 0\\
1/2 & 1 & 1
\end{bmatrix}$

.

$U=$
$\begin{bmatrix}
2 & 1 & 3\\
0 & -2 & -4\\
0 & 0 & -1
\end{bmatrix}$

.

------------------------------------------------------------------------------

.

-$$Espacios Vectoriales$$-

.
$\dashv{\text{Un espacio vectorial es un conjunto de objetos llamados vectores, que no está vacío y en el que se han definido dos operaciones: la suma y la multiplicación por un escalar (un número real). Estas operaciones deben cumplir diez axiomas que se aplican a todos los vectores u, v, y w en el espacio vectorial V, así como a todos los escalares α y β reales.}}$

.
$\blacktriangle{\text{"Llamamos $u + v$ a la suma de vectores en $V$, y $αv$ al producto de un número real α por un vector $v ∈ V$."}}$

.

------------------------------------------------------------------------------

.

$\blacktriangle{\text{"Axiomas"}}$

.

$\Longrightarrow{\text{$u+v ∈ V$}}$

.

$\Longrightarrow{\text{$u+v=v+u$}}$

.

$\Longrightarrow{\text{$(u+v)+w=u+(v+w)$}}$

.

$\Longrightarrow{\text{Existe un vector nulo $0_{V} ∈ V$ tal que $v+0_{V}=v$}}$

.

$\Longrightarrow{\text{Para cada $v$ en $V$, existe un opuesto $(-v) ∈ V$ tal que $v+(-v)=0_{V}$}}$

.

$\Longrightarrow{\text{$αv ∈ V$}}$

.

$\Longrightarrow{\text{$α(u+v)=αu+αv$}}$

.

$\Longrightarrow{\text{$(α+β)v=αv+βv$}}$

.

$\Longrightarrow{\text{$α(βv)=(αβ)v$}}$

.

$\Longrightarrow{\text{$1v=v$}}$

.

------------------------------------------------------------------------------

.

$\blacktriangle{\text{"Propiedades"}}$

.

$\Longrightarrow{\text{$0_{u}=0_{V}$}}$

.

$\Longrightarrow{\text{$α0_{V}=0_{V}$}}$

.

$\Longrightarrow{\text{$(-α)u=-(αu)$ En particular, para $α=1:(-1)u=-u$}}$

.

$\Longrightarrow{\text{$αu=0_{V} ⟹ α=0$  ó  $u=0_{V}$}}$

.

------------------------------------------------------------------------------

.

$\underline{\text{"Subespacios vectoriales"}}$

.

$\dashv{\text{Si tenemos un espacio vectorial V y un subconjunto no vacío W de V, entonces W se considera un subespacio de V si W, por sí mismo, es también un espacio vectorial que tiene las mismas operaciones de suma de vectores y multiplicación por un escalar definidas en V.}}$

.

$\blacktriangle{\text{"EJEMPLO:"}}$

.

$W=\{(x_{1},x_{2} ∈ R^{2}: x_{2}=3x_{1}\}$ ¿Es un subespacio vectorial de $R^{2}$?

.

$\dashv{\text{Primero analicemos el conjunto $W$. Son todos vectores de $R^{2}$ tales que la segunda componente es el triple de la primera:}}$

.

$$(x_{1},3x_{1})=x_{1}(1,3)$$

.

$\dashv{\text{$W$ es la recta que pasa por el origen y tiene vector director $(1,3)$, o sea la recta de ecuación $y=3x$}}$

.

$\dashv{\text{Para decidir si $W$ es un subespacio de $R^{2}$ habría que verificar que se cumplen los axiomas del 1 al 10. En este caso se *cumplen*.}}$

.

------------------------------------------------------------------------------

.

$\underline{\text{"Bases y Dimensiones"}}$

.

$\dashv{\text{En el contexto de un espacio vectorial o subespacio vectorial, se denomina base a un conjunto de vectores que es linealmente independiente y, al mismo tiempo, genera todo el espacio o subespacio en cuestión.}}$

.

------------------------------------------------------------------------------

.

$\blacktriangle{\text{Propiedades de las bases}}$

.

$\Longrightarrow{\text{Una base de $S$ es un sistema generador minimal de $S$ (lo más pequeño posible).}}$

.

$\Longrightarrow{\text{Además es un conjunto independiente maximal dentro de $S$ (lo más grande posible).}}$

.

$\Longrightarrow{\text{Una base de $S$ permite expresar todos los vectores de $S$ como combinación lineal de ella, de manera única para cada vector.}}$

.

$\blacktriangle{\text{"EJEMPLO:"}}$

.

-1. La base canónica de $R^{n}$-
$$e_{1}=(1,0,...,0)$$
$$e_{2}=(0,1,...,0)$$
$$...$$
$$e_{n}=(0,0,...,1)$$

.

$\Longrightarrow{\text{Son linealmente independientes porque forman un determinante no nulo.}}$

.

$\Longrightarrow{\text{Son sistema generador de $R^{n}$ porque todo vector $(a_{1},a_{2},...,a_{n})∈R^{n}$}}$

.

-2. Otra base de $R^{3}$ distinta de la canónica:- $(1,0,0),(1,1,0),(0,2,-3)$.

.

$\Longrightarrow{\text{Son linealmente independientes porque forman un determinante no nulo.}}$

.

$\Longrightarrow{\text{Son sistema generador de $R^{3}$ porque cualquier vector $(a,b,c)$ se puede poner como combinacion lineal de ellos. En efecto, dado $(a,b,c)$, buscamos $α,β$ y que satisfagan:}}$

.

$$(a,b,c)=α(1,0,0)+γ(0,2,-3)$$

.

$\blacktriangle{\text{Se obtiene un sistema:}}$

.

\begin{cases}
α+β=a\\
β+2γ=b\\
-3γ=c
\end{cases}

.

-3.* $(1,2,3), (4,5,6), (7,8,9)$ en $R^{3}$ *no forman base porque no son linealmente independientes (su determinante es nulo).-

.

-4. Base de un subespacio. En $R^{3}$, consideremos el subespacio* $S=$plano$XY$. *Veamos que los vectores* $(3,2,0), (1,-1,0)$ *forman una base de* $S$*.-

.

------------------------------------------------------------------------------

.

$\underline{\text{"Dimensión"}}$

.

$\dashv{\text{En un espacio vectorial o subespacio vectorial, todas las bases comparten la misma cantidad de vectores. A esta cantidad se le denomina dimensión del espacio o subespacio.}}$

.

$\blacktriangle{\text{"EJEMPLO:"}}$

.

$\Longrightarrow{\text{$R^{n}$ tiene dimension $n$, pues tiene una base de $n$ elementos.}}$

.

$\Longrightarrow{\text{$M_{2x2}$ ={matrices 2x2 con terminos reales} tiene dimensión 4. Una base de $M_{2x2}$ es:}}$

.

$\begin{bmatrix}
1 & 0\\
0 & 0
\end{bmatrix}$
$.$
$\begin{bmatrix}
0 & 1\\
0 & 0
\end{bmatrix}$
$.$
$\begin{bmatrix}
0 & 0\\
1 & 0
\end{bmatrix}$
$.$
$\begin{bmatrix}
0 & 0\\
1 & 0
\end{bmatrix}$
$.$
$\begin{bmatrix}
0 & 0\\
0 & 1
\end{bmatrix}$

.

$\Longrightarrow{\text{$P_{2}=${polinomios de grado <= 2 con coeficientes reales} tiene dimension 3. Una base de $P_{2}$ es, por ejemplo, la formada por los tres polinomios siguientes:}}$

.

$1+0x+0x^{2} , 0+x+0x^{2} , 0+0x+x^{2}$ (es decir, los polinomios $1, x, x^{2}$).

.

Otra base: $1+2x+3x^{2} , 4+x^2 , 3-x-5x^2$

.
------------------------------------------------------------------------------

.

$\blacktriangle{\text{Propiedades de la dimensión}}$

.
$\Longrightarrow{\text{Significado físico de la dimensión: los planos tienen dimensión 2, las rectas dimensión 1, el punto dimensión 0. El subespacio $\{0\}$ es el único que tiene dimensión 0.}}$

.

$\Longrightarrow{\text{La dimensión de un subespacio en $R^{n}$, coincide con el número de parámetros libres en su forma paramétrica.}}$

.

$\Longrightarrow{\text{Si $S$ y $T$ son subespacios y $S$ está contenido en $T$, entonces $dim S <= dim T$. Además, si se da la igualdad, $dim S = dim T$, ambos espacios han de coincidir.}}$

.

$\Longrightarrow{\text{El rango de una familia de vectores, es igual a la dimensión del subespacio que generan.
Es decir: si $v1,v2,. . . v_{n}$ generan un cierto subespacio $S$, y si el rango de dicho conjunto es $r$, entonces $dim S = r$. (Si un cierto conjunto de vectores tienen rango 2, entonces generan un plano; etc.)}}$

.

$\blacktriangle{\text{"EJEMPLO:"}}$

.

$\Longrightarrow{\text{En el espacio tridimensional ℝ³, consideremos el subespacio S generado por los vectores (1, 0, 2), (0, -1, -2), (3, 3, 3) y (2, 2, 0). Al observar que el rango de este conjunto, tanto si lo organizamos por filas como por columnas, es 3, podemos aplicar la propiedad 4 para concluir que la dimensión de S es 3. Sin embargo, dado que nos encontramos en ℝ³, según la propiedad... (la oración se corta en la pregunta original).}}$

.

------------------------------------------------------------------------------

.

$$-Conicas-$$

.
$\Longrightarrow{\text{Definición: El lugar geométrico de los puntos cuya relación de distancias a un punto y una recta fijos es constante recibe el nombre de sección cónica o simplemente cónica.}}$

.

\begin{cases}
Punto Fijo → Foco\\
Recta Fija → Directriz\\
Relación Constante → Excentricidad (e)
\end{cases}

.

$\blacktriangle{\text{*Excentricidad*}}$

.

$$e=\frac{c}{a}=\frac{\sqrt{a^2+b^2}}{a};e>1$$

.

------------------------------------------------------------------------------

.

$\underline{\text{"Categorías"}}$

.

$\checkmark{Si $e<1$, la cónica se llama *Elipse*}$

.

$\checkmark{Si $e=1$, la cónica se llama *Parábola*}$

.

$\checkmark{Si $e>1$, la cónica se llama *Hipérbola*}$

.

------------------------------------------------------------------------------

.

$\underline{\text{"Parábola"}}$

.

$\blacktriangle{\text{Ecuación de la parábola}}$

.

$\Longrightarrow{\text{*Foco a la derecha de directriz:*}}$

.

$$(y-k)^{2}=4a(x-h)$$

.

$\Longrightarrow{\text{*Directriz encima de foco*}}$

.

$$(x-h)^{2}=-4a(y-k)$$

.

$\Longrightarrow{\text{*Foco a la izquierda de directriz*}}$

.

$$(y-k)^{2}=-4a(x-h)$$

.

$\Longrightarrow{\text{*Foco encima de directriz*}}$

.

$$(x-h)^{2}=4a(y-k)$$

.

------------------------------------------------------------------------------

.

$\underline{\text{"Elipse"}}$

.

$\blacktriangle{\text{Ecuación de la elipse}}$

.

$$\frac{x^2}{a^2} + \frac{y^2}{b^2} = 1$$

.

$\Longrightarrow{\text{Si los focos fueran coordenadas (0,c) y (0,-c), el Eje Mayor estaría sobre el eje $y$ entonces la ec. sería:}}$

.

$$\frac{x^2}{b^2}+\frac{y^2}{a^2}=1$$

.

$\Longrightarrow{\text{*Ecs. de las directrices $D'D'$ y $DD$ respectivamente*}}$

.

$$x+\frac{a}{e}=0$$y$$x-\frac{a}{e}=0$$

.

$\Longrightarrow{\text{Se denomina *latus rectum* de la elipse a la cuerda perpendicular al eje mayor por uno de los focos, su longitud es $\frac{2b^{2}}{a}$}}$

.

$\Longrightarrow{\text{Si el centro de la elipse fuese el punto $(h,k)$ y el eje mayor tiene la dirección del eje $x$, la ecuación de la elipse seria igual a:}}$

.

$$\frac{(x-h)^2}{a^2}+\frac{(y-k)^2}{b^2}=1$$
→Eje mayor perpendicular al eje $x$
$$\frac{(x-h)^2}{b^2}+\frac{(y-k)^2}{a^2}=1$$
→Eje mayor perpendicular al eje $y$

.

$\Longrightarrow{\text{*Ecuacion general de la elipse*}}$

.

$$Ax^2+By^2+Dx+Ey+F=0$$

.

------------------------------------------------------------------------------

.

$\underline{\text{"Hipérbola"}}$

.

$\blacktriangle{\text{Ecuación de la hipérbola}}$

.

$$\frac{x^2}{a^2}-\frac{y^2}{b^2}=1$$

$$c^2-a^2=b^2$$

.
$\blacktriangle{\text{Focos tienen coordenadas}}$

$F(c,0)$ y $F'(-c,0)$

*Distancia entre $F$ y $F'$ es igual a $2a$*

.
$\blacktriangle{\text{Ecuaciones directrices DD'}}$

$$x=±\frac{a}{e}$$

.

$\blacktriangle{\text{Focos están sobre eje $x$}}$

$$y=±\frac{a}{e}$$

.

$\blacktriangle{\text{Focos están sobre eje $y$}}$

*Ecs. asíntotas*

$$y=±\frac{b}{a}x$$

.

$\blacktriangle{\text{Cuando el eje real es $x$}}$

$$y=±\frac{a}{b}x$$

.

$\blacktriangle{\text{Cuando el eje real es $y$}}$

.

$\blacktriangle{\text{Si el centro de la hipérbola es el pto coordenadas (h,k):}}$

$$\frac{(x-h)^2}{a^2}-\frac{(y-k)^2}{b^2}=1$$

.

$\blacktriangle{\text{Eje real paralelo al eje $x$}}$

$$\frac{(y-k)^2}{a^2}-\frac{(y-k)^2}{b^2}=1$$

.

$\blacktriangle{\text{Eje real paralelo al eje $y$}}$

.

------------------------------------------------------------------------------

.

$\blacktriangle{\text{Forma General de la Ec. de la Hipérbola}}$

.

$$Ax^2-By^2+Dx+Ey+F=0→$$ siendo $A$ y $B$ del mismo signo.

.

$$-Transformaciones Lineales y Vectores Propios-$$

.

$\underline{\text{"Transformaciones Lineales"}}$

.

$\Longrightarrow{\text{Una transformación lineal es una función que opera entre dos espacios vectoriales, denotados como V y W. Esta función asigna vectores de V a vectores de W. Sin embargo, no todas las funciones que transforman vectores de V a vectores de W son consideradas transformaciones lineales. Para que una función sea una transformación lineal, debe cumplir ciertas condiciones específicas.}}$

.

$F: V→W$ es una transformación lineal ssi:

.

$\checkmark{$F(u+v)=F(u)+F(v)$ , $ ∀ $ $u,v ∈ V$}$

.

$\checkmark{$F(k,v)=k,F(v)$ , $∀v∈V$ , $∀k∈R$}$

.


------------------------------------------------------------------------------

.

$\blacktriangle{\text{Propiedades de una Transformacion Lineal}}$

.

-Propiedad 1-

.

$\Longrightarrow{\text{La imagen del vector nulo del dominio $0_{v}$ es el vector nulo del codominio $0_{w}$:
$$T(0_V)=0_w$$}}$

.

-Propiedad 2-

.

$\Longrightarrow{\text{La imagen del vector $-v$ es igual al opuesto de la imagen de $v$:
$$T(-v)=-T(v)$$}}$

.

-Propiedad 3-

.

$\Longrightarrow{\text{Consideremos $r$ vectores del espacio vectorial $V$:
$$v_1,v_2,...,v_r ∈ V$$}}$

.

$\blacktriangle{\text{Tomemos una combinación lineal en el dominio:}}$

.

$$α_1v_1+α_2v_2+α_3v_3+...+α_rv_r$$

.

$\blacktriangle{\text{Donde $α_i ∈ R$}}$

.

$\Longrightarrow{\text{Si aplicamos la transformación lineal $F$ de $V$ a $W$, teniendo en cuenta las propiedades enunciadas en la definición, resulta:}}$

.

$$F(α_1v_1+α_2v_2+α_3v_3+...+α_rv_r)=α_1F(v_1)+α$$

.

$\Longrightarrow{\text{Es decir que una transformación lineal <\<transporta\>> combinaciones lineales de $V$ a $W$, conservando los escalares de la combinación lineal.}}$

.

$\blacktriangle{\text{"EJEMPLO:"}}$

.

Sea $$T(1,0)=(2,1,-1)$$
$$T(0,1)=(1,-1,0)$$

encuentre $T$
$$R^2→R^3$$
$$(x,y)→T(x,y)=?$$

.

$$B\{v_1, v_2\} → $$
$B=$
$\begin{cases}
\begin{bmatrix}
1\\
0
\end{bmatrix}
,
\begin{bmatrix}
0\\
1
\end{bmatrix}
\end{cases}$

.

$v_1=α_1v_2+α_2v_2$

$v=α$
$\begin{bmatrix}
1\\
0
\end{bmatrix}$
$+α_2$
$\begin{bmatrix}
0\\
1
\end{bmatrix}$

$$x=α_1$$
$$y=α_2$$

$T(\vec{v})=T$
$\left(
    \begin{bmatrix}
    x\\
    y
    \end{bmatrix}
\right)$
$=$
$α_1T$
$\left(
  \begin{bmatrix}
  1\\
  0
  \end{bmatrix}
\right)$
$+α_2T$
$\left(
  \begin{bmatrix}
  0\\
  1
  \end{bmatrix}
\right)$

$T$
$\left(
  \begin{bmatrix}
  x\\
  y
  \end{bmatrix}
\right)$
$=$
$α_1$
$\begin{bmatrix}
2\\
1\\
-1
\end{bmatrix}$
$+α_2$
$\begin{bmatrix}
1\\
-1\\
0
\end{bmatrix}$

$T$
$\left(
  \begin{bmatrix}
  x\\
  y
  \end{bmatrix}
\right)$
$=x$
$\begin{bmatrix}
2\\
1\\
1
\end{bmatrix}$
$+y$
$\begin{bmatrix}
1\\
-1\\
0
\end{bmatrix}$
$=$
$\begin{bmatrix}
2x+4\\
x-y\\
-x
\end{bmatrix}$
