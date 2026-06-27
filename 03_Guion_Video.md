# Guion de Video - Sistemas Expertos

**Autor:** Angel Osvaldo Villalon Roca  
**Materia:** Programación Avanzada  
**Actividad:** Punto 5 - Video Expositivo  

---

## 🔗 Enlace al Video (YouTube)

> **[Insertar enlace de YouTube aquí]**  
> *(Actualiza este enlace después de subir el video en YouTube en modalidad "No listado")*

---

## 🎬 Guion del Video 

---

### INTRODUCCIÓN

Hola, mi nombre es Angel Osvaldo Villalon Roca, soy estudiante de la materia de Programación Avanzada. En el día de hoy, voy a presentarles un tema fundamental dentro de la Inteligencia Artificial: los Sistemas Expertos.

Estos sistemas son programas informáticos que simulan el razonamiento y la pericia de un experto humano en un dominio específico. A diferencia de la inteligencia artificial general, no buscan resolver cualquier problema, sino alcanzar maestría en tareas concretas mediante el uso de conocimiento especializado y razonamiento lógico.

Acompáñenme a descubrir qué son, cómo funcionan, su evolución histórica y sus aplicaciones prácticas.

---

### DIAPOSITIVA 2: ¿Qué es un Sistema Experto?

Un Sistema Experto es un programa informático que simula la pericia de un experto humano en un dominio específico.

Se caracteriza por dos aspectos fundamentales:

Primero, su enfoque específico. Estos sistemas no buscan ser inteligencia general, sino alcanzar maestría en un dominio acotado. Por ejemplo, un sistema experto médico no sirve para diseñar puentes, pero es excelente para diagnosticar enfermedades.

Segundo, el razonamiento explícito. Usan conocimiento especializado para tomar decisiones y, a diferencia de otros sistemas de IA, pueden explicar el razonamiento que los lleva a una conclusión. Esto es fundamental en áreas como la medicina o la ingeniería, donde cada decisión debe ser justificable.

---

### DIAPOSITIVA 3: El Conocimiento y Base de Conocimiento

El conocimiento es el activo central de cualquier sistema experto. Su organización y representación determinan la calidad del razonamiento.

Existen dos tipos de conocimiento en un sistema experto:

El conocimiento declarativo describe qué es el mundo: conceptos, objetos y sus propiedades. Por ejemplo, en un sistema médico, esto sería que la fiebre es un síntoma o que el cuerpo humano tiene una temperatura normal de 36.5 grados.

El conocimiento procedimental describe cómo se hace: estrategias, métodos y pasos para resolver problemas. Por ejemplo, si el paciente tiene fiebre y tos, entonces podría tener una infección respiratoria.

La Base de Conocimiento es donde se almacenan todos estos hechos y reglas. Es el repositorio que contiene la experiencia del experto humano, codificada en forma de reglas SI-ENTONCES y heurísticas.

Un principio clave en los sistemas expertos es la separación explícita entre el conocimiento del dominio y el mecanismo de razonamiento. Esto permite actualizar el conocimiento sin afectar cómo se procesa.

---

### DIAPOSITIVA 4: El Motor de Inferencia

El Motor de Inferencia es el componente lógico que procesa la información almacenada en la base de conocimientos. Es el cerebro operativo del sistema.

El motor aplica reglas y hechos para resolver problemas, realizar diagnósticos o tomar decisiones, modelando el proceso de razonamiento humano.

Utiliza dos métodos principales de razonamiento:

El encadenamiento hacia adelante parte de los hechos conocidos y aplica reglas hasta alcanzar una conclusión. Es ideal para monitoreo y control en tiempo real. Por ejemplo, si sabemos que un paciente tiene fiebre y tos, el sistema aplica reglas hasta concluir que podría tener una infección respiratoria.

El encadenamiento hacia atrás parte de una hipótesis y busca evidencias que la confirmen o refuten. Es ideal para diagnóstico. Por ejemplo, si el sistema sospecha que un paciente tiene neumonía, busca evidencias como fiebre, tos y dificultad para respirar para confirmar o descartar esa hipótesis.

