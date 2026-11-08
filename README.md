# Classroom_2.0
Un aula virtual más clara para estudiantes y docentes

Archivos:
Modificado/creado: index.html. Es un solo archivo de unos 190 KB, con HTML, CSS y JS, sin dependencias ni servidor. Parte de tu Classroom_2_0__3_.html (≈40 KB), que dejé intacto.
Cómo ejecutarlo: abre index.html en Chrome, Edge o Firefox con doble clic. No necesita conexión ni instalación.

Cómo probarlo:
Cambia de rol con el selector «Estudiante / Docente» de la cabecera.
Cambia el tema con el botón del círculo dividido.
Abre la búsqueda con Ctrl+K, o con la lupa en móvil.
Prueba el flujo completo entre roles (ver abajo).
En Ajustes puedes restablecer los datos de demostración.

Funciones nuevas:
Interfaz docente completa:
panel de control
asignaturas
creación de actividades
anuncios
gestión de estudiantes
revisión y calificación con rúbricas
seguimiento del progreso
estadísticas de clase

Estudiante:
detalle de tarea con entrega simulada y los 5 estados
calendario mensual y semanal
centro de notificaciones
gráfico de evolución de notas
debates y grupos de estudio
biblioteca con subida de recursos
centro de estudio
asistente de demostración
búsqueda global por categorías
ajustes de accesibilidad

Transversal:
tema claro y oscuro persistente
selector de rol
navegación móvil inferior
avisos emergentes
modales
estados vacíos
Lo que conservé y mejoré
Conservado: el estilo visual, la estructura de navegación, los datos de las 4 asignaturas y las vistas del estudiante.

Mejorado:
El tema ya no parpadea al cargar.
El calendario no desborda su panel.
Corregí el contraste en tema claro.
Etiqueté los campos que no tenían nombre accesible.
La barra lateral admite scroll.
Los avisos se limitan a 3 a la vez.
Interacciones que funcionan de punta a punta
Si el estudiante entrega una tarea, aparece en la cola de revisión del docente.
Si el docente califica, el estudiante recibe la nota con el desglose de la rúbrica y una notificación.
Si el docente publica un anuncio o crea una actividad en su clase de Cálculo, el estudiante la recibe como notificación y como tarea.
Búsquedas, filtros, favoritos, reacciones, comentarios, respuestas, Pomodoro, flashcards, cuestionarios y metas responden y se guardan al recargar.

¿Qué es simulado?
No hay inicio de sesión real. El rol es solo un selector de demostración.
Los datos son ficticios y viven en localStorage, sin API ni credenciales.
El asistente y el resumen de la biblioteca son respuestas generadas localmente, y ambos lo indican con una etiqueta.
Subir archivos solo registra el nombre. No guarda el contenido.
Las respuestas del docente a los comentarios privados son simuladas.
Verificación
