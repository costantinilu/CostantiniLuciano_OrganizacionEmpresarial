# CostantiniLuciano_OrganizacionEmpresarial
Trabajo Práctico Integrador – Organización Empresarial
Descripción del proyecto

Este proyecto consiste en el desarrollo de un chatbot para la gestión de solicitudes de vacaciones de empleados.
El objetivo es automatizar un proceso administrativo interno de una organización, permitiendo que los empleados consulten y soliciten días de vacaciones mediante una conversación simple guiada por el sistema.
El chatbot valida el número de legajo, verifica la cantidad de días disponibles y determina automáticamente si la solicitud puede ser aprobada o rechazada.

Funcionalidades
Validación de legajo de empleado.
Consulta de días de vacaciones disponibles.
Solicitud de días de vacaciones.
Aprobación automática de solicitudes cuando existe saldo suficiente.
Rechazo automático cuando la cantidad solicitada supera los días disponibles.
Actualización de la información almacenada.
Posibilidad de realizar múltiples solicitudes en una misma sesión.
Base de datos simulada

Para simplificar el desarrollo del proyecto se utiliza un archivo CSV como mecanismo de persistencia de datos.
Archivo utilizado:
empleados.csv

El archivo contiene:
Legajo.
Nombre del empleado.
Cantidad de días de vacaciones disponibles.

Actualmente se incluyen únicamente cinco empleados para fines de prueba y demostración.

Se utilizó para el desarrollo: Python, Google Colab, GitHub, BPMN 2.0

Estructura del repositorio
CostantiniLuciano_OrganizacionEmpresarial                                                                                                   
│                                                                                                                                                              
├── BPMN.png  ---> Diagrama BPMN del proceso                                                                                                  
├── README.md  ---> Documentación del proyecto                                                                                                   
├── chatbot.ipynb  ---> Implementación del chatbot en Google Colab                                                                                             
└── empleados.csv  ---> Base de datos simulada de empleados                                                                                                  

Ejecución
1. Abrir el archivo del chatbot en Python o Google Colab.
2. Ejecutar todas las celdas del notebook o el script principal (según donde se ejecute)
3. Ingresar un número de legajo válido.
4. Ingresar la cantidad de días solicitados.
5. El sistema evaluará la solicitud e informará el resultado.
6. Lógica de negocio implementada
* Aclaración: Durante la ejecución del bot agregué algunos imput con "presioná enter" para que sea
más agradable ver como se va ejecutando paso a paso pero no forma parte del BPMN porque pensé
que no tenía sentido agregarlo.

El proceso fue modelado utilizando BPMN 2.0, incorporando:
Evento de inicio.
Actividades de usuario.
Actividades automatizadas del chatbot.
Decisiones lógicas.
Eventos de fin.
Carriles (Usuario y Sistema).

Luciano Costantini
Trabajo Práctico Integrador – Organización Empresarial.
