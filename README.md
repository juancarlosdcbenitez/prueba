# Prueba de Markdown

Esto es un texto introductorio. Markdown nos permite dar formato al texto de una manera sencilla y legible para documentar nuestro código.

## Cabeceras

Usamos `#` para las cabeceras. Cuantos más `#` se use, menor será el nivel del encabezado.

### Texto con formato

Podemos poner el texto en **negrita** usando dos asteriscos (`**negrita**`) o en *cursiva* con uno solo (`*cursiva*`). También podemos `resaltar código` con comillas invertidas.

### Listas

Las listas nos ayudan a organizar la información:

* **Lista de elementos:**
    * Primer elemento.
    * Segundo elemento.
        * Un sub-elemento anidado.

* **Lista de tareas:**
    - [x] Aprender la sintaxis básica de Markdown.
    - [ ] Crear una tabla con información.
    - [ ] Insertar un gráfico.

### Gráfico (se usa la sintaxis Mermaid)

GitHub tiene soporte integrado para **Mermaid**, una herramienta que permite crear diagramas y gráficos a partir de un texto, lo cual es idóneo para representar flujos de trabajo o diagramas simples.

```mermaid
graph TD;
    A[Inicio del Proyecto] --> B{¿Hay un README?};
    B -- Sí --> C[Leer documentación];
    B -- No --> D[Crear README.md];
    D --> C;
    C --> E[Empezar a codificar];
