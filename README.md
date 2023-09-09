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
| Stevens Kharis Acha Esquerre | u20201e735 |
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
Programadores de lavadadoras es un startup dedicado a fomentar y motivar los hábitos de lectura mediante el uso de tecnologías que facilitan el acceso, la distribución y la creación de contenidos.
En Programadores de lavadoras, nos visualizamos como líderes en la transformación del sector de la lectura a través de soluciones tecnológicas innovadoras y una cultura de colaboración. Queremos ser reconocidos por nuestra capacidad para crear un ecosistema de lectura inclusivo, accesible y sostenible, que inspire a las personas a leer y disfrutar de historias en todo el mundo.
Nuestra misión es hacer que la lectura sea más accesible y atractiva para todas las personas, sin importar su edad o nivel de educación. Para lograrlo, trabajamos en estrecha colaboración con autores, editores y lectores para desarrollar soluciones tecnológicas innovadoras que hagan que la lectura sea más conveniente y atractiva que nunca.
### 1.1.2. Perfiles de integrantes del equipo
| <div style="width:200px">Foto</div>                         | Descripción |
|-------------------------------------------------------------|-------------|
| <img src="./images/stevens.png" width="200" height="200">   |       Soy Stevens Kharis Acha Esquerre, tengo 20 años y me encuentro en el 6to ciclo de la carrera de Ingeniería de software, correspondiente a este curso. Tengo conocimientos amplios en la programación orientada a objetos (OOP) en lenguajes como C++, C#, Java y Python. He desarrollado aplicaciones web colaborativas aportando tanto en el front-end como en el back-end. Esto me ha permitido conocer sobre Frameworks como Angular, Vue y Tailwind; además de potenciar mis habilidades con HTML, CSS, JavaScript y TypeScript. Como persona, me gusta trabajar en equipo, priorizando la colaboración equitativa y organizada. No me considero un líder nato, pero estoy dispuesto a escuchar a los demás y tomar la iniciativa. Me gusta escuchar música y jugar videojuegos, y siempre tengo ganas de innovar.        |
| <img src="./images/salomon.png" width="200" height="200">   |       Soy Salomón Zegarra Moreno, estudiante de la carrera de Ingeniería de Software. Tengo experiencia trabajando en un equipo multidisciplinario, ya que he sido parte del Laboratorio de Software y Tecnologías Interactivas de la Universidad San Martín de Porres, en el año 2018. Además, he participado en congresos internacionales como parte del Staff de apoyo.      |
| <img src="./images/alexis.jpg" width="200" height="200">    |       Soy Santos Alexis Patazca Calderón, estudio Ingeniería de Software. Soy una persona responsable y soy respetuoso con mis compañeros de equipo, me gusta seguir aprendiendo diversos lenguajes de programación. Tengo grandes expectativas en este curso y poder seguir aprendiendo.      |
| <img src="./images/fabrizzio.jpg" width="200" height="200"> |       Mi nombre es Fabrizzio Hernán Laguerre Challco, tengo 19 años, desde pequeño siempre he sentido un interés por aprender a usar ciertos dispositivos siendo uno de estos los más útiles que tenemos en la actualidad, las computadoras, por ello me esforzado en practicar y aprender ciertas habilidades en ofimática, edición de videos, programación y en aprender inglés, habilidades que puedo ofrecer para contribuir al grupo.      |
| <img src="./images/leonardo.png" width="200" height="200">  |       Mi nombre es Dueñas Canales, Leonardo Manuel estudio ing. de Software, Me gusta los videojuegos y la programación. Este último no se me fue influenciada por nadie durante mi infancia, fue hasta 5to de primaria con un profesor de informática que me permití abrirme al mundo de la programación debido a que nos mandó a realizar un trabajo final que se trataba de crear una página web.      |
## 1.2. Solution Profile
### 1.2.1. Antecedentes y Problemática
**What?**<br>
La problemática detectada por nuestro startup se centra en la disminución de los hábitos de lectura que ha ocurrido en las últimas décadas, debido a la revolución tecnológica y la aparición de nuevos medios de entretenimiento.
Esto afecta tanto a los lectores, quienes consumen poco contenido o no disponen de una forma sencilla y directa de hacerlo, como a los autores, quienes producen contenido para ser disfrutado por los lectores.
Asimismo, se necesita innovar en el uso de la tecnología para hacer que la lectura sea más accesible, atractiva y conveniente para las personas.

**When?**<br>
Lamentablemente, este problema ha estado presente durante las últimas décadas debido al aumento de las aplicaciones y servicios de entretenimiento que han penetrado en el mercado con fuerza, lo que ha ocasionado que los medios tradicionales, como la lectura, ya no resulten tan atractivos como solían ser.
En consecuencia, con el fin de fomentar tanto la creación como el consumo de lectura, nuestro producto estaría diseñado para ser utilizado por personas interesadas en disfrutar o crear contenido de lectura como medio de entretenimiento.

