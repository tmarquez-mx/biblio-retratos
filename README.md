# Biblio-retratos. Visualizando identidades académicas 
*Una reinterpretación de Zotero como dispositivo para documentar identidades académicas desde la literacidad*
                         
## Descripción narrativa
Biblio-retratos es una aplicación web que permite a usuarios de Zotero (un manejador bibliográfico de código abierto de uso extendido en la comunidad académica alrededor del mundo), obtener diferentes analíticas y visualizaciones sobre sus prácticas de literacidad. Esto es, sobre sus habilidades, trabajo y trayectoria en la recolección y procesamiento de fuentes bibliográficas. Todas ellas actividades que además de consumir gran cantidad de tiempo a lo largo de una carrera académica, son prácticas que reflejan pertenencias, disposiciones y fronteras teórico-metodológicas, conformando parte importante de una identidad académica. 
Biblo-retratos (o Zotero-BR) es un proyecto de Humanidades Digitales. En 2023 recibió financiamiento la División de Investigación y Posgrado de la Universidad Iberoamericana, Ciudad de México. 

## Descripción operativa

- Biblio-retratos (BR) comunica al usuario con su base de datos bibliográfica alojada por defecto en el servidor de Zotero. Si la base se encuentra en otro servidor, la comunicación no será posible. 
- BR solicitará durante el resgitro **por única vez**  el *ID User* y el *Private Key* de la cuenta de usuario de Zotero (Ver Instrucciones).
- Las consultas se realizan por tipo de elemento (i.e book. book section, jorunal, etc.)  o por subcolecciones. También puede consultarse a lo largo de toda la base si no selecciona ningún tipo de elemento ni subcolección.
- Los campos que se puede solicitar visualizar son: autor, lugar de edición, año de edición, año de adición, palabra clave y tipo de elemento. Nota: Debido a que BR obtiene la información de la base de datos remota loss resultados de las consultas por palabras clave (tags), pueden no corresponder a las palabra clave que el usuario visualiza en su aplicación Zotero de escritorio. Para verificar y depurar sus palabras clave (Tags), dirigirse a la versión web de Zotero.
- Las consultas puede limitarse temporalmente. Las opcioes son: anual (cada año de registro desde el inicio de la base), por lustros, por décadas, cada X cantidad de años, o en un rango de años de interés. De no especificar ninguna opción, la consulta se hará en todos los registros.

## Palabras clave
identidades académicas | analítica visual | literacidad | Humanidades Digitales |Zotero


# Funciones habilitadas (tasks)
Fase 1 Concluida y operativa. No requiere instalación. Operación vía web.
Actualmente en beta pública (03 2024)

- Comunicación con Zotero
- Consultas
- Despliegue de información
- Exportación .CVS
- Visualización
- Exportación .PNG

# Funciones futuras (tasks)

Fase 2
- Carga de imagen o fotografia (retrato)
- Galería de layouts
- Generación de biblio-retrato
- Exportación

