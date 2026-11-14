# YABC - Yet Another Battle City

## Descripción Breve
Este proyecto consiste en el desarrollo de una versión propia del clásico videojuego **Battle City**, implementado en Java.
El objetivo es recrear la jugabilidad original incorporando la lógica de tanques, enemigos, obstáculos y power-ups, aplicando los conceptos de programación orientada a objetos y estructuras de datos.

---

## Instrucciones de ejecución
**Requisitos:**
Tener JDK versión 17 instalado. Maven instalado (de ser posible actualizado a las últimas versiones) y en el path del sistema.

**Pasos:**

Clonar el repositorio con `git clone https://github.com/MartinAlonso333/Yet-Another-Battle-City.git` y entrar a la carpeta `Yet-Another-Battle-City` con el comando `cd`.

Opción 1) En la terminal, en la raíz del proyecto, ejecutar `mvn clean compile`, luego `mvn exec:java -Dexec.mainClass="org.JuegoApp"`. Luego de esto se debería mostrar la ventana del juego.

Opción 2) Desde el IDE IntelliJ, asegurarse en `File -> Project Structure` que el SDK esté en la versión `ms-17`. Ir a la ventana de Maven a la derecha, entrar a la carpeta `juego-javafx/Plugins/clean/` y ejecutar `clean:clean`, luego en `juego-javafx/Plugins/compiler/` ejecutar `compiler:compile`, y por último entrar a `juego-javafx/Plugins/javafx` y ejecutar `javafx:run`. Luego de esto se debería mostrar la ventana del juego.

## Instrucciones de juego (comandos)

Controles (movimiento + DISPARO):

- Jugador 1: W-A-S-D + ESPACIO
- Jugador 2: flechas del teclado + ENTER