**Where?**<br>
Los usuarios podrán utilizar nuestra aplicación en cualquier dispositivo que dispongan de acceso a internet, ya que contará con diseño responsivo. Por ende, está dirigida (principalmente) a los autores y lectores de contenido literario.

**Who?**<br>
Los usuarios de la plataforma (e involucrados en el problema) son las personas interesadas en la creación y el consumo de historias, cómics y mangas.

**Why?**<br>
Se crea el startup para atender a la disminución de hábitos de lectura debido a la revolución tecnológica y la aparición de nuevos medios de entretenimiento. Nuestra plataforma busca fomentar la lectura y la creación de historias para ofrecer una alternativa de entretenimiento atractiva y accesible.

**How?**<br>
La plataforma permitirá a los autores compartir sus obras con la comunidad. Además, los autores podrán compartir en un blog ideas, tips, consejos, etc. para que los demás usuarios puedan leerlo. Se ofrecerán herramientas para la creación de contenido (como editor de texto o subida de imágenes) y se buscará incentivar a los autores a seguir publicando sus obras al recibir un tipo de retribución por ellas.

**How much?**<br>
Según La República (2022), el hábito de la lectura resulta importante porque permite quitar estrés, mejora el vocabulario, ayuda a evitar el alzheimer, fomenta la creatividad, permite desarrollar la empatía, etc. Por lo tanto, queda claro que resulta una actividad de ocio (dado que ayuda a quitar el estrés) que brinda varios beneficios útiles para la vida del lector.
Desafortunadamente, es importante destacar que, según Forbes (2021), los peruanos leen un libro al año aproximadamente. Valor que, en comparación a otros países latinoamericanos, queda dentro de los puestos de menor libros leídos.

**Antecedentes:**<br>
En la actualidad, los hábitos de lectura se encuentran disminuyendo debido al aumento de las distracciones y la competencia de otras formas de entretenimiento, como la televisión, los videojuegos y las redes sociales.
Asimismo, muchas personas tienen dificultades para acceder a libros y otros materiales de lectura debido a limitaciones geográficas, económicas o por su forma de acceso (librerías o bibliotecas).
Finalmente, es importante destacar que la industria editorial tradicional se enfrenta a la amenaza de la piratería digital, lo que dificulta la monetización de la creación de contenidos.

**Problemática a resolver:**<br>
En consecuencia, a todo lo presentado con anterioridad, existe una necesidad de fomentar hábitos de lectura saludables y mejorar la accesibilidad a los libros y otros materiales de lectura.
Para esto, es necesario encontrar nuevas formas de monetizar la creación de contenidos y proteger los derechos de autor. Asimismo, se necesita innovar en el uso de tecnología para hacer que la lectura sea más accesible, atractiva y conveniente para las personas.

### 1.2.2. Lean UX Process
#### 1.2.2.1. Lean UX Problem Statements
**Problem Statement #1: Creadores de contenido literario**<br>
En la actualidad, muchos autores (principalmente novatos) afrontan problemas para retener y atraer a nuevos usuarios que consuman sus obras. Asimismo, emplear los medios tradicionales de publicación suele implicar un proceso bastante extenso para obtener algún tipo de retribución económica por el trabajo realizado además de que, los medios de publicación que emplean suelen estar limitados en el uso de la nueva tecnología o no es aprovechado al máximo.
De este modo, se ha detectado como factor crítico el hecho de que no se brinden facilidades a los autores para la publicación y monetización de su contenido con el uso de las nuevas tecnologías que les permite alcanzar a una mayor cantidad de usuarios lectores.<br>
**¿Cómo brindar una mejor experiencia a los autores al momento de tener que publicar y vender sus obras según las nuevas tecnologías e innovaciones que existen en el mercado actual?**

**Problem Statement #2: Lectores de contenido**<br>
Las personas que buscan consumir contenido literario a menudo se enfrentan a la difícil realidad de no tener acceso fácil al contenido en formato digital. Además, en algunos casos no logran encontrar legalmente el contenido deseado, lo que las lleva a recurrir a prácticas ilegales como la piratería, lo que afecta directamente a los creadores de contenido.
De este modo, se detectó como factor crítico la falta de acceso fácil y legal al contenido literario en formato digital que permitan a los lectores seguir apoyando a los autores de las obras que ellos consumen sin tener que recurrir a prácticas no éticas que perjudican la industria.<br>
**¿Cómo se puede aprovechar al máximo las nuevas tecnologías y herramientas disponibles en la actualidad para brindar facilidades para adquirir y consumir contenido literario a los lectores que mejoren su experiencia en general?**

#### 1.2.2.2. Lean UX Assumptions
**Business Assumptions:**<br>
Creo que mis usuarios necesitan una mejor forma de realizar el proceso de publicación y monetización del contenido que ellos elaboran.
Estas necesidades se pueden resolver con una aplicación web que facilite la publicación de los diversos tipos de obras que se publiquen (cómics, mangas, novelas ligeras, etc.) y automatice y facilite la posibilidad de monetizar las obras de un autor.
Mis clientes iniciales son los autores que se encargan de crear el contenido a publicarse y monetizarse. <br>

