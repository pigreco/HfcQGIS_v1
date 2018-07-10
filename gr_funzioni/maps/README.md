## Gruppo `Maps` - solo DB (es:PostGIS)

Questo gruppo contiene funzioni espressione per la creazione e la manipolazione di strutture di dati 'a mappa' (noti anche come oggetti dizionario, coppie chiave-valore o array associative). Si possono assegnare valori a determinate chiavi. L'ordine delle coppie chiave valore nell'oggetto mappa non è rilevante come per gli Arrays ([gruppo Arrays](funzioni/../arrays)).

 Funzione  | Descrizione|Plugin
----------:|:-----------|------
[hstore_to_map](funzioni/hstore_to_map.md)|Coverte hstore in map|ArrayPlus
[json_to_map](funzioni/json_to_map.md)|Converte string json in map|ArrayPlus
[map](funzioni/map.md)|Restituisce una mappa con tutte le chiavi ed i valori passati come coppie di parametri
[map_akeys](funzioni/map_akeys.md)|	Restituisce tutte le chiavi di una mappa come un array
[map_avals](funzioni/map_avals.md)|	Restituisce tutti valori di una mappa come un array
[map_concat](funzioni/map_concat.md)|Restituisce una mappa con tutte le entità della mappe fornite
[map_delete](funzioni/map_delete.md)|Restituisce una mappa con il valore della corrispondente chiave passata rimosso
[map_exist](funzioni/map_exist.md)|	Restituisce vero se la chiave passata esiste in mappa
[map_get](funzioni/map_get.md)|Restituisce il valore di una mappa, passando la sua chiave
[map_insert](funzioni/map_insert.md)|Restituisce una mappa con una chiave/valore aggiunto

![](/img/maps/gruppo_maps1.png)