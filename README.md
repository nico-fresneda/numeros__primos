🔢 Verificador de Números Primos (Matrix Theme)

Una aplicación web interactiva de un solo archivo que permite verificar rápidamente si un número entero es primo o compuesto. Todo esto presentado bajo una inmersiva estética de "lluvia digital" inspirada en la película Matrix.

✨ Características

Estética Hacker: Interfaz oscura, tipografía de terminal antigua y un fondo animado creado con <canvas> que simula una lluvia de código binario (0 y 1).

Algoritmo Optimizado: Utiliza el método matemático de 6k ± 1 para comprobar la primalidad de los números de forma extremadamente rápida y eficiente, descartando múltiplos innecesarios desde el inicio.

Feedback Educativo: Si el número ingresado resulta no ser primo, la aplicación no solo te lo dice, sino que te explica el porqué mostrando su primer divisor (ej. "Es divisible por 2 (2 × 5 = 10)").

Diseño Responsivo: La interfaz de usuario se adapta perfectamente a pantallas de computadoras de escritorio, tablets y teléfonos móviles.

Validaciones Robustas: Manejo de errores visual integrado para prevenir entradas vacías, números decimales o números que por convención matemática no aplican (menores o iguales a 1).

🚀 Tecnologías Utilizadas

HTML5: Estructura semántica de la aplicación y elemento interactivo <canvas>.

Tailwind CSS: Framework de utilidades (cargado vía CDN) para el diseño, alineación, sombreados neón y efectos de desenfoque (backdrop-blur).

JavaScript (Vanilla): Motor de la aplicación. Maneja el algoritmo matemático, la manipulación del DOM (UI) y el bucle de animación para la lluvia digital del fondo.

Google Fonts: Uso de la fuente Share Tech Mono para darle el aspecto de consola de comandos.

💻 Cómo ejecutar el proyecto

La mayor ventaja de esta herramienta es su portabilidad; al estar contenida completamente en un solo archivo, no requiere instalación de dependencias (como Node.js) ni configuraciones de servidor:

Guarda el código fuente en un archivo llamado index.html.

Haz doble clic sobre el archivo para abrirlo directamente en cualquier navegador web moderno (Google Chrome, Firefox, Safari, Edge, etc.).

Escribe un número en el campo de texto y presiona la tecla Enter (o el botón "Verificar Número") para ver el resultado.

👨‍💻 Créditos

Elaborado por Nicolás Fresneda con asistencia de inteligencia artificial.