El valor #1 que un cliente requiere de mi servicio es que puedan publicar sus obras de manera rápida y sencilla, además de que les permita realizar las operaciones de edición y publicación.<br>

El cliente también puede obtener estos beneficios adicionales: ahorrar tiempo en realizar el proceso de publicación (al contar con una herramienta que lo gestiona de una manera más automatizada), una mejor experiencia por parte de los lectores (al contar con una amplia variedad de contenido centralizado en una aplicación que le fomente a seguir leyendo) y una mayor facilidad para obtener algún tipo de retribución económica por sus obras.

Voy a adquirir a mis clientes a través de publicidad en redes sociales como YouTube y Google Ads para alcanzar a los autores y lectores de contenido literario. Asimismo, buscaremos fidelizar a nuestros clientes para que empiecen a realizar marketing de boca a boca.

Haré dinero a través de planes de suscripción a los lectores de la página que quieran acceder al contenido completo del catálogo.

Mi competencia en el mercado serán las empresas ya establecidas que ofrecen aplicaciones que permiten realizar estas mismas acciones de acceso, publicación y edición de obras.

Los venceremos debido a que brindaremos una experiencia de software que cumple con lo requerido para que sea una aplicación completa en su rubro y sea amigable con los dos usuarios que interactúan con ella.

Mis mayores riesgos de producto son fallas en el sistema de la aplicación web y que el cliente no lo considere una alternativa adecuada a sus necesidades.

Resolveremos esto a través de un buen proceso de desarrollo, apoyado en el diseño previo de la aplicación; así como la realización de entrevistas para conocer más a fondo la situación actual, que es lo que espera el usuario y que tan cómodo se encuentra con la propuesta que planteamos.

Sabremos que hemos tenido éxito cuando veamos uno de estos cambios en el comportamiento de nuestro cliente:
- Mayor satisfacción al saber que puede acceder fácilmente a una retribución por su trabajo realizado.
- Motivación al saber que su contenido está siendo publicado en una plataforma que fomenta la lectura entre los lectores apasionados a las historias.

**¿Qué otras suposiciones tenemos que, de probarse falsas, pueden causar que nuestro proyecto fracase?**<br>
- Los lectores buscan utilizar medios más actuales para adquirir y consumir contenido literario.
- Los autores no se sienten cómodos con los medios tradicionales de publicación. Asimismo, esperan en algún momento recibir algún tipo de retribución por su trabajo.

**User Assumptions**<br>
**¿Quién es el usuario?**
- Los autores / creadores de contenido literario que escriban diferentes tipos de historias (ej. cómics, mangas y novelas ligeras).
- Lectores que consumen contenido literario por medio tradicionales y/o digitales.

**¿Dónde encaja nuestro producto? ¿En su trabajo o en su vida?**<br>
En el caso de los lectores, la utilización de la plataforma se da cuándo están buscando realizar una actividad de ocio. Por ende, el producto será utilizado en su vida cotidiana.

En el caso de los autores, dependerá de la percepción que ellos tengan sobre las obras que escriben (ya sea un hobby o un trabajo). No obstante, para fines prácticos, se considerará que nuestro producto será utilizado en el desarrollo de sus actividades de trabajo.

**¿Qué problemas tiene nuestro producto y cómo se pueden resolver?**<br>
Problemas:
- Que la herramienta no resulte atractiva para los lectores y autores, ya que sin ambas partes no se podría generar suficiente contenido y monetización para mantener el negocio en funcionamiento.
- Que los lectores no encuentren interesante nuestra propuesta y prefieran conservar o mantener la forma en la que consumían contenido hasta el momento.
Solución:
- Realizar un buen diseño de entrevistas para que esta sea realizada de la mejor manera posible y entender qué es lo que espera encontrar los dos tipos de usuario y cómo debería ser su experiencia de usuario al emplear la aplicación.
- Obtener información de la competencia y analizarla para establecer un estándar de qué características necesitamos desarrollar para nuestro producto.

**¿Cuándo y cómo es usado nuestro producto?**<br>
Nuestro producto de software será utilizado cuando el autor de historias decida publicar sus obras y busque, opcionalmente, recibir algún tipo de retribución económica por ello.

También, cuando el lector decida acceder a consumir diversas obras publicadas en una misma plataforma.

Finalmente, nuestro producto será utilizado por medio de una aplicación web que cuente con diseño responsivo y les permita a nuestros usuarios desarrollar cómodamente todas las operaciones que requiera independientemente del tamaño de la pantalla de su dispositivo.

**¿Qué características son importantes?**
- Realizar operaciones de creación, visualización y edición de las obras que el autor publique.
- Permitir a los autores crear blog post para que puedan compartir ideas, tips, consejos, etc. con los demás usuarios.
- Facilitar al lector la búsqueda de obras según la saga, género o título de este.
- Limitar el acceso de los usuarios gratuitos a los primeros 3 capítulos de las obras.

