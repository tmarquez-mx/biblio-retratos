# BIBLIO RETRATO. Un ejercicio de Humanidades Digitales

Proyecto de visualización que busca complementar los datos visuales de una imagen fotográfica (autorretrato) con las visualizaciones de los metadatos y analíticas de una base bibliográfica personal (o grupal). Idealmente, es un proyecto de largo aliento, donde los cambios de cada año en el rostro y expresiones, se traslapan con las lecturas hechas a lo largo de ese periodo de tiempo. Para este propósito usaré mi propia base de datos de Zotero cuyas primeras entradas datan del 2012. Es un proyecto híbrido que desarrollaría herramientas de minería y visualización para Zotero[^1], así como galerías en web que superpongan esas visualizaciones con retratos fotográficos a través de IA.

[^1]: Herramientas como Paper Machine y Zotero Voyant Export no han sido actualizadas a las últimas versiones de Zotero pero sus códigos están disponibles en Github. https://github.com/papermachines/papermachines; https://github.com/corajr/zotero-voyant-export/
## Objetivos
1. Explorar en los tipos de e-datos que conforman la identidad de una persona.
2. Elaborar herramientas de minería de datos y visualización para Zotero web, a fin de contruir trayectorias de uso. 
3. Crear visualizaciones que de manera estética a través de autorretarto, interroguen los vacíos de la fotografía y el lugar de la data-identidad
## Equipo
1. Teresa Marquez. Responsable
2. Un programador.
3. Un diseñador Transmedia.
## Antecedentes
Siempre es difícil identificar exactamente de dónde o cómo nace un proyecto. Debo decir que soy una usuaria entusiasta  de Zotero por sus múltiples posibilidades de adecuarse a un flujo de trabajo administrado con diferentes herramientas digitales. En ese sentido es muy importante para mí, que mis estudiantes identifiquen sus bondades y beneficios. No he tenido mucha suerte en ello y por lo mismo incorporar Zotero en un proyecto de HD resulta una oportunidad para incentivar su uso.
Por otro lado, el dato y la fotografia son dos temas de mi interés académico. Aunque parezcan opuestos (por asociarse uno a lo abstracto-digital y la otra a una representación material), ambos conforman representaciones de la persona, de modo que ponerlos a dialogar es una oportunidad para explorar sus posibilidades epistémicas en relacion a las identidades hibridas (análogas y digitales) que se forjan en estos tiempos. Por ultimo, siempre he tenido la inquietud de mostrar que el conocimiento tiene tambien un correlato sensorial y, por ende, estético que hay que sacar a la luz.  
## Estrategia de documentacion
El proyecto se documentará a través de Github y siguiendo la Guía de buenas prácticas para la elaboración y evaluación de proyectos de HD y Checklist de la Red HD. http://humanidadesdigitales.net/guia-de-buenas-practicas-para-la-elaboracion-y-evaluacion-de-proyectos-de-humanidades-digitales-y-checklist/
## Revisión y evaluación académica
Se buscará presentar el proyecto a una convocatoria institucional-académica de financiamiento de proyectos de investigación (DINV/Ibero). Además de la documentación en Github donde también se compartirá la metodología y los códigos desarrollados, habrá un sitio web desde donde se podrá hacer uso en línea de las aplicaciones desarrolladas. Se espera también desarrollar plugins para Zotero que estarán disponibles en la página de recursos de esa aplicación. De esta manera, los componentes del proyecto, al estar abierto, estarán en constante revisión de pares y no-pares.
## Estrategia de sostenibilidad
Se trata de un punto crítico pues el biblio-retrato depende de las actualizaciones de Zotero que exigirá revisiones  constantes de los plugins que se desarrollen. Al abrir el código, se espera que de no contar con recursos para el mantenimiento, la comunidad de usuarios pueda hacerlo.
## Habilidades involucradas
1.	Conocimiento de bases de datos: Se necesitara convertir los registros de Zotero en formato CVS que puedan ser introducidos a visualizadores 
2.	Fotografía digital: Manipulación de imagen digital a través de programas tipo Photoshop
3.	Programación HTML y Python
## Influencias
Proyectos en HD: 
1. “Intercambios oceánicos” https://oceanicexchanges.org/mx/ 
2. “I ♥ E-Poetry” https://iloveepoetry.org/
## Herramientas
Biblio-retrato, deberá hacer uso de Zotero y de OpenRefine, pues el primero contiene el corpus que se usará y el segundo es una herramienta para depurar los datos, por ello no se considerarán aquí como herramientas por separado.

