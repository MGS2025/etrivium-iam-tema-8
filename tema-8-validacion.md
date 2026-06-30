# Tema 8 — Checklist de Validación

> **Título oficial**: RDLeg 2/2004 (TRLHL): Recursos de las Haciendas Locales. Clasificación: ingresos de derecho público y privado. Tasas, contribuciones especiales y precios públicos. Impuestos municipales: concepto y clasificación.
> **Versión**: 1.1 — Correcciones de María (supuestos de tasas 20.3/20.4 + gestión ATM)
> **Fecha**: 2026-06-30
> **Revisoras**: María + Ana (IAM)

---

## Cómo usar este checklist

- **OK** → el criterio se cumple sin cambios.
- **REVISAR** → necesita ajuste o aclaración (indicar qué).
- **NO** → no se cumple o es incorrecto. Justificar.

---

## 1. Fuentes y trazabilidad

- [ ] La fuente nuclear es el **TRLHL (RDLeg 2/2004)** en su versión consolidada.
- [ ] Las cifras fiscales se han **auditado contra el BOE** antes de redactar (ver `tema-8-fuentes.md`, apartado de auditoría).
- [ ] Cada afirmación que reproduce el articulado está referenciada con `[TRLHL, art. X]`.
- [ ] Cada pregunta del banco y de los casos puede reconducirse a un artículo del TRLHL o normativa conexa.

## 2. Estructura del contenido

- [ ] El `tema-8-indice.md` refleja fielmente la estructura de `tema-8-contenido.md`.
- [ ] Las secciones cubren: marco normativo, recursos (art. 2), ingresos de derecho público y privado, tasas, contribuciones especiales, precios públicos, impuestos municipales (concepto y clasificación) y especialidad de Madrid.
- [ ] Los conceptos memorizables aparecen como `[DATO CLAVE EXAMEN]`.
- [ ] Las reproducciones del articulado aparecen como `[CITA NORMATIVA]` / `[CITA CONSTITUCIONAL]`.
- [ ] Los ejemplos del Ayto de Madrid / IAM están marcados como `[EJEMPLO AYTO MADRID]`.

## 3. Rigor jurídico (datos sensibles auditados)

- [ ] Fundamento constitucional: **arts. 137, 140 y 142 CE** (+ 133.2); NO el art. 156 (que es de CCAA).
- [ ] Recursos del **art. 2.1**: patrimonio, tributos propios + recargos, participación Estado/CCAA, subvenciones, precios públicos, crédito, multas, demás prestaciones de derecho público.
- [ ] Ingresos de derecho privado (art. 3): patrimonio + herencias/legados/donaciones; **el cobro impagado va por apremio** (art. 2.2).
- [ ] Tasas: cuantía por servicios **no excede del coste** [art. 24.2]; dominio público por valor/utilidad [art. 24.1]; ordenanza fiscal del Pleno.
- [ ] Contribuciones especiales: base **máx. 90 %** del coste soportado [**art. 31**]; módulos [**art. 32**] (¡no intercambiar artículos!).
- [ ] Precios públicos: **mínimo el coste** [art. 44]; **no** tienen naturaleza tributaria [art. 41]; Pleno (delegable JGL).
- [ ] IBI: urbana **0,4–1,10 %**, rústica **0,3–0,90 %** [art. 72]; gestión **compartida** [art. 77].
- [ ] IAE: exención cifra de negocios **< 1.000.000 €** [art. 82.1.c)]; personas físicas y 2 primeros años exentos [art. 82.1.b)].
- [ ] IVTM: coeficiente de incremento **máximo 2** [art. 95.4].
- [ ] ICIO: tipo **máximo 4 %** [art. 102.3]; potestativo.
- [ ] IIVTNU: sistema **dual** post-STC 182/2021 + RDL 26/2021; no sujeción si no hay incremento [art. 104.5].
- [ ] Gastos suntuarios: solo cotos de caza y pesca [**DT 6.ª**].

## 4. Diagramas SVG

