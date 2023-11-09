# Got'em
 compra le tue nuove scarpe con sicurezza e guadagna con le scarpe usate che non metti più un sito di compra/vendita di scarpe da collezione con verifica di quest'ultime
## risoluzione dei problema
### requisiti funzionali 
1.Il sito deve offrire un'ampia selezione di scarpe da collezione usate disponibili per l'acquisto e la vendita.

2.Il sito deve fornire un sistema di autenticazione affidabile per verificare l'autenticità delle scarpe da collezione usate.

3.Il sito deve consentire agli utenti di valutare e recensire i venditori, fornendo un sistema di valutazione trasparente e affidabile.

4.Il sito deve garantire la sicurezza delle transazioni e la protezione dei dati personali degli utenti.

5.Il sito deve offrire una piattaforma user-friendly e intuitiva, che faciliti la ricerca, la comparazione e l'acquisto delle scarpe da collezione usate.

6.Il sito deve fornire informazioni dettagliate sulle condizioni delle scarpe e sulle caratteristiche specifiche, come la marca, la taglia, il modello e l'anno di produzione.

7.Il sito deve consentire agli utenti di mettere in vendita le proprie scarpe da collezione usate in modo semplice e veloce, fornendo una procedura chiara e diretta.

8.Il sito deve garantire un prezzo equo per le scarpe da collezione usate, basato sul valore di mercato e sulle condizioni effettive delle calzature.

Il sito deve promuovere la cultura delle scarpe da collezione usate attraverso contenuti educativi, consigli di manutenzione e informazioni sulle ultime tendenze nel settore.
### requisiti non funzionali 
1.  riuscire ad avere delle spedizioni con controllo in magazzino sotto i 5 giorni lavorativi  
2.  avere un database con piu di 2000 modelli  
3.  imporsi sul mercato come un sito sicuro da cui comprare
4.  rispettare le norme del GDPR 
## casi d'uso
### utente registrato
1. ricerca di un paglio di scarpe (la ricerca è effetuata per prodotto)
2. inserire le scarpe in vendita
3. acquistare le scarpe 
4. recensire il venditore (valutare il vendiditore tramita delle stelle, bisogno di come si e trovato a contratare con il venditore e come si è comportato)
5. contratare per riuscire ad vendere/acquistastare la scarpa
### utente non registarto
1. può accedere al suo profilo
2. può creare un profilo
3. dare una ricerca sul sito  (la ricerca è effetuata per prodotto)
### sistema bancario 
1. acquistare una scarpa
### amministrazione di sistema 
1. controllare la verificata delle scarpe
2. veridicita delle recensione
3. manutenzione

![diagramma uml](https://yuml.me/diagram/scruffy/usecase/[utente%20non%20registrato]-(registrazione),%20[utente%20non%20registrato]-(accedi),%20[utente%20non%20registrato]-(ricerca),%20[utente%20registrato]-(ricerca),%20[utente%20registrato]-(acquista/vendi),%20[utente%20registrato]-(contratta),%20(contratta)%3C(acquista/vendi),%20[sistema%20bancario]-(acquista/vendi),%20[amministrazione%20di%20sistema]-(controllo),%20(acquista/vendi)%3E(controllo),%20[amministrazione%20di%20sistema]-(manutenzione),%20[utente%20registrato]-(recensione),%20(recensione)%5E(verifica),%20[amministrazione%20di%20sistema]-(verifica),)

