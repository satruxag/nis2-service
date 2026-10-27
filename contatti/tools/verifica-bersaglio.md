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
