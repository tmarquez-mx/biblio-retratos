# Biblio-retrato. ¿Somos lo que leemos? 
## Un ejercicio de Humanidades Digitales


Proyecto de visualización que busca complementar los datos visuales de un retrato fotográfico con los metadatos de un gestor de referencias bibliográficas.  Esta superposición explora digitalmente cierta representación identitaria que responde a la pregunta ¿somos lo que leemos? ¿en dónde se ubica ese cúmulo de lecturas bibliográficas respecto a nuestra propia representación y presentación? Para este proposito usaré mi propia base de datos de Zotero cuyas primeras entradas datan del 2012. Es un proyecto híbrido que desarrollará herramientas de minería de textos y visualización para Zotero [^1],así como galerías en web que superpondrán (overlap) esas visualizaciones que se generarán desde el gestor bibliográfico, con retratos fotográficos subidos por la web obteniendo por el mismo medio el biblio-retrato en formato .png o .jpg
[^1]: Herramientas como Paper Machine y Zotero Voyant Export no han sido actualizadas a las últimas versiones de Zotero pero sus códigos están disponibles en Github. https://github.com/papermachines/papermachines; https://github.com/corajr/zotero-voyant-export/
## Objetivos
1. Explorar los tipos de e-datos que conforman la identidad de una persona.
2. Elaborar herramientas de minería de textos y visualización para Zotero web, a fin de contruir trayectorias de las bases bibliográficas.
3. Crear visualizaciones que de manera estética a través de autorretarto, interroguen los vacíos de la fotografía y el lugar de la data-identidad

## Antecedentes
Siempre es difícil precisar con exactitud, de dónde o cómo nace un proyecto. Debo decir que soy una usuaria entusiasta  de Zotero por sus múltiples posibilidades de adecuarse flujos de trabajo académico manejados desde diferentes herramientas. En ese sentido, es muy importante para mí que mis estudiantes identifiquen sus bondades y beneficios. No he tenido mucha suerte en ello y por lo mismo incorporar Zotero en un proyecto de HD resulta una oportunidad para incentivar su uso.

Por otro lado, el dato y la fotografia son dos áreas de mi interés académico. Aunque parezcan opuestos por asociarse uno a lo abstracto-digital y la otra a lo concreto-material (el referente real), ambos conforman materiales para la representación de la persona. De modo que ponerlos a dialogar es una oportunidad para explorar sus posibilidades epistémicas en relacion a las identidades hibridas (análogas y digitales) que se forjan en estos tiempos. Por ultimo, siempre he tenido la inquietud de mostrar que el conocimiento tiene tambien un correlato sensorial y, por ende, estético que la academia debe sacar a la luz.  
## Estrategia de documentacion
El proyecto se documentará a través de Github y siguiendo la Guía de buenas prácticas para la elaboración y evaluación de proyectos de HD y Checklist de la Red HD. http://humanidadesdigitales.net/guia-de-buenas-practicas-para-la-elaboracion-y-evaluacion-de-proyectos-de-humanidades-digitales-y-checklist/
## Revisión y evaluación académica
Se buscará financiamiento académico por evaluación (DINV/Ibero). Además de la documentación en Github donde también se compartirá la metodología y los códigos desarrollados, habrá un sitio web desde donde se podrá hacer uso en línea de las aplicaciones desarrolladas. Se espera también desarrollar plugins para Zotero que estarán disponibles en la página de recursos de esa aplicación. De esta manera, los componentes del proyecto al estar abiertos al uso de una amplia comunidad académica, estará evaluación de pares y no-pares.
## Estrategia de sostenibilidad
Se trata de un punto crítico pues el biblio-retrato depende de las actualizaciones de Zotero que exigirá revisiones  constantes de los plugins que se desarrollen. Al abrir el código, se espera que de no contar con recursos para el mantenimiento, la comunidad de usuarios pueda hacerlo.
##  Experticias necesarias:
1.	Conocimiento del código abierto de Zotero y programación en JavaScript y SQLite 
2.	Manipulación de imagen digital y programación en HTML y Python
## Equipo
1. Teresa Marquez. Responsable
2. UnX programadorX. 
3. UnX diseñadorX Transmedia. 
## Influencias de proyectos HD
Proyectos en HD: 
1. “Intercambios oceánicos” https://oceanicexchanges.org/mx/ 
2. “I ♥ E-Poetry” https://iloveepoetry.org/
## Herramientas
Biblio-retrato, deberá hacer uso de Zotero y de OpenRefine, pues el primero contiene el corpus que se usará y el segundo es una herramienta para depurar los datos, por ello no se considerarán aquí como herramientas por separado.

