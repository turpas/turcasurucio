# Trabajo de Entornos

## Parte 1

- Hago git clone en el trabajo principal y creo una rama para hacer la parte 1, y de ahi me muevo con git checkout
  ![imagen1](../Imagenes/Imagen1.png)
  <br></br>
- Respondemos la primera pregunta como prueba para ver como va todo esto del git y le hacemos un push pero que solo se modifique la rama “Parte1”, y asi se hara con cada pregunta
  ![imagen2](../Imagenes/Imagen2.png)
  ![imagen2.1](../Imagenes/Imagen2.1.png)
  ![imagen2.2](../Imagenes/Imagen2.2.png)
  <br></br>

- Respondemos las preguntas del 2 al 4 y realizamos un commit de todo lo hecho para guardar el proceso
  ![imagen3](../Imagenes/Imagen3.png)
  <br></br>

- Tras responder todas las preguntas hacemos el commit final de la Parte1, y finalizamos con un push
  ![imagen4](../Imagenes/Imagen4.png)
  <br></br>

- Como la parte 1 se ha realizado, hacemos un merge a la rama main
  ![imagen5](../Imagenes/Imagen5.png)
  <br></br>

- Despues hago un commit, y finalizo con un push
  ![imagen6](../Imagenes/Imagen6.png)
  <br></br>

**_Tras finalizar con la Parte1, empiezo la Parte2 creando la rama ‘Parte2’_**
<br></br>

## Parte 2

- Creamos la rama Parte2 para empezar  
  ![imagen7](../Imagenes/Imagen7.png)
  ![imagen7.1](../Imagenes/Imagen7.1.png)
  <br></br>

- Creamos la forma en como estará ordenado la Parte2
  ![imagen8](../Imagenes/Imagen8.png)
  <br></br>

- Los añado para que el repositorio los tenga en seguimiento
  ![imagen9](../Imagenes/Imagen9.png)
  <br></br>

- Resuelvo las preguntas en cada archivo
  ![imagen10](../Imagenes/Imagen10.png)
  <br></br>

- Después realizo un commit donde hago la parte2 y le hago un merge de Parte2 a la rama main y a continuación le hago un push
  ![imagen11](../Imagenes/Imagen11.png)
  ![imagen11.1](../Imagenes/Imagen11.1.png)
  <br></br>

## Parte 3

**_En esta primera versión la parte 3 no existe porque tuvimos el fallo de realizar un merge cada vez que terminabamos una parte en vez de realizarlo al final del todo, esto hizo que nos rompamos la cabeza con tanto archivo entrelazado entre las ramas_**

### Intento de solución de la primera versión

- Hemos decidido solucionarlo manualmente, reiniciando casi todo el trabajo, primero eliminando las ramas _(Esto no estuvo del todo bien porque solo hemos eliminado las ramas del repositorio local, es decir, en el repositorio remoto aún se encontraba el desastre de los merges)_
  ![imagen12](../Imagenes/Imagen12.png)
  ![imagen12.1](../Imagenes/Imagen12.1.png)
  <br></br>

- Gracias a un git clone del último commit, pudimos recuperar una gran parte del proyecto _(El directorio llamado "turca2porsi" es un tipo de backup improvisado cuando nos dimos cuenta del desastre, antes de reinicar el proyecto, hemos guardado todo allí)_
  ![imagen13](../Imagenes/Imagen13.png)
  <br></br>

- Realizo un git add, un git commit y push para empezar un nuevo comienzo
  ![imagen14](../Imagenes/Imagen14.png)
  ![imagen14.1](../Imagenes/Imagen14.1.png)
  <br></br>

- Hacemos lo mismo con la Parte2
  ![imagen15](../Imagenes/Imagen15.png)
  <br></br>

- Tras realizar esto con todas las partes vamos a realizar un merge _(Spoiler, sale mal)_
  ![imagen16](../Imagenes/Imagen16.png)
  <br></br>

**_Hubo otro conflicto por hacer una mala conexión entre el repositorio local y el remoto, esto fue (o eso creemos) por querer reinciar el proyecto sin haber borrado las ramas en el remoto, así que empezamos denuevo desde 0, guardando las respuestas, y tambien borrando las ramas en el remoto con “git push origin --delete (Nombre de la rama)"_**

## Segunda versión

- Ahora con la experiencia adquirida de los fallos anteriores, hacemos esta segunda versión usando el cerebro y con paciencia
  ![imagen17](../Imagenes/Imagen17.png)
  <br></br>

- Con las preguntas guardadas, lo pasamos a la nueva versión, acabamos una parte, hacemos commit y push, así hasta la tercera parte, teniendo todo acabado, recién hacemos un merge de cada parte a la main, donde por fin se realizó el merge con éxito sin entrelazamienton de contenido entre ramas
  ![imagen17.1](../Imagenes/Imagen17.1.png)
  ![imagen17.2](../Imagenes/Imagen17.2.png)
  ![imagen17.3](../Imagenes/Imagen17.3.png)
  ![imagen17.4](../Imagenes/Imagen17.4.png)
  ![imagen17.5](../Imagenes/Imagen17.5.png)
  <br></br>

- Para finalizar nos faltaría añadir una última rama que sería la parte de la documentación del trabajo
  donde traspasaremos todo el proceso del proyecto a Markdown
  ![imagen18](../Imagenes/Imagen18.png)
  ![imagen18.1](../Imagenes/Imagen18.1.png)
  <br></br>

- Hacemos el paso del Word a Markdown en visual studio y guardamos cada captura en la carpeta imagenes
  ![imagen19](../Imagenes/Imagen19.png)
  <br></br>

- Y como último paso, hacemos un git add, después un git commit de este markdown y el directorio de imagenes en la rama "Documentacion", de ahí le hacemos un merge hacia la rama main y un git push -u origin main.
  <br></br>
  <br></br>

**_Este es el final del trabajo gracias por su atención._**

**_Atte: El grupo Turcasurucio_**
<br></br>
