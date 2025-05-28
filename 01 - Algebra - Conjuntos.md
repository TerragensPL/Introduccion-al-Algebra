# Algebra

## **Conjuntos**

## **1. Concepto de conjunto y elemento**

- Un *conjunto* es una colección de objetos llamados *elementos*, que comparten alguna característica común. Los conjuntos pueden ser finitos o infinitos.
- Los elementos se escriben entre llaves y separados por comas:
    
    Ejemplo:
    
    - Días de la semana: **{lunes, martes, miércoles, jueves, viernes, sábado, domingo}**
    - Números pares: **{2,4,6,8,…}**
- Notación: Si a es elemento de **A**, se escribe **a ∈ A**

**Gráfico:**

Representación de un conjunto finito:

```
A = {1, 2, 3, 4}
```

---

## 2. Tipos de conjuntos

- ***Conjunto finito*:** Tiene un número limitado de elementos.
    
    Un conjunto finito se representa gráficamente listando todos sus elementos entre llaves, ya que su cantidad es limitada y puede ser enumerada de manera completa.
    
    ## **Ejemplo de representación gráfica de un conjunto finito**
    
    - **Por extensión (listado):**
        - Días de la semana:
            
            **A = {lunes, martes, miércoles, jueves, viernes, sábado, domingo}**
            
        - Lanzamiento de un dado:
            
            **B = {1,2,3,4,5,6}**
            
        - Primeras letras del abecedario
            
            **C = {a,b,c}**
            
    - **En diagramas de Venn:**
        
        El conjunto se representa como un óvalo o círculo, y dentro de él se colocan todos los elementos explícitos del conjunto.
        
 <table>
  <td>A</td>
  <tr><td>

  lunes

  martes

  miércoles

  jueves

  viernes

  sábado

  domingo</td></tr>
</table>
    
  ### **Observaciones importantes**
  
  - En un conjunto finito, cada elemento aparece una sola vez y el orden no importa.
  - El cardinal (número de elementos) es un número natural: por ejemplo, |A| = 7 para los días de la semana1.
  - Si el conjunto no tiene elementos, se llama conjunto vacío y se representa como **∅** ó **{}**
  
  ---
  <br>

- ***Conjunto infinito***: Tiene infinitos elementos (por ejemplo, el conjunto de todos los números naturales).
    
    Un conjunto infinito se representa gráficamente de manera similar a un conjunto finito, pero con una notación que indica que la colección de elementos no termina. Generalmente, esto se hace usando puntos suspensivos (…) o una expresión matemática que describe la regla de formación del conjunto.
    
    ## **Ejemplo gráfico y notación**
    
    - **Por extensión (listado):**
        - Números naturales pares:
            
            **{2,4,6,8,10,12,…}**
            
        
        Aquí, los puntos suspensivos indican que la secuencia continúa indefinidamente1.
        
    - **Por comprensión (regla):**
        - Números naturales pares:
            
            **{2n : n ∈ N}**
            
        
        Esto **se lee** como “**el conjunto de todos los números de la forma 2n, donde n es un número natural**”.
        
    - **Visualización en diagramas de Venn:**
        
        En diagramas de Venn, los conjuntos infinitos se representan como cualquier otro conjunto (un óvalo o círculo), pero se entiende que su interior contiene infinitos elementos, normalmente indicados con puntos suspensivos o una notación simbólica.
        
    
    ## **Ejemplo visual sencillo:**
    
    A = {2, 4, 6, 8, ...}


    <table>
  <td>A</td>
  <tr><td>
    2,
    4,
    6,
    ...
  </td></tr>
  </table>
 
    
    En resumen, la clave para representar un conjunto infinito es usar puntos suspensivos o una expresión matemática general, ya que no es posible listar todos sus elementos.
    
    ---
    
- ***Conjunto vacío***: No tiene elementos. Se denota **∅** o **{}**.

**Ejemplo:**

- Conjunto de las vocales: **{a,e,i,o,u}** (finito)
- Conjunto de números naturales: **N={1,2,3,…}** (infinito)
- Conjunto vacío: **∅**

---

## **3. Representación de conjuntos**

