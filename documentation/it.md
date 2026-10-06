<!-- ELUCENIA technical documentation · densidade-do-psa · it · no clinical/professional/rights approval -->

# Densità del PSA

[condizioni, fonti e autorizzazioni](https://elucenia.org/it/strumenti/densidade-do-psa)

## Come usare

Usi lo strumento nel portale oppure apra index.html tramite un server HTTP locale. Selezioni la lingua, compili i campi ed esegua il calcolo.

## Dati di ingresso e unità

### PSA totale

`psa`

ng/mL · intervallo: 0,1–1000

### Volume prostatico (ecografia transrettale o RM)

`vol`

mL (cm³) · intervallo: 5–400

## Edizione del metodo

Densità PSA/Benson 1992: PSA/volume, ng/mL/cm³; nessuna soglia universale presunta

## Formula documentata

Densità del PSA (ng/mL/cm³) = PSA totale ÷ volume prostatico.

Se sono disponibili solo le tre dimensioni della prostata, calcolare prima il volume prostatico.

## Limiti e popolazione

Benson 1992 ha studiato la densità del PSA negli uomini, con volume prostatico mediante ecografia transrettale e PSA intermedio di 4,1–10 ng/mL con il dosaggio Hybritech. L’articolo descrive nomogrammi di rischio; il solo valore PSA/volume non costituisce una diagnosi né stabilisce una soglia universale. Occorre considerare il metodo di misurazione del volume, il dosaggio del PSA e la popolazione di applicazione.

## Riferimenti

- [Benson MC et al. The use of prostate specific antigen density to enhance the predictive value of intermediate levels of serum prostate specific antigen. J Urol, 1992.](https://doi.org/10.1016/S0022-5347(17)37394-9)

- [Nordström T et al. Prostate-specific antigen (PSA) density in the diagnostic algorithm of prostate cancer. Prostate Cancer Prostatic Dis, 2018.](https://doi.org/10.1038/s41391-017-0024-7)

## Riprodurre i test tecnici

Esegua node test.cjs nella cartella principale di questo repository per ripetere i casi sintetici registrati. Gli input, i risultati attesi e le tolleranze originali sono conservati. I test tecnici non costituiscono validazione clinica.

```sh
node test.cjs
```

tool.json contiene le fonti, l’edizione e l’ambito della revisione. examples.json conserva gli input e i risultati attesi dei casi sintetici; results.json registra i risultati ottenuti.

[Scheda e riferimenti](../tool.json) · [Codice JavaScript](../calculator.js) · [Casi di riferimento](../examples.json) · [results.json](../results.json)

## Revisione e condizioni d’uso

Non è stata effettuata una revisione clinica indipendente.

Questa interfaccia è una traduzione realizzata dagli autori, non un’edizione ufficiale o certificata. Non sono state eseguite la revisione clinica indipendente, la revisione linguistica professionale né la verifica delle autorizzazioni relative ai diritti sugli strumenti.

Risultato della formula o classificazione. Interpretazione, condotta e applicabilità dipendono dalla valutazione professionale e dalla fonte selezionata.

## Licenza e attribuzione

Apache-2.0 si applica solo al codice di ELUCENIA. I diritti su strumenti, pubblicazioni, traduzioni e dati restano ai rispettivi titolari. Conservi LICENSE e NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Risultati documentati

Le informazioni seguenti conservano gli output del metodo per esempi sintetici. Non costituiscono una validazione clinica indipendente.

### 1

Densità < 0,10: minore probabilità di cancro clinicamente significativo


### 2

Densità tra 0,10 e 0,15: zona intermedia


### 3

Densità ≥ 0,15: al di sopra della soglia classica, favorisce l’indagine per cancro

