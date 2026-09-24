# Proyecto final DAM / DAW

## Guía para la elaboración de la memoria

Esta guía sirve para ayudaros a redactar y organizar la memoria del proyecto final. La estructura se ha revisado para que el trabajo responda de forma clara a los resultados de aprendizaje y criterios de evaluación del módulo de proyecto establecidos en la normativa oficial.

La memoria no debe limitarse a describir el programa que habéis desarrollado. Debe demostrar que sois capaces de analizar una necesidad real, diseñar una solución viable, planificar su ejecución y establecer mecanismos para controlar y evaluar el proyecto.

Las explicaciones que aparecen bajo cada apartado son orientaciones para ayudaros a comprender **qué se espera que desarrolléis**. Debéis adaptarlas siempre a vuestro proyecto concreto.

------------------------------------------------------------------------

# 1. Introducción

En la introducción debéis presentar brevemente el proyecto y permitir que una persona que no lo conozca comprenda qué vais a desarrollar, qué problema pretende resolver y cuál será el alcance general del trabajo.

Intentad responder, de forma resumida, a cuestiones como:

- ¿En qué consiste el proyecto?
- ¿Qué necesidad o problema pretende resolver?
- ¿A qué usuarios, clientes o entidades va dirigido?
- ¿Qué tipo de solución vais a desarrollar?
- ¿Cuáles son sus principales funcionalidades?
- ¿Qué tecnologías o recursos principales vais a utilizar?
- ¿Cómo se organizará el resto de la memoria?

La introducción debe funcionar como una visión general del documento. No es necesario entrar todavía en detalles técnicos; esos aspectos se desarrollarán en los apartados posteriores.

Como orientación, una extensión aproximada de una página suele ser suficiente.

------------------------------------------------------------------------

# 2. Identificación de necesidades del sector productivo

El primer resultado de aprendizaje consiste en **identificar necesidades del sector productivo y relacionarlas con proyectos que puedan satisfacerlas**.

En esta primera parte debéis demostrar que vuestro proyecto no aparece de forma aislada: existe un contexto profesional, unas empresas, unos usuarios y unas necesidades que justifican la solución que proponéis.

## 2.1. Empresas del sector por sus características organizativas y por el producto o servicio que ofrecen

El proyecto entra dentro del sector del desarrollo de aplicaciones para la organización y gestión de reuniones. Aunque existen plataformas generales de productividad y colaboración que incorporan funciones relacionadas con las reuniones, he bsucado principalmente empresas cuyo producto está directamente relacionado con la planificación, desarrollo y seguimiento de reuniones.

### Beenote

**Beenote** es una plataforma especializada en la gestión de reuniones, dirigida principalmente a equipos, comités, juntas directivas y organizaciones. Su objetivo es centralizar todo el proceso de una reunión en una única herramienta.

Entre sus principales funcionalidades se encuentran la creación de agendas, organización y priorización de los puntos, control del tiempo, gestión de asistentes, toma de notas, registro de decisiones, creación de tareas y elaboración de actas. También permite controlar el acceso a documentos y mantener un historial de las reuniones. La plataforma dispone además de aplicaciones móviles.

Su modelo de negocio es principalmente de **software como servicio (SaaS)** mediante suscripciones. Ofrece una prueba gratuita y diferentes opciones adaptadas al número de usuarios y a las necesidades de las organizaciones.

Por sus características, Beenote es una de las empresas que presenta una mayor similitud con el proyecto planteado.

### Tadum

**Tadum** es una aplicación centrada en la gestión de reuniones periódicas. Permite preparar agendas, organizar los diferentes puntos, tomar notas y elaborar las actas de las reuniones.

Una de sus características más relevantes es la continuidad entre reuniones, ya que permite mantener los puntos y tareas pendientes para tratarlos posteriormente. Este funcionamiento resulta especialmente interesante para el proyecto, puesto que una de las necesidades detectadas es evitar tener que copiar manualmente los puntos que no se han terminado de una reunión a otra.

Su propuesta está más centrada en la gestión sencilla de reuniones recurrentes que en la gestión empresarial general, por lo que constituye una referencia directa para estudiar cómo simplificar el proceso de preparación, desarrollo y seguimiento de una reunión.

