<!-- ELUCENIA technical documentation · escore-twist · es · no clinical/professional/rights approval -->

# Puntuación TWIST (torsión testicular)

[condiciones, fuentes y permisos](https://elucenia.org/es/herramientas/escore-twist)

## Cómo usar

Utilice la herramienta en el portal o abra index.html mediante un servidor HTTP local. Seleccione el idioma, complete los campos y calcule.

## Entradas y unidades

### Aumento de volumen (edema) del testículo

`edema`

### Testículo endurecido

`duro`

### Reflejo cremastérico ausente

`cremaster`

### Náuseas o vómitos

`nausea`

### Testículo elevado (alto en el escroto)

`alto`

## Edición del método

TWIST/Barbosa 2013: 5 factores ponderados, total 0–7

## Fórmula documentada

2 puntos: edema testicular; testículo duro. 1 punto: reflejo cremastérico ausente; náuseas/vómitos; testículo elevado. Total de 0 a 7.

## Límites y población

El TWIST 2013 se desarrolló inicialmente en niños con escroto agudo, con examen por urólogo y ecografía en los 338 pacientes de la cohorte prospectiva. Los puntos de corte 2 y 5 también se evaluaron retrospectivamente; los autores aún solicitaron validación prospectiva. Estos resultados no garantizan la ausencia de torsión en una persona ni sustituyen la evaluación urgente de una posible emergencia quirúrgica.

## Referencias

- [Barbosa JA et al. Development and initial validation of a scoring system to diagnose testicular torsion in children. J Urol, 2013.](https://doi.org/10.1016/j.juro.2012.10.056)

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

Riesgo bajo (0 a 2): torsión improbable

En la derivación, valor predictivo negativo de 100%: no se requiere ultrasonografía urgente si el cuadro clínico es concordante.


### 2

Riesgo intermedio (3 a 4)

Ecografía Doppler urgente, sin retrasar la exploración si hay duda.


### 3

Alto riesgo (5 a 7): exploración quirúrgica inmediata

En la derivación, valor predictivo positivo de 100%: no retrase la cirugía por estudios de imagen.


### 4

Alto riesgo (5 a 7): exploración quirúrgica inmediata

En la derivación, valor predictivo positivo de 100%: no retrase la cirugía por estudios de imagen.

