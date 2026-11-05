======================================================================
README - ESTRUCTURA Y ORGANIZACIÓN DEL PROYECTO MULTIMEDIA DIGITAL
======================================================================

1. LÓGICA DE LA ESTRUCTURA DE DIRECTORIOS:
----------------------------------------------------------------------
La estructura de directorios fue diseñada aplicando un criterio modular 
y funcional, agrupando los archivos por su naturaleza dentro del flujo 
de trabajo multimedia (Gestión, Guion, Gráficos, Audio, Video, Software 
y Producción).

- /01_Gestion_y_Planificacion: Contiene la documentación organizativa 
  y de administración (cronograma, contactos, presupuestos y feedback).
- /02_Guiones_y_Documentos: Concentra el desarrollo literario y técnico 
  del proyecto.
- /03_Recursos_Graficos: Organiza el material visual plano, dividido 
  en subcarpetas para separar la identidad de marca (Branding) de las 
  fotografías de rodaje (Fotografía).
- /04_Audio: Diseñado para almacenar pistas de audio master y bandas 
  sonoras.
- /05_Video_y_Animacion: Aloja las piezas audiovisuales finales e 
  iteraciones de animación listas para postproducción.
- /06_Software_y_Licencias: Mantendremos aislados los ejecutables de 
  herramientas de edición, sus configuraciones (.ini) y licencias.
- /07_Produccion_y_Cronologias: Reúne la secuencia cronológica de 
  rodaje e hilado de escenas.


2. JUSTIFICACIÓN DE ELIMINACIONES Y REDUNDANCIAS:
----------------------------------------------------------------------
Con el objetivo de optimizar el espacio de almacenamiento y evitar 
confusiones por duplicidad o versiones obsoletas, se eliminaron los 
siguientes archivos:

a) render_escena1_001.tmp
   - Razón: Es un archivo temporal generado automáticamente por software 
     de renderizado. No aporta valor final y ocupa espacio innecesario.

b) video_inicial.mp4 y VIDEO_INTRO_revisado_OK.mp4
   - Razón: Archivos redundantes respecto a 'video_intro_final.mp4'. 
     Se conserva únicamente la versión final confirmada para evitar 
     errores en el armado final.

c) cronologia_de_escena_v1.pdf
   - Razón: Reemplazado por la versión superior 'cronologia_deescenav2.0.pdf' 
     (normalizada como 'cronologia_escenas_v2.pdf').

d) logocliente.psd
   - Razón: Obsoleto ante la presencia de la versión revisada 'logo cliente finalv2.psd'.


3. NOMENCLATURA Y CAMBIOS DE NOMBRE APLICADOS:
----------------------------------------------------------------------
Se estandarizó la nomenclatura utilizando minúsculas y guiones bajos (_) 
para garantizar compatibilidad multiplataforma en entornos de sistemas:

- 'guionepisodio1_borrador.docx' -> 'guion_episodio_01_v1.docx'
- 'logocliente finalv2.psd' -> 'logo_cliente_v2.psd'
- 'foto_set_produccion.jpg' -> 'fotografia_set_produccion.jpg'
- 'audio_musica_fondo.wav' -> 'musica_fondo_principal.wav'
- 'version_animacion_v1.gif' -> 'animacion_escena_v1.gif'
- 'cronologia_deescenav2.0.pdf' -> 'cronologia_escenas_v2.pdf'
- 'lista_contactos.txt' -> 'contactos_proyecto.txt'
- 'cronograma_proyecto_creativo.xlsx' -> 'cronograma_proyecto.xlsx'


4. CARPETAS Y RECURSOS ADICIONALES CREADOS:
----------------------------------------------------------------------
- Se crearon las subcarpetas /03.1_Branding y /03.2_Fotografia dentro 
  de /03_Recursos_Graficos para diferenciar recursos vectoriales/editables 
  de marca frente a registros fotográficos del set.
======================================================================