# 🧭 Guía de Organización Gráfica y Conexiones: 11-1 vs 11-2

Para mantener una estructura profesional y asegurar que la visualización gráfica de `11_1` y `11_2` permanezca limpia y separada, hemos implementado una metodología de "Silos de Información".

## 1. Principio de Separación (Silos)
Cada grado actúa como un universo independiente.
- **Regla de Oro**: Un archivo ubicado en la carpeta `11_1` **nunca** debe contener un enlace interno hacia la carpeta `11_2`, y viceversa.
- Si necesitas referenciar un tema común, crea una nota en una carpeta neutral (fuera de `11_1` y `11_2`) o duplica la información si es necesario diferenciar el contexto.

## 2. Gestión de Nombres Únicos (Sufijos)
Para garantizar la separación total en la gráfica y evitar nodos fusionados, es **OBLIGATORIO** usar sufijos en los nombres de archivos principales de materias.

### Regla de Nombres:
- **11-1**: `[NombreMateria]_11_1.md` (Ej: `Matemáticas_11_1.md`)
- **11-2**: `[NombreMateria]_11_2.md` (Ej: `Matemáticas_11_2.md`)

### ¿Por qué?
Obsidian une nodos si los nombres son idénticos. Al diferenciar el nombre del archivo, creamos entidades gráficas distintas que nunca se tocarán accidentalmente.

## 3. Configuración de la Vista de Gráfica
Para visualizar los grados por separado profesionalmente:

1. Abre la **Vista de Gráfica**.
2. Ve a la configuración (icono de engranaje).
3. **Filtros**:
   - Escribe `path:11_1` en la búsqueda para ver solo el universo de 11-1.
4. **Grupos** (Para ver ambos pero diferenciados):
   - Crea un grupo con la consulta `path:11_1` y asígnale un color (ej. Azul).
   - Crea un grupo con la consulta `path:11_2` y asígnale un color (ej. Rojo).

## 4. Estructura de Dashboards
Los archivos `11_1.md` y `11_2.md` funcionan como los "Hubs" o Centros de Control.
- **Jerarquía**: Dashboard > Materia > Temas.
- Mantén estos archivos limpios, actuando solo como índices hacia las carpetas de materias.

---
*Este archivo debe permanecer en la raíz para referencia futura de mantenimiento.*
