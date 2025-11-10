# 

# *[Seguridad en la Configuración de Sistemas Operativos]{.underline}*

**✏️ Datos Generales**

**Título del trabajo**: Seguridad en la configuración de sistemas
operativos

**Alumnos:** Braian Flores /
[[braian.flores.ig@gmail.com]{.underline}](mailto:braian.flores.ig@gmail.com)

Santino Naldini /santinaldini8@gmail.com

**Materia:** Arquitectura y Sistemas Operativos

**Profesor/a:** Roco

**Fecha de Entrega:** 10/11/2025

**📑 Índice**

**1. Introducción**

**2. Marco Teórico**

**3. Caso Práctico**

**4. Metodología Utilizada**

**5. Resultados Obtenidos**

**6. Conclusiones**

**7. Bibliografía**

**8. Anexos**

**1. Introducción**

La seguridad en la configuración de los sistemas operativos constituye
uno de los pilares fundamentales en el ámbito de la arquitectura de las
computadoras. En un contexto donde los ataques informáticos, la pérdida
de datos y las vulnerabilidades son cada vez más frecuentes, comprender
cómo proteger un sistema desde su núcleo resulta esencial para cualquier
técnico en programación.

El presente trabajo aborda la importancia de establecer configuraciones
seguras en los sistemas operativos, analizando sus componentes internos
y las estrategias utilizadas para resguardar la integridad,
disponibilidad y confidencialidad de la información.

El objetivo principal es reconocer los mecanismos que intervienen en la
protección del sistema operativo, comprendiendo su funcionamiento desde
la arquitectura del hardware hasta la gestión de permisos y procesos.
Asimismo, se busca fortalecer las competencias del estudiante en la
implementación de prácticas seguras, tanto en entornos personales como
profesionales.

## **2. Marco Teórico**

Un sistema operativo (SO) es el conjunto de programas que gestionan los
recursos de hardware y software de una computadora. Su función es
coordinar las operaciones entre el procesador, la memoria, los
dispositivos de entrada/salida y las aplicaciones. En el contexto de la
seguridad informática, el SO actúa como la primera línea de defensa
frente a amenazas internas y externas.

### **Conceptos Fundamentales**

-   **Seguridad en la arquitectura de las computadoras:** se refiere a
    > las medidas implementadas a nivel de hardware y software para
    > evitar accesos no autorizados y asegurar el correcto
    > funcionamiento del sistema. Incluye la segmentación de memoria,
    > los anillos de protección del procesador y el control de
    > privilegios.

-   **Gestión de usuarios y permisos:** los sistemas operativos modernos
    > aplican modelos de control de acceso basados en cuentas de
    > usuario, grupos y políticas de seguridad. Un ejemplo clásico es la
    > diferencia entre el usuario *root* o *administrador* y los
    > usuarios estándar.

-   **Mecanismos de protección del sistema:** entre ellos se encuentran
    > los firewalls, antivirus, actualizaciones automáticas, cifrado de
    > datos y control de integridad de archivos.

-   **Arquitectura segura:** los sistemas operativos utilizan modos de
    > ejecución protegidos (modo kernel y modo usuario) para aislar
    > procesos críticos y prevenir la manipulación directa del hardware
    > por programas no autorizados.

La configuración segura de un sistema operativo implica ajustar
correctamente estos elementos para minimizar vulnerabilidades. Un error
en permisos, una política de contraseñas débil o un servicio innecesario
habilitado pueden comprometer todo el sistema.

## **3. Caso Práctico (Simulación Teórica)**

Para este trabajo se plantea una simulación teórica basada en la
configuración segura de un sistema operativo Linux.

### **Escenario:**

Una pequeña empresa necesita implementar un servidor para almacenar
información de clientes y realizar copias de seguridad. Se busca
garantizar la seguridad del sistema mediante una configuración adecuada
del SO.

### **Acciones simuladas:**

1.  **Creación de usuarios y grupos:\
    > ** Se definen cuentas separadas para cada empleado con permisos
    > mínimos necesarios, evitando el uso del usuario *root* salvo para
    > tareas administrativas.

2.  **Configuración de permisos de archivos:\
    > ** Se asignan permisos según el principio de "menor privilegio",
    > de modo que cada usuario solo acceda a los archivos que requiere
    > para su trabajo.