### Decisions

**Decisions** es una empresa de software orientada a organizaciones que necesitan automatizar procesos y gestionar decisiones y flujos de trabajo. Dentro de sus productos y funcionalidades incluye herramientas relacionadas con la gestión de reuniones, agendas, decisiones y tareas.

Su propuesta está especialmente orientada a empresas y organizaciones de mayor tamaño y actualmente ofrece diferentes modalidades de servicio, incluyendo soluciones para organizaciones empresariales y grandes compañías. También permite diferentes opciones de despliegue y ofrece servicios de soporte y asistencia.

Aunque su producto es más amplio que el proyecto planteado, resulta una referencia interesante para estudiar cómo una herramienta de gestión de reuniones puede integrarse dentro de una plataforma empresarial más completa.

### Decidiq

**Decidiq** es una solución orientada a la gestión de reuniones y procesos de decisión en organizaciones. Su funcionamiento se centra en estructurar las reuniones, gestionar sus agendas y mantener un registro de las decisiones y acciones posteriores.

Su orientación hacia organizaciones y asociaciones resulta especialmente interesante para el proyecto, ya que permite estudiar una alternativa a las plataformas dirigidas exclusivamente a grandes empresas. Además, su relación con el ecosistema de **Nextcloud y el software libre** la diferencia de otras soluciones comerciales.

### Conclusión

Estas empresas muestran que existe un mercado consolidado para las herramientas de gestión de reuniones. Sin embargo, cada una se dirige a un público diferente. Beenote presenta una propuesta especialmente cercana al proyecto por reunir en una misma aplicación la preparación de la reunión, su desarrollo y el seguimiento posterior. Tadum resulta especialmente interesante por su gestión de los temas pendientes entre reuniones.

El proyecto planteado se diferenciaría principalmente por centrarse en **reuniones presenciales y en el uso desde dispositivos móviles**, buscando que los participantes puedan consultar la reunión, seguir el punto que se está tratando, controlar el tiempo, participar y registrar información en tiempo real sin necesidad de utilizar herramientas diferentes.

---

## 2.2. Empresas tipo: estructura organizativa y funciones de los departamentos

Las mayoria de empresas vistas pertenecen principalmente al sector del desarrollo de software y utilizan un modelo **SaaS** (Software as a Service), por lo que necesitan combinar las funciones relacionadas al desarrollo con otras áreas destinadas a comercializar el producto, atender al cliente y gestionar la empresa.

La estructura exacta depende del tamaño de cada compañía. Una empresa pequeña puede agrupar varias funciones en las mismas personas, mientras que una empresa de mayor tamaño dispone de departamentos independientes. Por ejemplo, Decisions cuenta con áreas relacionadas con dirección, producto, tecnología, ventas, servicios profesionales y gestión de personas.

Para una empresa dedicada al desarrollo de una aplicación de gestión de reuniones se podría plantear la siguiente estructura:

### Dirección

Se encarga de establecer los objetivos de la empresa, tomar las principales decisiones y coordinar el resto de departamentos. También define la estrategia del producto, el modelo de negocio y las prioridades de la empresa.

En una empresa pequeña, estas funciones podrían ser asumidas directamente por los fundadores.

### Análisis y producto

Este departamento estudia las necesidades de los usuarios y determina qué funcionalidades debe tener la aplicación. También establece las prioridades de desarrollo y analiza cómo mejorar el producto.

En este proyecto tendría especial importancia para estudiar cómo utilizan los usuarios la aplicación durante una reunión y detectar qué acciones deben poder realizar rápidamente desde el teléfono.

### Diseño y experiencia de usuario

Se encarga del diseño visual y de la experiencia de uso de la aplicación. Su objetivo es conseguir que las diferentes funciones sean fáciles de entender y utilizar.

En una aplicación centrada en reuniones presenciales, este departamento tendría especial importancia, ya que los usuarios deberían poder consultar y modificar información rápidamente mientras participan en la reunión.

### Desarrollo y tecnología

Es el departamento encargado de construir y mantener la aplicación. Entre sus funciones se encontrarían:

