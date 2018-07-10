## Funzione `length`

Restituisce il numero di caratteri in una stringa o la lunghezza di una geometria di tipo linestring.

## Variabile stringa

Restituisce il numero di caratteri contenuti in una stringa.

## Sintassi

length(_string_)

## Argomenti

* _string_ stringa della quale calcolare la lunghezza

## Esempi

* `length('hello') → 5`

![](/img/geometria/length/length1.png)

## Variabile geometria

Calcola la lunghezza di un oggetto a geometria lineare. I calcoli sono sempre _planimetrici_ nel Sistema di Riferimento Spaziale (SR) di detta geometria, e l'unità di misura della lunghezza restituita è conforme all'unità di misura del SR. Ciò differisce dal calcolo eseguito dalla funzione $length, la quale esegue calcoli _ellissoidici_ basati sull'ellissoide del progetto e sulle impostazioni delle unità di distanza.

## Sintassi

length(_geometry_)

## Esempi

* `length(geom_from_wkt('LINESTRING(0 0, 4 0)')) → 4.0`

![](/img/geometria/length/length2.png)

## nota bene

--

## osservazioni

--