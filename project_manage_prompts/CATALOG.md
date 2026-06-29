# Catálogo: project__manage_prompts/

## Propósito
Prompts para la gestión interna del proyecto. Sus ejecuciones producen cambios locales no rastreados por Git, como mover archivos al historial.

## Inventario

| Nombre base | Estado | Descripción | Formatos disponibles |
|---|---|---|---|
| update_history | LISTO | Mueve archivos válidos de `/to_history` a `/history/{rama}_{fecha}`. Incluye análisis de seguridad de los archivos a mover. | txt |

## Notas de uso
- Ejecutar con un agente de código que tenga permisos para correr comandos de shell.
- Los directorios `/to_history` y `/history` están excluidos de Git (ver `.gitignore`).
