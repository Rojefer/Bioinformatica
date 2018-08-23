# Laboratorio 03 - Ensamblaje de genomas y predicción de genes

### Parte 1: El artículo genoma

##### 1. ¿Cuántos Sequencing Projects y Analysis Projects hay depositados en GOLD? ¿Cuál es la diferencia entre ambos?
**Sequencing Projects**
215.124 proyectos depositados.

**Analysis Projects**
174.491 proyectos almacendos.

Van casi de l mano, **``Secuencing Projects``** Va dirigida a las secueniaciones individuales, esta secuenciacion puede ser un genoma aislado, transcriptoma o muestra de metagenomas. Muchos de estos proyectos de secuenciacion se pueden realizar  partir de una unica muestra. Por otro lado, **``Analysis Projets``** va dirigido al procesamiento informatico de un proyecto de secuenciacion. Esto quiere decir que entrega informacion sobre como fue su respectivo ensamblaje y sus distintas anotaciones. 

##### 2. ¿Cuál es el dominio más representado en la base de datos, archea, bacteria, eukaryote, o virus?

EL dominio más representado en gol son los organismos procarioticos, esto quiere deir que hay mas informacion a serca de  bacterias en general.

##### 3. ¿Cuáles son los phyla más representados entre los proyectos de genomas bacterianos en la base de datos?

Las más representadas son las proteobacterias.

##### 4. ¿A qué tipo de proyectos pertenece la mayor cantidad de genomas bacterianos depositados en GOLD? (tipo de proyecto, se refiere al tópico de la investigación, por ejemplo, salud humana, ambiental, etc.)

Están relacionados, en su mayor parte, al área de la medicina.

#####  5. ¿Cuál es el artículo original del genoma? (en el cual se reporta la sequenciación y ensamble del genoma).

The bonobo genome compared with the chimpanzee and human genomes. Prüfer K, et al. Nature 2012 Jun 28.

https://www.ncbi.nlm.nih.gov/pubmed/22722832.


##### 6. Explica, qué es el N50, L50, y NG50.

**N50**
Corresponde a la suma de contigs mas grandes, que en su conjunto son la mitad del tamaño de genoma.
**L50**
Corresponde a la cantidad de contigs que son capaces de producir un N50.

**NG50**
Es exactamente la mitad del genoma, generalmente es igual o muy parecido al N50. Para una mejor explicación se deja un jemplo. 

![](Ejemplo NG50).

##### 7. ¿Cuál es el propósito de calcular estas estadísticas?.

Son metodos estadisticos que ayudan a un mejor entendimiento de la longitud y composición de un genoma en especial. 

##### 8. ¿Cuántos contigs conforman el genoma del Bonobo? ¿Cuál es el N50 y L50 del genoma?.

La cantidad de contigs del Bonobo son 121.356.-, su N50 es 66.676.- y el L50 es 11.048.-

![](N50, L50 .....)

##### 9. ¿Cuál es el largo total y porcentaje de GC del genoma del Bonobo? ¿Qué quieren decir o qué indican éstos valores?.

La longitud total del espacio de ensamblaje	es de 560,706,734.
El porcentage de GC es de  42.3185%.

De estos datos se puede inferir que la longitud total del espacio de ensamblaje es de 560,706,734 Pb y que de ese largo, el 42.3185% corresponden al enlace Guanina-Citocina.

##### 10. ¿Qué tipo de tecnología se uso para secuenciar el genoma del Bonobo? ¿Qué método (programa o algorítmo bioinformático) se usó para ensamblar el genoma?.

La tecnología usada para secuenciar el genoma del Bonobo fue de **"454 GS FLX; 454 GS FLX Titanium"**  y el método de montage utilizado fué **"Celera Assembler v. 5.4.3"** .
---

![](fin parte 1) 

---

### Parte 2: Predicción de genes

##### 11. Describe los resultados obtenidos. ¿Cuántos ORFs o genes encontró ORFfinder? ¿En qué hebra están codificados? ¿De qué largo son los ORFs predichos? ¿Algunos de ellos se sobreponen (fíjate en la posición de inicio [start] y término [stop])? [3]

Se obtuvieron como resultado un total de 7 ORF, 2 codificados en la primera hebra y los otros 5 en la primera, también se puede observar que estos se sobrponen entre si, como se muestra en la fifura más abajo, donde se detalla l longitud de cada uno, junto con su inicio y final respectivo.

![](ORF)

##### 12. ¿Qué tipo de programa es ORFfinder, Ab initio o por homología?.

ORFfinder es un progrma  "Ab initio" ya que no busca genes homologos con otras especies, si no que, busca puntos de inicio y termino de genes, nada más. 

##### 13. ¿A qué organismo pertenece la secuencia en cuestión?.

Es una Bacteria, la cuál causa enfermedades generalmente a niños menores de 5 años.

##### 14. ¿Qué gen(s) está(n) codificados en la secuencia?.

Está codificada la superfamilia de FdhE, las proteinas ribosomales Riml y la DNA polimerasa 3.

##### 15. Tomando en cuenta la evidencia que acumulaste usando ORFfinder y BLAST. ¿Cuál o cuáles ORFs predichos por ORFfinder dirías tú que son o es el correcto(s)?

Después de observar dichos datos, se pudo concluir que los ORF predichos correctamente son 3, los cuales son los ORF número 1, 4 y 5.

![]()




