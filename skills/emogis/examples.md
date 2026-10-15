# Esempipi E.M.O.G.I.S.

## Esempio 1 — L'intro di questa stessa skill, in due versioni

### Versione documentazione (senza E.M.O.G.I.S.)
> E.M.O.G.I.S. è un framework di strutturazione composto da sei elementi: Eroe, Missione, Ostacolo, Guida, Itinerario e Scopo. Il framework permette di dare una struttura narrativa a un talk tecnico prima della creazione delle slide. Di seguito la spiegazione dei sei elementi, con esempi applicati al mondo dello sviluppo software.

### Versione raccontata (con E.M.O.G.I.S.)
- **E**: Sei uno sviluppatore con un talk accettato.
- **M**: Una stanza che resta seduta fino alla fine, e che tre giorni dopo si ricorda ancora cosa gli hai detto.
- **O**: Parti dalle slide: costruisci l'elenco prima della storia.
- **G**: Un telaio vecchio come il cinema, tradotto per i talk.
- **I**: Sei lettere, in ordine, per iscritto, prima di ogni slide.
- **S**: Un talk che si sposa con la memoria di chi ti ascolta.

Stesso contenuto, stessa lunghezza: ma la seconda ti ha messo al centro della storia, con una missione riconoscibile e un itinerario da seguire.

## Esempio 2 — Un talk tecnico reale: "TDD nell'era dell'AI"

Tema: come usare lo sviluppo guidato dai test per collaborare con gli agenti AI che scrivono codice.

### Senza storytelling
> **TDD in the AI era: technical deep dive**
> In questo talk esploreremo lo sviluppo guidato dai test (TDD) applicato alla collaborazione con agenti AI. Analizzeremo il ciclo red-green-refactor nel contesto del code generation, le strategie di verifica del codice prodotto da modelli linguistici e le tecniche per mantenere la qualità del software in un workflow ibrido uomo-macchina. L'esposizione includerà esempi pratici di refactoring con AI e pattern di test.

### Con storytelling
Titolo: **Il copilota che guida troppo veloce**

- **E**: Tu, che hai portato gli strumenti di AI coding nel tuo team.
- **M**: Spedire veloce come prima, ma senza paura di ciò che c'è sotto.
- **O**: L'agente scrive codice a una velocità che non riespi più a verificare: PR lunghe, review frettolose, bug "creativi" in produzione.
- **G**: Il TDD: il volante per guidare l'AI invece di ripulire i suoi incidenti.
- **I**: Tre passi: il test che dice cosa vuoi, l'agente che lo soddisfa, il refactor che tiene il codice tuo.
- **S**: Puoi anche non fidarti dell'AI, ma dei tuoi test sì. E spedisci di nuovo senza ansia.

Stesso contenuto tecnico (ciclo red-green-refactor, verifica del codice generato, workflow ibrido uomo-macchina): ma la versione raccontata ti mette al posto del guidatore, con un ostacolo che riconosci al volo e uno scopo che vale la pena portarsi a casa. Le slide tecniche e il codice arrivano uguale — semplicemente, adesso qualcuno li sta aspettando.

## Esempio 3 — Mappatura di un input povero (come raccogliere l'input)

Input utente: *"Devo fare un talk su Kubernetes e service mesh, 30 minuti, pubblico di backend developer. Non so come iniziare."*

Mappatura:
- **E** (da input): backend developer → da precisare: *chi*, con che problema? → domanda da fare.
- **M**: buco → domanda da fare.
- **O**: buco → domanda da fare (il villano: complessità? incidenti? on-call?).
- **G**: presumibilmente tu/service mesh → da confermare.
- **I**: buco → domanda da fare.
- **S**: buco → domanda da fare.
- Durata: 30 minuti (utile per l'itinerario: tre passi da ~7').
- Pubblico: backend developer → l'eroe è una persona di quel mondo.

Domande da porre (tutte insieme, una sola tornata):
1. **E**: Chi è la persona a cui pensi quando immagini il pubblico ideale? Che cosa vive, in concreto?
2. **M**: Cosa sta cercando davvero quella persona — cosa vince se risolve?
3. **O**: Cosa glielo impedisce oggi, esattamente?
4. **I**: Quali sono i tre passi del viaggio che vuoi farle fare?
5. **S**: Cosa deve rispondere chi esce dalla stanza, se un collega gli chiede "com'era il talk?"
