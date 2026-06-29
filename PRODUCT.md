# Product

## Register

brand

## Users

Público general con conexión afectiva o cultural al Instituto Carlos Pellegrini de Pilar — ex-alumnos, familias, comunidad de Pilar — y también las propias autoridades de la institución. Acceden desde escritorio, sin contexto previo, en un momento de pausa voluntaria. No vienen a "informarse": vienen a encontrarse con algo que ya intuyen que importa.

## Product Purpose

"El tiempo del predio" es una obra de scrollytelling cinematográfico que narra la historia del Instituto Carlos Pellegrini de Pilar (1906–2025) a través de 9 movimientos + epílogo. No es un sitio institucional ni un documento histórico: es una experiencia de lectura que usa el scroll como gesto narrativo. El éxito es que alguien llegue al epílogo y sienta que acaba de atravesar un lugar, no de leer sobre él.

## Brand Personality

Peso, extrañeza, permanencia.

La voz es la de un archivo que habla — precisa, econónica, sin adornos retóricos. El tono oscila entre el documento y el poema. Nunca explica; muestra. Nunca consuela; sostiene.

## Anti-references

- **Línea de tiempo escolar** (Wikipedia, Timetoast, cualquier timeline con fechas en lista y texto descriptivo): el mayor peligro. Esta pieza rechaza la lógica enciclopédica.
- **Sitio institucional con hero y CTA**: nada de "Conocé nuestra historia" en botón outline. Ninguna grid de valores corporativos.
- **Documental over-explained**: sin narrador omnisciente, sin música motivacional, sin "y así, El Glorioso..."

## Design Principles

1. **El silencio es contenido.** El espacio vacío, la pantalla en negro, la pausa larga son decisiones narrativas — no ausencia de diseño.
2. **El gesto del lector mueve la historia.** El scroll no es navegación: es tiempo. La velocidad, la dirección, la pausa del visitante forman parte de la obra.
3. **Economía radical de medios.** Una sola palabra puede ser un movimiento entero. El peso lo da la precisión, no la acumulación.
4. **Los colores tienen significado, no decoración.** Cyan = archivo/fecha. Amarillo = sueño/esperanza. Naranja = fundación/institucional. Rosa = costo humano/injusticia. Usarlos fuera de ese sistema rompe la gramática de la pieza.
5. **La obra termina abierta.** El epílogo no cierra — deja la pregunta en el aire. El diseño no debe resolver lo que el texto deliberadamente deja sin resolver.

## Accessibility & Inclusion

- WCAG AA como mínimo para todos los textos sobre fondo oscuro.
- `aria-hidden="true"` en todos los elementos decorativos (tracker, grain, viñeta, cursor).
- El contenido narrativo completo debe ser legible sin JavaScript (texto visible en HTML semántico).
- `@media (prefers-reduced-motion: reduce)` debe detener las animaciones de scroll sin perder legibilidad.