* Desarrollo de la aplicación.
* Desarrollo y mantenimiento de la base de datos.
* Creación y mantenimiento de las API.
* Corrección de errores.
* Actualizaciones y nuevas funcionalidades.
* Gestión de servidores e infraestructura.
* Seguridad de la aplicación.

En una empresa pequeña, varias de estas tareas podrían ser realizadas por los mismos desarrolladores.

### Calidad y pruebas

Se encarga de comprobar que la aplicación funciona correctamente antes de publicar nuevas versiones. Realiza pruebas para detectar errores y comprobar que las nuevas funcionalidades no afectan al resto del sistema.

También puede comprobar aspectos como el funcionamiento en diferentes dispositivos, la seguridad y el rendimiento de la aplicación.

### Marketing y comercial

Este departamento se encarga de dar a conocer la aplicación y conseguir nuevos clientes.

Entre sus funciones estarían:

* Publicidad y campañas de marketing.
* Gestión de redes sociales.
* Página web y contenido.
* Contacto con posibles clientes.
* Demostraciones del producto.
* Gestión de precios y planes de suscripción.

### Soporte y atención al cliente

Se encarga de resolver las dudas y problemas de los usuarios. También recoge sugerencias y problemas detectados por los clientes para transmitirlos al departamento de producto y desarrollo.

En Beenote, por ejemplo, existe soporte técnico y material de formación para ayudar a los usuarios a utilizar la plataforma.

### Administración y finanzas

Gestiona los aspectos económicos y administrativos de la empresa. Entre sus funciones se encuentran la facturación, los gastos, los presupuestos, los impuestos y el control de los ingresos procedentes de las suscripciones.

### Recursos humanos

Se encarga de la contratación y gestión de los trabajadores, así como de aspectos relacionados con la formación, organización interna y condiciones laborales.

En una empresa pequeña esta función puede ser asumida por la dirección o incluso externalizada.

### Estructura general

La estructura de una empresa de este tipo podría representarse de la siguiente manera:

```text
                         DIRECCIÓN
                             │
       ┌─────────────────────┼─────────────────────┐
       │                     │                     │
    PRODUCTO            TECNOLOGÍA          ADMINISTRACIÓN
       │                     │                     │
 ┌─────┴─────┐        ┌──────┴──────┐              │
 │           │        │             │              │
Análisis   Diseño   Desarrollo    Calidad       Finanzas
                      │
                 Infraestructura
       
       ┌─────────────────────┐
       │                     │
   COMERCIAL              SOPORTE
       │                     │
   Marketing          Atención al cliente
       │
     Ventas

                 RECURSOS HUMANOS
```

No sería necesario que una empresa recién creada contase desde el principio con todos estos departamentos. En sus primeras etapas podría existir un equipo reducido en el que una misma persona desempeñase varias funciones. Por ejemplo, los fundadores podrían encargarse de la dirección y administración, mientras que un pequeño equipo de desarrollo asumiría también parte del análisis, las pruebas y el mantenimiento.

A medida que aumentase el número de usuarios y clientes, las funciones podrían separarse en departamentos especializados. De esta forma, la estructura evolucionaría junto con las necesidades de la empresa.

Esta organización permite observar que el desarrollo de una aplicación de software requiere mucho más que la programación del producto. Para que una herramienta de gestión de reuniones pueda mantenerse y crecer son necesarias también funciones de análisis, diseño, calidad, soporte, comercialización y administración.


## 2.3. Necesidades más demandadas a las empresas

A partir de la investigación anterior, identificad qué necesidades parecen demandar con mayor frecuencia los clientes o usuarios del sector.

Pensad en problemas reales que puedan resolverse mediante software: automatización de procesos, gestión de información, comunicación, comercio electrónico, educación, análisis de datos, movilidad, seguridad, entretenimiento, accesibilidad, etc.

No basta con afirmar que una necesidad existe. Siempre que sea posible, justificad por qué la consideráis relevante a partir de vuestro análisis del sector.

## 2.4. Oportunidades de negocio previsibles en el sector

Además de estudiar la situación actual, debéis analizar posibles oportunidades futuras.

