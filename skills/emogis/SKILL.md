---
name: emogis
description: Struttura un talk con il framework E.M.O.G.I.S. (Eroe, Missione, Ostacolo, Guida, Itinerario, Scopo) per dargli le ossa narrative prima delle slide. Usala quando l'utente vuole strutturare, costruire o impostare un talk, keynote o presentazione tecnica, oppure quando chiede di revisionare, correggere o diagnosticare un talk o abstract già scritto ("non ingaggia", "manca qualcosa", "revisiona la struttura", "dai le ossa al talk", "prima delle slide").
---

# E.M.O.G.I.S. — le ossa del talk

Un talk senza struttura non è un talk: è una lista di slide con un microfono acceso. Questa skill applica il telaio narrativo dei film — tradotto per i talk tecnici — in sei lettere, da percorrere **in ordine, per iscritto, prima di ogni slide**.

## Le sei lettere

| Lettera | Domanda | Regola |
|---|---|---|
| **E — Eroe** | Chi è il protagonista? | **Mai tu, mai il sistema.** È chi ti ascolta, o una persona precisa con cui può identificarsi. Non "l'architettura ha un collo di bottiglia": è Marta, on-call alle due di notte, che rilegge l'incident report per la quarta volta. Le storie iniziano quando entrano in scena le persone. |
| **M — Missione** | Cosa sta cercando? | Cosa vuole davvero l'eroe, non cosa vuoi tu: un deploy senza ansia, un cliente salvato, una deadline rispettata. Se la missione non è chiara, nessuno ha un motivo per restare fino alla fine. |
| **O — Ostacolo** | Cosa gli si para davanti? | Il villano: debito tecnico, demo che si rompe in live, feature flag dimenticata, la riunione che non finisce mai. Finché non dai un nome alla frustrazione, nessuno sente il bisogno di una soluzione — e il tuo contenuto arriva troppo presto. |
| **G — Guida** | Chi lo aiuta? | Sei tu, ma **non come eroe**: come guida. Il mentore che consegna la spada. Sei Q, non Bond: la guida non prende il titolo di credito, fa vincere l'eroe. Chi ti ascolta deve pensare "posso farlo anch'io", non "che bravo che è". |
| **I — Itinerario** | Che viaggio vive? | Tensioni crescenti e decrescenti, di solito tre passi. Non un elenco: una salita. Se il talk si può riassumere con "prima spiego A, poi B, poi C" è un elenco; l'itinerario ha una direzione. |
| **S — Scopo** | Come finisce, e perché conta? | Non il lieto fine: lo scopo più grande. Cosa succede all'eroe dopo, e cosa significa oltre a questo talk. È la frase che la stanza si porterà a casa. |

## Come lavorare

### 1. Rileva la modalità
- **GENERA**: l'utente dà un argomento, un titolo, un'idea — o chiede di impostare un talk da zero.
- **CORREGGI**: l'utente dà un talk, abstract o struttura già scritti da revisionare o diagnosticare.

### 2. Raccogli e mappa l'input
Prendi **tutto** quello che l'utente ha già scritto e mappalo sulle sei lettere. Non riscoprire ciò che è già nell'input: estrai, riordina, non chiedere.

### 3. Chiedi solo le informazioni mancanti
Se una o più lettere restano vuote, o mancano elementi essenziali (argomento, pubblico, durata, tesi), chiedi all'utente **in un unico messaggio, tutte insieme**, elencando le lettere mancanti con la relativa domanda. Massimo una tornata di domande: poi lavora con quello che hai, segnando le ipotesi come ipotesi.

### 4. Modalità GENERA — output
1. Una frase per ogni lettera, in ordine, per iscritto, senza edizione.
2. La versione continua: un breve paragrafo narrativo costruito lettera per lettera (E → S).
3. Se utile, un titolo evocativo per il talk (non "technical deep dive").

### 5. Modalità CORREGGI — audit
Per ogni lettera, di': **OK / DEBOLE / BUCO** — con la frase dell'utente che la copre (o il buco), perché, e il fix suggerito riscritto.

Checklist degli odori:
- **E**: parla di "il team", "l'architettura", una tecnologia → nessuna persona in scena.
- **M**: si capisce cosa vuole lo speaker, non cosa vuole l'eroe.
- **O**: la soluzione arriva prima che il villano abbia un nome → il contenuto arriva troppo presto.
- **G**: lo speaker si mette al centro ("vi mostro come ho fatto") → eroe sbagliato.
- **I**: riassumibile come "prima A, poi B, poi C" → è un elenco, non un itinerario.
- **S**: finisce senza una frase da portare a casa, o con un semplice recap.

Chiudi con: le 1-3 cose da sistemare per priorità. Regola: **se una risposta è debole, non sistemare la slide: sistema la risposta.**

## Regole d'oro
- Una frase per lettera, in ordine, per iscritto: se una lettera resta vuota, la struttura ha un buco — e lo sentirai in platea quando gli occhi tornano sui telefoni.
- L'eroe è chi ascolta. Tu sei la guida.
- Cambiare un'idea costa dieci minuti; cambiare quaranta slide costa un weekend.

## Esempi
Gli esempi completi (talk riscritto con e senza E.M.O.G.I.S.) sono in `examples.md`: consultali quando serve un riferimento su come trasformare una descrizione da "versione documentazione" a "versione raccontata".
