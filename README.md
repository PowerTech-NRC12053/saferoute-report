![Logo UPC](assets/images/LogoUpc.png)

**Nombre de la Universidad:** Universidad Peruana de Ciencias Aplicadas
**Facultad:** Ingeniería  
**Carrera:** Ingeniería de Software
**Ciclo:** 2026-10  

**Código del curso:** 1ASI0730  
**Nombre del curso:** Aplicaciones Web 
**NRC:** 12053  
**Nombre del profesor:** Efraín Ricardo Bautista Ubillús  

**"Informe de Trabajo Final"** 
**Nombre del startup:** PowerTech  
**Nombre del producto:** SafeDrive  

**Relación de integrantes:**

* U202424059 - De La Cruz De Los Santos, Mathias Marcelo
* U202316852 - Ortega Quintana, Jose Zacarias
* U20241D922 - Quispe Serrano, Julio Frank
* U202415551 - Ramirez Ruiz, Nickolas
* U20211D989 - Vallejo Trujillo, Fabio Cesar

##### Abril, 2026

---

## Registro de Versiones del Informe

| Avance | Fecha | Autor | Descripción de Modificación |
| :--- | :--- | :--- | :--- |
| AV1 | --/04/2026 | "-" | "-" |

---

## Project Report Collaboration Insights

