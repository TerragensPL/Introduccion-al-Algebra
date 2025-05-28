# Combinatoria

# **Introducción a la Combinatoria**

La combinatoria es una rama fundamental de las matemáticas que estudia el arte de contar, organizar y seleccionar objetos siguiendo determinadas reglas. Este tema constituye la base para comprender muchos conceptos avanzados en matemáticas, informática y estadística. En esta unidad aprenderemos los principios fundamentales que nos permitirán resolver problemas de conteo de manera sistemática, desde los casos más simples hasta situaciones más complejas que involucran permutaciones, combinaciones y variaciones.

## **Conceptos Fundamentales y Principios de Cardinalidad**

## **Principio de la Adición**

El principio de la adición es el más básico de todos los principios de conteo y constituye el punto de partida para comprender la combinatoria1. Este principio establece que si tenemos dos conjuntos disjuntos (que no tienen elementos en común), el número total de elementos al unir ambos conjuntos es la suma de los elementos de cada conjunto individual.

**Definición formal**: Si **A** y **B** son dos conjuntos disjuntos, es decir, **A ∩ B = ∅**, entonces **|A ∪ B| = |A| + |B|**, donde **|X|** denota el cardinal (número de elementos) del conjunto **X**.

Para comprender mejor este concepto, imaginemos que tenemos una caja con 5 pelotas rojas y otra caja con 3 pelotas azules. Si queremos saber cuántas pelotas tenemos en total, simplemente sumamos: 5 + 3 = 8 pelotas. Este es el principio de la adición en su forma más simple.

**Ejemplo práctico**: En una clase hay 12 estudiantes que estudian francés y 8 que estudian alemán. Si ningún estudiante estudia ambos idiomas, ¿Cuántos estudiantes estudian un idioma extranjero? La respuesta es 12 + 8 = 20 estudiantes.

---

## **Principio de Dirichlet**

El principio de Dirichlet, también conocido como principio del palomar, es un principio fundamental que aparece frecuentemente en problemas de combinatoria y teoría de números. Este principio establece una relación entre el número de objetos y el número de contenedores donde se colocan.

**Enunciado**: Si tenemos n objetos que deben distribuirse en m contenedores, y **n > m**, entonces al menos un contenedor debe contener más de un objeto. De manera más general, si distribuimos n objetos en m contenedores, al menos un contenedor contendrá al menos **⌈n/m⌉** objetos, donde **⌈x⌉** denota el menor entero mayor o igual que **x**.

**Ejemplo ilustrativo**: En una fiesta hay 13 personas. Como un año tiene 12 meses, por el principio de Dirichlet, al menos dos personas deben haber nacido en el mismo mes. Este principio es especialmente útil para demostrar la existencia de ciertas propiedades sin necesidad de construir ejemplos específicos.

---

## **Principio de Inclusión-Exclusión**

El principio de inclusión-exclusión es una generalización del principio de la adición que nos permite contar elementos cuando los conjuntos no son disjuntos1. Este principio es fundamental cuando tenemos conjuntos que se superponen y necesitamos evitar contar elementos repetidamente.

**Formulación para dos conjuntos**: **|A ∪ B| = |A| + |B| - |A ∩ B|**. La idea es que al sumar **|A|** y **|B|**, estamos contando dos veces los elementos que están en ambos conjuntos, por lo que debemos restar **|A ∩ B|** para obtener el resultado correcto.

**Ejemplo**: En una escuela, 30 estudiantes practican fútbol, 20 practican baloncesto, y 8 practican ambos deportes. ¿Cuántos estudiantes practican al menos uno de estos deportes? Aplicando el principio: 30 + 20 - 8 = 42 estudiantes.

**Extensión a tres conjuntos**: **|A ∪ B ∪ C| = |A| + |B| + |C| - |A ∩ B| - |A ∩ C| - |B ∩ C| + |A ∩ B ∩ C|**. Esta fórmula ilustra el patrón alternante de suma y resta que caracteriza este principio.

---

## **Principio de la Multiplicación**

El principio de la multiplicación es fundamental para el conteo secuencial y forma la base de muchos conceptos combinatorios1. Este principio se aplica cuando tenemos una secuencia de decisiones o elecciones independientes.

**Enunciado**: Si una primera tarea puede realizarse de m maneras diferentes y, para cada una de estas maneras, una segunda tarea puede realizarse de n maneras diferentes, entonces las dos tareas juntas pueden realizarse de **m × n** maneras diferentes1.

**Ejemplo básico**: Si tenemos 3 camisas diferentes y 4 pantalones diferentes, podemos formar 3 × 4 = 12 conjuntos diferentes de vestimenta. Esta multiplicación se debe a que por cada camisa tenemos 4 opciones de pantalón.

**Generalización**: Para **k** tareas consecutivas que pueden realizarse de **n₁, n₂, ..., nₖ** maneras respectivamente, el número total de maneras de realizar todas las tareas es **n₁ × n₂ × ... × nₖ**.