- Por extensión: Listando todos los elementos.
- Por comprensión: Indicando una propiedad que cumplen los elementos.
    
    Ejemplo:
    
    - **{*x* ∈ N: *x* es par} = {2,4,6,…}**

---

## **4. Cardinal de un conjunto**

- El *cardinal* es el número de elementos de un conjunto.
    
    Notación: **∣A∣** o **#A**
    
- Si es finito: **∣A∣ = n**
- Si es infinito: **∣A∣ = ∞**

**Ejemplo:**

- Si **A = {1,2,3**}, entonces **∣A∣ = 3**.

---

## **Relaciones entre conjuntos**

## **1. Igualdad de conjuntos**

- Dos conjuntos **A** y B son *iguales* (**A=B**) si tienen exactamente los mismos elementos, sin importar el orden ni la repetición.
- Formalmente:
    
    **A = B**  ⟺  (**x ∈ A  ⟹  x ∈ B**) y (**x ∈ B  ⟹  x ∈ A**)
    

**Ejemplo:**

- **A = {a,b,c}, B = {b,c,a} ⇒ A = B**

---

## **2. Inclusión de conjuntos (Subconjuntos)**

- **A** está *incluido* en **B (A ⊆ B)** si todo elemento de **A** es también elemento de **B**.
- **A** es *subconjunto* de **B** si **∀x**(**x ∈ A ⟹ x ∈ B**).
- El conjunto vacío es subconjunto de cualquier conjunto: **∅ ⊆ A**.
- Todo conjunto es subconjunto de sí mismo: **A ⊆ A**.

**Ejemplo:**

- **A = {1,2}, B = {1,2,3} ⇒ A ⊆ B**
- **B = {1,2,3}, A = {1,2} ⇒ B ⊈ A**

**Gráfico:**

Diagrama de Venn mostrando **A ⊆ B**:

<table>
  <tr>
    <td>
      B
      <table>
        <tr>
          <td>A</td>
        </tr>
      </table>
    </td>
  </tr>
</table>



---

## **3. Propiedades de la inclusión y la igualdad**

## **Propiedades de la inclusión**

## **Reflexividad**

**Todo conjunto es subconjunto de sí mismo:**

**A ⊆ A**

Esto significa que, si tienes un conjunto **A**, todos sus elementos están en **A** (lo cual es obvio). Por ejemplo, si **A = {1,2,3}**, entonces claramente todos los elementos de **A** están en **A**, así que **A** es subconjunto de sí mismo.

---

## **El conjunto vacío**

**El conjunto vacío es subconjunto de cualquier conjunto:**

**∅ ⊆ A**

El conjunto vacío (**∅**) no tiene ningún elemento. Por definición, no existe ningún elemento en **∅** que no esté en **A**, así que se considera subconjunto de cualquier conjunto, sin importar cuál sea **A**.

---

## **Antisimetría**

**A = B si y solo si A ⊆ B y B ⊆ A**

Esto significa que dos conjuntos son iguales si cada uno es subconjunto del otro.

- Si todos los elementos de **A** están en **B** y todos los de B están en **A**, entonces ambos conjuntos tienen exactamente los mismos elementos, por lo tanto, son iguales.

**Ejemplo:**

**A = {a,b,c**} y **B = {c,b,a}**

Todos los elementos de **A** están en **B** y viceversa, así que **A = B**.

---

## **Transitividad**

**Si A ⊆ B y B ⊆ C, entonces A ⊆ C**

Esto significa que si todos los elementos de **A** están en **B**, y todos los de **B** están en **C**, entonces necesariamente todos los elementos de **A** también están en **C**.

**Ejemplo:**

- **A = {1}**
- **B = {1,2}**
- **C = {1,2,3}**
    
    Aquí, **A ⊆ B** y **B ⊆ C**, por lo tanto, **A ⊆ C**.
    

---

**Resumen gráfico (Diagrama de Venn para transitividad):**

<table>
  <tr>
    <td>
      C
      <table border="1" style="margin: auto;">
        <tr>
          <td>
            B
            <table border="1" style="margin: auto;">
              <tr>
                <td>A</td>
              </tr>
            </table>
          </td>
        </tr>
      </table>
    </td>
  </tr>
