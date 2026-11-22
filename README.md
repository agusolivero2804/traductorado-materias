# Mi Traductorado UNC

App web para llevar el seguimiento de la carrera **Traductorado Público Nacional de Inglés** de la Facultad de Lenguas (UNC).

## Qué hace

- Muestra todas las materias agrupadas por año, más el ingreso (Ciclo de Nivelación).
- A cada materia le podés poner el estado **sin cursar / libre**, **regular** o **aprobada**.
- Respeta las correlativas:
  - Para marcar una materia como regular, tenés que tener sus correlativas **regularizadas**.
  - Para marcarla como aprobada, tenés que tener sus correlativas **aprobadas**.
- Te deja cargar la **nota final** de cada materia y la **cantidad de aplazos**, con botones − / +.
- Calcula el promedio **sin aplazos** y **con aplazos**. En el promedio con aplazos, cada aplazo cuenta como un 2.
- Tiene contadores de materias aprobadas y regulares.
- Muestra el porcentaje de la carrera aprobada. Para el porcentaje cuenta las 31 materias obligatorias: deja afuera el ingreso y las optativas de Latín.
- Lista las materias a las que ya te podés anotar y las regulares que ya podés rendir.
- Tiene botones para deshacer, empezar de cero y copiar o importar tus datos.
- Funciona en el celular: se puede instalar en la pantalla de inicio y anda sin conexión.

Los datos se guardan solo en el navegador (localStorage). No se mandan a ningún servidor.

## Usarla desde el celular

1. Activá GitHub Pages en el repo: **Settings → Pages → Deploy from a branch → `main` / `(root)`**.
2. Abrí `https://agusolivero2804.github.io/traductorado-materias/` en el celular.
3. Instalala en la pantalla de inicio:
   - **Android (Chrome):** menú ⋮ → *Agregar a la pantalla principal* (o *Instalar app*).
   - **iPhone (Safari):** botón Compartir → *Agregar a inicio*.

## Fuente de las correlatividades

Están tomadas de la propuesta de flexibilización del régimen de correlatividades de la Facultad de Lenguas, aprobada por el Consejo Superior en septiembre de 2025 ([documento oficial](https://boletin.unc.edu.ar/bitstreams/94943d20-6d37-4f90-8a92-b4d976e6189b/download)). Antes de inscribirte, verificalas con el plan vigente.

## Archivos

| Archivo | Para qué sirve |
|---|---|
| `index.html` | La app completa (HTML, CSS y JS en un solo archivo) |
| `manifest.webmanifest` | Datos para instalarla como app |
| `sw.js` | Guarda la app para usarla sin conexión |
| `icon-*.png`, `apple-touch-icon.png` | Íconos |
