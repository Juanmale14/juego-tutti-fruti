📝 Tutti Frutti Pro 2026

Tutti Frutti Pro es una aplicación web moderna, colorida y funcional para jugar al clásico juego de palabras (también conocido como ¡Basta!, Stop o Ensalada de Frutas). Diseñada especialmente para ser utilizada en entornos educativos o reuniones familiares.

Desarrollado para el proyecto: El loco de la mochila.

🚀 Características Principales

Dualidad de Modo: Juega directamente en la aplicación (Modo App) o utilízala como soporte visual para jugar con papel y boli (Modo Papel).

Niveles de Dificultad:

🟢 Fácil: 5 categorías básicas para partidas rápidas.

🔴 Difícil: 10 categorías desafiantes para expertos.

Tablas Visuales: Tablas con colores vibrantes y diferenciados por columnas para una visibilidad perfecta en pizarras digitales o móviles.

Sistema de Validación: Incluye una tabla de ejemplos sugeridos según la letra de la ronda para facilitar la corrección.

Marcador Inteligente: Los jugadores se ordenan automáticamente de mayor a menor puntuación.

Diseño Adaptativo (Responsive): Totalmente funcional en tablets, móviles y ordenadores.

🛠️ Tecnologías Utilizadas

HTML5 (Estructura semántica)

CSS3 (Variables CSS, Flexbox, Grid y Animaciones)

JavaScript (Vanilla) (Lógica del juego y manipulación del DOM)

📖 Cómo jugar

Registro: Añade los nombres de los participantes.

Configuración: Elige el modo (App/Papel) y la dificultad.

Partida: -   Se genera una letra aleatoria.

Los jugadores deben rellenar las categorías que aparecen en la tabla de colores.

El primero en terminar pulsa el botón ¡BASTA!.

Puntuación:

20 pts: Eres el único que ha escrito en esa categoría.

10 pts: Palabra válida y original.

5 pts: Palabra válida pero repetida por otro jugador.

0 pts: Error o campo vacío.

Final: Consulta la clasificación final para ver quién es el ganador.

🔧 Instalación y Despliegue

Este proyecto no requiere servidores ni instalaciones complejas.

Clona el repositorio:

git clone [https://github.com/tu-usuario/tutti-frutti-pro.git](https://github.com/tu-usuario/tutti-frutti-pro.git)


Abre el archivo tutti_frutti.html en cualquier navegador web moderno.

¡Listo para jugar!

🎨 Personalización de Categorías

Si deseas cambiar las categorías, puedes editar el objeto CATS_DATA en el bloque de <script> dentro del archivo HTML:

const CATS_DATA = {
    easy: ['Nombre', 'Animal', 'Lugar', 'Comida', 'Cosa'],
    hard: [...]
};


📄 Licencia

Este proyecto está bajo la Licencia MIT. Siéntete libre de usarlo, modificarlo y compartirlo.

Creado con ❤️ por El loco de la mochila (2026).
