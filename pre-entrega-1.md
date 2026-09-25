## Preentrega: Repositorio Base y Documentación Profesional

Esta preentrega es el primer hito fundamental de tu camino como desarrollador/a profesional. Hasta ahora, has trabajado en tu propia computadora, pero el desarrollo de software moderno ocurre en la nube y de forma colaborativa.
En esta etapa, transformarás tu carpeta de trabajo local en un repositorio profesional. Esto significa que no solo guardarás archivos, sino que definirás qué debe ser rastreado, qué debe ignorarse por seguridad o eficiencia, y cómo otros (o tú mismo en el futuro) entenderán de qué trata tu proyecto a través de una documentación clara.
Al finalizar, tendrás el "esqueleto" de tu proyecto sincronizado en GitHub, listo para recibir nuevas funcionalidades y permitir la colaboración en los siguientes módulos.
¿Qué retomo?
Al ser esta la primera preentrega del programa, no retomamos piezas técnicas de entregas anteriores. Sin embargo, para completarla con éxito, utilizaremos los conocimientos y configuraciones que has construido durante este módulo:
Tu identidad Git: Tu nombre y correo configurados globalmente.
Tu repositorio local: La carpeta inicializada con git init.
Tus primeros commits: El historial básico que has generado mientras practicabas el ciclo de vida (staging y commit).
Tu cuenta de GitHub: El espacio remoto donde publicarás tu trabajo.
¿Qué construyo?
En esta unidad, consolidarás la estructura base de tu proyecto. El foco no es el código de programación todavía, sino la infraestructura de gestión. Deberás entregar un repositorio que contenga:
Inicialización Profesional: Un historial de commits limpio que muestre la evolución inicial.
Filtro de Archivos (.gitignore): Una configuración que asegure que no subiremos "basura" (archivos temporales del sistema, carpetas de dependencias pesadas o archivos de configuración del editor).
Documentación (README.md): Una presentación profesional escrita en Markdown que explique el propósito del proyecto.
Vinculación Remota: El enlace funcional entre tu computadora y GitHub mediante el remoto origin.
Importante
No es necesario tener código complejo. Un script simple o incluso solo los archivos de configuración y documentación son suficientes, siempre que la estructura de Git sea correcta.
Criterios de aceptación
Para que esta preentrega sea considerada aprobada, debe cumplir con los siguientes puntos:
Existencia de .gitignore: Debe estar en la raíz y excluir al menos 2 patrones comunes (ej: .DS_Store, node_modules/, .env, o archivos temporales de tu editor).
README.md estructurado: Debe contener al menos un título (H1), una descripción breve, una lista de tecnologías y una sección de "Cómo empezar".
Historial de Commits: Al menos 3 commits con mensajes descriptivos (evita mensajes como "cambios", "fix" o "test").
Sincronización: El repositorio debe estar visible en GitHub y reflejar exactamente el estado de tu rama principal local.
Limpieza: No deben existir archivos que el .gitignore debería haber evitado en el repositorio remoto.
Pasos sugeridos
Revisión Local: Ejecuta git status para asegurarte de que no tienes cambios pendientes sin confirmar.
Configura el Ignorado: Crea o edita tu archivo .gitignore. Asegúrate de añadir archivos que tu sistema operativo crea automáticamente.
Redacta tu README: Usa la sintaxis Markdown que aprendimos. Incluye un título claro y explica para qué sirve tu proyecto.
Haz el Commit Final: Agrega estos archivos al staging area y crea un commit con un mensaje como docs: agregar README y configuracion inicial de gitignore.
Crea el Repo en GitHub: Ve a GitHub, crea un repositorio nuevo (vacío, sin inicializar README allí) y copia la URL.
Vincula y Sube: Usa git remote add origin [URL] y luego git push -u origin main (o master).
Errores comunes a evitar
Subir archivos que deberían ignorarse: Si haces un commit de un archivo y luego lo agregas al .gitignore, Git lo seguirá rastreando. Debes borrarlo del índice con git rm --cached antes de que el ignorado surta efecto.
Mensajes de commit genéricos: "Update" no dice nada. Usa "feat: agregar estructura inicial" o "docs: mejorar instrucciones en README".
¿Cómo se integra al Proyecto Final?
Esta preentrega es la piedra angular. El Proyecto Final del programa será un repositorio colaborativo completo. Lo que entregas hoy es el "Contenedor" donde vivirá todo ese código.
Sin el .gitignore de hoy, tu proyecto final pesaría demasiado y sería inseguro.
Sin el README.md, nadie sabría cómo ejecutar tu entrega final.
Sin la vinculación a GitHub, no podrías realizar el despliegue que haremos en el Módulo 3.
¿Qué queda pendiente para próximas preentregas?
Esta entrega es estática y lineal. En las siguientes etapas añadiremos complejidad:
Módulo 2: Aprenderás a crear ramas (branches) para no trabajar siempre sobre la principal y a integrar cambios mediante Pull Requests.
Módulo 3: Resolverás conflictos de código con otros compañeros y realizarás la limpieza final del historial para que tu portfolio luzca impecable.
Tip
Piensa en el README como tu carta de presentación. Un reclutador verá primero ese archivo antes que tu código. ¡Haz que destaque!
Entregable
Instrucciones para la Preentrega 1: Configuración Profesional del Repositorio
El objetivo de esta práctica es transformar tu espacio de trabajo local en un repositorio de GitHub profesional y bien documentado. Sigue estos pasos detallados:
1. Preparación del Repositorio Local
Si aún no lo has hecho, inicializa Git en tu carpeta de proyecto con git init.
Asegúrate de tener configurado tu nombre y correo globalmente (git config --global user.name "Tu Nombre").
2. Configuración del Archivo de Ignorado
Crea un archivo llamado .gitignore en la raíz.
Incluye al menos dos patrones de archivos que no deben subirse (ejemplo: .DS_Store si usas Mac, node_modules/ si trabajas con Node, o extensiones de archivos temporales de tu editor como .swp o .log).
3. Documentación del Proyecto
Crea un archivo README.md utilizando sintaxis Markdown.
Debe incluir: Un título principal (#), una descripción del propósito del proyecto, una lista de tecnologías utilizadas y una sección breve de "Instalación" o "Cómo empezar".
4. Ciclo de Vida y Commits
Realiza al menos 3 commits significativos. Por ejemplo:
feat: inicializar estructura de carpetas
docs: agregar README detallado
config: configurar .gitignore para archivos del sistema
5. Sincronización con GitHub
Crea un nuevo repositorio en tu cuenta de GitHub (mantenlo público).
Vincula tu repositorio local con el remoto usando git remote add origin <URL-DE-TU-REPO>.
Sube tus cambios a la rama principal con git push -u origin main.
Nota importante: Verifica en la web de GitHub que no se hayan subido archivos accidentales que deberían estar en el .gitignore.
Qué tenés que entregar: Repositorio público en GitHub que contenga el historial de commits, el archivo .gitignore configurado y el README.md profesional.