Podéis considerar cambios tecnológicos, nuevas formas de consumo, transformación digital, inteligencia artificial, automatización, servicios en la nube, dispositivos móviles, nuevas necesidades empresariales o cualquier otra tendencia relacionada directamente con vuestro proyecto.

El objetivo es explicar si existe una oportunidad razonable para una solución como la que proponéis.

Evitad afirmaciones excesivamente generales. Relacionad las oportunidades detectadas con vuestro proyecto concreto.

## 2.5. Tipo de proyecto requerido para responder a las demandas previstas

Una vez identificada la necesidad, debéis justificar qué tipo de proyecto resulta adecuado para resolverla.

Por ejemplo:

- aplicación web;
- aplicación multiplataforma;
- aplicación móvil;
- aplicación de escritorio;
- videojuego;
- servicio de red;
- plataforma cliente-servidor;
- sistema de gestión;
- API o servicio web;
- solución que combine varias de las anteriores.

Explicad por qué habéis elegido esa solución y no otra.

Podéis responder preguntas como: ¿necesita funcionar desde un navegador?, ¿requiere instalación?, ¿debe funcionar en varios dispositivos?, ¿necesita almacenar datos?, ¿existirán distintos tipos de usuario?, ¿necesita un servidor?, ¿debe integrarse con otros sistemas?

## 2.6. Características específicas del proyecto según los requerimientos

Transformad las necesidades detectadas en características concretas del proyecto.

Por ejemplo, si los usuarios necesitan acceder desde cualquier dispositivo, una característica podría ser disponer de una interfaz web adaptable. Si necesitan conservar información, el proyecto deberá incorporar persistencia de datos. Si existen distintos perfiles, será necesario implementar autenticación, autorización y gestión de permisos.

Intentad diferenciar entre:

- requisitos funcionales: qué debe hacer el sistema;
- requisitos no funcionales: seguridad, rendimiento, usabilidad, compatibilidad, disponibilidad, accesibilidad, mantenibilidad, etc.;
- condicionantes técnicos o externos.

Este apartado debe permitir comprender qué tendrá que cumplir el proyecto para responder realmente a la necesidad identificada.

## 2.7. Obligaciones fiscales, laborales y de prevención de riesgos y condiciones de aplicación

Analizad qué obligaciones serían aplicables si el proyecto se desarrollara en un contexto profesional real.

No es necesario convertir este apartado en un tratado jurídico. Debéis identificar las obligaciones que tengan relación con vuestro caso y explicar brevemente cómo afectarían al proyecto.

Según el proyecto, pueden existir aspectos relacionados con:

- actividad empresarial y facturación;
- contratación de personal;
- prevención de riesgos laborales;
- propiedad intelectual y licencias;
- protección de datos;
- condiciones de uso de servicios de terceros;
- otras obligaciones específicas de la actividad.

Si alguna cuestión no resulta aplicable, podéis indicarlo y justificarlo.

## 2.8. Posibles ayudas o subvenciones para la incorporación de nuevas tecnologías

Investigad si un proyecto de estas características podría acogerse a ayudas, programas de digitalización, emprendimiento, innovación o incorporación de nuevas tecnologías.

No es imprescindible que exista una ayuda concreta aplicable. Si no encontráis ninguna adecuada, indicadlo razonadamente.

Lo importante es demostrar que habéis considerado la posibilidad de financiación o apoyo externo.

## 2.9. Guion de trabajo para la elaboración del proyecto

Cerrad esta primera fase explicando, de manera general, cómo vais a abordar el proyecto.

Este guion será una primera visión del trabajo que posteriormente desarrollaréis con mayor detalle en la planificación.

Indicad las grandes etapas previstas: análisis, diseño, preparación del entorno, implementación, pruebas, documentación, despliegue, evaluación, etc., adaptándolas a vuestro proyecto.

------------------------------------------------------------------------

# 3. Diseño del proyecto

El segundo resultado de aprendizaje consiste en **diseñar el proyecto desarrollando explícitamente las fases que lo componen**.

En esta parte ya no nos centramos tanto en justificar que existe una necesidad, sino en definir de forma concreta la solución que pretendemos desarrollar y comprobar que es viable.

