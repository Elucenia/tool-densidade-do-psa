<!-- ELUCENIA technical documentation · densidade-do-psa · es · no clinical/professional/rights approval -->

# Densidad del PSA

[condiciones, fuentes y permisos](https://elucenia.org/es/herramientas/densidade-do-psa)

## Cómo usar

Utilice la herramienta en el portal o abra index.html mediante un servidor HTTP local. Seleccione el idioma, complete los campos y calcule.

## Entradas y unidades

### PSA total

`psa`

ng/mL · intervalo: 0,1–1000

### Volumen prostático (ecografía transrectal o RM)

`vol`

mL (cm³) · intervalo: 5–400

## Edición del método

Densidad PSA/Benson 1992: PSA/volumen, ng/mL/cm³; sin corte universal supuesto

## Fórmula documentada

Densidad del PSA (ng/mL/cm³) = PSA total ÷ volumen prostático.

Si solo tiene las tres dimensiones de la próstata, calcule primero el volumen prostático.

## Límites y población

Benson 1992 estudió la densidad de PSA en hombres, con volumen prostático por ecografía transrectal y PSA intermedio de 4,1–10 ng/mL mediante el ensayo Hybritech. El artículo describe nomogramas de riesgo; el valor PSA/volumen aislado no constituye un diagnóstico ni establece un punto de corte universal. Deben considerarse el método de volumen, el ensayo de PSA y la población de aplicación.

## Referencias

- [Benson MC et al. The use of prostate specific antigen density to enhance the predictive value of intermediate levels of serum prostate specific antigen. J Urol, 1992.](https://doi.org/10.1016/S0022-5347(17)37394-9)

- [Nordström T et al. Prostate-specific antigen (PSA) density in the diagnostic algorithm of prostate cancer. Prostate Cancer Prostatic Dis, 2018.](https://doi.org/10.1038/s41391-017-0024-7)

## Reproducir las pruebas técnicas

Ejecute node test.cjs en el directorio raíz de este repositorio para repetir los casos sintéticos registrados. Se conservan las entradas, los resultados esperados y las tolerancias originales. Las pruebas técnicas no constituyen validación clínica.

```sh
node test.cjs
```

tool.json contiene las fuentes, la edición y el alcance de la revisión. examples.json conserva las entradas y los resultados esperados de los casos sintéticos; results.json registra los resultados obtenidos.

[Ficha y referencias](../tool.json) · [Código JavaScript](../calculator.js) · [Casos de referencia](../examples.json) · [results.json](../results.json)

## Revisión y condiciones de uso

No se ha realizado una revisión clínica independiente.

Esta interfaz es una traducción de elaboración propia, no una edición oficial o certificada. No se han realizado la revisión clínica independiente, la revisión lingüística profesional ni la autorización de derechos de los instrumentos.

Resultado de la fórmula o clasificación. La interpretación, la conducta y la aplicabilidad dependen de la evaluación profesional y de la fuente seleccionada.

## Licencia y atribución

Apache-2.0 se aplica únicamente al código de ELUCENIA. Los derechos de los instrumentos, publicaciones, traducciones y datos permanecen en manos de sus respectivos titulares. Conserve LICENSE y NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Resultados documentados

La información siguiente conserva las salidas del método para ejemplos sintéticos. No constituye una validación clínica independiente.

### 1

Densidad < 0,10: menor probabilidad de cáncer clínicamente significativo


### 2

Densidad entre 0,10 y 0,15: zona intermedia


### 3

Densidad ≥ 0,15: por encima del umbral clásico, favorece la investigación de cáncer

