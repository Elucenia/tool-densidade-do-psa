<!-- ELUCENIA technical documentation · densidade-do-psa · pt-BR · no clinical/professional/rights approval -->

# Densidade do PSA

[condições, fontes e permissões](https://elucenia.org/pt-br/ferramentas/densidade-do-psa)

## Como usar

Use a ferramenta no portal ou abra index.html em um servidor HTTP local. Selecione o idioma, preencha os campos e calcule.

## Entradas e unidades

### PSA total

`psa`

ng/mL · intervalo: 0,1–1000

### Volume prostático (USG transretal ou RM)

`vol`

mL (cm³) · intervalo: 5–400

## Edição do método

PSAdensidade/Benson 1992:PSA/volume, ng/m L/cm³; sem assumir ponto decorte universal

## Fórmula documentada

Densidade do PSA (ng/mL/cm³) = PSA total ÷ volume prostático.

Se tiver apenas as três medidas da próstata, calcule antes o volume prostático.

## Limites e população

Benson 1992 estudou densidade de PSA em homens, com volume prostático por ultrassom transretal e PSA intermediário de 4,1–10 ng/mL pelo ensaio Hybritech. O artigo descreve nomogramas de risco; o valor PSA/volume isolado não constitui diagnóstico nem estabelece um corte universal. Método de volume, ensaio de PSA e população de aplicação devem ser considerados.

## Referências

- [Benson MC et al. The use of prostate specific antigen density to enhance the predictive value of intermediate levels of serum prostate specific antigen. J Urol, 1992.](https://doi.org/10.1016/S0022-5347(17)37394-9)

- [Nordström T et al. Prostate-specific antigen (PSA) density in the diagnostic algorithm of prostate cancer. Prostate Cancer Prostatic Dis, 2018.](https://doi.org/10.1038/s41391-017-0024-7)

## Reproduzir os testes técnicos

Execute node test.cjs na pasta raiz deste repositório para repetir os casos sintéticos registrados. As entradas, expectativas e tolerâncias originais são preservadas. Testes técnicos não constituem validação clínica.

```sh
node test.cjs
```

tool.json contém fontes, edição e escopo de revisão. examples.json conserva as entradas e expectativas sintéticas; results.json registra os resultados obtidos.

[Ficha e referências](../tool.json) · [Código JavaScript](../calculator.js) · [Casos de referência](../examples.json) · [results.json](../results.json)

## Revisão e condições de uso

Revisão clínica independente não realizada.

Esta interface é uma tradução autoral, não uma edição oficial ou certificada. Revisão clínica independente, revisão linguística profissional e autorização de direitos de instrumentos não foram realizadas.

Resultado da fórmula ou classificação. Interpretação, conduta e aplicabilidade dependem da avaliação profissional e da fonte selecionada.

## Licença e atribuição

Apache-2.0 aplica-se somente ao código da ELUCENIA. Os instrumentos, publicações, traduções e dados mantêm os direitos dos respectivos titulares. Preserve LICENSE e NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Resultados documentados

As informações abaixo preservam as saídas do método para exemplos sintéticos. Não constituem validação clínica independente.

### 1

Densidade < 0,10: menor probabilidade de câncer clinicamente significativo


### 2

Densidade entre 0,10 e 0,15: zona intermediária


### 3

Densidade ≥ 0,15: acima do limiar clássico, favorece investigação de câncer

