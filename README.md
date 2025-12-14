🎮 4 en Raya - Juego en Consola Python
📋 Descripción
Juego clásico "4 en Raya" implementado en Python para consola. Dos jugadores compiten para alinear 4 fichas consecutivas horizontal, vertical o diagonalmente en un tablero 8x8.

🚀 Características Principales
✅ Tablero 8x8 con columnas de la A a la H

✅ 12 tipos diferentes de fichas (•, X, @, ☻, ♥, ♦, ♠, ○, ♂, ♀, ♪, ☼)

✅ Sistema de puntuación con 50 puntos iniciales

✅ Detector de empates y límite de columnas

✅ Easter egg secreto (ficha especial)

✅ Registro de puntajes en archivo "Puntaje"

🎯 Instalación y Ejecución
Requisitos
Python 3.6 o superior

Terminal/consola que soporte caracteres especiales

Ejecución
bash
# Clonar repositorio
git clone https://github.com/KevinAlajarin/4-En-Raya.git

# Navegar al directorio
cd 4-en-raya

# Ejecutar juego
python cuatro_en_raya.py
🕹️ Cómo Jugar
Flujo del Juego
Inicio: El juego muestra las reglas opcionales

Selección de nombres: Cada jugador ingresa su nombre

Elección de ficha: 12 opciones disponibles (no se pueden repetir)

Turnos alternados: Jugador 1 y Jugador 2 por turnos

Movimientos: Ingresar letra de columna (A-H)

Victoria: Conectar 4 fichas en línea

Puntuación final: Se calculan los puntos

Sistema de Puntos
Puntos iniciales: 50

Pérdida por turno: -1 punto por turno jugado

Victoria: +15 puntos

Derrota: -15 puntos

Empate: Solo se resta por turnos jugados

Comandos Especiales

# Easter egg (selección de ficha)        
Ingrese "creador" para desbloquear ficha secreta: ¢       

📁 Estructura del Código
```text
Funciones Principales
crearmatriz()          # Crea tablero 8x8
interfazdejuego()      # Muestra reglas e interfaz
eleccion()             # Selección de fichas
imprimirmatriz()       # Muestra tablero actual
llenarmatriz()         # Coloca fichas en tablero
checker()              # Verifica condiciones de victoria
puntajes()             # Calcula sistema de puntos
empatar()              # Detecta empates
Variables Clave
python
matrizvacia    # Tablero de juego
dic            # Mapeo columnas A-H → índices 0-7
f1, f2         # Fichas de jugadores
jugadas_filas  # Control de columnas llenas
turnos1, turnos2 # Contador de turnos
```
