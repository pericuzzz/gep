# Got'em
 compra le tue nuove scarpe con sicurezza e guadagna con le scarpe usate che non metti più un sito di compra/vendita di scarpe da collezione con verifica di quest'ultime
## risoluzione dei problema
### requisiti funzionali 
1.  sopperire alla mancanza di siti che si occupano di compra vendita di scarpe da collezione usate
2.  sopperire al fatto che siti più grandi di compra/vendita di scarpe non autenticano più le scarpe   
3.  sopperire al fatto che su molti siti non è possibile valutare il venditore
### requisiti non funzionali 
1.  riuscire ad avere delle spedizioni con controllo in magazzino sotto i 5 giorni lavorativi  
2.  avere un database con piu di 2000 modelli  
3.  imporsi sul mercato come un sito sicuro da cui comprare
4.  rispettare le norme del GDPR 
## casi d'uso
### utente registrato
1. ricerca di un paglio di scarpe
2. inserire le scarpe in vendita
3. acquistare le scarpe 
4. recensire il venditore
5. contratare per riuscire ad vendere/acquistastare la scarpa
### utente non registarto
1. può accedere al suo profilo
2. può creare un profilo
3. dare una ricerca sul sito  
### sistema bancario 
1. acquistare una scarpa
### amministrazione di sistema 
1. controllare la verificata delle scarpe
2. veridicita delle recensione
3. manutenzione

![diagramma uml](https://yuml.me/diagram/scruffy/usecase/[utente%20non%20registrato]-(registrazione),%20[utente%20non%20registrato]-(accedi),%20[utente%20non%20registrato]-(ricerca),%20[utente%20registrato]-(ricerca),%20[utente%20registrato]-(acquista/vendi),%20[utente%20registrato]-(contratta),%20(contratta)%3C(acquista/vendi),%20[sistema%20bancario]-(acquista/vendi),%20[amministrazione%20di%20sistema]-(controllo),%20(acquista/vendi)%3E(controllo),%20[amministrazione%20di%20sistema]-(manutenzione),%20[utente%20registrato]-(recensione),%20(recensione)%5E(verifica),%20[amministrazione%20di%20sistema]-(verifica),)

