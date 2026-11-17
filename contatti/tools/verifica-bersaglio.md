# Verifica bersaglio — la scheda da compilare per ogni candidato

**Perché esiste.** La lista bersagli del 20 ottobre è passata da quattro nomi a due (uno solido, uno debole) perché due candidati sono risultati già qualificati QC2. Il criterio a quattro punti funziona, ma finora era applicato a mano, caso per caso, e ogni candidato costava una ricerca web non registrata. Questo file è la **scheda di verifica**: una tabella da compilare prima di scrivere un'email, che rende il criterio ripetibile e la decisione ricostruibile da chi legge.

**Regola d'uso.** Un candidato entra in `lista-bersagli.md` solo se tutte e quattro le colonne sono `OK`. Un `NO` su una colonna lo esclude e la riga va conservata (documentata, non cancellata) — è così che si evita di ri-verificare lo stesso nome tra due mesi.

---

## La scheda

| Campo | Cosa contiene | Fonte ammessa |
|---|---|---|
| **Denominazione** | Ragione sociale esatta, come compare nel registro imprese | Sito aziendale / registro |
| **Sede** | Città | Sito aziendale |
| **Fonte del segnale** | Da dove sappiamo che serve un soggetto NIS: nome del cliente NIS, oppure URL dell'avviso ai fornitori ricevuto | Pubblico e verificabile |
| **Cliente NIS (nominato)** | Nome esatto + settore Allegato I/III | Case history del fornitore, o avviso del cliente |
| **Dimensione** | Dipendenti (o "PMI, struttura comparabile") | Sito / LinkedIn / registro |
| **Qualifica ACN?** | Presenza sul Portale Cloud ACN (sì/no) + eventuale codice scheda | Portale Cloud ACN |
| **ISO 27001/22301?** | Esposta sul sito (sì/no) | Sito del fornitore |
| **Contatto** | Nome di persona + email diretta (non `info@`) | Sito del fornitore |
| **Esito** | `OK` / `NO — motivo` | — |

---

## I quattro punti (dal criterio, ADR 0005)