Consideraré como herramientas, aquellas que traduzcan o transformar datos, como las herramientas visualizadoras. Siendo el concepto que el usuario de Zotero pueda directamente -a través de plugins- generar visualizaciones de analíticas a partir de  su(s) bases bibliográficas, para superponerlas con fotografías que suba a través de la web, de donde también bajará el biblio.retrato, las herramientas elegidas quizán deban ser modificadas para tal fin o desarrolladas.

Voyant Tools, recibirá los textos desde un .CSV para generar las analíticas y las visualizaciones. Extisten ya dos plugins sin mantenimiento (Ver nota al pie 2). La tarea es actualizarlo a la versión actual de Zotero.

Palladio, es otra herramienta de visualización de archivos .CSV que complementaria la galería de Voyant permitiendo mapear y conectar dos datos formando conjuntos.

La tercera  herramienta o código, deberá permitir recibir a través de una página web las visualizaciones de los plugins de Voyant y Palladio, así como las fotos que suba el usuario y hacer la superposición de ambas imágenes a través de IA. Habrá una galería con opciones preestablecidas de acuerdo al gráfico (nube, mapa, barras, etc.) y al encuadre de la foto. Finalmente, deberá devolver el biblio-retrato para ser bajado por el usuario. 

Ningún elemento ni objeto digital (i.e. archivos .csv; .svg; .jpg; .png, etc.) se conservará en servidores por lo que los datos del usuario estarán plenamente seguros y libres de todo uso o almacenamiento indebido.
## Recursos en revisión (en construcción)
1. https://vispo.com/index.html  (animación)
2. https://www.usandizaga.com/design/pinacogramas-y-caligramas-retratos-con-letras/![imagen](https://user-images.githubusercontent.com/69394840/173201608-666907ba-def1-455e-8030-35f75e47067d.png) (retratos con letras)
3. https://wordart.com/  (Online cloud creator)
4. https://openrefine.org
5. https://voyant-tools.org/?corpus=451e87665270278b3512bc72bbe3472c&panels=cirrus,reader,trends,summary,contexts

## Licencia
<p xmlns:cc="http://creativecommons.org/ns#" >This work is licensed under <a href="http://creativecommons.org/licenses/by-nc-sa/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">CC BY-NC-SA 4.0<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/nc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/sa.svg?ref=chooser-v1"></a></p>

<img width="965" alt="Captura de Pantalla 2022-06-11 a la(s) 21 00 29" src="https://user-images.githubusercontent.com/69394840/173211143-62becfaf-af07-4c53-9b94-302b48ec98c8.png">



## Cómo citar
Márquez, T. (2022), Biblio-retrato, https://github.com/tmarquez-mx/biblio-retrato/edit/main/README.md
## Acceso y sustentabilidad
La aplicacación estará alojada en un sitio institucional y los datos que se reciban a través del sistema (como fotografías personales y analíticas), no se conservarán como parte de la protección de los datos personales.
## Procedimiento para maqueta (en construcción)
1. Limpieza de la base Zotero con OpenRefine 
2. Separación del corpus en las columnas de un CSV utilizando delimitadores.
3. Extracción de columnas: título; autor; fechas; lugar de edición; subcolección. Separación del campo autor para extraer solo apellidos.
4. Generar en Palladio y Voyant visualizaciones a partir del archivos .CSV depurado
5. Remover fondo de las imágenes .SVG  con removeBG
6. Capturar foto retratos
7. Fundir ambas imágenes
