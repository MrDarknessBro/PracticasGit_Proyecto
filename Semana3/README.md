# Semana 3
# Semana 3: Resolución de conflictos y Git avanzado

En esta semana se realizaron las siguientes actividades:

1. Generación de conflictos modificando archivos en diferentes ramas.
2. Resolución de conflictos manualmente.
3. Uso de comandos avanzados de Git como `revert` y `reset`.
4. Subida de cambios al repositorio remoto.

## Archivos incluidos

- `ejemplo_semana3.txt`: Archivo de práctica de la Semana 3.
- `README.md`: Documentación de la Semana 3.

## Comandos de Git utilizados

```bash
git checkout -b rama_conflicto
git add .
git commit -m "Cambios que causan conflicto"
git checkout main
git merge rama_conflicto
git status
git revert <hash_commit>
git reset --hard <hash_commit>
git push origin main