---

## **Permutaciones: Ordenando Elementos**

## **Permutaciones sin Repetición**

Las permutaciones sin repetición estudian las diferentes maneras de ordenar un conjunto de elementos distintos1. Este concepto es fundamental cuando el orden importa y no podemos repetir elementos.

**Definición**: Una permutación de n elementos distintos es cualquier ordenación posible de estos n elementos1. El número de permutaciones de n elementos se denota como **P(n)** o **n!** (n factorial).

**Fórmula**: **P(n) = n! = n × (n-1) × (n-2) × ... × 2 × 11**. Por convención, **0! = 1**.

**Ejemplo práctico**: ¿De cuántas maneras diferentes pueden sentarse 5 personas en una fila de 5 sillas? Para la primera silla tenemos 5 opciones, para la segunda quedan 4, para la tercera quedan 3, y así sucesivamente. Por tanto: 5! = 5 × 4 × 3 × 2 × 1 = 120 maneras diferentes.

**Permutaciones parciales**: Cuando queremos ordenar solo r elementos de un conjunto de **n** elementos **(r ≤ n)**, usamos la fórmula **P(n,r) = n!/(n-r)!**. Por ejemplo, si queremos elegir y ordenar 3 personas de un grupo de 10 para formar un podio: **P(10,3) = 10!/(10-3)! = 10!/7! = 10 × 9 × 8 = 720**.

---

## **Permutaciones con Repetición**

Las permutaciones con repetición aparecen cuando algunos elementos del conjunto son idénticos. En estos casos, debemos ajustar nuestro conteo para evitar sobrestimar el número de ordenaciones realmente diferentes.

**Fórmula**: Si tenemos **n** elementos donde hay **n₁** elementos de tipo 1, **n₂** elementos de tipo 2, **..., nₖ** elementos de tipo **k**, entonces el número de permutaciones diferentes es: **n!/(n₁! × n₂! × ... × nₖ!)**.

**Ejemplo ilustrativo**: ¿Cuántas palabras diferentes se pueden formar con las letras de "MATEMATICAS"? Tenemos 11 letras en total: **M** aparece 2 veces, **A** aparece 3 veces, **T** aparece 2 veces, **E, I, C, S** aparecen 1 vez cada una. El número de permutaciones es: 11!/(2! × 3! × 2! × 1! × 1! × 1! × 1!) = 39,916,800/(2 × 6 × 2) = 1,663,200.

---

## **Combinaciones: Seleccionando sin Orden**

## **Combinaciones sin Repetición**

Las combinaciones estudian las maneras de seleccionar elementos de un conjunto cuando el orden no importa1. Este concepto es crucial en muchas aplicaciones prácticas donde solo nos interesa qué elementos elegimos, no en qué orden.

**Definición**: Una combinación de r elementos tomados de un conjunto de n elementos es cualquier selección de r elementos donde el orden no importa1.

**Fórmula**: **C(n,r) = (n r) = n!/(r! × (n-r)!)**. El símbolo **(n r)** **se lee** "**n sobre r**" o "**coeficiente binomial**".

**Ejemplo fundamental**: ¿De cuántas maneras podemos elegir 3 estudiantes de una clase de 20 para formar un comité? Como el orden no importa (el comité es el mismo independientemente del orden de selección), usamos combinaciones: **C**(20,3) = 20!/(3! × 17!) = (20 × 19 × 18)/(3 × 2 × 1) = 1,140.

**Propiedades importantes**:

- **C(n,0)** = 1 (solo hay una manera de no elegir nada)
- **C(n,n)** = 1 (solo hay una manera de elegir todo)
- **C(n,r)** = **C(n,n-r)** (elegir **r** elementos es equivalente a dejar **n-r** elementos)

---

## **Combinaciones con Repetición**

Las combinaciones con repetición permiten seleccionar el mismo elemento múltiples veces. Este tipo de problemas aparece frecuentemente en contextos donde tenemos recursos ilimitados de cada tipo.

**Fórmula**: El número de maneras de elegir r elementos de n tipos diferentes, permitiendo repetición, es: **C(n+r-1,r) = (n+r-1 r)**.

**Ejemplo práctico**: En una heladería hay 5 sabores diferentes. ¿De cuántas maneras podemos elegir 3 bolas de helado si podemos repetir sabores? Usamos la fórmula: C(5+3-1,3) = C(7,3) = 35 maneras diferentes.

**Interpretación visual**: Podemos visualizar este problema como distribuir r objetos idénticos en n cajas diferentes, lo cual equivale a colocar **r+n-1** objetos en línea con **n-1** separadores.

---

## **Variaciones: Seleccionando con Orden**

## **Variaciones sin Repetición**

Las variaciones sin repetición combinan los conceptos de selección y ordenación1. Estudiamos cuántas maneras hay de elegir y ordenar r elementos de un conjunto de n elementos distintos.

