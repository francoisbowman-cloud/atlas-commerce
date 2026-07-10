# Protocolo de vinculación — Atlas Commerce

Este proyecto es una **tienda o línea de negocio individual** dentro de la plataforma Atlas Commerce. No es un proyecto independiente: hereda su filosofía, constitución y procesos de la base, y no debe redefinirlos.

## Base del proyecto (fuente de verdad)

- Repositorio base: https://github.com/francoisbowman-cloud/atlas-commerce
- Ahí viven: la Constitución y filosofía (Volumen I / RFC-000), el proceso de RFCs (RFC-001), el modelo de negocio de productos digitales en Etsy (RFC-002), la delegación de ideación a Cowork (RFC-003), el stack de contenido audiovisual (RFC-004), la estructura multi-repositorio (RFC-005) y este mismo protocolo (RFC-006).

## Qué hereda esta tienda sin necesidad de redecidir

- La Constitución de 10 artículos y los 8 principios fundamentales (Volumen I).
- El proceso de RFCs: toda decisión importante se documenta, versiona y aprueba igual que en la base (RFC-001).
- El modelo de negocio de productos digitales (plantillas/printables, recursos gráficos, guías/mini-cursos, aplicaciones ligeras), con el criterio de "calidad sobre velocidad de lanzamiento" (RFC-002), si esta tienda opera bajo ese modelo.
- Cowork como responsable de ideación de producto (Scout + Research + Evaluator, de forma manual) salvo que se decida lo contrario para esta tienda (RFC-003).
- El stack de contenido audiovisual: MinimaxHub, Hailuo AI, Remotion, y el fallback de ffmpeg+Pillow cuando el entorno de Cowork no permita usar un navegador (RFC-004).

## Reglas de este proyecto (tienda)

1. **No copiar ni duplicar** la Biblia o los RFCs base aquí. Para citarlos, referencia el volumen/RFC exacto del repositorio base (ej. "según RFC-002").
2. Toda decisión importante y específica de **esta tienda** se documenta como un RFC propio de este repositorio, con su **propia numeración empezando en RFC-001** (independiente de la numeración del repositorio base — son ámbitos distintos).
3. Ninguna decisión de esta tienda puede contradecir la Constitución del Volumen I. Si hay conflicto, se resuelve a favor de la Constitución, o se escala como propuesta de cambio en el repositorio base.
4. Cowork actúa aquí con el mismo rol que en el repositorio base (Arquitecto Principal + ideación de producto), salvo que se decida lo contrario para esta tienda.
5. El acceso (token de GitHub) a este repositorio se configura por separado del repositorio base y de otras tiendas ("Only select repositories"), nunca compartido de forma amplia (RFC-005, Artículo III).

## Al iniciar cualquier chat nuevo sobre esta tienda, Cowork debe

- Asumir que la Constitución, el modelo de negocio general y el proceso de RFCs **ya están decididos**: no repetirlos ni volver a preguntarlos.
- Preguntar solo por lo específico de esta tienda que aún no esté documentado en su propio repositorio (producto, estado, métricas, próximos pasos).
