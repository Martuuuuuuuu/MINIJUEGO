# Piedra, Papel o Tijera con Persistencia de Datos

**Actividad 7 - Laboratorio de Programación**

**Institución:** E.E.S.T. N.º 1 "Eduardo Ader" - Vicente López  
**Curso:** 5.º año, 3.º - Grupos A-B  
**Ciclo lectivo:** 2026  
**Docente:** Mansilla Muñoz York Elías

## Integrantes

- Martina Araujo
- Thiago Goya
- Sofia Salaberry

## Descripción

Este proyecto corresponde a la Actividad 7 de Laboratorio de Programación. Consiste en desarrollar un juego de **Piedra, Papel o Tijera** en C++, donde el jugador se enfrenta contra la computadora y cada partida queda registrada en un archivo de texto.

## Funcionalidades

1. **Juego contra la computadora.** El jugador selecciona Piedra, Papel o Tijera y se genera una elección para la computadora.

2. **Registro de partidas.** Cada partida se almacena utilizando un `struct` con los datos del jugador, las elecciones realizadas y el resultado.

3. **Persistencia de datos.** Las partidas se guardan en `historial_partidas.txt` mediante `ofstream` e `ios::app`, permitiendo conservar el historial aunque se cierre el programa.

4. **Consulta del historial.** Se utiliza `ifstream` para leer y mostrar las partidas guardadas en el archivo.

## Estructura del repositorio

- `src/`: contiene el código fuente y el archivo de historial.
- `docs/`: contiene la documentación de la actividad.
- `docs/manuales/`: contiene los manuales del programador y del usuario.
- `capturas/`: contiene las evidencias de ejecución.
- `.gitignore`: establece los archivos y carpetas que Git debe ignorar.
- `LICENSE`: contiene la licencia del proyecto.
- `README.md`: presenta y describe el proyecto.

**Laboratorio de Programación - E.E.S.T. N.º 1 "Eduardo Ader"**