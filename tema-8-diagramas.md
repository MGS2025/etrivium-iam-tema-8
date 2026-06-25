# Tema 8 — Catálogo de Diagramas

> **Título oficial**: RDLeg 2/2004 (TRLHL): Recursos de las Haciendas Locales, ingresos de derecho público y privado, tasas, contribuciones especiales, precios públicos e impuestos municipales.
>
> **Versión**: 1.0 — generación inicial
> **Fecha**: 2026-06-25
> **Formato**: SVG inline (zero-dependencias, escalable, imprimible)
> **Paleta**: Ayuntamiento de Madrid #0055a0 (primario) + #d13c3c (alertas) + #2d8659 (ventajas) + #e89822 (callouts)

---

## Índice de diagramas

| ID  | Título                                                  | Sección | Tipo |
|-----|---------------------------------------------------------|---------|------|
| D1  | El marco normativo de la Hacienda Local                | § 1     | Esquema |
| D2  | Los recursos de las Haciendas Locales (art. 2)         | § 2     | Árbol |
| D3  | Ingresos de derecho público vs. derecho privado        | § 3-4   | Comparativa |
| D4  | Las tasas: las dos modalidades del hecho imponible     | § 5     | Esquema |
| D5  | Tasa vs. precio público: árbol de decisión             | § 9     | Flujo |
| D6  | Contribuciones especiales: base, módulos y límite      | § 6     | Esquema |
| D7  | Precios públicos: requisitos y cuantía                 | § 7     | Esquema |
| D8  | Impuestos municipales: obligatorios vs. potestativos   | § 8     | Árbol |
| D9  | Impuestos obligatorios: IBI · IAE · IVTM               | § 8     | Comparativa |
| D10 | Impuestos potestativos: ICIO · IIVTNU · suntuarios     | § 8     | Comparativa |
| D11 | Especialidad del Ayuntamiento de Madrid                | § 10    | Esquema |
| D12 | Mapa-resumen del Tema 8                                 | § 11    | Mapa conceptual |

---

## D1 · El marco normativo de la Hacienda Local