## 3.1. Información relativa a los aspectos que van a ser tratados en el proyecto

Describid con detalle los elementos que compondrán vuestra solución.

Podéis explicar:

- usuarios o perfiles;
- módulos principales;
- funcionalidades;
- arquitectura general;
- información que manejará el sistema;
- componentes de cliente y servidor;
- integraciones externas;
- mecanismos de autenticación;
- interfaces principales;
- despliegue previsto.

El objetivo es descomponer la idea general en partes suficientemente claras como para poder planificar después su desarrollo.

## 3.2. Estudio de viabilidad técnica

Debéis justificar que el proyecto puede realizarse con los conocimientos, tecnologías, recursos y tiempo disponibles.

Un proyecto final debe ser suficientemente completo para demostrar las competencias adquiridas, pero también debe ser realizable.

Analizad, entre otros aspectos:

- complejidad técnica;
- tecnologías necesarias;
- conocimientos disponibles y conocimientos que será necesario adquirir;
- disponibilidad de hardware y software;
- servicios externos necesarios;
- limitaciones;
- riesgos técnicos;
- tiempo disponible.

No planteéis un proyecto cuyo alcance sea imposible de asumir. Es preferible desarrollar correctamente un producto con un alcance razonable que proponer un sistema enorme que finalmente no pueda completarse.

## 3.3. Fases del proyecto, contenido y plazos de ejecución

Dividid el proyecto en fases claramente identificables.

Para cada fase indicad:

- qué se pretende conseguir;
- qué tareas contiene;
- qué resultado o entregable producirá;
- cuándo comenzará;
- cuándo debería finalizar;
- de qué fases anteriores depende, cuando corresponda.

Podéis representar esta información mediante una tabla, cronograma o diagrama de Gantt.

La planificación debe ser coherente con el tiempo real disponible.

## 3.4. Objetivos y alcance

Definid los objetivos concretos que pretendéis alcanzar.

Los objetivos deben ser verificables. En lugar de escribir únicamente «crear una buena aplicación», es preferible establecer objetivos como «implementar un sistema de autenticación con dos perfiles de usuario», «permitir operaciones CRUD sobre los datos principales» o «desplegar la aplicación en un servidor accesible mediante navegador».

También debéis definir el **alcance**: qué incluye el proyecto y qué queda expresamente fuera.

Definir los límites es importante para evitar que el proyecto crezca de forma incontrolada durante su desarrollo.

## 3.5. Actividades necesarias para el desarrollo

Identificad las actividades necesarias para poder realizar el proyecto.

No confundáis necesariamente una actividad preparatoria con una fase funcional del software.

Por ejemplo:

- preparar el equipo de desarrollo;
- instalar herramientas;
- configurar un repositorio;
- contratar o preparar un servidor;
- registrar un dominio;
- crear cuentas de servicios externos;
- preparar datos iniciales;
- configurar entornos de pruebas;
- obtener recursos gráficos o multimedia.

Indicad únicamente aquellas actividades que sean relevantes para vuestro proyecto.

## 3.6. Recursos materiales y personales necesarios

Enumerad los recursos necesarios para desarrollar el proyecto.

### Recursos materiales y técnicos

Por ejemplo:

- ordenadores;
- servidores;
- dispositivos móviles;
- periféricos;
- alojamiento;
- dominio;
- software;
- sistemas operativos;
- entornos de desarrollo;
- bases de datos;
- servicios externos;
- licencias.

Aunque utilicéis software gratuito o de código abierto, sigue siendo un recurso y conviene identificarlo.

### Recursos personales

Indicad qué perfiles profesionales serían necesarios si el proyecto se realizara en un contexto empresarial real: desarrollo, diseño, sistemas, pruebas, dirección de proyecto, soporte, etc.

Si el proyecto académico lo realiza una sola persona, podéis indicarlo, pero debéis ser capaces de analizar qué recursos humanos requeriría una ejecución profesional equivalente.

## 3.7. Necesidades de financiación

Estimad si sería necesario disponer de financiación para poner en marcha el proyecto.

Considerad costes como:

