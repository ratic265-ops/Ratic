RATIC WAR — SERVIDOR MULTIJUGADOR INICIAL

Incluye servidor Node.js + Socket.IO y el juego 3D modificado para mostrar a otros jugadores conectados.

PRUEBA EN PC:
1. Instala Node.js 20 o superior.
2. Abre una terminal dentro de esta carpeta.
3. Ejecuta: npm install
4. Ejecuta: npm start
5. Abre http://localhost:3000

PRUEBA EN VARIOS CELULARES CON LA MISMA WI-FI:
1. Ejecuta el servidor en una computadora.
2. Averigua la IP local de esa computadora.
3. En los celulares abre http://IP-DE-LA-COMPUTADORA:3000.

PUBLICAR EN INTERNET:
Despliega esta carpeta en un hosting compatible con Node.js, por ejemplo Render.
Build command: npm install
Start command: npm start
Después abre la URL HTTPS que te proporcione el hosting.

IMPORTANTE:
Este paquete es código de servidor listo para desplegar, no un servidor ya publicado en internet. No puedo crear una cuenta de hosting ni dejarlo alojado desde aquí. El multijugador inicial sincroniza posiciones y orientación; aún no sincroniza daño, disparos, puntuación, cuentas, matchmaking ni anti-trampas. El juego carga Three.js desde CDN y necesita internet.
