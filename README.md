# GDDJam
# Tabla de contenidos

1. Inicio
    1. Nombre del Juego
2. Resumen del Juego
    1. Concepto del juego
    2. Descripción
    3. Género
    4. Plataforma
    5. Motor Gráfico
3. Gameplay y mecánicas
    1. Gameplay
        1. Sistema de progresión
        2. Dificultad del juego
    2. Mecánicas
        1. Movimiento
        2. Camara
        3. Jugabilidad
    3. Apartado gráfico
4. Historia
5. Niveles(Ideas de desarrollo)


# Inicio
## Nombre del juego
One Touch Parry

# Resumen
## Concepto
Juego 2D Top Down, el jugador tendrá que sobrevivir para conseguir la máxima puntuación.

## Descripcion
El juego consistirá en que el jugador no debe ser tocado,si lo tocan,se reinicia la partida. El jugador tendrá que aguantar bloqueando ataques.

## Género
Survival?

## Plataforma
PC

## Motor gráfico
Unity

# Gameplay
## Sistema de progresion
El juego constará de niveles por los que avanzar,obviamente cada uno más dificil. Si el personaje muere,empieza desde el inicio del todo.
Para completar cada nivel,se tendrá que eliminar un número determinado de enemigos.

## Dificultad del juego 
La establecida por el creador

# Mecánicas
## Movimiento
1. WASD para mover
2. Clic izquierdo para Bloquear / Botón de espacio

## Cámara
Top Down

## Jugabilidad
El jugador tendrá que estar atento en todo momento de los enemigos. Como guía,cuando los enemigos estén apunto de atacar,se le avisará a partir de colores, y este podrá repeler los ataques. 
En cuanto se repele el ataque,el enemigo empujado y derrotado.
El botón de bloqueo solo se podrá usar en el momento del aviso.

### Comportamiento del enemigo
El enemigo tendrá tres fases:
1. Persecución al jugador: Aquí el enemigo irá a por el jugador(Moviéndose a la posición de este), cuando se acerque lo suficiente,procederá a la siguiente fase.
Si el juego llega a tener obstaculos,será necesario el uso de la herramienta Nav Mesh de Unity.
3. Movimiento de ataque: En el momento en el que el enemigo haga este movimiento,se señalará al jugador con los colores y podrá hacer el bloqueo.
4. Ataque del enemigo: Ataca al jugador y este es derrotado.


# Apartado gráfico
Será sencillo,lo importante serán jugar con las luces para mostrar el momento de hacer los bloqueos y para los diseños de nivel.
Si hay tiempo, sistema de particulas a la hora de destruír los enemigos o el jugador.

# Historia
Eres el rey del Parry.
Gastaste todos tus puntos de habilidad en hacer parrys.
Hay un solo pero...Las demás estadísticas están al minimo,puedes morir con el mínimo toque.

# Nivel
Los niveles cambiarán de tonalidad de color para el fondo para señalar el cambio de nivel
Si hay tiempo habría generación aleatoria de obstaculos, si no, será un nivel sin ellos.