- [ ] Los 12 diagramas están presentes en `tema-8-diagramas.md`.
- [ ] Cada diagrama incluye `role="img"` y `aria-label` descriptivo.
- [ ] Paleta coherente: Ayto Madrid #0055a0 + #d13c3c + #2d8659 + #e89822.
- [ ] Ningún diagrama depende de CDN, fuentes externas ni scripts.
- [ ] Verificado por render del `index.html` real (los 12 SVG juntos): 0 textos fuera de caja (CSS scoped).

## 5. Banco de 150 preguntas

- [ ] Las 150 preguntas tienen 3 opciones y una única respuesta correcta verificable.
- [ ] La distribución A/B/C está equilibrada (~50/50/50) tras el balanceo automático.
- [ ] No hay preguntas ambiguas.
- [ ] La sección pedagógica de 20 preguntas incluye explicación y referencia.

## 6. Casos prácticos

- [ ] Los 6 casos mantienen escenario del Ayto de Madrid / IAM (gestión tributaria).
- [ ] Las cuestiones de cada caso suman 10 puntos.
- [ ] Cada caso tiene solución orientativa y criterios de evaluación.

## 7. Nivel y adecuación al C1

- [ ] Nivel de profundidad adecuado para C1.
- [ ] Se priorizan los datos numéricos memorísticos (porcentajes, límites, cuantías).

## 8. Entregables HTML

- [ ] `index.html` autosuficiente (offline), con pestañas y motor de test con penalización 1/3.
- [ ] Imprimible a PDF.
- [ ] Branding Ayuntamiento de Madrid (#0055a0).

## 9. Consistencia inter-temas

- [ ] Referencia cruzada al **Tema 1** (autonomía y suficiencia financiera, arts. 137/140/142 CE) coherente.
- [ ] Referencia a los **Temas 2-4** (Administración Local, municipios de gran población, Pleno/JGL) coherente.

---

## Observaciones generales

### Decisiones conscientes que conviene confirmar

1. **Eliminado el residuo del título**: el índice del cliente (`TEMA_08.docx`) arrastraba al final del título oficial la coletilla *"La Ley 39/2015 (LPACAP): recordatorio de contexto"*, ajena a las Haciendas Locales (es procedimiento administrativo común). Se ha **suprimido** por considerarse un residuo de plantilla. → Confirmar con Jesús/María que es correcto omitirla.
2. **Cifras fiscales auditadas contra BOE** (no tomadas literalmente del índice): se corrigió que el **IBI rústica** es 0,3–0,90 % (distinto de la urbana 0,4–1,10 %); que el límite del **90 %** de contribuciones especiales es del **art. 31** (los módulos, del **art. 32**); y se desarrolló el **sistema dual del IIVTNU** posterior a la STC 182/2021. → Confirmar el alcance de la actualización.
3. **IIVTNU**: se incluye el régimen vigente tras la reforma de 2021 (sistema objetivo/real y no sujeción por inexistencia de incremento). → Confirmar nivel de detalle deseado para C1.
4. **Madrid**: se añade la especialidad de la **Ley 22/2006 de Capitalidad** (Tribunal Económico-Administrativo Municipal + Agencia Tributaria Madrid). → Confirmar que interesa este enfoque.
5. **150 preguntas + 20 pedagógicas + 6 casos + 12 diagramas + 8 pestañas**, replicando el formato de los Temas 1-5.

### Puntos a vigilar (datos volátiles)

- Los **importes en euros del IVTM** (cuadro de tarifas, art. 95.1) y los **coeficientes del IIVTNU** se actualizan vía Leyes de Presupuestos: no se reproducen importes concretos, solo la estructura. Reverificar antes de cada convocatoria.
- Las **ordenanzas fiscales del Ayuntamiento de Madrid** fijan tipos concretos cada ejercicio: se citan solo a título de ejemplo.

---

## Decisión de cierre

- [ ] Aprobado sin cambios.
- [ ] Aprobado con cambios menores (listarlos).
- [ ] Requiere v2 (listar cambios sustanciales).

**Firmas**:

- María: _______________________________ Fecha: _____________
- Ana: _______________________________ Fecha: _____________