</table>



Aquí, el círculo de **A** está dentro de **B**, y **B** está dentro de **C**, por lo que **A** está dentro de **C**.

---

## **Propiedades de la Igualdad**

Las **propiedades de la igualdad** entre conjuntos permiten identificar cuándo dos conjuntos son exactamente el mismo, basándose en la relación de inclusión. Según la fuente principal1, estas propiedades son:

### **Propiedad fundamental de la igualdad de conjuntos**

- **Dos conjuntos A y B son iguales (A = B) si y solo si cada uno es subconjunto del otro:**
    
    **A = B  ⟺  (A ⊆ B y B ⊆ A)**
    

**¿Qué significa esto?**

- Si **todos los elementos de A están en B** y **todos los elementos de B están en A**, entonces los conjuntos tienen exactamente los mismos elementos y, por lo tanto, son iguales.
- El orden en que se escriben los elementos o si se repiten en la notación no afecta la igualdad: solo importa la presencia de los elementos.

## **Ejemplo práctico:**

- **A = {a,b,c}**
- **B = {c,b,a}**

Ambos conjuntos tienen los mismos elementos, así que **A = B**.

## **Otra forma de verlo:**

- Si existe algún elemento que está en **A** pero no en **B**, o en **B** pero no en **A**, entonces **A ≠ B**.
- Si no hay ningún elemento que pertenezca a uno y no al otro, entonces son iguales.

---

## **Resumen visual**

| **Propiedad** | **Explicación** |
| --- | --- |
| **A = B** | Si y solo si **A ⊆ B** y **B ⊆ A** |

---

## **4. Ejemplos prácticos**

- **A = {1,2,10}, B = {1,2,3,6,10} ⇒ A ⊆ B**
- **A = {a,b,c}, B = {b,c,d}** ⇒ No hay relación de inclusión ni igualdad.

---

## **5. Cadenas de inclusión**

- Ejemplo clásico en números:
    
    **N ⊆ Z ⊆ Q ⊆ R ⊆ C**
    
    (**Naturales ⊆ Enteros ⊆ Racionales ⊆ Reales ⊆ Complejos**)
    

**Gráfico:**

Diagrama de Venn para la cadena de inclusión:


<table border="1">
  <tr>
    <td>
      C (Complejos)
      <table border="1" style="margin: auto;">
        <tr>
          <td>
            R (Reales)
            <table border="1" style="margin: auto;">
              <tr>
                <td>
                  Q (Racionales)
                  <table border="1" style="margin: auto;">
                    <tr>
                      <td>
                        Z (Enteros)
                        <table border="1" style="margin: auto;">
                          <tr>
                            <td>
                              N (Naturales)
                            </td>
                          </tr>
                        </table>
                      </td>
                    </tr>
                  </table>
                </td>
              </tr>
            </table>
          </td>
        </tr>
      </table>
    </td>
  </tr>
</table>



---

## **Operaciones entre Conjuntos**

## **Intersección de Conjuntos**

La intersección es una operación fundamental que nos permite encontrar elementos comunes entre conjuntos. Se define formalmente como el conjunto formado por todos los elementos que pertenecen simultáneamente a ambos conjuntos.

**Definición:** La intersección de dos conjuntos **A** y **B**, denotada como **A ∩ B**, es el conjunto:

**A ∩ B = {x | x ∈ A ∧ x ∈ B}**

> Concepto Clave: Dos conjuntos son disjuntos cuando su intersección es el conjunto vacío (∅), es decir, no tienen elementos en común.
> 

**Ejemplos prácticos:**

1. **Ejemplo básico:** Sean **A = {-1, 3, 5, 2, 6, 9}** y **B = {-1, 0, 4, 3, 7, 9, 10}**
    - Elementos comunes: -1, 3, y 9
    - Por tanto: **A ∩ B = {-1, 3, 9}**
2. **Conjuntos disjuntos:** Si **A = {a, b, c}** y **B = {d, e, f}**
    - No hay elementos comunes
    - Resultado: **A ∩ B = ∅**

---

## **Unión de Conjuntos**