El equipo ha utilizado un flujo de trabajo en github: [safedrive-report](https://github.com/FiveTech-NRC11896/safedrive-report)

---

## Contenido

1. [Student Outcome](#student-outcome)
2. [Capítulo I: Introducción](#capítulo-i-introducción)
3. [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)
4. [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
5. [Capítulo IV: Product Design](#capítulo-iv-product-design)
6. [Capítulo V: Product Implementation, Validation & Deployment](#capítulo-v-product-implementation-validation--deployment)
7. [Conclusiones](#conclusiones)
8. [Bibliografía](#bibliografía)

---

## Student Outcome

**ABET - EAC - Student Outcome 5:** Capacidad de funcionar efectivamente en un equipo.

---

## Capítulo I: Introducción

### 1.1. Startup Profile

#### 1.1.1. Descripción de la Startup

FiveTech es una startup de tecnología conformada por estudiantes de Ingeniería de Software de la Universidad Peruana de Ciencias Aplicadas (UPC), orientada al desarrollo de soluciones digitales que resuelven problemas reales en sectores con baja penetración tecnológica. Nació con la convicción de que la seguridad de los niños durante su traslado escolar no debería depender de llamadas telefónicas, mensajes de WhatsApp o registros manuales en papel.
Nuestra propuesta de valor se materializa en SafeRoute, una plataforma web de movilidad institucional inteligente diseñada para digitalizar y optimizar la gestión del transporte escolar. SafeRoute permite a cualquier organización de transporte escolar ya sea un grupo de padres que se organizaron para compartir una movilidad, un conductor independiente o una pequeña empresa del rubro que busquen centralizar la administración de sus rutas, conductores, alumnos y la comunicación en un solo lugar.

#### 1.1.2. Perfiles de integrantes del equipo

|                Foto                | Apellidos y Nombres         |    Código     | Carrera                | Resumen                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| :--------------------------------: | :-------------------------- | :-----------: | :--------------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|              ![foto]               | [Apellido 1], [Nombre 1]    | [U20XXXXXXXX] | Ingeniería de Software | [Descripción de conocimientos técnicos y habilidades que aporta al equipo]                                                                                                                                                                                                                                                                                                                                                                             |
|              ![foto]               | [Apellido 2], [Nombre 2]    | [U20XXXXXXXX] | Ingeniería de Software | [Descripción de conocimientos técnicos y habilidades que aporta al equipo]                                                                                                                                                                                                                                                                                                                                                                             |
| ![foto](assets/images/FrankFT.png) | Quispe Serrano, Julio Frank | [U20241D922]  | Ingeniería de Software | Mi nombre es Julio Frank Quispe Serrano, tengo 20 años,actualmente estoy cursando el 5to ciclo de la carrera de Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas. Soy un apasionado por la programación, el gym y explorador de música en distintos géneros. Mi aporte en este grupo será el de brindar soluciones prácticas y eficientes ante situaciones de adversidad que estanquen la fluidez de la elaboración del trabajo. |
| ![foto](assets/images/MathiasFt.jpg) | De la Cruz De los Santos, Mathias Marcelo   | [U202424059] | Ingeniería de Software | Soy estudiante de la carrera de Ingeniería de Software y actualmente me encuentro cursando el 5to ciclo de la carrera en la Universidad Peruana de Ciencias Aplicadas. Me considero un fanático de la programación, del futbol y los videojuegos. Considero que puedo aportar alequipo y al proyecto mis conocimientos técnicos, además de considerarme una persona disciplinada, responsable y que valora el trabajo en equipo.                                                                                                                                                                                                                                                                                                                                                  |
|              ![foto]               | [Apellido 5], [Nombre 5]    | [U20XXXXXXXX] | Ingeniería de Software | [Descripción de conocimientos técnicos y habilidades que aporta al equipo]                                                                                                                                                                                                                                                                                                                                                                             |

### 1.2. Solution Profile

#### 1.2.1 Antecedentes y problemática

Who (¿Quiénes son los afectados?)
Los afectados son dos grupos claramente identificables. En primer lugar, los padres de familia con hijos en nivel inicial, kínder y primaria que utilizan servicios de transporte escolar privado, quienes no cuentan con información en tiempo real sobre el estado del traslado de sus hijos. En segundo lugar, los conductores de transporte escolar independientes o pertenecientes a pequeñas empresas que gestionan múltiples alumnos y rutas sin herramientas digitales de apoyo.

What (¿Cuál es el problema?)
El transporte escolar privado en el Perú opera en su gran mayoría de forma tradicional y sin soporte tecnológico. La comunicación entre padres y conductores depende de canales no estructurados como llamadas telefónicas y grupos de WhatsApp, lo que genera desorganización, pérdida de información y una sensación constante de incertidumbre en los padres respecto a la seguridad de sus hijos. Por su parte, los conductores y administradores del servicio carecen de herramientas para registrar asistencia, gestionar rutas, reportar incidencias y llevar un historial ordenado de cada trayecto.

Where (¿Dónde ocurre?)
El problema se presenta principalmente en zonas urbanas de Lima Metropolitana, donde la demanda de transporte escolar privado es alta y la oferta opera de manera fragmentada e incluso a veces informal. Sin embargo, la problemática es extensible a cualquier ciudad del Perú con alta densidad de centros educativos privados y colegios que no cuentan con flota propia.

When (¿Cuándo ocurre?)
El problema se manifiesta de forma recurrente durante los horarios de entrada y salida escolar, típicamente entre las 6:00 a.m. y 8:30 a.m., y entre las 12:30 p.m. y 5:00 p.m. Es en estos momentos cuando la falta de información en tiempo real genera mayor ansiedad en los padres y mayor presión operativa en los conductores.

Why (¿Por qué es un problema?)
La ausencia de digitalización en este sector genera consecuencias concretas, por ejemplo los padres no saben si su hijo abordó la movilidad, si llegó al colegio o si ocurrió algún incidente en el camino. Los conductores cometen errores en las paradas, olvidan recoger alumnos o no tienen cómo comunicar retrasos de forma ordenada. Los administradores del servicio pierden tiempo valioso coordinando manualmente lo que podría automatizarse, y no cuentan con registros históricos que les permitan mejorar la operación.

How (¿Cómo se manifiesta?)
Se manifiesta en llamadas y mensajes constantes de padres al conductor durante el trayecto, listas de alumnos escritas en papel o en hojas de cálculo no compartidas, ausencia de registros de incidencias, imposibilidad de verificar el cumplimiento de las paradas, y falta de trazabilidad sobre qué alumnos abordaron o no en cada viaje.

How much (¿Cuál es la magnitud?)
Si bien no existen datos precisos y actualizados que cuantifiquen de forma específica el mercado del transporte escolar privado en el Perú, los indicadores educativos y de transporte disponibles permiten dimensionar la magnitud del problema.
Según el Censo Educativo 2022-2023 del Ministerio de Educación (MINEDU, 2023), en Lima Metropolitana existen aproximadamente 1.9 millones de estudiantes distribuidos en cerca de 7,602 instituciones educativas, de las cuales el 74% son de gestión privada. Esta alta concentración de colegios privados implica que muchas familias dependen de servicios externos de transporte escolar, dado que pocas instituciones cuentan con flotas propias.
Este panorama se ve agravado por una reducción en la oferta formal del servicio. Según la Autoridad de Transporte Urbano para Lima y Callao (ATU, 2024), la cantidad de movilidades escolares autorizadas disminuyó en un 25% en solo un año, lo que sugiere un incremento en la informalidad del sector y, con ello, una mayor ausencia de herramientas de control y monitoreo sobre el servicio que reciben los menores.
Respecto a la seguridad, la Superintendencia de Transporte Terrestre de Personas, Carga y Mercancías (SUTRAN, 2024) ejecutó campañas de sensibilización que alcanzaron a más de 47,000 escolares, evidenciando que la seguridad en el transporte escolar continúa siendo una preocupación activa para las autoridades. Sin embargo, no se dispone públicamente de cifras desagregadas de incidentes específicos en este sector entre 2022 y 2025.

**Figura 1** Distribución de estudiantes de Educación Inicial y Primaria en instituciones privadas y zonas urbanas en el Perú
![CensoEstudiantil](/assets/images/CensoEstudiantil.png)
*Nota.* Adaptado de Resultados del Censo Educativo 2022 (p. 12), por Ministerio de Educación, 2023.

#### 1.2.2 Lean UX Process

##### 1.2.2.1. Lean UX Problem Statements

El transporte escolar privado en el Perú opera mayoritariamente de forma informal, coordinándose mediante llamadas telefónicas, mensajes de WhatsApp y registros manuales en hojas privadas. En este contexto, tanto los padres de familia como los transportistas escolares enfrentan dificultades que comprometen la seguridad y eficiencia del servicio.
Hemos observado un factor crítico que afecta a este ecosistema, los padres de familia no cuentan con visibilidad sobre el trayecto de sus hijos, mientras que los transportistas carecen de herramientas digitales para gestionar rutas, alumnos e incidencias de forma estructurada. Estas dos necesidades son interdependientes, mientras que por un lado los padres necesitan visibilidad, y por el otro los transportistas no tienen los medios para proporcionársela.
¿Cómo podemos desarrollar una plataforma que permita a los transportistas escolares gestionar su operación de forma digital, mientras ofrece simultáneamente a los padres de familia la visibilidad y tranquilidad que necesitan sobre el traslado de sus hijos?

##### 1.2.2.2. Lean UX Assumptions

**Business Assumptions**
- Creemos que existe demanda suficiente para digitalizar el transporte escolar privado en Lima Metropolitana, dado que opera mayoritariamente de forma tradicional y sin soporte tecnológico.
- Creemos que los padres de familia adoptarán la plataforma si el proceso de incorporación es simple y la información que reciben sobre el trayecto de sus hijos es clara y confiable.
- Creemos que los transportistas adoptarán la plataforma si la interfaz operativa durante el trayecto es simple, rápida y no distrae la conducción.
- Creemos que el modelo de suscripción por planes escalonados Básico, Intermedio y Completo permite capturar tanto a grupos pequeños de padres organizados como a empresas de transporte escolar con flotas más grandes.
- Creemos que SafeRoute transmite ahorro de tiempo, reduccion de errores y confianza al transporte de los escolares frente a los padres de familia, lo que justifica el costo de la suscripción.
- Sabremos que estamos equivocados si los administradores abandonan la plataforma en los primeros 60 días por considerar que la curva de aprendizaje es demasiado alta o que el valor percibido no justifica el costo.

**User Assumptions**
- ¿Quién es el usuario? 
Los padres de familia con hijos en nivel inicial, kínder y primaria que utilizan un servicio de transporte escolar ya contratado, y los transportistas escolares  como por ejemplo los conductores independientes o responsables de pequeñas empresas que operan ese servicio. Dentro de la plataforma, cualquiera de estos segmentos puede asumir además el rol de Administrador.
- ¿Dónde encaja nuestro producto en su vida? 
Para el transportista, en su jornada laboral operativa diaria. Para el padre, en los momentos de entrada y salida escolar de sus hijos.
- ¿Qué problemas resuelve? 
Elimina la gestión manual y la comunicación no estructurada del transporte escolar, proporcionando al transportista herramientas operativas digitales y al padre visibilidad del trayecto de sus hijos.
- ¿Cuándo y cómo es usado? 
El transportista lo usa durante cada trayecto para gestionar abordajes, paradas e incidencias. El padre lo consulta en los horarios de traslado escolar para monitorear el estado del viaje de sus hijos.
- ¿Qué características son importantes? 
Registro de abordaje por alumno, visualización de ruta y paradas, reporte de incidencias, historial de trayectos y gestión centralizada de usuarios y rutas.
- ¿Cómo debe verse y comportarse? 
Interfaz limpia, responsiva, rápida y accesible (a11y), disponible en español e inglés (i18n), e intuitiva para usuarios con distintos niveles de familiaridad tecnológica.

##### 1.2.2.3. Lean UX Hypothesis Statements

- Hipótesis 1: "Creemos que lograremos que los padres de familia reduzcan su incertidumbre durante el traslado escolar si ofrecemos a los padres registrados en SafeRoute una vista del estado del trayecto con marcación de abordaje por alumno y visualización de paradas.
Sabremos que esto es verdad cuando veamos que al menos el 70% de los padres activos consulten el estado del trayecto al menos una vez por día durante las primeras 4 semanas de uso."

- Hipótesis 2: "Creemos que lograremos que los transportistas gestionen el trayecto con menos errores y menor carga operativa si ofrecemos a los conductores registrados en SafeRoute una interfaz operativa simple para marcar abordajes, seguir paradas y reportar incidencias durante el viaje.
Sabremos que esto es verdad cuando veamos que el 80% de los trayectos registrados incluyan el check-list de abordaje completado durante las primeras 4 semanas de operación."

- Hipótesis 3: "Creemos que lograremos que los administradores centralicen la gestión de su servicio en SafeRoute si ofrecemos a los administradores del plan Básico un panel único para registrar usuarios, conductores, hijos, asignaciones y rutas. Sabremos que esto es verdad cuando veamos que al menos el 75% de los administradores registren la totalidad de sus usuarios y rutas dentro de los primeros 15 días tras el onboarding."

- Hipótesis 4: "Creemos que lograremos que los administradores escalen su plan de suscripción si demostramos a los administradores de los planes inferiores que las funcionalidades de los plan superiores reducen significativamente el tiempo de coordinación del servicio. Sabremos que esto es verdad cuando veamos que al menos el 20% de los administradores de los planes Básico o Intermedio actualicen al algun plan superior dentro de los primeros 3 meses de uso."

##### 1.2.2.4. Lean UX Canvas

| Sección | Contenido |
| :----- | :--------- |
| 1. Business Problem | El transporte escolar privado en el Perú opera de forma tradicional y sin soporte tecnológico. Los padres no tienen visibilidad sobre el trayecto de sus hijos y los transportistas gestionan su operación con llamadas, WhatsApp y hojas privadas, lo que genera errores, ineficiencia y una experiencia de servicio poco confiable.|
| 2. Business Outcomes| Lograr que el 75% de administradores completen el registro de su operación en los primeros 15 días. Retener al 80% de suscriptores activos durante los primeros 3 meses. Alcanzar una tasa de upgrade del plan Básico al Intermedio del 20% en los primeros 3 meses de uso.|
| 3. Users | Los segmentos que interactúan con SafeRoute son los padres de familia con hijos en nivel inicial, kínder y primaria que utilizan un servicio de transporte escolar ya contratado, y los transportistas escolares conductores independientes o responsables de pequeñas empresas que operan ese servicio. Cualquiera de estos puede asumir además el rol de Administrador dentro de la plataforma.|
| 4. User Outcomes & Benefits | Los padres buscan reducir su incertidumbre sobre el trayecto de sus hijos, pudiendo monitorear el estado del viaje sin necesidad de interrumpir al conductor. Los transportistas buscan gestionar rutas, alumnos e incidencias de forma digital, reduciendo errores operativos y proyectando mayor profesionalismo frente a las familias. Quienes asumen el rol de administrador buscan centralizar toda la operación del servicio en un solo panel, eliminando la coordinación manual y el uso de herramientas desconectadas.|
| 5. Solution Ideas | Ofrecemos un panel de administración de usuarios, conductores, hijos y rutas. Tambien, Check-list de abordaje digital por conductor. Vista de paradas y estado del trayecto para padres. Registro de incidencias por ruta. Historial de trayectos por comunidad de ruta. Seguimiento GPS en tiempo real (plan Completo). Apertura a integración IoT futura.|
| 6. Hypotheses | - Si ofrecemos a los padres una vista de estado del trayecto, al menos el 70% la consultará diariamente en las primeras 4 semanas.<br> - Si ofrecemos al conductor una interfaz operativa simple, el 80% de los trayectos tendrán el check-list completado en las primeras 4 semanas.<br> - Si ofrecemos al administrador un panel único de gestión, el 75% completará su registro en los primeros 15 días.<br> - Si demostramos el valor del plan Intermedio, el 20% de administradores del plan Básico harán upgrade en los primeros 3 meses.|
| 7. What's the most important thing we need to learn first? | ¿El administrador del servicio percibe suficiente valor en SafeRoute como para abandonar los métodos informales actuales y pagar una suscripción mensual?|
| 8. What's the least amount of work we need to do to learn the next most important thing? | Realizar entrevistas con 3 a 5 administradores de servicios de transporte escolar (padres representantes o transportistas independientes) para validar su disposición al cambio y las funcionalidades que consideran imprescindibles antes de desarrollar el MVP.|

### 1.3. Segmentos objetivo

SafeRoute está dirigido a dos segmentos que forman parte del ecosistema del transporte escolar privado en Lima Metropolitana.

- **Segmento 1: Padres de Familia**
El primer segmento está conformado por padres de familia o apoderados con hijos en nivel inicial, kínder y primaria que utilizan un servicio de transporte escolar privado ya contratado. Se trata de personas que han delegado el traslado de sus hijos a un tercero y que, durante el trayecto, no cuentan con información estructurada sobre el estado del viaje. Este segmento no está delimitado por un nivel socioeconómico específico, sino por la condición de tener hijos en edad escolar que usan transporte privado y de contar con acceso a internet desde un dispositivo con navegador web. Su principal motivación al usar SafeRoute es, precisamente, reducir la incertidumbre que genera no saber si sus hijos abordaron con seguridad, en qué parte del recorrido se encuentran o si ocurrió alguna novedad durante el viaje. Para dimensionar este segmento, según el Censo Educativo 2022-2023, en Lima Metropolitana existen aproximadamente 1.9 millones de estudiantes distribuidos en cerca de 7,602 instituciones educativas, de las cuales el 74% son de gestión privada (Ministerio de Educación, 2023). Esta alta proporción de colegios privados implica que una parte significativa de las familias limeñas depende de servicios externos de transporte escolar, dado que pocas instituciones cuentan con flotas propias.

- **Segmento 1: Transportistas Escolares**
El segundo segmento está conformado por las personas o entidades que operan el servicio de transporte escolar privado. Dentro de este segmento conviven tres perfiles distintos. El primero corresponde a personas independientes que ofrecen el servicio de forma autónoma. El segundo agrupa a conductores que han sido asignados para operar una movilidad organizada por un conjunto de familias. El tercero engloba a los responsables de pequeñas empresas de transporte escolar que cuentan con una flota de vehículos y conductores a su cargo. A pesar de sus diferencias, todos comparten un factor común, pues operan sin herramientas digitales especializadas, apoyándose en métodos manuales e informales para gestionar una actividad que involucra directamente la seguridad de menores. La relevancia de este segmento se ve reflejada en que la cantidad de movilidades escolares autorizadas en Lima disminuyó en un 25% en solo un año, lo que evidencia un incremento en la informalidad del sector y, con ello, una mayor ausencia de mecanismos de control y monitoreo sobre el servicio que reciben los menores (Autoridad de Transporte Urbano para Lima y Callao, 2024). Adicionalmente, la Superintendencia de Transporte Terrestre de Personas, Carga y Mercancías ejecutó en 2024 campañas de sensibilización que alcanzaron a más de 47,000 escolares, lo que confirma que la seguridad en este sector continúa siendo una preocupación activa para las autoridades (SUTRAN, 2024). Por ello, la principal motivación de este segmento al usar SafeRoute es digitalizar y profesionalizar su operación, reducir los errores en la gestión de rutas y alumnos, y ofrecer a las familias que atienden una experiencia de servicio más confiable y transparente.

---

## Capítulo II: Requirements Elicitation & Analysis

### 2.1. Competidores

#### 2.1.1. Análisis competitivo

#### 2.1.2. Estrategias y tácticas frente a competidores

### 2.2. Entrevistas

#### 2.2.1. Diseño de entrevistas

#### 2.2.2. Registro de entrevistas

#### 2.2.3. Análisis de entrevistas

### 2.3. Needfinding

#### 2.3.1. User Personas

#### 2.3.2. User Task Matrix

#### 2.3.3. User Journey Mapping

#### 2.3.4. Empathy Mapping

### 2.4. Big Picture Event Storming

### 2.5. Ubiquitous Language


---

## Capítulo III: Requirements Specification

### 3.1. User Stories

### 3.2. Impact Mapping

### 3.3. Product Backlog


---

## Capítulo IV: Product Design

### 4.1. Style Guidelines

#### 4.1.1. General Style Guidelines

El diseño de SafeRoute se fundamenta en decisiones visuales estratégicas destinadas a proyectar seguridad, fiabilidad y modernidad. El objetivo principal es construir una experiencia de usuario que genere confianza inmediata, tanto en los padres de familia que buscan tranquilidad como en los transportistas que necesitan eficiencia.

#### Colores
La selección cromática de SafeRoute no es meramente estética; responde a una psicología del color aplicada a la seguridad y el entorno escolar, garantizando accesibilidad y jerarquía visual. Cada tono desempeña una función específica en la interfaz:

![Foto de paleta de colores](assets/images/paleta-colores.png)

- Azul Noche Profundo - #1A1A2E: Este color transmite autoridad, seriedad máxima y seguridad corporativa. En SafeRoute, se utiliza estratégicamente en el texto principal del logotipo y como fondo en secciones críticas de cierre, como el CTA final y el footer, para anclar la percepción de una plataforma robusta y confiable.

- Azul Marino - #1D3F6E y #16305a:Esta gama de azules medios y oscuros refuerza la percepción de una herramienta tecnológica, profesional y estable. Se emplean principalmente en títulos secundarios y elementos estructurales clave, estableciendo la jerarquía visual y la formalidad que el servicio requiere.

- Naranja Ámbar - #FFB74D: Este color funciona como el punto focal de acento y acción principal en SafeRoute, aportando vitalidad, energía y una conexión visual amigable con el entorno escolar. Se reserva exclusivamente para incentivar la acción en los botones de llamado a la acción principales y elementos destacados.

- Verde Éxito - #22C55E: Este color se asocia directamente con estados positivos, confirmación y seguridad. Se emplea de forma sutil en indicadores de estado (como el check en el mockup del teléfono) para validar acciones exitosas y reforzar la tranquilidad del usuario.

- Gris Neutro - #6B7280: Se ha seleccionado para el texto de cuerpo y párrafos largos. Ofrece una legibilidad excelente sobre fondos claros, reduciendo la fatiga visual y aportando un acabado limpio y moderno.

- Gris Claro y Neutral - #F8F9FB y #F4F7FA: Estos tonos muy claros se utilizan como fondos alternos para delimitar secciones (como el Hero, Planes o ¿Cómo funciona?). Su función es estructurar la página, proporcionando descansos visuales y una sensación de limpieza tecnológica y amplitud.

#### Tipografía

Se seleccionó la tipografía “Plus Jakarta Sans” como fuente principal para los títulos de la plataforma de SafeRoute por su estilo geométrico moderno y su capacidad para captar la atención del usuario con un toque tecnológico pero amigable. Se utiliza en pesos altos para asegurar que los encabezados sean visualmente impactantes, sólidos y de fácil lectura.

![Foto de ejemplo Jakarta Sans](assets/images/ejemplo-jakarta.png)

Asimismo, optamos por la tipografía “DM Sans” como fuente secundaria para los textos de cuerpo y navegación por su diseño extremadamente legible, limpio y neutro. Su apariencia estética y claridad garantizan una experiencia de uso accesible y agradable, reduciendo la fatiga visual del usuario al leer información detallada sobre funciones o planes.

![Foto de ejemplo DM Sans](assets/images/ejemplo-dm.png)

En cuanto al tamaño, se utiliza jerárquicamente en toda la página para resaltar títulos principales, botones de acción y texto de soporte. Los tamaños más grandes en los encabezados guían al usuario rápidamente por los puntos clave del mensaje, mientras que los más pequeños en los párrafos aseguran la comprensión y la eficiencia en la lectura de detalles secundarios.

#### Branding

El branding de SafeRoute está diseñado para reflejar simplicidad, confianza y profesionalismo. El logo y los íconos adoptan un enfoque minimalista, con líneas claras y formas simples que comunican el propósito de seguridad de la plataforma. El diseño incluye un símbolo que combina un escudo y un marcador de posición, representado de tal manera que simboliza protección y monitoreo con una apariencia limpia que es fácilmente reconocible, tanto en entornos web como móviles.

<img src="assets/images/logo.jpeg" alt="Foto de logo" width="400px" />

#### Espaciado

El diseño de SafeRoute utiliza una estrategia de espacios en blanco diseñada para transmitir orden y claridad, factores críticos en una herramienta de seguridad escolar. En lugar de saturar la vista, aprovechamos márgenes amplios en los laterales de cada sección para que el usuario pueda diferenciar rápidamente entre los beneficios para padres, conductores y colegios. El contenido se mantiene estructurado mediante el uso de Flexbox y CSS Grid, lo que evita que la información se disperse y mantiene una jerarquía visual equilibrada que facilita la lectura de las características del servicio. Además, los rellenos (padding) en elementos como las tarjetas de planes y funciones garantizan una distribución adecuada del contenido.

#### Dimensiones para el tono de comunicación y lenguaje aplicado

En SafeRoute, definimos cuidadosamente el tono de nuestra comunicación para alinearlo con la misión de la plataforma: garantizar la seguridad y la tranquilidad en el transporte escolar para padres, conductores e instituciones educativas. Nuestro tono de voz busca proyectar confianza y control, combinando una comunicación clara, directa y altamente profesional.

Optamos por un tono formal pero empático, que permita a los padres de familia sentirse seguros al interactuar con funciones críticas como el monitoreo en vivo o las notificaciones de abordaje. Queremos que cada interacción refleje eficiencia para fomentar la puntualidad y el orden, pero también serenidad, asegurando que los usuarios sientan que el bienestar de los estudiantes es nuestra prioridad absoluta. Este equilibrio nos permite inspirar autoridad en la gestión logística, al tiempo que proyectamos cercanía y compromiso con la comunidad escolar.

Además, se han considerado los siguientes aspectos clave en el diseño de SafeRoute:

- Consistencia: La coherencia visual y textual es fundamental para brindar una experiencia confiable. Todos los elementos, desde los mensajes de estado hasta las etiquetas de los botones, mantienen una línea comunicativa uniforme. Esto facilita que los usuarios se familiaricen rápido con el sistema, algo vital en una operación diaria que requiere precisión.
- Navegación: La estructura ha sido pensada para ser lógica y sin fricciones. Los usuarios pueden acceder rápidamente a la información relevante según su rol, ya sea para verificar una ruta o reportar una incidencia. Los menús son minimalistas para evitar confusiones y optimizar el tiempo de respuesta en entornos dinámicos.
- Accesibilidad: La plataforma está optimizada para ser inclusiva y funcional en diversos contextos. Mediante el uso de etiquetas claras y un diseño responsivo, aseguramos que la información sea legible tanto para un administrador en una oficina como para un padre que revisa el celular en movimiento, garantizando una experiencia de uso fluida para todos.

#### Elementos de diseño

Además de los lineamientos generales sobre colores, tipografía y branding, en el diseño visual de SafeRoute se han aplicado de manera consciente diversos elementos fundamentales del diseño gráfico que enriquecen la experiencia del usuario y refuerzan la identidad de seguridad de la plataforma.

Uno de los elementos clave es la **línea**, utilizada sutilmente para separar secciones y delimitar las tarjetas de planes y roles, lo que organiza visualmente la interfaz y guía la lectura sin saturar al usuario. El **color** cumple un rol fundamental no solo en la identidad, sino en la comunicación funcional; la paleta incluye el azul noche para la autoridad, el naranja ámbar para la acción y el verde para confirmaciones, seleccionados por su capacidad para transmitir estados de seguridad y éxito.

En cuanto al **tamaño**, se utiliza jerárquicamente para resaltar títulos, botones y texto de soporte. Los tamaños más grandes en los encabezados captan la atención en puntos clave como el Hero, mientras que los más pequeños se emplean para detalles secundarios en las tarjetas de características, mejorando la comprensión y la eficiencia. Por su parte, la **textura** es limpia y moderna, gracias al uso de fondos suaves y superficies blancas que aportan una sensación de amplitud tecnológica sin distraer de las funciones de monitoreo.

El **espacio** es uno de los elementos más destacados del diseño de SafeRoute. Se han implementado márgenes amplios y rellenos generosos entre secciones, lo que permite una interfaz despejada y cómoda para padres y conductores. A nivel de **brillo** (value), se aplican contrastes claros que diferencian los botones de acción del fondo, guiando al usuario de forma intuitiva hacia la conversión.

Respecto a las **formas**, se ha optado por geometrías amigables con bordes redondeados en botones y tarjetas. Estos acabados suavizados no solo mejoran la estética profesional, sino que también transmiten una imagen de accesibilidad y cercanía, alineándose con una herramienta diseñada para el cuidado y protección escolar.

#### Principios de diseño

En cuanto a los principios de diseño, el **contraste** se emplea para asegurar que los elementos críticos, como los llamados a la acción (CTA) de "Ver planes" o las etiquetas de "Sistema en vivo", sean claramente visibles y resalten sobre los fondos neutros. Este principio es fundamental para la accesibilidad visual, permitiendo que tanto padres como conductores identifiquen los puntos de interacción más importantes de la plataforma de manera inmediata.

La **repetición** de colores como el azul noche y el naranja ámbar, junto con una iconografía coherente de escudos y mapas, refuerza la familiaridad y la consistencia del sistema visual. Al utilizar componentes visuales recurrentes en toda la landing, los usuarios comprenden rápidamente la función de cada sección, lo que reduce la curva de aprendizaje al interactuar con las herramientas de monitoreo.

La **alineación** contribuye a la profesionalidad y solidez del diseño: la estructura de la página, los listados de roles y las tarjetas de precios mantienen una disposición coherente lograda mediante el uso de Flexbox y CSS Grid. Esta organización clara y alineada facilita una navegación intuitiva, transmitiendo el orden necesario para una plataforma de gestión logística.

Por último, el principio de **proximidad** agrupa de manera lógica los elementos relacionados, como los iconos de las funciones con sus respectivas descripciones o los beneficios específicos para cada rol. Al mantener los elementos vinculados cerca entre sí, se mejora significativamente la lectura y la comprensión de cada bloque de información, permitiendo que el usuario asocie rápidamente las soluciones de SafeRoute con sus necesidades específicas.

Estos elementos y principios no se aplican de forma aislada, sino como parte integral de un sistema visual que busca ser funcional, estético y coherente con la misión de SafeRoute: digitalizar y dar seguridad al transporte escolar a través de una experiencia clara, confiable y eficiente.

#### 4.1.2. Web Style Guidelines

El diseño web de **SafeRoute** está optimizado para proporcionar una experiencia fluida y segura en dispositivos de diversos formatos, garantizando que tanto administradores en escritorio como conductores en móviles operen sin fricciones. Se han implementado diseños de grillas flexibles que pasan de múltiples columnas en desktop a una sola columna en dispositivos móviles, priorizando la legibilidad y el acceso rápido a botones de acción.

En cuanto a la interactividad, los elementos táctiles en la versión móvil presentan áreas de contacto amplias, cumpliendo con estándares de accesibilidad. Se han definido estados visuales (hover, active) para ofrecer retroalimentación inmediata, y la navegación se transforma en un menú lateral (sidebar) en resoluciones menores a 768px, manteniendo el flujo de trabajo despejado.

### 4.2. Information Architecture

#### 4.2.1. Organization Systems

#### 4.2.2. Labeling Systems

#### 4.2.3. SEO Tags and Meta Tags

#### 4.2.4. Searching Systems

#### 4.2.5. Navigation Systems

### 4.3. Landing Page UI Design

#### 4.3.1. Landing Page Wireframe

#### 4.3.2. Landing Page Mock-up

### 4.4. Web Applications UX/UI Design

#### 4.4.1. Web Applications Wireframes

#### 4.4.2. Web Applications Wireflow Diagrams

#### 4.4.2. Web Applications Mock-ups

#### 4.4.3. Web Applications User Flow Diagrams

### 4.5. Web Applications Prototyping

### 4.6. Domain-Driven Software Architecture

#### 4.6.1. Design-Level Event Storming

#### 4.6.2. Software Architecture Context Diagram

#### 4.6.3. Software Architecture Container Diagrams

#### 4.6.4. Software Architecture Components Diagrams

### 4.7. Software Object-Oriented Design

#### 4.7.1. Class Diagrams

### 4.8. Database Design

#### 4.8.1. Database Diagrams

---

## Capítulo V: Product Implementation, Validation & Deployment

### 5.1. Software Configuration Management

#### 5.1.1. Software Development Environment Configuration

En esta sección se describen las herramientas y tecnologías utilizadas para el desarrollo del proyecto.

##### UX/UI Design

* **Figma**  
  Herramienta de diseño colaborativo utilizada para la creación de wireframes, mockups, prototipos y diseño de interfaces de usuario. Permite trabajar en equipo en tiempo real, facilitando la validación temprana de la experiencia del usuario.

---

##### Software Development

* **JetBrains Rider**  
  Entorno de desarrollo integrado (IDE) utilizado para el desarrollo del backend en C#.

* **Visual Studio Code**  
  Editor de código ligero utilizado como herramienta complementaria para el desarrollo frontend y edición de archivos del proyecto.

* **GitHub**  
  Plataforma de control de versiones utilizada para la gestión del código fuente y colaboración del equipo, implementando la metodología GitFlow para la organización del desarrollo.

* **HTML**  
  Lenguaje de marcado utilizado para la estructura de las interfaces web.

* **CSS**  
  Lenguaje de estilos utilizado para la presentación visual de la aplicación.

* **JavaScript (Vue.js)**  
  Framework utilizado para el desarrollo del frontend, permitiendo la creación de interfaces dinámicas e interactivas.

* **C#**  
  Lenguaje de programación utilizado para el desarrollo del backend de la aplicación.

---

### Software Deployment

* **GitHub Pages**  
  Servicio utilizado para el despliegue de la landing page del proyecto.

* **Vercel**  
  Plataforma utilizada para el despliegue del frontend desarrollado en Vue.js, permitiendo una integración continua y despliegue automatizado.

* **Railway**  
  Plataforma utilizada para el despliegue de servicios backend y APIs, facilitando la conexión entre frontend y backend en un entorno accesible en la nube.

#### 5.1.2. Source Code Management

Para el manejo del código fuente, utilizamos GitHub para colaborar entre miembros de equipo en multiples repositorios. A continuación se listan los enlaces de cada repositorio utilizado.

* Organización: <https://github.com/PowerTech-NRC12053>
* Repositorio de Landing Page: <https://github.com/PowerTech-NRC12053/safedrive-landing-page>
* Repositorio del informe: <https://github.com/PowerTech-NRC12053/safedrive-report>
* Repositorio del frontend: <https://github.com/PowerTech-NRC12053/safedrive-frontend-applications>
* Repositorio del backend: <https://github.com/PowerTech-NRC12053/safedrive-web-services>

En el repositorio del informe se seguirá un esquema de trabajo basado en GitFlow. La rama main almacenará la versión estable del informe correspondiente a cada entregable del trabajo, mientras que la rama develop concentrará la integración de avances validados por cada integrante antes de su consolidación final. A partir de develop, cada integrante creará ramas feature de trabajo para las secciones asignadas. Las ramas feature seguirán una nomenclatura asociada al capítulo o bloque trabajado, por ejemplo: feature/chapter-1-introduction-and-lean-ux, o feature/chapter-5-software-configuration-management. Esta convención permite identificar con claridad qué parte del informe está siendo desarrollada y reduce el riesgo de conflictos entre los miembros del equipo.

En los repositorios del Landing Page, Frontend y Backend también se utilizará GitFlow. En cada uno de ellos, la rama main contendrá las versiones estables del producto y la rama develop servirá como rama de integración del trabajo colaborativo. A partir de develop, se crearán ramas feature/... para el desarrollo de funcionalidades específicas. A diferencia del informe, en estos repositorios las ramas no estarán organizadas por capítulos, sino por funcionalidades o componentes del sistema. Algunos ejemplos de nomenclatura son: feature/home-page, feature/dashboard o feature/route-management. Esta convención nos permite que las ramas reflejen de manera directa el alcance funcional del producto en desarrollo.

No se realizarán cambios directos sobre la rama main, ya que esta representará únicamente versiones estables y listas para consolidarse como parte de un entregable. Del mismo modo, se evitará que los integrantes trabajen de forma continua directamente sobre la rama develop, ya que el flujo previsto consiste en desarrollar primero en ramas feature, integrar luego en develop y finalmente consolidar en main cuando el avance haya sido revisado y validado. Por tanto, el flujo general de trabajo será de la siguiente forma: feature → develop → main. Este esquema se alinea con la exigencia del curso de explicar la implementación de GitFlow mediante ramas principales, ramas de features, y convenciones para releases y hotfixes.

Asimismo, si se requiere corregir errores críticos sobre una versión estable, se podrán crear ramas hotfix/..., y si se decide preparar una versión de cierre antes de una entrega, se utilizarán ramas release/... de acuerdo con el flujo definido por GitFlow.

En relación con los mensajes de cada commit, el equipo aplicará Conventional Commits para mantener un historial más legible, consistente y profesional. Esta convención facilitará la revisión de avances y permitirá identificar rápidamente el propósito de cada uno de los cambios. Algunos prefijos que se utilizarán son:

* feat: incorporación de una nueva funcionalidad
* fix: corrección de errores
* docs: cambios en documentación
* style: cambios de formato o estilo sin alterar lógica
* refactor: reorganización interna sin agregar funcionalidad nueva
* test: incorporación o ajuste de pruebas
* chore: tareas de mantenimiento o configuración

Para el repositorio del informe se emplearán mensajes como docs(report): add project cover page o docs: add startup profile and lean ux process for chapter 1. Para los repositorios de software se utilizarán mensajes como feat: add school route registration, feat: implement student assignment to route o fix: correct login validation. Esta práctica contribuye a que la evidencia de commits sea coherente con el trabajo realizado por cada miembro

#### 5.1.3. Source Code Style Guide & Conventions

En esta sección se definen las convenciones de nombres y codificación adoptadas por el equipo para los lenguajes utilizados en el proyecto: HTML, CSS, JavaScript (Vue.js) y C#.

### Principios generales

* **Idioma estándar:** Todo el código fuente se desarrolla en inglés, incluyendo nombres de variables, funciones, clases, archivos y la documentación del código.
* **Legibilidad:** Se prioriza el uso de nombres descriptivos y claros, evitando abreviaciones innecesarias.
* **Consistencia:** Se mantiene un estilo uniforme en todo el proyecto para facilitar el trabajo colaborativo.
* **Nombres semánticos:**  
  * Sustantivos para clases y componentes.  
  * Verbos para funciones y métodos.
  
---

### HTML

* Los archivos terminan en `.html`.
* Se utilizan etiquetas semánticas como:
  * `<header>`, `<nav>`, `<section>`, `<article>`, `<footer>`.
* Se emplean atributos descriptivos para mejorar la accesibilidad (`alt`, `aria-*`).
* Estructura clara y ordenada para facilitar mantenimiento.

---

### CSS

* Los archivos terminan en `.css`.
* Las clases se nombran en **kebab-case**:
  * `.main-header`, `.route-card`, `.student-list`.
* Se mantiene consistencia visual mediante estilos reutilizables.

---

### JavaScript (Vue.js)

* Los archivos terminan en `.js`.
* Se utiliza **camelCase** para variables y funciones:
  * `getRoutes`, `calculateDistance`.
* Se prioriza el uso de `const` y `let`, evitando `var`.
* Los componentes de Vue siguen una estructura modular y reutilizable.
* Se mantiene separación clara entre lógica, presentación y datos.
* Se utilizan nombres descriptivos para props, métodos y eventos.

---

### C#

* Se sigue la convención estándar de **PascalCase**:
  * Clases: `StudentService`, `RouteController`.
  * Métodos: `GetStudents()`, `CreateRoute()`.
* Variables locales en **camelCase**:
  * `studentList`, `routeId`.
* Uso de sufijos por responsabilidad:
  * `Controller`, `Service`, `Repository`.
* Se mantiene una arquitectura organizada por capas (por ejemplo: Controllers, Services, Models).
* Se aplican buenas prácticas como separación de responsabilidades y reutilización de código.

---

#### 5.1.4. Software Deployment Configuration

En esta sección se describe la configuración necesaria para el despliegue de los principales componentes del proyecto: Landing Page, Frontend Web Application y Backend.

##### Despliegue de Landing Page

La Landing Page fue desarrollada utilizando HTML, CSS y JavaScript, y será desplegada mediante GitHub Pages, un servicio de hosting para sitios estáticos.

###### Pasos de despliegue

1. Crear un repositorio en GitHub destinado a la landing page.
2. Subir el código fuente (HTML, CSS, JS y recursos estáticos) al repositorio.
3. Asegurar que el archivo principal se denomine `index.html` y se encuentre en la raíz del proyecto.
4. Acceder a la sección **Settings > Pages** del repositorio.
5. Seleccionar la rama `main` (o `master`) y la carpeta raíz (`/`) como fuente.
6. GitHub generará automáticamente una URL pública para acceder a la landing page.

**URL desplegada:** Pendiente

---

##### Despliegue de Frontend Web Application

El frontend de la aplicación, desarrollado con Vue.js, será desplegado utilizando la plataforma Vercel, la cual permite integración continua y despliegue automatizado.

###### Pasos de despliegue

1. Crear o seleccionar el repositorio del frontend en GitHub.
2. Vincular el repositorio con la plataforma Vercel.
3. Configurar el entorno de despliegue (framework Vue.js).
4. Ejecutar el despliegue automático desde Vercel.
5. Obtener la URL pública generada para el acceso a la aplicación.
 
**URL desplegada:** Pendiente

---

### Despliegue de Backend Services

El backend del sistema, desarrollado en C#, será desplegado utilizando Railway, una plataforma que permite exponer servicios y APIs en la nube.

#### Pasos de despliegue:

1. Crear el repositorio del backend en GitHub.
2. Vincular el repositorio con Railway.
3. Configurar las variables de entorno necesarias para la ejecución del backend.
4. Configurar el servicio para exponer endpoints API.
5. Desplegar el servicio y obtener la URL pública del backend.

**URL desplegada:** Pendiente

---

### 5.2. Landing Page, Services & Applications Implementation

#### 5.2.1. Sprint 1

##### 5.2.1.1. Sprint Planning 1

##### 5.2.1.2. Aspect Leaders and Collaborators

##### 5.2.1.3. Sprint Backlog 1

##### 5.2.1.4. Development Evidence for Sprint Review

##### 5.2.1.5. Execution Evidence for Sprint Review

##### 5.2.1.6. Services Documentation Evidence for Sprint Review

##### 5.2.1.7. Software Deployment Evidence for Sprint Review

##### 5.2.1.8. Team Collaboration Insights during Sprint

---

## Conclusiones

### Conclusiones y recomendaciones

### Video About-the-Team

## Bibliografía

- Autoridad de Transporte Urbano para Lima y Callao. (2024). *Cifra de movilidades escolares autorizadas disminuyó en 25% en un año*. El Comercio. Recuperado el 9 de abril de 2026, de https://elcomercio.pe/lima/cifra-de-movilidades-escolares-autorizadas-disminuyo-en-25-en-un-ano-a-que-se-debe-esta-reduccion-informe-movilidad-escolar-noticia/

- Ministerio de Educación. (2023). *Resultados del Censo Educativo 2022*. ESCALE. Recuperado el 9 de abril de 2026, de https://escale.minedu.gob.pe/documents/10156/9345030/PPT_Censo_Educativo_2023_final.pdf

- Superintendencia de Transporte Terrestre de Personas, Carga y Mercancías. (2024). *Sutran (MTC) sensibilizó a más de 47 000 escolares sobre seguridad vial*. Gob.pe. Recuperado el 9 de abril de 2026, de https://www.gob.pe/institucion/sutran/noticias/1255228-sutran-mtc-sensibilizo-a-mas-de-47-000-escolares-sobre-seguridad-vial-en-lo-que-va-del-2025

## Anexos