# Flujo de comandos en Git

```bash
# Clonar el repositorio
$ git clone https://github.com/DavidBernalGonzalez/practicaGit.git
# Moverse al directorio del repositorio clonado
$ cd practicaGit/

# Ver las ramas remotas
$ git branch -r

# Cambiar a la rama 'practica01'
$ git checkout practica01

# Añadir los archivos modificados y hacer un commit
$ git add .
$ git commit -m "Edito los 3 archivos"

# Crear una nueva rama
$ git branch practica1_ROJOCOMAS_DANIEL

# Cambiar a la nueva rama creada
$ git checkout practica1_ROJOCOMAS_DANIEL

# Crear un archivo nuevo
$ nano practica1_ROJOCOMAS_DANIEL.txt

# Añadir y hacer commit del nuevo archivo
$ git add .
$ git commit -m "Lo subo"

# Editar el archivo y hacer otro commit
$ nano practica1_ROJOCOMAS_DANIEL.txt
$ git add .
$ git commit -m "Lo subo con mi nombre"

# Hacer push con upstream
$ git push --set-upstream origin practica1_ROJOCOMAS_DANIEL

# Cambiar la URL de push
$ git remote set-url --push origin https://github.com/Kbsoide21/practicaGit.git

# Verificar que la URL de push ha cambiado
$ git remote -v

# Hacer push nuevamente
$ git push --set-upstream origin practica1_ROJOCOMAS_DANIEL

# Cambiar de rama
$ git checkout practica01

# Hacer merge de las ramas
$ git merge practica1_ROJOCOMAS_DANIEL
