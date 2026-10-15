# Speaking skills

> Un talk non si spiega. Si racconta.

Tre skill per il tuo agent AI che ti fanno costruire il talk prima di aprire PowerPoint. Vengono dal sito [speaking.spyna.it](https://speaking.spyna.it), dove metto in ordine quello che ho imparato (e sbagliato) sui palchi di più di 30 conferene e meetup.

## La scena

Hai un talk tra qualche settimana. Il contenuto c'è, lo conosci a memoria. Dopo venti minuti però metà sala guarda il telefono.

Di solito non è un problema di contenuto. È che stai spiegando, e nessuno si ricorda una spiegazione. Queste skill fanno le domande scomode prima che salga sul palco, non dopo.

## Il cast

Tre skill, ognuna con il suo `SKILL.md` e un `examples.md` con esempi veri.

| Skill | Il ruolo | Quando scatta |
|---|---|---|
| `emogis` | Le ossa del talk: Eroe, Missione, Ostacolo, Guida, Itinerario, Scopo | Devi strutturare un talk, o il tuo "manca qualcosa" |
| `storia` | La narrazione: Someone, Tensione, Ostacolo, Rischio, Intervento, Aspettative | Il testo sembra documentazione e vuoi che si ricordino come si sono sentiti |
| `talk-builder` | La regia: sette passi dalla tesi all'ultima slide | Hai una scadenza e un foglio bianco, o una scaletta da controllare |

`talk-builder` è il film intero. Al passo cinque chiama `emogis` e `storia` per dare una storia a ogni sezione. Installale tutte e tre. Se manca qualcuna, applica una versione ridotta dei principi, ma non è la stessa cosa.

## Installazione

```bash
npx skills add <owner>/<repo>
```

Per vedere cosa c'è dentro senza installare niente:

```bash
npx skills add <owner>/<repo> --list
```

Per prenderne una sola:

```bash
npx skills add <owner>/<repo> -s talk-builder
```

Le opzioni possono cambiare tra versioni del CLI, quindi se qualcosa non torna guarda `npx skills add --help`.

Se preferisci lo zip, lo trovi su [speaking.spyna.it/skills](https://speaking.spyna.it/skills). La pagina spiega anche come installarlo su Claude Code, claude.ai, Codex CLI e OpenCode.

## Come si usano

Non devi imparare comandi. Parli con il tuo agent e lui capisce quale skill chiamare. Tre scene tipiche:

**Foglio bianco.** "Tra un mese ho il palco, aiutami a costruire il talk." L'agent parte dalla tesi in una frase e ti fa le domande che servono: chi ascolta, cosa deve portarsi a casa, quale ostacolo affronti.

**Bozza da controllare.** "Rivedi questa scaletta con E.M.O.G.I.S. e dimmi dove sono i buchi." Per ogni lettera ti dice se tiene, cosa è debole e come riscriverla.

**Un passaggio che non funziona.** "Riscrivi l'intro della seconda sezione con S.T.O.R.I.A." Solo quel pezzo, senza rifare tutto.

## L'ordine delle cose

Contenuto, storia, slide. In quest'ordine, sempre. Le slide arrivano per ultime e servono a te, non al pubblico. Se una risposta è debole, non la sistemi con la grafica: la riscrivi.

## Il resto del kit

Le skill sono solo una parte. Sul sito trovi anche:

- [E.M.O.G.I.S.](https://speaking.spyna.it/emogis) e [S.T.O.R.I.A.](https://speaking.spyna.it/storia), i due framework spiegati con esempi
- [Costruire il talk](https://speaking.spyna.it/costruire), il metodo in sette passi
- [Delivery](https://speaking.spyna.it/delivery), per quando il contenuto è pronto e devi provarlo ad alta voce
- [Workbooks](https://speaking.spyna.it/workbooks), mini-app per compilare i framework passo passo. Salvano nel browser, esportano in Markdown, nessun account
- [Pillole](https://speaking.spyna.it/pillole), venti idee brevi per aprire, strutturare e stare sul palco

## Com'è fatto il repo

```
skills/
  emogis/
    SKILL.md
    examples.md
  storia/
    SKILL.md
    examples.md
  talk-builder/
    SKILL.md
    examples.md
```

Per provare le modifiche in locale, prima di pubblicarle:

```bash
npx skills add ./ --list
```

## Contatti

Hai provato le skill e qualcosa non va? Hai un talk e vuoi una seconda opinione? Scrivimi a [hello@spyna.it](mailto:hello@spyna.it). Dimmi chi sei e che storia vuoi raccontare, così partiamo da lì.

Altro su di me e sui talk che ho fatto: [spyna.it](https://spyna.it). Su LinkedIn sono [lorenzospinelli](https://www.linkedin.com/in/lorenzospinelli).

Grafica e immagini del sito sono di [Mino](https://github.com/mino89).
