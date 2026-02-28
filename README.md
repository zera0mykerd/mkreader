# 🔍 MK-Reader

**MK-Reader** è un'applicazione web "lightweight" e ultra-veloce progettata da **zMykerd** per la consultazione e la ricerca rapida all'interno di database di quiz o manuali tecnici. Grazie a un'interfaccia moderna e un motore di ricerca ottimizzato, permette di trovare risposte istantanee in grandi volumi di dati.

---

## ✨ Caratteristiche Principali

Il software è stato sviluppato con un focus particolare sull'efficienza e sull'estetica:

### 1. Motore di Ricerca Intelligente
- **Filtro Istantaneo:** Risultati aggiornati in tempo reale durante la digitazione.
- **Deduplicazione Automatica:** Il sistema raggruppa i risultati simili ed elimina i duplicati basandosi sul contenuto della descrizione, garantendo una lista pulita.
- **Ordinamento Avanzato:** I risultati sono ordinati alfabeticamente ignorando prefissi comuni, facilitando la navigazione logica.
- **Limite Risultati:** Per mantenere alte le prestazioni, vengono mostrati i primi 25 risultati più rilevanti, con un contatore per le corrispondenze totali.

### 2. Gestione Database Multipli
- **Selettore Integrato:** Possibilità di passare da un database all'altro (es. diversi manuali o categorie di quiz) tramite un'interfaccia a pulsanti radio stilizzata.
- **Caricamento Asincrono:** I dati vengono caricati via `fetch` solo quando necessario, ottimizzando il consumo di memoria.

### 3. Design e Interfaccia Utente (UI)
- **Tema Cyber-Dark:** Un'estetica curata basata su toni scuri e accenti blu/lavanda per ridurre l'affaticamento visivo.
- **Effetti Dinamici:** Logo interattivo con animazione "bounce & rotate" al passaggio del mouse.
- **Scrollbar Personalizzata:** UI coerente in ogni dettaglio, incluse le barre di scorrimento stilizzate.
- **Design Full Responsive:** Utilizzabile senza problemi su desktop, tablet e smartphone.

### 4. Sicurezza e Ottimizzazione
- **Force HTTPS Supreme:** Uno script integrato che reindirizza automaticamente alla connessione sicura HTTPS (escludendo gli ambienti di sviluppo locale).
- **Sanitizzazione Input:** Protezione contro attacchi XSS tramite l'escaping automatico dei caratteri HTML nei risultati della ricerca.

---

## 🛠️ Stack Tecnologico

Il progetto è una "Single Page Application" (SPA) che non richiede installazione o server complessi:
- **HTML5 & CSS3:** Utilizzo di animazioni @keyframes e variabili CSS per la gestione dei temi.
- **Vanilla JavaScript (ES6+):** Logica pura senza dipendenze esterne per una velocità di esecuzione massima.
- **JSON Data:** I database vengono letti in formato JSON, rendendo il software estremamente facile da aggiornare.

---

## 🚀 Come Utilizzarlo

1. Clona il repository o scarica il file `mkreader.html`.
2. Assicurati di avere i file database (es. `manuale_quiz.json`) nella stessa cartella o nel percorso configurato.
3. Apri `mkreader.html` nel tuo browser preferito.
4. Digita ciò che cerchi nella barra di ricerca e seleziona il database desiderato.

---

## 📂 Struttura File

- `mkreader.html`: Contiene l'intera interfaccia, gli stili e la logica di ricerca.
- `*.json`: File esterni contenenti le coppie "Descrizione" ed "Esito".

---

## 🤝 Contributi e Open Source

Questo progetto è **Open Source** creato da **zMykerd**. 
Se vuoi contribuire:
- Apri una Issue per segnalare bug.
- Invia una Pull Request con nuove funzionalità o database pre-configurati.

---

## 👤 Autore

Creato da **zMykerd** - *Sviluppato per rendere lo studio e la consultazione più rapidi e piacevoli.*

---

## 📄 Licenza

Software distribuito sotto licenza Open Source.