1. **Serve un soggetto NIS riconoscibile.** Il cliente finale deve stare in un settore Allegato I o III, oppure aver ricevuto la comunicazione di inserimento. *Non basta "settore sanitario" generico: serve il nome o il settore specifico del cliente.*
2. **Il fornitore non ha già una qualificazione ACN né ISO 27001/22301 recente.** Verifica: ricerca sul Portale Cloud ACN + ricerca `ISO 27001` sul sito. Se ha già la griglia, il check-up gli è inutile (F17).
3. **È PMI.** Tra 50 e 250 dipendenti. Sotto i 50 il problema è del fornitore (Versione B dell'email), non del soggetto obbligato; sopra i 250 c'è già un ufficio interno.
4. **La leva è il cliente NIS, non il fornitore stesso.** L'email deve poter dire: «il tuo cliente [X] ti sta elencando all'ACN con questi codici». Se la leva è solo «la NIS2 riguarda anche te», è una campagna, non un contatto.

---

## Trappole già incontrate (non ripeterle)

- **Il fornitore che organizza già eventi su NIS2** (caso MiPS): non è un cliente ingenuo, è un semi-concorrente. Ci si scrive da pari, con un fatto operativo che gli serve, non con la spiegazione della norma.
- **Il cliente "sanitario" non dimostrato** (caso 3MSOLUTIONS / Else Solutions): se non è provato che il cliente sia soggetto NIS, il punto 1 non è soddisfatto. Non si scrive.
- **Il fornitore di software verticale già qualificato** (caso EL.CO., MYS): escluso dal punto 2. Resta nella mappa come *fornitore rilevante*, non come destinatario.

## Dove trovare i candidati (dal metodo, `contatti/README.md`)

Il segnale più forte e più economico è l'**avviso ai fornitori** pubblicato dal soggetto NIS sul proprio portale acquisti: chi ha ricevuto quell'avviso è, per effetto dell'atto, un fornitore che il soggetto sta considerando per l'elencazione. Cercare i portali acquisti che hanno pubblicato l'informativa NIS2 e leggere la sezione "comunicazioni ai fornitori" significa trovare, nello stesso posto, il candidato e il fatto da citargli.

*Schede compilate: 3 (MiPS, 3MSOLUTIONS, più i due esclusi EL.CO. e MYS). Regola: non si scrive a un candidato la cui scheda non è completa.*

---

## Scheda 1 — MiPS Informatica S.p.A. (esito: OK con cautela)

| Campo | Valore | Fonte |
|---|---|---|
| Denominazione | MiPS Informatica S.p.A. | <https://mips-informatica.com/> |
| Sede | Genova (+ Firenze) | Sito aziendale |
| Fonte del segnale | Case history aziendale che nomina i clienti — nessun avviso ai fornitori reperito | <https://mips-informatica.com/case-history> |
| Cliente NIS (nominato) | **Gruppo Ansaldo Energia** (energia, Allegato I — critico) + **Università di Genova** (Allegato III) + un istituto bancario | Case history |
| Dimensione | **33 dipendenti** dichiarati sul sito, due sedi (Genova, Firenze) | <https://www.mips-informatica.com/chi-siamo/> |
| Qualifica ACN? | Non risulta per servizi gestiti | Portale Cloud ACN |
| ISO 27001/22301? | Non risulta esposta come certificazione propria; **vende però "Legal & Compliance Service" su GDPR, NIS2 e ISO 27001**, e usa SOC/NOC del Gruppo WeTech's/WeSecure's | <https://www.mips-informatica.com/cybersecurity/> |
| Contatto | Da reperire: nome di persona, non `info@` | — |
| **Esito** | **NO — punti 3 e 4 non reggono (verifica del 27 ottobre)** | — |

**Perché è passato da "OK con cautela" a NO (verifica del 27 ottobre 2026).** Due fatti letti direttamente sul sito aziendale ribaltano la scheda:

1. **Dimensione (punto 3).** MiPS ha **33 professionisti**: è sotto la soglia dei 50 dipendenti. Non è il soggetto obbligato "impresa media" che compra il Check-up — al più è un *fornitore rilevante*, cioè il destinatario della Versione B, non della Versione A.
2. **Concorrenza diretta (punto 4).** Sulle sue pagine MiPS vende **"Legal & Compliance Service: supporto per la conformità normativa in ambito cybersecurity — GDPR, NIS2, ISO 27001"**, più **SOC/NOC H24**, penetration test e managed security services. Cioè: **vende esattamente il servizio che venderemmo noi**, con in più un SOC e la partnership con un datacenter Tier4 certificato. E organizza essa stessa eventi su NIS2. Non è un cliente: è un concorrente attrezzato, con più capacità di quante ne avremmo noi su questo specifico perimetro.

**Nota di metodo (la lezione).** La scheda del 20 ottobre si basava sulla case history — che oggi **non è più raggiungibile** (404 su `/case-history`): il fatto citato non è più verificabile sulla fonte indicata. Il dato che ha ribaltato la scheda (33 dipendenti, servizio NIS2 a catalogo) stava invece su due pagine che nessuno aveva letto: `/chi-siamo/` e `/cybersecurity/`. **Regola che ne deriva: la dimensione e l'offerta concorrente si verificano sulla home, su "chi siamo" e sulla pagina dei servizi — non solo sulla case history.** Senza questi due minuti, l'email sarebbe partita verso un concorrente dicendogli cosa gli manca.

## Scheda 2 — 3MSOLUTIONS srl (esito: NO)

| Campo | Valore | Fonte |
|---|---|---|
| Denominazione | 3MSOLUTIONS srl | <https://www.3msolutions.it/> |
| Sede | Meda (MB) | Sito |
| Fonte del segnale | Case history con un solo cliente NIS-adiacente | <https://www.3msolutions.it/case-history/> |
| Cliente NIS (nominato) | **Else Solutions** — descritto genericamente come "sanitario", **non dimostrato soggetto NIS** | Case history |
| Dimensione | PMI | Sito |
| Qualifica ACN? | No | Portale Cloud ACN |
| ISO 27001? | Non risulta | Sito |
| Contatto | Da reperire | — |
| **Esito** | **NO — punto 1 non dimostrato** | — |

**Motivo dell'esclusione.** La maggior parte dei clienti documentati sono **fuori perimetro** (oleodinamica, motori, tessile, farmacia, biotech). L'unico aggancio sanitario è Else Solutions, e non è provato che sia soggetto NIS. Senza quel fatto il punto 1 non regge, e l'email diventa una campagna. **Condizione di riammissione:** reperire una fonte che attesti Else Solutions (o un altro cliente) come soggetto NIS in perimetro — a quel punto la scheda va riaperta.

---

## Cosa dice questa verifica, senza addolcire

Le schede compilate sono **due**, e **dopo la verifica del 27 ottobre nessuna delle due passa**: 3MSOLUTIONS non dimostra il punto 1, MiPS non regge i punti 3 e 4. La lista dei destinatari dell'email è, oggi, **vuota**. Non è un peggioramento del materiale: è il risultato di aver verificato due candidati che sembravano buoni e non lo erano. Il collo di bottiglia non è il criterio: è il numero di candidati esaminati. Il metodo in `contatti/README.md` indica dove trovarne in fretta (i portali acquisti con l'avviso NIS2); finché non si applica quel metodo a dieci candidati, la lista resta a un nome. Questo file è lo strumento per farlo in modo che il decimo candidato costi cinque minuti e non mezz'ora.

