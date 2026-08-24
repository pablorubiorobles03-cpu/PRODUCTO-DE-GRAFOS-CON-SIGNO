# Producto de grafos con signo y equilibrio estructural

**Autor:** Pablo Rubio Robles  
**Titulación:** Grado en Matemáticas | Universidad de Oviedo  

---

## Resumen del proyecto

Este repositorio contiene la memoria completa de mi Trabajo de Fin de Grado (TFG) en Matemáticas. La investigación se centra en el análisis algebraico y estructural de los **grafos con signo**. 

Mientras que la teoría de grafos clásica se limita a modelar la existencia o ausencia de conexiones (adyacencia), los grafos signados introducen una dimensión cualitativa fundamental: la polaridad. Al asignar un signo (+ o -) a cada arista, es posible modelar matemáticamente relaciones de atracción/repulsión, confianza/desconfianza o correlación positiva/negativa.

El eje central de este trabajo es la formalización del **producto de grafos con signo**. A lo largo del documento, se demuestra que el espacio de todas las signaturas posibles sobre un grafo, equipado con esta operación, conforma un grupo abeliano isomorfo al grupo aditivo $\mathbb{Z}_2^{|A|}$.

---

##  Aplicaciones en Data Science y Machine Learning

Aunque este trabajo se desarrolla en el marco de la matemática pura y el álgebra abstracta, las estructuras aquí demostradas constituyen el motor algorítmico de múltiples soluciones reales en el sector de los datos:

*   **Análisis de Redes Dinámicas (SNA):** El producto de signaturas permite operar matemáticamente con estados temporales de una red. Multiplicar dos instantes temporales revela de forma exacta qué conexiones han mutado, facilitando el tracking de evolución en redes complejas.
*   **Detección de Fraude y Anomalías:** Mediante la agrupación en clases de equivalencia, es posible evaluar el balance global de redes financieras o transaccionales. Las desviaciones del equilibrio estructural son indicadores clave para la detección de comportamientos anómalos o fraudulentos.
*   **Clustering y Segmentación:** La partición de grafos a través de signaturas de corte ($\delta_X$) fundamenta los algoritmos de segmentación para identificar comunidades fuertemente polarizadas en redes sociales o bases de clientes.
*   **Sistemas de Recomendación:** Modelado riguroso del principio cognitivo *"el enemigo de mi enemigo es mi amigo"*. Entender el equilibrio de los ciclos permite a los algoritmos inferir relaciones no explícitas y predecir afinidades.

---

##  Habilidades técnicas demostradas

La realización de esta investigación certifica competencias clave para roles de carácter técnico:

*   **Abstracción Algorítmica:** Capacidad para generalizar problemas complejos y modelarlos mediante estructuras matemáticas sólidas (grupos, isomorfismos, clases de equivalencia).
*   **Resolución de Problemas:** Demostración formal de teoremas y optimización de análisis de ciclos, pasando de comprobaciones locales (ciclo a ciclo) a propiedades estructurales globales.
*   **Documentación Técnica:** Redacción científica rigurosa y maquetación profesional utilizando **LaTeX**.

---

##  Estructura del Documento

El documento principal (disponible en formato PDF en este repositorio) se estructura de la siguiente manera:

1. **Introducción:** Origen de la teoría de grafos con signo, noción de balance y motivación del estudio algebraico.
2. **Preliminares:** Bases formales de la teoría de grafos, álgebra de grupos, isomorfismos y teoría de conjuntos.
3. **Producto de grafos con signo:** Definición de la operación arista a arista y demostración de su estructura de grupo abeliano.
4. **Equivalencia de la aplicación cambio de signo:** Análisis del *switching* local y su reescritura exacta mediante signaturas de corte.
5. **Producto de clases de equivalencia:** Agrupación de signaturas y demostración de la compatibilidad del producto con el espacio cociente.
6. **Clase de cambio de signo de la signatura positiva:** Estudio del subgrupo que aglutina los grafos balanceados y demostración de su isomorfismo al grupo $\mathbb{Z}_2^{|V|-c}$.
7. **Conclusiones:** Recapitulación de los resultados, clasificación estructural y posibles líneas de trabajo futuro (grafos dirigidos y algoritmos computacionales).

> *"La matemática abstracta no solo resuelve ecuaciones; proporciona el andamiaje lógico para estructurar, comprender y extraer valor del caos de los datos."*
