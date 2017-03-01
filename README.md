# Ejercicio 5.7.6 - Mejora el juego con canvas.
## Enunciado
Partiendo del juego sencillo anterior, realiza las siguientes modicaciones:
- Impide que la princesa se situe entre los árboles.
- Impide que el héroe salga del recinto arbolado.
- Añade piedras, que el héroe ha de sortear para llegar a la princesa.
- Ten en cuenta que no puede haber una piedra suficientemente cerca de la posición de la princesa, ni en la posición inicial del príncipe.
- Añade monstruos que si tocan al héroe, lo matan
- Añade lógica para que cada 10 princesas cogidas, se "pase" al siguiente nivel (con más piedras y/o monstruos más veloces).

### 5.7.5. Un sencillo juego con canvas
> Estudia con detenimiento el juego sencillo realizado con canvas y javascript _simple_canvas_game_ que puedes encontrar en GitHub (repositorio X-Nav-5.7.6-JuegoCanvas).

> Pon especial atención en las siguientes cuestiones:
  - Cómo se cargan las imágenes.
  - Cómo se modelan los elementos (los objetos del juego).
  - Cómo se utilizan las pulsaciones de teclas para cambiar el estado.
  - Cómo es el loop principal del juego.

## Resultado
[http://acamara7es.github.io/X-Nav-5.7.6-JuegoCanvas/index.html](http://acamara7es.github.io/X-Nav-5.7.6-JuegoCanvas/index.html)

## Comentarios y mejoras
En lugar de cada 10 niveles, hay cambios más a menudo en el juego:
- Aparece una nueva piedra cada 3 niveles.
- Aparece un nuevo monstruo cada 6 niveles.
- Cuando aparece una piedra nueva, los monstruos que haya incrementan su velocidad un 30% (no afecta a futuros monstruos).
