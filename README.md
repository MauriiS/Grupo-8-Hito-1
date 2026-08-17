\## Nombre del caso de estudio:

Sistema de Soporte Técnico "TechSolve"



\## Nombre del equipo desarrollador:

Grupo C



\## Integrantes:

\- Santino Vignolo

\- Mauricio Sanchez

\- Martina Orzusa

\- Lucas Desia

\- Milagros Ibarra

\- Cintia Gomez



\## Descripción del sistema:

TechSolve es una aplicación web desarrollada para la empresa de logística internacional "RutaRápida", cuyo objetivo es automatizar la gestión de incidentes informáticos, el control del inventario de hardware y la administración del soporte a usuarios. 



El sistema permite a los empleados reportar fallas técnicas de manera ágil y sin depender de canales informales como WhatsApp, correo electrónico o el contacto directo con técnicos en pasillos. A través de un módulo de autogestión, el empleado puede cargar tickets de soporte categorizados, hacer seguimiento de su estado y agregar comentarios adicionales. Por su parte, los Técnicos de Soporte pueden visualizar y gestionar los tickets entrantes, mientras que el Gerente de TI cuenta con un tablero de control unificado para el seguimiento de indicadores clave del área.



\## Pantallas desarrolladas:

\## Breve explicación de cada una:



\- \*\*index.html (Inicio):\*\* Página principal del portal, con una bienvenida al usuario y un resumen de los servicios disponibles (solicitar ticket, consultar tickets, ver historial).



\- \*\*solicitar-ticket.html:\*\* Formulario para que el empleado cargue un nuevo ticket de soporte, indicando nombre y apellido, categoría del problema (Falla de Sistema, Acceso a Sistemas, Redes), título y descripción del incidente.



\- \*\*confirmacion.html:\*\* Pantalla de confirmación que se muestra luego de enviar el formulario de solicitud, informando al empleado que el ticket fue registrado exitosamente y que recibirá una notificación cuando sea confirmado.



\- \*\*mis-tickets.html:\*\* Vista donde el empleado puede consultar sus tickets activos en formato de tabla (ID, categoría, prioridad, estado), con la posibilidad de agregar un comentario adicional a un ticket existente.



\- \*\*historial.html:\*\* Listado del historial de tickets ya cerrados, mostrando para cada uno el ID, categoría, descripción, prioridad y estado.



\## Funcionalidades previstas para la siguiente entrega:

\- Implementación de la lógica de autenticación (inicio y cierre de sesión con credenciales corporativas).

\- Conexión del formulario de solicitud de ticket con el backend (Node.js) y persistencia en archivos JSON.

\- Asignación automática de prioridad según palabras clave del título del ticket.

\- Validación de la regla de negocio: máximo 3 tickets abiertos por empleado.

\- Desarrollo del panel del Técnico de Soporte (listado de tickets por urgencia, cambio de estado, envío de notificaciones al empleado).

\- Desarrollo del tablero de control del Gerente de TI (estadísticas, reporte de incidentes críticos, visualización de información confidencial con enmascaramiento por rol).

\- Implementación del Modo Oscuro forzado para la interfaz de técnicos.

