# 🚨 Solución de Problemas Comunes en Git

# 🐛 Error: "fatal: refusing to merge unrelated histories"
```bash
git pull origin main --allow-unrelated-histories
```
# Error: "Permission denied (publickey)"
- Verifica que tengas agregada tu clave SSH en GitHub.
- Usa:
```bash
ssh-add ~/.ssh/id_rsa
```

# Error: "Your branch is ahead/behind"
- Opción 1:
```bash
git pull --rebase
```

- Opción 2 (si estás seguro):
```bash
git push --force
```
