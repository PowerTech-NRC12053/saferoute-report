![Logo UPC](assets/images/Upc/Banner-UPC.png)

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
**Nombre del producto:** SafeRoute

**Relación de integrantes:**

- U202424059 - De La Cruz De Los Santos, Mathias Marcelo
- U202316852 - Ortega Quintana, Jose Zacarias
- U20241D922 - Quispe Serrano, Julio Frank
- U202415551 - Ramirez Ruiz, Nickolas
- U20211D989 - Vallejo Trujillo, Fabio Cesar

**Abril, 2026**

---

## Registro de Versiones del Informe

| Avance | Fecha      | Autor                                                                                                                                                                                                 | Descripción de Modificación |
| :----- | :--------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :-------------------------- |
| AV1    | --/04/2026 | De La Cruz De Los Santos, Mathias Marcelo; Ortega Quintana, Jose Zacarias; Quispe Serrano, Julio Frank; Ramirez Ruiz, Nickolas; Vallejo Trujillo, Fabio Cesar | Se desarrolló el Sprint Review correspondiente a la Semana 4, incluyendo la elaboración del Final Project Documentation Report, la presentación del Final Project Keynote y el reporte individual de desempeño de los integrantes. A nivel de implementación, se desarrolló y desplegó la primera versión del Landing Page. El informe incorpora la carátula, registro de versiones, insights de colaboración, student outcome, y los capítulos I al V, abarcando desde la introducción, levantamiento y especificación de requerimientos, diseño del producto, hasta la implementación, validación y despliegue. Además, se documenta la gestión de configuración del software, el entorno de desarrollo, control de código fuente, convenciones de estilo y configuración de despliegue. Finalmente, se incluye la evidencia completa del Sprint 1: planificación, backlog, desarrollo, ejecución, documentación de servicios, despliegue y análisis de la colaboración del equipo, junto con conclusiones, bibliografía y anexos. |

---

