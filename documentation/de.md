<!-- ELUCENIA technical documentation · densidade-do-psa · de · no clinical/professional/rights approval -->

# PSA-Dichte

[Bedingungen, Quellen und Berechtigungen](https://elucenia.org/de/werkzeuge/densidade-do-psa)

## Verwendung

Verwenden Sie das Werkzeug im Portal oder öffnen Sie index.html über einen lokalen HTTP-Server. Wählen Sie die Sprache, füllen Sie die Felder aus und berechnen Sie das Ergebnis.

## Eingaben und Einheiten

### Gesamt-PSA

`psa`

ng/mL · Bereich: 0,1–1000

### Prostatavolumen (transrektaler Ultraschall oder MRT)

`vol`

mL (cm³) · Bereich: 5–400

## Fassung der Methode

PSA-Dichte/Benson 1992: PSA/Volumen, ng/mL/cm³; kein universeller Grenzwert angenommen

## Dokumentierte Formel

PSA-Dichte (ng/mL/cm³) = Gesamt-PSA ÷ Prostatavolumen.

Wenn nur die drei Prostatamaße vorliegen, berechnen Sie zuerst das Prostatavolumen.

## Grenzen und Population

Benson 1992 untersuchte die PSA-Dichte bei Männern mit transrektal sonografisch bestimmtem Prostatavolumen und intermediärem PSA von 4,1–10 ng/mL im Hybritech-Assay. Der Artikel beschreibt Risikonomogramme; der Wert PSA/Volumen allein stellt weder eine Diagnose noch einen universellen Schwellenwert dar. Volumenmessmethode, PSA-Assay und Anwendungspopulation müssen berücksichtigt werden.

## Referenzen

- [Benson MC et al. The use of prostate specific antigen density to enhance the predictive value of intermediate levels of serum prostate specific antigen. J Urol, 1992.](https://doi.org/10.1016/S0022-5347(17)37394-9)

- [Nordström T et al. Prostate-specific antigen (PSA) density in the diagnostic algorithm of prostate cancer. Prostate Cancer Prostatic Dis, 2018.](https://doi.org/10.1038/s41391-017-0024-7)

## Technische Tests reproduzieren

Führen Sie node test.cjs im Stammverzeichnis dieses Repositorys aus, um die dokumentierten synthetischen Fälle zu wiederholen. Ursprüngliche Eingaben, erwartete Ergebnisse und Toleranzen bleiben erhalten. Technische Tests stellen keine klinische Validierung dar.

```sh
node test.cjs
```

tool.json enthält Quellen, Ausgabe und Umfang der Überprüfung. examples.json bewahrt die synthetischen Eingaben und erwarteten Ergebnisse; results.json dokumentiert die tatsächlich erhaltenen Ergebnisse.

[Eintrag und Referenzen](../tool.json) · [JavaScript-Code](../calculator.js) · [Referenzfälle](../examples.json) · [results.json](../results.json)

## Überprüfung und Nutzungsbedingungen

Eine unabhängige klinische Prüfung wurde nicht durchgeführt.

Diese Benutzeroberfläche ist eine selbst erstellte Übersetzung und keine offizielle oder zertifizierte Ausgabe. Eine unabhängige klinische Überprüfung, eine professionelle sprachliche Prüfung und eine Klärung der Rechte an den Instrumenten wurden nicht durchgeführt.

Ergebnis der Formel oder Klassifikation. Interpretation, Vorgehen und Anwendbarkeit hängen von der fachlichen Beurteilung und der ausgewählten Quelle ab.

## Lizenz und Urheberangaben

Apache-2.0 gilt nur für den ELUCENIA-Code. Die Rechte an Instrumenten, Veröffentlichungen, Übersetzungen und Daten verbleiben bei den jeweiligen Rechteinhabern. Bewahren Sie LICENSE und NOTICE auf.

ELUCENIA · Felipe Guedes · Copyright © 2026
