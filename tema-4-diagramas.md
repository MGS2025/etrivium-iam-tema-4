# Tema 4 — Catálogo de Diagramas

> **Título oficial**: El ROGA de 31 de mayo de 2004 (II): Los Distritos. El Concejal-Presidente. Estructura administrativa.
>
> **Versión**: 1.0
> **Fecha**: 2026-06-15
> **Formato**: SVG inline (zero-dependencias, escalable, imprimible)
> **Paleta**: Ayuntamiento de Madrid #0055a0 (primario) + #d13c3c (alertas) + #2d8659 (ventajas) + #e89822 (callouts)

---

## Índice de diagramas

| ID  | Título                                                  | Sección | Tipo |
|-----|---------------------------------------------------------|---------|------|
| D1  | División funcional vs territorial del Ayuntamiento      | § 1     | Comparativa |
| D2  | El distrito: concepto y naturaleza (art. 61)            | § 2     | Esquema |
| D3  | Órganos de gobierno del distrito (art. 62)              | § 3     | Árbol |
| D4  | La Junta Municipal del Distrito (art. 63)               | § 4     | Esquema |
| D5  | El concejal-presidente (art. 64)                        | § 5     | Mapa |
| D6  | Competencias del concejal-presidente (art. 65)          | § 6     | Lista |
| D7  | Forma de los actos: Decreto vs Resolución               | § 7     | Comparativa |
| D8  | Estructura administrativa del distrito (art. 69)        | § 9     | Árbol |
| D9  | El coordinador del distrito (arts. 70-71)               | § 10    | Esquema |
| D10 | Concejal-presidente vs coordinador del distrito         | § 10    | Comparativa |
| D11 | Los 21 distritos de Madrid                              | § 13    | Mapa |
| D12 | Mapa-resumen del Tema 4                                  | § 14    | Mapa conceptual |

---

## D1 · División funcional vs territorial del Ayuntamiento

