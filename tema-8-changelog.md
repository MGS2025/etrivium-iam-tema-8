# Tema 8 — Changelog

> **Título oficial**: RDLeg 2/2004 (TRLHL): Recursos de las Haciendas Locales. Ingresos de derecho público y privado. Tasas, contribuciones especiales y precios públicos. Impuestos municipales: concepto y clasificación.

---

## v1.5 — 2026-10-06 — Respuestas de la revisión jurídica

**Motivo**: respuestas a las dudas planteadas a la revisión jurídica (06-10-2026).

### Cambios

- Precio público: el ejemplo de instalaciones deportivas, que el art. 20.4.o) TRLHL recoge entre los supuestos de tasa, se sustituye por los campamentos urbanos de verano y las actividades de ocio de solicitud voluntaria que también ofrece el sector privado; mismo cambio en el caso práctico 1.
- **Citas entre corchetes al final del párrafo** (`[CE, art. 14]`) pasan a paréntesis con la ley detrás (`(art. 14 CE)`), el formato de las demás citas de inciso, por decisión de la revisión jurídica (06-10-2026). Se actualiza también la explicación de la convención de citas en Fuentes. Las claves bibliográficas de la tabla de fuentes no cambian.

---

## v1.4 — 2026-10-06 — Revisión de diagramas

**Motivo**: barrido de los diagramas de los 40 temas tras la revisión jurídica y de normas.

### Cambios

- Revisión visual de todos los diagramas, captura a captura (la medición automática no detecta contraste, flechas mal dirigidas ni textos pegados al borde): corregidos textos que se salían de su caja o del lienzo, cajas que se tocaban, flechas que no llegaban a su destino y textos con poco contraste. Sin cambios de contenido.

---

## v1.3 — 2026-10-01 — Revisión jurídica

**Estado**: aplicada la revisión jurídica de T1-T10 al Tema 8. Pendiente de validación.

### Cambios pedidos por la revisión (pestaña Fuentes)

1. Suprimida la nota metodológica sobre el título del índice de partida.
2. Suprimida la tabla «Tier 2» de material de partida (fila `[MAT-INDICE]` incluida). La fila `[BOAM-10032]` (temario oficial) pasa a la tabla de fuentes primarias; la tabla de descartadas pasa a «Tier 2».
3. Suprimida la fila de trazabilidad que remitía a ese material; la lista termina en la LBRL y la Ley 22/2006.
4. Pestaña Validación: suprimida la observación que repetía la nota del título.

### Reglas generales

- **Cajas**: «Dato clave examen» → «Dato clave»; «Cita constitucional» → «Cita normativa»; «Ejemplo Ayto Madrid» → «Ejemplo de aplicación en el Ayto»; «Referencia cruzada» → «Relación con otros temas» (HTML, `.md` y `CALLOUTS` de `build_t8.py`). Leyenda reescrita, sin promesas sobre el examen.
- **Citas de artículos**: «artículo» completo cuando la cita forma parte de la oración; «art.» abreviado dentro del paréntesis.
- **Reflexiones fuera de las cajas** suprimidas o reducidas al precepto («principio rector», «a medio camino», «prácticamente en desuso», «una vía de revisión propia del régimen de gran ciudad», «autotutela / ejecutividad / coercitividad»…).
- **Promesas sobre el examen** suprimidas («alta probabilidad de aparecer en el test oficial», «trampa de examen muy frecuente», «exención estrella», «es un clásico distractor», «se preguntan literalmente», «es donde más se examina», «la pregunta más repetida»…).

### Correcciones de fondo (contrastadas con el BOE consolidado)

1. **Ingresos de derecho privado**: se suprime la afirmación de que su cobro impagado va por apremio «(art. 2.2)». El art. 4 TRLHL sujeta su efectividad a las **normas y procedimientos del derecho privado**. Corregido en contenido, índice, diagramas D3 y D12, caso práctico 2, validación y test.
2. **Art. 3.3**: solo excluye los ingresos de **bienes de dominio público local**; se suprime la mención a los bienes comunales. Se añaden los arts. 3.4 y 5.
3. **Art. 2.1.b)**: los recargos son sobre los impuestos «de las comunidades autónomas o de otras entidades locales» (no del Estado).
4. **Art. 41**: se sustituye la definición antigua de precio público por el texto vigente («siempre que no concurra ninguna de las circunstancias especificadas en el artículo 20.1.B)»). El carácter no tributario se apoya en el art. 2.1.b) y e), no en el art. 41.
5. **Art. 47.1**: la delegación del Pleno es «en la Comisión de Gobierno, conforme al artículo 23.2.b) LBRL»; se suprime que en Madrid «suele estar delegada en la JGL» (el art. 11.3 LCREM solo permite delegar las competencias del Pleno en sus Comisiones).
6. **CE**: la frase «La Constitución garantiza la autonomía de los municipios» es del art. 140, no del 137.
7. **Estructura del TRLHL**: el título I abarca los arts. 2 a 55; los impuestos municipales están en el título II (arts. 56 a 130), no en el título I.
8. **Art. 1**: la cita «tiene por objeto la regulación de la actividad financiera» no está en la ley; se sustituye por el texto de los arts. 1.1 y 1.2.
9. **Art. 20.3**: tiene letras a) a v) tras la Ley 9/2025, de 3 de diciembre (zonas de bajas emisiones). Supuestos de 20.3 y 20.4 recolocados en su letra; añadidos 20.2, 20.5, 21, 22, 24.3 y 24.4.
10. **Art. 25**: el informe técnico-económico se exige para tasas por dominio público o para financiar nuevos servicios, y debe poner de manifiesto el valor de mercado o la previsible cobertura del coste.
11. **Contribuciones especiales**: el coste soportado está en el art. 31.5 (no 31.2); el acuerdo de ordenación, en el 34.3.
12. **IAE**: «dos primeros períodos impositivos» (no «dos primeros años»).
13. **IIVTNU**: «a instancia del sujeto pasivo» (art. 107.5) en lugar de «a elección del contribuyente»; base por coeficientes del art. 107.1.
14. **Gastos suntuarios**: base en la DT 6.ª, no en el art. 59.2; suprimidos los datos de sujeto pasivo y tipo que no figuran en la DT 6.ª.
15. **Ley 22/2006**: BOE núm. 159, de 05/07/2006 (no núm. 182, de 01/08/2006); el art. 26 crea un «ente autónomo de gestión tributaria».
16. **LGT**: el art. 12.1 TRLHL remite a la LGT («de acuerdo con lo prevenido»), no como aplicación «subsidiaria»; el apremio se apoya en los arts. 160, 161 y 163 LGT.