## Project Report Collaboration Insights
El equipo ha utilizado un flujo de trabajo en github: [https://github.com/FiveTech-NRC11896/SafeRoute-report](https://github.com/FiveTech-NRC11896/SafeRoute-report)

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
#### 1.1.2. Perfiles de integrantes del equipo

|                Foto                | Apellidos y Nombres         |    Código     | Carrera                | Resumen                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| :--------------------------------: | :-------------------------- | :-----------: | :--------------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|              ![foto]               | [Apellido 1], [Nombre 1]    | [U20XXXXXXXX] | Ingeniería de Software | [Descripción de conocimientos técnicos y habilidades que aporta al equipo]                                                                                                                                                                                                                                                                                                                                                                             |
|              ![foto]               | [Apellido 2], [Nombre 2]    | [U20XXXXXXXX] | Ingeniería de Software | [Descripción de conocimientos técnicos y habilidades que aporta al equipo]                                                                                                                                                                                                                                                                                                                                                                             |
| ![foto](assets/images/Team/frankFT.png) | Quispe Serrano, Julio Frank | [U20241D922]  | Ingeniería de Software | Mi nombre es Julio Frank Quispe Serrano, tengo 20 años,actualmente estoy cursando el 5to ciclo de la carrera de Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas. Soy un apasionado por la programación, el gym y explorador de música en distintos géneros. Mi aporte en este grupo será el de brindar soluciones prácticas y eficientes ante situaciones de adversidad que estanquen la fluidez de la elaboración del trabajo. |
|              ![foto]               | [Apellido 4], [Nombre 4]    | [U20XXXXXXXX] | Ingeniería de Software | [Descripción de conocimientos técnicos y habilidades que aporta al equipo]                                                                                                                                                                                                                                                                                                                                                                             |
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
_Nota._ Adaptado de Resultados del Censo Educativo 2022 (p. 12), por Ministerio de Educación, 2023.

#### 1.2.2 Lean UX Process
##### 1.2.2.1. Lean UX Problem Statements
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
  Los padres de familia con hijos en nivel inicial, kínder y primaria que utilizan un servicio de transporte escolar ya contratado, y los transportistas escolares como por ejemplo los conductores independientes o responsables de pequeñas empresas que operan ese servicio. Dentro de la plataforma, cualquiera de estos segmentos puede asumir además el rol de Administrador.
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

| Sección                                                                                  | Contenido                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| :--------------------------------------------------------------------------------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1. Business Problem                                                                      | El transporte escolar privado en el Perú opera de forma tradicional y sin soporte tecnológico. Los padres no tienen visibilidad sobre el trayecto de sus hijos y los transportistas gestionan su operación con llamadas, WhatsApp y hojas privadas, lo que genera errores, ineficiencia y una experiencia de servicio poco confiable.                                                                                                                                                                                                           |
| 2. Business Outcomes                                                                     | Lograr que el 75% de administradores completen el registro de su operación en los primeros 15 días. Retener al 80% de suscriptores activos durante los primeros 3 meses. Alcanzar una tasa de upgrade del plan Básico al Intermedio del 20% en los primeros 3 meses de uso.                                                                                                                                                                                                                                                                     |
| 3. Users                                                                                 | Los segmentos que interactúan con SafeRoute son los padres de familia con hijos en nivel inicial, kínder y primaria que utilizan un servicio de transporte escolar ya contratado, y los transportistas escolares conductores independientes o responsables de pequeñas empresas que operan ese servicio. Cualquiera de estos puede asumir además el rol de Administrador dentro de la plataforma.                                                                                                                                               |
| 4. User Outcomes & Benefits                                                              | Los padres buscan reducir su incertidumbre sobre el trayecto de sus hijos, pudiendo monitorear el estado del viaje sin necesidad de interrumpir al conductor. Los transportistas buscan gestionar rutas, alumnos e incidencias de forma digital, reduciendo errores operativos y proyectando mayor profesionalismo frente a las familias. Quienes asumen el rol de administrador buscan centralizar toda la operación del servicio en un solo panel, eliminando la coordinación manual y el uso de herramientas desconectadas.                  |
| 5. Solution Ideas                                                                        | Ofrecemos un panel de administración de usuarios, conductores, hijos y rutas. Tambien, Check-list de abordaje digital por conductor. Vista de paradas y estado del trayecto para padres. Registro de incidencias por ruta. Historial de trayectos por comunidad de ruta. Seguimiento GPS en tiempo real (plan Completo). Apertura a integración IoT futura.                                                                                                                                                                                     |
| 6. Hypotheses                                                                            | - Si ofrecemos a los padres una vista de estado del trayecto, al menos el 70% la consultará diariamente en las primeras 4 semanas.<br> - Si ofrecemos al conductor una interfaz operativa simple, el 80% de los trayectos tendrán el check-list completado en las primeras 4 semanas.<br> - Si ofrecemos al administrador un panel único de gestión, el 75% completará su registro en los primeros 15 días.<br> - Si demostramos el valor del plan Intermedio, el 20% de administradores del plan Básico harán upgrade en los primeros 3 meses. |
| 7. What's the most important thing we need to learn first?                               | ¿El administrador del servicio percibe suficiente valor en SafeRoute como para abandonar los métodos informales actuales y pagar una suscripción mensual?                                                                                                                                                                                                                                                                                                                                                                                       |
| 8. What's the least amount of work we need to do to learn the next most important thing? | Realizar entrevistas con 3 a 5 administradores de servicios de transporte escolar (padres representantes o transportistas independientes) para validar su disposición al cambio y las funcionalidades que consideran imprescindibles antes de desarrollar el MVP.                                                                                                                                                                                                                                                                               |

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

Las siguientes User Stories representan los requisitos detallados del sistema SafeRoute, cubriendo la operación completa, la Landing Page y la API técnica.

| Epic / ID | Título | Descripción | Escenarios de Aceptación (Gherkin: 2 Positivos / 1 Negativo) | Relacionado con |
|:---|:---|:---|:---|:---|
| **E1** | **Gestión Administrativa** | Control de planes, usuarios y flota | | |
| US1 | Contratar Plan | Como administrador, quiero elegir un plan, para escalar mi operación. | **S1:** Given el admin elige "Plan Pro", When confirma pago, Then los límites de rutas se actualizan. <br> **S2:** Given un plan activo, When elige "Upgrade", Then se prorratea el pago. <br> **S3:** Given tarjeta sin fondos, When intenta contratar, Then se muestra "Error de transacción". | E1 |
| US2 | Registro de Conductores | Como administrador, quiero crear cuentas de conductores, para asignar responsabilidades. | **S1:** Given datos válidos, When guarda, Then perfil se crea. <br> **S2:** Given licencia subida, When sistema valida, Then estado cambia a "Verificado". <br> **S3:** Given DNI duplicado, When intenta guardar, Then muestra "Usuario ya existe". | E1 |
| US3 | Registro de Padres | Como administrador, quiero registrar a los padres, para habilitar el monitoreo. | **S1:** Given correo válido, When registra, Then envía invitación. <br> **S2:** Given vínculo con alumno, When confirma, Then habilita vista de mapa. <br> **S3:** Given correo inválido, When intenta enviar, Then muestra "Formato no soportado". | E1 |
| US4 | Alta de Alumnos | Como administrador, quiero registrar alumnos, para incluirlos en los recorridos. | **S1:** Given datos del menor, When guarda, Then aparece en lista de espera. <br> **S2:** Given foto subida, When guarda, Then se muestra en carné digital. <br> **S3:** Given campos vacíos, When intenta guardar, Then resalta campos obligatorios. | E1 |
| US5 | Creación de Rutas | Como administrador, quiero trazar rutas y paradas, para optimizar el tiempo. | **S1:** Given puntos A y B, When traza en mapa, Then calcula tiempo estimado. <br> **S2:** Given paradas nuevas, When agrega a ruta, Then recalcula orden óptimo. <br> **S3:** Given puntos inaccesibles, When intenta trazar, Then muestra "Ruta no transitable". | E1 |
| US6 | Asignación de Roles | Como administrador, quiero asignar conductores a rutas, para organizar la operación. | **S1:** Given conductor libre, When asigna a ruta X, Then conductor recibe alerta. <br> **S2:** Given cambio de unidad, When reasigna, Then se actualiza en tiempo real. <br> **S3:** Given conductor ya ocupado, When intenta asignar, Then muestra "No disponible". | E1 |
| US7 | Analítica de Flota | Como administrador, quiero ver reportes de rendimiento, para evaluar eficiencia. | **S1:** Given Plan Completo, When abre dashboard, Then muestra consumo de combustible. <br> **S2:** Given periodo mensual, When filtra, Then genera PDF de rendimiento. <br> **S3:** Given Plan Básico, When intenta abrir analítica, Then pide "Upgrade". | E1 |
| US8 | Gestión de Notificaciones | Como administrador, quiero enviar avisos globales, para informar eventos del colegio. | **S1:** Given evento imprevisto, When escribe mensaje global, Then todos los padres reciben push. <br> **S2:** Given aviso programado, When elige fecha, Then se envía automáticamente. <br> **S3:** Given mensaje vacío, When intenta enviar, Then el botón se bloquea. | E1 |
| US9 | Auditoría de Logs | Como administrador, quiero ver logs de sistema, para rastrear errores técnicos. | **S1:** Given fallo reportado, When busca en logs, Then identifica hora y usuario. <br> **S2:** Given exportar datos, When elige formato CSV, Then descarga el historial. <br> **S3:** Given usuario sin permisos, When intenta acceder, Then muestra "Acceso Denegado". | E1 |
| **E2** | **Operación del Conductor** | Herramientas para la ejecución del servicio | | |
| US10 | Inicio de Trayecto | Como conductor, quiero activar la ruta, para notificar a los padres. | **S1:** Given ruta lista, When pulsa "Iniciar", Then cambia estado a "En camino". <br> **S2:** Given GPS activo, When inicia, Then comienza transmisión de coordenadas. <br> **S3:** Given sin conexión, When intenta iniciar, Then muestra "Modo Offline: reconectando". | E2 |
| US11 | Marcación de Abordaje | Como conductor, quiero registrar el abordaje, para confirmar asistencia. | **S1:** Given parada alcanzada, When marca check, Then notifica al padre. <br> **S2:** Given código QR, When escanea al alumno, Then registra abordaje automático. <br> **S3:** Given alumno equivocado, When intenta marcar, Then alerta "Alumno no pertenece a esta parada". | E2 |
| US12 | Reporte de Incidencias | Como conductor, quiero informar problemas, para que el admin tome medidas. | **S1:** Given tráfico denso, When reporta retraso, Then actualiza ETA de todos los padres. <br> **S2:** Given falla mecánica, When selecciona tipo, Then avisa a central de auxilio. <br> **S3:** Given falta de GPS, When intenta reportar, Then pide ingreso manual de ubicación. | E2 |
| US13 | Botón de Pánico | Como conductor, quiero usar el SOS, para emergencias críticas. | **S1:** Given peligro, When presiona 3 seg, Then envía alerta con ubicación GPS. <br> **S2:** Given alerta activa, When admin responde, Then abre canal de audio. <br> **S3:** Given presión accidental, When cancela en 2 seg, Then no envía la alerta. | E2 |
| US14 | Finalización de Ruta | Como conductor, quiero cerrar la sesión, para concluir el turno. | **S1:** Given fin de recorrido, When pulsa "Cerrar", Then detiene GPS. <br> **S2:** Given alumnos pendientes, When intenta cerrar, Then advierte "Hay alumnos a bordo". <br> **S3:** Given error de servidor, When cierra, Then guarda datos localmente. | E2 |
| US15 | Bitácora de Viajes | Como conductor, quiero ver mi historial, para revisar recorridos pasados. | **S1:** Given menú historial, When selecciona día, Then muestra mapa del recorrido. <br> **S2:** Given resumen semanal, When consulta, Then indica horas totales manejadas. <br> **S3:** Given sin historial previo, When abre pestaña, Then muestra "Sin viajes registrados". | E2 |
| US16 | Navegación Integrada | Como conductor, quiero usar mapas externos, para ver la mejor ruta. | **S1:** Given viaje iniciado, When pulsa "Navegar", Then abre app externa. <br> **S2:** Given cambio de tráfico, When mapas sugiere desvío, Then el sistema actualiza el ETA. <br> **S3:** Given app de mapas no instalada, When intenta abrir, Then sugiere descarga. | E2 |
| US17 | Check de Seguridad | Como conductor, quiero una lista de chequeo, para revisar el bus antes de salir. | **S1:** Given inicio de día, When marca luces y frenos, Then habilita el inicio de ruta. <br> **S2:** Given falla detectada, When reporta en check, Then bloquea unidad por seguridad. <br> **S3:** Given check incompleto, When intenta iniciar viaje, Then recuerda "Revisión obligatoria". | E2 |
| **E3** | **Monitoreo y Seguridad (Padres)** | Visibilidad y tranquilidad para la familia | | |
| US18 | Rastreo en Tiempo Real | Como padre, quiero ver el bus en el mapa, para calcular la hora de llegada. | **S1:** Given viaje activo, When abre mapa, Then ve el icono moverse. <br> **S2:** Given parada propia, When toca icono, Then muestra distancia en KM. <br> **S3:** Given viaje finalizado, When abre mapa, Then muestra "Servicio concluido". | E3 |
| US19 | Alerta de Proximidad | Como padre, quiero recibir un aviso previo, para bajar a la parada a tiempo. | **S1:** Given bus a 500m, When entra a geovalla, Then recibe notificación push. <br> **S2:** Given bus a 2min, When tiempo se cumple, Then vibra el teléfono. <br> **S3:** Given notificaciones desactivadas, When bus llega, Then solo registra el evento en log. | E3 |
| US20 | Confirmación de Llegada | Como padre, quiero saber si mi hijo llegó al colegio, para estar tranquilo. | **S1:** Given bus en colegio, When conductor cierra viaje, Then recibe notificación de éxito. <br> **S2:** Given viaje de retorno, When llega a casa, Then recibe "Hijo entregado". <br> **S3:** Given retraso mayor a 20min, When tiempo pasa, Then recibe alerta de demora. | E3 |
| US21 | Acceso a Cámara | Como padre, quiero ver el interior del bus, para verificar la seguridad. | **S1:** Given Plan Intermedio, When solicita video, Then carga cámara en vivo. <br> **S2:** Given modo nocturno, When poca luz, Then activa visión infrarroja. <br> **S3:** Given fallo de internet, When carga video, Then muestra "Señal débil". | E3 |
| US22 | Historial de Asistencia | Como padre, quiero ver los días que mi hijo abordó, para control mensual. | **S1:** Given pestaña asistencia, When elige mes, Then muestra calendario con checks. <br> **S2:** Given falta justificada, When marca día, Then el sistema cambia icono a "Justificado". <br> **S3:** Given mes futuro, When intenta ver, Then la opción aparece bloqueada. | E3 |
| US23 | Perfil del Estudiante | Como padre, quiero gestionar datos médicos, para informar alergias al conductor. | **S1:** Given editar perfil, When escribe "Alergia a maní", Then el conductor ve alerta en su panel. <br> **S2:** Given foto actualizada, When sube imagen, Then se actualiza en el panel del bus. <br> **S3:** Given campo vacío, When intenta guardar, Then mantiene datos anteriores. | E3 |
| US24 | Chat con Soporte | Como padre, quiero un chat interno, para reportar ausencias. | **S1:** Given ausencia programada, When escribe al chat, Then el admin recibe el aviso. <br> **S2:** Given respuesta de soporte, When llega mensaje, Then se muestra notificación. <br> **S3:** Given mensaje fuera de hora, When envía, Then recibe respuesta automática. | E3 |
| **E4** | **Landing Page (Visitantes)** | Captación de clientes e Internacionalización (i18n) | | |
| US25 | Visualización de Hero | Como visitante, quiero ver la propuesta de valor, para entender SafeRoute. | **S1:** Given carga de URL, When ve sección principal, Then lee "Seguridad en cada ruta". <br> **S2:** Given botón CTA, When hace clic, Then lo lleva a Registro. <br> **S3:** Given fallo de carga, When URL es errónea, Then muestra página 404 personalizada. | E4 |
| US26 | Navegación de Funciones | Como visitante, quiero ver las funcionalidades, para conocer el alcance técnico. | **S1:** Given sección funciones, When hace scroll, Then ve iconos de monitoreo. <br> **S2:** Given tarjetas de info, When pasa el mouse, Then se expande la descripción. <br> **S3:** Given pantalla pequeña, When usa móvil, Then las funciones se apilan verticalmente. | E4 |
| US27 | Detalle de Roles | Como visitante, quiero conocer las vistas por perfil, para ver los beneficios. | **S1:** Given sección roles, When elige "Padre", Then muestra capturas de la App de padres. <br> **S2:** Given rol "Conductor", When elige, Then muestra gestión de rutas. <br> **S3:** Given opción no seleccionada, When ve la sección, Then muestra el rol "Admin" por defecto. | E4 |
| US28 | Consulta de Precios | Como visitante, quiero ver los costos, para evaluar mi presupuesto. | **S1:** Given tabla de precios, When elige "Anual", Then aplica 20% de descuento. <br> **S2:** Given moneda local, When cambia región, Then muestra precios en Soles (PEN). <br> **S3:** Given plan no disponible, When intenta ver, Then aparece etiqueta "Próximamente". | E4 |
| US29 | Sección "¿Cómo funciona?" | Como visitante, quiero ver los pasos iniciales, para saber cómo empezar. | **S1:** Given infografía, When sigue los pasos 1-5, Then entiende el flujo de contrato. <br> **S2:** Given video demo, When pulsa play, Then visualiza el funcionamiento real. <br> **S3:** Given navegador antiguo, When carga video, Then muestra imagen estática. | E4 |
| US30 | Implementación i18n | Como visitante, quiero cambiar el idioma (ES/EN), para navegar cómodamente. | **S1:** Given selector de idioma, When marca "English", Then todo el texto cambia a inglés. <br> **S2:** Given navegador en inglés, When carga sitio, Then se muestra en inglés por defecto. <br> **S3:** Given idioma no soportado, When detecta región, Then carga español por defecto. | E4 |
| US31 | Testimonios Reales | Como visitante, quiero leer reseñas, para confiar en la marca. | **S1:** Given sección testimonios, When desliza, Then ve fotos y opiniones de colegios. <br> **S2:** Given estrellas de calificación, When ve promedio, Then nota 4.8/5 de satisfacción. <br> **S3:** Given sin internet, When carga sección, Then muestra testimonios cacheados. | E4 |
| US32 | Formulario de Contacto | Como visitante, quiero enviar dudas, para recibir una cotización. | **S1:** Given formulario completo, When envía, Then recibe mensaje "Enviado con éxito". <br> **S2:** Given campos obligatorios, When intenta enviar vacío, Then marca errores en rojo. <br> **S3:** Given bot detectado, When envía spam, Then el Captcha bloquea el envío. | E4 |
| US33 | Suscripción al Newsletter | Como visitante, quiero dejar mi correo, para recibir tips de seguridad. | **S1:** Given campo de email, When ingresa dato, Then recibe correo de bienvenida. <br> **S2:** Given checkbox de privacidad, When marca "Acepto", Then habilita botón Suscribir. <br> **S3:** Given correo duplicado, When intenta registrar, Then dice "Ya estás suscrito". | E4 |
| US34 | Visualización de Partners | Como visitante, quiero ver marcas aliadas, para validar la seriedad del servicio. | **S1:** Given sección aliados, When carga logos, Then se ven marcas de seguros y seguridad. <br> **S2:** Given enlace en logo, When hace clic, Then abre web del partner. <br> **S3:** Given logo roto, When no carga imagen, Then muestra el nombre en texto. | E4 |
| US35 | Preguntas Frecuentes (FAQ) | Como visitante, quiero ver dudas comunes, para evitar llamadas de soporte. | **S1:** Given lista de FAQs, When toca una pregunta, Then se despliega la respuesta. <br> **S2:** Given buscador de FAQs, When escribe "precio", Then filtra preguntas relacionadas. <br> **S3:** Given duda no resuelta, When baja al final, Then ve botón de contacto directo. | E4 |
| US36 | Responsive Design i18n | Como visitante, quiero que el texto se ajuste en móvil, para evitar cortes por traducción. | **S1:** Given idioma Alemán (texto largo), When ve en móvil, Then el contenedor se expande. <br> **S2:** Given modo horizontal, When gira teléfono, Then el menú se ajusta al idioma. <br> **S3:** Given fuente muy grande, When el texto desborda, Then aplica elipsis automáticamente. | E4 |
| US37 | Blog de Seguridad | Como visitante, quiero leer artículos, para aprender sobre movilidad escolar. | **S1:** Given lista de posts, When elige uno, Then abre lectura completa. <br> **S2:** Given botones sociales, When comparte post, Then abre ventana de RRSS. <br> **S3:** Given post sin imagen, When carga, Then usa una imagen corporativa por defecto. | E4 |
| US38 | Demo Interactiva | Como visitante, quiero probar un simulador de mapa, para ver la experiencia real. | **S1:** Given mapa demo, When pulsa "Play", Then ve un bus moviéndose ficticiamente. <br> **S2:** Given alertas demo, When bus llega a punto, Then suena un aviso de prueba. <br> **S3:** Given navegador sin JS, When intenta ver demo, Then pide activar JavaScript. | E4 |
| US39 | SEO & Meta Tags i18n | Como visitante, quiero encontrar la web en buscadores, según mi idioma local. | **S1:** Given búsqueda en Google (ES), When escribe "Transporte Seguro", Then aparece SafeRoute. <br> **S2:** Given búsqueda en Google (EN), When escribe "Safe School Bus", Then aparece SafeRoute. <br> **S3:** Given link compartido, When pega URL, Then muestra preview con título traducido. | E4 |
| US40 | Verificación de SSL | Como visitante, quiero ver el candado de seguridad, para confiar mis datos. | **S1:** Given acceso a la web, When ve la barra de direcciones, Then aparece el prefijo HTTPS. <br> **S2:** Given envío de datos, When procesa formulario, Then viajan cifrados. <br> **S3:** Given certificado vencido, When entra, Then el navegador muestra aviso de "Sitio no seguro". | E4 |
| US41 | Chatbot de Ventas | Como visitante, quiero interactuar con un bot, para resolver dudas rápidas. | **S1:** Given duda sobre planes, When pregunta al bot, Then recibe respuesta del catálogo. <br> **S2:** Given intención de compra, When solicita asesor, Then el bot deriva a un humano. <br> **S3:** Given texto incoherente, When escribe, Then el bot ofrece opciones de menú fijas. | E4 |
| US42 | Política de Cookies i18n | Como visitante, quiero aceptar cookies, para cumplir con normativas legales. | **S1:** Given primera visita, When aparece el banner, Then puede elegir "Aceptar todas". <br> **S2:** Given idioma inglés, When ve el banner, Then los términos están en inglés. <br> **S3:** Given rechazo de cookies, When navega, Then solo carga las técnicas esenciales. | E4 |
| US43 | Soporte Multimoneda | Como visitante, quiero ver precios en mi moneda, para facilitar la comparación. | **S1:** Given geolocalización Perú, When ve precios, Then muestra en Soles (PEN). <br> **S2:** Given cambio manual a USA, When selecciona, Then muestra precios en Dólares (USD). <br> **S3:** Given moneda desconocida, When carga sitio, Then muestra precios en USD por defecto. | E4 |
| **E5** | **SafeRoute RESTful API** | Integraciones para desarrolladores | | |
| US44 | API: Obtener Alumnos | Como developer, quiero listar alumnos por ruta, para integraciones externas. | **S1:** Given GET `/students`, When token Admin, Then retorna JSON lista. <br> **S2:** Given filtro por ID, When consulta, Then retorna datos de 1 alumno. <br> **S3:** Given token expirado, When consulta, Then retorna 401 Unauthorized. | E5 |
| US45 | API: Registro GPS | Como developer, quiero enviar coordenadas, para actualizar la posición del bus. | **S1:** Given alta frecuencia, When envía 10 req/seg, Then el sistema procesa sin delay. <br> **S2:** Given coordenadas inválidas, When envía null, Then retorna 400 Bad Request. | E5 |


### 3.2. Impact Mapping
Segmento Objetivo 1: Carlos Ramirez, conductor
![ImpactMapping1](./assets/images/ImpactMap1.png)

---
Segmento Objetivo 2: Rosita Nery, padre de familia
![ImpactMapping2](./assets/images/ImpactMap2.png)

### 3.3. Product Backlog
# Product Backlog - SafeRoute

| Orden | User Story ID | Título | Descripción | Story Points |
|------:|---------------|--------|-------------|-------------|
| 1 | US25 | Visualización de Hero | Como visitante, deseo ver la propuesta de valor de SafeRoute para entender rápidamente el servicio. | 2 |
| 2 | US28 | Consulta de Precios | Como visitante, deseo ver los planes y precios para evaluar mi presupuesto. | 3 |
| 3 | US32 | Formulario de Contacto | Como visitante, deseo enviar mis datos para solicitar información o una demo comercial. | 3 |
| 4 | US29 | Sección ¿Cómo funciona? | Como visitante, deseo entender el proceso del servicio antes de contratar. | 2 |
| 5 | US31 | Testimonios Reales | Como visitante, deseo leer reseñas para confiar en la marca. | 2 |
| 6 | US30 | Implementación i18n | Como visitante, deseo cambiar idioma ES/EN para navegar cómodamente. | 5 |
| 7 | US1 | Contratar Plan | Como administrador, deseo elegir un plan para digitalizar y escalar mi operación. | 5 |
| 8 | US2 | Registro de Conductores | Como administrador, deseo crear cuentas de conductores para asignar responsabilidades. | 3 |
| 9 | US4 | Alta de Alumnos | Como administrador, deseo registrar alumnos para incluirlos en rutas. | 5 |
| 10 | US3 | Registro de Padres | Como administrador, deseo registrar padres para habilitar monitoreo. | 3 |
| 11 | US5 | Creación de Rutas | Como administrador, deseo crear rutas y paradas para optimizar tiempos. | 8 |
| 12 | US6 | Asignación de Roles | Como administrador, deseo asignar conductores a rutas para organizar operaciones. | 3 |
| 13 | US10 | Inicio de Trayecto | Como conductor, deseo iniciar la ruta para notificar que estoy en camino. | 3 |
| 14 | US11 | Marcación de Abordaje | Como conductor, deseo registrar el abordaje para confirmar asistencia. | 5 |
| 15 | US18| Rastreo en Tiempo Real | Como padre, deseo ver la movilidad en el mapa para calcular hora de llegada. | 8 |
| 16 | US19 | Alerta de Proximidad | Como padre, deseo recibir aviso cuando el vehículo esté cerca. | 5 |
| 17 | US20 | Confirmación de Llegada | Como padre, deseo saber si mi hijo llegó al colegio para estar tranquilo. | 3 |
| 18 | US14 | Finalización de Ruta | Como conductor, deseo cerrar la ruta para concluir el servicio. | 2 |
| 19 | US12 | Reporte de Incidencias | Como conductor, deseo informar retrasos o problemas durante la ruta. | 5 |
| 20 | US16 | Navegación Integrada | Como conductor, deseo abrir mapas externos para usar la mejor ruta disponible. | 3 |
| 21 | US7 | Analítica de Flota | Como administrador, deseo revisar métricas de rendimiento operativo. | 8 |
| 22 | US22 | Historial de Asistencia | Como padre, deseo revisar asistencia mensual de mi hijo. | 5 |
| 23 | US15 | Bitácora de Viajes | Como conductor, deseo consultar historial de viajes realizados. | 3 |
| 24 | US23 | Perfil del Estudiante | Como padre, deseo registrar alergias o datos médicos relevantes. | 5 |
| 25 | US24 | Chat con Soporte | Como padre, deseo reportar ausencias o dudas desde la app. | 5 |
| 26 | US13 | Botón de Pánico | Como conductor, deseo activar SOS en emergencias críticas. | 8 |

---

## Capítulo IV: Product Design
### 4.1. Style Guidelines
#### 4.1.1. General Style Guidelines
#### 4.1.2. Web Style Guidelines
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

Plantilla de colores:
![Plantilla](assets/images/ChapterIV/EventStorming/ColorPosit.png)

1. Unstructured Exploration
   ![BigPicture](assets/images/ChapterIV/EventStorming/BigPicture.png)

En esta fase inicial, identificamos los eventos de dominio fundamentales para la movilidad escolar. El objetivo es capturar los hitos de negocio que permiten la interacción segura entre padres, conductores y administradores sin priorizar aún la cronología. Los eventos se organizan en seis ejes principales:

- Identidad y Gestión de Accesos (IAM): Maneja la seguridad y autenticación de la plataforma. Incluye eventos como el inicio de sesión (Login), autenticación de usuarios (Authenticate User), emisión de tokens JWT para sesiones seguras y el registro de administradores.

- Gestión de Suscripciones y Planes: Controla el acceso comercial a las funcionalidades de la plataforma. Abarca la selección de planes, el procesamiento de pagos a través de pasarelas externas y la activación de funciones de gestión de rutas según el plan elegido (básico, intermedio o completo).

- Gestión de Stakeholders y Activos: Administra los perfiles de los actores involucrados y sus relaciones. Incluye el registro de conductores, padres y estudiantes, así como la creación de grupos y la vinculación de hijos a sus respectivos padres para el seguimiento personalizado.

- Planificación de Flota y Rutas: Define la logística previa al viaje. Comprende la creación de geocercas para las rutas (RouteGeofenceCreated), la selección de puntos de parada (Pick Waypoints), la asignación de estudiantes a vehículos y la definición de horarios de salida.

- Ejecución y Monitoreo de Viajes: Es el núcleo operativo en tiempo real. Captura el inicio del trayecto por el conductor (TripStarted), el registro del estado de abordaje de cada estudiante (StudentStatus) y la consulta activa de la información de la ruta durante el recorrido.

2. Timelines
   ![TimeLines](assets/images/ChapterIV/EventStorming/Timelines.png)

En este paso, los eventos se organizan en secuencias cronológicas para comprender el flujo natural de los procesos de negocio. Las líneas de tiempo clave incluyen:

- Flujo de Incorporación y Suscripción: Registro de administrador → Creación de organización → Selección de plan de suscripción → Procesamiento de pago → Activación de cuotas de servicios.

- Gestión de Stakeholders y Activos: Registro de conductores y padres → Vinculación de estudiante a padre → Creación de grupos de transporte → Registro de vehículos → Asignación de conductor a vehículo.

- Planificación de Rutas Institucionales: Definición de geocerca de la ruta → Selección de puntos de parada (waypoints) → Asignación de estudiantes a la ruta → Establecimiento de horarios de salida → Finalización de la activación de ruta.

- Ejecución de Viajes y Monitoreo: Inicio de viaje por el conductor → Consulta de información de ruta → Registro de abordaje del estudiante → Notificación automática al padre → Seguimiento de progreso en tiempo real.

- Gestión de Comunicaciones e Incidentes: Detección de anomalía → Generación de alerta de pánico de alta prioridad → Despacho de alerta a administradores/padres → Difusión de mensajes de estado (broadcast) → Visualización en línea de tiempo.

- Cierre de Operación: Llegada al destino final → Confirmación de descenso total de estudiantes → Finalización de viaje → Archivamiento de datos de ejecución → Liberación de recursos de flota.

Estas líneas de tiempo revelan las dependencias temporales y la naturaleza secuencial de las operaciones dentro del sistema, asegurando que el flujo de información viaje correctamente desde la base de datos hasta las notificaciones en el dispositivo del padre.

3. Pain Points
   ![PainPoints](assets/images/ChapterIV/EventStorming/PainPoints.png)

En esta etapa, se identifican las situaiciones en las que se generan los puntos de fricción, cuellos de botella y ciertos problemas que surgen durante los procesos operativos y administrativos. Los pain points detectados incluyen:

- Sincronización de Notificaciones: Retrasos en la entrega de alertas push al padre cuando el estudiante aborda el vehículo, generando incertidumbre innecesaria.

- Gestión de Errores en Abordaje: Fallos manuales del conductor al registrar el estado del estudiante (StudentStatus), lo que puede resultar en registros de asistencia incorrectos.

- Validaciones de Seguridad: Bloqueos o fallos en la generación de alertas de pánico de alta prioridad durante emergencias debido a pérdida de conectividad o errores del sistema.

- Asignación de Recursos: Errores en la vinculación manual de conductores a vehículos o rutas, impidiendo el inicio correcto del viaje en la plataforma.

- Fricción en el Pago y Suscripción: Interrupciones en el procesamiento de pagos que inhabilitan las cuotas de rutas y bloquean la operación diaria de la institución.

- Precisión de Geolocalización: Problemas de precisión en el GPS que confunden la ubicacion de checkpoints.

Identificar estos puntos críticos permite al equipo de SafeRoute priorizar el desarrollo de mecanismos de redundancia y mejorar la experiencia de usuario, asegurando que la comunicación entre el transporte y el hogar sea infalible.

4. Pivotal Points
   ![PivotalPoints](assets/images/ChapterIV/EventStorming/PivotalPoints.png)

Los puntos pivotales son eventos determinantes que marcan transiciones críticas en el ciclo de vida del servicio. Estos incluyen:

Activación de Suscripción: Este hito marca la transición de un estado de configuración restringida a uno operativo, habilitando las cuotas de rutas y conductores necesarias para funcionar.

Finalización de Definición de Ruta: Es el punto donde la planificación técnica termina y la ruta queda lista para ser asignada a un vehículo y un conductor.

Inicio de Viaje: Este evento activa el monitoreo en tiempo real y permite que los padres comiencen a visualizar el progreso del transporte en sus aplicaciones.

Registro de Abordaje (Student Boarded): Es el evento pivotal de comunicación; confirma la seguridad del estudiante y dispara automáticamente la notificación push hacia el tutor legal.

Generación de Alerta de Pánico: Cambia el estado del viaje de "Normal" a "Emergencia", activando protocolos de respuesta inmediata y priorizando la comunicación de red de seguridad.

Completación de Viaje: Marca el fin de la responsabilidad operativa del conductor sobre los estudiantes y archiva el registro para liberar los recursos de la flota.

Estos puntos son determinantes para la continuidad y el éxito de la movilidad escolar, ya que aseguran que cada fase del proceso se cumpla antes de pasar a la siguiente.

5. Commands
   ![Commands](assets/images/ChapterIV/EventStorming/Commands.png)

Los comandos representan las acciones o intenciones de los usuarios que desencadenan eventos en el sistema. Los principales comandos identificados son:

- Gestión de Identidad y Acceso (IAM): Registrar administrador, iniciar sesión, autenticar usuario, asignar rol, revocar privilegios.

- Gestión de Suscripciones y Planes: Seleccionar plan, iniciar proceso de pago, activar funciones de gestión, actualizar cuotas de conductores, cancelar servicio.

- Gestión de Stakeholders y Activos: Registrar conductor, registrar padre, vincular estudiante a pariente, registrar vehículo, crear grupo de transporte, asignar miembros al grupo.

- Gestión de Flota y Rutas: Definir geocerca, seleccionar puntos de parada (waypoints), asignar estudiantes a ruta, asignar vehículo a ruta, establecer horario de salida, finalizar activación de ruta.

- Ejecución de Viajes y Monitoreo: Iniciar viaje, consultar información de ruta, registrar estado de abordaje del estudiante, reportar incidente (botón de pánico), finalizar viaje.

- Comunicación y Notificaciones: Preparar notificación push, despachar alerta a padres, publicar mensaje de difusión (broadcast), mostrar mensaje en línea de tiempo.

6. Policies
   ![Policies](assets/images/ChapterIV/EventStorming/Polices.png)

Las políticas automatizan la lógica de negocio y aseguran la coherencia del sistema ante eventos críticos. Las políticas clave incluyen:

- Cuando el pago es exitoso → Activar suscripción y habilitar cuotas de rutas/conductores automáticamente.

- Cuando el conductor inicia un viaje → Notificar a todos los padres vinculados a esa ruta sobre el inicio del monitoreo en tiempo real.

- Cuando se registra el abordaje del estudiante → Despachar notificación push inmediata al dispositivo del padre correspondiente.

- Cuando se reporta un incidente (pánico) → Generar alerta de alta prioridad y transmitirla instantáneamente a los administradores y padres del grupo.

- Cuando se publica un mensaje de difusión → Mostrar el mensaje en la línea de tiempo de todos los miembros del grupo seleccionado.

- Cuando se confirma el descenso total de estudiantes → Marcar el viaje como completado y archivar los datos de ejecución.

- Cuando falla el registro de un stakeholder → Enviar una notificación de error con los detalles de validación al administrador.

7. Read Models
   ![ReadModels](assets/images/ChapterIV/EventStorming/ReadModels.png)

Los principales modelos de lectura identificados para garantizar la visibilidad del sistema son:

- Dashboard del Conductor: Vista detallada de la ruta asignada, lista de estudiantes por recoger, puntos de parada (waypoints) y estado de abordaje en tiempo real.

- Panel de Monitoreo para Padres: Visualización en tiempo real de la ubicación del vehículo, estado de seguridad del estudiante y línea de tiempo de eventos del viaje.

- Vista de Gestión de Grupos: Listado de estudiantes agrupados por ruta, vinculación con sus respectivos padres y estado de asistencia mensual.

- Estado de la Flota: Registro de vehículos activos, conductores asignados a cada unidad y disponibilidad de recursos para nuevas rutas.

- Historial de Incidentes: Registro cronológico de alertas de pánico, mensajes de difusión enviados y resoluciones de eventos de seguridad.

- Panel de Suscripción y Cuotas: Información sobre el plan activo, estado de los pagos y uso de las cuotas de rutas y conductores contratados.

- Directorio de Stakeholders: Lista completa de perfiles de usuarios (padres, conductores y administradores) con sus respectivos roles y privilegios de acceso.

8. External Systems
   ![ExternalSystems](assets/images/ChapterIV/EventStorming/ExternalSystems.png)

Las integraciones identificadas para la solución incluyen:

- Leaflet (Proveedor de Mapas): Se encarga de la visualización interactiva de las rutas, el trazado de geocercas (geofencing) y la gestión de coordenadas geográficas para el monitoreo en tiempo real.

- Resend (Servicio de Email): Utilizado para el envío de notificaciones transaccionales y correos electrónicos automáticos, como mensajes de bienvenida, confirmaciones de registro y alertas administrativas.

- PayPal (Pasarela de Pago): Servicio encargado de procesar de forma segura las transacciones financieras para la activación, renovación y actualización de los planes de suscripción institucional.

- MySQL (Gestión de Base de Datos): Actúa como el sistema externo de persistencia relacional encargado de almacenar y organizar toda la estructura de usuarios, rutas, vehículos y registros operativos.

9. Aggregates
   ![Aggregates](assets/images/ChapterIV/EventStorming/Aggregates.png)

Basado en los dominios operativos identificados, los agregados son:

User (Raíz): Gestiona la identidad del usuario, incluyendo credenciales de autenticación, roles asignados (Administrador, Padre, Conductor) y privilegios de acceso al panel de control.

Organization (Raíz): Controla la configuración de la institución, la gestión de miembros y la vinculación de la cuenta con los parámetros base del sistema institucional.

Subscription (Raíz): Administra el ciclo de vida del plan de servicios, integrando el procesamiento de pagos a través de PayPal para habilitar o restringir las cuotas de rutas y conductores disponibles.

Stakeholder (Raíz): Encapsula la información de padres y conductores, gestionando la vinculación crítica entre el tutor (padre) y el estudiante para asegurar el flujo de notificaciones.

Vehicle (Raíz): Maneja el registro de las unidades de transporte, sus especificaciones técnicas y los cambios de estado (activo/inactivo) dentro de la flota.

Route (Raíz): Coordina la definición logística del recorrido, incluyendo la creación de geocercas, la selección de paraderos (waypoints) y la asignación previa de estudiantes a la ruta.

Trip (Raíz): Controla la ejecución operativa en tiempo real, registrando el inicio del trayecto, los cambios en el estado de abordaje de los estudiantes y el log de incidentes generados durante el viaje.

10. Bounded Contexts
    ![BoundedContexts](assets/images/ChapterIV/EventStorming/BoundedContexts.png)

Los contextos delimitados organizan los agregados en dominios de negocio independientes, permitiendo que cada uno evolucione de manera autónoma para facilitar la escalabilidad del sistema:

- Identity & Access Management: Este contexto gestiona la seguridad perimetral, incluyendo la autenticación de usuarios, la creación de organizaciones, y la asignación de roles y privilegios para administradores, padres y conductores. Agregados: User, Organization.

- Subscription & Plan Management: Administra el ciclo de vida comercial del servicio. Se encarga de la selección de planes, el procesamiento de pagos mediante la integración con PayPal y la activación de las cuotas operativas de rutas y conductores contratados. Agregados: Subscription.

- Stakeholder & Asset Management: Maneja los perfiles de los actores críticos y los recursos físicos de la institución. Incluye el registro de conductores y padres, la vinculación esencial entre padres e hijos (estudiantes), y la gestión de la flota de vehículos. Agregados: Stakeholder, Vehicle.

- Route Planning & Execution: Coordina la logística integral, desde la planificación técnica hasta la operación en tiempo real. Cubre la definición de geocercas, la selección de paraderos, el monitoreo del abordaje de estudiantes y la gestión de incidentes durante el trayecto. Agregados: Route, Trip.

- Notifications & Communication: Actúa como el eje de interacción inmediata entre el transporte y el hogar. Orquesta el envío de notificaciones push (como el estado de abordaje del estudiante), alertas de pánico y mensajes de difusión general para mantener informados a los padres y administradores.

- Trip Execution & Monitoring: Es el núcleo operativo donde el conductor inicia el viaje, se registra el abordaje de estudiantes y se activa el log de incidentes. Coordina la ejecución y el seguimiento en tiempo real, permitiendo el registro exacto del estado de cada estudiante y la respuesta inmediata ante emergencias mediante alertas de pánico.


#### 4.6.2. Software Architecture Context Diagram
Este diagrama proporciona una vista de alto nivel de SafeRoute y su entorno. Ilustra cómo los actores principales (Administrador, Conductor, Padre/Tutor) y los sistemas externos (como PayPal para pagos, Leaflet para mapas y Resend para correos) interactúan lógicamente con la plataforma de gestión de transporte escolar.

![ContextDiagram](/assets/images/ChapterIV/C4/SystemContext.png)

#### 4.6.3. Software Architecture Container Diagrams
Aquí se detallan las unidades de despliegue principales del sistema. El diagrama muestra cómo SafeRoute se divide en una Landing Page, una aplicación interactiva en el cliente (SPA desarrollada en Vue 3), una API backend modularizada (Web Service en ASP.NET Core) y un repositorio persistente central (Base de Datos MySQL).

![ContainerDiagram](/assets/images/ChapterIV/C4/ContainerDiagram.png)

#### 4.6.4. Software Architecture Components Diagrams
Este diagrama ofrece la visión macro del backend. Demuestra cómo el monolito de ASP.NET Core está organizado lógicamente en siete Bounded Contexts independientes y un Shared Kernel (núcleo compartido de Value Objects), asegurando una separación clara de responsabilidades a nivel de dominio.

![WebServices](/assets/images/ChapterIV/C4/WebServiceComponents.png)

- Identity & Access Management:
Desglosa el módulo de identidad en su arquitectura interna de 4 capas (API, Application, Domain, Infrastructure). Ilustra cómo se maneja la autenticación de usuarios, la provisión de cuentas y la emisión de tokens de seguridad de forma aislada.
![WebServices](/assets/images/ChapterIV/C4/ComponentDiagram_IAM-dark.png)

- Subscription & Plan Management:
Muestra la estructura interna de 4 capas del contexto encargado de la monetización. Detalla el flujo desde el controlador REST hasta la infraestructura que se integra con PayPal para gestionar el ciclo de vida de los planes y pagos.
![WebServices](/assets/images/ChapterIV/C4/ComponentDiagram_Subscription-dark.png)

- Stakeholder & Asset Management:
Representa las capas internas del dominio que administra la información core del negocio: la creación y vinculación de perfiles para conductores, padres de familia y estudiantes.
![WebServices](/assets/images/ChapterIV/C4/ComponentDiagram_Stakeholder-dark.png)

- Route Planning & Execution:
Detalla la arquitectura modular (Controlador, Servicio, Dominio, Repositorio) encargada de la logística. Maneja toda la configuración previa al viaje, como la definición de paradas, asignación de vehículos y diseño de rutas mediante coordenadas GPS.
![WebServices](/assets/images/ChapterIV/C4/ComponentDiagram_Route-dark.png)

- Notifications & Communication:
Describe el módulo dedicado a la comunicación asíncrona en sus 4 capas. Orquesta la recepción de eventos internos (como un estudiante abordando) y utiliza su capa de infraestructura para emitir alertas y correos mediante el proveedor externo Resend.
![WebServices](/assets/images/ChapterIV/C4/ComponentDiagram_Notification-dark.png)

- Trip Execution & Monitoring:
Ilustra el núcleo operativo del sistema en sus 4 capas. Muestra cómo se procesa la lógica en tiempo real durante la ejecución del viaje, gestionando el registro de abordajes y el estado de la ruta del transporte escolar.
![WebServices](/assets/images/ChapterIV/C4/ComponentDiagram_Trip-dark.png)

- Shared Kernel:
Este diagrama expone las 4 capas transversales (Building Blocks) que fundamentan la arquitectura limpia del monolito. Detalla cómo se proveen clases base y utilidades compartidas: Middlewares en la capa API, interfaces y DTOs base en Application, Value Objects globales (TripId, StudentId) en Domain, y repositorios genéricos en Infrastructure, evitando la duplicidad de código en el resto de los Bounded Contexts.
![WebServices](/assets/images/ChapterIV/C4/ComponentDiagram_SharedKernel-dark.png)

### 4.7. Software Object-Oriented Design
#### 4.7.1. Class Diagrams

**BackEnd**
- Identity and Access Management:

![saferoute-iam](https://www.plantuml.com/plantuml/proxy?src=https://raw.githubusercontent.com/PowerTech-NRC12053/saferoute-platform/main/saferoute-asp-net-developer/Safer-Route-Platform/docs/saferoute-iam.puml)

Gestiona organizaciones, usuarios y roles. Contiene dos Aggregate Roots y una Entity:
Organization (AggregateRoot) — Tiene -id: OrganizationId, -name: OrganizationName, -status: OrganizationStatus y -createdAt: DateTime. Expone métodos públicos para su ciclo de vida: Create(), Activate(), Suspend() e IsActive(). Se relaciona 1:1 con OrganizationId (identified by), OrganizationName (has) y OrganizationStatus (has).
User (AggregateRoot) — Tiene -id: UserId, -organizationId: OrganizationId, -fullName: FullName, -email: Email, -passwordHash: PasswordHash y -role: Role. Expone Register(), Authenticate(password), ChangeRole(role). Se asocia 1:1 con todos sus value objects y con la entidad Role (has). Pertenece a una organización vía OrganizationId compartido.
Role (Entity) — Referenciada desde User, tiene -id: int y -roleTier: RoleTier, con métodos IsAdmin(), IsDriver(), IsParent(). Se asocia 1:1 con RoleTier (categorized by).
Los Value Objects propios (OrganizationName, OrganizationStatus, Email, PasswordHash, RoleTier) encapsulan strings privados con validaciones y métodos de consulta públicos. PasswordHash es especial: expone Hash() y Verify().

- Subscription & Plan Management: 

![saferoute-subscription](https://www.plantuml.com/plantuml/proxy?src=https://raw.githubusercontent.com/PowerTech-NRC12053/saferoute-platform/main/saferoute-asp-net-developer/Safer-Route-Platform/docs/saferoute-subscription.puml)

Gestiona los planes y suscripciones de cada organización.
Subscription (AggregateRoot) — Atributos: id, organizationId, planId, -state: SubscriptionState, startDate, endDate. Métodos: Activate(), Upgrade(planId), Cancel(), IsActive(), GetRemainingDays(). Se asocia 1:1 con User del bounded context IAM (owned by), indicando dependencia entre contextos.
Plan (AggregateRoot) — Atributos: id, -planTier: PlanTier, -routeQuota: RouteQuota, -driverQuota: DriverQuota, price: decimal. Métodos: GetPlanName(), GetRouteLimit(), GetDriverLimit(), IsWithinRouteQuota(), IsWithinDriverQuota(). Asociado 1:1 con PlanTier, RouteQuota y DriverQuota.
Value Objects propios: SubscriptionState (active/expired/cancelled), PlanTier (basic/intermediate/complete), RouteQuota y DriverQuota (encapsulan límites enteros con validación de cuota).

- Stakeholder & Asset Management: 

![saferoute-stakeholder](https://www.plantuml.com/plantuml/proxy?src=https://raw.githubusercontent.com/PowerTech-NRC12053/saferoute-platform/main/saferoute-asp-net-developer/Safer-Route-Platform/docs/saferoute-stakeholder.puml)

Modela a los actores humanos del sistema: padres, conductores, hijos y grupos de estudiantes.
Parent (AggregateRoot) — Atributos privados: id, organizationId, userId, fullName, email, phoneNumber y -children: List<Child>. Métodos públicos: AddChild(), RemoveChild(), GetChildren(). Composición 1:1..* con Child (has): un Parent debe tener al menos un hijo.
Driver (Entity) — Similar a Parent pero agrega -licenseNumber: LicenseNumber. Métodos: IsAvailable(), GetLicenseNumber(), UpdatePhoneNumber(). Sin composición propia, referenciado desde otros contextos vía DriverId compartido.
Child (Entity, compuesta dentro de Parent) — Atributos: id, fullName, age: int y -enrollmentState: ChildEnrollmentState. Métodos: Enroll(), Unenroll(), IsEnrolled().
StudentGroup (Entity) — Agrupa referencias a hijos (-children: List<ChildId>) sin poseerlos directamente. Métodos: AddChild(), RemoveChild(), Finalize(), IsFinalized(). Relación 1:1..* con ChildId compartido (groups).

- Fleet & Route Planning: 

![saferoute-fleet](https://www.plantuml.com/plantuml/proxy?src=https://raw.githubusercontent.com/PowerTech-NRC12053/saferoute-platform/main/saferoute-asp-net-developer/Safer-Route-Platform/docs/saferoute-fleet.puml)

Gestiona rutas, vehículos, paradas y asignaciones.
Route (AggregateRoot) — Atributos: id, organizationId, name, routeState, departureTime, serviceDays, vehicle, assignment y -stops: List<Stop>. Métodos: DefineRoute(), AddStop(), RemoveStop(), Activate(), Deactivate(), GetStopSequence(). Tiene composición 1:1..* con Stop (has): una ruta requiere al menos una parada. Se relaciona 1:1 con Vehicle y Assignment.
Stop (Entity) — Atributos: id, name, coordinates: Coordinates, -stopOrder: StopOrder. Métodos: GetNextStop(), IsFirst(), IsLast(), UpdateCoordinates(). Asociada a Coordinates del shared kernel.
Vehicle (Entity) — Atributos: id, organizationId, plate, model, capacity: int, brand. Métodos: IsAvailable(), GetPlate(), GetCapacity(), UpdateDetails().
Assignment (Entity) — Atributos: id, -driverId: DriverId, -children: List<ChildId>. Métodos: AssignDriver(), AssignChild(), RemoveChild(). Referencia 1:1..* a ChildId compartido (includes).
Value Objects propios: RouteState (draft/active/inactive), StopOrder (posición entera), DepartureTime (TimeSpan), ServiceDays (lista de días).

- Trip Execution & Monitoring: 

![saferoute-trip](https://www.plantuml.com/plantuml/proxy?src=https://raw.githubusercontent.com/PowerTech-NRC12053/saferoute-platform/main/saferoute-asp-net-developer/Safer-Route-Platform/docs/saferoute-trip.puml)

Gestiona la ejecución de viajes, asistencia e incidentes.
Trip (AggregateRoot) — Atributos: id, organizationId, routeId, driverId, tripState, startTime, endTime, -attendances: List<Attendance> e -incidents: List<Incident>. Métodos: Start(), Complete(), RecordBoarding(childId, state), ReportIncident(description), GetAttendanceSummary(), GetIncidentLog(). Composición 1:0..* con ambas entidades hijas.
Attendance (Entity) — Atributos: id, childId, -boardingState: BoardingState, boardedAt. Métodos: UpdateBoardingState(), IsBoarded(), GetBoardingTime(). Referencia al ChildId compartido (tracks) con multiplicidad 1:1.
Incident (Entity) — Atributos: id, -description: IncidentDescription, reportedAt. Métodos: Report(), GetDescription(), GetReportedAt(). Asociada 1:1 con IncidentDescription (described by).
Value Objects propios: TripState (pending/inProgress/completed), BoardingState (boarded/missing/omitted), IncidentDescription (con validación).

- Notifications & Communication:

![saferoute-notifications](https://www.plantuml.com/plantuml/proxy?src=https://raw.githubusercontent.com/PowerTech-NRC12053/saferoute-platform/main/saferoute-asp-net-developer/Safer-Route-Platform/docs/saferoute-notifications.puml)

Gestiona el envío de notificaciones hacia padres de familia.
Notification (AggregateRoot) — Atributos: id, organizationId, parentId, tripId, -category: NotificationCategory, -deliveryState: NotificationDeliveryState, -message: NotificationMessage, sentAt, -alerts: List<Alert> y -announcements: List<Announcement>. Métodos: Queue(), Dispatch(), MarkDelivered(), IsDelivered(), GetCategory(), GetMessage(). Composición 1:0..* con Alert y 1:0..* con Announcement.
Alert (Entity) — Atributos: id, triggeredAt. Métodos: Trigger(), GetTriggeredAt(), IsPanic(). Representa un evento de alerta puntual dentro de una notificación.
Announcement (Entity) — Atributos: id, routeId, -message: NotificationMessage, publishedAt. Métodos: Publish(), GetMessage(), GetPublishedAt(). Referencia RouteId del shared kernel (belongs to) con multiplicidad 1:1.
Value Objects propios: NotificationCategory (boarding/arrival/incident/panic), NotificationDeliveryState (queued/dispatched/delivered), NotificationMessage (encapsula contenido con validación).

- Shared:

![saferoute-shared](https://www.plantuml.com/plantuml/proxy?src=https://raw.githubusercontent.com/PowerTech-NRC12053/saferoute-platform/main/saferoute-asp-net-developer/Safer-Route-Platform/docs/saferoute-shared.puml)

Este módulo no pertenece a un bounded context específico sino que actúa como kernel compartido. Contiene exclusivamente Value Objects reutilizables a lo largo de toda la aplicación: OrganizationId, UserId, ParentId, DriverId, ChildId, RouteId, TripId, SubscriptionId, PlanId, FullName y Coordinates. Todos son inmutables, encapsulan un valor primitivo (Guid, string o double) con scope privado, y exponen métodos públicos como New(), Equals() y ToString(). FullName es el único con dos atributos (firstName, lastName) y agrega GetFullName() e IsValid(). Coordinates encapsula latitude y longitude como double con validación geoespacial.

**FrontEnd**
En todos los diagramas el componente raíz App actúa como contenedor principal: tiene composición (contains) con todos los componentes de cada bounded context, y recibe sus eventos mediante emisiones (emits).

- Identity and Access Management:

![saferoute-iam](https://www.plantuml.com/plantuml/proxy?src=https://raw.githubusercontent.com/PowerTech-NRC12053/saferoute-webapp/main/saferoute/docs/saferoute-frontend-iam.puml)

App compone cinco componentes: AdminLoginForm, AdminRegisterForm y UserLoginForm gestionan autenticación con atributos de formulario privados (email, password, errorMessage) y emiten eventos como admin-logged-in o login-failed hacia App. OrganizationForm y OrganizationProfile manejan la creación y visualización de la organización, emitiendo organization-created y edit-requested respectivamente. Los modelos User y Organization son usados directamente por los componentes correspondientes, con User asociado a Organization (belongs to).

- Subscription & Plan Management: 

![saferoute-subscription](https://www.plantuml.com/plantuml/proxy?src=https://raw.githubusercontent.com/PowerTech-NRC12053/saferoute-webapp/main/saferoute/docs/saferoute-frontend-subscription.puml)

App compone PlanSelector y SubscriptionStatus. PlanSelector permite elegir un plan de la lista disponible, emitiendo plan-selected. SubscriptionStatus muestra el estado actual de la suscripción con métodos getRemainingDays() e isActive(), emitiendo upgrade-requested y cancel-requested. SubModel se asocia a PlanModel (has) con multiplicidad 1:1.

- Stakeholder & Asset Management: 

![saferoute-stakeholder](https://www.plantuml.com/plantuml/proxy?src=https://raw.githubusercontent.com/PowerTech-NRC12053/saferoute-webapp/main/saferoute/docs/saferoute-frontend-stakeholder.puml)

App compone cuatro listas: ParentList, DriverList, ChildList y StudentGroupList. Cada una tiene atributos -searchQuery y métodos de filtrado, selección y eliminación, emitiendo eventos *-selected y *-deleted hacia App. Los modelos Parent, Driver, Child y StudentGroup son DTOs planos. ParentModel tiene composición con ChildModel (has), reflejando que un padre agrupa sus hijos.

- Fleet & Route Planning: 

![saferoute-fleet](https://www.plantuml.com/plantuml/proxy?src=https://raw.githubusercontent.com/PowerTech-NRC12053/saferoute-webapp/main/saferoute/docs/saferoute-frontend-fleet.puml)

App compone RouteForm, StopList, VehicleList y AssignmentForm. RouteForm gestiona creación/edición de rutas incluyendo paradas dinámicas (addStop, removeStop), emitiendo route-created. StopList permite reordenar paradas con reorderStops() emitiendo stops-reordered. VehicleList soporta búsqueda y selección. AssignmentForm gestiona la asignación de conductor e hijos a una ruta. RouteModel tiene composición con StopModel (has).

- Trip Execution & Monitoring: 

![saferoute-trip](https://www.plantuml.com/plantuml/proxy?src=https://raw.githubusercontent.com/PowerTech-NRC12053/saferoute-webapp/main/saferoute/docs/saferoute-frontend-trip.puml)

App compone TripDashboard, AttendanceChecklist e IncidentForm. TripDashboard controla el ciclo de vida del viaje (startTrip, completeTrip) emitiendo trip-started y trip-completed. AttendanceChecklist maneja el estado de embarque por niño (updateBoardingState, isAllBoarded), emitiendo boarding-updated. IncidentForm registra incidentes con validación, emitiendo incident-reported. TripModel tiene composición con AttendanceModel (tracks) e IncidentModel (records).

- Notifications & Communication:

![saferoute-notifications](https://www.plantuml.com/plantuml/proxy?src=https://raw.githubusercontent.com/PowerTech-NRC12053/saferoute-webapp/main/saferoute/docs/saferoute-frontend-notifications.puml)

App compone NotificationList, AlertPanel y AnnouncementForm. NotificationList filtra y marca notificaciones como leídas, emitiendo notification-read. AlertPanel gestiona alertas activas con soporte de pánico (triggerPanic, dismissAlert), emitiendo panic-triggered. AnnouncementForm publica comunicados asociados a una ruta, emitiendo announcement-published. NotificationModel tiene composición con AlertModel (triggers) y AnnouncementModel (includes).


### 4.8. Database Design
**- Identity & Access Management**

Este bounded context gestiona la seguridad perimetral del sistema. La tabla `organizations` actúa como raíz estructural, siendo referenciada por prácticamente todos los demás contextos. `users` centraliza las credenciales de autenticación (`email` UNIQUE, `password_hash`) y se vincula a `organizations` y `roles` mediante FK. `roles` es una tabla de catálogo con clave `INT` que define los niveles de acceso disponibles: administrador, conductor y padre de familia.

**Tabla: organizations**
| Atributo   | Tipo         |
|------------|--------------|
| id         | CHAR(36) (PK)|
| name       | VARCHAR(100) |
| status     | VARCHAR(20)  |
| created_at | DATETIME     |

**Métodos**
| Método        | Descripción                          |
|---------------|--------------------------------------|
| Create()      | Crea una nueva organización.         |
| Activate()    | Activa la organización.              |
| Suspend()     | Suspende la organización.            |
| IsActive()    | Verifica si la organización está activa. |

---

**Tabla: roles**
| Atributo | Tipo        |
|----------|-------------|
| id       | INT (PK)    |
| name     | VARCHAR(20) |

**Métodos**
| Método         | Descripción                        |
|----------------|------------------------------------|
| GetRoleName()  | Retorna el nombre del rol.         |
| IsAdmin()      | Verifica si el rol es administrador.|
| IsDriver()     | Verifica si el rol es conductor.   |
| IsParent()     | Verifica si el rol es padre.       |

---

**Tabla: users**
| Atributo        | Tipo         |
|-----------------|--------------|
| id              | CHAR(36) (PK)|
| organization_id | CHAR(36) (FK)|
| role_id         | INT (FK)     |
| first_name      | VARCHAR(100) |
| last_name       | VARCHAR(100) |
| email           | VARCHAR(255) |
| password_hash   | VARCHAR(255) |
| created_at      | DATETIME     |

**Métodos**
| Método                      | Descripción                              |
|-----------------------------|------------------------------------------|
| Register()                  | Registra un nuevo usuario.               |
| Authenticate(password)      | Autentica al usuario con su contraseña.  |
| ChangeRole(role)            | Cambia el rol asignado al usuario.       |
| GetEmail()                  | Retorna el email del usuario.            |


---

**- Subscription & Plan Management**

Este bounded context administra el ciclo de vida comercial del servicio. La tabla `plans` es un catálogo que define los tiers disponibles y sus cuotas operativas. La tabla `subscriptions` vincula una organización a un plan y registra su estado, fecha de inicio y fecha de fin nullable, ya que una suscripción activa no tiene fecha de término definida.

**Tabla: plans**
| Atributo    | Tipo          |
|-------------|---------------|
| id          | INT (PK)      |
| plan_tier   | VARCHAR(20)   |
| max_routes  | INT           |
| max_drivers | INT           |
| price       | DECIMAL(10,2) |

**Métodos**
| Método                    | Descripción                                  |
|---------------------------|----------------------------------------------|
| GetPlanName()             | Retorna el nombre del tier del plan.         |
| GetRouteLimit()           | Retorna el límite de rutas del plan.         |
| IsWithinRouteQuota(n)     | Verifica si el valor está dentro de la cuota de rutas. |
| IsWithinDriverQuota(n)    | Verifica si el valor está dentro de la cuota de conductores. |

---

**Tabla: subscriptions**
| Atributo        | Tipo        |
|-----------------|-------------|
| id              | CHAR(36) (PK)|
| organization_id | CHAR(36) (FK)|
| plan_id         | INT (FK)    |
| state           | VARCHAR(20) |
| start_date      | DATETIME    |
| end_date        | DATETIME    |

**Métodos**
| Método            | Descripción                                  |
|-------------------|----------------------------------------------|
| Activate()        | Activa la suscripción.                       |
| Upgrade(planId)   | Cambia el plan de la suscripción.            |
| Cancel()          | Cancela la suscripción.                      |
| GetRemainingDays()| Retorna los días restantes de la suscripción.|


---

**- Stakeholder & Asset Management**

Este bounded context maneja los perfiles de los actores críticos y los recursos físicos de la institución. Las tablas `parents` y `drivers` referencian tanto `organization_id` como `user_id` (FK hacia IAM), separando los datos de perfil de las credenciales de acceso. `children` pertenece exclusivamente a un padre mediante `parent_id` FK. `student_groups` agrupa referencias lógicas a hijos mediante la tabla de unión `student_group_children`. `vehicles` registra la flota de transporte disponible por organización.

**Tabla: parents**
| Atributo        | Tipo         |
|-----------------|--------------|
| id              | CHAR(36) (PK)|
| organization_id | CHAR(36) (FK)|
| user_id         | CHAR(36) (FK)|
| first_name      | VARCHAR(100) |
| last_name       | VARCHAR(100) |
| email           | VARCHAR(255) |
| phone_number    | VARCHAR(20)  |

**Métodos**
| Método                  | Descripción                              |
|-------------------------|------------------------------------------|
| AddChild(child)         | Agrega un hijo al padre.                 |
| RemoveChild(childId)    | Elimina un hijo del padre.               |
| GetChildren()           | Retorna la lista de hijos del padre.     |
| GetEmail()              | Retorna el email del padre.              |

---

**Tabla: drivers**
| Atributo        | Tipo         |
|-----------------|--------------|
| id              | CHAR(36) (PK)|
| organization_id | CHAR(36) (FK)|
| user_id         | CHAR(36) (FK)|
| first_name      | VARCHAR(100) |
| last_name       | VARCHAR(100) |
| email           | VARCHAR(255) |
| phone_number    | VARCHAR(20)  |
| license_number  | VARCHAR(50)  |

**Métodos**
| Método                       | Descripción                                 |
|------------------------------|---------------------------------------------|
| IsAvailable()                | Verifica si el conductor está disponible.   |
| GetLicenseNumber()           | Retorna el número de licencia.              |
| UpdatePhoneNumber(phone)     | Actualiza el número de teléfono.            |
| GetFullName()                | Retorna el nombre completo del conductor.   |

---

**Tabla: children**
| Atributo         | Tipo         |
|------------------|--------------|
| id               | CHAR(36) (PK)|
| parent_id        | CHAR(36) (FK)|
| first_name       | VARCHAR(100) |
| last_name        | VARCHAR(100) |
| age              | INT          |
| enrollment_state | VARCHAR(20)  |

**Métodos**
| Método         | Descripción                                    |
|----------------|------------------------------------------------|
| Enroll()       | Matricula al estudiante en el servicio.        |
| Unenroll()     | Retira la matrícula del estudiante.            |
| IsEnrolled()   | Verifica si el estudiante está matriculado.    |
| GetFullName()  | Retorna el nombre completo del estudiante.     |

---

**Tabla: student_groups**
| Atributo        | Tipo         |
|-----------------|--------------|
| id              | CHAR(36) (PK)|
| organization_id | CHAR(36) (FK)|
| name            | VARCHAR(100) |
| is_finalized    | BOOLEAN      |

**Métodos**
| Método              | Descripción                                   |
|---------------------|-----------------------------------------------|
| AddChild(childId)   | Agrega un estudiante al grupo.                |
| RemoveChild(childId)| Elimina un estudiante del grupo.              |
| Finalize()          | Marca el grupo como finalizado.               |
| GetChildCount()     | Retorna la cantidad de estudiantes del grupo. |

---

**Tabla: student_group_children**
| Atributo         | Tipo         |
|------------------|--------------|
| student_group_id | CHAR(36) (FK)|
| child_id         | CHAR(36) (FK)|

**Métodos**
| Método           | Descripción                                        |
|------------------|----------------------------------------------------|
| AssignChild()    | Asocia un estudiante a un grupo.                   |
| RemoveChild()    | Desvincula un estudiante de un grupo.              |

---

**Tabla: vehicles**
| Atributo        | Tipo         |
|-----------------|--------------|
| id              | CHAR(36) (PK)|
| organization_id | CHAR(36) (FK)|
| plate           | VARCHAR(20)  |
| model           | VARCHAR(100) |
| brand           | VARCHAR(100) |
| capacity        | INT          |

**Métodos**
| Método                        | Descripción                              |
|-------------------------------|------------------------------------------|
| IsAvailable()                 | Verifica si el vehículo está disponible. |
| GetPlate()                    | Retorna la placa del vehículo.           |
| GetCapacity()                 | Retorna la capacidad del vehículo.       |
| UpdateDetails(model, brand)   | Actualiza los datos del vehículo.        |


---

**- Route Planning & Execution**

Este bounded context coordina la planificación técnica de las rutas de transporte escolar. La tabla `routes` define cada ruta con su vehículo asignado, horario de salida y días de servicio. `stops` almacena los paraderos georreferenciados con coordenadas de alta precisión y orden de parada. `assignments` vincula una ruta con un conductor en cardinalidad 1:1, y `assignment_children` resuelve la relación muchos a muchos entre asignaciones y estudiantes.

**Tabla: routes**
| Atributo        | Tipo         |
|-----------------|--------------|
| id              | CHAR(36) (PK)|
| organization_id | CHAR(36) (FK)|
| vehicle_id      | CHAR(36) (FK)|
| name            | VARCHAR(100) |
| route_state     | VARCHAR(20)  |
| departure_time  | TIME         |
| service_days    | VARCHAR(100) |

**Métodos**
| Método              | Descripción                                  |
|---------------------|----------------------------------------------|
| Activate()          | Activa la ruta para operación.               |
| Deactivate()        | Desactiva la ruta.                           |
| AddStop(stop)       | Agrega un paradero a la ruta.                |
| GetStopSequence()   | Retorna la secuencia ordenada de paraderos.  |

---

**Tabla: stops**
| Atributo   | Tipo          |
|------------|---------------|
| id         | CHAR(36) (PK) |
| route_id   | CHAR(36) (FK) |
| name       | VARCHAR(100)  |
| latitude   | DECIMAL(10,8) |
| longitude  | DECIMAL(11,8) |
| stop_order | INT           |

**Métodos**
| Método                       | Descripción                                  |
|------------------------------|----------------------------------------------|
| IsFirst()                    | Verifica si es el primer paradero.           |
| IsLast()                     | Verifica si es el último paradero.           |
| UpdateCoordinates(coords)    | Actualiza las coordenadas del paradero.      |
| GetPosition()                | Retorna la posición del paradero en la ruta. |

---

**Tabla: assignments**
| Atributo  | Tipo         |
|-----------|--------------|
| id        | CHAR(36) (PK)|
| route_id  | CHAR(36) (FK)|
| driver_id | CHAR(36) (FK)|

**Métodos**
| Método                  | Descripción                                   |
|-------------------------|-----------------------------------------------|
| AssignDriver(driverId)  | Asigna un conductor a la ruta.                |
| AssignChild(childId)    | Agrega un estudiante a la asignación.         |
| RemoveChild(childId)    | Elimina un estudiante de la asignación.       |
| GetChildCount()         | Retorna la cantidad de estudiantes asignados. |

---

**Tabla: assignment_children**
| Atributo      | Tipo         |
|---------------|--------------|
| assignment_id | CHAR(36) (FK)|
| child_id      | CHAR(36) (FK)|

**Métodos**
| Método         | Descripción                                          |
|----------------|------------------------------------------------------|
| AssignChild()  | Asocia un estudiante a una asignación de ruta.       |
| RemoveChild()  | Desvincula un estudiante de una asignación de ruta.  |


---

**- Trip Execution & Monitoring**

Este bounded context es el núcleo operativo del servicio. La tabla `trips` registra cada ejecución real de una ruta, con `start_time` y `end_time` nullable dado que el viaje puede estar en curso. `attendances` captura el estado de abordaje de cada estudiante por viaje, con `boarded_at` nullable para casos de ausencia. `incidents` referencia tanto `trip_id` como `route_id`, permitiendo trazabilidad del evento al viaje específico y a la ruta afectada.

**Tabla: trips**
| Atributo        | Tipo         |
|-----------------|--------------|
| id              | CHAR(36) (PK)|
| organization_id | CHAR(36) (FK)|
| route_id        | CHAR(36) (FK)|
| driver_id       | CHAR(36) (FK)|
| trip_state      | VARCHAR(20)  |
| start_time      | DATETIME     |
| end_time        | DATETIME     |

**Métodos**
| Método                          | Descripción                                       |
|---------------------------------|---------------------------------------------------|
| Start()                         | Inicia el viaje.                                  |
| Complete()                      | Completa el viaje.                                |
| RecordBoarding(childId, state)  | Registra el estado de abordaje de un estudiante.  |
| IsInProgress()                  | Verifica si el viaje está en curso.               |

---

**Tabla: attendances**
| Atributo       | Tipo         |
|----------------|--------------|
| id             | CHAR(36) (PK)|
| trip_id        | CHAR(36) (FK)|
| child_id       | CHAR(36) (FK)|
| boarding_state | VARCHAR(20)  |
| boarded_at     | DATETIME     |

**Métodos**
| Método                       | Descripción                                     |
|------------------------------|-------------------------------------------------|
| UpdateBoardingState(state)   | Actualiza el estado de abordaje del estudiante. |
| IsBoarded()                  | Verifica si el estudiante abordó.               |
| GetBoardingTime()            | Retorna la hora de abordaje.                    |

---

**Tabla: incidents**
| Atributo    | Tipo         |
|-------------|--------------|
| id          | CHAR(36) (PK)|
| trip_id     | CHAR(36) (FK)|
| route_id    | CHAR(36) (FK)|
| description | TEXT         |
| reported_at | DATETIME     |

**Métodos**
| Método             | Descripción                             |
|--------------------|-----------------------------------------|
| Report()           | Registra el incidente.                  |
| GetDescription()   | Retorna la descripción del incidente.   |
| GetReportedAt()    | Retorna la fecha de reporte.            |


---

**- Notifications & Communication**

**Tabla: notifications**
| Atributo        | Tipo         |
|-----------------|--------------|
| id              | CHAR(36) (PK)|
| organization_id | CHAR(36) (FK)|
| parent_id       | CHAR(36) (FK)|
| trip_id         | CHAR(36) (FK)|
| category        | VARCHAR(20)  |
| delivery_state  | VARCHAR(20)  |
| message         | TEXT         |
| sent_at         | DATETIME     |

**Métodos**
| Método           | Descripción                                        |
|------------------|----------------------------------------------------|
| Queue()          | Encola la notificación para su envío.              |
| Dispatch()       | Despacha la notificación al destinatario.          |
| MarkDelivered()  | Marca la notificación como entregada.              |
| GetCategory()    | Retorna la categoría de la notificación.           |

---

**Tabla: alerts**
| Atributo        | Tipo         |
|-----------------|--------------|
| id              | CHAR(36) (PK)|
| notification_id | CHAR(36) (FK)|
| triggered_at    | DATETIME     |

**Métodos**
| Método            | Descripción                            |
|-------------------|----------------------------------------|
| Trigger()         | Activa la alerta.                      |
| IsPanic()         | Verifica si la alerta es de pánico.    |
| GetTriggeredAt()  | Retorna la hora en que se activó.      |

---

**Tabla: announcements**
| Atributo        | Tipo         |
|-----------------|--------------|
| id              | CHAR(36) (PK)|
| notification_id | CHAR(36) (FK)|
| route_id        | CHAR(36) (FK)|
| message         | TEXT         |
| published_at    | DATETIME     |

**Métodos**
| Método            | Descripción                                   |
|-------------------|-----------------------------------------------|
| Publish()         | Publica el comunicado.                        |
| GetMessage()      | Retorna el contenido del comunicado.          |
| GetPublishedAt()  | Retorna la fecha de publicación.              |
#### 4.8.1. Database Diagrams
Esta sección presenta y explica los Database Diagrams para cada bounded context de SafeRoute. Los diagramas modelan la persistencia relacional del sistema, especificando tablas, columnas, tipos de dato, constraints (PK, FK, NOT NULL, UNIQUE) y las relaciones entre tablas con su cardinalidad. Todos los identificadores primarios utilizan `CHAR(36)` para soportar UUIDs, a excepción de catálogos fijos como `roles` y `plans` que usan `INT`. Las relaciones entre bounded contexts se materializan mediante columnas FK que referencian los IDs del contexto origen.
![DataBase](/assets/images/ChapterIV/DataBase/SafeRoute-DataBase.png)

**Identity and Access Management**

El bounded context de IAM persiste las entidades centrales de identidad y acceso. La tabla `organizations` actúa como raíz del sistema, siendo referenciada por prácticamente todos los demás contextos. `users` centraliza las credenciales de autenticación (`email` UNIQUE, `password_hash`) y se vincula a `organizations` y `roles` mediante FK. `roles` es una tabla de catálogo con clave `INT` que define los niveles de acceso disponibles en el sistema.

![DataBase](/assets/images/ChapterIV/DataBase/DbIAM.png)

---

**SafeRoute.Subscription**

Este contexto gestiona los planes comerciales y el estado de suscripción de cada organización. La tabla `plans` es un catálogo con `INT` PK que define los tiers disponibles y sus cuotas (`max_routes`, `max_drivers`, `price`). `subscriptions` vincula una organización a un plan mediante FK y registra el ciclo de vida de la suscripción a través de `state`, `start_date` y `end_date` (nullable, ya que una suscripción activa no tiene fecha de fin definida).

![DataBase](/assets/images/ChapterIV/DataBase/DbSubscription.png)

---

**Stakeholder & Asset Management**

Este contexto persiste los actores humanos del sistema. `parents` y `drivers` referencian tanto `organization_id` como `user_id` (FK hacia IAM), separando los datos de perfil de las credenciales de acceso. `children` pertenece exclusivamente a un padre mediante `parent_id` FK. `student_groups` agrupa referencias lógicas a hijos a través de la tabla de unión `student_group_children`, que resuelve la relación muchos a muchos entre grupos y niños con `student_group_id` + `child_id` como clave compuesta.

![DataBase](/assets/images/ChapterIV/DataBase/DbStakeHolder.png)

---

**Fleet & Route Planning**

Este contexto modela la infraestructura operativa de transporte. `vehicles` pertenece a una organización y se asigna a rutas mediante FK en `routes`. `routes` almacena `departure_time` como `TIME` y `service_days` como `VARCHAR` serializado. `stops` define los puntos geográficos de cada ruta con coordenadas decimales de alta precisión (`DECIMAL(10,8)` y `DECIMAL(11,8)`) y un `stop_order` para secuenciamiento. `assignments` relaciona una ruta con un conductor en cardinalidad 1:1, y `assignment_children` resuelve la relación muchos a muchos entre asignaciones y niños.

![DataBase](/assets/images/ChapterIV/DataBase/DbFleet.png)

---

**Trip Execution & Monitoring**

Este contexto registra la ejecución operativa de cada viaje. `trips` referencia `organization_id`, `route_id` y `driver_id` como FK, con `start_time` y `end_time` nullable dado que el viaje puede estar en curso. `attendances` registra el estado de embarque de cada niño por viaje (`trip_id` + `child_id`), con `boarded_at` nullable para casos de ausencia. `incidents` referencia tanto `trip_id` como `route_id`, permitiendo trazabilidad del incidente tanto al viaje específico como a la ruta afectada.

![DataBase](/assets/images/ChapterIV/DataBase/DbTrip.png)

---

**Notifications & Communication**

Este contexto gestiona la comunicación hacia los padres. `notifications` referencia `organization_id`, `parent_id` y `trip_id`, registrando `category`, `delivery_state` y `message` con `sent_at` obligatorio. `alerts` pertenece a una notificación mediante `notification_id` FK y registra el momento exacto del disparo. `announcements` extiende la notificación con una referencia adicional a `route_id`, permitiendo comunicados asociados a una ruta específica con su propio `message` y `published_at`.

![DataBase](/assets/images/ChapterIV/DataBase/DbNotifications.png)



---

## Capítulo V: Product Implementation, Validation & Deployment
### 5.1. Software Configuration Management
#### 5.1.1. Software Development Environment Configuration

En esta sección se describen las herramientas y tecnologías utilizadas para el desarrollo del proyecto.

##### UX/UI Design

- **Figma**  
  Herramienta de diseño colaborativo utilizada para la creación de wireframes, mockups, prototipos y diseño de interfaces de usuario. Permite trabajar en equipo en tiempo real, facilitando la validación temprana de la experiencia del usuario.

---

##### Software Development

- **JetBrains Rider**  
  Entorno de desarrollo integrado (IDE) utilizado para el desarrollo del backend en C#.

- **Visual Studio Code**  
  Editor de código ligero utilizado como herramienta complementaria para el desarrollo frontend y edición de archivos del proyecto.

- **GitHub**  
  Plataforma de control de versiones utilizada para la gestión del código fuente y colaboración del equipo, implementando la metodología GitFlow para la organización del desarrollo.

- **HTML**  
  Lenguaje de marcado utilizado para la estructura de las interfaces web.

- **CSS**  
  Lenguaje de estilos utilizado para la presentación visual de la aplicación.

- **JavaScript (Vue.js)**  
  Framework utilizado para el desarrollo del frontend, permitiendo la creación de interfaces dinámicas e interactivas.

- **C#**  
  Lenguaje de programación utilizado para el desarrollo del backend de la aplicación.

---

### Software Deployment

- **GitHub Pages**  
  Servicio utilizado para el despliegue de la landing page del proyecto.

- **Vercel**  
  Plataforma utilizada para el despliegue del frontend desarrollado en Vue.js, permitiendo una integración continua y despliegue automatizado.

- **Railway**  
  Plataforma utilizada para el despliegue de servicios backend y APIs, facilitando la conexión entre frontend y backend en un entorno accesible en la nube.

#### 5.1.2. Source Code Management

Para el manejo del código fuente, utilizamos GitHub para colaborar entre miembros de equipo en multiples repositorios. A continuación se listan los enlaces de cada repositorio utilizado.

- Organización: <https://github.com/PowerTech-NRC12053>
- Repositorio de Landing Page: <https://github.com/PowerTech-NRC12053/SafeRoute-landing-page>
- Repositorio del informe: <https://github.com/PowerTech-NRC12053/SafeRoute-report>
- Repositorio del frontend: <https://github.com/PowerTech-NRC12053/SafeRoute-frontend-applications>
- Repositorio del backend: <https://github.com/PowerTech-NRC12053/SafeRoute-web-services>

En el repositorio del informe se seguirá un esquema de trabajo basado en GitFlow. La rama main almacenará la versión estable del informe correspondiente a cada entregable del trabajo, mientras que la rama develop concentrará la integración de avances validados por cada integrante antes de su consolidación final. A partir de develop, cada integrante creará ramas feature de trabajo para las secciones asignadas. Las ramas feature seguirán una nomenclatura asociada al capítulo o bloque trabajado, por ejemplo: feature/chapter-1-introduction-and-lean-ux, o feature/chapter-5-software-configuration-management. Esta convención permite identificar con claridad qué parte del informe está siendo desarrollada y reduce el riesgo de conflictos entre los miembros del equipo.

En los repositorios del Landing Page, Frontend y Backend también se utilizará GitFlow. En cada uno de ellos, la rama main contendrá las versiones estables del producto y la rama develop servirá como rama de integración del trabajo colaborativo. A partir de develop, se crearán ramas feature/... para el desarrollo de funcionalidades específicas. A diferencia del informe, en estos repositorios las ramas no estarán organizadas por capítulos, sino por funcionalidades o componentes del sistema. Algunos ejemplos de nomenclatura son: feature/home-page, feature/dashboard o feature/route-management. Esta convención nos permite que las ramas reflejen de manera directa el alcance funcional del producto en desarrollo.

No se realizarán cambios directos sobre la rama main, ya que esta representará únicamente versiones estables y listas para consolidarse como parte de un entregable. Del mismo modo, se evitará que los integrantes trabajen de forma continua directamente sobre la rama develop, ya que el flujo previsto consiste en desarrollar primero en ramas feature, integrar luego en develop y finalmente consolidar en main cuando el avance haya sido revisado y validado. Por tanto, el flujo general de trabajo será de la siguiente forma: feature → develop → main. Este esquema se alinea con la exigencia del curso de explicar la implementación de GitFlow mediante ramas principales, ramas de features, y convenciones para releases y hotfixes.

Asimismo, si se requiere corregir errores críticos sobre una versión estable, se podrán crear ramas hotfix/..., y si se decide preparar una versión de cierre antes de una entrega, se utilizarán ramas release/... de acuerdo con el flujo definido por GitFlow.

En relación con los mensajes de cada commit, el equipo aplicará Conventional Commits para mantener un historial más legible, consistente y profesional. Esta convención facilitará la revisión de avances y permitirá identificar rápidamente el propósito de cada uno de los cambios. Algunos prefijos que se utilizarán son:

- feat: incorporación de una nueva funcionalidad
- fix: corrección de errores
- docs: cambios en documentación
- style: cambios de formato o estilo sin alterar lógica
- refactor: reorganización interna sin agregar funcionalidad nueva
- test: incorporación o ajuste de pruebas
- chore: tareas de mantenimiento o configuración

Para el repositorio del informe se emplearán mensajes como docs(report): add project cover page o docs: add startup profile and lean ux process for chapter 1. Para los repositorios de software se utilizarán mensajes como feat: add school route registration, feat: implement student assignment to route o fix: correct login validation. Esta práctica contribuye a que la evidencia de commits sea coherente con el trabajo realizado por cada miembro

#### 5.1.3. Source Code Style Guide & Conventions

En esta sección se definen las convenciones de nombres y codificación adoptadas por el equipo para los lenguajes utilizados en el proyecto: HTML, CSS, JavaScript (Vue.js) y C#.

### Principios generales

- **Idioma estándar:** Todo el código fuente se desarrolla en inglés, incluyendo nombres de variables, funciones, clases, archivos y la documentación del código.
- **Legibilidad:** Se prioriza el uso de nombres descriptivos y claros, evitando abreviaciones innecesarias.
- **Consistencia:** Se mantiene un estilo uniforme en todo el proyecto para facilitar el trabajo colaborativo.
- **Nombres semánticos:**
  - Sustantivos para clases y componentes.
  - Verbos para funciones y métodos.

---

### HTML

- Los archivos terminan en `.html`.
- Se utilizan etiquetas semánticas como:
  - `<header>`, `<nav>`, `<section>`, `<article>`, `<footer>`.
- Se emplean atributos descriptivos para mejorar la accesibilidad (`alt`, `aria-*`).
- Estructura clara y ordenada para facilitar mantenimiento.

---

### CSS

- Los archivos terminan en `.css`.
- Las clases se nombran en **kebab-case**:
  - `.main-header`, `.route-card`, `.student-list`.
- Se mantiene consistencia visual mediante estilos reutilizables.

---

### JavaScript (Vue.js)

- Los archivos terminan en `.js`.
- Se utiliza **camelCase** para variables y funciones:
  - `getRoutes`, `calculateDistance`.
- Se prioriza el uso de `const` y `let`, evitando `var`.
- Los componentes de Vue siguen una estructura modular y reutilizable.
- Se mantiene separación clara entre lógica, presentación y datos.
- Se utilizan nombres descriptivos para props, métodos y eventos.

---

### C#

- Se sigue la convención estándar de **PascalCase**:
  - Clases: `StudentService`, `RouteController`.
  - Métodos: `GetStudents()`, `CreateRoute()`.
- Variables locales en **camelCase**:
  - `studentList`, `routeId`.
- Uso de sufijos por responsabilidad:
  - `Controller`, `Service`, `Repository`.
- Se mantiene una arquitectura organizada por capas (por ejemplo: Controllers, Services, Models).
- Se aplican buenas prácticas como separación de responsabilidades y reutilización de código.

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
#### 5.2.X. Sprint n
##### 5.2.X.1. Sprint Planning n
##### 5.2.X.2. Aspect Leaders and Collaborators
##### 5.2.X.3. Sprint Backlog n
##### 5.2.X.4. Development Evidence for Sprint Review
##### 5.2.X.5. Execution Evidence for Sprint Review
##### 5.2.X.6. Services Documentation Evidence for Sprint Review
##### 5.2.X.7. Software Deployment Evidence for Sprint Review
##### 5.2.X.8. Team Collaboration Insights during Sprint

---

## Conclusiones
### Conclusiones y recomendaciones
### Video About-the-Team

## Bibliografía

- Autoridad de Transporte Urbano para Lima y Callao. (2024). _Cifra de movilidades escolares autorizadas disminuyó en 25% en un año_. El Comercio. Recuperado el 9 de abril de 2026, de https://elcomercio.pe/lima/cifra-de-movilidades-escolares-autorizadas-disminuyo-en-25-en-un-ano-a-que-se-debe-esta-reduccion-informe-movilidad-escolar-noticia/

- Ministerio de Educación. (2023). _Resultados del Censo Educativo 2022_. ESCALE. Recuperado el 9 de abril de 2026, de https://escale.minedu.gob.pe/documents/10156/9345030/PPT_Censo_Educativo_2023_final.pdf

- Superintendencia de Transporte Terrestre de Personas, Carga y Mercancías. (2024). _Sutran (MTC) sensibilizó a más de 47 000 escolares sobre seguridad vial_. Gob.pe. Recuperado el 9 de abril de 2026, de https://www.gob.pe/institucion/sutran/noticias/1255228-sutran-mtc-sensibilizo-a-mas-de-47-000-escolares-sobre-seguridad-vial-en-lo-que-va-del-2025

## Anexos
