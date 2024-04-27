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
#### Utente Registrato:
1. Come utente registrato, voglio poter cercare un paio di scarpe per marca, taglia o modello, così da trovare facilmente ciò che desidero.
2. Come utente registrato, desidero poter inserire le scarpe che voglio vendere, fornendo tutte le informazioni necessarie sulle stesse.
3. Come utente registrato, voglio poter acquistare le scarpe desiderate in modo semplice e veloce.
4. Come utente registrato, desidero poter recensire il venditore con cui ho effettuato un acquisto, assegnando un punteggio e fornendo feedback sulla mia esperienza.
5. Come utente registrato, desidero poter contrattare il prezzo delle scarpe con il venditore, per ottenere un accordo vantaggioso per entrambe le parti.

#### Utente Non Registrato:
1. Come utente non registrato, desidero poter registrare un account sul sito per accedere a tutte le funzionalità offerte.
2. Come utente non registrato, voglio poter accedere al mio profilo una volta registrato, per gestire le mie informazioni e le mie attività sul sito.
3. Come utente non registrato, voglio poter cercare un paio di scarpe per marca, taglia o modello, così da esplorare l'ampia selezione disponibile.

![diagramma uml]<img src="http://yuml.me/diagram/scruffy/usecase/[Utente Non Registrato]-(Registrazione),[Utente Non Registrato]-(Accedi),[Utente Non Registrato]-(Ricerca),[Utente Registrato]-(Ricerca),(Ricerca)<(Acquista/Vendi),[Utente Registrato]-(Contratta),(Contratta)<(Acquista/Vendi),[Utente Registrato]-(Recensione)]" >

### WBS (Work Breakdown Structure):

1. Analisi dei requisiti
   - Definizione dei requisiti funzionali, non funzionali e di dominio
   - Identificazione delle user stories
   
2. Progettazione
   - Progettazione dell'architettura del sistema
   - Progettazione dell'interfaccia utente
   - Progettazione del database

3. Sviluppo
   - Implementazione delle funzionalità di ricerca e visualizzazione delle scarpe
   - Implementazione del sistema di autenticazione e gestione degli account utente
   - Implementazione del sistema di vendita e acquisto delle scarpe
   - Implementazione del sistema di recensione dei venditori
   - Implementazione del sistema di contrattazione dei prezzi
   
4. Test e QA
   - Testing delle funzionalità del sito
   - Verifica della sicurezza e delle prestazioni del sistema
   - Risoluzione dei bug e ottimizzazione del codice
   
5. Lancio e Deployment
   - Preparazione per il lancio del sito
   - Deployment del sito sul server Linux con database MySQL
   - Monitoraggio post-lancio e gestione dei feedback degli utenti