La unión combina todos los elementos de dos o más conjuntos, eliminando las repeticiones. Esta operación es inclusiva, ya que incluye elementos que pertenecen a cualquiera de los conjuntos1.

**Definición:** La unión de dos conjuntos **A** y **B**, denotada como **A** ∪ **B**, es:

**A ∪ B = {x | x ∈ A ∨ x ∈ B}**

**Ejemplos ilustrativos:**

1. **Con elementos comunes:** **A = {a, b, c, e}** y **B = {c, e, f}**
    - Resultado: **A ∪ B = {a, b, c, e, f}**
    - **Nota importante:** Los elementos c y e no se repiten en el resultado
2. **Conjuntos disjuntos:** **A = {1, 3, 5}** y **B = {2, 4, 6}**
    - Resultado: **A ∪ B = {1, 2, 3, 4, 5, 6}**

---

## **Complementario de Conjuntos**

El complementario permite identificar qué elementos de un conjunto no pertenecen a otro. Esta operación es especialmente útil para entender las diferencias entre conjuntos1.

**Definición:** El complementario de **A** respecto a **B**, denotado como **B \ A**, es:

**B \ A = {x | x ∈ B ∧ x ∉ A}**

> Notación Especial: Cuando trabajamos con un **conjunto universal X**, el complementario de **A** se denota como **A^c = X \ A**
> 

**Ejemplos detallados:**

1. **Caso general: A = {a, b, c, f}** y **B = {b, c, e, f, g, j}**
    - Elementos de **B** que no están en **A**: e, g, j
    - Resultado: **B \ A = {e, g, j}**
2. **Conjuntos disjuntos:** **A = {a, b, c}** y **B = {d, e, f}**
    - Como no hay elementos comunes: **B \ A = {d, e, f} = B**
3. **Complementario de números pares:** Si **A = {2, 4, 6, 8, ...}** (números pares) sobre **ℕ**
    - Resultado: **A^c = {1, 3, 5, 7, 9, ...}** (números impares)

---

## **Propiedades Fundamentales de las Operaciones**

Las operaciones entre conjuntos siguen propiedades algebraicas importantes que facilitan los cálculos y demostraciones:

**Propiedades Distributivas:**

- **Unión distributiva respecto a la intersección:**
    
    Si tienes un conjunto **A** y quieres unirlo con la intersección de **B** y **C**, es lo mismo que unir **A** con **B** y, por separado, unir **A** con **C**, y después tomar lo que ambos tienen en común.
    
    **Ejemplo:**
    
    - **A = {1}**
    - **B = {1, 2}**
    - **C = {1, 3}**
        
        Primero, la intersección de **B** y **C** es **{1}**.
        
        Unir A con ese resultado da **{1}**.
        
        Ahora, unir **A** con **B** es **{1, 2}** y unir **A** con **C** es **{1, 3}**.
        
        La intersección de esos dos conjuntos es **{1}**.
        
        El resultado es el mismo por ambos caminos.
        
- **Intersección distributiva respecto a la unión:**
    
    Si tienes un conjunto A y quieres intersectarlo con la unión de **B** y **C**, es lo mismo que intersectar **A** con **B** y, por separado, intersectar **A** con **C**, y luego unir esos dos resultados.
    
    **Ejemplo:**
    
    - **A = {1, 2}**
    - **B = {2, 3}**
    - **C = {1, 3}**
        
        La unión de **B** y **C** es **{1, 2, 3}**.
        
        Intersectar **A** con ese resultado da **{1, 2}**.
        
        Ahora, intersectar **A** con **B** es **{2}** y intersectar **A** con **C** es **{1}**.
        
        Unir esos dos resultados da **{1, 2}**.
        
        El resultado coincide.
        
    1. **A ∪ (B ∩ C) = (A ∪ B) ∩ (A ∪ C)**
    2. **A ∩ (B ∪ C) = (A ∩ B) ∪ (A ∩ C)**
    
    ---
    

**Propiedades Conmutativas:**

- **Unión conmutativa:**
    
    Unir **A** con **B** es lo mismo que unir **B** con **A.**
    
    **Ejemplo:**
    
    - **A = {1, 2}**
    - **B = {2, 3}**
        
        Unir **A** con **B** da **{1, 2, 3}**.
        
        Unir **B** con **A** también da {**1, 2, 3}**.
        
