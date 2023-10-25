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
### utente visitatore
1. registrazione di un nuovo utente
2. ricerca di un paglio di scarpe
### utente acquirente/venditore 
1. inserire le scarpe in vendita 
2. recensire il venditore
3. contratare per riuscire ad vendere/acquistastare la scarpa
### sistema bancario 
1. acquistare una scarpa
### amministrazione di sistema 
1. controllare la verificata delle scarpe
2. veridicita delle recensione
3. smistamento

![diagramma uml](https://yuml.me/diagram/scruffy/usecase/[utente]-(registrazione),(registrazione)%3E(ricerca),(registrazione)%3E(inserisce),(registrazione)%3E(contratta),(acquista)%3C(inserisce),(acquista)%3C(contratta),[sistema%20bancario]%3C(acquista),[amministrazione%20di%20sistema]%3C(acquista),[amministrazione%20di%20sistema]%3E(%20controllo),[amministrazione%20di%20sistema]%3E(smistamento),(smistamento)%3E[utente],[utente]%3E(recensione),(recensione)%3E(veridicita),(veridicita)%3C[amministrazione%20di%20sistema])

