# 🔵 Comandos Avanzados de Git

```bash
# Ver ramas
git branch

# Crear nueva rama
git checkout -b nombre-rama

# Cambiar de rama
git checkout nombre-rama

# Rebase interactivo
git rebase -i HEAD~3

# Fusionar ramas
git merge nombre-rama

# Ver diferencias entre ramas o commits
git diff

# Deshacer último commit (sin borrar cambios)
git reset --soft HEAD~1

# Eliminar commit permanentemente
git reset --hard HEAD~1
