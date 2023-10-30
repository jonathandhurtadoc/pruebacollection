{% assign imagesample = site.data[site.metadata] | where_exp: 'item','item.format contains "image"' | first %}
{% capture imagesampleid %}{{imagesample.objectid | default: "https://www.lib.uidaho.edu/collectionbuilder/demo-objects/mg101_b6_photographs_01.jpg"}}{% endcapture %}
{% assign pdfsample = site.data[site.metadata] | where_exp: 'item','item.format contains "pdf"' | first %}
{% capture pdfsampleid %}{{pdfsample.objectid | default: "https://digital.lib.uidaho.edu/utils/getfile/collection/ui_ep/id/21768/filename/uiext21768.pdf"}}{% endcapture %}
{% assign videosample = site.data[site.metadata] | where_exp: 'item','item.format contains "video"' | first %}
{% capture videosampleid %}{{videosample.objectid | default: "https://cdil.lib.uidaho.edu/storying-extinction/objects/trailcams/videos/ballcreek-cedarrub-birdonpath.mp4"}}{% endcapture %}
{% assign audiosample = site.data[site.metadata] | where_exp: 'item','item.format contains "audio"' | first %}
{% capture audiosampleid %}{{audiosample.objectid | default: "https://www.lib.uidaho.edu/digital/mp3s/Clouds.mp3"}}{% endcapture %}


## Tutorial 

Para iniciar la navegación por las representaciones, usted podrá tomar dos caminos: Categorías y Navegar. Ambas páginas de la web están pensadas para que comprenda la colección en su profundidad de 231 escenas. Primero, debe saber que cada escena tiene un título, una descripción, una casilla que nos dice a qué película corresponde, su director y el año de estreno, un discurso y su descripción, un tiempo de inicio y final, una etiqueta narrativa y una gestual; distancia entre los personajes; tipos de representación; fuente (source); tipo de archivo y formato del archivo. 

Bajo la pestaña “navegar” podrá encontrar la totalidad de la colección y buscar por orden aleatorio, título o película. Por ejemplo, puede escribir el nombre de una película y verá todas las escenas que hacen parte de ella. Si decide filtrar por título, puede intentar probar suerte y poner una palabra que crea que puede aparecer en la búsqueda. Como sugerencia le recomiendo buscar las palabras “paseo” o “amor”. Verá que, buscando por orden aleatorio, la búsqueda se hará por cualquier casilla de las que fueron descritas en el párrafo anterior. 
 
Por el contrario, bajo la pestaña “categorías”, usted encontrará una nube de palabras. Entre más grande sea la palabra significa que aparece más veces en las escenas. En esta nube aparecen mezclados los tipos de representación y los discursos. Al hacer click sobre una palabra, verá reflejada como resultado una lista de las escenas que contienen este discurso o ese tipo de representación. 


## Películas

En los siguientes botones podrá encontrar las películas que fueron analizadas para esta colección con el título de cada escena y su respectiva temporalidad, debe hacer click sobre el nombre de la película: 

{% include feature/button.html text="La tragedia del silencio" link="https://drive.google.com/file/d/1xXi59KpEh0CvucJKU54f3igCeCSw3KvH/view?usp=sharing" color="success" centered=true %}

{% include feature/button.html text="El amor, el deber y el crimen" link="https://drive.google.com/file/d/11pQUMnfk140pnpmR5gZ1pbJOmaPdKbig/view?usp=sharing" color="success" centered=true %}

{% include feature/button.html text="Aura o las violetas" link="https://drive.google.com/file/d/1m8UaVITGz6He97HLpwNlt0PkIoaYZQzb/view?usp=sharing" color="success" centered=true %}

{% include feature/button.html text="Madre" link="https://drive.google.com/file/d/1XsiQ9bezkRVVM5AVygUo1-m6rdvtV9GX/view?usp=sharing" color="success" centered=true %}

{% include feature/button.html text="Bajo el cielo antioqueño" link="https://drive.google.com/file/d/1T1b4Zm6wHxEPX91qG7tIahl_HayAoRlp/view?usp=sharing" color="success" centered=true %}

{% include feature/button.html text="Manizales City" link="https://drive.google.com/file/d/1NBG39SLQKbSRyMTsOIP5qLuwdKLeXZL2/view?usp=sharing" color="success" centered=true %}

{% include feature/button.html text="Garras de oro" link="https://drive.google.com/file/d/1Dde4CARSizeGZ-5cK2iP9a_Ldrnn6uOq/view?usp=sharing" color="success" centered=true %}