**¿Cómo debe verse y comportarse nuestro producto?**
- La interfaz de usuario (UI) de nuestra aplicación debe de ser moderna, llamativa y coherente con nuestro rubro de lectura.
- La experiencia de usuario (UX) de nuestra aplicación debe de priorizar la navegación sencilla e intuitiva a través de los diferentes apartados de la aplicación.
- El servicio debe de estar disponible en todo momento (24/7).

#### 1.2.2.3. Lean UX Hypothesis Statements
**Creemos que** sí ofrecemos una plataforma para la publicación de obras literarias como mangas y novelas ligeras asiáticas (principalmente), aumentará el interés del público en estas formas de entretenimiento. **Sabremos que** estamos en lo cierto **cuando** se observa un aumento en el número de usuarios que visitan y utilizan nuestro sitio web regularmente.

**Creemos que**, si permitimos que los autores novatos publiquen sus obras en nuestro sitio web, aumentará la diversidad de contenido y atraerá a una audiencia más amplia. **Sabremos que** estamos en lo cierto **cuando** recibamos comentarios positivos de autores novatos y lectores, indicando que nuestro sitio web ha sido útil para mejorar sus habilidades y satisfacer sus necesidades de lectura.

**Creemos que**, si proporcionamos herramientas y recursos por medio de blog posts para que los autores novatos mejoren sus habilidades de escritura y arte, podrán mejorar sus obras y atraer a más lectores. **Sabremos que** estamos en lo cierto **cuando** veamos un aumento en la cantidad y calidad de obras de autores novatos publicadas en nuestro sitio web.

**Creemos que** sí ofrecemos una experiencia de usuario fácil de usar y una interfaz de alta calidad, los lectores estarán más inclinados a usar nuestro sitio web como su fuente principal para leer y publicar mangas y novelas ligeras. **Sabremos que** estamos en lo cierto **cuando** los autores novatos que publicaron sus obras en nuestro sitio web comienzan a ser notados por editoriales importantes y logran publicar sus obras en formatos físicos.

#### 1.2.2.4. Lean UX Canvas
![leanux.jpg](images%2Fleanux.jpg)
## 1.3. Segementos Objetivos
**Creadores de contenido:** Personas que desean crear y compartir sus propias historias, cómics o mangas en línea.

**Lectores de contenido:** Personas que disfrutan de leer historias, cómics o mangas y buscan una plataforma en línea para hacerlo de manera sencilla, rápida y accesible.

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
:v
## 3.2. User Stories
--escribir aquí--
## 3.3. Impact Mapping
--escribir aquí--
## 3.4. Product Backlog
--escribir aquí--

# Capítulo IV: Product Design
## 4.1. Style Guidelines
### 4.1.1. General Style Guidelines
Para el branding de la startup se tendrá a disposición las siguientes imágenes:

![logo startup](images/Startup_logo_No_Fondo2.png)

Por otro lado, el branding que utilizaremos para nuestro servicio (FicUniverse), serán los siguientes modelos:

![logo product](images/ficuniverse-logo.png)

#### **Typography**
Se optó por utilizar la tipografía "Inter", debido a que es simple, fácil de leer y está diseñada para ayudar con la legibilidad de letras minúsculas y mayúsculas para el lector. (Google fonts, s.f.).

#### **Colors**
Brand colors:

![primary color](images/color_primario.png)
![primary color](images/color_secundario.png)
![primary color](images/color_terciario.png)

Para el resto de colores de los aspectos básicos de la aplicación, se utilizará la siguiente paleta de colores:

![color palette](images/paleta_colores.png)

#### **Spacing**

Para el uso de espaciado en nuestra aplicación, usaremos multiplos de 8 en un rango amplio para poder tener a nuestra disposición distintos tamaños para los elementos según sea requerido.

![spacing pixels](images/spacing.png)

#### **Tono de comunicación y lenguaje aplicado**

Al tener como segmento objetivo a jóvenes (en su mayoría) y adultos lectores y/o escritores de fanfics, en un rango de entre 18 y 40 años, hemos optado por utilizar un tono divertido, casual, respetuoso y sereno para que estos puedan sentir que están en una aplicación juvenil, remarcando la energía y emoción al momento de leer sus historias favoritas.

### 4.1.2. Web Style Guidelines

Uno de los aspectos más importantes en el desarrollo web es el uso correcto del responsive design para que la aplicación se visualice perfectamente sin importar el tamaño de la pantalla o dispositivo.

Por esta razón, se decidió realizar el desarrollo de nuestra solución tomando en cuenta los siguientes breakpoints para que el responsive design se muestre correctamente:

| Breakpoint prefix | Minimum width |
|-----------|----------|
| sm | 640px |
| Md | 768px |
| L | 1024px |
| xl | 1280px |
| 2xl | 1536px |

