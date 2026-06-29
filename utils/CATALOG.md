# Catálogo: utils/

## Propósito
Prompts de utilidad para operaciones internas del proyecto. Generan salidas relevantes para el flujo de trabajo del agente, como transformaciones de formato entre prompts.

## Inventario

| Nombre base | Estado | Descripción | Formatos disponibles |
|---|---|---|---|
| transformar_txt_to_xml | LISTO | Transforma un prompt entre formatos estructurados. Actualmente soporta el tipo `txt_to_xml`. Genera un archivo de evaluación de la transformación. | txt |

## Notas de uso
- Proporcionar en los datos de entrada: el prompt secundario, el tipo de transformación (`txt_to_xml`) y las reglas de mapeo opcionales.
- La salida de evaluación se guarda en `to_history/` para ser procesada con `project_manage_prompts/txt/update_history.txt`.
