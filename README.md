# Got'em
 compra le tue nuove scarpe con sicurezza e guadagna con le scarpe usate che non metti più un sito di compra/vendita di scarpe da collezione con verifica di quest'ultime
## risoluzione dei problema
### requisiti funzionali 
1. Il sito deve offrire un'ampia selezione di scarpe da collezione usate disponibili per l'acquisto e la vendita.
2. Il sito deve fornire un sistema di autenticazione affidabile per verificare l'autenticità delle scarpe da collezione usate.
3. Il sito deve consentire agli utenti di valutare e recensire i venditori, fornendo un sistema di valutazione trasparente e affidabile.
5. Il sito deve fornire informazioni dettagliate sulle condizioni delle scarpe e sulle caratteristiche specifiche, come la marca, la taglia, il modello e l'anno di produzione.
6. Il sito deve consentire agli utenti di mettere in vendita le proprie scarpe da collezione usate in modo semplice e veloce, fornendo una procedura chiara e diretta.
7. Il sito deve garantire un prezzo equo per le scarpe da collezione usate, basato sul valore di mercato e sulle condizioni effettive delle calzature.
### requisiti non funzionali 
1. Tempo di consegna: Il sistema deve essere in grado di gestire le spedizioni in modo efficiente e garantire che le consegne vengano effettuate entro 5 giorni lavorativi. Questo richiede una pianificazione e organizzazione delle spedizioni, oltre a un sistema di  
monitoraggio in tempo reale per verificare che i tempi di consegna siano rispettati.
2. Database esteso: Il sistema deve essere in grado di gestire un database con più di 2000 modelli. Ciò richiede una struttura di database solida e scalabile, in grado di gestire grandi quantità di dati senza compromettere le prestazioni del sistema. È importante anche garantire la sicurezza dei dati nel database per proteggere i modelli e le informazioni personali dei clienti.
3. Sicurezza del sito: Il sistema deve garantire un alto livello di sicurezza per instaurare la fiducia dei clienti. Ciò include la protezione dei dati personali dei clienti, l'utilizzo di connessioni sicure (HTTPS) e l'implementazione di misure di sicurezza per prevenire accessi non autorizzati al sistema o agli account dei clienti. È importante anche garantire la sicurezza dei pagamenti online per evitare frodi.
4. Conformità al GDPR: Il sistema deve rispettare le norme del GDPR (General Data Protection Regulation) per la protezione dei dati personali. Ciò include la raccolta e l'elaborazione corretta dei dati personali dei clienti, il consenso esplicito per l'uso di tali dati, la loro sicurezza e la possibilità per i clienti di richiedere l'accesso, la modifica o la cancellazione dei propri dati personali. È importante anche tenere traccia delle preferenze di consenso dei clienti riguardo all'elaborazione dei loro dati persona
### requisiti di dominio 
1. i sito di appogerà con Linux, Sarà inoltre necessario utilizzare un server MySQL per gestire il database del sito.
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

