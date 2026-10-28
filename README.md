# To-Do List in Vanilla JavaScript

Applicazione To-Do List in JavaScript puro (Vite), con architettura a tre pilastri: **stato**, **azioni**, **view** (`View = f(State)`).

## Funzioni

- aggiungere un task (pulsante o Invio)
- completare / riaprire un task con un click
- eliminare un task con il pulsante ×
- contatore di totali e completati
- persistenza dei dati con `localStorage`

## Avvio

```bash
npm install
npm run dev
```

Poi apri l'indirizzo mostrato nel terminale (di solito `http://localhost:5173`).

## Struttura

```
index.html
src/
  main.js    # stato, view, azioni, eventi, persistenza
  style.css
```
