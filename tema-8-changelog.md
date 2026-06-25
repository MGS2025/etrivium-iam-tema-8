# Tema 8 — Changelog

> **Título oficial**: RDLeg 2/2004 (TRLHL): Recursos de las Haciendas Locales. Ingresos de derecho público y privado. Tasas, contribuciones especiales y precios públicos. Impuestos municipales: concepto y clasificación.

---

## v1.0 — 2026-06-25 — Generación inicial completa

**Estado**: Pendiente de validación por María / Ana (IAM).

### Alcance y decisiones

- **Fuente nuclear**: **TRLHL (RDLeg 2/2004)**, versión consolidada del BOE.
- **Material del cliente**: `TEMA_08.docx` (índice oficial del tema).
- **Auditoría previa de cifras**: antes de redactar se verificaron todas las cifras fiscales contra el texto consolidado del BOE (ver `tema-8-fuentes.md`).

### Depuración del título del cliente

- El índice del cliente arrastraba al final del título la coletilla **"La Ley 39/2015 (LPACAP): recordatorio de contexto"**, que **no pertenece al objeto del Tema 8** (la LPACAP regula el procedimiento administrativo común, ajeno a las Haciendas Locales). Parece un **residuo de copia** de otra plantilla. **Se ha eliminado** del título oficial y de la estructura. Anotado para confirmación con Jesús/María.

### Correcciones aplicadas respecto del índice (auditoría BOE)

1. **IBI**: se corrige el rango de la **rústica** a **0,3 %–0,90 %** (el índice sugería un único rango; la urbana es 0,4 %–1,10 % y la rústica es distinta) [art. 72]. Añadido el tipo supletorio de los BICE (0,6 %).
2. **IBI — gestión**: precisado que es **gestión compartida** (catastral por el Estado / tributaria por el ayuntamiento), no solo "catastral por el Estado" [art. 77].
3. **Contribuciones especiales**: aclarado que el límite del **90 % es de la base imponible (art. 31)** y que los **módulos de reparto son del art. 32** (el índice los situaba juntos en el art. 31/32 de forma ambigua).
4. **IIVTNU**: desarrollado el **sistema dual** (objetivo/real) vigente tras la **STC 182/2021** y el **RDL 26/2021**, con la no sujeción por inexistencia de incremento (art. 104.5). El índice solo lo mencionaba como "plusvalía municipal".
5. **Gastos suntuarios**: precisada su base legal en la **DT 6.ª del TRLHL** (no en un artículo del cuerpo).
6. **Art. 2 (recursos)**: ajustada la letra h) a "**demás prestaciones de derecho público**" y reubicados los ingresos de derecho privado en la letra a); añadidos los **recargos** dentro de los tributos propios.
7. **Fundamento constitucional**: fijados los **arts. 137, 140 y 142 CE** (+ 133.2), con advertencia de que el art. 156 corresponde a las CCAA.
8. **IAE**: citados los artículos exactos de las exenciones (**82.1.b)** inicio de actividad y **82.1.c)** cifra de negocios < 1.000.000 €).
9. **IVTM**: añadido el **coeficiente de incremento máximo de 2** (art. 95.4).

### Entregables generados

| Fichero | Contenido |
|---|---|
| `tema-8-indice.md` | Índice de 11 secciones + tablas de datos clave |
| `tema-8-fuentes.md` | Registro Tier 1/2/3 + auditoría de cifras contra BOE |
| `tema-8-contenido.md` | Contenido teórico (11 secciones, callouts) |
| `tema-8-diagramas.md` | 12 diagramas SVG accesibles |
| `tema-8-test.md` | 150 preguntas + 20 pedagógicas |
| `tema-8-caso-practico.md` | 6 casos prácticos (gestión tributaria / IAM), 10 pts c/u |
| `tema-8-validacion.md` | Checklist de validación |
| `index.html` | Web autosuficiente, pestañas, motor test 1/3 |

### QA aplicado

- Cifras fiscales contrastadas con el texto consolidado del TRLHL (BOE) antes de la redacción.
- Diagramas con CSS **scoped** por SVG (evita el bug sistémico de colisión de estilos entre los 12 SVG) y verificados por render del `index.html` real.
- Balanceo automático A/B/C de las respuestas del test.
- Refs cruzadas verificadas vs BOAM 10.032 (T1, T2-T4).

### Pendiente

- Validación de contenido por María / Ana (IAM).
- Confirmar la eliminación de la coletilla LPACAP del título.
- Reverificar importes volátiles (tarifas IVTM, coeficientes IIVTNU) antes de cada convocatoria.
