# Come costruire la lista dei contatti

**Vincolo:** questa cartella contiene un **metodo** e le fonti per costruire la lista. Nessun contatto va fatto da qui, e nessun nome va raccolto da fonti che non siano pubbliche e verificabili.

---

## Il segnale che qualifica un destinatario

Il destinatario primario è il **fornitore di un soggetto NIS** (vedi `perdita-di-trattativa.md` e ADR 0003). La domanda da porsi per ciascun candidato è una sola:

> **Questo fornitore serve un soggetto NIS riconoscibile, e la sua fornitura è ICT o non fungibile?**

Non serve sapere se il fornitore è nel perimetro: quasi certamente non lo è. Serve sapere che il **suo cliente** lo è — perché è il cliente a metterlo in elenco.

## Dove sta il segnale, in ordine di facilità

**1. Gli avvisi ai fornitori pubblicati dai soggetti NIS (segnale più forte, e pubblico).**
I soggetti obbligati comunicano ai propri fornitori l'avvio della finestra di aggiornamento. Un esempio reale e verificabile: il **Gruppo IREN** ha pubblicato sul proprio portale acquisti un'informativa ai fornitori che cita esplicitamente la Determinazione ACN 127437/2026 e la finestra 15 aprile – 31 maggio.

> <https://portaleacquisti.gruppoiren.it/documenti/Informativa_NIS2.pdf>

Un fornitore che ha ricevuto quel documento **sa** di essere potenzialmente in elenco. **Il bersaglio è il destinatario di quell'avviso: i fornitori iscritti a quel portale acquisti.** Non è una supposizione, è l'effetto dichiarato di quell'atto.

**Il metodo replicabile:** quasi ogni grande soggetto NIS (utility, trasporti, grandi manifatturiere, ospedali pubblici) ha un **portale acquisti con sezione "comunicazioni ai fornitori"**. Molti hanno pubblicato l'informativa NIS2 tra il 2026 e oggi. Trovare un portale acquisti con quell'avviso significa trovare, nello stesso posto, il fornitore da contattare e il fatto da citargli.

**2. Gli elenchi fornitori pubblicati per obbligo o per trasparenza.**
Grandi gruppi pubblicano liste di fornitori qualificati (spesso per appalti). Sono elenchi nominativi di aziende che **servono già** un soggetto di grandi dimensioni — cioè quasi sempre un soggetto NIS.

**3. Il settore sanitario privato (il bacino più addensato).**
Le strutture sanitarie sono prestatari di assistenza sanitaria e rientrano nell'ambito se superano i massimi delle piccole imprese (ACN, FAQ A1.5.2). I grandi gruppi privati italiani — tra gli altri **Gruppo San Donato**, **KOS**, **GHC (Garofalo Health Care)**, **Sereni Orizzonti**, **Don Gnocchi** — sono gruppi di strutture, ciascuna con sistemi propri e ciascuna potenzialmente in perimetro: **un solo gruppo contiene decine di possibili soggetti NIS e altrettanti fornitori ICT**.

Fonte per l'elenco degli operatori: report Mediobanca sui maggiori operatori sanitari privati in Italia (28 player) via <https://www.orthoacademy.it/operatori-sanitari-privati-italia-mediobanca/>; quadro dei gruppi via <https://www.dottnet.it/articolo/32536667/cresce-la-sanita-privata-in-italia-ecco-chi-sono-i-maggiori-operatori-e-i-loro-bilanci>.

**4. I fornitori ICT ricorrenti di più soggetti NIS.**
Un MSP, un fornitore di software gestionale, un integratore di rete che serve più strutture sanitarie o più utility: la stessa richiesta di garanzie gli arriva da più clienti contemporaneamente. Il check-up è la risposta una volta sola a tutte — è l'argomento più forte che abbiamo.

## La verifica minima prima di scrivere (2 minuti per contatto)

1. **Il fornitore ha un sito con un indirizzo email e un nome di persona?** Se no, scartare: l'email generica non porta a una call.
2. **Serve un settore che sappiamo essere nell'ambito NIS?** (ICT/Allegato I punti 8-9, sanità, energia, trasporti, manifattura, acqua, PA.) Se no, la Versione A è più adatta della B.
3. **Esiste un fatto datato da citargli?** La finestra 15 aprile – 31 maggio, o l'avviso ricevuto dal suo cliente. Senza un fatto, l'email è una campagna.
4. **Ha una partita IVA e una dimensione plausibile (> 50 dipendenti o struttura comparabile)?** Il problema è reale solo dove esiste una struttura da governare.

## Regola dimensionale (dalla norma, non dall'intuito)

