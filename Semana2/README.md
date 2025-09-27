# Semana 2
# Semana 2: Trabajando con ramas y commits

En esta semana se realizaron las siguientes actividades:

1. Creación de una rama llamada `rama_semana2`.
2. Realización de cambios en archivos de prueba dentro de la rama.
3. Unión de la rama con la rama principal (`main`) mediante merge.
4. Subida de los cambios al repositorio remoto.

## Archivos incluidos

- `ejemplo_semana2.txt`: Archivo de práctica de la Semana 2.
- `README.md`: Documentación de la Semana 2.

## Comandos de Git utilizados

```bash
git checkout -b rama_semana2
git add .
git commit -m "Agregar cambios de la Semana 2"
git checkout main
git merge rama_semana2
git push origin main
