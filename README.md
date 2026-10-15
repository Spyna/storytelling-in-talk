# ciak-speaking

> Un talk non si spiega. Si racconta.

Tre skill per il tuo agent AI (Claude Code, Codex, Cursor, OpenCode e altri) che ti aiutano a costruire un talk prima di aprire PowerPoint. Le installi con un comando e poi parli con l'agent come faresti con un collega che ha già fatto qualche palco.

Le skill nascono da [speaking.spyna.it](https://speaking.spyna.it), il sito dove Lorenzo Spinelli raccoglie quello che ha imparato sui palchi di PyCon, Codemotion e Open Source Day.

## Perché ti servono

Hai un talk tra qualche settimana. Il contenuto c'è, lo conosci a memoria. Ma dopo venti minuti metà sala guarda il telefono.

Di solito il problema non è quello che sai. È che lo stai spiegando, e nessuno si ricorda una spiegazione. Queste skill ti fanno le domande scomode prima di salire sul palco: chi è l'eroe della storia, cosa gli impedisce di arrivare dove vuole, cosa si porta a casa il pubblico.

## Cosa installi

| Skill | Cosa fa per te |
|---|---|
| `emogis` | Dà le ossa al talk con sei domande: Eroe, Missione, Ostacolo, Guida, Itinerario, Scopo |
| `storia` | Trasforma l'argomento in narrazione con sei passaggi: Someone, Tensione, Ostacolo, Rischio, Intervento, Aspettative |
| `talk-builder` | Ti accompagna dal foglio bianco al palco in sette passi, con le slide per ultime |

Possono creare un talk da zero oppure correggere una scaletta che hai già scritto.

Installale tutte e tre. `talk-builder` al passo cinque chiama `emogis` e `storia` per dare una storia a ogni sezione. Se ne manca una, funziona lo stesso ma con una versione ridotta dei principi.

## Installazione

### Cosa ti serve

Node.js, perché il comando usa `npx`. Controlla con `node --version`. Se non lo hai, lo trovi su [nodejs.org](https://nodejs.org).

### Il modo più veloce

Dalla cartella del tuo progetto:

```bash
npx skills add Spyna/ciak-speaking
```

Il CLI ti chiede quali skill installare e per quali agent. Seleziona le tre skill e il tuo agent. Finito.

Per averle in ogni progetto e non solo in quello corrente, aggiungi `-g`:

```bash
npx skills add Spyna/ciak-speaking -g
```

### Senza domande

Tutte e tre le skill, per Claude Code, a livello globale, senza conferme:

```bash
npx skills add Spyna/ciak-speaking -s '*' -a claude-code -g -y
```

Cambia `claude-code` con il tuo agent. Puoi indicarne più di uno: `-a claude-code codex cursor`.

### Solo una skill

```bash
npx skills add Spyna/ciak-speaking -s talk-builder
```

Se vuoi due skill su tre: `-s emogis storia`.

### Prima guarda, poi decidi

```bash
npx skills add Spyna/ciak-speaking --list
```

Mostra le skill disponibili senza installare niente.

### Dove finiscono i file

| Agent | Valore di `-a` | Cartella del progetto | Cartella globale (`-g`) |
|---|---|---|---|
| Claude Code | `claude-code` | `.claude/skills/` | `~/.claude/skills/` |
| Codex | `codex` | `.agents/skills/` | `~/.agents/skills/` |
| OpenCode | `opencode` | `.agents/skills/` | `~/.config/opencode/skills/` |
| Cursor | `cursor` | `.agents/skills/` | `~/.cursor/skills/` |
| GitHub Copilot | `github-copilot` | `.agents/skills/` | `~/.copilot/skills/` |
| Gemini CLI | `gemini-cli` | `.agents/skills/` | `~/.gemini/skills/` |

Il CLI supporta molti altri agent. L'elenco completo è nella [documentazione di skills](https://github.com/vercel-labs/skills).

Di default il CLI crea una copia unica delle skill e collega ogni agent con un symlink. Se il tuo sistema non supporta i symlink (capita su Windows senza permessi particolari), aggiungi `--copy` e ogni agent riceve una copia sua.

### Gestire le skill installate

```bash
npx skills list                    # cosa hai installato
npx skills update                  # aggiorna all'ultima versione
npx skills remove emogis           # toglie una skill
```

### Riavvia l'agent

Alcuni agent leggono le skill solo all'avvio. Se dopo l'installazione non le vedi, chiudi la sessione e aprine una nuova.

### Se usi l'app di Claude (claude.ai o Desktop)

Qui non serve il terminale. Scarica lo zip da [speaking.spyna.it/skills](https://speaking.spyna.it/skills), poi vai su Settings, Capabilities, Skills e caricalo. Dentro ci sono le stesse tre skill.

### Installazione a mano

Se non vuoi usare `npx`, clona il repo e copia le cartelle dentro `skills/` nella cartella skill del tuo agent (vedi la tabella sopra):

```bash
git clone https://github.com/Spyna/ciak-speaking.git
cp -r ciak-speaking/skills/* ~/.claude/skills/
```

## Come si usano

Non devi imparare comandi. Parli con il tuo agent e lui capisce quale skill chiamare. Tre scene tipiche.

**Hai un foglio bianco e una data.** Scrivi: "Tra un mese ho il palco, aiutami a costruire il talk." L'agent parte dalla tesi in una frase e ti fa le domande che servono: chi ascolta, cosa deve portarsi a casa, quale ostacolo affronti.

**Hai già una bozza.** Incolla scaletta e slide e scrivi: "Rivedile con E.M.O.G.I.S. e dimmi dove sono i buchi." Per ogni lettera ti dice se tiene, cosa è debole e come riscriverla.

**Un pezzo non funziona.** Scrivi: "Riscrivi l'intro della seconda sezione con S.T.O.R.I.A." Lavora solo su quel passaggio, senza rifarti tutto il talk.

## Se qualcosa non va

**La skill non parte.** Riavvia la sessione dell'agent, poi controlla con `npx skills list` che sia installata per l'agent che stai usando. Se hai installato con `-g`, vale per ogni progetto. Senza `-g`, vale solo per la cartella da cui hai lanciato il comando.

**`npx` non trovato.** Manca Node.js. Installalo e riprova.

**Il repo non si scarica.** Controlla di essere online e di aver scritto bene `Spyna/ciak-speaking`. Se sei dietro un proxy aziendale, prova con l'URL completo: `npx skills add https://github.com/Spyna/ciak-speaking`.

**Altro.** Apri una issue su [GitHub](https://github.com/Spyna/ciak-speaking/issues) o scrivi a [hello@spyna.it](mailto:hello@spyna.it).

## Un'ultima cosa sull'ordine

Contenuto, storia, slide. In quest'ordine, sempre. Le slide arrivano per ultime e servono a te, non al pubblico. Se una risposta è debole, non la sistemi con la grafica: la riscrivi.

## Il resto del kit

Le skill sono solo una parte. Sul sito trovi anche:

- [E.M.O.G.I.S.](https://speaking.spyna.it/emogis) e [S.T.O.R.I.A.](https://speaking.spyna.it/storia), i due framework spiegati con esempi
- [Costruire il talk](https://speaking.spyna.it/costruire), il metodo in sette passi
- [Delivery](https://speaking.spyna.it/delivery), per quando il contenuto è pronto e devi provarlo ad alta voce
- [Workbooks](https://speaking.spyna.it/workbooks), mini-app per compilare i framework passo passo. Salvano nel browser, esportano in Markdown, nessun account
- [Pillole](https://speaking.spyna.it/pillole), venti idee brevi per aprire, strutturare e stare sul palco

## Autore

Lorenzo Spinelli. Altro su di lui e sui talk che ha fatto su [spyna.it](https://spyna.it), su [LinkedIn](https://www.linkedin.com/in/lorenzospinelli) e su [GitHub](https://github.com/Spyna).

Hai un talk e vuoi una seconda opinione? Scrivi a [hello@spyna.it](mailto:hello@spyna.it) e racconta chi sei e che storia vuoi portare sul palco.

Grafica e immagini del sito sono di [Mino](https://github.com/mino89).