- hardware;
- licencias;
- alojamiento;
- dominios;
- servicios externos;
- publicación en plataformas;
- contratación de profesionales;
- promoción;
- mantenimiento inicial.

Si el proyecto puede ponerse en marcha con una inversión reducida, explicadlo. Si no necesita financiación externa, indicad igualmente por qué.

## 3.8. Documentación necesaria para el diseño

Indicad qué documentación necesitáis consultar o preparar para diseñar correctamente el proyecto.

Puede incluir:

- requisitos;
- documentación técnica de lenguajes y frameworks;
- documentación de APIs;
- modelos de datos;
- diagramas;
- especificaciones funcionales;
- normativa aplicable;
- licencias;
- manuales de servicios externos;
- criterios de accesibilidad, seguridad o protección de datos cuando correspondan.

La finalidad de este apartado es demostrar que el diseño no se realiza únicamente por intuición, sino apoyándose en información y documentación adecuada.

## 3.9. Aspectos que se deben controlar para garantizar la calidad

Definid qué entenderéis por calidad en vuestro proyecto.

Podéis establecer criterios relacionados con:

- cumplimiento de requisitos;
- funcionamiento correcto;
- ausencia de errores graves;
- usabilidad;
- accesibilidad;
- seguridad;
- rendimiento;
- compatibilidad;
- calidad del código;
- mantenibilidad;
- documentación;
- pruebas realizadas.

Los indicadores deben poder comprobarse posteriormente.

------------------------------------------------------------------------

# 4. Planificación de la ejecución

El tercer resultado de aprendizaje consiste en **planificar la ejecución del proyecto, determinando el plan de intervención y la documentación asociada**.

Ahora debéis convertir el diseño anterior en un plan de trabajo ejecutable.

## 4.1. Secuenciación de tareas según las necesidades de implementación

Desglosad el proyecto en tareas concretas y estableced su orden.

Por ejemplo, en una aplicación podría ser necesario diseñar primero el modelo de datos, preparar después la base de datos, implementar la lógica de negocio, desarrollar las interfaces y finalmente integrar y probar el conjunto.

En otros proyectos algunas tareas podrán realizarse en paralelo.

La secuencia debe responder a dependencias reales, no simplemente a un orden arbitrario.

## 4.2. Recursos y logística necesaria para cada tarea

Relacionad las tareas principales con los recursos que necesitan.

Una tarea de despliegue puede necesitar un servidor; una prueba móvil puede requerir dispositivos o emuladores; una integración puede necesitar credenciales de una API; una fase de diseño puede necesitar determinadas herramientas.

La pregunta que debéis responder es: **¿qué necesito tener preparado para poder ejecutar correctamente cada tarea?**

## 4.3. Permisos y autorizaciones

Analizad si alguna tarea requiere permisos o autorizaciones.

Pueden existir, por ejemplo:

- permisos de acceso a sistemas de una empresa;
- autorización para utilizar determinados datos;
- credenciales para servicios externos;
- permisos para publicar una aplicación;
- consentimiento para realizar pruebas con usuarios;
- licencias de uso de recursos.

Si no necesitáis permisos especiales, indicadlo y justificadlo.

No debéis afirmar que una autoridad concreta debe autorizar un tratamiento de datos salvo que realmente exista ese requisito legal para vuestro caso; lo importante es identificar correctamente las obligaciones y permisos aplicables.

## 4.4. Procedimientos para la ejecución de las tareas

Explicad qué procedimientos utilizaréis para trabajar de forma ordenada.

Por ejemplo:

- control de versiones;
- estrategia de ramas;
- copias de seguridad;
- revisión de código;
- nomenclatura;
- gestión de versiones;
- pruebas antes de integrar cambios;
- procedimiento de despliegue;
- registro de tareas;
- validación de entregables.

No todos los proyectos necesitan los mismos procedimientos. Seleccionad los que aporten valor a vuestro caso.

## 4.5. Riesgos inherentes a la ejecución y plan de prevención

Identificad los riesgos asociados al proyecto y explicad cómo los reduciréis.

Además de los riesgos propios del trabajo con equipos informáticos ---ergonomía, fatiga visual, riesgos eléctricos cuando se manipula hardware, etc.--- podéis considerar riesgos del propio proyecto:

