# Ejercicio
1. Hacer un fork del repositorio https://github.com/undefined-academy/semana-1
2. Clonar tu repositorio "forked" en tu carpeta de HOME.
3. Agregar allí un archivo markdown de tu perfil de GitHub, dentro de la carpeta github-profiles y el nombre de archivo debe ser tu usuario de discord incluyendo el tag numérico*.
4. Incluye dentro del archivo un link que nos lleve directamente a tu perfil de GitHub.
5. Haz commit de dicho archivo.
6. Ve al repositorio del paso 1 y crea tu primer Pull Request
7. No dejes la descripción del Pull Request vacia, escribe cómo fue el proceso de resolver este ejercicio, usar Markdown.

* No se puede poner # como nombre de archivo, cambiar por un guión (-).

---

1. Voy a la página https://github.com/undefined-academy/semana-1 y hago click en fork, dejo el nombre del repositorio igual y acepto.
2. Para clonar:
   1. En **mi** repositorio,  busco la opción *Code* y copio la dirección.
   2. Escribo el siguiente comando en la terminal ```git clone https://github.com/marcospenalosa/semana-1.git```
3. En la terminal entro en la carpeta del repositorio
   1. ```Cd github-profiles```
   2. ```touch murquis-5340.md```
4. Escribo en la terminal ```code``` (abro el VS y modifico el archivo)
5. ```git commit -m "Add profile murquis-5340"```
   1. ```git remote``` (para saber en que rama de **MI** repositorio estoy)
   2. ```git push origin``` (para subir el archivo de local a github)
6. Entramos en el repositorio de https://github.com/undefined-academy/semana-1
  1. Buscamos el botón **Pull request** (arriba a la izquierda)
  2. Botón **New pull request**
  3. Por defecto intenta comparar las mismas ramas del repositorio (el mismo *main* de semana-1)
     1. Click en *compare across forks*
     2. Buscamos el nuestro
     3. Nos indica los cambios que se van a realizar al hacer click en **Create pull request**
7. Añadimos la descripción del Pull Request.
