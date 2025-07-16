# 🧠 Git

Comandos esenciales de Git y repositorios llenos de aprendizaje. Guarda este archivo como referencia rápida para tu trabajo diario con Git. 🚀

---

bash
# Crear una nueva rama
git branch nombre-de-la-rama

# Cambiarse a una rama existente
git checkout nombre-rama

# Ver todas las ramas
git branch

# Fusionar una rama con la rama actual
git merge rama-villanos

# Eliminar una rama
git branch -d rama-villanos

# Forzar la eliminación de una rama
git branch -d rama-villanos -f

# Crear una rama y pasarse directamente a ella
git checkout -b 1-subir-todos-los-archivos-y-carpetas-avanzadas-desde-ahorita-en-git

# Hacer un commit con todos los archivos modificados
git commit -am "Agregamos a Doomsday"

# Hacer un commit normal (requiere git add)
git commit -m "Agregamos a Doomsday"

# Crear un tag simple
git tag super-release

# Eliminar un tag
git tag -d super-release

# Crear un tag anotado en el último commit
git tag -a v1.0.0 -m "Version 1.0.0 lista"

# Crear un tag anotado en un commit específico (por hash)
git tag -a v0.1.0 5dd61b1 -m "Version alpha de nuestra app"

# Ver detalles de un tag específico
git show v0.1.0

# Guardar cambios en stash
git stash

# Aplicar el último stash y eliminarlo de la lista
git stash pop

# Eliminar todos los stash
git stash clear

# Guardar stash con mensaje
git stash save "Agregamos a loki en villanos"

# Ver la lista de stash con estadísticas
git stash list --stat