{% include feature/button.html text="Como los muertos" link="https://drive.google.com/file/d/18ptw_9C0kAPXWiZ98D9hxmU2VSyB-aft/view?usp=sharing" color="success" centered=true %}

{% include feature/button.html text="Alma provinciana" link="https://drive.google.com/file/d/1uXEvUMAvu3w0wzVoG-NI1cwBBmcVpl0M/view?usp=sharing" color="success" centered=true %}

{% include feature/alert.html text="Nota: Las escenas que aparecen en las tablas con el nombre de 'créditos' o 'fin' no fueron incluidas en la colección. " color="warning" align="center" %}


#### Tipo de representación: 
Las representaciones, es decir las interacciones entre personajes en la pantalla, se catalogan en relaciones binarias entre dominados y dominantes. En la escena se pueden presentar relaciones entre iguales o desiguales, esto quiere decir que en algunas escenas existen relaciones entre hombres únicamente o sólo entre mujeres, estas son denominadas “iguales”.  Pero, si la interacción se da entre un hombre y una mujer, será una representación desigual ¿qué sucede si en la misma escena se identifican relaciones entre iguales y desiguales? Se le asignó según la relación más relevante desarrollada en la escena en términos de las relaciones de poder y que represente un insumo para los ejercicios analíticos.

Las representaciones de podrá encontrar en este ejercicio son:

##### Desiguales

Hombre/mujer

Rico/pobre

Adulto/niño

Padre/hija

##### Iguales

Hombre/hombre

Rico/rico

Pobre/pobre

Mujer/mujer


#### Discursos:
Los discursos son categorías analíticas emergentes que aparecen luego de realizar un ejercicio de descripción con todas las partes anteriores. Según esta información, fueron asignados discursos que surgían para entender la profundidad de las escenas y lo que mostraban de la identidad colombiana. Es decir, un discurso es una abstracción de lo que aparece en la pantalla, es un análisis que comprende el sentido identitario de esas interacciones en pantalla y sus posibles relaciones con otras escenas. En total existen 30 discursos que condensan los principales valores de la identidad colombiana, por lo menos, de los que las películas representaron. Para entender visualmente la magnitud de la aparición de los discursos puede consultar la siguiente visualización: 

{% include feature/button.html text="Discursos" link="https://public.flourish.studio/visualisation/15217308/" color="success" centered=true %}

#### Etiqueta narrativa: 
Esta etiqueta es una simplificación en una palabra de lo que pasa en la escena. Es decir, si en la escena hay una muestra de fe religiosa a través de iglesias o rezos, la palabra será religiosidad. Esto sucede con todas las escenas y permite comprender a través de las visualizaciones ancladas las principales etiquetas y patrones que aparecen en las películas. 

{% include feature/button.html text="Visualización tag_narrativa" link="https://public.flourish.studio/visualisation/15412296/" color="success" centered=true %}

#### Etiqueta gestual: 
Esta etiqueta es una simplificación en una palabra de lo que lo que los gestos de los personajes simbolizan. Si los gestos de los personajes y la narración indican que están preocupados, la palabra será preocupación. Podrá identificar las principales etiquetas a través de las visualizaciones ancladas. 

{% include feature/button.html text="Visualización tag_gestual" link="https://public.flourish.studio/visualisation/15413250/" color="success" centered=true %}

#### Proxemia (distancia entre personajes): 
La proxemia mide la distancia entre los personajes. Esto es importante porque permite identificar cómo interactúan los personajes entre ellos. Por ejemplo, a través de la visualización anclada podemos entender que los personajes ricos suelen estar cerca entre ellos, pero los ricos suelen estar a distancia media de los pobres.

{% include feature/button.html text="Visualización proxemia" link="https://public.flourish.studio/visualisation/15413327/" color="success" centered=true %}

#### Descripción
La información descrita en la casilla de descripción de la escena se realizó manualmente. Es decir, el investigador describió cada escena pensando en los procesos de representación dentro de las escenas, por tanto, aunque tienen tiene una descripción narrativa, esta está concentrada en cómo representan a la identidad y son el principal insumo de los análisis discursivos. 


#### DATA

Si usted desea descargar los datos de esta colección, podrá hacerlo presionando en la pestaña “Data” dónde encontrará la opción para descargar los datos completos. Así mismo, en la pestaña  “Inicio” podrá encontrar la opción de descargar los datos específicos en diversos formatos. Esto aparece cuando navega al fondo de la pestaña “Inicio” y podrá descargar datos en CSV, JSON y el CODE que permitió desarrollar esta colección web. 



