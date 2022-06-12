# BIBLIO RETRATO. Un ejercicio de Humanidades Digitales

Proyecto de visualización que busca complementar los datos visuales de una imagen fotográfica (autorretrato) con los metadatos de una base bibliográfica personal. Idealmente, es un proyecto de largo aliento, donde los cambios de cada año en el rostro y expresiones, se traslapan con las lecturas hechas a lo largo de ese periodo de tiempo. Para este proposito usaré mi propia base de datos de Zotero cuyas primeras entradas datan del 2012. Es un proyecto híbrido que desarrollaría herramientas de minería y visualización para Zotero[^1], así como galerías en web que superpongan esas visualizaciones con retratos fotográficos.

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




## Recursos en revisión
1. https://vispo.com/index.html  (animación)
2. https://www.usandizaga.com/design/pinacogramas-y-caligramas-retratos-con-letras/![imagen](https://user-images.githubusercontent.com/69394840/173201608-666907ba-def1-455e-8030-35f75e47067d.png) (retratos con letras)
3. https://wordart.com/  (Online cloud creator)
4. https://openrefine.org
5. https://voyant-tools.org/?corpus=451e87665270278b3512bc72bbe3472c&panels=cirrus,reader,trends,summary,contexts
6.
## Licencia
Todos los productos y servicios del proyecto son de acceso abierto
## Cómo citar
Márquez, T. (2022), Biblio-retrato, https://github.com/tmarquez-mx/biblio-retrato/edit/main/README.md
## Acceso y sustentabilidad
La aplicacación estará alojada en un sitio institucional y los datos que se reciban a través del sistema (como fotografías personales y analíticas), no se conservarán como parte de la protección de los datos personales.
## Procedimiento
1. Limpieza de la base Zotero con OpenRefine 
2. Separación del corpus en las columnas de un CSV utilizando delimitadores.
3. Extracción de columnas: título; autor; fechas; lugar de edición; subcolección


