# product-landing

# Retos adicionales implementados
Durante el desarrollo de este proyecto enfrenté varios desafíos técnicos que me ayudaron a fortalecer mis habilidades y a comprender mejor el proceso de construcción y despliegue de una página web.

Uno de los principales retos fue el conflicto entre los estilos definidos en mi archivo styles.css y los estilos que intentaba aplicar mediante Tailwind CSS. Al principio, los márgenes (margin) y rellenos (padding) que agregaba con Tailwind no surtían efecto. Esto se debía a que las reglas de normalización que había incluido en mi archivo CSS tenían mayor prioridad y estaban sobrescribiendo los estilos de Tailwind. Para solucionarlo, fue necesario revisar el orden de los archivos y ajustar las reglas de normalización para que no interfirieran con el framework.

Otro desafío surgió durante la fase de pruebas. En un momento, los cambios de estilo que realizaba no se reflejaban en el navegador, a pesar de que revisaba el código y no encontraba errores en la sintaxis. Después de investigar, descubrí que el problema se debía a que el Live Server estaba mostrando una versión en caché de la página. La solución fue reiniciar el servidor para que cargara la versión actualizada del sitio, lo que me permitió continuar con el desarrollo sin inconvenientes.

Por último, tuve dificultades al intentar subir el proyecto a GitHub. Al hacer push, me encontré con conflictos porque el repositorio remoto ya contenía archivos previos (por ejemplo, un README generado al crear el repositorio en GitHub). Esto impedía que pudiera subir mis archivos locales directamente. Para resolverlo, tuve que realizar un git pull --rebase para integrar los cambios remotos con los míos, resolver los conflictos y finalmente subir el proyecto correctamente al repositorio.



# Decisiones técnicas clave.
Durante el desarrollo del proyecto tomé varias decisiones técnicas con el objetivo de mejorar la estructura, el rendimiento y la experiencia del usuario.

Uso de HTML5 semántico:
Elegí emplear etiquetas semánticas como header, nav, main, section y footer para lograr un código más legible y accesible. Esto facilita que los lectores de pantalla y los motores de búsqueda comprendan mejor la estructura de la página.

Aplicación de Tailwind CSS:
Opté por utilizar Tailwind CSS para el diseño visual del sitio. Esto me permitió acelerar el proceso de maquetado y lograr una interfaz consistente gracias a sus clases utilitarias. Tailwind se usó principalmente en la landing page y en el apartado de testimonios, combinándose con Flexbox y Grid para organizar los elementos.

Uso de Flexbox y Grid:
Para la distribución de los elementos en la interfaz, utilicé Flexbox en los componentes más sencillos como el header, botones y secciones de textos, y CSS Grid en áreas donde la disposición requería mayor control, como la galería de productos y el bloque de testimonios.

Gestión de versiones con Git:
Decidí trabajar con ramas para organizar mejor el desarrollo. Por ejemplo, creé una rama específica para la integración de Tailwind CSS y otra para funcionalidades adicionales. Estas ramas fueron fusionadas en main mediante Pull Requests, asegurando un flujo de trabajo ordenado y controlado.

Accesibilidad:
Me aseguré de incluir atributos alt en todas las imágenes y consideré el contraste de colores y tamaños de fuente para que el contenido fuera legible y accesible para todos los usuarios.

Validación crítica del uso de IA:
Para optimizar el tiempo y evitar errores de sintaxis, empleé herramientas de inteligencia artificial como apoyo en la generación de fragmentos de código y ejemplos de maquetación. Sin embargo, revisé y adapté cada sugerencia para asegurarme de que cumpliera con los estándares del proyecto.



# Enlace al sitio.
https://laurasalas-dev.github.io/product-landing-page/