Con respecto a los estándares visuales, se utilizarán los mismos elementos presentados en la sección anterior para lograr uniformidad en todo el uso de nuestra aplicación. Igualmente, las medidas y propiedades presentadas son escalables, manejables y compatibles con el desarrollo de responsive design.

## 4.2. Information Architecture
### 4.2.1. Organization Systems

El área de diseño de nuestra startup decidió enfocarse principalmente en la facilidad o satisfacción que el usuario tendrá al usar nuestra aplicación. Todos los elementos de diseño que hemos utilizado como las paletas de colores, imágenes e íconos, han seguido una tendencia minimalista con el fin de no exponer a los usuarios con tanta información.

### 4.2.1. Organization Systems

En el caso del landing page de nuestra aplicación nos hemos basado en el sistema de organización jerárquica (o “Visual hierarchy”, en inglés). La razón de esta elección es debido al impacto positivo que una página bien distribuida según tamaños, espacios y colores brinda al usuario. Por ejemplo, en la primera vista del landing page se añadirán elementos de tamaños grandes y con colores únicos (como el botón call to action), para captar la atención del visitante. Asimismo, mientras se hace scroll down por la página los tamaños se verán reducidos.

Por otro lado, cuando el usuario entre a la aplicación web en sí, utilizaremos un sistema de organización matricial (en inglés, “Matrix”). Este sistema, a diferencia del jerárquico, es un poco más complejo para el usuario porque está diseñado para que el usuario tome el control de su navegación (tubik, 2017). Sin embargo, al ser una aplicación basada en la lectura y/o escritura fanfics, es necesario dividir las secciones de esta manera para que se pueda tener mejor organizado lo que ofrecemos.

En nuestra aplicación se aplican los cuatro esquemas de categorización de contenido, mediante un sistema de filtros para buscar contenido. Se podrá rotar entre el Alphabetical, Chronological, Topic y Audience schemes.

### 4.2.2. Labeling Systems

Sera realizado de tal forma que las palabras utilizadas sean simples y fáciles de entender. Las etiquetas en la aplicación tendrán un máximo de cuatro palabras.

Esto se verá reflejado cuando hagamos la presentación del landing page y web application, de manera que sea más sencillo entender este concepto y cómo buscamos realizarlo.

### 4.2.3. SEO Tags and Meta Tags

Title: Readr

Description: Registrate y descrubre las mejores historias de tus personajes favoritos, o escribe tus propias historias. Adentrate en Readr!

Keywords: Fanfic, Fanfiction, Lectura, Novelas, Escritura.

Author: Programadores de Lavadoras.
### 4.2.4. Searching Systems

Se optó por implementar una interfaz que resalte los botones  e información principal para llamar la atención de los usuarios más emocionales e invitarlos a entrar en nuestra aplicación. Sin embargo, para los usuarios racionales, se ha brindado información más detallada para que puedan tomar la decisión de utilizar nuestro producto.

Es por estas razones que disponemos de los botones “call to action” que permiten llevar al usuario al registro para empezar a hacer uso de la aplicación. Se han posicionado al inicio y al final del landing page.

Con respecto a la aplicación, vamos a resaltar los subtítulos más importantes que dividen las funcionalidades de esta, para que a los usuarios se les facilite encontrar lo que buscan.

### 4.2.5. Navigation Systems

Se buscará priorizar fluidez a través de todo el contenido de nuestra landing page y aplicación web, con la capacidad de encontrar toda la información necesaria.

De esta manera, el usuario no se sentirá frustrado o confundido por una mala organización de la información.

En consecuencia, todo el diseño trabajado para nuestro proyecto, será enfocado en cumplir estas reglas establecidas.

## 4.3. Landing Page UI Design
### 4.3.1. Landing Page UI Design
![wireframe landing page](images/wireframes_landing.png)

### 4.3.2. Landing Page Mock-up
![mockup landing page](images/mockup_landing.png)

## 4.4. Web Applications UX/UI Design
### 4.4.1. Web Application Wireframes
Register

![wireframe web app 1](images/wireframe_1.png)

Log in

![wireframe web app 2](images/wireframe_2.png)

Home 1

![wireframe web app 3](images/wireframe_3.png)

Home 2

![wireframe web app 4](images/wireframe_4.png)

Home 3

![wireframe web app 5](images/wireframe_5.png)

My profile

![wireframe web app 7](images/wireframe_7.png)

Another person profile

![wireframe web app 8](images/wireframe_8.png)

Creations 1

![wireframe web app 9](images/wireframe_9.png)

Creation 2

![wireframe web app 10](images/wireframe_10.png)

Reading

![wireframe web app 11](images/wireframe_11.png)

Writing

![wireframe web app 12](images/wireframe_12.png)

Authors

![wireframe web app 13](images/wireframe_13.png)


### 4.4.2. Web Application Wireflow Diagrams

User goal 01: Entrar a la aplicación mediante una cuenta
![wireflow diagram 1](images/wd_1.png)

