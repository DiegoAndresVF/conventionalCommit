# conventionalCommit

# Qué es conventional commit y por qué es importante usarlo?

Un Conventional Commit es una especificación para crear mensajes de commit que sigue un conjunto simple de reglas para que el historial de cambios sea explícito y legible tanto por humanos como por máquinas. Su objetivo es estandarizar los mensajes de commit para facilitar la automatización de tareas como la generación de registros de cambios (changelogs) y la actualización de versiones, además de mejorar la comprensión del historial del proyecto. 


**Componentes principales de un Conventional Commit**

* Tipo: Indica la naturaleza del cambio (ej. feat para una nueva característica, fix para una corrección de error). 

* Alcance (opcional): Describe la sección del código afectada (ej. feat(auth): o fix(ui):). 

* Descripción: Un resumen conciso del cambio en presente (ej. Add login functionality to the homepage). 

* Cuerpo (opcional): Proporciona contexto adicional y explicaciones más detalladas.

* BREAKING CHANGE: (opcional): Una sección para describir cambios importantes que rompen la compatibilidad con versiones anteriores, lo que se correlaciona con un cambio de versión mayor en el control de versiones semántico. 


**Beneficios clave**

* Automatización:
Facilita la creación de herramientas para generar automáticamente registros de cambios, actualizar versiones de paquetes y automatizar el proceso de lanzamiento. 

* Claridad:
Proporciona un historial de commit consistente y fácil de entender, lo que mejora la colaboración en equipo y permite comprender rápidamente los cambios. 

* Eficiencia:
Permite a los desarrolladores invertir menos tiempo en escribir mensajes de commit y más en la productividad, ya que el formato estandarizado reduce la ambigüedad


**Tipos principales**

* feat: Se utiliza para agregar una nueva funcionalidad. 

* fix: Se usa para corregir un error. 

* BREAKING CHANGE: Se incluye si el commit introduce un cambio que rompe la retrocompatibilidad con versiones anteriores. Este tipo puede ir acompañado de cualquier otro tipo, como feat(api)! o fix(auth). La palabra clave BREAKING CHANGE: debe aparecer en el cuerpo o pie del mensaje. 

Otros tipos comunes

* chore: Para tareas de mantenimiento que no modifican el código fuente ni los tests, como actualizar dependencias o modificar archivos de configuración. 

* docs: Para cambios que afectan únicamente a la documentación. 
* style: Para cambios que no afectan la lógica del código, como la corrección de estilos de código, formato o puntuación. 
* refactor: Cuando se reorganiza código existente sin añadir ni corregir funcionalidad. 
* perf: Para cambios que mejoran el rendimiento del código. 
* test: Para agregar o modificar tests. 
* build: Para cambios que afectan al sistema de compilación o a las dependencias externas. 
* ci: Para cambios en los scripts o archivos de configuración de la integración continua. 
* revert: Para revertir un commit anterior. Debe indicar el hash del commit que se está revirtiendo. 

\
\
\
\
![Logo](https://chile.generation.org/wp-content/uploads/2023/02/Generation_Chile_logo_BLUE_v2.svg)
