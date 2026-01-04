Chat Simulator

Descrizione

Chat Simulator è un simulatore di chat fittizia in cui tutti gli utenti sono bot.
Il sistema genera automaticamente messaggi ed eventi senza l’intervento diretto del giocatore, che può solo osservare l’evoluzione del gioco e controllarne lo stato.

Il simulatore utilizza thread per eseguire più attività in parallelo e file JSON per salvare e ripristinare lo stato del gioco.

Funzionamento

All’avvio del programma:
	•	Il gioco parte automaticamente.
	•	Due componenti lavorano in parallelo:
	•	Un thread che invia messaggi automatici nella chat.
	•	Un thread che genera eventi automatici che influenzano il gioco.

Il giocatore non può scrivere nella chat, ma solo monitorare ciò che accade.

Comandi disponibili

Durante l’esecuzione sono disponibili solo due comandi:
	•	status
Mostra lo stato attuale del gioco.
	•	exit
Termina il simulatore e salva lo stato del gioco.

Stato del gioco

Il comando status visualizza le seguenti informazioni:
	•	💰 Soldi
	•	⭐ Reputazione
	•	⏱️ Tempo di gioco
	•	💬 Messaggi recenti della chat

Salvataggio

Lo stato del gioco viene salvato in formato JSON, permettendo di riprendere la simulazione da dove era stata interrotta.

Tecnologie utilizzate
	•	Thread per la gestione di eventi e messaggi automatici
	•	JSON per il salvataggio dello stato del gioco

Obiettivo

Il progetto è pensato come simulatore osservativo, in cui il focus è sulla gestione concorrente dei processi e sulla persistenza dello stato, piuttosto che sull’interazione diretta dell’utente.
