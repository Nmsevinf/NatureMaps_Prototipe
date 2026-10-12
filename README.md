# Nature MAPS — Prototipo

Prototipo navegable de Nature MAPS, una guía de turismo botánico por Valencia, para que los testers lo prueben desde el móvil.

Abre `index.html` en el navegador para probarlo.

## Recorrido para la exposición oral

**1. Demostración de la app: mapa, escaneo y fichas**
- Elige **Modo aventura**. Toca **Mapa**: primero aparece el permiso de ubicación y después el mapa "Caza de especies".
- Toca un pin con **?** y luego **Hacer foto**. Verás el permiso de cámara, el visor, "Analizando tu foto" con Pl@ntNet y el resultado con el % de certeza y las especies alternativas.
- Pulsa **Ver ficha**. La ficha incluye la atribución de Pl@ntNet y las fuentes de información. Con los botones **ES / EN / VAL** se traduce, y la fuente del Ayuntamiento abre el Portal de Datos.

**2. Modos de uso**
- **Descubridor**: "Paseo tranquilo" muestra el mapa con plantas y puntos históricos, y "Solo lo esencial" el mapa simple. Desde el escáner, **Monumento o calle** identifica las Torres de Serranos.
- **Aventura**: **Tus logros** reúne las recompensas de conocimiento real: ficha ampliada, audioguía y curiosidades.
- **Educativo**: incluye la misión, el mapa de la ruta, el test final jugable y el resumen agregado de la clase.
  - Para la vista de profesor: **Ajustes › Vista Profesor**. Desde ahí se configura la ruta y se crea el test; las preguntas que añada la profesora aparecen después en el test del alumno.

**3. Tecnología diferencial e IA**
- **Identificación visual con IA (Pl@ntNet)**: el flujo del punto 1.
- **Búsqueda por IA**: pestaña **Buscar**; prueba "flor morada" o "edificio con arcos".
- **Mapa offline**: **Ajustes › Modo offline › Descargar**.
- **Notificaciones pasivas**: **Ajustes › Probar aviso al pasear (demo)**. El aviso aparece solo, sin abrir nada.

En **Ajustes › Demo para la presentación** se puede simular "Sin conexión" o "Límite diario" para enseñar las pantallas de error.

## Documentación

- [`docs/NatureMaps_Navegacion_de_pantallas.docx`](docs/NatureMaps_Navegacion_de_pantallas.docx): documento de navegación de pantallas en Word, con la vista general del Figma, cada modo, los diagramas tipo UML y el índice de pantallas.
- [`docs/NatureMaps_Navegacion_de_pantallas.pdf`](docs/NatureMaps_Navegacion_de_pantallas.pdf): el mismo documento en PDF.
- [`docs/diagramas/`](docs/diagramas): diagramas de navegación tipo UML en SVG (modos de uso; identificación y fichas; ajustes, profesor y administrador).
- [`docs/NatureMAPS_QR.png`](docs/NatureMAPS_QR.png): QR que abre el prototipo publicado en Claude. Solo funciona para los testers si el enlace está compartido desde el menú Compartir de la página.
