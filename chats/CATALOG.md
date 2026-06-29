# Catálogo: chats/

## Propósito
Prompts diseñados para consumo directo en interfaces de chat LLM o como instrucciones base para agentes.

## Inventario

| Nombre base | Estado | Descripción | Formatos disponibles |
|---|---|---|---|
| refinar_prompt | LISTO | Analiza, califica y mejora un prompt proporcionado por el usuario | txt, xml |

## Notas de uso
- Antes de ejecutar `refinar_prompt`, colocar el prompt a refinar entre los delimitadores `=== INICIO PROMPT SECUNDARIO ===` / `=== FIN PROMPT SECUNDARIO ===`.
- Usar `../utils/transformar_txt_to_xml.txt` para generar versiones en otros formatos a partir del `txt/` canónico.
