# Trading Assistant

Web app mobile-first per analisi tecnica in modalità DEMO.

## Pubblicazione
Carica **tutti i file della cartella** su un hosting che serva HTTPS e poi apri l'indirizzo dal telefono.

Per installarla su iPhone: apri il sito in Safari → Condividi → **Aggiungi alla schermata Home**.

## Stato attuale
- EUR/USD, GBP/USD, USD/JPY
- timeframe selezionabile
- EMA 20/50
- RSI 14
- MACD/Signal inseriti manualmente
- supporto/resistenza
- rischio in euro
- SL/TP indicativi
- registro demo
- manifest + service worker per comportamento da PWA

## Importante
Questa versione non riceve ancora quotazioni reali e non invia ordini a MT5.

## Prossimo step tecnico
Aggiungere un backend HTTPS che recuperi dati di mercato, poi un connettore separato per MT5/demo. Non mettere mai password o credenziali MT5 nel frontend pubblico.
