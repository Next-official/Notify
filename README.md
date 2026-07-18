# **NOTIFY**

Il diario personale che trasforma i tuoi momenti quotidiani in un archivio privato, sempre a portata di mano.



**Descrizione**

Notify Diary è un'applicazione interattiva ispirata al design iOS, pensata per rendere la scrittura di un diario personale semplice, veloce e piacevole da usare. L'obiettivo è offrire uno spazio privato in cui annotare pensieri e momenti della giornata, restituendo allo stesso tempo una panoramica visiva e motivante delle proprie abitudini di scrittura.



**Caratteristiche Principali**

Il codice con cui è stata programmata l'app gestisce interamente la persistenza dei dati in locale tramite IndexedDB, senza alcun invio di informazioni a server esterni.

L'app include una schermata Insights completa, con calcolo reale di streak giornaliere e settimanali, parole scritte nel mese e nell'anno corrente, giorni diariati e un istogramma delle ultime voci — tutti valori ricalcolati dinamicamente sui dati effettivi dell'utente.

Ogni voce dispone di un menu contestuale dedicato, richiamabile dal pulsante •••, che permette di modificare, eliminare o reagire con emoji stilizzate a ciascun momento salvato.

Una barra laterale impostazioni consente di alternare tema chiaro e scuro, esportare o importare i propri dati in formato JSON e cancellare l'intero archivio in qualsiasi momento.



**Dati e Privacy**

Tutte le voci del diario, le reazioni e le preferenze (come il tema selezionato) sono salvate esclusivamente sul dispositivo dell'utente tramite IndexedDB. Nessun dato lascia il dispositivo, a meno che l'utente stesso non scelga di esportare un backup. L'app non utilizza cookie, tracciamento né connessioni a servizi terzi.



**Note Legali e Copyright**

Proprietà: il software e l'interfaccia grafica sono stati ideati e programmati da \[Nome Autore].

Questo strumento ha scopo personale ed educativo. I dati inseriti restano nella piena disponibilità dell'utente, che è l'unico responsabile della loro conservazione: si consiglia di effettuare periodicamente un backup tramite la funzione di esportazione, poiché la cancellazione dei dati del browser comporta la perdita permanente delle voci salvate.



**Approccio e Filosofia di Design**

Uno spazio privato prima di tutto: l'app nasce con l'idea che un diario debba restare un luogo sicuro e personale, motivo per cui ogni dato risiede solo sul dispositivo di chi scrive.

Motivazione tramite dati reali: mostrando streak, parole scritte e giorni diariati calcolati sui dati effettivi — e non su valori fittizi — l'app vuole incoraggiare una scrittura costante basata su progressi autentici, non su numeri di facciata.

Familiarità dell'interazione: menu contestuali, fogli scorrevoli e un linguaggio visivo coerente con le convenzioni iOS rendono l'esperienza immediata, senza bisogno di istruzioni.