- pérdida de información;
- fallo de hardware;
- indisponibilidad de servicios;
- errores de configuración;
- problemas de seguridad;
- retrasos;
- dependencia de tecnologías externas.

Para cada riesgo relevante podéis indicar su probabilidad, impacto, medidas preventivas y respuesta prevista.

## 4.6. Asignación de recursos materiales y humanos según los tiempos de ejecución

Relacionad la planificación temporal con los recursos.

Indicad qué recursos se necesitan en cada fase, durante cuánto tiempo y qué perfil profesional sería responsable en un escenario profesional.

Aunque el proyecto académico sea individual, este ejercicio permite demostrar que sois capaces de planificar el proyecto desde una perspectiva profesional.

## 4.7. Valoración económica

Realizad una estimación razonable del coste del proyecto.

Debéis considerar tanto recursos materiales como humanos.

No asumáis que el coste es cero simplemente porque ya tenéis un ordenador o porque realizáis el proyecto como estudiantes. El objetivo es estimar cuánto costaría desarrollar una solución equivalente en un contexto profesional.

Podéis contemplar:

- amortización o adquisición de equipos;
- licencias;
- servidores y servicios;
- dominios;
- publicación;
- recursos gráficos o multimedia;
- horas de trabajo de los perfiles profesionales necesarios;
- otros gastos directamente relacionados.

Explicad los criterios utilizados para realizar los cálculos.

## 4.8. Documentación necesaria para la ejecución

Indicad qué documentos serán necesarios durante la ejecución.

Por ejemplo:

- especificación de requisitos;
- modelo de datos;
- diagramas;
- planificación;
- documentación de APIs;
- instrucciones de despliegue;
- plan de pruebas;
- registro de incidencias;
- control de cambios;
- documentación técnica.

No se trata de repetir toda la memoria, sino de identificar la documentación que sirve realmente de apoyo a la ejecución.

------------------------------------------------------------------------

# 5. Seguimiento y control

El cuarto resultado de aprendizaje consiste en **definir procedimientos para el seguimiento y control de la ejecución del proyecto, justificando las variables e instrumentos empleados**.

Un proyecto profesional no termina con una planificación inicial. Durante su desarrollo debemos comprobar si el trabajo avanza correctamente, registrar problemas, gestionar cambios y evaluar los resultados.

## 5.1. Procedimiento de evaluación de las actividades realizadas

Explicad cómo comprobaréis que cada tarea o fase ha finalizado correctamente.

Podéis establecer, por ejemplo:

- criterios de aceptación;
- revisión de requisitos;
- pruebas funcionales;
- revisión del código;
- comprobación del entregable;
- demostración de funcionamiento;
- lista de verificación.

Para cada tarea importante debería existir alguna forma objetiva de decidir si está realmente terminada.

## 5.2. Indicadores de calidad

Definid indicadores que permitan evaluar la calidad del proyecto.

Intentad que sean concretos y comprobables. Por ejemplo:

- porcentaje de requisitos implementados;
- número de pruebas superadas;
- errores abiertos y cerrados;
- tiempos de respuesta;
- compatibilidad con los entornos definidos;
- cumplimiento de criterios de accesibilidad;
- cobertura de documentación;
- incidencias detectadas por usuarios;
- cumplimiento de convenciones de código.

No es necesario utilizar todos estos indicadores. Elegid los que tengan sentido para vuestro proyecto y justificadlos.

## 5.3. Registro y evaluación de incidencias

Durante el desarrollo aparecerán errores, bloqueos, retrasos y cambios imprevistos.

Definid cómo vais a registrar las incidencias.

Un registro sencillo podría incluir:

- fecha;
- descripción;
- tarea afectada;
- gravedad o prioridad;
- causa;
- responsable;
- estado;
- solución aplicada;
- fecha de resolución.

El objetivo es que las incidencias no se resuelvan de forma informal sin dejar constancia de lo ocurrido.

## 5.4. Procedimiento para solucionar las incidencias

Explicad qué proceso seguiréis desde que se detecta una incidencia hasta que se considera resuelta.

Por ejemplo:

