# Proceso de Rebase

## Objetivo
Limpiar el historial de commits del proyecto Terraform.

## Pasos realizados
1. Se revisó el historial con `git log --oneline`.
2. Se ejecutó `git rebase -i HEAD~3`.
3. Se cambiaron mensajes poco claros usando `reword`.
4. Se fusionaron commits innecesarios usando `squash`.
5. Se subió el historial corregido con `git push --force`.

## Resultado
El historial remoto queda más limpio, con mensajes descriptivos y commits agrupados.