**Sección**: § 1 — Introducción
**Propósito**: Situar el TRLHL bajo el fundamento constitucional y su relación con la LBRL.

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 700 330" role="img" aria-label="La Constitución (arts. 137, 140 y 142) garantiza la autonomía y la suficiencia financiera local; la LBRL remite a la legislación estatal; el TRLHL (RDLeg 2/2004) regula los recursos de las Haciendas Locales">
  <style>
    .h{font:700 14px system-ui,sans-serif;fill:#fff;text-anchor:middle}
    .t{font:13px system-ui,sans-serif;fill:#1a1a1a;text-anchor:middle}
    .s{font:11px system-ui,sans-serif;fill:#555;text-anchor:middle}
  </style>
  <rect x="170" y="18" width="360" height="58" rx="8" fill="#003d75"/>
  <text x="350" y="42" class="h">Constitución Española</text>
  <text x="350" y="62" class="h" style="font-weight:400;font-size:11px">arts. 137 y 140 (autonomía) · 142 (suficiencia financiera)</text>
  <line x1="350" y1="76" x2="350" y2="98" stroke="#0055a0" stroke-width="1.5"/>
  <rect x="120" y="98" width="200" height="58" rx="8" fill="#e8f0f8" stroke="#0055a0"/>
  <text x="220" y="122" class="t" style="font-weight:700">LBRL (Ley 7/1985)</text>
  <text x="220" y="142" class="s">remite a la legislación estatal</text>
  <rect x="380" y="98" width="200" height="58" rx="8" fill="#e8f0f8" stroke="#0055a0"/>
  <text x="480" y="122" class="t" style="font-weight:700">art. 133.2 CE</text>
  <text x="480" y="142" class="s">potestad tributaria conforme a ley</text>
  <line x1="350" y1="156" x2="350" y2="180" stroke="#0055a0" stroke-width="1.5"/>
  <rect x="180" y="180" width="340" height="60" rx="8" fill="#e8f5ee" stroke="#2d8659"/>
  <text x="350" y="205" class="t" style="font-weight:700">TRLHL · RDLeg 2/2004, de 5 de marzo</text>
  <text x="350" y="225" class="s">refunde la Ley 39/1988 · regula los recursos locales</text>
  <rect x="160" y="262" width="380" height="52" rx="8" fill="#fff5e6" stroke="#e89822"/>
  <text x="350" y="284" class="s" style="font-weight:700;fill:#b5740f">Principio rector: suficiencia financiera (art. 142 CE)</text>
  <text x="350" y="302" class="s">los recursos deben bastar para las competencias locales</text>
</svg>
```

---

## D2 · Los recursos de las Haciendas Locales (art. 2)

**Sección**: § 2 — Recursos
**Propósito**: Enumerar los ocho recursos del art. 2.1 TRLHL.

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 720 360" role="img" aria-label="El artículo 2.1 del TRLHL enumera ocho recursos: patrimonio, tributos propios y recargos, participación en tributos del Estado y CCAA, subvenciones, precios públicos, crédito, multas y sanciones, y demás prestaciones de derecho público">
  <style>
    .h{font:700 13px system-ui,sans-serif;fill:#fff;text-anchor:middle}
    .t{font:12px system-ui,sans-serif;fill:#1a1a1a;text-anchor:middle}
    .s{font:10.5px system-ui,sans-serif;fill:#555;text-anchor:middle}
  </style>
  <rect x="240" y="16" width="240" height="48" rx="8" fill="#003d75"/>
  <text x="360" y="37" class="h">RECURSOS (art. 2.1 TRLHL)</text>
  <text x="360" y="54" class="h" style="font-weight:400;font-size:10.5px">ocho categorías</text>
  <rect x="20" y="90" width="160" height="64" rx="8" fill="#fdeaea" stroke="#d13c3c"/>
  <text x="100" y="114" class="t" style="font-weight:700">a) Patrimonio</text>
  <text x="100" y="134" class="s">y demás de derecho privado</text>
  <rect x="200" y="90" width="180" height="64" rx="8" fill="#e8f5ee" stroke="#2d8659"/>
  <text x="290" y="110" class="t" style="font-weight:700">b) Tributos propios</text>
  <text x="290" y="128" class="s">tasas · contrib. especiales ·</text>
  <text x="290" y="144" class="s">impuestos (+ recargos)</text>
  <rect x="400" y="90" width="180" height="64" rx="8" fill="#e8f0f8" stroke="#0055a0"/>
  <text x="490" y="114" class="t" style="font-weight:700">c) Participación</text>
  <text x="490" y="134" class="s">tributos del Estado y CCAA</text>
  <rect x="600" y="90" width="100" height="64" rx="8" fill="#e8f0f8" stroke="#0055a0"/>
  <text x="650" y="114" class="t" style="font-weight:700">d) Subven-</text>
  <text x="650" y="132" class="t" style="font-weight:700">ciones</text>
  <rect x="20" y="172" width="160" height="64" rx="8" fill="#e8f5ee" stroke="#2d8659"/>
  <text x="100" y="196" class="t" style="font-weight:700">e) Precios</text>
  <text x="100" y="214" class="t" style="font-weight:700">públicos</text>
  <rect x="200" y="172" width="180" height="64" rx="8" fill="#e8f0f8" stroke="#0055a0"/>
  <text x="290" y="196" class="t" style="font-weight:700">f) Operaciones</text>
  <text x="290" y="214" class="t" style="font-weight:700">de crédito</text>
  <rect x="400" y="172" width="180" height="64" rx="8" fill="#e8f0f8" stroke="#0055a0"/>
  <text x="490" y="196" class="t" style="font-weight:700">g) Multas y</text>
  <text x="490" y="214" class="t" style="font-weight:700">sanciones</text>
  <rect x="600" y="172" width="100" height="64" rx="8" fill="#e8f0f8" stroke="#0055a0"/>
  <text x="650" y="196" class="t" style="font-weight:700">h) Demás</text>
  <text x="650" y="214" class="s">prest. dcho. público</text>
  <rect x="120" y="270" width="480" height="70" rx="8" fill="#fff5e6" stroke="#e89822"/>
  <text x="360" y="296" class="t" style="font-weight:700;fill:#b5740f">Tributos propios = TASAS + CONTRIBUCIONES ESPECIALES + IMPUESTOS</text>
  <text x="360" y="320" class="s">el resto son recursos no tributarios (salvo recargos)</text>
</svg>
```

---

## D3 · Ingresos de derecho público vs. derecho privado

**Sección**: § 3-4 — Clasificación nuclear
**Propósito**: Contrastar régimen, clases y cobro de ambas categorías.

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 720 350" role="img" aria-label="Los ingresos de derecho público gozan de prerrogativas de autotutela y apremio; los de derecho privado se rigen por el Derecho privado y no tienen prerrogativas, pero su cobro impagado también va por apremio">
  <style>
    .h{font:700 13px system-ui,sans-serif;fill:#fff;text-anchor:middle}
    .t{font:12px system-ui,sans-serif;fill:#1a1a1a;text-anchor:middle}
    .s{font:10.5px system-ui,sans-serif;fill:#444;text-anchor:start}
  </style>
  <rect x="30" y="20" width="310" height="44" rx="8" fill="#0055a0"/>
  <text x="185" y="47" class="h">INGRESOS DE DERECHO PÚBLICO</text>
  <rect x="380" y="20" width="310" height="44" rx="8" fill="#7a5230"/>
  <text x="535" y="47" class="h">INGRESOS DE DERECHO PRIVADO</text>
  <rect x="30" y="78" width="310" height="180" rx="8" fill="#e8f0f8" stroke="#0055a0"/>
  <text x="48" y="104" class="s" style="font-weight:700;fill:#0055a0">Régimen: Derecho Admvo./Tributario</text>
  <text x="48" y="128" class="s">• Autotutela y ejecutividad</text>
  <text x="48" y="150" class="s">• Cobro por procedimiento de apremio</text>
  <text x="48" y="172" class="s">• Clases: tributos (impuestos, tasas,</text>
  <text x="58" y="190" class="s">contrib. especiales), recargos,</text>
  <text x="58" y="208" class="s">participaciones, subvenciones,</text>
  <text x="58" y="226" class="s">multas, precios públicos</text>
  <text x="48" y="248" class="s" style="fill:#0055a0">art. 2.2 TRLHL</text>
  <rect x="380" y="78" width="310" height="180" rx="8" fill="#f3ece4" stroke="#7a5230"/>
  <text x="398" y="104" class="s" style="font-weight:700;fill:#7a5230">Régimen: Derecho privado (civil/mercantil)</text>
  <text x="398" y="128" class="s">• NO gozan de prerrogativas</text>
  <text x="398" y="150" class="s">• Clases: rendimientos del patrimonio;</text>
  <text x="408" y="168" class="s">herencias, legados y donaciones</text>
  <text x="398" y="192" class="s">• Excluye dominio público y comunales</text>
  <text x="398" y="216" class="s" style="font-weight:700;fill:#d13c3c">• PERO el cobro impagado también</text>
  <text x="408" y="234" class="s" style="font-weight:700;fill:#d13c3c">va por apremio (art. 2.2)</text>
  <text x="398" y="252" class="s" style="fill:#7a5230">art. 3 TRLHL</text>
  <rect x="120" y="278" width="480" height="56" rx="8" fill="#fff5e6" stroke="#e89822"/>
  <text x="360" y="302" class="t" style="font-weight:700;fill:#b5740f">Diferencia decisiva: las PRERROGATIVAS de cobro</text>
  <text x="360" y="322" class="s">el negocio privado no las tiene, pero su impago sí se apremia</text>
</svg>
```

---

## D4 · Las tasas: las dos modalidades del hecho imponible

**Sección**: § 5 — Tasas
**Propósito**: Distinguir las dos modalidades del art. 20 y la regla de cuantía.

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 720 330" role="img" aria-label="El hecho imponible de la tasa tiene dos modalidades: utilización privativa del dominio público local, y prestación de servicios coactivos; la cuantía por servicios no puede exceder del coste">
  <style>
    .h{font:700 13px system-ui,sans-serif;fill:#fff;text-anchor:middle}
    .t{font:12px system-ui,sans-serif;fill:#1a1a1a;text-anchor:middle}
    .s{font:10.5px system-ui,sans-serif;fill:#555;text-anchor:middle}
  </style>
  <rect x="250" y="16" width="220" height="46" rx="8" fill="#003d75"/>
  <text x="360" y="37" class="h">TASA — hecho imponible</text>
  <text x="360" y="54" class="h" style="font-weight:400;font-size:10.5px">art. 20 TRLHL</text>
  <line x1="360" y1="62" x2="360" y2="78" stroke="#0055a0"/>
  <line x1="180" y1="78" x2="540" y2="78" stroke="#0055a0"/>
  <line x1="180" y1="78" x2="180" y2="94" stroke="#0055a0"/>
  <line x1="540" y1="78" x2="540" y2="94" stroke="#0055a0"/>
  <rect x="40" y="94" width="280" height="110" rx="8" fill="#e8f0f8" stroke="#0055a0"/>
  <text x="180" y="118" class="t" style="font-weight:700">1) Dominio público local</text>
  <text x="180" y="140" class="s">utilización privativa o</text>
  <text x="180" y="158" class="s">aprovechamiento especial</text>
  <text x="180" y="182" class="s">(vados, terrazas, ocupación</text>
  <text x="180" y="198" class="s">de la vía pública…)</text>
  <rect x="400" y="94" width="280" height="110" rx="8" fill="#e8f5ee" stroke="#2d8659"/>
  <text x="540" y="118" class="t" style="font-weight:700">2) Servicios/actividades</text>
  <text x="540" y="140" class="s">en régimen de derecho público</text>
  <text x="540" y="162" class="s" style="font-weight:700;fill:#2d8659">si NO son voluntarios O</text>
  <text x="540" y="180" class="s" style="font-weight:700;fill:#2d8659">NO los presta el sector privado</text>
  <text x="540" y="198" class="s">(coactividad)</text>
  <rect x="130" y="232" width="460" height="80" rx="8" fill="#fff5e6" stroke="#e89822"/>
  <text x="360" y="258" class="t" style="font-weight:700;fill:#b5740f">Cuantía (art. 24)</text>
  <text x="360" y="280" class="s">dominio público → valor de mercado / utilidad (24.1)</text>
  <text x="360" y="300" class="s" style="font-weight:700">servicios → NO excede del coste real o previsible (24.2)</text>
</svg>
```

---

## D5 · Tasa vs. precio público: árbol de decisión

**Sección**: § 9 — Distinción de figuras
**Propósito**: Resolver por descarte si una prestación es tasa o precio público.

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 720 350" role="img" aria-label="Árbol de decisión: si el servicio es voluntario y además lo presta el sector privado, es precio público; si falta cualquiera de las dos condiciones, es tasa">
  <style>
    .h{font:700 13px system-ui,sans-serif;fill:#fff;text-anchor:middle}
    .t{font:12px system-ui,sans-serif;fill:#1a1a1a;text-anchor:middle}
    .s{font:10.5px system-ui,sans-serif;fill:#555;text-anchor:middle}
    .d{font:700 11px system-ui,sans-serif;fill:#0055a0;text-anchor:middle}
  </style>
  <rect x="230" y="16" width="260" height="50" rx="8" fill="#003d75"/>
  <text x="360" y="38" class="h">¿Servicio de competencia local?</text>
  <text x="360" y="57" class="h" style="font-weight:400;font-size:10.5px">prestación pecuniaria a decidir</text>
  <line x1="360" y1="66" x2="360" y2="86" stroke="#0055a0"/>
  <rect x="210" y="86" width="300" height="46" rx="8" fill="#e8f0f8" stroke="#0055a0"/>
  <text x="360" y="106" class="t" style="font-weight:700">¿Es de solicitud/recepción VOLUNTARIA?</text>
  <text x="360" y="124" class="s">y además, ¿lo presta también el sector privado?</text>
  <line x1="360" y1="132" x2="360" y2="150" stroke="#0055a0"/>
  <line x1="200" y1="150" x2="520" y2="150" stroke="#0055a0"/>
  <line x1="200" y1="150" x2="200" y2="168" stroke="#2d8659"/>
  <line x1="520" y1="150" x2="520" y2="168" stroke="#d13c3c"/>
  <text x="200" y="164" class="d" style="fill:#2d8659">SÍ a las dos</text>
  <text x="520" y="164" class="d" style="fill:#d13c3c">NO a alguna</text>
  <rect x="70" y="168" width="260" height="92" rx="8" fill="#e8f5ee" stroke="#2d8659"/>
  <text x="200" y="194" class="t" style="font-weight:700;fill:#2d8659">PRECIO PÚBLICO</text>
  <text x="200" y="216" class="s">no es tributo · art. 41</text>
  <text x="200" y="236" class="s">cuantía: MÍNIMO el coste (44)</text>
  <text x="200" y="254" class="s">lo fija el Pleno (delegable JGL)</text>
  <rect x="390" y="168" width="260" height="92" rx="8" fill="#fdeaea" stroke="#d13c3c"/>
  <text x="520" y="194" class="t" style="font-weight:700;fill:#d13c3c">TASA</text>
  <text x="520" y="216" class="s">es tributo · arts. 20-27</text>
  <text x="520" y="236" class="s">cuantía: MÁXIMO el coste (24.2)</text>
  <text x="520" y="254" class="s">ordenanza fiscal del Pleno</text>
  <rect x="150" y="286" width="420" height="50" rx="8" fill="#fff5e6" stroke="#e89822"/>
  <text x="360" y="308" class="t" style="font-weight:700;fill:#b5740f">Regla espejo: precio público = suelo · tasa = techo</text>
  <text x="360" y="327" class="s">ambos se cobran por apremio (son ingresos de derecho público)</text>
</svg>
```

---

## D6 · Contribuciones especiales: base, módulos y límite

**Sección**: § 6 — Contribuciones especiales
**Propósito**: Fijar el hecho imponible, el límite del 90 % (art. 31) y los módulos (art. 32).

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 720 330" role="img" aria-label="La contribución especial grava el beneficio especial por obras o servicios; la base imponible es como máximo el 90 por ciento del coste soportado (art. 31) y se reparte por módulos del art. 32">
  <style>
    .h{font:700 13px system-ui,sans-serif;fill:#fff;text-anchor:middle}
    .t{font:12px system-ui,sans-serif;fill:#1a1a1a;text-anchor:middle}
    .s{font:10.5px system-ui,sans-serif;fill:#555;text-anchor:middle}
  </style>
  <rect x="190" y="16" width="340" height="48" rx="8" fill="#003d75"/>
  <text x="360" y="38" class="h">CONTRIBUCIÓN ESPECIAL (arts. 28-37)</text>
  <text x="360" y="55" class="h" style="font-weight:400;font-size:10.5px">beneficio especial por obra o servicio local</text>
  <rect x="40" y="86" width="300" height="74" rx="8" fill="#e8f0f8" stroke="#0055a0"/>
  <text x="190" y="110" class="t" style="font-weight:700">Hecho imponible (art. 28)</text>
  <text x="190" y="132" class="s">obtención de un beneficio o aumento</text>
  <text x="190" y="150" class="s">de valor de los bienes del sujeto pasivo</text>
  <rect x="380" y="86" width="300" height="74" rx="8" fill="#e8f5ee" stroke="#2d8659"/>
  <text x="530" y="110" class="t" style="font-weight:700">Sujetos pasivos (art. 30)</text>
  <text x="530" y="132" class="s">los especialmente beneficiados</text>
  <text x="530" y="150" class="s">(propietarios, titulares, aseguradoras)</text>
  <rect x="40" y="176" width="300" height="76" rx="8" fill="#fdeaea" stroke="#d13c3c"/>
  <text x="190" y="200" class="t" style="font-weight:700;fill:#d13c3c">Base imponible — art. 31</text>
  <text x="190" y="222" class="s" style="font-weight:700">MÁXIMO el 90 % del coste soportado</text>
  <text x="190" y="242" class="s">(coste total − subvenciones, art. 31.2)</text>
  <rect x="380" y="176" width="300" height="76" rx="8" fill="#e8f0f8" stroke="#0055a0"/>
  <text x="530" y="200" class="t" style="font-weight:700">Módulos de reparto — art. 32</text>
  <text x="530" y="222" class="s">metros de fachada · superficie ·</text>
  <text x="530" y="242" class="s">volumen edificable · valor catastral</text>
  <rect x="140" y="268" width="440" height="48" rx="8" fill="#fff5e6" stroke="#e89822"/>
  <text x="360" y="290" class="t" style="font-weight:700;fill:#b5740f">¡No confundir! 90 % = art. 31 · módulos = art. 32</text>
  <text x="360" y="309" class="s">posibilidad de anticipar el pago (art. 33.2)</text>
</svg>
```

---

## D7 · Precios públicos: requisitos y cuantía

**Sección**: § 7 — Precios públicos
**Propósito**: Fijar las dos condiciones, la naturaleza no tributaria y la regla de cuantía.

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 720 320" role="img" aria-label="El precio público exige solicitud voluntaria y concurrencia del sector privado, no tiene naturaleza tributaria, debe cubrir como mínimo el coste y lo fija el Pleno con posible delegación en la Junta de Gobierno Local">
  <style>
    .h{font:700 13px system-ui,sans-serif;fill:#fff;text-anchor:middle}
    .t{font:12px system-ui,sans-serif;fill:#1a1a1a;text-anchor:middle}
    .s{font:10.5px system-ui,sans-serif;fill:#555;text-anchor:middle}
  </style>
  <rect x="220" y="16" width="280" height="48" rx="8" fill="#003d75"/>
  <text x="360" y="38" class="h">PRECIO PÚBLICO (arts. 41-47)</text>
  <text x="360" y="55" class="h" style="font-weight:400;font-size:10.5px">NO tiene naturaleza tributaria (art. 41)</text>
  <rect x="60" y="86" width="280" height="66" rx="8" fill="#e8f5ee" stroke="#2d8659"/>
  <text x="200" y="110" class="t" style="font-weight:700">Condición 1</text>
  <text x="200" y="132" class="s">solicitud o recepción VOLUNTARIA</text>
  <rect x="380" y="86" width="280" height="66" rx="8" fill="#e8f5ee" stroke="#2d8659"/>
  <text x="520" y="110" class="t" style="font-weight:700">Condición 2</text>
  <text x="520" y="132" class="s">prestado TAMBIÉN por el sector privado</text>
  <rect x="120" y="168" width="480" height="36" rx="8" fill="#eef3f8" stroke="#0055a0"/>
  <text x="360" y="191" class="s" style="font-weight:700;fill:#0055a0">deben concurrir LAS DOS · si falta una → es TASA</text>
  <rect x="60" y="220" width="280" height="80" rx="8" fill="#fdeaea" stroke="#d13c3c"/>
  <text x="200" y="244" class="t" style="font-weight:700;fill:#d13c3c">Cuantía (art. 44)</text>
  <text x="200" y="266" class="s" style="font-weight:700">MÍNIMO: cubrir el coste</text>
  <text x="200" y="286" class="s">excepción social → por debajo,</text>
  <rect x="380" y="220" width="280" height="80" rx="8" fill="#fff5e6" stroke="#e89822"/>
  <text x="520" y="244" class="t" style="font-weight:700;fill:#b5740f">Establecimiento (art. 47)</text>
  <text x="520" y="266" class="s">lo fija el PLENO</text>
  <text x="520" y="286" class="s">delegable en la Junta de Gobierno Local</text>
</svg>
```

---

## D8 · Impuestos municipales: obligatorios vs. potestativos

**Sección**: § 8 — Impuestos municipales
**Propósito**: Clasificar los seis impuestos según el art. 59.

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 720 330" role="img" aria-label="Los impuestos municipales se dividen en obligatorios (IBI, IAE, IVTM) y potestativos (ICIO, IIVTNU, gastos suntuarios)">
  <style>
    .h{font:700 13px system-ui,sans-serif;fill:#fff;text-anchor:middle}
    .t{font:12px system-ui,sans-serif;fill:#1a1a1a;text-anchor:middle}
    .s{font:10.5px system-ui,sans-serif;fill:#555;text-anchor:middle}
  </style>
  <rect x="250" y="16" width="220" height="48" rx="8" fill="#003d75"/>
  <text x="360" y="38" class="h">IMPUESTOS MUNICIPALES</text>
  <text x="360" y="55" class="h" style="font-weight:400;font-size:10.5px">art. 59 TRLHL</text>
  <line x1="360" y1="64" x2="360" y2="80" stroke="#0055a0"/>
  <line x1="190" y1="80" x2="530" y2="80" stroke="#0055a0"/>
  <line x1="190" y1="80" x2="190" y2="96" stroke="#0055a0"/>
  <line x1="530" y1="80" x2="530" y2="96" stroke="#0055a0"/>
  <rect x="40" y="96" width="300" height="40" rx="8" fill="#2d8659"/>
  <text x="190" y="121" class="h">OBLIGATORIOS (art. 59.1)</text>
  <rect x="380" y="96" width="300" height="40" rx="8" fill="#e89822"/>
  <text x="530" y="121" class="h">POTESTATIVOS (art. 59.2)</text>
  <rect x="40" y="148" width="300" height="44" rx="8" fill="#e8f5ee" stroke="#2d8659"/>
  <text x="190" y="175" class="t" style="font-weight:700">IBI · Bienes Inmuebles (60-77)</text>
  <rect x="40" y="200" width="300" height="44" rx="8" fill="#e8f5ee" stroke="#2d8659"/>
  <text x="190" y="227" class="t" style="font-weight:700">IAE · Actividades Económicas (78-91)</text>
  <rect x="40" y="252" width="300" height="44" rx="8" fill="#e8f5ee" stroke="#2d8659"/>
  <text x="190" y="279" class="t" style="font-weight:700">IVTM · Vehículos (92-99)</text>
  <rect x="380" y="148" width="300" height="44" rx="8" fill="#fff5e6" stroke="#e89822"/>
  <text x="530" y="175" class="t" style="font-weight:700">ICIO · Construcciones (100-103)</text>
  <rect x="380" y="200" width="300" height="44" rx="8" fill="#fff5e6" stroke="#e89822"/>
  <text x="530" y="227" class="t" style="font-weight:700">IIVTNU · Plusvalía (104-110)</text>
  <rect x="380" y="252" width="300" height="44" rx="8" fill="#fff5e6" stroke="#e89822"/>
  <text x="530" y="273" class="t" style="font-weight:700">Gastos Suntuarios</text>
  <text x="530" y="289" class="s">cotos de caza y pesca (DT 6.ª)</text>
</svg>
```

---

## D9 · Impuestos obligatorios: IBI · IAE · IVTM

**Sección**: § 8 — Impuestos obligatorios
**Propósito**: Ficha de los tres impuestos de exacción obligatoria y sus cifras clave.

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 720 320" role="img" aria-label="IBI grava la titularidad de inmuebles con tipos 0,4 a 1,10 por ciento urbana y 0,3 a 0,90 rústica; IAE grava la actividad económica con exención por debajo de un millón de euros; IVTM grava los vehículos con coeficiente máximo 2">
  <style>
    .h{font:700 13px system-ui,sans-serif;fill:#fff;text-anchor:middle}
    .t{font:12px system-ui,sans-serif;fill:#1a1a1a;text-anchor:middle}
    .s{font:10px system-ui,sans-serif;fill:#555;text-anchor:middle}
  </style>
  <rect x="200" y="14" width="320" height="40" rx="8" fill="#2d8659"/>
  <text x="360" y="39" class="h">IMPUESTOS OBLIGATORIOS</text>
  <rect x="20" y="70" width="220" height="226" rx="8" fill="#e8f5ee" stroke="#2d8659"/>
  <text x="130" y="96" class="t" style="font-weight:700;fill:#2d8659">IBI (60-77)</text>
  <text x="130" y="120" class="s">titularidad de derechos</text>
  <text x="130" y="136" class="s">reales sobre inmuebles</text>
  <text x="130" y="162" class="s" style="font-weight:700">urbana 0,4 % – 1,10 %</text>
  <text x="130" y="182" class="s" style="font-weight:700">rústica 0,3 % – 0,90 %</text>
  <text x="130" y="206" class="s">gestión COMPARTIDA:</text>
  <text x="130" y="222" class="s">catastral (Estado) +</text>
  <text x="130" y="238" class="s">tributaria (ayuntamiento)</text>
  <text x="130" y="266" class="s" style="fill:#2d8659">art. 72 y 77</text>
  <rect x="250" y="70" width="220" height="226" rx="8" fill="#e8f5ee" stroke="#2d8659"/>
  <text x="360" y="96" class="t" style="font-weight:700;fill:#2d8659">IAE (78-91)</text>
  <text x="360" y="120" class="s">ejercicio de actividad</text>
  <text x="360" y="136" class="s">empresarial/profesional/</text>
  <text x="360" y="152" class="s">artística</text>
  <text x="360" y="180" class="s" style="font-weight:700">EXENTOS:</text>
  <text x="360" y="200" class="s">• personas físicas</text>
  <text x="360" y="218" class="s">• 2 primeros años</text>
  <text x="360" y="236" class="s" style="font-weight:700">• cifra neg. &lt; 1.000.000 €</text>
  <text x="360" y="266" class="s" style="fill:#2d8659">art. 82</text>
  <rect x="480" y="70" width="220" height="226" rx="8" fill="#e8f5ee" stroke="#2d8659"/>
  <text x="590" y="96" class="t" style="font-weight:700;fill:#2d8659">IVTM (92-99)</text>
  <text x="590" y="120" class="s">titularidad de vehículos</text>
  <text x="590" y="136" class="s">aptos para circular</text>
  <text x="590" y="164" class="s">cuota por TARIFA</text>
  <text x="590" y="182" class="s">según clase y potencia</text>
  <text x="590" y="210" class="s" style="font-weight:700">coeficiente municipal</text>
  <text x="590" y="228" class="s" style="font-weight:700">máximo = 2</text>
  <text x="590" y="266" class="s" style="fill:#2d8659">art. 95</text>
</svg>
```

---

## D10 · Impuestos potestativos: ICIO · IIVTNU · suntuarios

**Sección**: § 8 — Impuestos potestativos
**Propósito**: Ficha de los impuestos potestativos, con la reforma dual del IIVTNU.

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 720 320" role="img" aria-label="ICIO grava obras con licencia, tipo máximo 4 por ciento; IIVTNU grava la plusvalía del suelo urbano con sistema dual tras la STC 182/2021; el impuesto sobre gastos suntuarios solo subsiste para cotos de caza y pesca">
  <style>
    .h{font:700 13px system-ui,sans-serif;fill:#fff;text-anchor:middle}
    .t{font:12px system-ui,sans-serif;fill:#1a1a1a;text-anchor:middle}
    .s{font:10px system-ui,sans-serif;fill:#555;text-anchor:middle}
  </style>
  <rect x="200" y="14" width="320" height="40" rx="8" fill="#e89822"/>
  <text x="360" y="39" class="h">IMPUESTOS POTESTATIVOS</text>
  <rect x="20" y="70" width="220" height="226" rx="8" fill="#fff5e6" stroke="#e89822"/>
  <text x="130" y="96" class="t" style="font-weight:700;fill:#b5740f">ICIO (100-103)</text>
  <text x="130" y="122" class="s">construcciones, instalaciones</text>
  <text x="130" y="138" class="s">u obras con licencia</text>
  <text x="130" y="166" class="s">base = coste real y</text>
  <text x="130" y="182" class="s">efectivo de la obra</text>
  <text x="130" y="212" class="s" style="font-weight:700">tipo MÁXIMO 4 %</text>
  <text x="130" y="266" class="s" style="fill:#b5740f">art. 102.3</text>
  <rect x="250" y="70" width="220" height="226" rx="8" fill="#fff5e6" stroke="#e89822"/>
  <text x="360" y="96" class="t" style="font-weight:700;fill:#b5740f">IIVTNU (104-110)</text>
  <text x="360" y="120" class="s">plusvalía del suelo urbano</text>
  <text x="360" y="136" class="s">en transmisiones</text>
  <text x="360" y="162" class="s" style="font-weight:700;fill:#d13c3c">tras STC 182/2021 +</text>
  <text x="360" y="180" class="s" style="font-weight:700;fill:#d13c3c">RDL 26/2021:</text>
  <text x="360" y="200" class="s">sistema DUAL (objetivo/real)</text>
  <text x="360" y="218" class="s">a elección del contribuyente</text>
  <text x="360" y="238" class="s">no sujeción si no hay incremento</text>
  <text x="360" y="266" class="s" style="fill:#b5740f">art. 104.5 y 107</text>
  <rect x="480" y="70" width="220" height="226" rx="8" fill="#fff5e6" stroke="#e89822"/>
  <text x="590" y="96" class="t" style="font-weight:700;fill:#b5740f">Gastos Suntuarios</text>
  <text x="590" y="124" class="s">solo subsiste la modalidad</text>
  <text x="590" y="142" class="s" style="font-weight:700">de cotos de caza y pesca</text>
  <text x="590" y="172" class="s">prácticamente en desuso</text>
  <text x="590" y="204" class="s">base legal:</text>
  <text x="590" y="222" class="s" style="font-weight:700">Disposición Transitoria 6.ª</text>
  <text x="590" y="266" class="s" style="fill:#b5740f">DT 6.ª TRLHL</text>
</svg>
```

---

## D11 · Especialidad del Ayuntamiento de Madrid

**Sección**: § 10 — Especialidad Madrid
**Propósito**: Situar la Ley 22/2006 y sus dos instituciones tributarias propias.

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 700 300" role="img" aria-label="La Ley 22/2006 de Capitalidad y Régimen Especial de Madrid crea el Tribunal Económico-Administrativo Municipal y habilita la Agencia Tributaria Madrid; en lo no previsto se aplica el TRLHL">
  <style>
    .h{font:700 14px system-ui,sans-serif;fill:#fff;text-anchor:middle}
    .t{font:12px system-ui,sans-serif;fill:#1a1a1a;text-anchor:middle}
    .s{font:10.5px system-ui,sans-serif;fill:#555;text-anchor:middle}
  </style>
  <rect x="150" y="18" width="400" height="56" rx="8" fill="#003d75"/>
  <text x="350" y="42" class="h">Ley 22/2006 de Capitalidad</text>
  <text x="350" y="62" class="h" style="font-weight:400;font-size:11px">y de Régimen Especial de Madrid (LCREM)</text>
  <line x1="350" y1="74" x2="350" y2="92" stroke="#0055a0"/>
  <line x1="190" y1="92" x2="510" y2="92" stroke="#0055a0"/>
  <line x1="190" y1="92" x2="190" y2="108" stroke="#0055a0"/>
  <line x1="510" y1="92" x2="510" y2="108" stroke="#0055a0"/>
  <rect x="50" y="108" width="280" height="92" rx="8" fill="#e8f0f8" stroke="#0055a0"/>
  <text x="190" y="134" class="t" style="font-weight:700">Tribunal Económico-</text>
  <text x="190" y="152" class="t" style="font-weight:700">Administrativo Municipal</text>
  <text x="190" y="174" class="s">resuelve reclamaciones</text>
  <text x="190" y="190" class="s">económico-administrativas (art. 25)</text>
  <rect x="370" y="108" width="280" height="92" rx="8" fill="#e8f5ee" stroke="#2d8659"/>
  <text x="510" y="134" class="t" style="font-weight:700">Agencia Tributaria Madrid</text>
  <text x="510" y="156" class="s">órgano de gestión tributaria</text>
  <text x="510" y="174" class="s">integral de los tributos</text>
  <text x="510" y="190" class="s">municipales (art. 26)</text>
  <rect x="130" y="224" width="440" height="60" rx="8" fill="#fff5e6" stroke="#e89822"/>
  <text x="350" y="248" class="t" style="font-weight:700;fill:#b5740f">Madrid = municipio de gran población (Título X LBRL)</text>
  <text x="350" y="270" class="s">en lo no previsto por la LCREM se aplica el TRLHL</text>
</svg>
```

---

## D12 · Mapa-resumen del Tema 8

**Sección**: § 11 — Esquema resumen
**Propósito**: Visión global del tema en un solo golpe de vista.

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 760 380" role="img" aria-label="Mapa resumen: el TRLHL clasifica los recursos en ingresos de derecho público y privado; los tributos propios son tasas, contribuciones especiales e impuestos; los precios públicos no son tributo; los impuestos se dividen en obligatorios y potestativos">
  <style>
    .h{font:700 13px system-ui,sans-serif;fill:#fff;text-anchor:middle}
    .t{font:11.5px system-ui,sans-serif;fill:#1a1a1a;text-anchor:middle}
    .s{font:10px system-ui,sans-serif;fill:#555;text-anchor:middle}
  </style>
  <rect x="270" y="14" width="220" height="44" rx="8" fill="#003d75"/>
  <text x="380" y="34" class="h">TRLHL (RDLeg 2/2004)</text>
  <text x="380" y="50" class="h" style="font-weight:400;font-size:10px">recursos de las Haciendas Locales</text>
  <line x1="380" y1="58" x2="380" y2="74" stroke="#0055a0"/>
  <line x1="200" y1="74" x2="560" y2="74" stroke="#0055a0"/>
  <line x1="200" y1="74" x2="200" y2="88" stroke="#0055a0"/>
  <line x1="560" y1="74" x2="560" y2="88" stroke="#0055a0"/>
  <rect x="70" y="88" width="260" height="34" rx="7" fill="#0055a0"/>
  <text x="200" y="110" class="h">INGRESOS DE DERECHO PÚBLICO</text>
  <rect x="430" y="88" width="260" height="34" rx="7" fill="#7a5230"/>
  <text x="560" y="110" class="h">DERECHO PRIVADO</text>
  <rect x="430" y="132" width="260" height="50" rx="7" fill="#f3ece4" stroke="#7a5230"/>
  <text x="560" y="153" class="t" style="font-weight:700">Patrimonio · herencias</text>
  <text x="560" y="171" class="s">no prerrogativas (pero apremio si impago)</text>
  <rect x="40" y="132" width="150" height="50" rx="7" fill="#e8f5ee" stroke="#2d8659"/>
  <text x="115" y="153" class="t" style="font-weight:700">Tasas</text>
  <text x="115" y="171" class="s">coste = máx (24.2)</text>
  <rect x="200" y="132" width="160" height="50" rx="7" fill="#e8f5ee" stroke="#2d8659"/>
  <text x="280" y="150" class="t" style="font-weight:700">Contrib. especiales</text>
  <text x="280" y="170" class="s">máx 90 % (art. 31)</text>
  <rect x="370" y="132" width="40" height="50" rx="7" fill="#eef3f8" stroke="#0055a0"/>
  <text x="390" y="150" class="s" style="font-weight:700">+</text>
  <text x="390" y="168" class="s">PP</text>
  <rect x="40" y="194" width="370" height="34" rx="7" fill="#003d75"/>
  <text x="225" y="216" class="h">IMPUESTOS (tributos propios)</text>
  <rect x="40" y="238" width="180" height="120" rx="7" fill="#e8f5ee" stroke="#2d8659"/>
  <text x="130" y="260" class="t" style="font-weight:700;fill:#2d8659">Obligatorios</text>
  <text x="130" y="284" class="s">IBI (0,4–1,10 / 0,3–0,90)</text>
  <text x="130" y="306" class="s">IAE (exención &lt; 1 M €)</text>
  <text x="130" y="328" class="s">IVTM (coef. máx. 2)</text>
  <text x="130" y="350" class="s" style="fill:#2d8659">art. 59.1</text>
  <rect x="230" y="238" width="180" height="120" rx="7" fill="#fff5e6" stroke="#e89822"/>
  <text x="320" y="260" class="t" style="font-weight:700;fill:#b5740f">Potestativos</text>
  <text x="320" y="284" class="s">ICIO (máx. 4 %)</text>
  <text x="320" y="306" class="s">IIVTNU (dual, post-STC)</text>
  <text x="320" y="328" class="s">G. suntuarios (cotos)</text>
  <text x="320" y="350" class="s" style="fill:#b5740f">art. 59.2</text>
  <rect x="430" y="194" width="260" height="164" rx="7" fill="#fff5e6" stroke="#e89822"/>
  <text x="560" y="218" class="t" style="font-weight:700;fill:#b5740f">Claves de examen</text>
  <text x="560" y="244" class="s">tasa = techo · precio púb. = suelo</text>
  <text x="560" y="266" class="s">precio público NO es tributo (41)</text>
  <text x="560" y="288" class="s">90 % = art. 31 · módulos = art. 32</text>
  <text x="560" y="310" class="s">CE: 137 · 140 · 142 (no 156)</text>
  <text x="560" y="332" class="s">Madrid: Ley 22/2006 (TEAM + ATM)</text>
  <text x="560" y="352" class="s" style="fill:#b5740f">apremio para todo lo público</text>
</svg>
```
