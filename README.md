# Satellite Orbit Explorer · Space Career Week 2026 · GNSS Academy

- Sofía Barbás

Este notebook contiene la implementación completa y ordenada del simulador en 8 etapas consecutivas:

1. **Stage 1**: Configuración del entorno de trabajo.
2. **Stage 2**: Carga de datos OMM JSON.
3. **Stage 3**: Conversión a parámetros Keplerianos físicos.
4. **Stage 4**: Definición de la grilla de tiempo unificada.
5. **Stage 5**: Propagación analítica (Dos cuerpos con rotación terrestre).
6. **Stage 6**: Extracción de resúmenes de telemetría.
7. **Stage 7**: Visualización 2D de ground tracks y velocidades.
8. **Stage 8**: Exportación KML para Google Earth y reporte analítico final.

# Guía para abrir los KML en Google Earth Pro (Escritorio)
1. **Visualización de Órbitas 3D Estáticas (orbit_tracks_ecef.kml):**
Abre Google Earth Pro y selecciona Archivo > Abrir... para cargar orbit_tracks_ecef.kml.
Verás las órbitas suspendidas en el espacio tridimensional alrededor de la Tierra, cada una con su respectiva altitud real (metros) y un color representativo idéntico al de los gráficos.
2. **Visualización de Animaciones Dinámicas (orbit_animation.kml):**
Importa orbit_animation.kml de la misma manera.
Google Earth Pro detectará automáticamente las etiquetas temporales <when> y activará un reproductor y deslizador de tiempo en la esquina superior izquierda de la pantalla.
Ajusta la velocidad de reproducción y presiona Play (►) para ver a los cuatro satélites avanzar de forma coordinada, respetando la física de su velocidad a lo largo de las 24 horas.