## Controllo 5 (nuovo, 3 novembre 2026) — La P.IVA si legge sull'atto, non si deduce dalla ragione sociale

**Caso reale che ha generato questo controllo.** ASL Biella ha affidato l'«Applicativo MMG e PLS» a una «SYSTEM TECHNOLOGY S.R.L.», P.IVA 02387320985. Quella P.IVA corrisponde a una ditta di **Botticino (BS) che vende CAD/CAM per la meccanica** — un'impresa **omonima**, non il fornitore sanitario. Una ricerca per ragione sociale avrebbe prodotto un'email, una sede e una dimensione **sbagliate**, e l'invio sarebbe arrivato all'azienda sbagliata.

**Regola.** Per ogni bersaglio preso da un atto pubblico:
1. Prendere la **P.IVA dall'atto**, non dal motore di ricerca (l'atto la scrive accanto alla ragione sociale: è quella la fonte).
2. Verificare che il **settore** dell'impresa trovata combaci col **software nominato nell'atto**. Se l'atto dice «Applicativo MMG e PLS» e il sito dice «CAD/CAM, fresatura, tornitura», non è la stessa impresa: fermarsi.
3. Prima di scrivere, aprire il sito e cercare **ISO 27001** (o «Information Security Policy»). Se c'è, il criterio 4 è violato: **fuori dalla lista**. Caso reale: SHORR KAN espone ISO 27001:2022 + 27017 + 27018 — esclusa.
4. Se il settore non combacia e la P.IVA è confermata, il nome va marcato **«dato inattendibile»** e non usato: non è un bersaglio, è un'ambiguità da sciogliere sull'atto.

**Perché vale.** Un invio sbagliato a un'impresa omonima brucia il nome e non produce nulla. Due dei nove candidati di questo giro sono caduti qui — cioè la verifica ha risparmiato due invii a vuoto. Il costo è 10 minuti per nome.

---

## Scheda 3 — SINED S.r.l. (esito: OK — bersaglio confermato, priorità 1)

