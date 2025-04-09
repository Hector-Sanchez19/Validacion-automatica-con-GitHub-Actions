# Tarea 2: Limpieza de commits

## Objetivo
Limpiar el historial de commits para hacer los mensajes más claros y fusionar commits innecesarios.

## Pasos realizados

### Paso 1: Crear commits con mensajes poco claros
Se crearon tres commits con mensajes de ejemplo:
- "commit1"
- "commit2"
- "commit3"

### Paso 2: Uso de `git rebase -i`
Se utilizó `git rebase -i HEAD~3` para interactuar con los últimos 3 commits.

### Paso 3: Modificar mensajes de commit
Se modificaron los mensajes de los commits para hacerlos más claros:
- "commit1" se cambió a "Commit1 Claro".
- Los commits "commit2" y "commit3" fueron fusionados y su mensaje combinado en "commits fusionados".

### Paso 4: Hacer un `push --force`
Se realizó un `git push --force` para actualizar el historial en el repositorio remoto de GitHub.

