<!-- ELUCENIA technical documentation · escore-twist · en · no clinical/professional/rights approval -->

# TWIST score (testicular torsion)

[conditions, sources and permissions](https://elucenia.org/en/tools/escore-twist)

## How to use

Use the tool in the portal or open index.html through a local HTTP server. Select the language, complete the fields and calculate.

## Inputs and units

### Testicular enlargement (swelling)

`edema`

### Hard testicle

`duro`

### Absent cremasteric reflex

`cremaster`

### Nausea or vomiting

`nausea`

### High-riding testicle

`alto`

## Method edition

TWIST/Barbosa 2013: 5 weighted factors, total 0–7

## Documented formula

2 points: testicular swelling; hard testis. 1 point: absent cremasteric reflex; nausea/vomiting; high-riding testis. Total 0 to 7.

## Limits and population

TWIST 2013 was initially developed in children with acute scrotum, with examination by a urologist and ultrasound in all 338 patients of the prospective cohort. Cutoffs of 2 and 5 were also assessed retrospectively; the authors still called for prospective validation. These results do not guarantee that an individual has no torsion or replace urgent assessment of a possible surgical emergency.

## References

- [Barbosa JA et al. Development and initial validation of a scoring system to diagnose testicular torsion in children. J Urol, 2013.](https://doi.org/10.1016/j.juro.2012.10.056)

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
