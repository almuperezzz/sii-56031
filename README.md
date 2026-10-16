# 🎾 Juego del Tenis

👩‍💻 Autora: Almudena Pérez (56031)

📚 Prácticas de Sistemas Informáticos Industriales (ETSIDI-UPM).
Juego de tenis para dos jugadores hecho en C++ con OpenGL y GLUT.

## 🕹️ Controles
- Jugador 1: w (subir) y s (bajar)
- Jugador 2: o (subir) y l (bajar)

## ⚙️ Cómo compilar
Desde la carpeta workspace:
mkdir build, cd build, cmake .. y make

## ▶️ Cómo ejecutar
Primero se abre el logger en una terminal (./logger) y después el juego en otra (./tenis).
⚠️ Si se abre antes el juego se queda esperando a que el logger abra la FIFO.

## ✅ Práctica 1
- Movimiento de las raquetas y de la pelota
- README y .gitignore

## ✅ Práctica 2
- He añadido un programa logger que lee de una FIFO y muestra los puntos por pantalla
- El juego escribe en la FIFO cada vez que un jugador marca un punto
- Cuando un jugador llega a 3 puntos se acaba la partida y el logger se cierra solo 🏆
