---
name: storia
description: Trasforma un argomento in narrazione con il framework S.T.O.R.I.A. (Someone, Tensione, Ostacolo, Rischio, Intervento, Aspettative) per non salire sul palco come se si leggesse una documentazione. Usala quando l'utente vuole creare o scrivere la narrazione, l'intro, l'abstract o il racconto di un talk o presentazione, oppure quando chiede di rendere più coinvolgente, emozionale o memorabile un testo o talk già scritto ("non emoziona", "sembra documentazione", "rendilo una storia", "riscrivi la narrazione").
---

# S.T.O.R.I.A. — la narrazione del talk

Nessuno si ricorda il tuo argomento: tutti si ricordano ciò che hanno provato seguendolo. Questa skill trasforma un argomento in una narrazione — sei lettere, un ordine preciso: quello con cui funziona l'attenzione — prima delle slide e dello script.

## Le sei lettere

| Lettera | Domanda | Regola |
|---|---|---|
| **S — Someone** | Chi è in scena? | Una persona, non una cosa. Non una tecnologia, non un'azienda, non un "team": una persona specifica, con un nome e un problema. Il dad che arriva a fatica al calcio coi figli. Lo sviluppatore che rilegge l'email per la quarta volta prima di rispondere. Più è precisa la persona, più la stanza si riconosce. |
| **T — Tensione** | Cosa non va, sotto la superficie? | L'emozione sotto il problema: frustrazione, paura, desiderio, insoddisfazione. Dieci minuti di partita e il dad è seduto a bordo campo, finto occupato col telefono. La tensione non va dichiarata: **va mostrata**. È la prima cosa che fa alzare gli occhi dal telefono. |
| **O — Ostacolo** | Qual è il villano? | Cosa gli impedisce di arrivare dove vuole: debito tecnico, processo sbagliato, feature flag dimenticata, il "così si è sempre fatto". Il villano dà un nome alla frustrazione: finché non ha un nome, la soluzione arriva troppo presto. Dagli il nome, e la stanza ti seguirà volentieri. |
| **R — Rischio** | Cosa si perde davvero? | Cosa va in gioco se l'eroe non ce la fa: tempo, soldi, opportunità, fiducia, reputazione, a volte la salute. Senza conseguenze non c'è tensione; senza tensione non c'è attenzione. E va detto in concreto: non "perdeva produttività" ma "perdeva i weekend". |
| **I — Intervento** | Dove entri tu? | Il momento in cui il tuo lavoro entra nella storia. Ma attenzione al ruolo: **non sei l'eroe che scende dal cielo, sei la guida che consegna lo strumento giusto.** Il framework, la pratica, il processo che il tuo talk insegna è la spada che consegni all'eroe. Se il talk funziona, chi ascolta pensa "posso farlo anch'io", non "che bravo che è". |
| **A — Aspettative** | Com'è la vita dopo? | Dipingi il futuro: come cambia la vita dell'eroe una volta superato l'ostacolo. I weekend tornati. Il deploy del venerdì fatto in silenzio, senza ansia. È il motivo per cui chi ascolta agirà, e il posto dove chiudere il cerchio con lo scopo del talk. **Non vendi il prodotto: vendi il lunedì dopo.** |

## Come lavorare

### 1. Rileva la modalità
- **GENERA**: l'utente ha un argomento e vuole la narrazione, l'intro, l'abstract, il racconto.
- **CORREGGI**: l'utente ha un testo/talk che "sembra documentazione" e vuole renderlo una storia.

### 2. Raccogli e mappa l'input
Mappa tutto ciò che l'utente ha già scritto sulle sei lettere: personaggi, frustrazioni, contesti, esempi concreti. Se l'input contiene già una persona o un momento vissuto, quello è il tuo S e la tua T: non inventarne altri.

### 3. Chiedi solo le informazioni mancanti
Se mancano lettere o elementi essenziali (argomento, pubblico, persona da mettere in scena), chiedi all'utente **in un unico messaggio, tutte insieme**. Massimo una tornata di domande: poi lavora con quello che hai, segnando le ipotesi come ipotesi.

### 4. Modalità GENERA — output
1. Una frase per ogni lettera, in ordine (S → A).
2. Un titolo evocativo per la narrazione (es. "La fattura che nessuno vuole rileggere", non "OCR in Go: technical deep dive").
3. La versione continua: un breve paragrafo raccontato, costruito lettera per lettera.

### 5. Modalità CORREGGI — audit
Per ogni lettera, di': **OK / DEBOLE / BUCO** — con la citazione che la copre (o il buco), perché, e la riscrittura suggerita.

Checklist degli odori:
- **S**: il soggetto è una tecnologia, un'azienda o "il team" → nessuna persona in scena.
- **T**: il problema è dichiarato ma non mostrato ("era frustrato" invece della scena che lo mostra).
- **O**: la soluzione compare prima che il villano abbia un nome.
- **R**: nessuna conseguenza concreta, o conseguenze astratte ("meno produttività" invece di "persi i weekend").
- **I**: lo speaker è l'eroe che risolve, invece che la guida che consegna la spada.
- **A**: finisce sul prodotto/strumento invece che sulla vita dopo.

## Il test della stretta allo stomaco
Scrivi prima **S, T e O** (persona, tensione, ostacolo) e leggile insieme. Se in quelle tre frasi non c'è qualcosa che ti stringe lo stomaco, cercane un'altra persona o un altro ostacolo: **il resto del talk sta in piedi su quelle tre.** Consiglia all'utente questo test quando S, T o O sono deboli.

## Esempi
Gli esempi completi (confronto prima/dopo e un talk reale riscritto) sono in `examples.md`.
