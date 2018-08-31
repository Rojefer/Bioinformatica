# Laboratorio 04 - Filogenética Molecular

### Plataforma Phylogeny.fr y preparación de datos

##### 1. ¿Qué ofrece o para qué sirve el portal Phylogeny.fr?

Sirve para contruir secuencias filogenéticas, entre especies, a la vez esá acoplada a varios programas computacionales, los cuales sirven para comparar la evolucion de alguna secuencia en específico.

##### 2. Nombra y explica brevemente los 3 modos en los que se puede ejecutar el pipeline de Phylogeny.fr.

Pipeline es un programa que hace que el trabajo se realice de una forma en específica o de manera ordenada, ya sea como primer paso alineamiento, creacion del arbol, inferencias relacionadas a la evolucion de esa secuencia en específico. 

**One Click:**    Es un método en donde el programa toma las desiciones por uno.
**Avanzado:**     Es un método en donde uno elige sus propios parámetros de estudio.
**A la carta:**   Es un método que sólo trabaja con una secuencia única pero te permite comparar el resultado con otras secuencias homologas.

##### 3. Menciona qué tipos de análsis se pueden realizar en el portal de acuerdo a la documentación. 

Se pueden realizar Blast, Alineamientos múltiples, Poligenia, Arboles filogenicos, entre otros.

##### 4. Incluye en tu informe una captura de pantalla de las dos filogenias que inferiste.

![](https://github.com/Rojefer/Bioinformatica/blob/master/.gitignore/filogenia%201%20y%202.png?raw=true).

##### 5. ¿A qué se refiere el paso de Alignment curation y para qué sirve? 

Es una herramienta que te permite seleccionar como quieres que sea tu tratamiento de alineamiento. En esta herramienta se encuentran disponibles dos modos, "Gblocks" (se encarga de remover todas las partes no alineadas de la secuencia), y "Remove positions with gaps" (se encarga de remover solo los gaps del alineamiento).

##### 6. ¿Cuál es la diferencia entre BioNJ y Neighbor?.

**BioNJ:** Reduce la distancia de la matriz mediante reemplazo de taxones.
**Neighbor:** En comparacion con "BioNJ", éste método mantiene una mayor distancia.

##### 7. Incluye en tu informe una captura de pantalla de las dos filogenias que inferiste (sin Alignment curation).

![](https://github.com/Rojefer/Bioinformatica/blob/master/.gitignore/Filogenia%201%20y%202%20sin%20curacion%20de%20alineamiento.png?raw=true).

##### 8. ¿Cuál es el efecto de no hacer la curación del alineamiento en las filogenias?.

El efecto se puede identificar observando las dos imagenes, tanto curadas como no curadas. Se puede observar en ambas imágenes que cambia drasticamente en arbol filogenético final, a su vez se puede observar que se desordenan las posiciones de las ramas con los distintos genes y distintas interacciones entre ellos. 

##### 9. Describe las diferencias entre las filogenias que has estimado (4 en total): cantidad de grupos monofiléticos, relaciones que potencialmente cambiaron, etc.

En la pregunta 4 y 7, donde la 4 están las filogenias con curación y en la 7 están las filogenias sin curación.
Se puede dar cuenta del cambio producido por la curación del alineamiento. 

Si se observa la filogenia nº1, se puede dar cuenta de la diferencia producida en el arbol filogenético final. A su vez, se pueden observar 24 grupos monofileticos pero cuando está sin curación la cantidad de grupos monofiléticos cambia a 28. Por otra parte, al identificar el gen del Homo_spiens, al principio, está más cercano al gen Macaca_mulatta pero cuando está sin curamiento, Macaca_mulatta está mas cerca a Chlorocebus_sabacus.


Finalmente ne la filogenia nº2 se pueden obserbar cambios similares a los mencionados anteriormente pero, en las diferencias monofiléticas, al inicio posee 25 y al final posee 28. El arbol filogenético está más disperso y con mayor número de ramificaciones.




