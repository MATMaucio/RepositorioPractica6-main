# _¿Cómo se inicializa un repositorio en Git?_

Para inicializar un repositorio en Git se usa el comando:
```
git init
```

# _¿Cómo creas un repositorio en GitHub?_

1. Para crear un repositorio en git hub primero hay que ir a:
```
https://github.com
```
2. Vas a ingresar o crear una cuenta

3. Le das en el boton de New y agregas los datos que te pide

4. Creas el repositorio.

# _¿Cómo vinculas un repositorio local de Git con uno remoto en GitHub?_

Para vincular un repositorio local de git con uno remoto vas a:

1. Ejecutar el comando:

```
git remote add origin <URL_del_repositorio>
```

# _¿Cuál es el flujo básico de trabajo en Git y GitHub?_

El flujo de Trabajo de Git y Git Hub es:

1. Es agregar los cambios del directorio de trabajo al stage usando:

```
git add .
```

2. Luego hay que escribir el mensaje de lo que se esta modificando:

```
git commit
git commit - m "Mensaje Descriptivo"
```

3 Por ultimo se suben los cambios del repositorio local al remoto

```
git push -u origin master (Solo la primera vez)
git push para futuros cambios
```

# _¿Para que sirve el archivo .gitignore?_

Funciona para omitir archivos que no quieres que se suban

```
.gitignore
```

# _ ¿Cuál es el propósito de una rama?_

Una rama nos permite mantener por aparte algunas funciones para luego unirlas con la rama main

```
git branch nombre-rama(Crear rama)
git checkout nombre-rama(cambiar de rama)
git branch -d nombre-rama(Eliminar rama)

```

# _¿Qué es una fusión?_

Es una union entre la rama main y la rama que estes trabajando.

# _Explica los diferentes tipos de fusión que existen._

1. El primero es el:

```
git checkout rama-principal
```
Este nos permite cambiarnos a la rama principal en donde va a quedar la fusion

2. El segundo es:

```
git merge rama-secundaria
```
Este nos funciona para unir la rama secundaria con la primera

Las fudiones las podemos hacer automaticas y manual si encesitamos resolver conflictos

# _¿Cómo puedes ver el historial de tu repositorio?_

Para poder ver el historial de un repositorio usamos el comando:

```
git log
```
Tambien podemos guardar un archivo .txt usando el comando:

```
git log > commits.txt
```

# _¿Cuál es el propósito de una etiqueta?_

Las etiquetas se usan para versionar nuestros proyectos,librerias o codigos.

```
git tag (Lista las etiquetas)
git tag numero-versión(Crea etiquetas)
git tag -d numero-versión(Eliminar etiquetas)
```