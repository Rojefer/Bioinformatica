# Laboratorio 02 - Alineamiento de secuencias

### Parte 1: Colectar genes homólogos

##### **1. ¿Qué función cumple el gen SRY?**

Es un gen sin intrones, el cual codifica para un factor de transcripcion encargado de la codifiacion de los testiulos, por lo que inicia la determinaion del sexo.

##### **2. ¿Cuántos genes ortólogos están anotados en esa base de datos?**

Atualmente, según la pagina, existen 29 organismos que poseen genes ortologos con el gen SRY humano.

https://raw.githubusercontent.com/bioinf-biotec/labs_bioinf/master/documents/SRY_orthologs_mRNAs.fasta
   
### Parte 2: Alineamiento múltiple

##### **3. ¿Qué es el EMBL-EBI?**

Es un programa de alinemiento de secuenias, ess puedes ser de acidos nucleios o proteinas, tambien deben ser de longitud parecida. Este programa puede hacer dicho alineamiento entre 3 o mas seuenias a la vez.
De acuerdo con el resulatdo del alineamiento se puede inferir de la homologia o no homologia de los genes secuenciados.

##### **4. ¿Cuál es el programa que ellos ofrecen que funciona mejor para secuencias de proteínas?**

La mejor par ratamiento de proteinas es "MUSCLE"(https://www.ebi.ac.uk/Tools/msa/muscle/)

##### **5.¿Qué otros tipo de herramientas ofrece EMBL-EBI?**

Ofrece distintos tipos de alinemiento de seuencias, ya se para proteinas completas, regiones especificas o cualquier otro sitio de interes. ya sean de seuencias medianas, laras o cortas.

##### **6. ¿Cuál es el costo de abrir un gap?**

1.53

##### **7. ¿Cuál es el costo de extender un gap?**

0.123

##### **8. ¿Cuál es la longitud total del alineamiento?**

La longitud de alineamiento es de 1782 

![](Imagen de alineamiento)

##### **9. ¿Cuál es la especie cuyo gen SRY está más relacionado con el gen SRY de humanos?**

SRY_Piliocolobus_tephrosceles 0.0014

![](Imagen del arbol filogenetico, mas cercano)

##### **10. ¿Cuál es el más lejano?**

SRY_Puma_concolor 0.10024

![](Imagen del arbol filogenetico, mas lejano)

##### **11. ¿Cuál es la especie cuyo gen SRY es más cercana a la del burro?**

SRY_Equus_przewalskii 0.00059

![](Gen mas cercano al del burro)

##### **12. ¿Cómo esperas que sea el alineamiento si el costo de abrir un gap aumenta? ¿Y si disminuye?**

Se espera un cambio en elnumero de alineamiento de pares debido a la alza de abrir un gap. se verían menos gaps abiertos y más etenciones de gaps, con el objetivo de disnuir el consumo o gasto; en el caso contrario se observaría lo opuesto a lo descrito anteriormente.

##### **13. ¿Cómo esperas que sea el alineamiento si el costo de extender un gap aumenta? ¿Y si disminuye?**

Se espera una secuencia con mas aperturas de gaps que extensiones de estos, ya que le saldría mas barato abrir que extender gaps.
en el caso contrario, si disminuye el costo de la extencion de gaps, habrá mas extenciones de gaps que aperturas ya que el programa busca disminuir al minimo los costos.

##### **14. ¿Cuál fue el efecto de aumentar el costo de abrir un gap en la longitud total del alineamiento?**

La longitud del alineamiento se mantuvo constante, en donde el gen >SRY_Odobenus_rosmarus/1-663
mantuvo la longitud de 1782.

##### **15. Prueba lo mismo, pero esta vez disminuyendo al mínimo el costo de extender un gap. Describe cómo cambia el alineamiento.**

Al disminuir al mínimo el costo de extender un gap, se ve afetado el alineamiento, ya que el sistema busca gastar lo menos posible. Por esto, los aminoacidos se agrupan al inicio del alineamiento; tambien, presenta espacios en blanco casi completos entre medio.

![](Imagen de extencion al minimo de gap).

### Parte 3: Diseño de partidores

##### **16. Agrega a tu informe una lista de los "LEFT PRIMER" y "RIGHT PRIMER" que obtuviste usando Primer3.**

**Left Primer:** 

     1.- TTACAGGCCATGCACAGAGA
     2.- GGATAGAGTGAAGCGACCCA
     3.- AGATGCTGCCGAAGAATTGC
     4.- CGAAGATGCTGCCGAAGAAT

**Right Primer:** 

     1.- CTTGAGTGTGTGGCTTTCGT
     2.- TTTCTCTCTGTGCATGGCCT
     3.- GCTTTGTCCAGTGGCTGTAG
     4.- CTACAGCTTTGTCCAGTGGC
     
 ![](imagen de lefth and Right primer 3)
 
##### **17. Indica los partidores forward y reverse que escogiste y explica por qué son la mejor opción para amplificar el gen SRY de humano.**

Partidor Forward: CGAAGATGCTGCCGAAGAAT
Partidor Reverse: GCTTTGTCCAGTGGCTGTAG

Se eligieron estos primers porque todos los otros parametros están marcados como buenos; ademas, al revisar lainformacion del alinemaiento, da un porcentaje de GC del 57% según Amplix.

##### **18. ¿Cuál es el largo del amplicón? ¿Y la temperatura de annealing sugerida?**

El largo es de 207 nucl. y la temperatura sugerida es de 55 °C.

![](Temperatura y largo del alineamiento)





