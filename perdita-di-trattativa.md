# La perdita di trattativa

*Il problema che questo documento risolve: il materiale è pronto, il mercato esiste, e comunque non arriva un euro. Perché non è il materiale a mancare.*

---

## Il punto

Abbiamo tre documenti scritti bene — scheda, email, traccia di call — e **zero contatti**. La scheda servizio è già a un livello che la maggior parte dei concorrenti non raggiunge: distingue importante da essenziale, cita le sanzioni giuste (7M/1,4%, non 10M/2%), dichiara cosa **non** è compreso. È materiale di vendita finito.

Eppure il primo incasso non arriva. Il motivo non è la qualità: è che **la vendita di un servizio di compliance si perde su una domanda a cui l'email non risponde**, e finora non abbiamo preparato quella risposta.

## La domanda che perde la trattativa

Chi riceve la proposta di check-up a 1.490 EUR, dopo l'interesse iniziale, fa mentalmente una sola domanda:

> **"Se faccio il check-up e poi mi dite che devo fare altro, quanto mi costa tutto? E chi me lo fa?"**

Questa è la **perdita di trattativa**. Il check-up è un acquisto a bassa intensità emotiva; l'adeguamento che ne consegue è un progetto da decine di migliaia di euro, senza preventivo, senza scadenza chiara, affidato a una persona sconosciuta. Il compratore razionale non compra la diagnosi **finché non vede l'intero conto**, perché teme che la diagnosi sia l'esca di una spesa illimitata.

Non è un problema di prezzo: 1.490 EUR sono pochi per una media impresa. È un problema di **prospettiva**. La scheda attuale vende il check-up come prodotto chiuso ("non è una roadmap con costi"), il che è **onesto ma commercialmente sbagliato**: disinnesca l'urgenza e lascia il cliente con il problema aperto, che è la ragione per cui dire "sì" costa fatica.

## La correzione: far vedere il conto, non nasconderlo

Serve un secondo documento — **un foglio, non un'offerta** — che risponda alla domanda in modo diretto:

**"Cosa succede dopo il check-up"**: le fasce di lavoro successive, con gli ordini di grandezza di costo e le cose che **il cliente può fare da solo a costo zero**. Un preventivo di massima, dichiarato come tale, che toglie il terrore dell'ignoto.

Il principio: **chi mostra il conto finale vende più di chi lo nasconde.** Il timore di un progetto a fondo perduto blocca la firma più di qualunque cifra — specialmente di fronte a un consulente singolo che nessuno ha ancora visto lavorare. E mostrare le parti che si possono auto-risolvere rende credibile tutto il resto.

Va scritto con due vincoli:
1. **Non è un preventivo vincolante** e va detto. Si dichiarano forchette e la dipendenza dall'esito della diagnosi.
2. **Non si promette la conformità.** Si dichiara cosa costa il lavoro e cosa resta in capo al cliente — l'attestazione all'ACN è un atto del soggetto, non un servizio che si vende.

*Il documento operativo è `dopo-il-checkup.md`. Le condizioni di vendita che non vanno violate sono in `AGENTS.md`.*

---

## Trappole che perdono la trattativa, in ordine di frequenza

| Trappola | Cosa succede | Correzione |
|---|---|---|
| **Silenzio sul costo di adeguamento** | Il cliente intuisce che è molto, immagina il peggio, e rimanda. | Mostrare le fasce di costo. Un numero spaventoso è meno paralizzante di un numero invisibile. |
| **Vendere la conformità** | Il cliente chiede "me la certifichi?" — e chi risponde "sì" ha già perso la credibilità davanti a chi lo sa. | Dire chiaramente che nessuno certifica la NIS2 e che l'attestazione è un atto del soggetto. |
| **Presentare 87 requisiti** | Il cliente vede un muro e non guarda le prime 10. | Consegnare sempre prima le 10 azioni prioritarie, con le altre in appendice. |
| **Prezzo a ore** | Riapre la paura del contatore. | Prezzo a corpo, e dirlo due volte. |
| **Chiedere accesso ai sistemi** | Alza la barriera e fa scattare il timore su dati e produzione. | La diagnosi si fa su documenti e interviste. Dichiararlo. |
| **Citare i 10 milioni / 2% a un soggetto importante** | È la cifra sbagliata per lui, ed è il segnale che chi scrive non ha letto il decreto. | 7M / 1,4% per l'importante. Se non si conosce la categoria, non si cita la cifra. |
| **Trattare il fornitore come "non soggetto"** | Si scavalca il canale più concreto. Vedi sotto. | Per il fornitore il valore è un altro. Vedi sezione seguente. |

