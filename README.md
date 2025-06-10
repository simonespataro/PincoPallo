# Analisi Turni Operatori

Questa web app è contenuta interamente nel file `index.html` e non richiede build o dipendenze esterne.
Di seguito i passaggi per eseguirla in locale:

1. Clona questo repository:
   ```bash
   git clone <repo-url>
   cd PincoPallo
   ```
2. Avvia un semplice server HTTP (ad esempio con Python):
   ```bash
   python3 -m http.server
   ```
   In alternativa puoi usare qualsiasi altro web server.
3. Apri il browser all'indirizzo `http://localhost:8000/index.html`.

Una volta aperta l'applicazione seleziona il file CSV e premi il pulsante **Carica** per importarlo.

L'app utilizza `localStorage` per salvare i dati degli operatori e CDN pubblici per le librerie JavaScript.
