# Tema 8 — Checklist de Validación

> **Título oficial**: RDLeg 2/2004 (TRLHL): Recursos de las Haciendas Locales. Clasificación: ingresos de derecho público y privado. Tasas, contribuciones especiales y precios públicos. Impuestos municipales: concepto y clasificación.
> **Versión**: 1.3 — Revisión jurídica
> **Fecha**: 2026-10-01
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
- [ ] Los conceptos memorizables aparecen en cajas **Dato clave**.
- [ ] Las reproducciones del articulado, incluida la Constitución, aparecen en cajas **Cita normativa**.
- [ ] Los ejemplos del Ayto de Madrid / IAM aparecen en cajas **Ejemplo de aplicación en el Ayto**.
- [ ] Fuera de las cajas, el texto se ciñe a lo que dice la norma.

## 3. Rigor jurídico (datos sensibles auditados)

- [ ] Fundamento constitucional: **arts. 137, 140 y 142 CE** (+ 133.2); NO el artículo 156 (que es de CCAA).
- [ ] Recursos del **art. 2.1**: patrimonio, tributos propios + recargos sobre impuestos de las CCAA o de otras entidades locales, participación Estado/CCAA, subvenciones, precios públicos, crédito, multas, demás prestaciones de derecho público.
- [ ] Ingresos de derecho privado (art. 3): patrimonio + herencias/legados/donaciones; su efectividad se sujeta a las **normas y procedimientos del derecho privado** (art. 4); nunca lo son los que procedan de bienes de dominio público local (art. 3.3).
- [ ] Tasas: cuantía por servicios **no excede del coste** [art. 24.2]; dominio público por el valor de mercado de la utilidad [art. 24.1]; ordenanza fiscal del Pleno; artículo 20.3 con letras a)-v) (Ley 9/2025).
- [ ] Contribuciones especiales: base **máx. 90 %** del coste soportado [**art. 31**]; módulos [**art. 32**].
- [ ] Precios públicos: **mínimo el coste** [art. 44]; proceden si no concurre ninguna circunstancia del artículo 20.1.B) [art. 41]; **no** figuran entre los tributos propios [art. 2.1]; Pleno, con delegación en la Comisión de Gobierno [art. 47.1].
- [ ] IBI: urbana **0,4–1,10 %**, rústica **0,3–0,90 %** [art. 72]; gestión **compartida** [art. 77].
- [ ] IAE: exención de las personas físicas y por cifra de negocios **< 1.000.000 €** [art. 82.1.c)]; exención en los dos primeros períodos impositivos de actividad [art. 82.1.b)].
- [ ] IVTM: coeficiente de incremento **máximo 2** [art. 95.4].
- [ ] ICIO: tipo **máximo 4 %** [art. 102.3]; potestativo.
- [ ] IIVTNU: base por coeficientes o por el incremento real si es inferior [art. 107.5], tras la STC 182/2021 + RDL 26/2021; no sujeción si no hay incremento [art. 104.5].
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
- [ ] Enunciado y respuesta salen del texto literal del precepto citado (o de una variación leve); los distractores son variaciones leves e inequívocamente falsas.
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

1. **Cifras fiscales auditadas contra el BOE**: el **IBI rústica** es 0,3–0,90 % (distinto de la urbana 0,4–1,10 %); el límite del **90 %** de contribuciones especiales es del **artículo 31** (los módulos, del **art. 32**); y se desarrolla la base del **IIVTNU** posterior a la STC 182/2021. → Confirmar el alcance de la actualización.
2. **IIVTNU**: se incluye el régimen vigente tras la reforma de 2021 (base por coeficientes o por el incremento real y no sujeción por inexistencia de incremento). → Confirmar nivel de detalle deseado para C1.
3. **Madrid**: se añade la especialidad de la **Ley 22/2006 de Capitalidad** (Tribunal Económico-Administrativo Municipal + Agencia Tributaria Madrid). → Confirmar que interesa este enfoque.
4. **150 preguntas + 20 pedagógicas + 6 casos + 12 diagramas + 8 pestañas**, replicando el formato de los Temas 1-5.

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
