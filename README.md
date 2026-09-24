# Taller Integrador - Auditoría y Refactorización de Calculadora

## Estudiante: Cristian Diaz

### Descripción del proyecto
Este proyecto consiste en la auditoría, refactorización y control de versiones de una aplicación web de calculadora de notas académicas, aplicando buenas prácticas de desarrollo, semántica HTML5, modularización CSS y un flujo de trabajo profesional con ramas en Git.

### Tabla de Hallazgos y Correcciones
| Componente | Hallazgo / Defecto Original | Corrección Aplicada |
| :--- | :--- | :--- |
| **HTML** | Presencia de código muerto y variables globales sin uso (`data1`, `TempValue2`). | Eliminación de código obsoleto y mejora de la semántica con etiquetas estructuradas. |
| **CSS** | Nombres de archivos con espacios y mayúsculas (`Estilos Del Sitio.CSS`). | Estandarización del archivo a `styles.css` para evitar fallos en producción. |
| **JS** | Lógica poco legible y manejo básico de errores. | Refactorización de la función de cálculo con validación estricta de notas y formato limpio. |