- **Intersección conmutativa:**
    
    Intersectar **A** con **B** es lo mismo que intersectar **B** con **A**.
    
    **Ejemplo:**
    
    - **A = {1, 2}**
    - **B = {2, 3}**
        
        Intersectar **A** con **B** da **{2}**.
        
        Intersectar **B** con A también da **{2}**.
        

3. **A ∪ B = B ∪ A**

4. **A ∩ B = B ∩ A**

---

**Leyes de De Morgan:**

- **Complemento de la unión:**
    
    Los elementos que no están ni en **A** ni en **B** son exactamente los que no están en **A** y tampoco están en **B**.
    
    **Ejemplo:**
    
    - **Universal: {1, 2, 3, 4}**
    - **A = {1, 2}**
    - **B = {2, 3}**
        
        La unión de **A** y **B** es **{1, 2, 3}**.
        
        Los que no están en la unión son **{4}**.
        
        Los que no están en **A** son **{3, 4}**, los que no están en **B** son **{1, 4}**.
        
        Lo que está en ambos conjuntos (**fuera de A y fuera de B**) es **{4}**.
        
- **Complemento de la intersección:**
    
    Los elementos que no están en ambos conjuntos a la vez son los que están fuera de A o fuera de B (o fuera de ambos).
    
    **Ejemplo:**
    
    - **Universal: {1, 2, 3, 4}**
    - **A = {1, 2}**
    - **B = {2, 3}**
        
        La intersección de **A** y **B** es **{2}**.
        
        Los que no están en la intersección son **{1, 3, 4}**.
        
        Los que no están en **A** son **{3, 4}**, los que no están en **B** son **{1, 4}**.
        
        Si unes esos dos resultados, tienes **{1, 3, 4}**.
        
    
    7. (**A ∪ B)^c = A^c ∩ B^c**
    
    8. **(A ∩ B)^c = A^c ∪ B^c**
    

---

## **Conjunto de las Partes**

## **Definición y Construcción**

El conjunto de las partes de un conjunto A, denotado como P(A), es el conjunto formado por todos los subconjuntos posibles de A, incluyendo el conjunto vacío y el propio A1.

**Definición formal: P(A) = {B | B ⊆ A}**

## **Método de Construcción Sistemática**

Para construir **P(A)** de manera organizada, se recomienda clasificar los subconjuntos por su cardinal (número de elementos):

**Ejemplo práctico:** Sea **A = {1, 2, 3}**

- **Cardinal 0:** **∅**
- **Cardinal 1:** **{1}, {2}, {3}**
- **Cardinal 2:** **{1,2}, {1,3}, {2,3}**
- **Cardinal 3:** **{1,2,3}**

Por tanto: **P(A) = {∅, {1}, {2}, {3}, {1,2}, {1,3}, {2,3}, {1,2,3}}**

> Teorema Fundamental: **Si |A| = n (A tiene n elementos), entonces |P(A)| = 2^n**
> 

## **Aplicaciones Prácticas**

El conjunto de las partes es fundamental en:

- Teoría de probabilidades (espacios muestrales)
- Lógica matemática (álgebras de Boole)
- Informática (representación de estados)

---

## **Relaciones entre Conjuntos**

## **Producto Cartesiano**

Antes de definir relaciones, necesitamos comprender el producto cartesiano, que proporciona la base para establecer correspondencias entre elementos de diferentes conjuntos1.

**Definición:** El producto cartesiano de **A** y **B**, denotado **A × B**, es:

**A × B = {(a,b) | a ∈ A ∧ b ∈ B}**

**Ejemplos fundamentales:**

1. **Caso finito:** **A = {1, 2, 3}** y **B = {c, d}**
    
    **A × B = {(1,c), (1,d), (2,c), (2,d), (3,c), (3,d)}**
    
2. **Caso infinito:** Si **A = ℝ** y **B = ℝ1**
    
    **A × B = ℝ²** (el plano real)
    

> Propiedad del Cardinal:**|A × B| = |A| × |B|**
> 

