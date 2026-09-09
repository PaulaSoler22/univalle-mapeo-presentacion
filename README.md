# CompanyGame en Univalle — Mapeo curricular

Presentación comercial para directores de programa y decanos de la **Facultad de Ciencias de la
Administración** de la **Universidad del Valle (Univalle)**.

No presenta un simulador: muestra, pregrado por pregrado, **qué asignaturas del plan de estudios
ya pueden trabajarse con un simulador CompanyGame**, con cuál y en qué semestre.

## En cifras

- **7 pregrados**: Administración de Empresas, Contaduría Pública, Comercio Exterior, Finanzas y
  Banca, Gestión del Emprendimiento y la Innovación, Administración Turística, Administración
  Pública.
- **70 asignaturas** con simulador — 27 de aplicación directa, 43 como apoyo al curso.
- **29 simuladores** distintos del catálogo CompanyGame, de primer a noveno semestre.
- **Fundamentos de Contabilidad** es transversal a los 7 programas: en todos entra de aplicación
  directa con ContaTrainer.

Las cifras completas (incluida la cobertura real y el detalle por programa) están documentadas
en `CLAUDE.md`, junto con las salvedades del Excel fuente y los cambios hechos frente a la
plantilla maestra.

## Estructura — 15 slides

1. Portada y contexto
2. Cartelera de simuladores CompanyGame · **fijo**
3. Lo que ya se puede hacer hoy
4. Alcance por programa
5–11. **Ficha por programa** — una por cada uno de los 7 pregrados
12. Asignatura transversal: Fundamentos de Contabilidad
13. Los tres modelos de uso docente (A / B / C) · **fijo**
14. Evidencia de aprendizaje y acreditación
15. Cierre y contacto · **fijo**

## Cómo verla

Abre `index.html` en cualquier navegador. Navegación con flechas en pantalla, teclado
(← →, espacio) y swipe en móvil. Las capturas se amplían al hacer clic.

Para publicarla como Artifact de Claude:

```bash
node build-artifact.js
```

## Identidad visual

Paleta de **Simuladores de Negocios Colombia** (no cambia según la universidad): cyan
`#16AAE2`, azul `#0E73B8` y los grises `#737170` / `#989998` / `#CECBCB`.

## Tecnología

HTML5 + CSS3 + JavaScript vanilla, todo embebido en `index.html`. Sin frameworks.

---

Generada a partir de `plantilla-mapeo-curricular/`. Simuladores de Negocios Colombia S.A.S. ·
Distribuidor autorizado CompanyGame.
