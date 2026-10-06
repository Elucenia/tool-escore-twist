<!-- ELUCENIA technical documentation · escore-twist · de · no clinical/professional/rights approval -->

# TWIST-Score (Hodentorsion)

[Bedingungen, Quellen und Berechtigungen](https://elucenia.org/de/werkzeuge/escore-twist)

## Verwendung

Verwenden Sie das Werkzeug im Portal oder öffnen Sie index.html über einen lokalen HTTP-Server. Wählen Sie die Sprache, füllen Sie die Felder aus und berechnen Sie das Ergebnis.

## Eingaben und Einheiten

### Hodenvergrößerung (Schwellung)

`edema`

### Verhärteter Hoden

`duro`

### Fehlender Kremasterreflex

`cremaster`

### Übelkeit oder Erbrechen

`nausea`

### Hochstehender Hoden

`alto`

## Fassung der Methode

TWIST/Barbosa 2013: 5 gewichtete Faktoren, Gesamt 0–7

## Dokumentierte Formel

2 Punkte: Hodenschwellung; harter Hoden. 1 Punkt: fehlender Kremasterreflex; Übelkeit/Erbrechen; Hodenhochstand. Gesamt 0 bis 7.

## Grenzen und Population

TWIST 2013 wurde ursprünglich bei Kindern mit akutem Skrotum entwickelt, mit urologischer Untersuchung und Ultraschall bei allen 338 Patienten der prospektiven Kohorte. Die Schwellen 2 und 5 wurden auch retrospektiv geprüft; die Autoren forderten weiterhin prospektive Validierung. Diese Ergebnisse garantieren bei einer Person keine Torsionsfreiheit und ersetzen nicht die dringende Beurteilung eines möglichen chirurgischen Notfalls.

## Referenzen

- [Barbosa JA et al. Development and initial validation of a scoring system to diagnose testicular torsion in children. J Urol, 2013.](https://doi.org/10.1016/j.juro.2012.10.056)

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

## Dokumentierte Ergebnisse

Die folgenden Angaben bewahren die Ausgaben der Methode für synthetische Beispiele. Sie stellen keine unabhängige klinische Validierung dar.

### 1

Niedriges Risiko (0 bis 2): Torsion unwahrscheinlich

In der Ableitung betrug der negative prädiktive Wert 100 %: Eine dringliche Sonographie ist nicht erforderlich, wenn das klinische Bild übereinstimmt.


### 2

Mittleres Risiko (3 bis 4)

Dringende Doppler-Ultraschalluntersuchung, ohne die Exploration bei Unklarheit zu verzögern.


### 3

Hohes Risiko (5 bis 7): sofortige chirurgische Exploration

In der Ableitung ein positiver prädiktiver Wert von 100 %: die Operation nicht durch Bildgebung verzögern.


### 4

Hohes Risiko (5 bis 7): sofortige chirurgische Exploration

In der Ableitung ein positiver prädiktiver Wert von 100 %: die Operation nicht durch Bildgebung verzögern.