---

## **Concepto de Relación**

Una relación entre conjuntos **A** y **B** es esencialmente un subconjunto del producto cartesiano **A × B** que especifica qué elementos de **A** están relacionados con qué elementos de **B**.

**Definición:** Una relación **R** de **A** en **B** es un subconjunto **R ⊆ A × B**.

Si **(a,b) ∈ R**, decimos que "**a** está relacionado con **b**" ****y lo escribimos como **aRb**.

---

## **Relaciones de Equivalencia**

Las relaciones de equivalencia son un tipo especial de relación que generaliza el concepto de igualdad. Una relación R en un conjunto A es de equivalencia si cumple tres propiedades fundamentales:

**Propiedades:**

1. **Reflexiva:** **∀a ∈ A, aRa**
2. **Simétrica: ∀a,b ∈ A, aRb ⟹ bRa**
3. **Transitiva:** **∀a,b,c ∈ A, (aRb ∧ bRc) ⟹ aRc**

**Ejemplos importantes:**

- Congruencia módulo n en los enteros
- Igualdad de conjuntos
- Semejanza de triángulos

---

## **Aplicaciones (Funciones)**

## **Definición Fundamental**

Una aplicación o función de **A** en **B** es una relación especial que asigna a cada elemento de **A** exactamente un elemento de **B**.

**Definición:** Una aplicación **f: A → B** es una relación donde:

- Para todo **a ∈ A**, existe un único **b ∈ B** tal que **f(a) = b**
- A se llama dominio, B se llama codominio

## **Tipos de Aplicaciones**

## **Aplicaciones Inyectivas**

Una función es inyectiva (uno a uno) si elementos diferentes del dominio se mapean a elementos diferentes del codominio.

**Definición:** **f: A → B** es inyectiva si:

**∀a₁,a₂ ∈ A, a₁ ≠ a₂ ⟹ f(a₁) ≠ f(a₂)**

**Equivalentemente:** **f(a₁) = f(a₂) ⟹ a₁ = a₂**

---

## **Aplicaciones Sobreyectivas**

Una función es sobreyectiva (sobre) si todo elemento del codominio es imagen de al menos un elemento del dominio.

**Definición:** **f: A → B** es sobreyectiva si:

**∀b ∈ B**, **∃a ∈ A** tal que **f(a) = b**

---

## **Aplicaciones Biyectivas**

Una función es biyectiva si es tanto inyectiva como sobreyectiva. Las funciones biyectivas establecen una correspondencia uno a uno entre los conjuntos.

**Propiedades importantes:**

- Solo las funciones biyectivas tienen función inversa
- Establecen que dos conjuntos tienen el mismo cardinal

---

## **Composición de Aplicaciones**

La composición permite combinar funciones secuencialmente.

**Definición:** Si **f: A → B** y **g: B → C**, entonces la composición **g ∘ f: A → C** se define como:

**(g ∘ f)(a) = g(f(a))**

**Propiedades:**

1. **Asociativa:** **(h ∘ g) ∘ f = h ∘ (g ∘ f)**
2. **No conmutativa:** En general, **g ∘ f ≠ f ∘ g**

---

## **Aplicación Inversa**

Una función **f: A → B** tiene inversa **f⁻¹: B → A** si y solo si f es biyectiva.

**Propiedades:**

- **f⁻¹(f(a)) = a para todo a ∈ A**
- **f(f⁻¹(b)) = b para todo b ∈ B**
- **(f⁻¹)⁻¹ = f**

---

## **Numerabilidad**

La numerabilidad clasifica conjuntos infinitos según su "tamaño".

**Definiciones:**

- Un conjunto es **numerable** si existe una biyección con **ℕ**
- Un conjunto es **no numerable** si es infinito pero no numerable

**Ejemplos importantes:**

- **ℕ, ℤ, ℚ** son numerables
- **ℝ, ℂ** son no numerables

**Teorema de Cantor:** El conjunto de las partes de ℕ no es numerable, demostrando que existen infinitos de diferentes "tamaños".

> Aplicación práctica: La numerabilidad es fundamental en teoría de la computación para entender qué problemas son computables y cuáles no.
>