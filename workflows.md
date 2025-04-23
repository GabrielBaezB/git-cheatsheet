# ⚙️ Flujos de Trabajo Recomendados

# 🚀 Feature Branch Workflow:
git checkout -b feature/nueva-funcionalidad
# haces commits...
git push origin feature/nueva-funcionalidad
# pull request y merge a main

# 🧹 Git Rebase para historial limpio:
git fetch origin
git rebase origin/main

# 🎯 Release Workflow:
git checkout -b release/v1.0.0
git merge develop
git tag -a v1.0.0 -m "Primera versión"
git push --tags