| Campo | Valore | Fonte |
|---|---|---|
| Denominazione | SINED S.r.l. (Medical Computer Systems) | <https://www.sined.it/> |
| Sede | Via Ferrarese 219/7, 40128 Bologna (+ filiale Orvault, Francia) | sito aziendale |
| P.IVA | 01757941206 (C.F. 04226120378, REA BO 357596) | **lettera sull'atto** (Det. ASL Biella 680/2026; Det. 642/2026) + footer sito |
| Fonte del segnale | **Due atti pubblici**: ASL Biella Det. 642/2026 (Medware Nefrologia e dialisi, € 70.000) e Det. 680/2026 (CCA/OE con Medware per la Dialisi, € 10.000) | `fonti.md` F19.a, F19.e |
| Cliente NIS (nominato) | **ASL Biella** (sanità, Allegato I — settore «Sanità», soggetto essenziale); ASL V.C.O. terzo ente della stessa famiglia | atti ASL Biella |
| Dimensione | **11–50 dipendenti** (LinkedIn: 53 profili; «0» contatore installazioni non valorizzato sul sito). Micro/piccola impresa, nessuna funzione compliance interna | LinkedIn company/sined-srl; classe dimensionale da sito |
| Qualifica ACN? | **No** — non risulta qualificata né elencata sul Portale Cloud ACN per servizi gestiti | Portale Cloud ACN (verifica 17/11/2026) |
| ISO 27001/22301? | **NO.** Espone **ISO 13485:2016** e **ISO 9001:2015** soltanto, più «ACCREDITAMENTO FSE 2.0». Nessuna ISO 27001, nessuna 27017/27018, nessuna Information Security Policy pubblicata | <https://www.sined.it/certificazioni/> e Politica Qualità rev. 27/01/2026 (<https://www.sined.it/wp-content/uploads/2026/03/Politica-per-la-Qualita-SINED-v20260127.pdf>) |
| Contatto | `info@sined.it` (generale) · `giulia.marchi@sined.it` (nome, da verificare attuale) · tel. +39 051 604 88 11 | portale Unione Terre di Pianura; sito aziendale |
| **Esito** | **OK — 4/4. Primo bersaglio dopo ME.S.I.S.** | — |

**Perché regge tutti e quattro i punti.**
1. **Punto 1 (soggetto NIS riconoscibile): OK.** Non un cliente «sanitario» generico: **ASL Biella**, un'ASL piemontese che è soggetto NIS di Allegato I, e che ha affidato a SINED il software *Medware* per dialisi e nefrologia con **due** determinazioni distinte nello stesso periodo (giugno 2026). Il software nominato sull'atto («Cartella Clinica Aziendale con Medware per la Dialisi») combacia esattamente col prodotto dichiarato sul sito SINED («MedWare® — Cartella clinica nefrologia e dialisi»): **identificazione confermata, nessuna omonimia**.
2. **Punto 2 (non ha già la griglia): OK.** ISO 9001 e ISO 13485 sono sistemi qualità/dispositivi medici, **non** un SGSI. ISO 13485 non copre la sicurezza delle informazioni come farebbe la ISO 27001: una software house che certifica la qualità dei processi può avere zero policy di accesso, zero gestione incidenti, zero continuità documentata. Nessuna qualifica ACN.
3. **Punto 3 (dimensione): OK — e qui il criterio va letto con la rettifica di F19.c.** Criterio sostituito = «troppo piccola per avere compliance interna, abbastanza grande da avere un contratto NIS che vale più del check-up». 11–50 dipendenti, ~900 K follower LinkedIn, 300+ centri installati: nessun CISO interno plausibile, ma un contratto con ASL Biella da **€ 70.000** per il solo Medware.
4. **Punto 4 (leva = il cliente NIS): OK, la più forte della lista finora.** L'email può dire il numero di un atto pubblico del giugno 2026 in cui SINED è fornitore di un'ASL che è soggetto NIS. Non «la NIS2 riguarda anche te»: «il tuo cliente ha firmato questo, e al rinnovo ti chiederà questo».

**Perché è più forte di ME.S.I.S.**
- ME.S.I.S. ha **un** contratto NIS provato (ASL Biella, € 16.320/anno). SINED ne ha **due** nello stesso arco di tempo (€ 70.000 + € 10.000, oltre a comparire nella mappa di ASL V.C.O.): la probabilità che riceva la richiesta di clausole al rinnovo è più alta e più vicina.
- SINED è **11–50 dipendenti** contro i 7 di ME.S.I.S.: ha una struttura (ufficio qualità, software quality, PRRC per i dispositivi medici) abituata a rispondere a requisiti documentali — paga più facilmente 1.490 EUR per un referto che le risparmia tempo, mentre una micro-impresa da 7 persone è più sensibile al prezzo.
- SINED è **società di gruppo** (gruppo francese THÉRADIAL): ha un percorso di due diligence già avviato, quindi riconosce il valore di un referto formale.

**Trappola evitata in questa scheda.** La ricerca per ragione sociale «SINED» restituisce anche **SINED S.P.A. (Parma, materiali edili)**: impresa del tutto diversa. Qui la P.IVA **01757941206** è stata letta **sull'atto** ASL Biella e ricompare identica nel footer del sito: nessuna ambiguità. Applicato il Controllo 5.

