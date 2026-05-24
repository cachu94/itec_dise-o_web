Reto 3 | Maquetar la Home de un producto digital

Trabajo Integrador: HTML Semántico, CSS Variables y Flexbox

🧭 Introducción:

Un cliente nos solicita que creemos el sitio web para su nuevo producto digital. Ya

contamos con un diseño base (Layout), pero ahora debemos profesionalizar el código

asegurando que sea escalable, ordenado y moderno.

🧰 Instrucciones Iniciales:

El objetivo es maquetar la página de inicio (Index) basándote en las imágenes de

referencia.

●  Requisito Principal: Todo el diseño debe ser construido utilizando Flexbox.

●  Mantenibilidad: El uso de variables es obligatorio para evitar repetir códigos de

color.

💡 Consejos:

●  En el siguiente link encontrarás los materiales que necesitas para resolver éste reto:

●  🔗 IMÁGENES PARA RETOS

●  En la tarea de Classroom dejo adjuntos 2 links para ampliar conocimientos acerca

de la manipulación de imágenes que te serán de utilidad.

🛠 Requisitos Técnicos Obligatorios

Para que el proyecto sea aprobado, deberá cumplir con los siguientes puntos técnicos:

1.  Variables CSS (:root): Deberás deﬁnir al menos 4 variables al inicio de tu CSS:

○  --color-primario

○  --color-secundario

○  --color-fondo

○  --fuente-principal

○  --otras

2.  Google Fonts: Importar al menos una fuente desde Google Fonts (ej: Montserrat,

Roboto, Open Sans) y aplicarla a través de la variable --fuente-principal.

3.  HTML Semántico: No uses <div> para todo. Estructura tu HTML con:

○  <header> para la navegación.

○  <main> para el contenido central.

○  <section> para separar las áreas de productos/servicios.

○  <footer> para el pie de página.

4.  Box Model: El diseño debe tener un uso prolijo de padding (aire interno) y gap

(espacio entre elementos en Flexbox).

🪜 Desarrollo del Proyecto

El sitio que quiere el cliente debe quedar de la siguiente manera:

Paso 1: Estructura y Navegación (Header)

Crea una barra de navegación que use justify-content: space-between;. El logo debe

quedar a la izquierda y los links a la derecha.

Paso 2: Sección de Beneﬁcios (Cards)

En esta sección verás tres tarjetas de productos o servicios.

●  Utiliza ﬂex-wrap: wrap; para que, si achicamos la pantalla, las tarjetas bajen solas.

●  Aplica un border-radius y un padding interno a cada tarjeta.

Paso 3: Sección Menciones (Imagen y Texto)

Esta sección suele ser la más compleja.

📂 Estructura de Archivos

Para trabajar como un profesional, tu carpeta de proyecto debe verse así:

●

index.html

●  /css

○  estilos.css

●  /img (Imágenes descargadas del link de Classroom)

📈 Checklist de Evaluación

Antes de entregar, asegurate de marcar con una "X" si cumpliste con lo siguiente:

Criterio

Descripción

Cumplido

Variables

¿Usé :root para colores y fuentes?

[   ]

Flexbox

¿Evité el uso de ﬂoats y usé display: ﬂex?

[   ]

Fuentes

¿La fuente se carga desde Google Fonts?

[   ]

Semántica

¿Usé etiquetas header, main, section y footer?

[   ]

Box Model

¿Los elementos tienen respiro (padding) y

[   ]

separación (gap)?

Responsividad

¿Usé ﬂex-wrap para que el contenido no se

[   ]

desborde?

💡 Consejo Pro: Si una imagen se ve muy grande, recordá usar la propiedad max-width:

100%; en CSS para que se adapte al contenedor padre que creaste con Flexbox.

🏆 Manos a la obra! Al ﬁnalizar este reto, tendrás tu primera maquetación profesional

completa.

