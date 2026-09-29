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