### Test (regla de preguntas literales)

- **Banco de 150**: 50 preguntas reescritas para que enunciado y respuesta salgan del texto literal del precepto citado (supuestos de aplicación, preguntas de opinión, de doctrina o con datos erróneos), 4 con solo la referencia corregida (Q79, Q88, Q108, Q145) y 1 con el enunciado ajustado al literal (Q66). El resto se mantiene.
- Respuestas correctas repartidas 50/50/50 entre a, b y c en el `.md` (antes 102 en a).
- **20 pedagógicas**: 6 reescritas (3, 4, 7, 8 y, en parte, 14 y 20) y explicaciones ajustadas al texto de la norma.

---

## v1.2 — 2026-09-06 — Ficha de extensión y tiempo de estudio

**Estado**: sin cambios de contenido. Solo se añade información sobre el propio tema.

**Motivo**: petición del IAM (Jesús Cuadrado, 02-09-2026) al validar el Tema 30. Acepta la extensión de los temas «compuestos» a condición de que se informe de «su extensión en palabras y tiempo estimado de estudio». Al revisarlo se vio que ese dato solo aparecía en 16 de los 40 temas, y que faltaba justo en los más largos.

### Alcance

- Ficha bajo la cabecera del tema, y al final de la pestaña Índice donde esa pestaña existe:
  - **Extensión**: ~5.800 palabras · 12 diagramas · 150 preguntas de test
  - **Tiempo estimado de estudio**: 11-13 horas (primera vuelta completa, sin contar repasos)
- La cifra de palabras de la tabla de entregables se sincroniza con la ficha, para que el tema no muestre dos recuentos distintos.
- Las horas salen de una fórmula común a los 40 temas, para que sean comparables entre sí: contenido a 1.500 palabras/hora (ritmo de estudio activo), diagramas a una hora por cada cinco y test a dos minutos por pregunta. Se publica como intervalo de dos horas.
- Generado con `_tools-qa/ficha_estudio.py`, idempotente y reejecutable tras cualquier regeneración con `build_tNN.py`.

---

## v1.1 — 2026-06-30 — Correcciones de María (IAM)

**Estado**: Revisión de María aplicada. Pendiente de validación final.

### Cambios

1. **§5.2 (nueva) — Supuestos concretos de tasas (arts. 20.3 y 20.4)**: a petición de María, y atendiendo a que el enunciado oficial pide *"especial referencia a las tasas"*, se añade el listado expreso del TRLHL:
   - **Art. 20.3** — utilización privativa o aprovechamiento especial del **dominio público** (vados, terrazas, ocupación de suelo/subsuelo/vuelo, estacionamiento ORA/SER, zanjas, quioscos…).
   - **Art. 20.4** — **servicios y actividades** administrativas (documentos, licencias urbanísticas y de apertura, extinción de incendios, cementerios, recogida de residuos, alcantarillado…).
   - Se subraya que **ambos listados son enunciativos, no cerrados**, y se aclara la diferencia 20.3 (dominio público) vs 20.4 (servicios), que en el índice del cliente aparecía referida solo como "art. 20.3".
2. **§10.2 (nueva) — Gestión de la Agencia Tributaria Madrid**: se amplía la sección de Madrid con una tabla de **forma de gestión**: **IBI, IVTM e IAE por padrón/matrícula** (recibo periódico) y **ICIO e IIVTNU por autoliquidación** del contribuyente. La antigua §10.2 ("relevancia para el IAM") pasa a **§10.3**.
3. **Test**: dos preguntas reorientadas (Q49 → supuestos del art. 20.3; Q72 → supuestos del art. 20.4) para cubrir la posible pregunta de examen sobre si un servicio concreto encaja como tasa de dominio público o de servicio. El banco se mantiene en **150 preguntas**.
4. **Versionado** actualizado en todos los `.md`, el `index.html` y el changelog.

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