**Nota di metodo (nuovo, 17 novembre 2026) — La certificazione ISO 9001/13485 NON esonera: falsifica il criterio «ha già le certificazioni».** ME.S.I.S. (ISO 9001) e SINED (ISO 9001 + ISO 13485) espongono certificati di sistema e restano bersagli validi. La variabile discriminante resta **una sola**: la presenza di **ISO/IEC 27001** (o 22301) — il sistema di gestione della sicurezza delle informazioni. Le altre certificazioni sono rumore: una software house sanitaria con ISO 13485 certifica che il *prodotto* è affidabile, non che i *sistemi* sono protetti. Corollario pratico: quando una PMI dice «siamo già certificati», la domanda giusta è «certificati su quale norma?», e nel 90% dei casi la risposta è 9001.

---

## Screening del 17 novembre 2026 — cinque candidati, un solo OK

Applicando la stessa scheda ai nomi restanti della mappa (F19.a + F19.e), con la regola: *prima di tutto, leggere la pagina Certificazioni del sito aziendale e cercare «27001»*.

| Candidato | P.IVA | Esito | Motivo (fonte letta il 17/11/2026) |
|---|---|---|---|
| **SINED S.r.l.** | 01757941206 | **OK** | ISO 9001 + 13485 soltanto; no ACN; 2 contratti ASL Biella → scheda 3 |
| METEDA S.r.l. | 01713290441 | **NO** | Espone **ISO/IEC 27001:2022** (con 27017/27018) su <https://www.meteda.it/qualita>; inoltre è **«un'azienda IQVIA»** (gruppo multinazionale) → gruppo, non PMI |
| FUJIFILM Healthcare Italia S.p.A. | 11025740157 | **NO** | **ISO/IEC 27001:2022**, certificato n. 40672 (emissione 27/05/2026, scadenza 10/12/2027): PDF pubblico su asset.fujifilm.com. >200 dipendenti, € 113 M → fuori anche per dimensione |
| AXIOS Informatica S.r.l. | 03166670244 | **NO** | Espone **ISO/IEC 27001** (cert. n. 55819 del 24/04/2020, integrata con 27017-27018) **+ ISO 22301** (cert. n. 71107) e dichiara la **qualificazione ACN QC1 e QC2** su <https://www.axios.it/certificazioni/> → la griglia ce l'ha già, doppio motivo |
| LIZARD S.r.l. | 01867040220 | **NO** | Lizard (Trento, <https://lizardnet.it/>) **vende cyber security, cloud e managed service**, ha una business unit «Network and Security» → **concorrente**, non cliente (stessa logica di MiPS) |
| METROPOLIS S.r.l. (marchio Punto Giallo®) | 10368880158 | **DA VERIFICARE** | Il sito <https://www.puntogiallo.it/> espone **ISO 9001:2015** e nulla su 27001 — ma un **catalogo espositore 2023** (ComuniCare) la descrive come operante «secondo ISO 9001, ISO 27001, ISO 22301». **Contraddizione non risolta**: da chiarire prima di scrivere. Il sito .it ufficiale non espone 27001, il catalogo sì |

**Risultato dello screening: cinque esclusioni, un candidato confermato (SINED), uno da sciogliere (METROPOLIS).** Il criterio si è dimostrato **discriminante**: ha separato senza ambiguità chi ha un SGSI (METEDA, FUJIFILM, AXIOS) da chi non lo ha (SINED), e chi è concorrente (LIZARD) da chi è cliente.

**Il fatto strutturale che questo screening conferma, ed è quello che vale più di ogni singola scheda:** i grandi fornitori del SSN — Dedalus, FUJIFILM, Meteda/IQVIA, Axios — hanno **tutti** la ISO 27001. La NIS2 li ha già spinti a certificarsi, perché sono abbastanza grandi da avere un ufficio qualità che ha visto arrivare la scadenza. **I bersagli sono i piccoli sotto i 50 dipendenti**: SINED (11–50), ME.S.I.S. (7), e i nomi come METROPOLIS (10–15) che stanno nella stessa tabella ma non hanno né la dimensione né il sistema. Non è un mercato saturo: è un mercato **diviso in due** dalla stessa soglia, e la metà che paga è quella sotto.
