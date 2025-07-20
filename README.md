# Telemedicine Portal – Pagamenti Sicuri

Questo progetto mostra come integrare frontend e backend per la gestione sicura dei pagamenti nel portale di medicina sviluppato in questa repository per un hackathon: [Telemedicine-portal](https://github.com/achenio/Telemedicine-portal).

## Funzionalità

- Form grafico per pagamenti con diversi metodi (Carta, PayPal, Bonifico, Assicurazione)
- Salvataggio dei dati nel database SQLite
- Crittografia dei dati sensibili (numero carta, CVC, IBAN) con bcrypt
- Conferma visiva del pagamento all’utente

## Esempio grafica frontend

![Schermata Pagamenti dal sito](/frontend-example.jpg)

## Esempio database

![Tabella pagamenti in DB Browser](/db-example.jpg)

## Struttura

- **Frontend:** HTML/CSS/JS per la raccolta dati e invio al backend
- **Backend:** Python Flask con endpoint `/payments` e salvataggio su `utenti.db`

## Sicurezza

I dati sensibili vengono crittografati prima di essere salvati nel database, garantendo la privacy degli utenti.