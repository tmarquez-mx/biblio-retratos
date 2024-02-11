# Biblio-retratos. Visualizando identidades académicas 
*Una reinterpretación desde las Humanidades Digitales de Zotero como dispositivo para documentar identidades académicas desde la literacidad*
                         
## Descripción narrativa
Biblio-retratos es una aplicación web que permite a usuarios de Zotero (un manejador bibliográfico de código abierto de uso extendido en la comunidad académica alrededor del mundo), obtener diferentes analíticas y visualizaciones sobre sus prácticas de literacidad. Esto es, sobre sus habilidades, trabajo y trayectoria en la recolección y procesamiento de fuentes bibliográficas. Todas ellas actividades que además de consumir gran cantidad de tiempo a lo largo de una carrera académica, son prácticas que reflejan pertenencias, disposiciones y fronteras teórico-metodológicas, conformando parte importante de una identidad académica. 
Biblo-retratos (o Zotero-BR) es un proyecto de Humanidades Digitales. En 2023 recibió financiamiento la [Dirección de Investigación y Posgrado](https://investigacion.ibero.mx/) de la [Universidad Iberoamericana, Ciudad de México](https://ibero.mx/)

## Descripción operativa

- Biblio-retratos (BR) comunica al usuario con su base de datos bibliográfica alojada por defecto en el servidor de Zotero mediante [Zotero Web API v3](https://www.zotero.org/support/dev/web_api/v3/start#zotero_web_api_v3). Si la base se encuentra en otro servidor, la comunicación no será posible. 
- BR solicitará durante el resgitro **por única vez**  el *ID User* y el *Private Key* de la cuenta de usuario de Zotero [Ver Instrucciones](Registro_Instruciones.md)
- Las consultas se realizan por tipo de elemento (i.e book. book section, jorunal, etc.)  o por subcolecciones. También puede consultarse a lo largo de toda la base si no selecciona ningún tipo de elemento ni subcolección.
- Los campos que se puede solicitar visualizar son: autor, lugar de edición, año de edición, año de adición, palabra clave y tipo de elemento. Nota: Debido a que BR obtiene la información de la base de datos remota loss resultados de las consultas por palabras clave (tags), pueden no corresponder a las palabra clave que el usuario visualiza en su aplicación Zotero de escritorio. Para verificar y depurar sus palabras clave (Tags), dirigirse a la versión web de Zotero.
- Las consultas puede limitarse temporalmente. Las opcioes son: anual (cada año de registro desde el inicio de la base), por lustros, por décadas, cada X cantidad de años, o en un rango de años de interés. De no especificar ninguna opción, la consulta se hará en todos los registros.

## Palabras clave
identidades académicas | analítica visual | literacidad | Humanidades Digitales |Zotero


## Funciones habilitadas (tasks)
Fase 1 Concluida y operativa. No requiere instalación. Operación vía web.
Actualmente en beta pública (03 2024)

- Comunicación con Zotero
- Consultas
- Despliegue de información
- Exportación .CVS
- Visualización
- Exportación .PNG

## Funciones futuras (tasks)

Fase 2
- Carga de imagen o fotografia (retrato)
- Galería de layouts
- Generación de biblio-retrato
- Exportación

## Seguridad
- Biblio-retratos no almacena contenido proveniente de la base de datos del usuario en Zotero. Solo facilita la comunicación entre ambos. 
- Los datos de correo electrónico, Zotero User Id y Zotero Private Key está protegidos por ley. Ver [Aviso de privacidad](https://ibero.mx/sites/all/themes/ibero/descargables/avisos-legales/2024/estudiantes-ingles.pdf)

## Guía de inicio
1. Entre al sitio de Biblio-retratos  XXXXXX.XXX
2. La primera vez deberá obtener su usuario introduciendo dando click al botón *"Regístrate aquí"
<img width="380" alt="Captura de pantalla 2024-02-10 a la(s) 7 19 40 p m" src="https://github.com/tmarquez-mx/biblio-retrato/assets/69394840/ddb04ce8-fd84-4321-b832-eb9b821b8c26">

    
  
4. En la siguiente pantalla ingrese su mail y una contraseña de 10 caracteres, usando altas y bajas.
<img width="480" alt="Captura de pantalla 2024-02-10 a la(s) 7 21 35 p m" src="https://github.com/tmarquez-mx/biblio-retrato/assets/69394840/09b3a791-2075-49fd-b4ef-c5210f607385">

  

6. La siguiente pantalla le solicitará por única vez el Zotero User ID y la Private Key. Para obtenerlos puede dirigirse a: https://www.zotero.org/settings/keys
o siga las siguientes [instrucciones](Registro_Instruciones.md)
   
 <img width="480" alt="imagen" src="https://github.com/tmarquez-mx/biblio-retrato/assets/69394840/38d60baa-9c6a-4899-8306-92b529858bbc">



## Guía de uso
Biblio-retratos le permitirá saber por ejemplo, qué autores ha registrado en Zotero en determinado periodo de años (cuando realizaba alguna tesis, cuando trabaja ciertos temas, cuando impartía ciertos curso).  
También podrá saber en qué años fueron publicados los artículos que tiene registrados o de dónde fueron editados sus libros de consulta. Son muchas las combinaciones que puede realizar en sus consultas


(PENDIENTE)
<img width="514" alt="Captura de pantalla 2024-02-10 a la(s) 9 10 28 p m" src="https://github.com/tmarquez-mx/biblio-retrato/assets/69394840/d6f570ca-2b62-422e-9d95-017fc003c90e">












## Historia 

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



## Diseño y registro de imagen de marca
En proceso  
Todos los derechos reservados a Universidad Iberoamerica, A.C.

  ![biblio-retratos_LOGOFIN](https://github.com/tmarquez-mx/biblio-retrato/assets/69394840/bd9cc728-0fb4-45ef-a59e-0b07fae4fe9b)

## Créditos
[Teresa Márquez](https://socialesypoliticas.ibero.mx/TeresaMarquez/), investigadora / [Xavier Tortolero](https://www.gtsf.com.mx/), desarrollador.


## Agradecimientos
- Dirección de Investigación y Posgrado, Ibero
- Cómputo Académico, Ibero
- Andrés Tortolero, Ingeniería de Datos, Ibero
- Jorge Angel González, INIAT, Ibero
- Sonia Montes, Dpto. de Letras, Ibero
- Informática, Ibero
- Zotero (forever! We ❤️ Z)



  
--- END ... SO FAR ---
 
