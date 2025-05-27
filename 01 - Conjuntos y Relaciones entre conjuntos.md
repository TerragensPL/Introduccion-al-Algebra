

## Tema 1.1: Conjuntos

**¿Qué debes estudiar?**

### 1. Concepto de conjunto y elemento

- Un *conjunto* es una colección de objetos llamados *elementos*, que comparten alguna característica común. Los conjuntos pueden ser finitos o infinitos.
- Los elementos se escriben entre llaves y separados por comas:
Ejemplo:
    - Días de la semana: {lunes, martes, miércoles, jueves, viernes, sábado, domingo}
    - Números pares: {2,4,6,8,…}
- Notación: Si $a$ es elemento de $A$, se escribe $a \in A$.

**Gráfico:**
Representación de un conjunto finito:

```
A = {1, 2, 3, 4}
```
<br><br>

### 2. Tipos de conjuntos

- **Conjunto finito**: Tiene un número limitado de elementos.


    Un conjunto finito se representa gráficamente listando todos sus elementos entre llaves, ya que su cantidad es limitada y puede ser enumerada de manera completa.

    ### Ejemplo de representación gráfica de un conjunto finito

    - **Por extensión (listado):**
        - Días de la semana:

    $$
    A = \{lunes, martes, miércoles, jueves, viernes, sábado, domingo\}
    $$
             - Lanzamiento de un dado:

    $$
    B = \{1, 2, 3, 4, 5, 6\}
    $$
        - Primeras letras del abecedario:

    $$
    C = \{a, b, c\}
    $$
    - **En diagramas de Venn:**
    El conjunto se representa como un óvalo o círculo, y dentro de él se colocan todos los elementos explícitos del conjunto.
    <br><br>
    ```
    +------------------+
    |   A              |
    |  lunes           |
    |  martes          |
    |  miércoles       |
    |  jueves          |
    |  viernes         |
    |  sábado          |
    |  domingo         |
    +------------------+
    ```


    ### Observaciones importantes

    - En un conjunto finito, cada elemento aparece una sola vez y el orden no importa.
    - El cardinal (número de elementos) es un número natural: por ejemplo, $|A| = 7$ para los días de la semana.
    - Si el conjunto no tiene elementos, se llama conjunto vacío y se representa como $\emptyset$ o $\{\}$.


<br>


- **Conjunto infinito**: Tiene infinitos elementos (por ejemplo, el conjunto de todos los números naturales).

    Un conjunto infinito se representa gráficamente de manera similar a un conjunto finito, pero con una notación que indica que la colección de elementos no termina. Generalmente, esto se hace usando puntos suspensivos (…) o una expresión matemática que describe la regla de formación del conjunto.

    ### Ejemplo gráfico y notación

    - **Por extensión (listado):**
        - Números naturales pares:

    $$
    \{2, 4, 6, 8, 10, 12, \ldots\}
    $$

    Aquí, los puntos suspensivos indican que la secuencia continúa indefinidamente[^1].
    - **Por comprensión (regla):**
        - Números naturales pares:

    $$
    \{2n : n \in \mathbb{N}\}
    $$

    Esto se lee como “el conjunto de todos los números de la forma 2n, donde n es un número natural”.
    - **Visualización en diagramas de Venn:**
    En diagramas de Venn, los conjuntos infinitos se representan como cualquier otro conjunto (un óvalo o círculo), pero se entiende que su interior contiene infinitos elementos, normalmente indicados con puntos suspensivos o una notación simbólica.


    #### Ejemplo visual sencillo:

    ```
    A = {2, 4, 6, 8, ...}
    +-----------------+
    |    A            |
    |  2, 4, 6, ...   |
    +-----------------+
    ```
<br><br>




- **Conjunto vacío**: No tiene elementos. Se denota $\emptyset$ o $\{\}$.

**Ejemplo:**

- Conjunto de las vocales: $\{a, e, i, o, u\}$ (finito)
- Conjunto de números naturales: $\mathbb{N} = \{1, 2, 3, \ldots\}$ (infinito)
- Conjunto vacío: $\emptyset$<br><br>


### 3. Representación de conjuntos

- Por extensión: Listando todos los elementos.
- Por comprensión: Indicando una propiedad que cumplen los elementos.
Ejemplo:
    - $\{x \in \mathbb{N} : x$ es par$\} = \{2, 4, 6, \ldots\}$
<br><br>

### 4. Cardinal de un conjunto

- El *cardinal* es el número de elementos de un conjunto.
Notación: $|A|$ o $\#A$
- Si es finito: $|A| = n$
- Si es infinito: $|A| = \infty$

**Ejemplo:**

- Si $A = \{1, 2, 3\}$, entonces $|A| = 3$.
<br><br><br>
---

## Tema 1.1.1: Relaciones entre conjuntos

**¿Qué debes estudiar?**

### 1. Igualdad de conjuntos

- Dos conjuntos $A$ y $B$ son *iguales* ($A = B$) si tienen exactamente los mismos elementos, sin importar el orden ni la repetición.
- Formalmente:
$A = B \iff (x \in A \implies x \in B)$ y $(x \in B \implies x \in A)$

**Ejemplo:**

- $A = \{a, b, c\}$, $B = \{b, c, a\}$ ⇒ $A = B$
<br><br>
### 2. Inclusión de conjuntos (Subconjuntos)

