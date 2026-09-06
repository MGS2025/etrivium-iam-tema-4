# Tema 4 — Changelog

> **Título oficial**: El Reglamento Orgánico del Gobierno y de la Administración del Ayuntamiento de Madrid, de 31 de mayo de 2004 (II): Los Distritos: Disposiciones Generales. El Concejal Presidente. Estructura administrativa.

---

## v1.1 — 2026-09-06 — Ficha de extensión y tiempo de estudio

**Estado**: sin cambios de contenido. Solo se añade información sobre el propio tema.

**Motivo**: petición del IAM (Jesús Cuadrado, 02-09-2026) al validar el Tema 30. Acepta la extensión de los temas «compuestos» a condición de que se informe de «su extensión en palabras y tiempo estimado de estudio». Al revisarlo se vio que ese dato solo aparecía en 16 de los 40 temas, y que faltaba justo en los más largos.

### Alcance

- Ficha bajo la cabecera del tema, y al final de la pestaña Índice donde esa pestaña existe:
  - **Extensión**: ~2.200 palabras · 12 diagramas · 150 preguntas de test
  - **Tiempo estimado de estudio**: 8-10 horas (primera vuelta completa, sin contar repasos)
- La cifra de palabras de la tabla de entregables se sincroniza con la ficha, para que el tema no muestre dos recuentos distintos.
- Las horas salen de una fórmula común a los 40 temas, para que sean comparables entre sí: contenido a 1.500 palabras/hora (ritmo de estudio activo), diagramas a una hora por cada cinco y test a dos minutos por pregunta. Se publica como intervalo de dos horas.
- Generado con `_tools-qa/ficha_estudio.py`, idempotente y reejecutable tras cualquier regeneración con `build_tNN.py`.

---

## v1.0 — 2026-06-15 — Generación inicial completa

**Estado**: Pendiente de validación por María / Ana (IAM).

### Alcance y decisiones

- **Fuente nuclear**: ROGA 2004, arts. 61-72, a partir del `Tema 4 tema.docx` aportado por el cliente (articulado de distritos, concejal-presidente y estructura administrativa).
- **Terminología vigente**: se usa "**coordinador del distrito**" (no "gerente del distrito"). El cliente aporta "coordinador", que es el término consolidado por el **Reglamento Orgánico 6/2021 de los Distritos del Ayuntamiento de Madrid**. El antiguo ROGA 2004 empleaba "gerente". Verificado con fuentes oficiales.
- **Sección complementaria de los 21 distritos** añadida (verificada lista oficial), paralela a las "Áreas de Gobierno actuales" del Tema 3.
- **Formato de referencia**: Temas 1/2/3 (admin): 150 preguntas + 20 pedagógicas + 6 casos + 12 diagramas + 7 pestañas.

### Entregables generados

| Fichero | Contenido |
|---|---|
| `tema-4-indice.md` | Índice de 14 secciones + tablas de datos clave |
| `tema-4-fuentes.md` | Registro Tier 1/2/3 + nota sobre coordinador/gerente |
| `tema-4-contenido.md` | Contenido teórico (14 secciones, 4 callouts) + 21 distritos |
| `tema-4-diagramas.md` | 12 diagramas SVG accesibles |
| `tema-4-test.md` | 150 preguntas + 20 pedagógicas |
| `tema-4-caso-practico.md` | 6 casos prácticos (Ayto Madrid), 10 pts c/u |
| `tema-4-validacion.md` | Checklist de validación |
| `index.html` | Web autosuficiente, 7 pestañas, motor test 1/3 |

### QA aplicado

- Articulado del cliente contrastado con el texto oficial del ROGA y con el Reglamento de Distritos vigente (coordinador vs gerente resuelto).
- Lista de los 21 distritos verificada con fuente oficial.
- Balanceo automático A/B/C de las respuestas del test.
- Refs cruzadas verificadas vs BOAM 10.032 (T2, T3, T5).

### Pendiente

- Validación de contenido por María / Ana (IAM).
- Reverificar terminología (coordinador) y número de distritos antes de cada convocatoria.
