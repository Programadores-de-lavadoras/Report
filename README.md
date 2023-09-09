<div align="center"> 

![logo upc](images/upc-logo.png)

## Universidad Peruana de Ciencias Aplicadas

### Desarrollo de aplicaciones Open Source

#### Sección: WX52

#### Profesor: Juan Antonio Flores Moroco

### Informe del trabajo final

### Grupo 1

### "Readr"

### Ciclo 2023-2

| Nombres y Apellidos | Código |
|----------|----------|
| Stevens Acha    | Cell 2   |
| Santos Alexis Patazca Calderón    | u20201c269   |
| Leonardo Manuel Dueñas Canales    | u202117475   |
| Fabrizzio Hernán Laguerre Challco    | u20211a950   |
| Salomón Zegarra Moreno    | u201917922   |

#### AGOSTO 2023
</div>

----

# Registro de versión del informe 

| Versión | Fecha | Autor | Descripción de modificación |
|----------|----------|----------|----------|
| 1.0   | 27/08/2023   | Salomón Zegarra Moreno |Creación del reporte y se definió la estructura del informe|

-----

# Project Report Collaboration Insights
[Repository to Final Report](https://github.com/Programadores-de-lavadoras/Report)

----
# Tabla de Contenido
- [Capitulo I: Introducción](#capitulo-i-introducción)
    - [Startup Profile](#11-startup-profile)
        - [Descripción de la Startup](#111-descripción-de-la-startup)  
        - [Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)  
    - [Solution Profile](#12-solution-profile)
        - [Antecedentes y Problemática](#121-antecedentes-y-problemática)  
        - [Lean UX Process](#122-lean-ux-process)  
        - [Lean UX Problem Statements](#1221-lean-ux-problem-statements)  
        - [Lean UX Assumptions](#1222-lean-ux-assumptions)  
        - [Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)  
        - [Lean UX Canvas](#1224-lean-ux-canvas)  
    - [Segementos Objetivos](#13-segementos-objetivos)
- [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)
    - [Competidores](#21-competidores)
        - [Análisis Competitivo](#211-análisis-competitivo)
        - [Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
    -  [Entrevistas](#22-entrevistas)
        - [Diseño de entrevistas](#221-diseño-de-entrevistas)
        - [Registro de entrevistas](#222-registro-de-entrevistas)
        - [Análisis de entrevistas](#223-análisis-de-entrevistas)
    - [Needfinding](#23-needfinding)
        - [User Personas](#231-user-personas)
        - [User Task Matrix](#232-user-task-matrix)
        - [User Journey Mapping](#233-user-journey-mapping)
        - [Empathy Mapping](#234-empathy-mapping)
        - [As-Is Scenario Mapping](#235-as-is-scenario-mapping)
- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
    - [To-Be Scenario Mapping](#31-to-be-scenario-mapping)
    - [User Stories](#32-user-stories)
    - [Impact Mapping](#33-impact-mapping)
    - [Product Backlog](#34-product-backlog)
- [Capítulo IV: Product Design](#capítulo-iv-product-design)
    - [Style Guidelines](#41-style-guidelines)
        - [General Style Guidelines](#411-general-style-guidelines)
        - [Web Style Guidelines](#412-web-style-guidelines)
    - [Information Architecture](#42-information-architecture)
        - [Organization Systems](#421-organization-systems)
        - [Labeling Systems](#422-labeling-systems)
        - [SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
        - [Searching Systems](#424-searching-systems)
        - [Navigation Systems](#425-navigation-systems)
    - [Landing Page UI Design](#43-landing-page-ui-design)
        - [Landing Page UI Design](#431-landing-page-ui-design)
        - [Landing Page Mock-up](#432-landing-page-mock-up)
    - [Web Applications UX/UI Design](#44-web-applications-uxui-design)
        - [Web Application Wireframes](#441-web-application-wireframes)
        - [Web Application Wireflow Diagrams](#442-web-application-wireflow-diagrams)
        - [Web Applicationns Mock-up](#443-web-applicationns-mock-up)
        - [Web Application User Flow Diagrams](#444-web-application-user-flow-diagrams)
    - [Web Application Prototyping](#45-web-application-prototyping)
    - [Domain-Driven Software Architecture](#46-domain-driven-software-architecture)
        - [Software Architecture Context Diagram](#461-software-architecture-context-diagram)
        - [Software Architecture Container Diagrams](#462-software-architecture-container-diagrams)
        - [Software Architecture Components Diagram](#463-software-architecture-components-diagram)
    - [Software Object-Oriented Design](#47-software-object-oriented-design)
        - [Class Diagrams](#471-class-diagrams)
        - [Class Dictionary](#472-class-dictionary)
    - [Database Design](#48-database-design)
        - [Database Diagram](#481-database-diagram)

- [Capítulo V: Product Implementation, Validation, & Deployment](#capítulo-v-product-implementation-validation--deployment)
    - [Software Configuration Managment](#51-software-configuration-managment)
        - [Software Development Enviroment Configuration](#511-software-development-enviroment-configuration)
        - [Source Code Managment](#512-source-code-managment)
        - [Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)
        - [Software Deployment Configuration](#514-software-deployment-configuration)
    - [Landing Page, Services & Applications Implementation](#52-landing-page-services--applications-implementation)
        - [Sprint 1](#521-sprint-1)
            - [Sprint Planning 1](#5211-sprint-planning-1)
            - [Sprint Backlog 1](#5212-sprint-backlog-1)
            - [Development Evidence for Sprint Review](#5213-development-evidence-for-sprint-review)
            - [Testing Suite Evidence for Sprint Review](#5214-testing-suite-evidence-for-sprint-review)
            - [Execution Evidence for Sprint Review](#5215-execution-evidence-for-sprint-review)
            - [Services Documentation Evidence for Sprint Review](#5216-services-documentation-evidence-for-sprint-review)
            - [Software Deployment for Sprint Review](#5217-software-deployment-for-sprint-review)
            - [Team Collaboration Insights during Sprint](#5218-team-collaboration-insights-during-sprint)
- [Conclusiones](#conclusiones)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)

----

# Capitulo I: Introducción
## 1.1. Startup Profile
### 1.1.1. Descripción de la Startup
--escribir aquí--
### 1.1.2. Perfiles de integrantes del equipo
--escribir aquí--
## 1.2. Solution Profile
### 1.2.1. Antecedentes y Problemática
--escribir aquí--
### 1.2.2. Lean UX Process
#### 1.2.2.1. Lean UX Problem Statements
--escribir aquí--
#### 1.2.2.2. Lean UX Assumptions
--escribir aquí--
#### 1.2.2.3. Lean UX Hypothesis Statements
--escribir aquí--
#### 1.2.2.4. Lean UX Canvas
--escribir aquí--
## 1.3. Segementos Objetivos
--escribir aquí-- 

# Capítulo II: Requirements Elicitation & Analysis
## 2.1. Competidores
- **Archive of Our Own (AO3)**: Es la mayor plataforma de fanfics en el mundo, con un cátalogo que supera los 10 millones de historias disponibles en 50 lenguajes diferentes. Su interfaz es amigable y sencilla de navegar, cuenta con diversas categorías que sea de tu agrado.
- **Fanfiction.net (FF.net)**: Se clasifica como la segunda plataforma de fanfics más conocida, con un catálogo de más de 1 millón de relatos en inglés. Aunque su interfaz es más tradicional en comparación con AO3, sigue siendo una excelente alternativa para descubrir relatos de gran calidad.
- **Wattpad**: Es una plataforma de lectura y escritura de historias que también alberga una gran cantidad de fanfics. Se caracteriza por su interfaz social, que permite a los usuarios interactuar entre sí y comentar las historias.
### 2.1.1. Análisis Competitivo


¿Por qué llevar a cabo este análisis?	
¿Cómo contribuye al análisis de las preferencias que los usuarios buscan en una plataforma similar a la nuestra?


Nos capacita para ajustarnos y mejorar en áreas distintas a las de nuestros competidores, lo que nos permitirá sobresalir y atraer a una audiencia.

Competidores y logo	
Read-r	Archive of Our Own	Fanfiction.net	Wattpad
Perfil	Overview	 	 	 	 

Ventaja Competitiva
¿Qué valor ofrece a los clientes?	

Ofrece un amplio catálogo de contenido de fanfics, así como también una gran comunidad de lectores y escritores, estos ultimos siendo fuente de nuestra exclusividad	Ofrece una extensa colección de fanficts , se tiene acceso a un contenido que abarca toos los generos.	Posee una vasta colección de fanficts, Brinda una amplia variedad de elecciones.	Cuenta con una Plataforma de uso sencillo, tiene una extensa biblioteca de fanfics, cuenta con una comunidad de usuarios que interactuan mediante comentarios, foros. Esto fomenta apoyo a los escritores.
Perfil del Marketing	Mercado Objetivo	Fanáticos del fanfics, ademas de escritores con potencial.	Cualquier persona que disfrute de la lectura y escritura de fanficts 	Fanaticos de Fancits, Jovenes adultos y adolescents.	Fanáticos de franquicias populares de television, libros y películas. También para escritores aspirantes.

Estrategias de Marketing	Ofrecen una variedad de opciones de suscripción, incluyendo una versión gratuita con anuncios y una versión premium sin anuncios ademas de colaboracion de escritores y editores para ofrecer un mayor catalogo y calidad

Proporciona un entorno seguro para los escritores y lectores. Ofrece una variedad de herramientas diseñadas para ayudar a los usuarios a mejorar.	PArticipa en eventos de los fans y festivals de literature, la Plataforma por su parte realiza eventos. También trabaja con influencers escritores y lectores de las redes sociales. Proporciona incentivos a aquellos que recomienden la Plataforma a otras personas.	Emplea diversos medios marketing digital, publicidad en linea, presencia en redes social con los que colabora con personas influyentes para promocionar, y realiza campañas de correo electronico. También se involucra en eventos.
Perfil del producto	Productos y Servicios	Servicio de suscripción de fanfics que ofrece un gran catalogo en linea y la opcion de leer y publicar contenido en varios idiomas.	Los usuarios tiene la capacidad de cargar una amplia gama de archivos, incluyen texto, imagenes, audio y video. Tiene a disposición una serie de busquedas, según el título, el autor, el genero y otros criterios. 	Brinda un valor considerable a sus usuarios al proporcionar una amplia colección de fanfict, comunidad particpativa y una interfaz sencilla.	Brinda a los escritores publicar sus creaciones de manera gratuita, presenta una serie de programas de becas para respaldar a escritores en Desarrollo.
A los lectores les proporciona diversas herramientas que ayudan a encontrar contenido de su interés.

Precios y costos	Aplicación web que obtiene ganancia por suscripción y publicidad	No require ningún tipo de tarifa. La Plataforma se sustenta gracias a las donaciones de sus usuarios y aportaciones. 	Tiene a disposición una opción de suscripción premium, que Brinda acceso a características y servicios adicionales.	Es gratuito, pero Tambien ofrece un acceso de contenido exclusivo, como historias, no tener publicidad y descargar libros ilimitadament.

Canales de distribución (Web y/o Móvil)	Web Site	Web Site	Web site	Web site y dispositvos móviles (iOS y Android )

Análisis SWOT	Fortalezas	Amplia variedad de fanfics, además de la posibilidad de publicar obras de autores novatos de todo el mundo	Sin fines de lucro, no tiene publicidad es de libre contenido, permite a los usuarios publicar cualquier tipo de fanfict, cuenta con una gran comunidad de escritores, ofrece una variedad de servicios.	Cuenta con millones de historias para leer, desde populares hasta desconocidas, cuenta con una Plataforma intuitiva y facil de usar por parte del usuario. Su capacidad de calificar a otros usuarios.	Promocionar herramientas de edcición y publicación que ayudan a los escritores a mejorar la calidad de su trabajo. Contar con un programa de becas para brindar oportunidades a los escritores para que ganen reconocimiento y en algunos casos ingresos.

Oportunidades	Ampliar la variedad de contenido, crear material original, elevar los estándares de traducción, establecer alianzas con otros servicios de streaming, incursionary en nuevos mercados y nuevas alternativas adicionales para generar ingresos.	Expandirese a nuevos idiomas, mejorar todas sus funciones que ofrece a los usuarios. También colaborar con diversas organizaciones.	Ofrece nuevas funciones y servicios, contar con nuevas herramientas para los escritores.	Dispone en mas de 50 idiomas, pero podria alcanzar a mas audiencia. Contar con nuevas herramientas y colaborar con nuevos socios.

Debilidades	Existen ciertas carencias en los acuerdos de licencia que poodrian pone ren riesgo la integridad de algunas historias.  	Su interfaz puede causar confusion y no es tan sencillo para los nuevos usuarios, el moderar su contenido, los problemas de financiamiento. En algunas ocasiones la pagina puede ser inestable.	Su interfaz puede ser complicado de utilizer para algunos usuarios.
Los escritores cuentan con pocas alternativas para obtener ganancias.	 Cuenta con una amplia de contenido, eso incluye una cantidad de material de calidad inferior y puede complicar la busquedad de sus usarios.
La distribución de contenido illegal y casos de acoso en liena.

Amenazas	.La alta competencia, con competidores solidamente establecidos y las politicas de censura en cada país, lo cual podria influir en los fanfics.	Empresas o los gobiernos pueden censurar el contenido que Brinda, el no contar con un financiamiento por parte de la misma Plataforma puede que disminuya su popularidad.	Aumento de rivalidad en el mercado y tener mejores caracterisitcas esto puede causar dificultad que la Plataforma atraiga y retenga a sus usuarios.	Las tendencias tecnologicas en constante cambio, las preferencias cambiantes de los usarios y possible regulacion de gobiernos podria influir.


### 2.1.2. Estrategias y tácticas frente a competidores
- Asegurar la calidad del contenido: Los fanfics que pongamos a disposición contarán con traducciones y de alta calidad. Dado que la calidad del contenido es fundamental, nos esforzamos para evitar que los lectores se sientan decepcionados y así poder asegurar su fidelidad.
- Fomentar la creación de una comunidad: Facilitar un espacio de discusión, ya sea un foro o una sección de interacción, para que los lectores interactúen entre si y con los escritores representen una excelente forma de establecer una comunidad. Los lectores puedan debatir sus opiniones y compartir recomendaciones. 
- Estrategias de Marketing: Implementar una estrategia de promoción que incluirá publicidad en línea, campañas en redes sociales y realizar eventos para los usuarios, realizar colaboraciones con otros sitios web similares. 
- Ofrecer una experiencia de usuario atractivo: Diseñar una página web de fácil uso con una interfaz de usuario intuitiva para el usuario. Además, consideramos la implementación de funciones como búsquedas avanzadas y opciones de filtrado de títulos para facilitar al usuario. 
- Proporcionar contenido exclusivo: la oferta de contenido exclusivo, como ver los capítulos adelantados, con la finalidad de atraer a los lectores y mantenerlos comprometidos con la plataforma. 


## 2.2. Entrevistas

### 2.2.1. Diseño de entrevistas
**Para escritores:**

Preguntas introductorias:
1.	¿Cuál es su nombre completo y cuántos años tiene? Además, ¿en qué distrito se encuentra actualmente?
2.	¿A qué se dedica actualmente?
3.	¿Cuáles son los dispositivos que utiliza principalmente?
4.	¿Qué te motiva a escribir fanfics y compartirlos en línea?
5.	¿Qué género de historias te gusta producir y cuál es la razón?

Preguntas principales:
1.	¿Cómo evalúas la accesibilidad de publicar tus fanfics en formato digital para llegar a una audiencia considerable?
2.	¿Has tenido la posibilidad de generar ingresos a través de tu labor?

De ser el caso:

3.	¿Fue fácil lograr rentabilizar tu obra?

Caso contrario:
1.	¿Has explorado oportunidades para obtener ingresos con tu contenido?
2.	En caso de que hayas intentado monetizarlo, ¿qué obstáculos o dificultades encontraste que impidieron que lo lograras?
3.	En caso de que no hayas buscado monetizarlo, ¿te interesaría recibir alguna forma de recompensa económica por tu trabajo?
4.	¿Cómo te gustaría que una plataforma en línea te ayudara en tu proceso de creación de contenido?
5.	¿Qué funcionalidades esperarías de una plataforma en línea para simplificar el proceso de creación y compartición de contenido?
6.	Desde tu perspectiva como creador de contenido, ¿cuál crees que es el aspecto más crucial para que una plataforma en línea sea efectiva?
7.	¿De qué manera te gustaría recibir incentivos o reconocimientos por tu labor en una plataforma en línea?
8.	¿Qué tipo de feedback o interacción con los lectores valoras más como autor de fanfics?

**Para lectores de contenido:**

Preguntas introductorias:
1.	¿Cuál es su nombre completo y cuántos años tiene? Además, ¿en qué distrito se encuentra actualmente?
2.	¿Cuáles son los aspectos que disfrutas al leer fanfics?
3.	¿Cuáles son los dispositivos que utiliza principalmente?
4.	¿Cuáles son los géneros de fanfics que captan más tu interés y cuál es la razón detrás de esa preferencia?

Preguntas principales:
1.	¿En qué lugares frecuentas para buscar y consumir contenido en línea?
2.	¿Qué funciones esperarías de una plataforma en línea para hacer la experiencia de lectura más sencilla?
3.	¿Cómo te gustaría que la plataforma te ayude a descubrir nuevos fanfics relacionados con tus intereses?
4.	¿Cómo te gustaría que una plataforma web reconociera y premiara a los autores talentosos?
5.	¿Qué tipos de recompensas o estímulos te gustaría recibir por participar en la lectura y compartición de contenido en una plataforma en línea?
6.	Desde tu perspectiva como lector de contenido, ¿qué crees que es esencial para que una plataforma en línea te resulte beneficiosa?
7.	¿Qué expectativas tienes acerca de cómo una plataforma en línea podría asistirte en el seguimiento y la gestión de los contenidos que te atraen?
8.	¿Valorarías la opción de poder seguir a autores o historias específicas en la plataforma?

### 2.2.2. Registro de entrevistas

*Escritor*

Nombre: Nelson Maicol Guevara Oré 

Edad: 23 años

Distrito: San Miguel, Lima

![Alt text](image-8.png)

Nelson es un universitario que en sus pasatiempos se dedica a escribir fanfics. El comenta que ha realizado algunas publicaciones de sus fanfics y ha logrado obtener algunos ingresos, pero se debe a que sus seguidores le dieron de forma voluntaria y tampoco ha llegado a expandir con sus historias. 
A el le gustaría confiar en una plataforma que le brinde herramientas necesarias para poder seguir creciendo como escritor y le den visibilidad para poder ser conocido y tener ingresos mas solventes y fijos ya que eso le daría más confianza en seguir creciendo.


Nombre completo: Bhelén Orellana Patazca

Edad: 20 años

Distrito: Monsefú, Chiclayo

![Alt text](image-9.png)

Bhelén es una universitaria que escribe historias en sus tiempos libres. A ella le gustaría empezar a publicar sus historias, pero teme que estas no lleguen al público objetivo, y que no pueda surgir como escritora amateur.
A Bhelén le gustaría que en la aplicación web se pudiese escribir los escritos de una manera familiar, semejante a la interfaz de Word. Asimismo, desea que sea sencilla de entender y que exista una herramienta que le ayude a conocer la tecnología en su totalidad. Por otro lado, desea recibir feedback de los usuarios a través de la aplicación, pero desea poder controlar los comentarios negativos mediante filtros. 
Finalmente, piensa que la startup es una gran apuesta para ella, ya que le permitiría centrar la publicación de sus historias con seguridad de que llegará a sus usuarios objetivos, además de significar un ingreso económico a largo plazo.

*Lector*

Nombre completo: Ana Valentina Jimenes Cruz

Edad: 21 años

Distrito: Pachacamac

![Alt text](image-10.png)

Ana es una universitaria que lee fanfics en sus tiempos libres. Ella disfruta de leer las interacciones entre los lectores con el autor y entre ellos. Emplea principalmente su celular para leer y los géneros que más lee son el romance y el mismo género “fanfic” (relaciones entre personajes creadas por los fans)
Ana visita principalmente Wattpad y AO3 (Archive of Our Own), ya que son los dos sitios más grandes para leer contenido fanfiction. Ella considera que es difícil encontrar fanfics específicos en los sitios que visita, y le gustaría que la plataforma cuente con una funcionalidad que facilite la búsqueda.
Ana quisiera que la página le mostrase datos como las vistas, likes y comentarios del fanfic, de forma que tiene una idea si el fanfic que leerá será interesante.
Ella conoce que Wattpad da premios y ayuda a los escritores a publicar sus fanfics de manera oficial en formato físico. Considera que es una buena forma de incentivar a los escritores a seguir con su buen trabajo.
Sobre recompensas, considera que sería bueno que la aplicación diera a los lectores la posibilidad de leer capítulos de pago de manera gratuita por compartir o leer muchos capítulos gratuitos.
La idea de aplicación le pareció interesante, y le gustaría que nos enfoquemos en puntos clave: Que sea visualmente agradable y moderna, que contenga un sistema de bibliotecas y favoritos, así como seguimientos, y que su sistema de búsqueda cuente con filtros con el fin que sea más sencillo encontrar los fanfics de su preferencia.






### 2.2.3. Análisis de entrevistas
- Lectores:

Se valora la comunidad la accesibilidad a las métricas. Además, se considera que se debe brindar recompensas y apoyo a los escritores.
Los entrevistados consideran que una plataforma con características claves como bibliotecas, favoritos y búsqueda avanzada, esto seria ideal para mejorar la experiencia de la lectura de fanfics.

- Escritores:

Buscas una plataforma que ayuden a crecer como escritor, que aumente su visibilidad y obtener ingresos estables.
Una plataforma que les brinde herramientas necesarias para poder crear sus fanfics y no tener inconvenientes al subir a la plataforma.

## 2.3. Needfinding
### 2.3.1. User Personas

![Alt text](image.png)

![Alt text](image-1.png)

### 2.3.2. User Task Matrix

*Escritores*

Task	Abril López
Frecuencia	Importancia

Poner en público su contenido	Alta	Alta

Tener una estadística sobre el contenido que suben	Alta	Alta

Modificar su contenido que realizan	Media	Media

Hacer anuncios de su contenido antes de subir a la plataforma	Media	Media

*Lectores*

Task	Kevin Miranda
	Frecuencia	Importancia

Realizar búsqueda avanzada de contenidos.	Alta	Alta

Leer contenidos usando nuestra plataforma	Alta	Alta

Brindar más información y diversos géneros de fanfics	Media	Media

Revisar las tendencias y recomendaciones que brinda la plataforma	Media	Media

Descargar diversos fanfics a través de la pagina web.	Alta	Alta

Tener interacción con la comunidad a través de la plataforma	Alta	Alta



### 2.3.3 User Journey Mapping

*Escritores*

![Alt text](image-2.png)

*Lectores*

![Alt text](image-3.png)

### 2.3.4. Empathy Mapping

*Escritores*

![Alt text](image-4.png)

*Lectores*

![Alt text](image-5.png)

### 2.3.5 As-Is Scenario Mapping

*Escritores*

![Alt text](image-6.png)

*Lectores*

![Alt text](image-7.png)

# Capítulo III: Requirements Specification
## 3.1. To-Be Scenario Mapping
--escribir aquí--
## 3.2. User Stories
--escribir aquí--
## 3.3. Impact Mapping
--escribir aquí--
## 3.4. Product Backlog
--escribir aquí--

# Capítulo IV: Product Design
## 4.1. Style Guidelines
### 4.1.1. General Style Guidelines
--escribir aquí--
### 4.1.2. Web Style Guidelines
--escribir aquí--
## 4.2. Information Architecture
### 4.2.1. Organization Systems
--escribir aquí--
### 4.2.2. Labeling Systems
--escribir aquí--
### 4.2.3. SEO Tags and Meta Tags
--escribir aquí--
### 4.2.4. Searching Systems
--escribir aquí--
### 4.2.5. Navigation Systems
--escribir aquí--
## 4.3. Landing Page UI Design
### 4.3.1. Landing Page UI Design
--escribir aquí--
### 4.3.2. Landing Page Mock-up
--escribir aquí--
## 4.4. Web Applications UX/UI Design
### 4.4.1. Web Application Wireframes
--escribir aquí--
### 4.4.2. Web Application Wireflow Diagrams
--escribir aquí--
### 4.4.3. Web Applicationns Mock-up
--escribir aquí--
### 4.4.4. Web Application User Flow Diagrams
--escribir aquí--
## 4.5. Web Application Prototyping
--escribir aquí--
## 4.6. Domain-Driven Software Architecture
### 4.6.1. Software Architecture Context Diagram
--escribir aquí--
### 4.6.2. Software Architecture Container Diagrams
--escribir aquí--
### 4.6.3. Software Architecture Components Diagram
--escribir aquí--
## 4.7. Software Object-Oriented Design
### 4.7.1. Class Diagrams
--escribir aquí--
### 4.7.2. Class Dictionary
--escribir aquí--
## 4.8. Database Design
### 4.8.1. Database Diagram

# Capítulo V: Product Implementation, Validation, & Deployment
## 5.1. Software Configuration Managment
### 5.1.1. Software Development Enviroment Configuration
--escribir aquí--
### 5.1.2. Source Code Managment
--escribir aquí--
### 5.1.3. Source Code Style Guide & Conventions
--escribir aquí--
### 5.1.4. Software Deployment Configuration
--escribir aquí--
## 5.2. Landing Page, Services & Applications Implementation
### 5.2.1. Sprint 1
#### 5.2.1.1. Sprint Planning 1
--escribir aquí--
#### 5.2.1.2. Sprint Backlog 1
--escribir aquí--
#### 5.2.1.3. Development Evidence for Sprint Review
--escribir aquí--
#### 5.2.1.4. Testing Suite Evidence for Sprint Review
--escribir aquí--
#### 5.2.1.5. Execution Evidence for Sprint Review
--escribir aquí--
#### 5.2.1.6. Services Documentation Evidence for Sprint Review
--escribir aquí--
#### 5.2.1.7. Software Deployment for Sprint Review
--escribir aquí--
#### 5.2.1.8. Team Collaboration Insights during Sprint
--escribir aquí--

---
# Conclusiones

--escribir aquí--

---
# Bibliografía

--escribir aquí--

---
# Anexos

--escribir aquí--