Il perimetro NIS parte dalle imprese che **superano i massimali delle piccole imprese**: meno di 50 dipendenti **e** fatturato o bilancio sotto i 10 milioni EUR (Raccomandazione 2003/361/CE). Sotto quella soglia, l'organizzazione è di regola fuori — **salvo individuazione ex art. 3, c. 13**.

Conseguenza operativa per la qualifica: **il destinatario interessante è l'azienda tra 50 e 250 dipendenti.** Sotto i 50, il problema diventa quello del fornitore (Versione B), non del soggetto obbligato. Sopra i 250, esiste già un ufficio che se ne occupa.

Approfondimento sulle soglie e sul "tetto dimensionale": <https://bulltech.it/blog/nis2-pmi-obblighi-guida>.

## Cosa NON fare

- **Non raccogliere email da liste comprate.** Violano il GDPR e bruciano il dominio — l'unico bene che questo servizio ha.
- **Non scrivere a un'entità pubblica** come primo bersaglio: ha tempi e canali suoi, non risponde a un'email a freddo.
- **Non dichiarare che il destinatario è soggetto NIS** quando non lo sappiamo. Si scrive "il vostro cliente è soggetto NIS", che è verificabile; non "voi siete nel perimetro", che è falso finché non c'è una PEC.
- **Non inserire in questa cartella nomi e riferimenti raccolti per uso interno** senza dichiararne la fonte: la lista deve essere ricostruibile da chi legge.

---

*Metodo verificato il 29 settembre 2026. Nessun contatto presente in questa cartella: serve il titolare umano per l'invio.*


---

## Addendum del 27 ottobre 2026 — il segnale è cambiato di qualità, e va cercato altrove

*(Questo addendum tiene conto del fatto F18 in `fonti.md`.)*

Il metodo descritto sopra cercava il fornitore **a valle**: partiva dal portale acquisti del soggetto NIS e leggeva i suoi avvisi. Il 27 ottobre ho trovato un documento che rovescia il senso di quella ricerca: **A.S.L. V.C.O. ha pubblicato l'allegato contrattuale NIS2 completo, con la checklist di conformità che il fornitore deve sottoscrivere** (F18). Non è più un avviso generico: è il questionario con cui il fornitore verrà misurato.

**La conseguenza pratica: le stazioni appaltanti pubblicano, insieme al bando, il questionario. Quindi le "clausole NIS2" e le "checklist di conformità ICT" sono reperibili come documenti di gara pubblici — e chi le ha già pubblicate ha, per definizione, dei fornitori che le stanno firmando.**

### Il nuovo filtro, in tre passi

1. **Cerca documenti di gara che contengano "NIS2" nel titolo dell'allegato** — non comunicati, non guide: **allegati contrattuali**. Stringhe fruttuose: `"clausole" NIS2 fornitore`, `"checklist di conformità" ICT cybersecurity NIS2`, `"obblighi di cybersecurity" supply chain fornitore allegato`.
2. **Dall'allegato risali all'ente che lo ha pubblicato.** L'ente (ASL, azienda ospedaliera, utility, università, consorzio di comuni) è un soggetto NIS che ha già iniziato a imporre la clausola: ha fornitori ICT che devono rispondere, e li ha sotto contratto.
3. **Il bersaglio non è l'ente: sono i suoi fornitori ICT.** L'ente non compra una diagnosi (ha già i suoi consulenti, probabili autori della clausola). Il fornitore PMI che deve compilare la checklist sì — e ha una scadenza contrattuale, non una scadenza normativa astratta.

### La riga che va scritta nel registro dei candidati

Per ogni ente trovato, registrare: **ente**, **URL dell'allegato**, **data di pubblicazione**, **i termini numerici che impone** (giorni per le patch, ore per la notifica), e **il fornitore ICT coinvolto** se desumibile dal bando. La clausola con i termini numerici è l'aggancio: è un fatto che il fornitore non può contestare, perché è nel *suo* contratto.

### Perché questo metodo è migliore del precedente

- **Non richiede di indovinare se il cliente è NIS**: chi pubblica una clausola NIS2 dichiara, con quel documento, di esserlo.
- **Il fatto da citare non è la legge, è il contratto del destinatario.** È l'unico tipo di affermazione a cui un fornitore non può rispondere «lo so già».
- **Il documento esiste già, è pubblico e datato**: zero congetture, zero rischi di affermare il falso.

### Avvertenza onesta

Il passo 3 è **un'ipotesi di lavoro, non un fatto verificato**: non ho ancora aperto il bando ASL V.C.O. per estrarre un fornitore nominato. Finché non lo faccio, la lista resta senza destinatari. Ma il metodo ha ora un punto di partenza concreto e una fonte primaria, invece di un criterio da applicare alla cieca a dieci MSP sperati.