3.  **Firewall y servicios:\
    > ** Se activa el cortafuegos del sistema y se deshabilitan
    > servicios innecesarios como el acceso remoto SSH para cuentas no
    > autorizadas.

4.  **Actualizaciones y parches:\
    > ** El sistema se configura para recibir actualizaciones
    > automáticas de seguridad, reduciendo el riesgo de explotación de
    > vulnerabilidades.

5.  **Cifrado de datos:\
    > ** Los directorios que contienen información sensible se cifran
    > mediante herramientas nativas como *LUKS* o *GnuPG*.

Esta simulación teórica demuestra cómo una correcta configuración del
sistema operativo puede prevenir ataques y proteger los recursos de la
organización.

## **4. Metodología Utilizada**

El desarrollo de este trabajo se basó en una investigación teórica de
fuentes oficiales y material académico sobre seguridad de sistemas
operativos. Se consultaron manuales técnicos, documentación de Linux y
bibliografía especializada en arquitectura de computadoras.

Las etapas seguidas fueron:

1.  Revisión conceptual sobre arquitectura y seguridad del sistema
    > operativo.

2.  Identificación de buenas prácticas de configuración segura.

3.  Simulación teórica de un entorno controlado aplicando dichas
    > prácticas.

4.  Análisis de resultados y elaboración de conclusiones.

Las herramientas conceptuales incluyeron la documentación de
distribuciones Linux y referencias bibliográficas de autores reconocidos
como Silberschatz y Stallings.

## **5. Resultados Obtenidos**

El estudio permitió reconocer la importancia de una configuración segura
desde el momento de la instalación del sistema operativo. La simulación
teórica evidenció que la mayoría de las vulnerabilidades no provienen
del hardware, sino de configuraciones deficientes o privilegios
excesivos otorgados a los usuarios.

También se observó que los mecanismos integrados en los sistemas
operativos actuales (control de acceso, cifrado, auditorías y
actualizaciones automáticas) son herramientas efectivas si se aplican
correctamente. El resultado más relevante fue comprender que la
seguridad no depende de un único componente, sino de una combinación
coherente de configuraciones y políticas preventivas.

## **6. Conclusiones**

El trabajo permitió comprender que la seguridad en la configuración de
los sistemas operativos es un aspecto esencial dentro de la arquitectura
de las computadoras, ya que garantiza la estabilidad y la protección de
los datos del usuario.

El alumno aprendió a identificar las áreas críticas de seguridad del
sistema operativo y la importancia de mantener políticas de acceso y
actualización adecuadas. Además, se destacó el valor del principio de
menor privilegio y de la segmentación de tareas como estrategias para
prevenir fallos y ataques.

Como posible mejora, se podría complementar este trabajo con una
práctica real sobre instalación y configuración segura de un sistema
Linux o Windows, aplicando las recomendaciones teóricas desarrolladas.

## **7. Bibliografía** 

-   Red Hat Documentation. *Security and Hardening Guide*.
    > [[https://access.redhat.com/documentation]{.underline}](https://access.redhat.com/documentation)

-   Microsoft Learn. (2024). *Security best practices for Windows
    > Server*.
    > [[https://learn.microsoft.co](https://learn.microsoft.com)m]{.underline}

-   [[Instituto Nacional de Ciberseguridad (INCIBE).
    > (2023).]{.underline} [*Guía de buenas prácticas en sistemas
    > operativos*.]{.underline}](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwjI9PiciuaQAxX6q5UCHYX4JK4QFnoECBkQAQ&url=https%3A%2F%2Fwww.incibe.es%2Fsites%2Fdefault%2Ffiles%2Fdocs%2Fsenior%2Fguia_ciberseguridad_para_todos.pdf&usg=AOvVaw2ORukEGCzrWmWNsGnGtlGb&opi=89978449)

-   [[Universidad Carlos III de Madrid.Introducción a la Seguridad -
    > SISTEMAS
    > OPERATIVOS]{.underline}](https://ocw.uc3m.es/pluginfile.php/3335/mod_page/content/19/introduccion_seguridad.pdf)

-   [[Universidad Nacional Del Sur. Seguridad y
    > Proteccion]{.underline}](https://cs.uns.edu.ar/~so/data/apuntes/SO-2020-mod%2013.pdf)

-   [[BlueHosting.Conceptos básicos de seguridad en
    > Linux]{.underline}](https://docs.bluehosting.cl/tutoriales/servidores/conceptos-basicos-de-seguridad-en-linux.html)
