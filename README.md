# Panel Carrera Hangar

Panel de resultados de la campaña de RPs de la **Carrera Hangar** (Hangar Gym, Villahermosa · domingo 22 de noviembre de 2026). Hecho por Ingenioso.

Muestra cuántos RPs del plan entregaron su reel, las vistas, me gusta, comentarios y compartidos de cada uno, el ranking por tier, las anomalías y una tarjeta con la gráfica del reel de cada RP.

## Cómo verlo

Abre `index.html` en el navegador. Funciona sin servidor y sin conexión: los datos y `d3.min.js` vienen en el repositorio.

## Archivos

| Archivo | Qué es |
| --- | --- |
| `index.html` | Panel listo para abrir, con los datos incrustados |
| `panel-claude-artifact.html` | Código del panel tal como está publicado como artifact de Claude (lee los datos con `dash.data('rps')`) |
| `rps.json` | Un renglón por RP del plan (54): tier, sucursal, estado, vistas, likes, comentarios, compartidos, perfil, guion y capturas. Incluye `meta` con la fuente de cada dato |
| `plan.json` | Cuántos RPs lleva cada tier: A 20, B 15, C 12, D 7 |
| `d3.min.js` | d3 v7, para que abra sin internet |

## De dónde salen los números

- Lectura de cada reel en Instagram el 18 y 19 de noviembre de 2026.
- Para 15 RPs de tier A, las capturas de estadísticas que ellos mismos mandaron el 19 de noviembre (entre 11:45 a. m. y 4:17 p. m.). Son los números de su propia cuenta.
- Seguidores, siguiendo y publicaciones del perfil público de cada RP. Instagram redondea las cifras grandes.

## Privacidad

El repositorio es privado: trae nombres, usuarios de Instagram y cifras de personas reales. No lo hagas público sin avisarles.
