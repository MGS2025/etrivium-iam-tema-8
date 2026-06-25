# Tema 8 — Registro de Fuentes

> **Título oficial**: Real Decreto Legislativo 2/2004, de 5 de marzo, por el que se aprueba el texto refundido de la Ley Reguladora de las Haciendas Locales: Recursos de las Haciendas Locales. Clasificación: ingresos de derecho público e ingresos de derecho privado. Especial referencia a las tasas. Contribuciones especiales y precios públicos. Impuestos municipales: concepto y clasificación.
>
> **Bloque**: Parte I — Administrativo/Jurídico
> **Nivel**: C1 — Técnico Auxiliar TIC, Ayuntamiento de Madrid
> **Versión**: 1.0 — Generación inicial
> **Fecha**: 2026-06-25

---

## Naturaleza de las fuentes en este tema

El Tema 8 trabaja con un **corpus normativo cerrado**: el articulado del **texto refundido de la Ley Reguladora de las Haciendas Locales (TRLHL)**, aprobado por el **Real Decreto Legislativo 2/2004, de 5 de marzo**, en su redacción vigente (versión consolidada del BOE), completado con:

- la **Constitución Española** (arts. 133, 137, 140 y 142) para el fundamento de la autonomía y suficiencia financiera local;
- la **Ley 58/2003, General Tributaria (LGT)**, de aplicación subsidiaria y de la que procede el concepto de impuesto (art. 2.2) y la enumeración de entidades del art. 35.4;
- el **Real Decreto-ley 26/2021, de 8 de noviembre**, y la **STC 182/2021** para la reforma del **IIVTNU** (plusvalía municipal);
- la **Ley 22/2006, de 4 de julio, de Capitalidad y de Régimen Especial de Madrid**, para la especialidad del Ayuntamiento de Madrid.

> **Nota metodológica sobre el título del índice del cliente**: el índice aportado (`TEMA_08.docx`) arrastraba al final del título la coletilla *"La Ley 39/2015 (LPACAP): recordatorio de contexto"*, que **no pertenece al objeto de este tema** (procedimiento administrativo común, ajeno a las Haciendas Locales) y parece un residuo de copia de otra plantilla. Se ha **eliminado** del título y de la estructura. Ver `tema-8-changelog.md`.

---

## Tier 1 — Fuentes primarias (cita directa)

| Ref | Título | Publicación / origen | Uso |
|---|---|---|---|
| [TRLHL] | Real Decreto Legislativo 2/2004, de 5 de marzo, texto refundido de la Ley Reguladora de las Haciendas Locales | BOE núm. 59 de 09/03/2004 (versión consolidada, BOE-A-2004-4214) | **Fuente nuclear**: recursos (art. 2), ingresos de derecho privado (art. 3), tasas (arts. 20-27), contribuciones especiales (arts. 28-37), precios públicos (arts. 41-47), impuestos municipales (arts. 59-110) |
| [CE] | Constitución Española de 1978 | BOE núm. 311 de 29/12/1978 | Arts. 133 (legalidad tributaria), 137 y 140 (autonomía local), 142 (suficiencia financiera) |
| [LGT] | Ley 58/2003, de 17 de diciembre, General Tributaria | BOE núm. 302 de 18/12/2003 | Aplicación subsidiaria; concepto de impuesto (art. 2.2.c); entidades sin personalidad (art. 35.4) |
| [RDL 26/2021] | Real Decreto-ley 26/2021, de 8 de noviembre, de adaptación del TRLHL a la STC 182/2021 | BOE núm. 268 de 09/11/2021 (BOE-A-2021-18276) | Nuevo sistema dual de base imponible del IIVTNU |
| [STC 182/2021] | Sentencia del Tribunal Constitucional 182/2021, de 26 de octubre | BOE (suplemento) | Declaración de inconstitucionalidad del método objetivo único del IIVTNU |
| [LCREM] | Ley 22/2006, de 4 de julio, de Capitalidad y de Régimen Especial de Madrid | BOE núm. 182 de 01/08/2006 (BOE-A-2006-12057) | Régimen especial de Madrid: Tribunal Económico-Administrativo Municipal (art. 25) y Agencia Tributaria Madrid (art. 26) |
| [LBRL] | Ley 7/1985, de 2 de abril, Reguladora de las Bases del Régimen Local | BOE núm. 80 de 03/04/1985 | Autonomía para establecer y exigir tributos; municipios de gran población (Título X) |

