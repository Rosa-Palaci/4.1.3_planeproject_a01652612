# Tarea de Desarrollo de Juego 2D

## Propósito
El propósito de esta tarea es crear un prototipo 2D de un juego que aplique conceptos básicos de colisiones y triggers en Unity. El juego incluirá mecánicas como la generación de enemigos, movimiento de enemigos, la gestión de la vida del jugador y los enemigos, y la pausa en el disparo de los enemigos cuando reciben un impacto.

## Instrucciones
Para completar esta tarea, sigue las siguientes instrucciones:

1. **Generar un Spawner de Enemigos:**
   - Crea un sistema de generación de enemigos que genere nuevos enemigos cada cierto intervalo de tiempo (n). Puedes ajustar este intervalo según sea necesario.
   - Implementa una lógica que permita destruir a los enemigos en algún punto de su vida. Puedes elegir entre las siguientes opciones o proponer tu solución:
     - Destrucción después de un tiempo específico.
     - Destrucción cuando el enemigo salga de la pantalla.

2. **Movimiento en X de los Enemigos:**
   - Añade movimiento en el eje X a los enemigos para que se desplacen horizontalmente en la pantalla.

3. **Gestión de la Vida:**
   - Agrega un sistema de vida al jugador y a los enemigos. Preferiblemente, ambos deben tener una barra de vida visible en la pantalla.
   - Cuando la vida del jugador llegue a 0, el juego debe finalizar.
   - Cuando la vida de un enemigo llegue a 0, ese enemigo debe ser destruido.

4. **Pausa en el Disparo de los Enemigos:**
   - Implementa una pausa en el modo de disparo de los enemigos cuando reciben un impacto. Esto significa que los enemigos no deben disparar durante un cierto período de tiempo (n) después de ser impactados.