Esta capacidad de razonar es lo que permite a los Sistemas Expertos llegar a conclusiones válidas y justificables.

---

### DIAPOSITIVA 5: Línea de Tiempo

Los sistemas expertos evolucionaron desde experimentos teóricos hasta herramientas industriales consolidadas en menos de tres décadas.

En 1965 nació DENDRAL, considerado el primer sistema experto. Fue desarrollado en la Universidad de Stanford para identificar estructuras moleculares en química orgánica.

En 1972 apareció MYCIN, un sistema para diagnosticar infecciones bacterianas. Logró una precisión del sesenta y cinco por ciento, superior al cuarenta y dos por ciento de los médicos juniors.

En 1980 llegó XCON, que configuraba sistemas VAX de DEC. Ahorró millones de dólares a la empresa al reducir errores de configuración.

En la década de 1990 hubo una caída debido a problemas de escalabilidad y mantenimiento, lo que se conoce como el invierno de la IA.

A partir del 2010, los sistemas expertos han resurgido como sistemas híbridos que combinan reglas con Machine Learning, potenciando la IA explicable y confiable.

---

### DIAPOSITIVA 6: Tipos de Sistemas Expertos

Los sistemas expertos se clasifican según el tipo de problema que resuelven.

Clasificación y Diagnóstico: relacionan situaciones observadas con causas conocidas para identificar el problema. MYCIN es un ejemplo clásico en el ámbito médico.

Predicción: anticipan eventos futuros basándose en patrones y tendencias del dominio. Por ejemplo, en finanzas para predecir el comportamiento del mercado.

Control y Monitorización: supervisan procesos en tiempo real y corrigen desviaciones automáticamente. Se usan en plantas industriales para mantener condiciones óptimas.

Diseño: construyen soluciones bajo restricciones técnicas y requisitos específicos. Por ejemplo, en ingeniería para diseñar estructuras o circuitos.

Cada tipo adapta el razonamiento a la naturaleza de la tarea, demostrando la versatilidad de estos sistemas.

---

### DIAPOSITIVA 7: ¿Por qué los usamos? (Ventajas)

Los sistemas expertos ofrecen ventajas estratégicas que los hacen indispensables en entornos críticos.

Productividad: mejoran la calidad y rapidez en la resolución de problemas complejos, reduciendo errores humanos. Un sistema experto no se cansa ni comete errores por fatiga.

Escalabilidad: permiten replicar la experiencia de un experto en múltiples ubicaciones sin coste adicional. Un solo sistema experto puede estar disponible en cientos de hospitales simultáneamente.

Confiabilidad: ofrecen justificaciones audibles y trazables. En medicina, ingeniería y sectores regulados, es fundamental que cada decisión pueda ser explicada y auditada.

En conclusión, los sistemas expertos representan uno de los primeros éxitos prácticos de la IA, demostrando que el conocimiento bien estructurado es tan poderoso como el algoritmo que lo procesa.

---

### CONCLUSIÓN FINAL

En resumen, los Sistemas Expertos nos enseñan que la clave de la Inteligencia Artificial no es sustituir al humano, sino amplificar su criterio. Entender su arquitectura, sus componentes y su evolución nos da las bases para construir software más robusto, confiable y explicable.

Como vimos en el archivo ia-y-programacion, la IA no eliminará la programación tradicional, pero la transformará. Los mejores programadores del futuro serán aquellos que sepan colaborar con la IA, entender problemas complejos y mantener un pensamiento crítico sobre el código generado.

Soy Angel Osvaldo Villalon Roca, muchas gracias por su atención. Les deseo éxito en sus proyectos.

---

### CIERRE TÉCNICO

Este video ha sido elaborado para la actividad 0.1.1 de la materia Programación Avanzada, correspondiente al tema de Sistemas Expertos e Inteligencia Artificial. Queda a disposición del profesor para su evaluación.