**Sección**: § 1 — Introducción
**Propósito**: Situar el distrito como la vertiente territorial de la organización.

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 700 300" role="img" aria-label="División funcional en Áreas de Gobierno frente a gestión territorial en distritos">
  <style>
    .a-h{font:700 14px system-ui,sans-serif;fill:#fff;text-anchor:middle}
    .a-t{font:13px system-ui,sans-serif;fill:#1a1a1a;text-anchor:middle}
    .a-s{font:11px system-ui,sans-serif;fill:#555;text-anchor:middle}
  </style>
  <rect x="250" y="20" width="200" height="46" rx="8" fill="#003d75"/>
  <text x="350" y="40" class="a-h">AYUNTAMIENTO DE MADRID</text>
  <text x="350" y="57" class="a-h" style="font-weight:400;font-size:11px">ROGA 2004 · art. 5</text>
  <line x1="350" y1="66" x2="350" y2="86" stroke="#0055a0" stroke-width="1.5"/>
  <line x1="180" y1="104" x2="180" y2="86" stroke="#0055a0" stroke-width="1.5"/>
  <line x1="520" y1="104" x2="520" y2="86" stroke="#0055a0" stroke-width="1.5"/>
  <line x1="180" y1="86" x2="520" y2="86" stroke="#0055a0" stroke-width="1.5"/>
  <rect x="60" y="104" width="240" height="150" rx="8" fill="#e8f0f8" stroke="#0055a0" stroke-width="1.5"/>
  <text x="180" y="132" class="a-h" style="fill:#003d75">DIVISIÓN FUNCIONAL</text>
  <text x="180" y="160" class="a-t">Áreas de Gobierno</text>
  <text x="180" y="184" class="a-s">órganos centrales</text>
  <text x="180" y="200" class="a-s">(todo el municipio)</text>
  <text x="180" y="228" class="a-s" style="font-weight:700;fill:#0055a0">→ TEMA 3</text>
  <rect x="400" y="104" width="240" height="150" rx="8" fill="#e8f5ee" stroke="#2d8659" stroke-width="1.5"/>
  <text x="520" y="132" class="a-h" style="fill:#1f5e3f">GESTIÓN TERRITORIAL</text>
  <text x="520" y="160" class="a-t">Distritos</text>
  <text x="520" y="184" class="a-s">órganos territoriales</text>
  <text x="520" y="200" class="a-s">(ámbito de un distrito)</text>
  <text x="520" y="228" class="a-s" style="font-weight:700;fill:#2d8659">→ TEMA 4 (este)</text>
</svg>
```

---

## D2 · El distrito: concepto y naturaleza (art. 61)

**Sección**: § 2 — Concepto
**Propósito**: Fijar los rasgos del distrito y quién lo divide.

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 700 290" role="img" aria-label="El distrito como división territorial con gestión desconcentrada, cuya división corresponde al Pleno, según el artículo 61">
  <style>
    .b-c{fill:#0055a0;stroke:#003d75;stroke-width:2}
    .b-b{fill:#fff;stroke:#0055a0;stroke-width:1.5}
    .b-t{font:700 14px system-ui,sans-serif;fill:#fff;text-anchor:middle}
    .b-h{font:700 12px system-ui,sans-serif;fill:#003d75;text-anchor:middle}
    .b-s{font:11px system-ui,sans-serif;fill:#555;text-anchor:middle}
  </style>
  <ellipse cx="350" cy="70" rx="170" ry="46" class="b-c"/>
  <text x="350" y="64" class="b-t">EL DISTRITO</text>
  <text x="350" y="84" class="b-t" style="font-weight:400;font-size:11px">división territorial del municipio</text>
  <rect x="30" y="160" width="200" height="100" rx="8" class="b-b"/>
  <text x="130" y="186" class="b-h">Gestión</text>
  <text x="130" y="204" class="b-h">DESCONCENTRADA</text>
  <text x="130" y="228" class="b-s">sin personalidad</text>
  <text x="130" y="244" class="b-s">jurídica propia</text>
  <rect x="250" y="160" width="200" height="100" rx="8" class="b-b"/>
  <text x="350" y="186" class="b-h">Finalidad</text>
  <text x="350" y="210" class="b-s">impulso de la</text>
  <text x="350" y="226" class="b-s">participación</text>
  <text x="350" y="242" class="b-s">ciudadana</text>
  <rect x="470" y="160" width="200" height="100" rx="8" fill="#fdf4e4" stroke="#e89822" stroke-width="1.5"/>
  <text x="570" y="186" class="b-h" style="fill:#a8650f">La divide</text>
  <text x="570" y="210" class="b-h" style="fill:#a8650f">EL PLENO</text>
  <text x="570" y="234" class="b-s">por norma orgánica</text>
  <text x="570" y="250" class="b-s">(art. 61.2 · LBRL 128)</text>
  <line x1="250" y1="110" x2="130" y2="160" stroke="#0055a0" stroke-width="1.2"/>
  <line x1="350" y1="116" x2="350" y2="160" stroke="#0055a0" stroke-width="1.2"/>
  <line x1="450" y1="110" x2="570" y2="160" stroke="#0055a0" stroke-width="1.2"/>
</svg>
```

---

## D3 · Órganos de gobierno del distrito (art. 62)

**Sección**: § 3 — Órganos de gobierno
**Propósito**: Los dos órganos de gobierno del distrito.

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 700 260" role="img" aria-label="Órganos de gobierno del distrito: la Junta Municipal y el concejal-presidente, según el artículo 62">
  <style>
    .c-root{fill:#0055a0;stroke:#003d75;stroke-width:2}
    .c-box{fill:#fff;stroke:#0055a0;stroke-width:1.5}
    .c-t{font:700 13px system-ui,sans-serif;fill:#fff;text-anchor:middle}
    .c-h{font:700 13px system-ui,sans-serif;fill:#003d75;text-anchor:middle}
    .c-s{font:11px system-ui,sans-serif;fill:#555;text-anchor:middle}
    .c-l{stroke:#0055a0;stroke-width:1.5;fill:none}
  </style>
  <rect x="230" y="20" width="240" height="50" rx="8" class="c-root"/>
  <text x="350" y="42" class="c-t">GOBIERNO Y ADMINISTRACIÓN</text>
  <text x="350" y="60" class="c-t" style="font-weight:400;font-size:11px">del distrito · art. 62</text>
  <line x1="350" y1="70" x2="350" y2="96" class="c-l"/>
  <line x1="180" y1="114" x2="180" y2="96" class="c-l"/>
  <line x1="520" y1="114" x2="520" y2="96" class="c-l"/>
  <line x1="180" y1="96" x2="520" y2="96" class="c-l"/>
  <rect x="70" y="114" width="220" height="90" rx="8" class="c-box"/>
  <text x="180" y="142" class="c-h">JUNTA MUNICIPAL</text>
  <text x="180" y="160" class="c-h">DEL DISTRITO</text>
  <text x="180" y="184" class="c-s">órgano colegiado</text>
  <rect x="410" y="114" width="220" height="90" rx="8" class="c-box"/>
  <text x="520" y="142" class="c-h">CONCEJAL-</text>
  <text x="520" y="160" class="c-h">PRESIDENTE</text>
  <text x="520" y="184" class="c-s">órgano unipersonal · la preside</text>
</svg>
```

---

## D4 · La Junta Municipal del Distrito (art. 63)

**Sección**: § 4 — La Junta Municipal
**Propósito**: De dónde provienen sus competencias.

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 700 250" role="img" aria-label="La Junta Municipal del Distrito ejerce competencias por delegación del alcalde o de la Junta de Gobierno, según el artículo 63">
  <style>
    .d-box{fill:#fff;stroke:#0055a0;stroke-width:1.5}
    .d-c{fill:#0055a0}
    .d-h{font:700 12px system-ui,sans-serif;fill:#003d75;text-anchor:middle}
    .d-t{font:700 13px system-ui,sans-serif;fill:#fff;text-anchor:middle}
    .d-s{font:11px system-ui,sans-serif;fill:#555;text-anchor:middle}
    .d-l{stroke:#0055a0;stroke-width:1.5;fill:none}
  </style>
  <rect x="50" y="40" width="180" height="50" rx="8" class="d-box"/>
  <text x="140" y="63" class="d-h">ALCALDE</text>
  <text x="140" y="80" class="d-s">delega</text>
  <rect x="50" y="150" width="180" height="50" rx="8" class="d-box"/>
  <text x="140" y="173" class="d-h">JUNTA DE GOBIERNO</text>
  <text x="140" y="190" class="d-s">delega</text>
  <rect x="430" y="95" width="220" height="60" rx="8" class="d-c"/>
  <text x="540" y="120" class="d-t">JUNTA MUNICIPAL</text>
  <text x="540" y="138" class="d-t" style="font-weight:400;font-size:11px">competencias ejecutivas/administrativas</text>
  <line x1="230" y1="65" x2="430" y2="115" class="d-l"/>
  <line x1="230" y1="175" x2="430" y2="135" class="d-l"/>
  <text x="350" y="225" class="d-s" style="font-style:italic">…sin perjuicio de las que le atribuya el Pleno (art. 123.1.c LBRL)</text>
</svg>
```

---

## D5 · El concejal-presidente (art. 64)

**Sección**: § 5 — El concejal-presidente
**Propósito**: Funciones nucleares de la figura.

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 700 320" role="img" aria-label="El concejal-presidente: nombrado por el alcalde, representa y dirige el distrito, preside la Junta Municipal, tiene voto de calidad y ejecuta los acuerdos">
  <style>
    .e-c{fill:#0055a0;stroke:#003d75;stroke-width:2}
    .e-n{fill:#fff;stroke:#0055a0;stroke-width:1.5}
    .e-ct{font:700 14px system-ui,sans-serif;fill:#fff;text-anchor:middle}
    .e-s{font:11px system-ui,sans-serif;fill:#1a1a1a;text-anchor:middle}
    .e-l{stroke:#0055a0;stroke-width:1;fill:none}
  </style>
  <rect x="250" y="130" width="200" height="60" rx="10" class="e-c"/>
  <text x="350" y="156" class="e-ct">CONCEJAL-</text>
  <text x="350" y="176" class="e-ct">PRESIDENTE</text>
  <rect x="250" y="20" width="200" height="44" rx="8" fill="#fdf4e4" stroke="#e89822" stroke-width="1.5"/>
  <text x="350" y="40" class="e-s" style="font-weight:700;fill:#a8650f">Nombrado y separado</text>
  <text x="350" y="56" class="e-s" style="fill:#a8650f">por EL ALCALDE</text>
  <line x1="350" y1="64" x2="350" y2="130" class="e-l"/>
  <rect x="20" y="120" width="200" height="44" rx="8" class="e-n"/>
  <text x="120" y="140" class="e-s">Representa el distrito</text>
  <text x="120" y="156" class="e-s">y dirige su administración</text>
  <rect x="480" y="120" width="200" height="44" rx="8" class="e-n"/>
  <text x="580" y="140" class="e-s">Convoca y preside</text>
  <text x="580" y="156" class="e-s">la Junta Municipal</text>
  <rect x="20" y="230" width="200" height="44" rx="8" class="e-n"/>
  <text x="120" y="250" class="e-s">Voto de calidad</text>
  <text x="120" y="266" class="e-s">(dirime empates)</text>
  <rect x="480" y="230" width="200" height="44" rx="8" class="e-n"/>
  <text x="580" y="250" class="e-s">Ejecuta los acuerdos</text>
  <text x="580" y="266" class="e-s">de la Junta</text>
  <line x1="250" y1="150" x2="220" y2="142" class="e-l"/>
  <line x1="450" y1="150" x2="480" y2="142" class="e-l"/>
  <line x1="280" y1="190" x2="160" y2="230" class="e-l"/>
  <line x1="420" y1="190" x2="560" y2="230" class="e-l"/>
</svg>
```

---

## D6 · Competencias del concejal-presidente (art. 65)

**Sección**: § 6 — Competencias
**Propósito**: Lista de competencias del art. 65.

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 700 300" role="img" aria-label="Competencias del concejal-presidente según el artículo 65">
  <style>
    .f-head{fill:#0055a0}
    .f-h{font:700 13px system-ui,sans-serif;fill:#fff;text-anchor:middle}
    .f-s{font:12px system-ui,sans-serif;fill:#1a1a1a;text-anchor:start}
    .f-k{font:700 12px system-ui,sans-serif;fill:#0055a0;text-anchor:middle}
  </style>
  <rect x="60" y="20" width="580" height="36" rx="8" class="f-head"/>
  <text x="350" y="44" class="f-h">CONCEJAL-PRESIDENTE · dirección, planificación y coordinación (art. 65)</text>
  <rect x="60" y="66" width="580" height="30" rx="5" fill="#e8f0f8"/>
  <text x="80" y="86" class="f-k">a</text><text x="105" y="86" class="f-s">Representación, dirección, gestión e inspección del distrito</text>
  <rect x="60" y="100" width="580" height="30" rx="5" fill="#fff" stroke="#e8ecf0"/>
  <text x="80" y="120" class="f-k">b</text><text x="105" y="120" class="f-s">Fijar objetivos, aprobar planes de actuación y asignar recursos</text>
  <rect x="60" y="134" width="580" height="30" rx="5" fill="#e8f0f8"/>
  <text x="80" y="154" class="f-k">c</text><text x="105" y="154" class="f-s">Proponer al titular del Área las propuestas para el Pleno o la Junta de Gobierno</text>
  <rect x="60" y="168" width="580" height="30" rx="5" fill="#fff" stroke="#e8ecf0"/>
  <text x="80" y="188" class="f-k">d</text><text x="105" y="188" class="f-s">Proponer al alcalde los proyectos de organización del distrito</text>
  <rect x="60" y="202" width="580" height="30" rx="5" fill="#e8f0f8"/>
  <text x="80" y="222" class="f-k">e</text><text x="105" y="222" class="f-s">Evaluar al coordinador y ejercer el control de eficacia</text>
  <rect x="60" y="236" width="580" height="30" rx="5" fill="#fff" stroke="#e8ecf0"/>
  <text x="80" y="256" class="f-k">f</text><text x="105" y="256" class="f-s">Superior autoridad sobre el personal del distrito</text>
</svg>
```

---

## D7 · Forma de los actos: Decreto vs Resolución

**Sección**: § 7 — Forma de los actos
**Propósito**: No confundir decreto (concejal-presidente) y resolución (coordinador).

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 700 230" role="img" aria-label="Forma de los actos: los del concejal-presidente son decretos y los del coordinador del distrito son resoluciones">
  <style>
    .g-h{font:700 14px system-ui,sans-serif;fill:#fff;text-anchor:middle}
    .g-t{font:700 18px system-ui,sans-serif;fill:#fff;text-anchor:middle}
    .g-s{font:12px system-ui,sans-serif;fill:#1a1a1a;text-anchor:middle}
  </style>
  <rect x="40" y="30" width="290" height="150" rx="10" fill="#fff" stroke="#0055a0" stroke-width="1.5"/>
  <rect x="40" y="30" width="290" height="44" rx="10" fill="#0055a0"/>
  <text x="185" y="58" class="g-h">CONCEJAL-PRESIDENTE</text>
  <rect x="90" y="92" width="190" height="44" rx="8" fill="#003d75"/>
  <text x="185" y="120" class="g-t">DECRETO</text>
  <text x="185" y="160" class="g-s">"Decretos del concejal-presidente</text>
  <text x="185" y="175" class="g-s">de la Junta Municipal de Distrito"</text>
  <rect x="370" y="30" width="290" height="150" rx="10" fill="#fff" stroke="#2d8659" stroke-width="1.5"/>
  <rect x="370" y="30" width="290" height="44" rx="10" fill="#2d8659"/>
  <text x="515" y="58" class="g-h">COORDINADOR DEL DISTRITO</text>
  <rect x="420" y="92" width="190" height="44" rx="8" fill="#1f5e3f"/>
  <text x="515" y="120" class="g-t">RESOLUCIÓN</text>
  <text x="515" y="162" class="g-s">decisiones administrativas (art. 71.2)</text>
  <text x="350" y="212" class="g-s" style="font-style:italic;fill:#a3271c">Pregunta típica de examen: no confundir decreto y resolución</text>
</svg>
```

---

## D8 · Estructura administrativa del distrito (art. 69)

**Sección**: § 9 — Estructura administrativa
**Propósito**: Jerarquía de la organización administrativa del distrito.

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 700 300" role="img" aria-label="Estructura administrativa del distrito: el concejal-presidente como jefe superior, el coordinador del distrito y las unidades administrativas, según el artículo 69">
  <style>
    .h-box{fill:#fff;stroke:#0055a0;stroke-width:1.5}
    .h-root{fill:#0055a0;stroke:#003d75;stroke-width:2}
    .h-t{font:700 13px system-ui,sans-serif;fill:#fff;text-anchor:middle}
    .h-h{font:700 12px system-ui,sans-serif;fill:#003d75;text-anchor:middle}
    .h-s{font:11px system-ui,sans-serif;fill:#555;text-anchor:middle}
    .h-l{stroke:#0055a0;stroke-width:1.5;fill:none}
  </style>
  <rect x="230" y="20" width="240" height="50" rx="8" class="h-root"/>
  <text x="350" y="42" class="h-t">CONCEJAL-PRESIDENTE</text>
  <text x="350" y="60" class="h-t" style="font-weight:400;font-size:11px">jefe superior (art. 69.1)</text>
  <line x1="350" y1="70" x2="350" y2="100" class="h-l"/>
  <rect x="230" y="100" width="240" height="56" rx="8" class="h-box"/>
  <text x="350" y="124" class="h-h">COORDINADOR DEL DISTRITO</text>
  <text x="350" y="142" class="h-s">dirige y coordina los servicios (art. 69.2)</text>
  <line x1="350" y1="156" x2="350" y2="186" class="h-l"/>
  <rect x="190" y="186" width="320" height="80" rx="8" fill="#e8f0f8" stroke="#0055a0" stroke-width="1.2"/>
  <text x="350" y="212" class="h-h">UNIDADES ADMINISTRATIVAS</text>
  <text x="350" y="234" class="h-s">funcionalmente homogéneas</text>
  <text x="350" y="252" class="h-s">se crean/modifican/suprimen vía RPT (art. 69.3)</text>
</svg>
```

---

## D9 · El coordinador del distrito (arts. 70-71)

**Sección**: § 10 — El coordinador del distrito
**Propósito**: Nombramiento, rango y forma de los actos.

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 700 280" role="img" aria-label="El coordinador del distrito: nombrado por la Junta de Gobierno a propuesta del concejal-presidente, con rango de director general, según los artículos 70 y 71">
  <style>
    .i-c{fill:#0055a0;stroke:#003d75;stroke-width:2}
    .i-b{fill:#fff;stroke:#0055a0;stroke-width:1.5}
    .i-t{font:700 13px system-ui,sans-serif;fill:#fff;text-anchor:middle}
    .i-h{font:700 12px system-ui,sans-serif;fill:#003d75;text-anchor:middle}
    .i-s{font:11px system-ui,sans-serif;fill:#555;text-anchor:middle}
    .i-l{stroke:#0055a0;stroke-width:1.5;fill:none}
  </style>
  <rect x="250" y="110" width="200" height="56" rx="10" class="i-c"/>
  <text x="350" y="134" class="i-t">COORDINADOR</text>
  <text x="350" y="152" class="i-t">DEL DISTRITO</text>
  <rect x="40" y="30" width="280" height="56" rx="8" class="i-b"/>
  <text x="180" y="54" class="i-h">Lo nombra la JUNTA DE GOBIERNO</text>
  <text x="180" y="72" class="i-s">a propuesta del concejal-presidente (art. 70.1)</text>
  <rect x="380" y="30" width="280" height="56" rx="8" fill="#fdf4e4" stroke="#e89822" stroke-width="1.5"/>
  <text x="520" y="54" class="i-h" style="fill:#a8650f">Rango de DIRECTOR GENERAL</text>
  <text x="520" y="72" class="i-s">nombramiento conforme al art. 49 (Tema 3)</text>
  <rect x="40" y="200" width="280" height="56" rx="8" class="i-b"/>
  <text x="180" y="224" class="i-h">Jefatura inmediata</text>
  <text x="180" y="242" class="i-s">de las unidades adscritas (art. 71)</text>
  <rect x="380" y="200" width="280" height="56" rx="8" fill="#e8f5ee" stroke="#2d8659" stroke-width="1.5"/>
  <text x="520" y="224" class="i-h" style="fill:#1f5e3f">Sus actos: RESOLUCIÓN</text>
  <text x="520" y="242" class="i-s">(art. 71.2)</text>
  <line x1="300" y1="120" x2="300" y2="86" class="i-l"/>
  <line x1="400" y1="120" x2="430" y2="86" class="i-l"/>
  <line x1="300" y1="166" x2="280" y2="200" class="i-l"/>
  <line x1="400" y1="166" x2="450" y2="200" class="i-l"/>
</svg>
```

---

## D10 · Concejal-presidente vs coordinador del distrito

**Sección**: § 10 — Comparativa
**Propósito**: Diferenciar las dos figuras clave del distrito.

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 700 280" role="img" aria-label="Comparación entre el concejal-presidente (órgano superior) y el coordinador del distrito (órgano directivo)">
  <style>
    .j-hb{font:700 13px system-ui,sans-serif;fill:#fff;text-anchor:middle}
    .j-r{font:600 11px system-ui,sans-serif;fill:#777;text-anchor:middle}
    .j-v{font:12px system-ui,sans-serif;fill:#1a1a1a;text-anchor:middle}
  </style>
  <rect x="40" y="20" width="300" height="40" rx="8" fill="#0055a0"/>
  <text x="190" y="45" class="j-hb">CONCEJAL-PRESIDENTE</text>
  <rect x="360" y="20" width="300" height="40" rx="8" fill="#2d8659"/>
  <text x="510" y="45" class="j-hb">COORDINADOR DEL DISTRITO</text>
  <text x="350" y="86" class="j-r">NATURALEZA</text>
  <rect x="40" y="94" width="300" height="34" rx="5" fill="#e8f0f8"/><text x="190" y="116" class="j-v">Órgano superior (política)</text>
  <rect x="360" y="94" width="300" height="34" rx="5" fill="#e8f5ee"/><text x="510" y="116" class="j-v">Órgano directivo (ejecución)</text>
  <text x="350" y="152" class="j-r">NOMBRAMIENTO</text>
  <rect x="40" y="160" width="300" height="34" rx="5" fill="#e8f0f8"/><text x="190" y="182" class="j-v">El alcalde</text>
  <rect x="360" y="160" width="300" height="34" rx="5" fill="#e8f5ee"/><text x="510" y="182" class="j-v">La Junta de Gobierno</text>
  <text x="350" y="218" class="j-r">FORMA DE SUS ACTOS</text>
  <rect x="40" y="226" width="300" height="34" rx="5" fill="#e8f0f8"/><text x="190" y="248" class="j-v">Decreto</text>
  <rect x="360" y="226" width="300" height="34" rx="5" fill="#e8f5ee"/><text x="510" y="248" class="j-v">Resolución</text>
</svg>
```

---

## D11 · Los 21 distritos de Madrid

**Sección**: § 13 — Los distritos
**Propósito**: Listar los 21 distritos numerados.

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 700 360" role="img" aria-label="Los 21 distritos de Madrid, del distrito 1 Centro al 21 Barajas">
  <style>
    .k-h{font:700 14px system-ui,sans-serif;fill:#fff;text-anchor:middle}
    .k-n{font:700 11px system-ui,sans-serif;fill:#0055a0;text-anchor:middle}
    .k-t{font:11px system-ui,sans-serif;fill:#1a1a1a;text-anchor:start}
  </style>
  <rect x="170" y="14" width="360" height="36" rx="8" fill="#0055a0"/>
  <text x="350" y="38" class="k-h">LOS 21 DISTRITOS DE MADRID</text>
  <g>
    <text x="40" y="80" class="k-n">01</text><text x="60" y="80" class="k-t">Centro</text>
    <text x="40" y="106" class="k-n">02</text><text x="60" y="106" class="k-t">Arganzuela</text>
    <text x="40" y="132" class="k-n">03</text><text x="60" y="132" class="k-t">Retiro</text>
    <text x="40" y="158" class="k-n">04</text><text x="60" y="158" class="k-t">Salamanca</text>
    <text x="40" y="184" class="k-n">05</text><text x="60" y="184" class="k-t">Chamartín</text>
    <text x="40" y="210" class="k-n">06</text><text x="60" y="210" class="k-t">Tetuán</text>
    <text x="40" y="236" class="k-n">07</text><text x="60" y="236" class="k-t">Chamberí</text>
  </g>
  <g>
    <text x="270" y="80" class="k-n">08</text><text x="290" y="80" class="k-t">Fuencarral-El Pardo</text>
    <text x="270" y="106" class="k-n">09</text><text x="290" y="106" class="k-t">Moncloa-Aravaca</text>
    <text x="270" y="132" class="k-n">10</text><text x="290" y="132" class="k-t">Latina</text>
    <text x="270" y="158" class="k-n">11</text><text x="290" y="158" class="k-t">Carabanchel</text>
    <text x="270" y="184" class="k-n">12</text><text x="290" y="184" class="k-t">Usera</text>
    <text x="270" y="210" class="k-n">13</text><text x="290" y="210" class="k-t">Puente de Vallecas</text>
    <text x="270" y="236" class="k-n">14</text><text x="290" y="236" class="k-t">Moratalaz</text>
  </g>
  <g>
    <text x="500" y="80" class="k-n">15</text><text x="520" y="80" class="k-t">Ciudad Lineal</text>
    <text x="500" y="106" class="k-n">16</text><text x="520" y="106" class="k-t">Hortaleza</text>
    <text x="500" y="132" class="k-n">17</text><text x="520" y="132" class="k-t">Villaverde</text>
    <text x="500" y="158" class="k-n">18</text><text x="520" y="158" class="k-t">Villa de Vallecas</text>
    <text x="500" y="184" class="k-n">19</text><text x="520" y="184" class="k-t">Vicálvaro</text>
    <text x="500" y="210" class="k-n">20</text><text x="520" y="210" class="k-t">San Blas-Canillejas</text>
    <text x="500" y="236" class="k-n">21</text><text x="520" y="236" class="k-t">Barajas</text>
  </g>
  <text x="350" y="300" class="k-t" text-anchor="middle" style="fill:#777;font-style:italic">La división la establece el Pleno por norma orgánica (art. 61.2). Cada distrito se subdivide en barrios.</text>
</svg>
```

---

## D12 · Mapa-resumen del Tema 4

**Sección**: § 14 — Resumen
**Propósito**: Mapa conceptual de cierre.

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 700 320" role="img" aria-label="Mapa resumen del Tema 4: el distrito, sus órganos de gobierno y su estructura administrativa">
  <style>
    .l-c{fill:#0055a0;stroke:#003d75;stroke-width:2}
    .l-n{fill:#fff;stroke:#0055a0;stroke-width:1.5}
    .l-ct{font:700 13px system-ui,sans-serif;fill:#fff;text-anchor:middle}
    .l-h{font:700 12px system-ui,sans-serif;fill:#003d75;text-anchor:middle}
    .l-s{font:10.5px system-ui,sans-serif;fill:#555;text-anchor:middle}
    .l-l{stroke:#0055a0;stroke-width:1;fill:none}
  </style>
  <line x1="350" y1="160" x2="160" y2="70" class="l-l"/>
  <line x1="350" y1="160" x2="540" y2="70" class="l-l"/>
  <line x1="350" y1="160" x2="160" y2="255" class="l-l"/>
  <line x1="350" y1="160" x2="540" y2="255" class="l-l"/>
  <ellipse cx="350" cy="160" rx="90" ry="44" class="l-c"/>
  <text x="350" y="156" class="l-ct">EL DISTRITO</text>
  <text x="350" y="174" class="l-ct" style="font-weight:400;font-size:11px">ROGA arts. 61-72</text>
  <rect x="40" y="42" width="240" height="56" rx="8" class="l-n"/>
  <text x="160" y="66" class="l-h">Concepto</text>
  <text x="160" y="84" class="l-s">división territorial · gestión desconcentrada · la divide el Pleno</text>
  <rect x="420" y="42" width="240" height="56" rx="8" class="l-n"/>
  <text x="540" y="66" class="l-h">Órganos de gobierno</text>
  <text x="540" y="84" class="l-s">Junta Municipal + concejal-presidente</text>
  <rect x="40" y="228" width="240" height="56" rx="8" class="l-n"/>
  <text x="160" y="252" class="l-h">Concejal-presidente</text>
  <text x="160" y="270" class="l-s">alcalde lo nombra · decreto · superior</text>
  <rect x="420" y="228" width="240" height="56" rx="8" class="l-n"/>
  <text x="540" y="252" class="l-h">Coordinador del distrito</text>
  <text x="540" y="270" class="l-s">Junta de Gobierno · resolución · rango DG</text>
</svg>
```
