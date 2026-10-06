<!-- ELUCENIA technical documentation · escore-twist · it · no clinical/professional/rights approval -->

# Punteggio TWIST (torsione testicolare)

[condizioni, fonti e autorizzazioni](https://elucenia.org/it/strumenti/escore-twist)

## Come usare

Usi lo strumento nel portale oppure apra index.html tramite un server HTTP locale. Selezioni la lingua, compili i campi ed esegua il calcolo.

## Dati di ingresso e unità

### Aumento di volume (edema) del testicolo

`edema`

### Testicolo indurito

`duro`

### Riflesso cremasterico assente

`cremaster`

### Nausea o vomito

`nausea`

### Testicolo risalito (alto nello scroto)

`alto`

## Edizione del metodo

TWIST/Barbosa 2013: 5 fattori ponderati, totale 0–7

## Formula documentata

2 punti: edema testicolare; testicolo duro. 1 punto: riflesso cremasterico assente; nausea/vomito; testicolo sollevato. Totale da 0 a 7.

## Limiti e popolazione

Il TWIST 2013 è stato inizialmente sviluppato in bambini con scroto acuto, con esame da parte di un urologo ed ecografia in tutti i 338 pazienti della coorte prospettica. Le soglie 2 e 5 sono state valutate anche retrospettivamente; gli autori richiedevano ancora una validazione prospettica. Questi risultati non garantiscono l’assenza di torsione in una persona né sostituiscono la valutazione urgente di una possibile emergenza chirurgica.

## Riferimenti

- [Barbosa JA et al. Development and initial validation of a scoring system to diagnose testicular torsion in children. J Urol, 2013.](https://doi.org/10.1016/j.juro.2012.10.056)

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

Rischio basso (0 a 2): torsione improbabile

Nella derivazione, valore predittivo negativo del 100%: l'ecografia urgente non è necessaria se il quadro clinico è concordante.


### 2

Rischio intermedio (3 a 4)

Ecografia Doppler urgente, senza ritardare l’esplorazione in caso di dubbio.


### 3

Rischio elevato (5 a 7): esplorazione chirurgica immediata

Nella derivazione, valore predittivo positivo del 100%: non ritardare l’intervento chirurgico per esami di imaging.


### 4

Rischio elevato (5 a 7): esplorazione chirurgica immediata

Nella derivazione, valore predittivo positivo del 100%: non ritardare l’intervento chirurgico per esami di imaging.