---

## Il canale, riordinato: il fornitore viene prima

Nella prima stesura di questo materiale il fornitore di soggetto NIS era già indicato come "il canale più concreto". **Lo è più di quanto pensassimo**, e il motivo è ora verificabile (`fonti.md`, F12).

I soggetti NIS — **oltre 21.000**, di cui almeno 5.000 essenziali (`F14`) — sono obbligati, in ogni finestra **15 aprile – 31 maggio**, a trasmettere ad ACN l'**elenco dei propri fornitori rilevanti**, con una soglia di rilevanza che è **larga**: basta che la fornitura tocchi le infrastrutture digitali o i servizi di gestione TIC, **oppure** che la sua interruzione impatti la capacità del cliente di erogare il servizio per cui è nel perimetro.

Dove porta quel dato:
- Il fornitore che entra in quell'elenco ha un'esposizione **documentata** ad ACN: i soggetti che non superano le soglie possono essere individuati come importanti o essenziali **su proposta dell'Autorità di settore** (art. 3, c. 13) — e questo vale anche per **piccole e micro-imprese**.
- Il fornitore **impara dell'esistenza di questo rischio dal suo cliente obbligato**, non da sé stesso, e tipicamente **al rinnovo del contratto** — cioè quando ha già il problema o l'ha già superato.
- Un fornitore ICT che serve più soggetti NIS è nello stesso elenco di più clienti, ciascuno dei quali può chiedergli garanzie sulla sicurezza. Il check-up non è più una spesa di compliance: è **ciò che gli permette di rispondere in una settimana e non perdere il contratto**.

Questa è la ragione per cui, in una lista di destinatari da contattare, **il primo posto è del fornitore, non del soggetto NIS**: il fornitore non è costretto dalla legge, è costretto **dal suo cliente**, e quindi ha fretta *oggi* — non quando scade il suo termine.

## Chi ha davvero questo problema: profilo del destinatario

La lista dei contatti va costruita su un profilo, non su un settore:

- **Sa di essere NIS** il soggetto obbligato; **non lo sa ancora** il fornitore. Il primo ha già ricevuto una PEC e probabilmente ha già un consulente (o ha rimandato). Il secondo è il bersaglio.
- **È sufficientemente grande da avere un problema** (sistemi propri, dati di clienti, dipendenti) **e sufficientemente piccolo da non avere un ufficio interno** che se ne occupa. Sotto le 50 persone il problema è reale; sopra le 250 c'è già qualcuno che lo segue.
- **Ha un cliente NIS riconoscibile**: il segnale più forte è un fornitore ICT che compare nella lista fornitori di un'utility, di un ospedale, di un trasportatore, di una grande manifattura. **Quel fornitore, se serve un soggetto NIS, lo sa** — e questa è l'unica verifica che serve prima di scrivergli.
- **È governato da una persona che risponde direttamente**: il titolare, il direttore tecnico. Nelle medie imprese italiane la richiesta di sicurezza passa da lui, non da un reparto acquisti.

## Regola operativa

L'email di primo contatto va inviata **per prime ai fornitori** (Versione B in `email-primo-contatto.md`), e nella Versione B va aggiunto un solo elemento: **la finestra 15 aprile – 31 maggio** in cui i loro clienti NIS li devono elencare. È un fatto verificabile, è imbarazzante da scoprire in ritardo, e non richiede di spiegare la NIS2 a chi non ha voglia di ascoltarla.

Il soggetto NIS direttamente obbligato resta un bersaglio, ma **secondario**, perché ha già la scadenza addosso e ha già avuto modo di cercare qualcuno. Il fornitore no.

---

*Documento di prodotto, non legale. I riferimenti normativi rinviano a `fonti.md`, che distingue fonti primarie e secondarie. Verificato il 29 settembre 2026.*