### Esquema de referencia para el contenido

- **Articulado TRLHL**: `[TRLHL, art. X]` o `[TRLHL, art. X.Y]` — p. ej. `[TRLHL, art. 24.2]`
- **Constitución**: `[CE, art. 142]`
- **Ley General Tributaria**: `[LGT, art. 2.2.c)]`
- **Disposición transitoria**: `[TRLHL, DT 6.ª]`

---

## Tier 2 — Material aportado por el cliente

| Ref | Archivo | Aporte |
|---|---|---|
| [MAT-INDICE] | `Test_Prompting/temas junio/TEMA_08.docx` | Índice/esqueleto oficial del tema (título + epígrafes). Depurado el residuo "Ley 39/2015 LPACAP" del título |
| [BOAM-10032] | Temario oficial BOAM 10.032 (23-dic-2025) | Enunciado oficial del Tema 8 |

---

## Tier 3 — Descartadas

- **Doctrina académica y academias privadas**: no se usan como fuente de contenido (solo apoyo de contraste).
- **Ordenanzas fiscales concretas del Ayuntamiento de Madrid**: se citan a título de ejemplo, sin reproducir cuantías concretas (datos **volátiles**, se actualizan cada ejercicio).
- **Importes en euros del cuadro de tarifas del IVTM (art. 95.1)**: no se reproducen importes concretos por actualizarse vía Leyes de Presupuestos; solo se explica la estructura (clase + potencia + coeficiente máx. 2).

---

## Normas de citación en el contenido

1. Toda afirmación que reproduzca el articulado va acompañada de `[TRLHL, art. X]`.
2. Los datos memorísticos (cuantías, porcentajes, límites, órganos competentes) se marcan con `[DATO CLAVE EXAMEN]`.
3. Las reproducciones literales o paráfrasis cercanas del articulado se marcan con `[CITA NORMATIVA]`; las de la Constitución, con `[CITA CONSTITUCIONAL]`.
4. La aplicación al Ayuntamiento de Madrid (IAM) se marca con `[EJEMPLO AYTO MADRID]`.
5. Los enlaces a otros temas del temario se marcan con `[REFERENCIA CRUZADA]`.

---

## Datos verificados contra el BOE (auditoría v1.0)

Las siguientes cifras y referencias se han **contrastado con el texto consolidado** antes de la redacción:

- IBI: urbana **0,4 %–1,10 %**, rústica **0,3 %–0,90 %**, BICE 0,6 % supletorio [art. 72]; gestión **compartida** [art. 77].
- IAE: exención por cifra de negocios **< 1.000.000 €** [art. 82.1.c)]; exención inicio (2 periodos) [art. 82.1.b)]; personas físicas exentas.
- IVTM: coeficiente de incremento **máximo 2** [art. 95.4].
- ICIO: tipo **máximo 4 %** [art. 102.3]; potestativo [art. 59.2].
- IIVTNU: sistema **dual** y no sujeción por inexistencia de incremento [art. 104.5], conforme a STC 182/2021 + RDL 26/2021.
- Contribuciones especiales: base **máx. 90 %** del coste soportado [**art. 31**]; módulos [**art. 32**] (no confundir artículos).
- Tasas: límite del **coste** [art. 24.2]; dominio público por valor/utilidad [art. 24.1].
- Precios públicos: cuantía **mínimo coste** [art. 44]; **no** son tributo [art. 41].
- Gastos suntuarios: solo cotos de caza y pesca [**DT 6.ª**].
- Fundamento constitucional: **arts. 137, 140, 142 (+133.2)**; el art. 156 CE es de las CCAA (distractor).

---

## Trazabilidad fuente → contenido → pregunta

Cada pregunta del banco y cada cuestión de los casos prácticos debe poder reconducirse a:

1. Un artículo concreto del TRLHL (arts. 2-110 o DT 6.ª), o
2. Un precepto constitucional invocado (arts. 133, 137, 140, 142 CE), o
3. Un precepto de la LGT (arts. 2.2, 35.4) o de la reforma del IIVTNU (RDL 26/2021), o
4. La Ley 22/2006 de Capitalidad (especialidad de Madrid), o
5. El material aportado por el cliente (Tier 2).
