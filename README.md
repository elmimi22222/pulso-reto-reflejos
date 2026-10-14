# Pulso — Reto de reflejos y clics

Un contador de clics y juego de reflejos responsive, hecho con HTML, CSS y JavaScript. Haz clic sobre el punto luminoso tantas veces como puedas antes de que acabe el tiempo. No necesita instalar nada: abre `index.html` en tu navegador y juega.

Elige una partida de **5 segundos, 15 segundos, 30 segundos o 1 minuto**. Puedes detener la partida en cualquier momento para ver tus resultados, o cambiar la duración durante una partida para reiniciarla inmediatamente con el nuevo tiempo. Al terminar, aparece un resumen a pantalla completa con tus puntos, el tiempo medio de reacción, precisión y récord personal. Los clics en el fondo del área de juego cuentan como intentos fallidos para calcular la precisión. Los récords se guardan por duración en el navegador del jugador. El objetivo tiene un área táctil amplia y no se agranda al pasar el cursor.

## Publicarlo en GitHub Pages

1. Crea un repositorio en GitHub y sube estos archivos.
2. En GitHub, abre **Settings → Pages**.
3. En **Build and deployment → Source**, selecciona **GitHub Actions**.
4. Al subir cambios a la rama `main`, el flujo de trabajo publicará el sitio automáticamente. La primera vez también puedes iniciarlo desde **Actions → Deploy to GitHub Pages → Run workflow**.
5. Cuando termine, GitHub mostrará la dirección del sitio en **Settings → Pages**.

El récord se guarda localmente en el navegador de cada jugador.
