# 0004 — Far vedere la forchetta di costo dell'adeguamento, invece di tacerla

**Data:** 29 settembre 2026
**Stato:** Accettata

## Contesto

L'`offerta-checkup.md` dichiara esplicitamente che il check-up non è una roadmap con costi, ed è una scelta corretta sul piano della precisione: una diagnosi non può preventivare ciò che non ha ancora visto.

Nell'uso commerciale, però, quella precisione si è rivelata un costo. `perdita-di-trattativa.md` descrive il meccanismo: il compratore che non vede il conto finale **non compra la diagnosi**, perché teme che la diagnosi sia l'esca di una spesa illimitata. Il check-up a 1.490 EUR non è bloccato dal suo prezzo, ma dall'ignoto che gli sta dietro.

## Decisione

Si aggiunge un documento autonomo, `dopo-il-checkup.md`, con **forchette di costo dichiarate come non vincolanti** per le fasi successive all'adeguamento (documentale 4.000–12.000 EUR; tecnico 3.000–25.000 EUR; percorso completo 10.000–40.000 EUR su 12–18 mesi).

Il documento elenca anche, con pari evidenza, **le azioni a costo zero** che il cliente può eseguire internamente.

## Perché

Due ragioni distinte, entrambe necessarie:

1. **Un numero spaventoso è meno paralizzante di un numero invisibile.** Il rinvio non nasce dalla cifra, nasce dall'assenza di cifra.
2. **Mostrare le parti auto-risolvibili rende credibile il resto.** Un venditore che dice "questo ve lo potete fare da soli, non serve comprarlo" è credibile quando dice "questo invece serve". È anche l'unico modo per posizionarsi contro il "pacchetto chiavi in mano", che per definizione non distingue le due cose.

## Alternative considerate

- **Mettere la forchetta nella scheda servizio.** Scartata: la scheda è un documento di una pagina e la sua forza è la chiusura del perimetro. Mescolare la diagnosi chiusa con l'adeguamento aperto reintroduce l'ambiguità che l'ADR 0001 ha eliminato.
- **Non dichiarare nulla e rispondere solo in call.** Scartata: il momento della paura è prima della call, non durante. Chi non ha la risposta scritta non fissa la call.
- **Dichiarare un prezzo unico per l'adeguamento.** Scartata: sarebbe un preventivo senza diagnosi, cioè un numero inventato. Le forchette sono oneste nella misura in cui si dichiarano come tali.

## Conseguenze

- `dopo-il-checkup.md` va consegnato **dopo** il referto o insieme alla risposta a chi mostra interesse — mai al posto del referto.
- La forchetta alta (40.000 EUR) va comunicata insieme al fatto che una parte consistente è a costo zero interno, altrimenti scoraggia invece di rassicurare. L'ordine nel documento è costruito per questo.
- Vincolo invariato: non è un preventivo, è dichiarato non vincolante, e non promette la conformità. L'attestazione all'ACN resta un atto del soggetto.
