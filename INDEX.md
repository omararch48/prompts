# Índice del proyecto: prompts

## Propósito del proyecto
Compilación de prompts, scripts y herramientas reutilizables para tareas recurrentes, organizados por tema. Cada directorio de tema contiene un archivo `CATALOG.md` con el inventario y la descripción de los prompts disponibles.

## Convenciones

### Formatos
Los prompts pueden existir en múltiples formatos equivalentes dentro de sus subdirectorios (`txt/`, `xml/`, `json/`, `md/`). Para transformar entre formatos, usar `utils/transformar_txt_to_xml.txt`.

### Estados
Cada prompt incluye al inicio la línea `[ESTADO: LISTO | BORRADOR | DEPRECADO]`. Si no aparece, el estado por defecto es `BORRADOR`. Solo ejecutar prompts con estado `LISTO` salvo indicación explícita del usuario.

---

## Directorios de temas

| Directorio | Descripción |
|---|---|
| `chats/` | Prompts para consumo en interfaces de chat LLM o como base para agentes |
| `git/` | Prompts para tareas relacionadas con el sistema de control de versiones Git |
| `project_manage_prompts/` | Prompts para la gestión interna del proyecto (ejecuciones no rastreadas en Git) |
| `utils/` | Prompts de utilidad para transformaciones y operaciones dentro del proyecto |

---

## Directorios auxiliares

| Directorio | Descripción |
|---|---|
| `guides/` | Recursos de referencia para el desarrollador (no contiene prompts ni `CATALOG.md`) |
| `history/` | Historial de ejecuciones y reportes — excluido de Git, gestionado por `project__manage_prompts/` |
| `to_history/` | Buffer de staging hacia `/history` — excluido de Git |
