## Resumen de Flujo de Trabajo

1. Asegúrate de tener la última versión del código:

```bash
git pull origin main
```

2. Trabaja en tus cambios y haz commits locales:

```bash
git add .
git commit -m "Tu mensaje de commit"
```

3. Antes de hacer un push, asegúrate de que tu rama esté actualizada:

```bash
git pull --rebase origin main
```

4. Finalmente, sube tus cambios al repositorio remoto:

```bash
git push origin feature
```

## Consejos:

- Siempre asegúrate de estar en la rama correcta antes de realizar un push o rebase.
- Si hay conflictos durante el rebase o el pull, resuélvelos manualmente y luego continúa con los pasos de la operación.
