# ⚙️ Flujos de Trabajo Recomendados

# 🚀 Feature Branch Workflow:
```bash
git checkout -b feature/nueva-funcionalidad
```
# haces commits...
```bash
git push origin feature/nueva-funcionalidad
```
# pull request y merge a main

# 🧹 Git Rebase para historial limpio:
```bash
git fetch origin
```
```bash
git rebase origin/main
```
# 🎯 Release Workflow:
```bash
git checkout -b release/v1.0.0
```
```bash
git merge develop
```
```bash
git tag -a v1.0.0 -m "Primera versión"
```
```bash
git push --tags
```