1.	Ingresa a la aplicación web "FicUniverse".
2.	Si tiene una cuenta inicia sesión. Si no, se registra.
3.	Entra a la cuenta.

User goal 02: Ingresar al perfil de usuario
![wireflow diagram 2](images/wd_2.png)

1.	Ingresa a la aplicación web “FicUniverse”.
2.	Hace click en la foto de perfil de usuario.
3.	Visualiza sus datos.

User goal 03: Leer un Fanfic
![wireflow diagram 3](images/wd_3.png)

1.	Ingresa a la aplicación web "FicUniverse".
2.	Abre el menú lateral.
3.	Selecciona la opción “Creaciones”.
4.	Selecciona el fanfic que desee.
5.	Se abre la vista de lectura.

User goal 04: Escribir cualquier Fanfic
![wireflow diagram 4](images/wd_4.png)

1.	Ingresa a la aplicación "FicUniverse".
2.	Abre el menú lateral.
3.	Selecciona la opción “Escribir”.
4.	Edita su obra.

User goal 05: Buscar y seleccionar un autor
![wireflow diagram 5](images/wd_5.png)

1.	Ingresa a la aplicación "FicUniverse".
2.	Abre el menú lateral.
3.	Selecciona la opción “Autores”.
4.	Escoge el autor que desee.
5.	Visualiza su perfil

### 4.4.3. Web Applicationns Mock-up

 Register

![register mock-up](images/Register.png)

Log in

![log in mock-up](images/Log_in.png)

Home 1

![Home1](images/Home1.png)

Home 2

![Home2](images/Home2.png)

Home 3

![Home3](images/Home3.png)

My profile

![MyProfile](images/Myprofile.png)

Another person profile

![AnotherProfile](images/Another-person-profile.png)

Creation 1

![Creations1](images/Creations_1.png)

Creation 2

![Creations2](images/Creations_2.png)

Reading 

![Reading](images/Reading.png)

Writing

![Writing](images/Writing.png)

Authors

![Authors](images/Authors.png)

### 4.4.4. Web Application User Flow Diagrams

User Flow 01: Entrar a la aplicación mediante una cuenta

![UserFlow1](images/uf_1.png)

- Happy path: Puede crear una cuenta o iniciar sesión satisfactoriamente
- Unhappy path: No ingresa los datos correctamentes

User Flow 02: Ingresar al perfil de usuario
![UserFlow2](images/uf_2.png)


- Happy path: Puede visualizar sus datos del perfil
- Unhappy path: No ingresa a su perfil o no se visualizan los datos

User Flow 03: Leer un fanfic
- Happy path: Puede leer la creación seleccionada
- Unhappy path: No carga la selección o no se muestra la información

User Flow 04: Escribir cualquier obra

![UserFlow4](images/uf_4.png)

- Ingresa a la aplicación “FicUniverse”.
- Selecciona la opción “Escribir”.
- Edita su obra.

User goal 05: Buscar y seleccionar un autor

![UserFlow5](images/uf_5.png)

- Ingresa a la aplicación “FicUniverse”.
- Selecciona la opción “Autores”.
- Escoge el autor que desee.
- Visualiza su perfil

## 4.5. Web Application Prototyping

Para la creación del prototipo de la Web Application nos hemos enfocado en las funcionalidades más importantes de nuestra aplicación. Es decir, poder leer o escribir libros, cómics o mangas. De igual manera, hemos agregado otras funcionalidades como vista de perfiles o autores para que se entienda mejor cómo funciona el apartado social de la aplicación.

![Prototyping](images/prototyping.png)

## 4.6. Domain-Driven Software Architecture

Para esta sección hemos empleado los principios de Domain-Driven Design (DDD) en conjunto con el modelo de visualización de la arquitectura de software C4 (Context, container, components and code).

**Herramientas del domain-driven design:**

A continuación, se muestran los principales ejemplos del uso de las herramientas de DDD aplicados a nuestro dominio, tales como el Storytelling, Event Storming, Domain message flow modeling y Bounded context canvas.

**Storytelling:**

Publishing a literary product:

![storitelling1](images/st1.png)

Looking for a literary product:

![storitelling2](images/st2.png)

Reading a literary producto
 
![storitelling3](images/st3.png)

**Event storming:**

Leyenda

![eventStorming1](images/e1.png)

Publicación de productos literarios

![eventStorming2](images/e2.png)

Visualizacion de productos literarios

![eventStorming3](images/e3.png)

Lectura de productos literarios

![eventStorming4](images/e4.png)

**Domain Message Flow Modeling:**

Elementos

![eventStorming4](images/dm1.png)

Escenario: Publicación de un producto literario nuevo

![DMFM](images/dm2.png)

**Bounded context canvas:**

Leyenda de colaboradores

![BCC](images/c1.png)

Publicación de un producto literario

![BCC](images/c2.png)


En esta sección se especifican los Ubiquitous Language para cada subdominio del negocio. Sin embargo, no es necesario especificarlo para todos ya que el negocio no presenta términos complejos, sino palabras claves conocidas por todos los involucrados.