**Definición**: Una variación de **r** elementos tomados de n elementos distintos es cualquier ordenación de r elementos seleccionados del conjunto original.

**Fórmula**: **V(n,r) = n!/(n-r)! = n × (n-1) × ... × (n-r+1)**. Esta es la misma fórmula que las permutaciones parciales, ya que el concepto es idéntico.

**Ejemplo clarificador**: En una carrera con 10 corredores, ¿de cuántas maneras pueden quedar los 3 primeros lugares? Como el orden importa (1º, 2º, 3º son posiciones diferentes), usamos variaciones: V(10,3) = 10 × 9 × 8 = 720.

**Relación con combinaciones**: **V(n,r) = C(n,r) × r!**, ya que primero seleccionamos **r** elementos (combinación) y luego los ordenamos (**r!** permutaciones).

---

## **Variaciones con Repetición**

Las variaciones con repetición son el caso más general donde podemos tanto repetir elementos como considerar el orden. Este tipo de problemas aparece cuando tenemos recursos ilimitados y el orden de selección es importante.

**Fórmula**: El número de variaciones de r elementos tomados de n tipos diferentes, con repetición permitida, es: **n^r**.

**Ejemplo fundamental**: ¿Cuántas contraseñas de 4 dígitos se pueden formar usando los dígitos 0-9? Como podemos repetir dígitos y el orden importa, tenemos: 10^4 = 10,000 contraseñas posibles.

**Justificación de la fórmula**: Para cada una de las r posiciones, tenemos n opciones disponibles (ya que podemos repetir). Por el principio de la multiplicación: **n × n × ... × n** (**r** veces) = **n^r**.

---

## **Relaciones entre Conceptos y Estrategias de Resolución**

## **Tabla Comparativa de Fórmulas**

| **Tipo** | **Sin repetición** | **Con repetición** |
| --- | --- | --- |
| Permutaciones | **n!** | **n!/(n₁!×n₂!×...×nₖ!)** |
| Variaciones | **n!/(n-r)!** | **n^r** |
| Combinaciones | **n!/(r!×(n-r)!)** | **(n+r-1)!/(r!×(n-1)!)** |

## **Estrategia para Identificar el Tipo de Problema**

Para resolver correctamente un problema combinatorio, debemos preguntarnos tres cuestiones fundamentales:

1. **¿Importa el orden?** Si sí, consideramos permutaciones o variaciones. Si no, consideramos combinaciones.
2. **¿Seleccionamos todos los elementos o solo algunos?** Si todos, son permutaciones. Si algunos, son variaciones o combinaciones.
3. **¿Podemos repetir elementos?** Esto determina si usamos fórmulas con o sin repetición.

**Diagrama de decisión**:



<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Árbol de decisiones</title>
    <style>
        ul {
            list-style-type: none;
        }
        .tree {
            font-family: Arial, sans-serif;
        }
        .tree ul {
            padding-left: 20px;
            border-left: 2px solid #000;
            margin: 10px 0;
        }
        .tree li {
            margin: 5px 0;
            position: relative;
        }
        .tree li::before {
            content: "├─";
            position: absolute;
            left: -18px;
        }
        .tree li:last-child::before {
            content: "└─";
        }
    </style>
</head>
<body>
    <h1>Árbol de decisiones</h1>
    <div class="tree">
        <ul>
            <li>¿Importa el orden?
                <ul>
                    <li>SÍ
                        <ul>
                            <li>¿Todos los elementos? → SÍ → Permutaciones</li>
                            <li>¿Solo algunos? → Variaciones</li>
                        </ul>
                    </li>
                    <li>NO → Combinaciones</li>
                </ul>
            </li>
        </ul>
    </div>
</body>
</html>




Esta estructura conceptual proporciona las herramientas fundamentales para abordar problemas combinatorios de complejidad creciente, estableciendo las bases para estudios más avanzados en matemáticas discretas y teoría de la probabilidad.

---

## **Ejemplos Integrados de Aplicación**

- **Problema 1**: Un código de seguridad consta de 2 letras seguidas de 3 números. ¿Cuántos códigos diferentes existen si no se pueden repetir ni letras ni números?
    
    *Solución*: Las letras: V(26,2) = 26 × 25 = 650. Los números: V(10,3) = 10 × 9 × 8 = 720. Total: 650 × 720 = 468,000 códigos.
    
- **Problema 2**: ¿De cuántas maneras se pueden repartir 12 libros idénticos entre 4 estudiantes?
    
    *Solución*: Es una combinación con repetición: C(4+12-1,12) = C(15,12) = C(15,3) = 455 maneras.
    
- **Problema 3**: En un torneo de ajedrez participan 8 jugadores. ¿Cuántas maneras hay de que queden los 3 primeros lugares si no puede haber empates?
    
    *Solución*: Como el orden importa y no hay repetición, usamos variaciones: V(8,3) = 8 × 7 × 6 = 336 maneras.