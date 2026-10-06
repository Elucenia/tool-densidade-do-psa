<!-- ELUCENIA technical documentation · densidade-do-psa · en · no clinical/professional/rights approval -->

# PSA density

[conditions, sources and permissions](https://elucenia.org/en/tools/densidade-do-psa)

## How to use

Use the tool in the portal or open index.html through a local HTTP server. Select the language, complete the fields and calculate.

## Inputs and units

### Total PSA

`psa`

ng/mL · range: 0.1–1000

### Prostate volume (transrectal ultrasound or MRI)

`vol`

mL (cm³) · range: 5–400

## Method edition

PSA density/Benson 1992: PSA/volume, ng/mL/cm³; no universal cutoff assumed

## Documented formula

PSA density (ng/mL/cm³) = total PSA ÷ prostate volume.

If only the three prostate dimensions are available, calculate prostate volume first.

## Limits and population

Benson 1992 studied PSA density in men, with prostate volume measured by transrectal ultrasound and intermediate PSA of 4.1–10 ng/mL using the Hybritech assay. The article describes risk nomograms; PSA/volume alone is not a diagnosis and does not establish a universal cutoff. The volume method, PSA assay and population of application must be considered.

## References

- [Benson MC et al. The use of prostate specific antigen density to enhance the predictive value of intermediate levels of serum prostate specific antigen. J Urol, 1992.](https://doi.org/10.1016/S0022-5347(17)37394-9)

- [Nordström T et al. Prostate-specific antigen (PSA) density in the diagnostic algorithm of prostate cancer. Prostate Cancer Prostatic Dis, 2018.](https://doi.org/10.1038/s41391-017-0024-7)

## Reproduce the technical tests

Run node test.cjs in the root directory of this repository to repeat the recorded synthetic cases. Original inputs, expectations and tolerances are preserved. Technical tests do not constitute clinical validation.

```sh
node test.cjs
```

tool.json contains sources, edition and review scope. examples.json retains synthetic inputs and expectations; results.json records the obtained results.

[Record and references](../tool.json) · [JavaScript code](../calculator.js) · [Reference cases](../examples.json) · [results.json](../results.json)

## Review and conditions of use

Independent clinical review has not been performed.

This interface is an authorial translation, not an official or certified edition. Independent clinical review, professional language review and instrument rights clearance have not been performed.

Formula or classification result. Interpretation, care and applicability depend on professional assessment and the selected source.

## License and attribution

Apache-2.0 applies only to ELUCENIA code. Rights to instruments, publications, translations and data remain with their respective holders. Preserve LICENSE and NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Documented results

The information below preserves the method outputs for synthetic examples. It does not constitute independent clinical validation.

### 1

Density < 0,10: lower probability of clinically significant cancer


### 2

Density between 0,10 and 0,15: intermediate zone


### 3

Density ≥ 0,15: above the classic threshold, favors cancer investigation

