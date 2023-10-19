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

{% include feature/button.html text="discursos" link="https://public.flourish.studio/visualisation/15217308/" color="success" centered=true %}

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



## About the About Page

We want to make engaging interpretive pages easier to create, so CollectionBuilder gives you tools to write *with* your collection content!

The template comes with a customizable "About" page layout designed for long form content with rich media embeds.
Content is written in [Markdown](https://guides.github.com/features/mastering-markdown/) and enhanced using "includes" that pull in collection content, external media, and [Bootstrap](https://getbootstrap.com/) features like cards and modals.
We hope this makes it easier for site builders to develop the collection AND add interesting and engaging contextual information. 

Each "include" file has several options, which are documented in the files themselves--copy the examples to see how it works with your content! 
In the demo below, we've given display widths of 25% and 50% to save space, but you can feature the entire image or document.

You can also see a page featuring [a bonanza of feature includes options](https://collectionbuilder.github.io/collectionbuilder-gh/feature_options.html) on our CollectionBuilder-GH demo site. 

{% include feature/button.html text="Feature *Includes* Bonanza page" link="https://collectionbuilder.github.io/collectionbuilder-gh/feature_options.html" color="primary" size="lg" centered=true %}

### Include Collection Items

The template provides includes to pull your collection objects and metadata into your interpretive page, allowing you to write with your materials directly embedded in the content.

#### Include an Image

- Image --> `{% raw %}{% include feature/image.html objectid="demo_001" width="75" %}{% endraw %}`

{% include feature/image.html objectid=imagesampleid width="75" %}

#### Include a PDF

- PDF -- > `{% raw %}{% include feature/pdf.html objectid="demo_002"  width="50" %}{% endraw %}`

{% include feature/pdf.html objectid=pdfsampleid width="50" %}

#### Include a Video

- Video: `{% raw %}{% include feature/video.html objectid="demo_004" %}{% endraw %}`

{% include feature/video.html objectid=videosampleid width="75" %}

#### Include an Audio File

- Audio: `{% raw %}{% include feature/audio.html objectid="demo_003" %}{% endraw %}`

{% include feature/audio.html objectid=audiosampleid  %}

### Include Bootstrap Features

The template also provides includes to make it easier to add [Bootstrap](https://getbootstrap.com/) components to your Markdown writing.
These features allow you to better organize and highlight your content.

#### Include a Card

- Card -- > `{% raw %}{% include feature/card.html header="This is a Card" text="The card features an image from the collection as a cap" objectid="demo004" width="25" centered=true %}{% endraw %}`

{% include feature/card.html header="This is a Card" text="The card features an image from the collection as a cap" objectid="demo_001" width="25" centered=true %}

#### Include a Button 

- Buttons -- > `{% raw %}{% include feature/button.html text="Button Link to Somewhere" link="https://collectionbuilder.github.io/" color="success" %}{% endraw %}`

{% include feature/button.html text="Button Link to Somewhere" link="https://collectionbuilder.github.io/" color="success" centered=true %}
  
#### Include an Alert

- Alerts -- > `{% raw %}{% include feature/alert.html text="this is an *alert* that 'warns' a user" color="warning" align="center" %}{% endraw %}`

{% include feature/alert.html text="This is an *alert* that 'warns' a user with centrally aligned text." color="warning" align="center"  %}

#### Include a Modal

- Modals -- > `{% raw %}{% include feature/modal.html button="This is a modal using a 'primary' colored button to invite clicking" title="when clicked:" text="A Modal will pop out a box with some more information" color="primary"  %}{% endraw %}`

{% include feature/modal.html button="This is a modal using a 'primary' colored button to invite clicking" title="When clicked:" text="A Modal will pop out a box with some more information" color="primary"  %} 