### 4.6.1. Software Architecture Context Diagram

Este diagrama corresponde al diagrama de contextos del modelo C4. En él se detalla los principales usuarios, nuestro sistema y los sistemas externos que emplearemos. Asimismo, se muestra la relación entre cada elemento.

![contextDiagram](images/context_d.png)

Landscape diagram:

![contextDiagram](images/landscape.png)

### 4.6.2. Software Architecture Container Diagrams

Este diagrama corresponde al diagrama de contenedores del modelo C4. Aquí se especifican los contenedores y bounded context que conforman nuestro sistema Read-R, tomando elementos como el Landing, el Api Rest, la base de datos, etc. Y detalla en qué contexto están relacionados los sistemas externos con nuestro sistema de software.

![containerDiagram](images/container_d.png)

### 4.6.3. Software Architecture Components Diagram

Estos diagramas corresponden a los diagramas de componentes del modelo C4. Aquí se detalla mucho más cada bounded context que conforma nuestro software Read-R, mostrando sus componentes y la relación entre ellos.

Account Context:

![componentDiagram](images/component1.png)

Visualization Context:

![componentDiagram](images/component2.png)

Publishing context:

![componentDiagram](images/component3.png)

Reading context:

![componentDiagram](images/component4.png)

Payment context:

![componentDiagram](images/component5.png)

## 4.7. Software Object-Oriented Design
### 4.7.1. Class Diagrams

![classDiagram](images/class_d.png)

### 4.7.2. Class Dictionary

| **Plan** | |
| --- | --- |
| **Atributo** | **Descripción** |
| - name: String | El nombre que recibe el plan (ej. Entry Readr o Expert Readr). |
| - description: String | La descripción sobre el plan elaborado |

| **PlanPrice** | |
| --- | --- |
| **Atributo** | **Descripción** |
| - frequency: Frequency | Un objeto de la clase Frequency que encapsula la lógica que abarca la frecuencia en la que es vigente el Plan. |
| - price: Money | Un objeto de la clase Price que encapsula la lógica que abarca un valor monetario. Incluye la referencia al currency y valor correspondiente. |

| **PlanDiscount** | |
| --- | --- |
| **Atributo** | **Descripción** |
| - percentApplied: float | El valor del porcentaje de descuento que se aplica al precio del plan. |
| - maxAmountOfUsages: int | Un entero que permite conocer cuántos usos como máximo tiene el descuento |
| - amountOfUsages: int | Un entero que indica cuántas veces ha sido utilizado el descuento. |
| **Método** | **Descripción** |
| + isAvailable(): boolean | Un método que permite determinar si el descuento está disponible. |
| + decreaseUsages(quantity: int): void | Un método que permite decrementar la cantidad de usos del descuento. |
| + increaseUsages(quantity: int): void | Un método que permite incrementar la cantidad de usos del descuento. |

| **FeatureActivatable** | |
| --- | --- |
| **Atributo** | **Descripción** |
| - value: boolean | Un boolean que permite conocer si la feature está activa o no. |
| **Método** | **Descripción** |
| + getDescription(): String | Retorna la descripción del feature. En este caso, se planteó como FeatureActivatable el disponer de acceso ilimitado al contenido. |

| **FeatureSingleAccountableValue** | |
| --- | --- |
| **Atributo** | **Descripción** |
| - value: number | Un valor que permite conocer un límite que se puede establecer sobre una característica. |
| **Método** | **Descripción** |
| + getDescription(): String | Retorna la descripción del feature. En este caso, se planteó como FeatureSingleAccountableValue el disponer de un límite de capítulos que se pueden leer al ser usuario free. |

| **Subscription** | |
| --- | --- |
| **Atributo** | **Descripción** |
| - startedAt: Date | La fecha en la que inició la suscripción. |
| - finishedAt: Date | La fecha en la que terminó la suscripción. |
| **Método** | **Descripción** |
| + isActive(): boolean | Un boolean que permite conocer si la suscripción está activa |

| **User** | | 
| --- | --- |
| **Atributo** | **Descripción** |
| - username: String | El nombre de usuario que será su identificador dentro de la aplicación entre los demás usuarios. |
| - email: String | El correo del usuario. |
| - password: String | La contraseña hasheada. |
| - account: Account | Una referencia a la cuenta a la cuál se está asociado el usuario. |
| **Método** | **Descripción** |
| + closeAccount(): void | Un método para cerrar la cuenta a la que se está asociado. |
| + isAccountOwner(): boolean | Un método que permitirá conocer si el usuario fue el mismo que creó la cuenta (ej. no proviene de una organización). |

