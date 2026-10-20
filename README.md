# Regulatory Overlap Map

[![Code: Apache 2.0](https://img.shields.io/badge/code-Apache%202.0-blue.svg)](LICENSE) [![Data: CC BY 4.0](https://img.shields.io/badge/data-CC%20BY%204.0-lightgrey.svg)](LICENSE-DATA)

Un mapa interactivo de las obligaciones que imponen las normas europeas y españolas cuando un banco decide con un sistema automatizado si concede un crédito o abre una cuenta, y de cómo se relacionan entre ellas. Está centrado en la persona: separa lo que el banco hace por dentro de lo que la persona tiene derecho a pedir.

*An interactive, person-centred map of the obligations that EU and Spanish law impose when a bank uses an automated system to grant consumer credit or open an account, and of how those obligations relate to each other. Available in Spanish and English.*

**Mapa en línea →** [fernandasvilla.github.io/regulatory-overlap-map](https://fernandasvilla.github.io/regulatory-overlap-map/)  
**Calculadora en línea →** [fernandasvilla.github.io/regulatory-overlap-calculator](https://fernandasvilla.github.io/regulatory-overlap-calculator/calculadora/)

---

## Qué muestra

Cada punto es una de las 50 obligaciones de diez instrumentos normativos (el Reglamento de IA, el RGPD, la Directiva de crédito al consumo, DORA, el AMLR, la Directiva 2014/92/UE, las directrices de la EBA y la normativa española). Cada línea une dos obligaciones de normas distintas que regulan lo mismo, con su tipo de relación:

- **N**, integrada: una norma dice que cumplir una basta o que se cumplen juntas.
- **D**, misma finalidad con definición distinta.
- **I**, equivalente o compatible.
- **C**, en tensión.

Al tocar un punto o una línea aparece la explicación y el artículo de origen, y cada obligación enlaza al texto oficial de su norma (EUR-Lex, BOE o EBA). Se puede agrupar por orientación (obligaciones internas o de cara a la persona) o por decisión (crédito o alta de cuenta), y elegir el país para ver su norma nacional sobre la cuenta básica y la prevención del blanqueo.

## Cómo usarlo

Abre `index.html` en cualquier navegador. Es un solo archivo, funciona sin conexión y no guarda ni envía ningún dato.

## Datos

El mapa usa la matriz v1.2, congelada el 14 de octubre de 2026, del [Regulatory Overlap Calculator](https://github.com/FernandaSVilla/regulatory-overlap-calculator), donde están los archivos CSV y el libro de códigos.

## Licencia

El código se publica con licencia Apache 2.0 y los datos con CC BY 4.0. El archivo incluye la librería d3 (licencia ISC); ver `NOTICE`.

## Cómo citar

Este trabajo está archivado en Zenodo y tiene un DOI permanente.

> Sánchez-Villa, M. F. (2026). *Regulatory Overlap Map: person-centred map of obligations in automated credit and account-opening decisions* (Version 1.0.0) [Software]. Zenodo. https://doi.org/10.5281/zenodo.23496803

[![DOI](https://zenodo.org/badge/1422187635.svg)](https://doi.org/10.5281/zenodo.23496803)

Ese DOI es el DOI de concepto: siempre lleva a la versión más reciente. Para citar exactamente la versión 1.0.0, usa https://doi.org/10.5281/zenodo.23496804. También puedes usar el botón **«Cite this repository»** de esta página, que genera la cita en APA y BibTeX.
