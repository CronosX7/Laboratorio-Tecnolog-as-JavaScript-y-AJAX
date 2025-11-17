Laboratorio de JavaScript y AJAX – Práctica Web

Este proyecto es una página web desarrollada con HTML, CSS interno y JavaScript, diseñada como un laboratorio de ejercicios prácticos.
Incluye actividades básicas de JavaScript y una demostración funcional del uso de AJAX mediante XMLHttpRequest.

Todo el contenido del sitio se encuentra en un solo archivo HTML.

📌 Contenido del Proyecto

La página está dividida en dos grandes secciones:

📝 1. Ejercicios en JavaScript

Incluye cuatro ejercicios interactivos:

1. Detector de Palíndromos

Permite ingresar una palabra o frase para verificar si es un palíndromo.
El script:

Elimina espacios, tildes y caracteres especiales.

Compara la cadena original con su versión invertida.

2. Comparar Dos Números

El usuario ingresa dos números y el sistema determina cuál es mayor o si son iguales.
Incluye validación de entrada.

3. Mostrar Vocales de una Frase

Identifica qué vocales aparecen en una frase, sin importar mayúsculas o tildes.

4. Contar Vocales en una Frase

Cuenta cuántas veces aparece cada vocal (a, e, i, o, u).
Muestra el total y el detalle individual.

🌐 2. Ejercicio Práctico con AJAX

Incluye una demostración del ciclo completo de una petición AJAX usando XMLHttpRequest.

El usuario puede:

Ingresar una URL.

Consultar su contenido mediante petición GET.

Observar:

Estado de la petición (readyState)

Código de estado HTTP

Cabeceras de respuesta

Contenido retornado

La página muestra visualmente las transiciones entre estados:

No iniciada

Cargando

Procesando

Completada

Error

🎨 Estilos (CSS interno)

El archivo incluye estilos embebidos con:

Fondo gris en degradado

Encabezados en color negro

Botones en tonos gris metálico

Tarjetas y bloques blancos con sombra

Diseño responsive para móviles

Indicadores visuales de estado AJAX

Cuadros de resultados con colores diferenciados (éxito/error)

📁 Estructura del Proyecto

Todo el contenido se encuentra en un único archivo:

index.html


No existen archivos CSS ni JS externos.
El <style> y el <script> están incluidos dentro del HTML.

⚙️ Tecnologías Utilizadas

HTML5

CSS3 (interno)

JavaScript puro

AJAX con XMLHttpRequest

▶️ Cómo Ejecutarlo

Abre la carpeta del proyecto en VS Code.

Asegúrate de que el archivo index.html esté ubicado en la raíz.

(Opcional) Usa la extensión Live Server.

Haz clic derecho en el archivo → Open with Live Server.

La página cargará completamente en el navegador sin configuraciones adicionales.

🎯 Objetivo del Proyecto

Este laboratorio está orientado a reforzar:

Manipulación del DOM

Validaciones básicas

Manejo de cadenas

Lógica en JavaScript

Operaciones con XMLHttpRequest

Visualización del ciclo de vida de una petición AJAX

Estructuración de una página con HTML, CSS y JS combinados

✏️ Autor

Proyecto desarrollado por Juan David como práctica de programación web.
