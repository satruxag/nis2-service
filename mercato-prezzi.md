# Riferimenti di mercato per il prezzo

**Rilevati il 22 settembre 2026** con ricerca web. Sono tutti **fonti secondarie commerciali**: servono a posizionare il prezzo, non a sostenere un'affermazione normativa. I prezzi sono indicativi e spesso "da", non "a".

---

## Cosa è stato trovato

### Italia — gap analysis / assessment NIS2

| Riferimento | Prezzo indicato | Cosa comprende |
|---|---|---|
| BullTech (Vimercate) | **Security Audit 1.500 EUR** una tantum | vulnerability assessment rete+endpoint+cloud, report, priorità remediation — *punto di partenza, non NIS2* |
| BullTech | **5.000–15.000 EUR** | NIS2 compliance: gap analysis + implementazione controlli + documentazione + preparazione audit. "Progetto chiavi in mano" |
| BullTech | Pentest **da 3.000 EUR** | simulazione attacco, report OWASP, remediation plan, "valido per audit NIS2" |
| DNA10 Technology | prezzo non pubblico (login richiesto) | prodotto "Gap analysis NIS2" venduto a catalogo — segnale che il format esiste già come SKU |

- BullTech: <https://bulltech.it/cybersecurity-milano>
- DNA10: <https://www.dna10.it/shop/gap-analysis-nis2-435>

### Spagna — mercato NIS2 più maturo del nostro (riferimento di confronto)

| Voce | Intervallo | Note |
|---|---|---|
| Gap analysis NIS2 (vs art. 21 + guide ENISA) | **3.000–6.000 EUR** | impresa di riferimento 100 dipendenti, settore sanitario, senza base pregressa |
| Consulenza di implementazione | **12.000–20.000 EUR** | politiche, procedure, controlli tecnici, catena di fornitura |
| Pentest e valutazione tecnica | **5.000–10.000 EUR** | indicato come "praticamente obbligatorio" per entità NIS2 |

- Fonte: <https://www.delbion.com/insights/consultoria-nis2-espana-que-necesita-cuanto-cuesta/>

### Unione Europea — costo totale di conformità (stime di settore)

- **Entità essenziali: 150.000 – 2.000.000+ EUR**
- **Entità importanti: 30.000 – 500.000 EUR**
- Sviluppo politiche con consulente esterno: 15.000–80.000 EUR
- Formazione del board: 2.000–10.000 EUR a sessione
- Mantenimento annuo: 15–25% del costo iniziale
- Fonte: <https://resiliently.ai/blog/posts/nis2-compliance-cost-what-companies-spend-2026> (stima di settore, brand di prodotto — usare come ordine di grandezza)

---

## Lettura del mercato: è saturo?

**Su alcune cose sì, e va detto.**

1. **Il "pacchetto NIS2 chiavi in mano" è una commodity.** Chiunque, da Milano, vende gap analysis + implementazione + documentazione a 5.000–15.000 EUR. Se questa fosse l'offerta, la competizione sarebbe sul prezzo e sull'email più accattivante, e chi ha più budget di marketing vince.
2. **Il format "gap analysis a prezzo fisso" esiste già come prodotto di catalogo** (DNA10 lo vende a listino). Non è un'idea nuova. Chi lo compra sa già cosa cerca.
3. **Il contenuto regolatorio è in gran parte replicabile da chiunque sappia leggere le FAQ ACN.** Non è un fossato.

**Dove invece c'è spazio reale:**

1. **La precisione normativa è rara.** Il mercato ripete "scadenza 31 ottobre 2026" e "sanzioni fino a 10 milioni". Entrambe le affermazioni sono imprecise (vedi `fonti.md` F2 e F5). Chi opera nel settore *sa* riconoscere la differenza, e la differenza è verificabile. Un documento che dice "per la vostra categoria il massimo è 1,4%, non 2%" e "il vostro termine dipende dall'anno di inserimento" si distingue immediatamente da dieci email identiche.
2. **La competenza tecnica reale vs. la competenza documentale.** Molte offerte producono *documenti*. Poche producono una *valutazione fatta da chi amministra davvero infrastrutture*. L'angolo difendibile non è il prezzo più basso: è "la persona che ti fa la gap analysis è la stessa che sa cosa significa implementare MFA su un parco misto con un ERP legacy".
3. **Il segmento "siamo sotto soglia, cosa ci tocca davvero?"** è poco servito, perché non si vende una big remediation. Una diagnosi breve e onesta, a basso costo, che dice "non sei soggetto NIS, ma il tuo cliente NIS ti chiederà requisiti di sicurezza al rinnovo" è un prodotto che gli altri non fanno, perché non è abbastanza redditizio per loro. Per questa offerta, invece, è un ingresso.
4. **Il canale dei fornitori.** Con la misura GV.SC-01 e l'obbligo di inserire requisiti di sicurezza nei contratti *rinnovati*, c'è un flusso di richieste che scende dai soggetti NIS ai loro fornitori PMI. Chi aiuta le PMI a rispondere a quelle richieste — e a non perdere il contratto — ha un accesso al mercato che non passa dal marketing.

**Conclusione senza addolcire:** non è un mercato vergine, e questo prodotto non inventa nulla. È un mercato dove la maggior parte dell'offerta è approssimativa sui fatti. L'unico vantaggio sostenibile qui è essere quello che non lo è — e questo richiede che ogni documento sia verificato, non riscritto.

---

## Come è stato fissato il prezzo del Check-up

Il Check-up NIS2 (`offerta-checkup.md`) è posizionato a **1.490 EUR** (importanti, fino a 60 postazioni) e **2.900 EUR** (essenziali o parco più grande).

Logica:
- **Sotto la forbice 3.000–6.000 EUR** della gap analysis classica. Il Check-up non è una gap analysis completa: è la domanda preliminare ("siamo soggetti? cosa ci manca?") e produce una stima, non una roadmap con costi. Il prezzo deve riflettere che è più piccolo.
- **Sopra il Security Audit generico da 1.500 EUR**, perché il Check-up verifica misure specifiche contro un allegato normativo identificato, non produce un report di vulnerabilità generico. Vale di più di uno scan.
- **Abbastanza basso da essere deciso dal titolare senza comitato.** Un importo a quattro cifre basse, con scope scritto, si firma in una settimana. Un progetto da 12.000 EUR richiede budget, gara e tre mesi: non chiude la necessità di incasso rapido.
- **Il prezzo fisso è l'argomento di vendita.** "Non vi fatturo le ore, vi fatturo il referto" elimina la paura del contatore aperto, che è il principale freno a contattare un consulente per una PMI.

**Ciò che resta fuori di proposito:** implementazione, piano di adeguamento, attestazione di conformità. Sono voci successive, da quotare **dopo** che il referto ha mostrato quanto è grande il buco — ed è esattamente il motivo per cui il Check-up rende: trasforma una vendita da 12.000 EUR, impossibile a freddo, in una vendita da 1.490 EUR seguita da una seconda proposta informata.
