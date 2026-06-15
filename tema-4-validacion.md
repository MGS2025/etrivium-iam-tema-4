# Tema 4 — Checklist de Validación

> **Título oficial**: El Reglamento Orgánico del Gobierno y de la Administración del Ayuntamiento de Madrid, de 31 de mayo de 2004 (II): Los Distritos: Disposiciones Generales. El Concejal Presidente. Estructura administrativa.
> **Versión**: 1.0
> **Fecha**: 2026-06-15
> **Revisoras**: María + Ana (IAM)

---

## Cómo usar este checklist

- **OK** → el criterio se cumple sin cambios.
- **REVISAR** → necesita ajuste o aclaración (indicar qué).
- **NO** → no se cumple o es incorrecto. Justificar.

---

## 1. Fuentes y trazabilidad

- [ ] La fuente nuclear es el ROGA 2004, arts. 61-72, coincidente con el `Tema 4 tema.docx` aportado por el cliente.
- [ ] Se emplea el término vigente "**coordinador del distrito**" (no "gerente"), conforme al Reglamento Orgánico de los Distritos vigente.
- [ ] Cada afirmación que reproduce el articulado está referenciada con `[ROGA, art. X]` o `[LBRL, art. X]`.
- [ ] Cada pregunta del banco y de los casos puede reconducirse a un artículo del ROGA, la LBRL o la división vigente en distritos.

## 2. Estructura del contenido

- [ ] El `tema-4-indice.md` refleja fielmente la estructura de `tema-4-contenido.md`.
- [ ] Las secciones cubren: concepto de distrito, órganos de gobierno, Junta Municipal, concejal-presidente, competencias, responsabilidad y forma de actos, vicepresidente, estructura administrativa, coordinador del distrito, funciones del coordinador, participación y los 21 distritos.
- [ ] Los conceptos memorizables aparecen como `[DATO CLAVE EXAMEN]`.
- [ ] Las reproducciones del articulado aparecen como `[CITA NORMATIVA]`.
- [ ] Los ejemplos del Ayto de Madrid están marcados como `[EJEMPLO AYTO MADRID]`.
- [ ] Los enlaces a otros temas se marcan como `[REFERENCIA CRUZADA]`.

## 3. Rigor jurídico

- [ ] El distrito es división territorial con gestión **desconcentrada** (sin personalidad jurídica propia) [art. 61.1].
- [ ] La división en distritos la establece el **Pleno** por norma orgánica [art. 61.2].
- [ ] El gobierno del distrito corresponde a la **Junta Municipal** y al **concejal-presidente** [art. 62].
- [ ] La Junta Municipal ejerce competencias **por delegación** del alcalde o de la Junta de Gobierno [art. 63].
- [ ] El concejal-presidente es **nombrado y separado por el alcalde**; preside la Junta y tiene **voto de calidad** [art. 64].
- [ ] Los actos del concejal-presidente son **decretos** [art. 67]; los del coordinador, **resoluciones** [art. 71.2].
- [ ] El vicepresidente es un **concejal-vocal** nombrado por el alcalde [art. 68].
- [ ] El jefe superior de la organización administrativa es el **concejal-presidente** [art. 69.1].
- [ ] El **coordinador del distrito** lo nombra la **Junta de Gobierno** a propuesta del concejal-presidente y tiene **rango de director general** [arts. 70, 49].
- [ ] Los 21 distritos están correctamente enumerados (Centro=1 … Barajas=21).

## 4. Diagramas SVG

- [ ] Los 12 diagramas están presentes en `tema-4-diagramas.md`.
- [ ] Cada diagrama incluye `role="img"` y `aria-label` descriptivo.
- [ ] Paleta coherente: Ayto Madrid #0055a0 + #d13c3c + #2d8659 + #e89822.
- [ ] Ningún diagrama depende de CDN, fuentes externas ni scripts.

## 5. Banco de 150 preguntas

- [ ] Las 150 preguntas tienen 3 opciones y una única respuesta correcta verificable.
- [ ] La distribución A/B/C está equilibrada (~50/50/50) tras el balanceo automático.
- [ ] No hay preguntas ambiguas.
- [ ] La sección pedagógica de 20 preguntas incluye explicación y referencia.

## 6. Casos prácticos

- [ ] Los 6 casos mantienen escenario del Ayto de Madrid (distritos concretos).
- [ ] Las cuestiones de cada caso suman 10 puntos.
- [ ] Cada caso tiene solución orientativa y criterios de evaluación.

## 7. Nivel y adecuación al C1

- [ ] Nivel de profundidad adecuado para C1.
- [ ] Se prioriza la memorización de órganos, formas de actos, rangos y los 21 distritos.

## 8. Entregables HTML

- [ ] `index.html` autosuficiente (offline), 7 pestañas, motor de test con penalización 1/3.
- [ ] Imprimible a PDF.
- [ ] Branding Ayuntamiento de Madrid (#0055a0).

## 9. Consistencia inter-temas

- [ ] Referencia cruzada al **Tema 3** (Áreas de Gobierno) coherente.
- [ ] Referencia al **Tema 2** (régimen especial) y al **Tema 5** (EBEP, directivos) coherente.

---

## Observaciones generales

### Decisiones conscientes que conviene confirmar

1. **Terminología "coordinador del distrito"** (no "gerente"): el cliente aporta "coordinador" en `Tema 4 tema.docx`, que es el término **vigente** (Reglamento Orgánico 6/2021 de los Distritos). El antiguo ROGA 2004 decía "gerente". Se sigue la versión del cliente.
2. **Sección de los 21 distritos** añadida como complemento (el epígrafe no la exige literalmente, pero aporta valor; paralela a las Áreas actuales del Tema 3). Dato actualizable.
3. **150 preguntas + 20 pedagógicas + 6 casos + 12 diagramas + 7 pestañas**, replicando el formato de los Temas 1/2/3.
4. **Balanceo automático A/B/C** mediante permutación determinista en `build_t4.py`.

### Punto a vigilar

- La **denominación de la figura directiva** (coordinador vs gerente) y el **número de distritos** son datos sujetos a la norma orgánica vigente. Reverificar antes de cada convocatoria.

---

## Decisión de cierre

- [ ] Aprobado sin cambios.
- [ ] Aprobado con cambios menores (listarlos).
- [ ] Requiere v2 (listar cambios sustanciales).

**Firmas**:

- María: _______________________________ Fecha: _____________
- Ana: _______________________________ Fecha: _____________
