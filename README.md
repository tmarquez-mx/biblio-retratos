# Biblio-retratos. Visualizando identidades académicas

> Una reinterpretación, desde las Humanidades Digitales, de Zotero como *artefacto* para documentar y reflexionar sobre las identidades académicas a partir de las prácticas de literacidad.

##### [ENGLISH VERSION](https://github.com/tmarquez-mx/Biblio-retratosEV/blob/main/README.md)

---

## Esquema

- [Síntesis](#síntesis)
- [Marco conceptual](#marco-conceptual)
- [Descripción narrativa](#descripción-narrativa)
- [Descripción operativa](#descripción-operativa)
- [Palabras clave](#palabras-clave)
- [Funciones habilitadas](#funciones-habilitadas-tasks)
- [Funciones futuras](#funciones-futuras-tasks)
- [Desarrollo](#desarrollo)
- [Seguridad](#seguridad)
- [Limitaciones y alcances](#limitaciones-y-alcances)
- [Guía de registro](#guía-de-registro)
- [Guía de consultas](#guía-de-consultas)
- [Guía de visualización](#guía-de-visualización)
- [Historia](#historia)
- [Diseño y registro de imagen de marca](#diseño-y-registro-de-imagen-de-marca)
- [Cómo citar](#cómo-citar)
- [Referencias](#referencias)
- [Créditos](#créditos)
- [Agradecimientos](#agradecimientos)

---

## Síntesis

Biblio-retratos (BR) es una [aplicación web](https://biblioretratos.ibero.mx/) que conecta a quienes usan Zotero con su propia base bibliográfica para devolverles analíticas y visualizaciones de sus registros a lo largo del tiempo. Su apuesta no es meramente instrumental. BR parte de una hipótesis de las ciencias sociales y las Humanidades Digitales: la biblioteca que cada investigadora o investigador construye a lo largo de su carrera no es un archivo neutro, sino el sedimento de un conjunto de prácticas de literacidad situadas que expresan pertenencias, disposiciones y fronteras teórico-metodológicas. Leer esa base bibliográfica como un objeto interpretable permite componer un *retrato* reflexivo de una trayectoria académica.

## Marco conceptual

BR se sostiene en tres pilares teóricos que articulan su propuesta más allá de la función técnica.

**1. La literacidad como práctica social.** Desde los New Literacy Studies, la literacidad no se entiende como una destreza técnica autónoma y neutral, sino como una práctica social situada, atravesada por relaciones de poder y por contextos culturales e ideológicos (Street, 1984, 1995). Recolectar, clasificar, etiquetar y citar fuentes son prácticas de literacidad académica: actividades que consumen una parte sustantiva del tiempo de una carrera y que, al hacerlo, configuran identidad. La forma en que alguien construye y organiza su base bibliográfica revela adscripciones disciplinares, tradiciones teóricas y maneras de leer el mundo.

**2. El gestor bibliográfico como artefacto.** Desde los estudios sociales de la ciencia y la tecnología, un artefacto es un objeto material o digital interpretado: los objetos tecnológicos son productos contingentes de la acción humana, tanto física como interpretativa, y no instrumentos transparentes ni inevitables (Bijker, Hughes y Pinch, 1987). BR reinterpreta a Zotero, un gestor de uso extendido, como un artefacto cuyos metadatos pueden volverse a leer para documentar una práctica. No se trata de medir productividad, sino de hacer visible un proceso.

**3. La analítica visual como interpretación.** Las visualizaciones no son ventanas neutras a un dato preexistente. En la perspectiva humanística de la visualización, las formas gráficas no solo muestran conocimiento sino que lo producen, y los datos son mejor entendidos como *capta*: tomados y construidos como interpretación del mundo, no dados de antemano (Drucker, 2014). Por eso BR ofrece sus resultados como insumos para la reflexividad y no como verdades autoevidentes: cada gráfica es una lectura posible de una trayectoria, abierta a interpretación.

La conjunción de estos tres pilares define el sentido del proyecto. Un *biblio-retrato* es un autorretrato analítico y visual de una práctica de literacidad académica, una herramienta para que quien investiga observe, historice y problematice su propia identidad académica.

## Descripción narrativa

Biblio-retratos permite a usuarios de Zotero (un gestor bibliográfico de código abierto, de uso extendido en la comunidad académica internacional) obtener distintas analíticas y visualizaciones sobre sus prácticas de literacidad. Esto es, sobre sus habilidades, su trabajo y su trayectoria en la recolección y el procesamiento de fuentes bibliográficas. Estas actividades, además de consumir gran cantidad de tiempo a lo largo de una carrera, reflejan pertenencias, disposiciones y fronteras teórico-metodológicas que conforman una parte importante de la identidad académica.

Biblio-retratos (o Zotero-BR) es un proyecto de Humanidades Digitales. En 2023 recibió financiamiento de la [Dirección de Investigación y Posgrado](https://investigacion.ibero.mx/) de la [Universidad Iberoamericana Ciudad de México](https://ibero.mx/).

## Descripción operativa

- Biblio-retratos (BR) comunica al usuario con su base de datos bibliográfica, alojada por defecto en el servidor de Zotero, mediante la [Zotero Web API v3](https://www.zotero.org/support/dev/web_api/v3/start#zotero_web_api_v3). Si la base se encuentra en otro servidor, la comunicación no será posible.
- BR solicitará durante el registro, **por única vez**, el *User ID* y la *Private Key* de la cuenta de usuario de Zotero. [Ver instrucciones](https://github.com/tmarquez-mx/biblio-retratos/blob/main/Registro_Instruciones.md).
- Las consultas se realizan por tipo de elemento (por ejemplo, libro, capítulo de libro, artículo de revista, etc.) o por subcolecciones. También puede consultarse toda la base si no se selecciona ningún tipo de elemento ni subcolección.
- Los campos que se pueden solicitar para visualización son: autor, lugar de edición, año de edición, año de adición, palabra clave y tipo de elemento.

> Nota: dado que BR obtiene la información de la base de datos remota, los resultados de las consultas por palabras clave (*tags*) pueden no corresponder a las palabras clave que el usuario visualiza en su aplicación Zotero de escritorio. Para verificar y depurar sus palabras clave (*tags*), conviene dirigirse a la versión web de Zotero.

- Las consultas pueden limitarse temporalmente. Las opciones son: anual (cada año de registro desde el inicio de la base), por lustros, por décadas, cada cierta cantidad de años, o en un rango de años de interés. De no especificarse ninguna opción, la consulta se hará sobre todos los registros.

## Palabras clave

identidades académicas | analítica visual | literacidad | Humanidades Digitales | Zotero

## Funciones habilitadas (tasks)

Fase 1 concluida y operativa. No requiere instalación. Operación vía web. Actualmente en beta pública (03.2024).

- Comunicación con Zotero
- Consultas
- Despliegue de información
- Exportación .CSV
- Visualización
- Exportación .PNG

## Funciones futuras (tasks)

Fase 2

- Carga de imagen o fotografía (retrato)
- Galería de *layouts*
- Generación de biblio-retrato
- Exportación

## Desarrollo

- *Frontend*: framework Vue.js (JavaScript, código abierto)
- *Backend*: Java

## Seguridad

- Biblio-retratos no almacena contenido proveniente de la base de datos del usuario en Zotero. Solo facilita la comunicación entre ambos.
- Los datos de correo electrónico, *Zotero User ID* y *Zotero Private Key* están protegidos por ley. Ver [Aviso de privacidad](https://ibero.mx/sites/all/themes/ibero/descargables/avisos-legales/2024/estudiantes-ingles.pdf).
- Estándar de contraseña segura y validación Captcha.
- Servidor Apache libre de vulnerabilidades.

## Limitaciones y alcances

En coherencia con su marco conceptual, BR asume de manera explícita los límites de lo que ofrece:

- Las analíticas describen prácticas registradas en Zotero, no la totalidad de la práctica lectora o investigadora de una persona. Una base bibliográfica es una huella parcial, no un censo de la trayectoria.
- Los resultados dependen de la calidad y la consistencia de los metadatos del propio usuario (por ejemplo, palabras clave heterogéneas o registros incompletos). BR visibiliza esas prácticas tal como fueron registradas, sin corregirlas ni completarlas.
- Las visualizaciones son interpretaciones, no descripciones neutras. Se ofrecen como insumo para la reflexión y deben leerse con atención a las decisiones (filtros, intervalos, campos) que las produjeron.
- BR no infiere ni atribuye juicios de valor sobre la calidad académica de una trayectoria. No es un instrumento de evaluación ni de ranking.

## Guía de registro

1. Entre al sitio de Biblio-retratos (<https://biblioretratos.ibero.mx/>).
2. La primera vez deberá crear su usuario dando clic en el botón **`Regístrate aquí`**.

<img width="380" alt="Captura de pantalla 2024-02-10 a la(s) 7 19 40 p m" src="https://github.com/tmarquez-mx/biblio-retrato/assets/69394840/ddb04ce8-fd84-4321-b832-eb9b821b8c26">

3. En la siguiente pantalla ingrese su correo y una contraseña de 10 caracteres, usando mayúsculas y minúsculas.

<img width="480" alt="Captura de pantalla 2024-02-10 a la(s) 7 21 35 p m" src="https://github.com/tmarquez-mx/biblio-retrato/assets/69394840/09b3a791-2075-49fd-b4ef-c5210f607385">

4. La siguiente pantalla le solicitará, por única vez, el *Zotero User ID* y la *Private Key*. Para obtenerlos puede dirigirse a <https://www.zotero.org/settings/keys> o seguir estas [instrucciones](https://github.com/tmarquez-mx/biblio-retratos/blob/main/Registro_Instruciones.md).

 <img width="480" alt="imagen" src="https://github.com/tmarquez-mx/biblio-retrato/assets/69394840/38d60baa-9c6a-4899-8306-92b529858bbc">

## Guía de consultas

Biblio-retratos le permitirá obtener analíticas de los metadatos de su base bibliográfica. Podrá saber, por ejemplo, qué autores registró con mayor frecuencia en Zotero en determinado intervalo de años (por ejemplo, mientras realizaba alguna tesis, mientras trabajaba ciertas metodologías o mientras impartía determinados cursos). También podrá saber de qué años y lugares de edición proceden con mayor frecuencia sus fuentes, o qué subcolección de su biblioteca emplea tipos de elementos o formatos más variados.

Al ingresar a BR, después de identificarse (no será necesario ingresar correo ni contraseña, pues el sistema los conserva), aparecerá una pantalla donde identificará el botón **`Iniciar consulta`**. Al darle clic deberá seguir los siguientes pasos:

**Paso 1. Filtros de consulta.** Para iniciar una consulta deberá elegir, mediante un *check* en los recuadros del lado izquierdo, por qué **tipo de elemento** o por qué **colección** hará la consulta.

<!-- Conserve aquí las capturas de pantalla del paso 1 de su README actual -->

 <img width="514" alt="Captura de pantalla 2024-02-10 a la(s) 9 10 28 p m" src="https://github.com/tmarquez-mx/biblio-retrato/assets/69394840/d6f570ca-2b62-422e-9d95-017fc003c90e">

**Paso 2. Campos a visualizar.** Aquí debe elegir, mediante un *check*, el campo por el que quiere hacer la búsqueda en el tipo de elemento o colección que seleccionó en el paso anterior.

<img width="430" alt="Captura de pantalla 2024-02-11 a la(s) 5 44 31 a m" src="https://github.com/tmarquez-mx/biblio-retrato/assets/69394840/8401920d-119d-4877-bdc7-56fe1fcb51fb">

**Paso 3. Intervalos de tiempo.** Seleccione el intervalo temporal deseado.

<!-- Conserve aquí las capturas de pantalla del paso 3 de su README actual -->

Luego de configurar la consulta, dé clic en el botón correspondiente. La consulta puede tomar algún tiempo, ya que se realiza de manera remota sobre sus datos alojados en el servidor de Zotero. La duración dependerá de la velocidad de conexión, el tamaño de la base de datos, el número de parámetros de búsqueda, entre otros factores. Los resultados se desplegarán en forma de tabla, indicando frecuencias, y pueden exportarse a Excel.

<!-- Conserve aquí la captura de pantalla de resultados de su README actual -->

## Guía de visualización

Para generar visualizaciones de las tablas o analíticas, solo debe dirigir el cursor hacia los tres puntos que aparecen al lado izquierdo de los intervalos de tiempo y elegir la gráfica apropiada en el menú que se desplegará. La visualización resultante puede exportarse en formato .PNG.

<!-- Conserve aquí la captura de pantalla del menú de visualización de su README actual -->

El ejemplo siguiente es una nube de palabras que grafica la frecuencia con que aparecen todos los autores registrados en una base bibliográfica completa.

<!-- Conserve aquí la captura de pantalla de la nube de palabras de su README actual -->

### Demostración del proceso completo de consulta y visualización

<!-- Conserve aquí el GIF demostrativo de su README actual -->

## Historia

### 2023: (re)diseño y desarrollo

| Mes        | Hito                                                                                  |
| ---------- | ------------------------------------------------------------------------------------- |
| Abril      | Aprobación de financiamiento DINVP, Ibero                                             |
| Mayo       | Formación del equipo de trabajo                                                       |
| Junio      | Análisis y rediseño: de plugin a aplicación web. Coordinación con Cómputo Académico   |
| Julio      | Catálogo de funciones. Gestiones logísticas y financieras                             |
| Agosto     | Pruebas de comunicación con la base de datos                                          |
| Septiembre | Diseño y desarrollo de consultas                                                      |
| Octubre    | Pruebas, evaluación y aprobación del módulo de consultas                              |
| Noviembre  | Diseño y desarrollo de visualizaciones                                                |
| Diciembre  | Pruebas, evaluación y aprobación del módulo de visualización                          |

### 2024: beta y producción

| Mes        | Hito                                                                                                   |
| ---------- | ------------------------------------------------------------------------------------------------------ |
| Enero      | Cierre de la primera fase, entrega y presentación pública preliminar                                   |
| Febrero    | Gestión de servidor para beta pública. Evaluación del Depto. de Informática. Adecuaciones de seguridad |
| Marzo      | Lanzamiento de beta pública. Divulgación en el foro de Zotero y redes sociales (en preparación)        |
| Abril      | Presentaciones públicas (en preparación)                                                               |
| Mayo       | Diseño y registro de marca (pendiente)                                                                 |
| Junio      | Sistematización de comentarios y evaluaciones (pendiente)                                              |
| Julio      | Propuestas de financiamiento de mejoras y etapa 2 (pendiente)                                          |
| Agosto     | Artículo académico                                                                                     |

## Diseño y registro de imagen de marca

En proceso. Todos los derechos reservados a Universidad Iberoamericana, A.C.

<!-- Conserve aquí el logotipo de su README actual -->

## Cómo citar

Si Biblio-retratos resulta útil en su investigación o docencia, puede citarlo. Complete los datos entre corchetes según corresponda:

> Márquez, T. (2024). *Biblio-retratos. Visualizando identidades académicas* (Versión [número de versión]) [aplicación web]. Universidad Iberoamericana Ciudad de México. https://biblioretratos.ibero.mx/

## Referencias

Bijker, W. E., Hughes, T. P. y Pinch, T. (Eds.). (1987). *The social construction of technological systems: New directions in the sociology and history of technology*. MIT Press.

Drucker, J. (2014). *Graphesis: Visual forms of knowledge production*. Harvard University Press.

Street, B. V. (1984). *Literacy in theory and practice*. Cambridge University Press.

Street, B. V. (1995). *Social literacies: Critical approaches to literacy in development, ethnography and education*. Longman.

## Créditos

[Teresa Márquez](https://socialesypoliticas.ibero.mx/TeresaMarquez/), investigadora / [Xavier Tortolero](https://www.gtsf.com.mx/), desarrollador.

## Agradecimientos

- [Dirección de Investigación y Posgrado](https://investigacion.ibero.mx/), Ibero
- [Coordinación de Cómputo Académico](https://www.sis.uia.mx/), Ibero
- Andrés Tortolero, Ingeniería de Datos, Ibero
- Jorge Ángel González, INIAT, Ibero
- Sonia Montes, Depto. de Letras, Ibero
- Dirección de Informática y Telecomunicaciones, Ibero
- [Zotero](https://www.zotero.org/) (We ❤️ Z forever!)

---

*Un artefacto es aquí un objeto material o digital interpretado. La idea proviene de los estudios sociales de la tecnología, según los cuales los objetos tecnológicos son productos contingentes de la acción humana, tanto física como interpretativa.*








                         


## Desarrollo
- Frontend :  Framework Vue.js Javascript (open source)
- Backend  :  Java 

## Seguridad
- Biblio-retratos no almacena contenido proveniente de la base de datos del usuario en Zotero. Solo facilita la comunicación entre ambos.
- Los datos de correo electrónico, *Zotero User ID* y *Zotero Private Key* está protegidos por ley. Ver [Aviso de privacidad](https://ibero.mx/sites/all/themes/ibero/descargables/avisos-legales/2024/estudiantes-ingles.pdf)
- Estándar de contraseña segura y validación Catcha
- Servidor Apache libre de vulnerabilidades

## Guía de registro
1. Entre al sitio de Biblio-retratos (https://biblioretratos.ibero.mx/)
2. La primera vez deberá obtener su usuario introduciendo dando click al botón **`Regístrate aquí`**
<img width="380" alt="Captura de pantalla 2024-02-10 a la(s) 7 19 40 p m" src="https://github.com/tmarquez-mx/biblio-retrato/assets/69394840/ddb04ce8-fd84-4321-b832-eb9b821b8c26">

    

    
3. En la siguiente pantalla ingrese su mail y una contraseña de 10 caracteres, usando altas y bajas.
<img width="480" alt="Captura de pantalla 2024-02-10 a la(s) 7 21 35 p m" src="https://github.com/tmarquez-mx/biblio-retrato/assets/69394840/09b3a791-2075-49fd-b4ef-c5210f607385">

  

  
4. La siguiente pantalla le solicitará por única vez el *Zotero User ID* y la *Private Key*. Para obtenerlos puede dirigirse a: https://www.zotero.org/settings/keys
o siga las siguientes [instrucciones](Registro_Instruciones.md)
   
 <img width="480" alt="imagen" src="https://github.com/tmarquez-mx/biblio-retrato/assets/69394840/38d60baa-9c6a-4899-8306-92b529858bbc">



## Guía de consultas
Biblio-retratos le permitirá obtener analíticas de los metadatos de su base bibliográfica. Podrá saber por ejemplo, qué autores registró con mayor frecuencia en Zotero en determinado intervalo de años (i.e. cuando realizaba alguna tesis, cuando trabaja ciertos metodologías, cuando impartía determinados cursos).  
También podrá saber de qué años y lugares de edición proceden con mayor frecuencia sus fuentes. O qué subcolección de su biblioteca usa tipos de elementos o formatos más variados. 
Al ingresar a BR, después de identificarse (no será necesario ingresar mail ni contraseña pues el sistema los conserva) aparecerá una pantalla donde indentifcará el botón **`Iniciar consulta`**   
Al darle click deberá seguir los siguientes pasos para realizar una consulta:
 
 <img width="514" alt="Captura de pantalla 2024-02-10 a la(s) 9 10 28 p m" src="https://github.com/tmarquez-mx/biblio-retrato/assets/69394840/d6f570ca-2b62-422e-9d95-017fc003c90e">

Paso 1  
Filtros de consulta: 

--- 
Para iniciar una consulta, deberá elegir a través de un check en los recuadros del lado izquierdo, porqué **tipo de elemento** Y/O de **colección** hará la consulta

<img width="430" alt="Captura de pantalla 2024-02-11 a la(s) 5 23 41 a m" src="https://github.com/tmarquez-mx/biblio-retrato/assets/69394840/f9a0d49c-bf1d-419d-836c-441d3292b0d0">
<img width="430" alt="Captura de pantalla 2024-02-11 a la(s) 5 37 36 a m" src="https://github.com/tmarquez-mx/biblio-retrato/assets/69394840/6e65c805-435c-4e67-93b4-1302df9f51ef">



  
Paso 2   
Campos a visualizar

---
Aquí debe elegir mediante un check el campo por el que quiere hacer la búsqueda en el tipo de elemento o colección que seleccionó en el paso anterior

<img width="430" alt="Captura de pantalla 2024-02-11 a la(s) 5 44 31 a m" src="https://github.com/tmarquez-mx/biblio-retrato/assets/69394840/8401920d-119d-4877-bdc7-56fe1fcb51fb">


Paso 3   
Intervalos de tiempo

---



<img width="430" alt="Captura de pantalla 2024-02-11 a la(s) 5 48 35 a m" src="https://github.com/tmarquez-mx/biblio-retrato/assets/69394840/9179c53c-b95d-483a-9234-28aa12cffd63">
<img width="430" alt="Captura de pantalla 2024-02-11 a la(s) 5 53 05 a m" src="https://github.com/tmarquez-mx/biblio-retrato/assets/69394840/07edd22c-d9d1-466b-8aae-67061a4ad230">






Luego de configurar las consultas, dar click en el botón
<img width="96" alt="Captura de pantalla 2024-02-15 a la(s) 11 55 14 p m" src="https://github.com/tmarquez-mx/biblio-retratos/assets/69394840/ee3073cf-a94c-4561-9680-566f77765edd">

  
La consulta puede tomar algún tiempo debido a que se está realizando de manera remota en sus datos alojados en el servidor de Zotero. La duración dependerá de la velocidad de conexión, el tamaño de la base de datos, el número de parámetros de la búsqueda, etc.
Los resultados se desplegarán en forma de tabla indicando frecuencias y pueden exportarse e Excel.

<img width="430" alt="Captura de pantalla 2024-02-16 a la(s) 12 02 38 a m" src="https://github.com/tmarquez-mx/biblio-retratos/assets/69394840/dfa658e4-cbc2-417c-8bfe-1105e043c3b3">

  
## Guía de visualización

Para generar visualizaciones de las tablas o analíticas, solo debe dirigir el cursos hacia los 3 puntos que aparecen al lado izquierdo de los intervalos de tiempo y elegir la gráfica apropiada del menú que se desplegará.
La visualización resultante puede exportarse en formato .PNG

<img width="430" alt="Captura de pantalla 2024-02-16 a la(s) 12 05 06 a m" src="https://github.com/tmarquez-mx/biblio-retratos/assets/69394840/43ea6e02-62f0-43a7-84f2-6ea3300b0449">



  
El ejemplo mostrado a continuación es una nube de palabras que grafica la fecuencia con que aparecen todos los autores registrados en una base bibliográfica completa. 
﻿![imagen img width="430 ](https://github.com/tmarquez-mx/biblio-retrato/assets/69394840/aa00b0d8-ab21-4fc3-81b7-bc289fb5e6db)


  


    
### IMG: Demo del proceso de completo de consulta y visualización  

  
![BR_gif](https://github.com/tmarquez-mx/biblio-retrato/assets/69394840/3483fef7-1859-4091-a2da-4b4497de20c6)




  
## Historia 

### 2023 : (re) diseño y desarrollo ###

| <!-- -->      | <!-- -->        | 
|:-------------|:---------------|
| Abril         | Aprobación financimiento  DINVP, Ibero.       | 
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
| Abril       | Presentaciones públicas (en preparación)  | 
| Mayo        |Diseño y registro de marca (pendiente) | 
| Junio        |Sistematización de comentarios y evaluaciones (pendiente) | 
| Julio       | Propuestas para financiamiento de mejores y etapa 2 (pendiente)  | 
| Agosto       |Artículo académico  | 
| Septiembre   |  | 



## Diseño y registro de imagen de marca
En proceso  
Todos los derechos reservados a Universidad Iberoamerica, A.C.

  ![biblio-retratos_LOGOFIN](https://github.com/tmarquez-mx/biblio-retrato/assets/69394840/bd9cc728-0fb4-45ef-a59e-0b07fae4fe9b)

## Créditos
[Teresa Márquez](https://socialesypoliticas.ibero.mx/TeresaMarquez/), investigadora / [Xavier Tortolero](https://www.gtsf.com.mx/), desarrollador.


## Agradecimientos
- [Dirección de Investigación y Posgrado](https://investigacion.ibero.mx/), Ibero
- [Coordinación de Cómputo Académico](https://www.sis.uia.mx/), Ibero
- Andrés Tortolero, Ingeniería de Datos, Ibero
- Jorge Angel González, INIAT, Ibero
- Sonia Montes, Dpto. de Letras, Ibero
- Dirección de Informática y Telecomunicaciones, Ibero
- [Zotero](https://www.zotero.org/) ( We ❤️ Z forever!)


---
* Un artefacto es aquí un objeto material o digital interpretado. Esta idea está inserta en los estudios sociales de la tecnología por la cual los objetos tecnológicos son productos contingentes de la acción humana tanto física como interpretativa.
  
 