| **Account** | | 
| --- | --- |
| **Atributo** | **Descripción** |
| - firstName: String | El nombre de la persona que utiliza la cuenta. |
| - lastName: String | El apellido de la persona que utiliza la cuenta. |
| - createdBy: User | Una referencia al usuario que creó su cuenta. |
| **Método** | **Descripción** |
| + changeSubscription(newPlan: Plan): void | Un método que le permitirá cambiar de la suscripción a la que está sujeta la cuenta. |
| + getCurrentSubscription(): Subscription | Un método que permitirá acceder a la suscripción actual de la cuenta. |
| + changeOwner(newOwner: User): void | Un método para cambiar el propietario de la cuenta (quién la creó). |

| **Book** | |
| --- | --- |
| **Atributo** | **Descripción** |
| - title: String | El título del libro. |
| - publishedDate: Date | La fecha en la que se publicó el libro. |
| - author: Author | Una referencia al autor del libro. |
| - synopsis: String | La sinopsis del libro. |
| - language: String | El lenguaje en el que se escribió el libro. |
| - status: BookStatusType | Indica en qué estado se encuentra el libro (publicándose, en pausa, terminado, cancelado). |
| - genres: List\<Genre\> | Una lista de los géneros en los que se clasifica el libro. (ej. Ficción, Aventura, Sci-Fi, etc.). |
| - chapters: List\<Chapter\> | La lista de capítulos que conforman al libro en su totalidad. |
| **Método** | **Descripción** |
| + getNumberOfChapters(): int | Un método que permitirá conocer cuántos capítulos en total contiene el libro. |
| + getNumberOfPages(): int | Un método que permitirá conocer la cantidad total de páginas que contiene el libro. |

| **Saga** | |
| --- | --- |
| **Atributo** | **Descripción** |
| - title: String | El título que recibe la saga. |
| - books: List\<Book\> | Los libros que componen la saga. |
| - synopsis: String | La sinopsis de la saga. |
| - language: String | El lenguaje en el que se encuentra la saga. |
| - status: SagaStatusType | Indica el estado en el que se encuentra la saga (publicándose, en pausa, terminado o cancelado). |

| **BookRepository** | |
| --- | --- |
| **Atributo** | **Descripción** |
| - repository: DatabaseManager | El repositorio que proviene de la base de datos. |
| **Método** | **Descripción** |
| + addBook(newBook: Book): void | El método que nos permitirá agregar un nuevo libro al repositorio. |
| + removeBook(bookToErase: Book) | El método nos permitirá eliminar un libro del repositorio |
| + getBooks(): List\<Book\> | El método que nos permitirá obtener la lista completa de los libros. |

| **BlogPost** | |
| --- | --- |
| **Atributo** | **Descripción** |
| - title: Author | Guarda una referencia al autor del blog post. |
| - tags: List\<Tags\> | La lista de tags a la que pertenece el blogspot (ej. educación, dibujo, técnicas, tips, consulta, etc.). |
| - documentContentUrl: String | Guarda el URL que hace referencia al documento en markdown que se renderiza para mostrar el blog post. |
| - comments: List\<Comment\> | La lista de comentarios que hay en el blog post. |

## 4.8. Database Design

### 4.8.1. Database Diagram

![dataBase_Diagram](images/database_d.png)

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
Para lograr un proyecto exitoso, resulta vital realizar todo el proceso de documentación y diseño de la aplicación que se busca solucionar. En este sentido, destacamos la gran importancia que supone la elaboración de entrevistas, ya que estas nos permiten comprender y reconocer qué es lo que verdaderamente espera el usuario encontrar en nuestra aplicación.

Asimismo, es fundamental tener una base sólida y una organización clara sobre cómo llegar del punto inicial de planteamiento, al punto final que será la implementación del producto de software. Es por ello por lo que recomendamos encarecidamente realizar buenos diagramas C4, UML y de DB, ya que estos son la base fundamental sobre la que se trabajará en los posteriores entregables y, de tener un buen diseño, se podrán adaptar a las necesidades que surjan al momento de llevar a cabo la implementación.

---
# Bibliografía

Inter. (s.f.). Google Fonts. Recuperado 26 de marzo de 2023, de https://fonts.google.com/specimen/Inter

La República. (2022, 7 marzo). Día Mundial de la Lectura: ¿por qué es importante y qué beneficios brinda leer a menudo? Recuperado 27 de marzo de 2023, de https://larepublica.pe/datos-lr/respuestas/2022/03/07/dia-mundial-de-la-lectura-por-que-es-importante-y-que-beneficios-brinda-la-lectura-libros-evat

Staff, F. (2021, 6 noviembre). Peruanos leen un libro al año en promedio, según estudio. Forbes Perú. Recuperado 26 de marzo de 2023, de https://forbes.pe/forbes-life/2021-11-06/peruanos-leen-un-libro-al-ano-en-promedio-segun-estudio/

T. (2018, 21 junio). Information Architecture. Basics for Designers. - UX Planet. Medium. https://uxplanet.org/information-architecture-basics-for-designers-b5d43df62e20

---
# Anexos
Lean UX Canva: https://miro.com/app/board/uXjVMmr7aIo=/?share_link_id=353946713036