Consideraré como herramientas, aquellas que traduzcan o transformen datos, como las aplicaciones de visualización siguientes

Voyant Tools, recibirá los textos desde un .CSV para generar las analíticas y las visualizaciones. Extisten ya dos plugins sin mantenimiento (Ver nota al pie 2). La tarea es actualizarlo a la versión vigente de Zotero.

Palladio, es otra herramienta de visualización de archivos .CSV que complementaria la galería de Voyant permitiendo mapear y conectar dos datos formando conjuntos.

La tercera  herramienta o código, deberá permitir recibir a través de una página web las visualizaciones de los plugins de Voyant y Palladio, así como las fotos que suba el usuario y realizar la superposición de ambas imágenes a través de IA. Una opción es trabajar sobre Pine Tools, una herramienta online gratuita. Habrá una galería con opciones preestablecidas de acuerdo al gráfico (nube, mapa, barras, etc.) y al encuadre de la foto. Finalmente, la aplicación web deberá devolver el biblio-retrato para ser bajado por el usuario.

Ningún elemento ni objeto digital (i.e. archivos .csv; .svg; .jpg; .png, etc.) se conservará en servidores por lo que los datos del usuario estarán plenamente seguros y libres de todo uso o almacenamiento indebido.

## Recursos en revisión (en proceso)
1. https://vispo.com/index.html  (animación)
2. https://www.usandizaga.com/design/pinacogramas-y-caligramas-retratos-con-letras/![imagen](https://user-images.githubusercontent.com/69394840/173201608-666907ba-def1-455e-8030-35f75e47067d.png) (retratos con letras)
3. https://wordart.com/  (Online cloud creator)
4. https://openrefine.org
5. https://voyant-tools.org/?corpus=451e87665270278b3512bc72bbe3472c&panels=cirrus,reader,trends,summary
## Acceso y sustentabilidad
La aplicacación estará alojada en un sitio institucional y los datos que se reciban a través del sistema (como fotografías personales y analíticas), no se conservarán como parte de la protección de los datos personales.
## Productos esperables
Al ser el primer proyecto de HD que se realizará en la Ibero, herramientas de software que se desarrollen, sinergias, infraestructura, metodologías y procesos (incluidos los de documentación) serán en sí mismos productos de la investigación. Como resultado final se pueden considerar participaciones en reuniones académicas o congresos; al menos dos artículos académicos y una exposición multimedia donde se mostrarán fotos impresas y en pantalla, así como animaciones del proceso de trabajo. La página web de biblio-retratos es el producto principal y contendrá además toda la documentación del proyecto lo que en sí mismo generará aprendizaje y antecedentes para buenas prácticas de la investigación abierta en la Ibero. 
## Licencia
<p xmlns:cc="http://creativecommons.org/ns#" >This work is licensed under <a href="http://creativecommons.org/licenses/by-nc-sa/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">CC BY-NC-SA 4.0<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/nc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/sa.svg?ref=chooser-v1"></a></p> 
<img width="965" alt="Captura de Pantalla 2022-06-11 a la(s) 21 00 29" src="https://user-images.githubusercontent.com/69394840/173211143-62becfaf-af07-4c53-9b94-302b48ec98c8.png">

## Procedimiento para maqueta (en proceso)
1. Limpieza de la base Zotero con OpenRefine 
2. Separación del corpus en las columnas de un CSV utilizando delimitadores.
3. Extracción de columnas: título; autor; fechas; lugar de edición; subcolección. Separación del campo autor para extraer solo apellidos.
4. Generar en Palladio y Voyant visualizaciones a partir del archivos .CSV depurado
5. Remover fondo de las imágenes .SVG  con removeBG
6. Capturar foto retratos
7. Fundir ambas imágenes
## Narrativa visual a partir de biblio-retratos simulados con fines demostrativos
![4](https://user-images.githubusercontent.com/69394840/173243391-75859132-e8fd-4829-8866-111a3d8e076d.png)
![1](https://user-images.githubusercontent.com/69394840/173243415-7db81dea-86e8-4159-bf9d-0d6c52f6efeb.png)
![2](https://user-images.githubusercontent.com/69394840/173243418-13b82350-55a1-4452-b328-10b69ccd38c6.png)
![3](https://user-images.githubusercontent.com/69394840/173243423-1f146093-2b5b-453a-a0b2-cbd8ca7b0817.png)
