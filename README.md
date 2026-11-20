# Maqueta de Buenos Aires

Toda la Ciudad de Buenos Aires en 3D, en el navegador: los 48 barrios y sus 1.386.616 volúmenes edificados, cada uno con
su altura medida. Los barrios se cargan solos al acercarse, y tiene un buscador de direcciones y esquinas.

También muestra calzadas, 406.340 árboles censados, 3.799 semáforos y 8.462 lugares (estaciones de servicio, comisarías,
bomberos, hospitales, escuelas, museos, cajeros y más), con cuántos hay de cada uno en cada barrio.

Tiene un panel de **capas** para prender y apagar cada cosa (y elegir cuántos árboles ver), 15 **edificios conocidos** con su
forma (Obelisco, Congreso, Torre Monumental, Planetario, Barolo, Floralis Genérica, los puentes y más; se buscan por nombre),
las 6 líneas de **subte** con sus 90 estaciones y el **sol** en su posición real para el día y la hora que elijas, con sombras.

**Abrir:** https://agloland-organizacion.github.io/maqueta-caba/

- Arrastrar: mover · clic derecho o dos dedos: girar · rueda o pellizco: acercar.
- Las alturas vienen en escalones de 2,8 m (pisos) y el relevamiento es de 2021: lo construido después no está.
- Coordenadas: Gauss-Krüger BA (EPSG:9498) menos 100.000 m.

## Fuentes

Datos del Gobierno de la Ciudad de Buenos Aires, [BA Data](https://data.buenosaires.gob.ar), licencia
[CC-BY 2.5 AR](https://creativecommons.org/licenses/by/2.5/ar/): Tejido Urbano, callejero, manzanas catastrales,
espacios verdes, red de ferrocarril, barrios, arbolado, semáforos y los mapas de lugares (estaciones de servicio,
comisarías, bomberos, salud, educación, cultura, deporte y servicios). Subte: estaciones de SBASE (unidas en línea recta: el dataset no trae los túneles). Edificios conocidos: © [OpenStreetMap](https://www.openstreetmap.org/copyright) contributors, licencia ODbL; el Barolo, la Floralis y los dos puentes van armados a mano con medidas aproximadas. Los datos van procesados (proyectados y empaquetados por barrio) en `datos/`.

