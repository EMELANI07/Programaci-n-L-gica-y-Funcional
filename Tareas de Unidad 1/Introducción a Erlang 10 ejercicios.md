-------------------------------------------------------------------

# Programación Lógica y Funcional · TecNM Tijuana
 
## Tema: Introducción a Erlang (Grupo 4pm)

 Se realizo la actividad de Hola mundo en Erlang, se añadiran

 los procesos realizados desde el Aciinema para mostrar el proceso.

## Datos del estudiante

 Nombre: Estrada Rodriguez Melani

 Número de control: 23211953

 Carrera: Ingeniería en Sistemas Computacionales

 Grupo: SC7C

 Materia: Programación Lógica y Funcional

 Profesor: Rene Solis Reyes

-------------------------------------------------------------------

14. ESTRADA RODRIGUEZ, MELANI

| # | Ejercicio | Enunciado |
|---|---|---|
| 1 | Aritmética en el shell | Calcula `(14 * 7) + 25` y `14 rem 4` usando el shell interactivo `erl`. |
| 2 | Átomos y tuplas | Crea la tupla `{alumno, melani, 14, "4pm"}` y extrae el nombre con pattern matching. |
| 3 | Listas | Define `Materias = ["Erlang", "Prolog", "OCaml", "Haskell", "Clojure"]` y obtén el primer y último elemento con `hd/1` y `lists:last/1` (longitud = 3 + (N rem 4), rotación con inicio N rem 13). |
| 4 | Pattern matching | Dada `Punto = {3, 8}`, escribe una función que extraiga `X` y `Y` y calcule `X*X + Y*Y`. |
| 5 | Función simple | Escribe `duplicar(N) -> N * 2.` y pruébala con `duplicar(14)`. |
| 6 | Recursión — factorial | Implementa `factorial/1` (recursivo) y evalúa `factorial(9)` (5 + (14 rem 5)). |
| 7 | Recursión sobre listas | Implementa `suma_lista/1` que sume los elementos de `[1, 2, 3, 4, 5, 6, 7, 8, 9]` (longitud = 5 + (14 rem 5)). |
| 8 | Expresión `case` | Escribe una función `clasifica(N)` que use `case` para decir si `N` es `positivo`, `negativo` o `cero`; pruébala con `-6` (V = N - 20). |
| 9 | Guards | Escribe `es_par(N)` con guards (`when N rem 2 =:= 0`) y evalúa `es_par(14)`. |
| 10 | Módulo propio | Crea el módulo `estrada.erl` con `-module(estrada).` y `-export([saludo/0]).`, compílalo con `c(estrada).` y ejecuta `estrada:saludo()`. |

Aciinema:
1. Aritmética en el shell

<a href="https://asciinema.org/a/1265584" target="_blank"><img src="https://asciinema.org/a/1265584.svg" /></a>

2. Átomos y tuplas

<a href="https://asciinema.org/a/1265585" target="_blank"><img src="https://asciinema.org/a/1265585.svg" /></a>

3. Listas

<a href="https://asciinema.org/a/1265587" target="_blank"><img src="https://asciinema.org/a/1265587.svg" /></a>

4. Pattern matching

<a href="https://asciinema.org/a/1265588" target="_blank"><img src="https://asciinema.org/a/1265588.svg" /></a>

5. Función simple

<a href="https://asciinema.org/a/1265589" target="_blank"><img src="https://asciinema.org/a/1265589.svg" /></a>

6. Recursión — factorial

<a href="https://asciinema.org/a/1265590" target="_blank"><img src="https://asciinema.org/a/1265590.svg" /></a>

7. Recursión sobre listas

<a href="https://asciinema.org/a/1265591" target="_blank"><img src="https://asciinema.org/a/1265591.svg" /></a>

8. Expresión `case`

<a href="https://asciinema.org/a/1265592" target="_blank"><img src="https://asciinema.org/a/1265592.svg" /></a>

9. Guards

<a href="https://asciinema.org/a/1265593" target="_blank"><img src="https://asciinema.org/a/1265593.svg" /></a>

10. Módulo propio

<a href="https://asciinema.org/a/1265595" target="_blank"><img src="https://asciinema.org/a/1265595.svg" /></a>
