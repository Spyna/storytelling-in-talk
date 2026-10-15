# Esempi S.T.O.R.I.A.

## Esempio 1 — L'intro di questa stessa skill, in due versioni

### Versione documentazione (senza S.T.O.R.I.A.)
> S.T.O.R.I.A. è un framework di storytelling composto da sei elementi: Someone, Tensione, Ostacolo, Rischio, Intervento e Aspettative. Il framework permette di strutturare la narrazione di un talk tecnico, evitando l'effetto "documentazione letta ad alta voce". Di seguito la spiegazione dei sei elementi, con esempi applicati al mondo dello sviluppo.

### Versione raccontata (con S.T.O.R.I.A.)
- **S**: Sei uno sviluppatore con un talk in scadenza.
- **T**: Hai un sospetto che non ti lascia dormire: manca qualcosa.
- **O**: La modalità documentazione: spieghi, illustri, elenchi.
- **R**: Quaranta minuti della vita di cento persone, e la tua idea che non arriva da nessuno.
- **I**: S.T.O.R.I.A.: sei lettere per trasformare un argomento in una narrazione, prima delle slide.
- **A**: Il talk che la gente racconta ancora al caffè, tre giorni dopo.

Stesso contenuto, stessa lunghezza: ma la seconda ti ha dato qualcuno da seguire (te stesso), un problema che è tuo, un rischio che hai già vissuto — e un motivo per arrivare fino in fondo.

## Esempio 2 — Un talk tecnico reale: OCR in Go con Ollama

Tema: sviluppare applicazioni OCR in Go integrando modelli AI multimodali tramite Ollama, live coding incluso.

### Senza storytelling
> **OCR in Go con Ollama: technical deep dive**
> In questo talk esploreremo lo sviluppo di applicazioni OCR in Go attraverso l'integrazione di modelli AI multimodali tramite Ollama. Vedremo un confronto tra i modelli vision open source, le opzioni di esecuzione locale e cloud, e le differenze tra API generate e chat. L'esposizione includerà esempi pratici e live coding per la realizzazione di strumenti concreti.

### Con storytelling
Titolo: **La fattura che nessuno vuole rileggere**

- **S**: Giulia gestisce l'amministrazione di una piccola azienda: ogni mese, quattrocento fatture cartacee da trascrivere a mano.
- **T**: Due ore al giorno davanti allo scanner, gli occhi che bruciano, e la sensazione che il suo tempo valga più di così.
- **O**: Gli strumenti OCR "di sempre": licenze care, errori di formatazione continui, e il timore che un'AI non ce la faccia con i documenti italiani.
- **R**: Se non risolve, ogni trimestre il backlog cresce, e con lui il rischio di perderne una davvero importante.
- **I**: Ecco dove entriamo noi: modelli vision open source in Go, eseguiti in locale con Ollama. Il tuo laptop diventa il motore OCR.
- **A**: Live coding: in venti minuti costruiamo insieme lo strumento che porta le quattrocento fatture di Giulia da due settimane a due ore, e le restituisce il pomeriggio.

Stesso contenuto tecnico (modelli multimodali, Ollama, API generate vs chat, esecuzione locale o cloud, live coding): ma la versione raccontata ha una persona, una tensione, un ostacolo con un nome e un rischio concreto — e per questo la stanza aspetta il live coding invece di controllare l'orario.

## Esempio 3 — Il test della stretta allo stomaco (correzione)

Input utente: *"Ho questo talk su observability ma non emoziona. Ho scritto: 'Parleremo di come monitorare sistemi distribuiti con OpenTelemetry, tracing distribuito e metriche, con esempi pratici e una demo finale.'"*

Audit:
- **S — BUCO**: nessuna persona; il soggetto è "sistemi distribuiti" (una cosa).
- **T — BUCO**: nessuna emozione sotto il problema.
- **O — DEBOLE**: c'è implicitamente (i sistemi difficili da debuggare) ma il villano non ha nome.
- **R — BUCO**: nessuna conseguenza concreta.
- **I — OK**: OpenTelemetry è la spada giusta, ma arriva prima che il villano abbia un nome.
- **A — BUCO**: finisce sulla demo, non sulla vita dopo.

Domande da porre (una sola tornata):
1. Chi è la persona che vive questo problema nel peggiore dei giorni? Come si chiama, cosa fa alle 2 di notte?
2. Cosa prova, in quel momento, in concreto?
3. Cosa glielo impedisce oggi, esattamente? Come si chiama il villano?
4. Cosa perde se non risolve — in weekend, soldi, fiducia?
5. Com'è la sua vita una volta risolto? Cosa cambia il lunedì dopo?

Test: scritte S, T e O insieme, devono stringere lo stomaco. Se non lo fanno, cambiare persona o ostacolo — il resto del talk sta in piedi su quelle tre.