- $A$ está *incluido* en $B$ ($A \subseteq B$) si todo elemento de $A$ es también elemento de $B$.
- $A$ es *subconjunto* de $B$ si $\forall x (x \in A \implies x \in B)$.
- El conjunto vacío es subconjunto de cualquier conjunto: $\emptyset \subseteq A$.
- Todo conjunto es subconjunto de sí mismo: $A \subseteq A$.

**Ejemplo:**

- $A = \{1, 2\}$, $B = \{1, 2, 3\}$ ⇒ $A \subseteq B$
- $B = \{1, 2, 3\}$, $A = \{1, 2\}$ ⇒ $B \not\subseteq A$

**Gráfico:**
Diagrama de Venn mostrando $A \subseteq B$:

```
+---------------------+
|         B           |
|   +---------+       |
|   |    A    |       |
|   +---------+       |
+---------------------+
```
<br><br>

### 3. Propiedades de la inclusión y la igualdad


### Propiedades de la inclusión


#### **Reflexividad**

**Todo conjunto es subconjunto de sí mismo:**
$A \subseteq A$

Esto significa que, si tienes un conjunto $A$, todos sus elementos están en $A$ (lo cual es obvio). Por ejemplo, si $A = \{1, 2, 3\}$, entonces claramente todos los elementos de $A$ están en $A$, así que $A$ es subconjunto de sí mismo.

<br>

#### **El conjunto vacío**

**El conjunto vacío es subconjunto de cualquier conjunto:**
$\emptyset \subseteq A$

El conjunto vacío ($\emptyset$) no tiene ningún elemento. Por definición, no existe ningún elemento en $\emptyset$ que no esté en $A$, así que se considera subconjunto de cualquier conjunto, sin importar cuál sea $A$.

<br>

#### **Antisimetría**

**$A = B$ si y solo si $A \subseteq B$ y $B \subseteq A$**

Esto significa que dos conjuntos son iguales si cada uno es subconjunto del otro.

- Si todos los elementos de $A$ están en $B$ y todos los de $B$ están en $A$, entonces ambos conjuntos tienen exactamente los mismos elementos, por lo tanto, son iguales.

**Ejemplo:**
$A = \{a, b, c\}$ y $B = \{c, b, a\}$
Todos los elementos de $A$ están en $B$ y viceversa, así que $A = B$.
<br><br>

#### **Transitividad**

**Si $A \subseteq B$ y $B \subseteq C$, entonces $A \subseteq C$**

Esto significa que si todos los elementos de $A$ están en $B$, y todos los de $B$ están en $C$, entonces necesariamente todos los elementos de $A$ también están en $C$.

**Ejemplo:**

- $A = \{1\}$
- $B = \{1, 2\}$
- $C = \{1, 2, 3\}$
Aquí, $A \subseteq B$ y $B \subseteq C$, por lo tanto, $A \subseteq C$.



**Resumen gráfico (Diagrama de Venn para transitividad):**

```
+---------------------+
|         C           |
|   +---------+       |
|   |    B    |       |
|   |  +---+  |       |
|   |  | A |  |       |
|   |  +---+  |       |
|   +---------+       |
+---------------------+
```

Aquí, el círculo de $A$ está dentro de $B$, y $B$ está dentro de $C$, por lo que $A$ está dentro de $C$.

<br>


### 4. Ejemplos prácticos

- $A = \{1, 2, 10\}$, $B = \{1, 2, 3, 6, 10\}$ ⇒ $A \subseteq B$
- $A = \{a, b, c\}$, $B = \{b, c, d\}$ ⇒ No hay relación de inclusión ni igualdad.

<br>

### 5. Cadenas de inclusión

- Ejemplo clásico en números:

$$
\mathbb{N} \subseteq \mathbb{Z} \subseteq \mathbb{Q} \subseteq \mathbb{R} \subseteq \mathbb{C}
$$

(Naturales ⊆ Enteros ⊆ Racionales ⊆ Reales ⊆ Complejos)

**Gráfico:**
Diagrama de Venn para la cadena de inclusión:

```
+---------------------------------------------------+
|                   C (Complejos)                   |
|   +-------------------------------------------+   |
|   |                R (Reales)                 |   |
|   |   +-------------------------------+       |   |
|   |   |      Q (Racionales)           |       |   |
|   |   |   +-------------------+       |       |   |
|   |   |   | Z (Enteros)       |       |       |   |
|   |   |   |   +---------+     |       |       |   |
|   |   |   |   | N       |     |       |       |   |
|   |   |   |   +---------+     |       |       |   |
|   |   |   +-------------------+       |       |   |
|   |   +-------------------------------+       |   |
|   +-------------------------------------------+   |
+---------------------------------------------------+
```


---

## Orden recomendado de estudio

1. **Concepto y notación de conjunto y elemento**
2. **Tipos de conjuntos (finito, infinito, vacío)**
3. **Representación y notación de conjuntos**
4. **Cardinalidad**
5. **Igualdad de conjuntos**
6. **Subconjuntos e inclusión**
7. **Propiedades de la inclusión y la igualdad**
8. **Ejemplos y diagramas de Venn para visualizar relaciones**
9. **Cadenas de inclusión entre conjuntos numéricos**

---

