# PAS_Procesos_estoc-sticos
En este documento realizaré varias gráficas con simulaciones de un ejemplo específico de proceso estocástico, llamado paseo aleatorio simple (PAS).
En primer lugar, un proceso estocástico se define como una familia de variables aleatorias $\{X_t\}_{t \in T}$ , donde el conjunto T es arbitrario.

 En particular, el PAS se define de la siguiente manera: consideramos en primer lugar el proceso estocástico $\{Z_n\}_{n \in \mathbb{N}}$, donde las variables $Z_n$ son independientes e idénticamente distribuidas; y $P(Z_n = 1) = p$, $P(Z_n = -1) =1-p$

De esa manera, el PAS de parámetro p se define como $X_n = \sum_{t=1}^{n} Z_t$

Intuitivamente, cada observación de un PAS de parámetro p representa una posible  trayectoria de una partícula que se despalaza hacia arriba con probabilidad $p$ y hacia abajo con probabilidad $1-p$
