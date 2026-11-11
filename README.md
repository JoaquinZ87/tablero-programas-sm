# Intervenciones con NNoA · General San Martín

Tablero de las intervenciones de **Responsabilidades Compartidas**, **Autonomía Joven** y
**Entramados** con niñas, niños y adolescentes de General San Martín, 2021–2026 (datos al
31/10/2026).

Sitio: https://joaquinz87.github.io/tablero-programas-sm/

## Qué contiene

- `index.html`: el tablero (barras apiladas con total y desagregación, mapas de calor por
  barrio y localidad, filtros guardados en la dirección).
- `cubo.csv`: conteos agregados por programa, año, territorio, género y edad.
- `entr_espacios.csv`: espacios grupales de Entramados 2026 (taller × lugar) con encuentros y
  participantes estimados por medianas.
- `entr_individuales.csv`: NNoA con intervención individual de Entramados 2026, por barrio,
  género y edad.

Ningún archivo contiene datos personales (ni DNI, ni nombres, ni domicilios).
- `d3.v7.min.js`: biblioteca de gráficos ([d3](https://d3js.org), licencia ISC).

## Cómo se cuenta

Se cuentan intervenciones, no personas: un NNoA que está en dos programas suma dos. Dentro de
un mismo programa, cada NNoA cuenta una vez por año. Los casos ingresados en 2020 no se
cuentan. El detalle está al pie del tablero («Cómo se cuentan estos números»).

Fuente: elaboración propia sobre la planilla Base_gestion de los tres programas y la
asistencia con nombre a talleres de SIGEI. Polígonos: GeoServer de la Municipalidad de
General San Martín.

## Actualización

Los datos se regeneran a mano con `armar_datos_tablero.py` y `generar_pages.py` (fuera de
este repositorio) y se suben con un commit.
