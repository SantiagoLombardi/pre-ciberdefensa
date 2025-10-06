# Reglas de Interacción de Gemini en el Vault

Este documento define las reglas y procedimientos que seguiré (Gemini) para asistir en la gestión de este vault de Obsidian. El objetivo es mantener la consistencia, calidad y estructura del conocimiento aquí almacenado.

## Reglas Generales

1.  **Idioma:** Todas mis interacciones y contribuciones serán en español, para mantener la coherencia del vault.
2.  **Consistencia:** Antes de cualquier acción, analizaré los archivos y carpetas circundantes para entender y replicar los patrones de nombrado, formato y estructura existentes.
3.  **Atomicidad:** Realizaré cambios de forma incremental y atómica, explicando cada paso si es necesario.
4.  **No Modificar Archivos Críticos:** Nunca modificaré archivos dentro de las carpetas `.obsidian` o `.smart-env`, ya que contienen configuración vital del vault y sus plugins.
5.  **Uso de Wiki-Links:** Para conectar ideas y conceptos, utilizaré el formato `[[Nombre de la Nota]]` siempre que sea relevante.

---

## Sistematización de Acciones

### 1. Búsqueda de Archivos y Contenido

-   **Herramientas:** Utilizaré `glob` para búsquedas por patrón de nombre/ruta y `search_file_content` para búsquedas por contenido interno.
-   **Proceso:**
    1.  Iniciar con una búsqueda amplia para localizar archivos potencialmente relevantes.
    2.  Si la búsqueda es por concepto, usaré `search_file_content` con palabras clave en español.
    3.  Antes de proponer una acción, leeré el contenido de los archivos más relevantes con `read_file` para asegurar el contexto.

### 2. Creación de Archivos

-   **Regla Principal:** La creación de un archivo nuevo siempre seguirá la estructura predefinida del vault.
-   **Proceso para Zettelkasten (en `03 - Zettelkasten/`):**
    1.  **Ubicación:** El archivo se creará en la carpeta `03 - Zettelkasten/` o una subcarpeta apropiada (ej. `comandos/`).
    2.  **Plantilla:** El contenido se basará estrictamente en la plantilla `Templates/template_zettel_mejorado.md`.
    3.  **Metadata:** Generaré y completaré la metadata requerida:
        -   `id`: Con el formato `YYYYMMDDHHmmss`.
        -   `date`: Con el formato `YYYY-MM-DD`.
        -   `tags`: Sugeriré etiquetas relevantes basadas en el contenido.
    4.  **Nombre del Archivo:** El nombre será descriptivo, conciso y en español (ej. `Nuevo Concepto de Redes.md`).
-   **Proceso para otros archivos:** Para notas de plan (`01 - Plan...`) o recursos (`02 - Recursos...`), seguiré la nomenclatura y estructura de carpetas existente.

### 3. Edición de Archivos

-   **Herramientas:** Usaré `replace` para cambios pequeños y precisos. Para cambios mayores, podría leer el archivo, modificar el contenido y reescribirlo con `write_file`, siempre pidiendo confirmación.
-   **Proceso:**
    1.  **Contexto:** Siempre leeré el archivo con `read_file` para obtener el contexto exacto y la indentación correcta antes de una modificación.
    2.  **Respetar Estructura:** Al editar, especialmente un Zettel, respetaré las secciones (`Idea Atómica`, `Desarrollo`, `Conexiones`).
    3.  **Actualizar Conexiones:** Si edito o añado información que se relaciona con otras notas, propondré añadir los `[[wiki-links]]` correspondientes en la sección `Notas relacionadas`.

### 4. Reestructuración del Proyecto

-   **Regla de Oro:** No moveré, renombraré ni eliminaré masivamente archivos sin proponer un plan detallado y recibir tu aprobación explícita.
-   **Proceso:**
    1.  **Propuesta:** Presentaré una justificación clara del cambio (ej. "Propongo crear la carpeta `Herramientas/` dentro de `02 - Recursos de Repaso/Técnica` para organizar mejor los archivos relacionados").
    2.  **Plan:** Detallaré los archivos a mover/renombrar y la estructura final.
    3.  **Advertencia:** Te informaré sobre el posible impacto en los enlaces, aunque Obsidian suele manejarlos bien.

### 5. Proactividad y Propuestas de Mejora

-   **Mandato:** Actuaré como un asistente proactivo para mejorar la calidad y organización del vault.
-   **Ejemplos de Propuestas:**
    -   **Sugerir Enlaces:** "He notado que las notas [[Shodan]] y [[Censys]] no están enlazadas directamente, pero ambas tratan sobre motores de búsqueda de activos. ¿Quieres que las interconecte?"
    -   **Completar Metadata:** "Este Zettel no tiene etiquetas. Basado en su contenido, sugiero añadir `tags: [protocolo, redes]`. ¿Te parece bien?"
    -   **Identificar Patrones:** "Veo que has creado varias notas sobre comandos de red. ¿Quieres que cree una nota índice llamada `Comandos de Red` que las enlace a todas?"
    -   **Mejorar Contenido:** "La sección de 'Desarrollo' en esta nota es muy breve. ¿Te gustaría que la expandiera con más detalles sobre [tema]?"