# Seguridad
- Biblio-retratos no almacena contenido proveniente de la base de datos del usuario en Zotero. Solo facilita la comunicación entre ambos. 
- Los datos de correo electrónico, Zotero User Id y Zotero Private Key está protegidos por ley. Ver [Aviso de privacidad](https://ibero.mx/sites/all/themes/ibero/descargables/avisos-legales/2024/estudiantes-ingles.pdf)

# Créditos
[Teresa Márquez](https://socialesypoliticas.ibero.mx/TeresaMarquez/), investigadora / [Xavier Tortolero](https://www.gtsf.com.mx/), desarrollador.

# Historia #

### 2023 : (re) diseño y desarrollo ###



| <!-- -->      | <!-- -->        | 
|:-------------|:---------------|
| Abril         | Aprobación financimiento  DINV, Ibero.       | 
| Mayo         |  Formación de equipo de trabajo     |
| Junio         | Análisis y rediseño: de plugin a aplicación web. Coordinaciones con Cómputo Académico  | 
| Julio        | Catálogo de funciones. Gestiones logísticas y financieras | 
| Agosto         | Pruebas de comunicación con base de datos   | 
| Septiembre        | Diseño y desarrolo de consultas | 
| Octubre        | Pruebas, evaluación y aprobación del módulo consultas| 
| Noviembre        | Diseño y desarrollo de visualizaciones | 
| Diciembre        | Pruebas, evaluación y aprobación del módulo visualización| 

### 2024 : beta y producción ###

| <!-- -->      | <!-- -->        | 
|:-------------|:---------------|
| Enero       | Cierre de primera fase, entrega y presentación pública preliminar | 
| Febrero        | Gestión de servidor para beta pública. Evaluación de Dpto. de Informática. Adecuaciones de seguridad |
| Marzo        | Lanzamiento beta pública. Divulgación en Forum Zotero y redes sociales (en preparación| 
| Abril       | Presentacioens pública (en preparación)  | 
| Mayo        |Diseño y registro de marca (pendiente) | 
| Junio        |Sistematización de comentarios y evaluaciones (pendiente) | 
| Julio       | Propuestas para financiamiento de mejores y etapa 2 (pendiente)  | 
| Agosto       |Artículo académico  | 
| Septiembre   | ¿RIP? | 






# Diseño y registro de imagen de marca
En proceso

# Agradecimientos
- Dirección de Investigación y Posgrado, Ibero
- Cómputo Académico, Ibero
- Andrés Tortolero, Ingeniería de Datos, Ibero
- Jorge Angel González, INIAT, Ibero
- Informática, Ibero
- Zotero (forever! We ❤️ Z)




<p align="center">
  <img width="484" alt="Captura de Pantalla 2022-06-17 a la(s) 1 39 34" src="https://user-images.githubusercontent.com/69394840/174241124-ad4216f9-5db3-4d9f-9353-782ed7f856ed.png"> 

[^1]: Herramientas como Paper Machine y Zotero Voyant Export no han sido actualizadas a las últimas versiones de Zotero pero sus códigos están disponibles en Github. https://github.com/papermachines/papermachines; https://github.com/corajr/zotero-voyant-export/

## Inspiración y motivación

  Zotero / visualización   /  identidades académicas  (pendiente de desarrollo)
  
  ## Objetivo general
Posibilitar la autogeneración de visualizaciones --mediante desarrollo de código-- de las analíticas sobre las prácticas personales de lectura académica como componentes de la identidad del investigador universitario.
## Objetivos específicos
1. Explorar conceptualmente la configuración de identidades académicas digitales en relación a las métricas y visualizaciones de prácticas académicas de lectura
2. Estudiar la estructura algorítmica de Zotero
2. Desarrollar y/o actualizar plugins de minería de textos y de visualización para el gestor bibliográfico Zotero
3. Escribir código  para la generación de imágenes combinadas y superpuestas tipo retrato en plataforma web

## Antecedentes
El trabajo de investigación realizado por los académicos en las universidades, es evaluado en términos de productividad científica que se expresa en indicadores y métricas. Se trata de un tema en pleno debate donde aparecen por un lado las grandes editoriales científicas que buscan imponer el factor de impacto como medida hegemónica y, por el otro lado, se encuentran diferentes grupos más académicos (i.e. DORA, la propia UNESCO y Folec-CLACSO en Latinoamérica) que defienden métricas responsables que atiendan a la calidad de los resultados de la investigación y no al prestigio de las revistas donde son publicados. Una abundante producción de gráficas y visualizaciones resultan del choque de estas dos posiciones que respaldan en estudios y análisis bibliométricos sus argumentos. En esa guerra de imágenes cientificas, el investigador de a pie debe decidir quién es y cuál es en última instancia su trabajo. 

Tales datos, métricas y visualizaciones integran el repertorio de representaciones mediadas por código con que los investigadores conforman una huella digital con la que son rastreados por los motores de extracción de datos de sus universidades e instituciones, agencias financiadoras, instancias gubernamentales y las editoriales científicas dominantes. Los investigadores contrarrestan estas narrativas evaluadoras con más presencia y "egosurfing" (Feher, 2021, p. 2) en las redes sociales, tanto académicas como no académicas. 

Se generan entonces auto-narrativas en resistencia donde también importa lo que los investigadores eligen leer para nutrir su trabajo a la vez que se posicionan en sus áreas de estudio y respecto a sus colegas. Además de su importancia para la propia investigación, la lectura de fuentes constituye una *práctica académica de literacidad* y, como tal, influye en la conformación de la identidad académica del investigador(a).(Ver Calle-Arango et al., 2021; Kirka, 2021).

Biblio-retratos explorará la conformación de las identidades académicas-digitales a partir de código y visualizaciones digitales. Esto es, de las métricas y analíticas producidas por el trabajo de lectura del investigador(a).A diferencia de visualizaciones hechas desde la vigilancia evaluativa, o por otros investigadores que toman la producción de sus colegas como objetos de estudio, este proyecto se enfoca en narrativas visuales que están totalmente bajo control del investigador y que él mismo generará. 

Para identificar el trabajo de lectura se tomarán las bases bibliográficas donde el investigador gestiona sus fuentes. Concretamente, se trabajará con Zotero por ser un programa de código abierto y de amplia difusión en la comunidad científica (actualmente se encuentra traducido a 57 idiomas). Se desarrollarán o actualizarán plugins para Zotero que permitirán construir analíticas de las fuentes registradas y de sus usos, así como generar visualizaciones con esos datos. Tales imágenes se superpondrán con una fotografía del investigador dando como resultado un "biblio-retrato" que reflejará cómo su presentación como investigador está conformada -al menos en parte- por la relación que guarda con lo que lee.

## Justificación
El tema de las identidades académicas ha sido escasamente estudiado en la Región Latinoamericana. Los pocos estudios realizados en nuestros países abordan poblaciones de estudiantes de posgrado o investigadores jóvenes en relación a la escritura, hay muy pocos estudios de prácticas académicas de lectura en investigadores en diferentes estadios de su trayectoria profesional. Por otra parte, los estudios sobre identidad digital, de la que se viene hablando hace 20 años, recién empiezan a cobrar notoriedad debido a temas como seguridad de datos personales y a la fuerte presencia de  narrativas personales, selfies y storytelligs en el mundo online, en particular, en las redes sociales. 

El trabajo de lectura académica es generativo de procesos de investigación por lo que ocupa un lugar central en el trabajo de producción de conocimiento.
Por tanto, la huella que produce es constitutiva de una narrativa identitaria pendiente de estudiarse. 

Por otro lado, al orientar el proyecto a la producción de imágenes (los biblio-retratos) se espera tener un impacto importante a través de un artefacto estético que genere cuestionamientos y reflexión en los jóvenes estudiantes sobre las herramientas que tienen a su alcance y sus posibilidades operativas y narrativas (nos hacen como investigadores pero también nos narran). También interesa mostrar que el conocimiento no solo es creado sino que tiene un correlato visual y sensorial que la ciencia debe asumir.  

## Aportes
1. Estímulo a los estudiantes a sistematizar su información bibliográfica a través de software
2. Incentivo a los profesores e investigadores a monitorear y evaluar sus fuentes de lectura
3. Formación de un grupo de trabajo interdisciplinario
4. Desarrollo de metodologías para la documentación de procesos de trabajo y su apertura pública
5. Incursión en el terreno de las Humanidades Digitales y en los principios FAIR de ciencia abierta
6. Desarrollo de herramientas para la visualización de corpus bibliográficos que se abrirán a una comunudad global de usuarios de Zotero
7. Reflexión sobre cómo los datos y la experiencia de consulta de fuentes nos constituyen (identificación y análisis de patrones y trayectorias)
8. Desarrollo de código en el terreno de la IA para la generación de imágenes a partir de análiticas
9. Desarrollo de código para la superposición y composición de imágenes agregadas vía web.
10. Sensibilización sobre el tema de las identidades académicas y el papel político de las visualizaciones y métricas.
11. Tiene el potencial de proponer un indicador más en la productividad científica incluyendo la etapa previa y ardua de revisión y lectura de fuentes.


## Estrategia de documentacion
El proyecto se documentará a través de:
1. Github para el aseguramiento de versiones y apertura de código; 
2. OSF Open Science Framework, OSF (https://osf.io) siguiendo la Guía de buenas prácticas para la elaboración y evaluación de proyectos de HD y Checklist de la Red HD. http://humanidadesdigitales.net/guia-de-buenas-practicas-para-la-elaboracion-y-evaluacion-de-proyectos-de-humanidades-digitales-y-checklist/
3. Los principios TIER para la reproducibilidad  https://www.projecttier.org/  
4. Los principios FAIR https://www.go-fair.org/fair-principles/ para la gestión de datos.
5. Publicación de pre-prints en Zenodo y Open Science Framework (OSF).
## Revisión y evaluación académica
Se buscará financiamiento académico por evaluación (DINV/Ibero). Se espera invitar a colegas pertenecientes a la RedHD-Ibero a que conformen un comité de acompañamiento ético-académico del proyecto. De ser aprobado para su financiación, la DINV/Ibero realiza también un seguimiento de los objetivos y metodología. 
Además de la documentación en Github donde también se compartirá la metodología y los códigos desarrollados, habrá un sitio web desde donde se podrá hacer uso en línea de las aplicaciones desarrolladas. Se espera también desarrollar plugins para Zotero que estarán disponibles en la página de recursos de esa aplicación. De esta manera, los componentes del proyecto al estar abiertos al uso de una amplia comunidad académica, estará en permanente evaluación de pares y no-pares (ciencia pública).
## Estrategia de sostenibilidad
Se trata de un punto crítico pues el biblio-retrato depende de las actualizaciones de Zotero que exigirá revisiones semestrales de los plugins que se desarrollen. Al abrir el código, se espera que de no contar con recursos para el mantenimiento, la comunidad de usuarios alrededor del mundo pueda hacerlo.
##  Experticias necesarias:
1.	Conocimiento del código abierto de Zotero y programación en JavaScript y SQLite 
2.	Manipulación de imagen digital y programación en HTML y Python
## Equipo
1. Teresa Marquez. Responsable
2. UnX programadorX. 
3. UnX diseñadorX Transmedia. 
## Influencias de proyectos HD
Proyectos en HD: 
1. “Intercambios oceánicos” https://oceanicexchanges.org/mx/  En la lectura del proyecto, se encontró la realización de un taller donde se generaron mapas a partir de bases de Zotero previamente depuradas con OpenRefine. Soy una usuario frecuente y entusiasta de Zotero y este proyecto me puso en la ruta de pensar en visualizaciones a partir del contenido de las bases bibliográficas y del uso que se les da, tales como nubes de frecuencias de autores más registrados, procedencia editorial de las fuentes, etiquetas más frecuentes, frecuencia de años de edición, etc.
2. “I ♥ E-Poetry” https://iloveepoetry.org/  Es un proyecto muy estético que funde el lenguaje de la poesía con las capacidades evocadoras de la manipulación visual de textos digitales. Esto me llevó a pensar en las posibilidades expresivas de juntar datos provenientes del mundo no-digital con el propiamente digital y buscar no solo lo que te permite ver el conocimiento, sino cómo se ve él mismo. 

Otros proyectos No-HD que exploran computacionalmente la generación de imágenes a partir de textos:

"Imagen" https://imagen.research.google/
Imagen es un modelo de difusión de texto a imagen con un alto grado de fotorrealismo y un profundo nivel de comprensión del lenguaje. "Imagen" se basa en la potencia de los grandes modelos lingüísticos transformadores para la comprensión del texto y se apoya en la fuerza de los modelos de difusión para la generación de imágenes de alta fidelidad. Su principal descubrimiento es que los grandes modelos lingüísticos genéricos (por ejemplo, T5), preentrenados en corpus de sólo texto, son sorprendentemente eficaces en la codificación de texto para la síntesis de imágenes: el aumento del tamaño del modelo lingüístico en Imagen aumenta tanto la fidelidad de la muestra como la alineación imagen-texto mucho más que el aumento del tamaño del modelo de difusión de imágenes. 
 
"Identity Relationship Visualization" https://www.forgerock.com/platform/identity-management/identity-visualization
Aplicación comercial que permite visualizar las relaciones de identidad de cualquier usuario, dispositivo o cosa. También incorporar informes creados a partir de la plataforma de visualización de datos de código abierto Kibana, directamente en la consola del administrador y profundizar en cada nodo u objeto para obtener información más detallada.

"Text-to-Image Generation"  https://vision-explorer.allenai.org/text_to_image_generation
 La generación de texto a imagen es una aplicación web que de genera una imagen condicionada por el texto de entrada.
 
"Visualizing Identity" (2019 - WIP) http://www.chrissybrimmage.com/visualizing-identity  
Un proyecto de aprendizaje automático de texto a imagen que intenta salvar la brecha de percepción entre las identidades sociales a través de visuales creados por la IA, formados por datos de identidad. Estos elementos visuales servirán para representar las percepciones aisladas de la experiencia de los individuos y como referencias para comprender mejor la formación de la identidad, cómo la identidad influye en la experiencia y cómo estas experiencias se comparan y contrastan entre los grupos sociales.

## Herramientas
Biblio-retrato, deberá hacer uso de Zotero y de OpenRefine, pues el primero contiene el corpus que se usará y el segundo es una herramienta para depurar los datos, por ello no se considerarán aquí como herramientas por separado.

Consideraré como herramientas, aquellas que traduzcan o transformen datos, como las aplicaciones de visualización siguientes

Voyant Tools, recibirá los textos desde un .CSV para generar las analíticas y las visualizaciones. Extisten ya dos plugins sin mantenimiento (Ver nota al pie 2). La tarea es actualizarlo a la versión vigente de Zotero.

Palladio, es otra herramienta de visualización de archivos .CSV que complementaria la galería de Voyant permitiendo mapear y conectar dos datos formando conjuntos.

La tercera  herramienta o código, deberá permitir recibir a través de una página web las visualizaciones de los plugins de Voyant y Palladio, así como las fotos que suba el usuario y realizar la superposición de ambas imágenes a través de IA. Una opción es trabajar sobre Pine Tools, una herramienta online gratuita. Habrá una galería con opciones preestablecidas de acuerdo al gráfico (nube, mapa, barras, etc.) y al encuadre de la foto. Finalmente, la aplicación web deberá devolver el biblio-retrato para ser bajado por el usuario.

Ningún elemento ni objeto digital (i.e. archivos .csv; .svg; .jpg; .png, etc.) se conservará en servidores por lo que los datos del usuario estarán plenamente seguros y libres de todo uso o almacenamiento indebido.

## Procedimiento del usuario
1. Para obtener un biblio-retrato, el investigador deberá tener sus fuentes de consulta bibliográfica en Zotero lo más depurada posible
2. Deberá instalar el o los plugins que desarrollaremos para visualizar analíticas como: frecuencia de autores, frecuencia de años publicación, geolocalización de los lugares de publicación; frecuencia de los idiomas de la bibliografía; fuentes más consultadas, etc.
3. Una vez obtenida la visualización deseada, deberá subirla a la página web de biblio-retratos junto con una foto tipo oficial con el primer plano de su rostro
4. Deberá elegir de una galería proporcionada el tipo de arreglo o composición de la superposición de su foto con la visual de su base de Zotero
5. Se generará su biblio-retrato que podrá bajar en diferentes resoluciones y formatos
6. El sistema no guardará los objetos digitales subidos y no será necesario registrarse en la página.


## Recursos en revisión (en proceso)
1. https://vispo.com/index.html  (animación)
2. https://www.usandizaga.com/design/pinacogramas-y-caligramas-retratos-con-letras/![imagen](https://user-images.githubusercontent.com/69394840/173201608-666907ba-def1-455e-8030-35f75e47067d.png) (retratos con letras)
3. https://wordart.com/  (Online cloud creator)
4. https://openrefine.org
5. https://voyant-tools.org/?corpus=451e87665270278b3512bc72bbe3472c&panels=cirrus,reader,trends,summary
6. http://musingsaboutlibrarianship.blogspot.com/2019/09/the-rise-of-new-citation-indexes-and_5.html
7.https://github.com/papermachines/papermachines
8. https://www.vosviewer.com
9. https://github.com/corajr/zotero-voyant-export/ 


## Acceso y sustentabilidad
La aplicacación estará alojada en un sitio institucional y los datos que se reciban a través del sistema (como fotografías personales y analíticas), no se conservarán como parte de la protección de los datos personales.
## Productos esperables
Al ser el primer proyecto de HD que se realizará en la Ibero, herramientas de software que se desarrollen (i.e. plugins para Zotero), sinergias (trabajo colaborativo interdiciplinario), infraestructura, metodologías y procesos (incluidos los de documentación) serán en sí mismos productos de la investigación. 
Como resultado final se pueden considerar participaciones en reuniones académicas o congresos; al menos cuatro artículos académicos (uno por investigador participante y otro elaborado por los estudiantes-asistentes) y una exposición multimedia donde se mostrarán fotos impresas y en pantalla, así como animaciones del proceso de trabajo. La página web de biblio-retratos es el producto principal y contendrá además toda la documentación del proyecto lo que en sí mismo generará aprendizaje y antecedentes para buenas prácticas de la investigación abierta en la Ibero. 
## Licencia
<p xmlns:cc="http://creativecommons.org/ns#" >This work is licensed under <a href="http://creativecommons.org/licenses/by-nc-sa/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">CC BY-NC-SA 4.0<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/nc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/sa.svg?ref=chooser-v1"></a></p> 
<img width="965" alt="Captura de Pantalla 2022-06-11 a la(s) 21 00 29" src="https://user-images.githubusercontent.com/69394840/173211143-62becfaf-af07-4c53-9b94-302b48ec98c8.png">

## Procedimiento para maqueta
1. Limpieza de la base Zotero con OpenRefine 
2. Separación del corpus en las columnas de un CSV utilizando delimitadores.
3. Extracción de columnas: título; autor; fechas; lugar de edición; subcolección. Separación del campo autor para extraer solo apellidos.
4. Generar en Palladio y Voyant visualizaciones a partir del archivos .CSV depurado
5. Remover fondo de las imágenes .SVG  con removeBG
6. Capturar foto retratos
7. Fundir ambas imágenes

## Maqueta 
<p align="center">
<img width="449" alt="Captura de Pantalla 2022-06-20 a la(s) 23 13 08" src="https://user-images.githubusercontent.com/69394840/174714753-93a6c711-81e6-40c6-9ca2-c9819b6ada3f.png">

![base_zotero](https://user-images.githubusercontent.com/69394840/204355163-9eca3b0c-bf36-40ec-92a2-3690b6778c3a.PNG)

![base_zotero_excel](https://user-images.githubusercontent.com/69394840/204355176-a632ab7b-7e44-4e98-a006-2256eb3223de.PNG)


![base_zotero_voyant](https://user-images.githubusercontent.com/69394840/204355183-2c901045-9248-4ee7-a27c-c6d52c3d47a6.PNG)

![2](https://user-images.githubusercontent.com/69394840/204355731-b90fd6f9-13b8-4d6d-b4d3-771b77d5d399.png)

![4](https://user-images.githubusercontent.com/69394840/204355997-33b9b1ec-a93f-4320-a764-e5ff9adae063.png)

![3](https://user-images.githubusercontent.com/69394840/204355769-55451777-20db-4085-b60a-550c843e0001.png)

![Biblio-retrato_TM1](https://user-images.githubusercontent.com/69394840/204355791-69716719-b9aa-4a52-89b4-694ba1694eb2.jpg)


## Fuentes relevantes identificadas
Allen, W. L. (2021). The conventions and politics of migration data visualizations. New Media & Society, 14614448211019300. https://doi.org/10.1177/14614448211019300

Amoore, L., & Piotukh, V. (Eds.). (2015). Algorithmic Life: Calculative Devices in the Age of Big Data. https://s3.amazonaws.com/arena-attachments/826659/e79de8190a31b0acd41b20f8e137fd0e.pdf

Bucchi, M., & Saracino, B. (2016). “Visual Science Literacy”: Images and Public Understanding of Science in the Digital Age. Science Communication, 38(6), 812-819. https://doi.org/10.1177/1075547016677833

Calle-Arango, L., Reyes, N. Á., & Meneses, A. (2021). Construcción y transformaciones de las identidades académicas de estudiantes doctorales mediante la citación*. Íkala, Revista de Lenguaje y Cultura, 26(2), 331-346.

Castelló, M., McAlpine, L., Sala-Bubaré, A., Inouye, K., & Skakni, I. (2021). What perspectives underlie ‘researcher identity’? A review of two decades of empirical studies. Higher Education, 81(3), 567-590. https://doi.org/10.1007/s10734-020-00557-8

D’Ignazio, C., & Klein, L. F. (s. f.). Feminist Data Visualization. 

D’Ignazio, C., & Klein, L. F. (2020). Data Feminism. MIT Press.

Dörk, M., Feng, P., Collins, C., & Carpendale, S. (2013). Critical InfoVis: Exploring the politics of visualization. CHI ’13 Extended Abstracts on Human Factors in Computing Systems on - CHI EA ’13, 2189. https://doi.org/10.1145/2468356.2468739

Dundalk Institute of Technology, Maguire, M., Reynolds, A. E., Dundalk Institute of Technology, Delahunt, B., & Dundalk Institute of Technology. (2020). Reading to Be: The role of academic reading in emergent academic and professional student identities. Journal of University Teaching and Learning Practice, 17(2), 58-70. https://doi.org/10.53761/1.17.2.5

Engebretsen, M., & Kennedy, H. (Eds.). (2020). Data Visualization in Society. Amsterdam University Press. https://doi.org/10.5117/9789463722902

Fardella Cisternas, C., García-Meneses, J., Soto Roy, A., & Corvalán-Navia, A. (2021). Exacerbados. Identidades académicas y la transformación de la educación superior chilena. Quaderns de Psicologia, 23(2), e1602. https://doi.org/10.5565/rev/qpsicologia.1602

Feher, K. (2021). Digital identity and the online self: Footprint strategies – An exploratory and comparative research study. Journal of Information Science, 47(2), 192-205. https://doi.org/10.1177/0165551519879702

Fernández-Marcial, V., & González-Solar, L. (2017). Servicios a la investigación en la biblioteca universitaria: Gestión de la identidad digital. LIS Scholarship Archive. https://doi.org/10.31229/osf.io/975e3

García-Peñalvo, F. J. (2018). Identidad digital científica. https://doi.org/10.5281/zenodo.1413335

García-Peñalvo, F. J., Fidalgo-Blanco, Á., Sein-Echaluce, M. L., & Tricas García, F. (2019). La Presencia del Investigador en el Ecosistema Digital de la Ciencia Abierta. Aprendizaje, Innovación y Cooperación como impulsores del cambio metodológico, 498-503. https://doi.org/10.26754/CINAIC.2019.0101

Gómez, S. R. (2021). Signos visuales a escala humana: Una clasificación de métodos de visualización de datos y una reflexión sobre sus alcances para la investigación humanística. Revista de Humanidades Digitales, 6, 64-84. https://doi.org/10.5944/rhd.vol.6.2021.30734

Guzmán-Valenzuela, C., & Martínez Larraín, M. (2016). Tensiones en la construcción de identidades académicas en una universidad chilena. Estudios pedagógicos (Valdivia), 42(3), 191-206. https://doi.org/10.4067/S0718-07052016000400010

Hullman, J., & Diakopoulos, N. (2011). Visualization Rhetoric: Framing Effects in Narrative Visualization. IEEE Transactions on Visualization and Computer Graphics, 17(12), 2231-2240. https://doi.org/10.1109/TVCG.2011.255

Identity Visualization | ForgeRock Identity Platform. (s. f.-a). Recuperado 16 de junio de 2022, de https://www.forgerock.com/platform/identity-management/identity-visualization

Identity Visualization | ForgeRock Identity Platform. (s. f.-b). Recuperado 16 de junio de 2022, de https://www.forgerock.com/platform/identity-management/identity-visualization

Imagen: Text-to-Image Diffusion Models. (s. f.). Recuperado 16 de junio de 2022, de https://imagen.research.google/

Ivanič, R. (1998). Writing and Identity: The discoursal construction of identity in academic writing. John Benjamins. https://doi.org/10.1075/swll.5

Kennedy, H., & Hill, R. L. (2017). The Pleasure and Pain of Visualizing Data in Times of Data Power. Television & New Media, 18(8), 769-782. https://doi.org/10.1177/1527476416667823

Kirca, H. S., & Glover, P. (2021). We are what we read: Reading identity of university students of English language teaching. RumeliDE Dil ve Edebiyat Araştırmaları Dergisi. https://doi.org/10.29000/rumelide.997589

Kohli, M. (2011). Transformation from Identity Stone Age to Digital Identity. https://doi.org/10.5121/ijnsa.2011.3309

Lectura y Escritura para aprender, crecer y transformar: 25 años de la Cátedra UNESCO. (2020). https://www.estudiosdelaescritura.org/uploads/4/7/8/1/47810247/mart%C3%ADnez_sol%C3%ADs_et_al_2020_lectura_y_escritura_para_aprender_crecer_y_transformar.pdf

Lupton, D. (2016). The Quantified Self. John Wiley & Sons.

Nash, K., Trott, V., & Allen, W. (2022). The politics of data visualisation and policy making. Convergence, 28(1), 3-12. https://doi.org/10.1177/13548565221079156

Paloma, M.-A. (2019, diciembre 9). ORCID and your digital identity as a researcher. https://doi.org/10.5281/zenodo.3567268
Renteria, A. L. (2016). Identidades académicas en cambio en el seno de la universidad multilingüe. Papeles del CEIC, 163-163. https://doi.org/10.1387/pceic.15978

Saharia, C., Chan, W., Saxena, S., Li, L., Whang, J., Denton, E., Ghasemipour, S. K. S., Ayan, B. K., Mahdavi, S. S., Lopes, R. G., Salimans, T., Ho, J., Fleet, D. J., & Norouzi, M. (2022). Photorealistic Text-to-Image Diffusion Models with Deep Language Understanding (arXiv:2205.11487). arXiv. https://doi.org/10.48550/arXiv.2205.11487

Taylor, L. (2016). The ethics of big data as a public good: Which public? Whose good? Philosophical Transactions of the Royal Society A: Mathematical, Physical and Engineering Sciences, 374(2083), 20160126. https://doi.org/10.1098/rsta.2016.0126

Text-to-Image Generation. (s. f.). Recuperado 16 de junio de 2022, de https://vision-explorer.allenai.org/text_to_image_generation

Valle, C. S. D. (s. f.). RETOS Y DESAFÍOS DE LOS INVESTIGADORES DE LA FORMACIÓN DE INVESTIGADORES EN EDUCACIÓN. 30.

Varios, E. E. P., S. L. ,Antoni Gutiérrez-Rubí. (s. f.). Infografías, visualizaciones y política. Micropolítica. Recuperado 16 de junio de 2022, de https://blogs.elpais.com/micropolitica/2012/04/infografias-visualizaciones-y-politica.html

Vélez-Cuartas, G., Suárez-Tamayo, M., Jaramillo-Guevara, L., & Gutiérrez, G. (2021). Nuevo modelo de métricas responsables para medir el desempeño de revistas científicas en la construcción de comunidad: El caso de Redes. Redes. Revista hispana para el análisis de redes sociales, 32(2), 110-152. https://doi.org/10.5565/rev/redes.919

Viewpoint: The Politics of Data Visualisation. (2015, agosto 3). Discover Society. https://archive.discoversociety.org/2015/08/03/viewpoint-the-politics-of-data-visualisation/

Visualize your Identity! (s. f.). Google Arts & Culture. Recuperado 16 de junio de 2022, de https://artsandculture.google.com/asset/visualize-your-identity/zwEw6Mt80lL91w

Visualizing Identity. (s. f.). Chrissy Brimmage. Recuperado 16 de junio de 2022, de http://www.chrissybrimmage.com/visualizing-identity

Xiong, C., Shapiro, J., Hullman, J., & Franconeri, S. (2020). Illusion of Causality in Visualized Data. IEEE Transactions on Visualization and Computer Graphics, 26(1), 853-862. https://doi.org/10.1109/TVCG.2019.2934399

Xu, T., Zhang, P., Huang, Q., Zhang, H., Gan, Z., Huang, X., & He, X. (2018). AttnGAN: Fine-Grained Text to Image Generation with Attentional Generative Adversarial Networks. 2018 IEEE/CVF Conference on Computer Vision and Pattern Recognition, 1316-1324. https://doi.org/10.1109/CVPR.2018.00143

Zakraoui, J., Saleh, M., Al-Maadeed, S., & Jaam, J. M. (2021). Improving text-to-image generation with object layout guidance. Multimedia Tools and Applications, 80(18), 27423-27443. https://doi.org/10.1007/s11042-021-11038-0


## Plugins existentes / desuso
1. SEASR analytics plugin. 2009. https://www.seasr.org/documentation/seasr-analytics-for-zotero/ (analíticas)
2. Papermachines. Sin mantenimiento desde 2017.   https://github.com/papermachines/papermachines (visualización)