1. registrar la incidencia;
2. clasificar su prioridad;
3. reproducir y analizar el problema;
4. proponer una solución;
5. aplicar el cambio;
6. realizar pruebas;
7. documentar el resultado;
8. cerrar la incidencia.

Adaptad el procedimiento a vuestro proyecto.

## 5.5. Gestión y registro de cambios en recursos y tareas

La planificación inicial puede cambiar.

Puede ser necesario modificar una tecnología, ampliar o reducir una tarea, cambiar fechas, sustituir un servicio o redistribuir recursos.

Definid cómo registraréis estos cambios para poder comparar el plan inicial con lo que realmente ocurrió.

Para cada cambio podéis anotar:

- fecha;
- elemento modificado;
- situación inicial;
- modificación realizada;
- motivo;
- impacto en tiempo, coste o alcance;
- decisión adoptada.

## 5.6. Participación de los usuarios en la evaluación

Cuando sea posible, incorporad usuarios reales o representativos a la evaluación.

Podéis utilizar:

- pruebas de usuario;
- cuestionarios;
- entrevistas;
- observación;
- formularios de satisfacción;
- pruebas de usabilidad;
- sesiones de validación.

Explicad quién participaría, qué aspectos evaluaría y cómo registraríais los resultados.

Si vuestro proyecto no permite realizar pruebas con usuarios, justificadlo y plantead cómo podrían realizarse en un escenario real.

## 5.7. Cumplimiento del pliego de condiciones, cuando exista

Si el proyecto dispone de un pliego de condiciones, contrato, documento de requisitos o especificación formal, debéis definir cómo comprobaréis su cumplimiento.

Podéis utilizar una matriz de trazabilidad que relacione cada requisito con:

- la funcionalidad que lo implementa;
- la tarea en la que se desarrolla;
- la prueba que permite verificarlo;
- su estado final.

Si vuestro proyecto no dispone de un pliego de condiciones formal, indicadlo. Podéis utilizar como referencia equivalente vuestra propia especificación de requisitos y alcance.

------------------------------------------------------------------------

# 6. Conclusiones

Cerrad la memoria con una síntesis del proyecto realizado.

Las conclusiones deberían responder, al menos, a estas cuestiones:

- ¿se ha resuelto la necesidad inicialmente identificada?;
- ¿se han alcanzado los objetivos?;
- ¿qué resultado final se ha obtenido?;
- ¿cuáles han sido las principales dificultades?;
- ¿qué habéis aprendido?;
- ¿qué mejoras o ampliaciones podrían realizarse en el futuro?

Las conclusiones deben estar relacionadas con lo que realmente habéis desarrollado y con los objetivos establecidos al principio de la memoria.

------------------------------------------------------------------------

# 7. Bibliografía y fuentes consultadas

Incluid las fuentes que realmente hayáis utilizado durante el proyecto: documentación técnica, libros, artículos, normativa, manuales, documentación de lenguajes, frameworks, APIs, librerías o servicios.

Utilizad un formato coherente en todas las referencias.

No incluyáis fuentes que no hayan sido consultadas y diferenciad, cuando corresponda, entre bibliografía, documentación técnica y normativa.

------------------------------------------------------------------------

# Lista final de comprobación

Antes de entregar la memoria, comprobad que:

- habéis analizado empresas y necesidades reales del sector;
- habéis justificado el tipo de proyecto y sus requisitos;
- habéis definido objetivos y alcance;
- habéis realizado un estudio de viabilidad;
- habéis dividido el proyecto en fases y tareas;
- habéis establecido una planificación temporal;
- habéis identificado recursos materiales y humanos;
- habéis realizado una valoración económica;
- habéis contemplado riesgos, permisos y documentación;
- habéis definido procedimientos de ejecución;
- habéis establecido indicadores de calidad;
- habéis previsto cómo registrar incidencias y cambios;
- habéis explicado cómo evaluaréis el proyecto y, cuando proceda, cómo participarán los usuarios;
- habéis documentado las tecnologías empleadas;
- habéis realizado una autoevaluación y unas conclusiones coherentes;
- la memoria describe vuestro proyecto concreto y no contiene apartados genéricos sin relación con él.