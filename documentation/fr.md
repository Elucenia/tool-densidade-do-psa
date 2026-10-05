<!-- ELUCENIA technical documentation · densidade-do-psa · fr · no clinical/professional/rights approval -->

# Densité du PSA

[conditions, sources et autorisations](https://elucenia.org/fr/outils/densidade-do-psa)

## Mode d’emploi

Utilisez l’outil sur le portail ou ouvrez index.html via un serveur HTTP local. Sélectionnez la langue, remplissez les champs et lancez le calcul.

## Données d’entrée et unités

### PSA total

`psa`

ng/mL · intervalle: 0,1–1000

### Volume prostatique (échographie transrectale ou IRM)

`vol`

mL (cm³) · intervalle: 5–400

## Édition de la méthode

Densité PSA/Benson 1992 : PSA/volume, ng/mL/cm³ ; sans seuil universel présumé

## Formule documentée

Densité du PSA (ng/mL/cm³) = PSA total ÷ volume prostatique.

Si seules les trois dimensions de la prostate sont disponibles, calculez d’abord le volume prostatique.

## Limites et population

Benson 1992 a étudié la densité du PSA chez des hommes, avec le volume prostatique mesuré par échographie transrectale et un PSA intermédiaire de 4,1–10 ng/mL au dosage Hybritech. L’article décrit des nomogrammes de risque ; la valeur PSA/volume seule ne pose pas un diagnostic ni un seuil universel. La méthode de mesure du volume, le dosage du PSA et la population d’application doivent être pris en compte.

## Références

- [Benson MC et al. The use of prostate specific antigen density to enhance the predictive value of intermediate levels of serum prostate specific antigen. J Urol, 1992.](https://doi.org/10.1016/S0022-5347(17)37394-9)

- [Nordström T et al. Prostate-specific antigen (PSA) density in the diagnostic algorithm of prostate cancer. Prostate Cancer Prostatic Dis, 2018.](https://doi.org/10.1038/s41391-017-0024-7)

## Reproduire les tests techniques

Exécutez node test.cjs dans le répertoire racine de ce dépôt pour reproduire les cas synthétiques enregistrés. Les données d’entrée, les résultats attendus et les tolérances d’origine sont conservés. Les tests techniques ne constituent pas une validation clinique.

```sh
node test.cjs
```

tool.json contient les sources, l’édition et le périmètre de la revue. examples.json conserve les données d’entrée et les résultats attendus des cas synthétiques ; results.json consigne les résultats obtenus.

[Fiche et références](../tool.json) · [Code JavaScript](../calculator.js) · [Cas de référence](../examples.json) · [results.json](../results.json)

## Revue et conditions d’utilisation

Aucune révision clinique indépendante n’a été effectuée.

Cette interface est une traduction réalisée par nos soins, et non une édition officielle ou certifiée. La revue clinique indépendante, la révision linguistique professionnelle et l’autorisation des droits sur les instruments n’ont pas été réalisées.

Résultat de la formule ou de la classification. L’interprétation, la conduite et l’applicabilité dépendent de l’évaluation professionnelle et de la source sélectionnée.

## Licence et attribution

Apache-2.0 s’applique uniquement au code d’ELUCENIA. Les droits sur les instruments, publications, traductions et données restent ceux de leurs titulaires respectifs. Conservez LICENSE et NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
