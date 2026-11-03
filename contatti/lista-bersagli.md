# Lista bersagli — a chi si scrive

**Versione 20 ottobre 2026.** Questa lista è stata **riscritta** dopo la verifica sul Portale Cloud ACN (F17 in `fonti.md`). La versione del 13 ottobre conteneva quattro bersagli; due di essi (**EL.CO.** e **MYS**) sono risultati già qualificati QC2 con ISO 27001 — quindi **fuori bersaglio**, vedi sotto. La lista che segue è l'esito onesto di quella verifica, non l'elenco precedente.

## Il criterio di conferma (aggiornato)

Un fornitore ICT è un bersaglio per il Check-up NIS2 **solo se tutte** queste sono vere:

1. **Serve un soggetto NIS riconoscibile** — un cliente il cui settore è nell'Allegato I o III del D.Lgs. 138/2024 (sanità, energia, trasporti, acqua, infrastrutture digitali, PA…), oppure un soggetto che ha ricevuto la comunicazione di inserimento nell'elenco ACN.
2. **Non ha già una qualificazione ACN né ISO 27001 recente.** Se il fornitore è sul Portale Cloud ACN, o espone ISO 27001/22301, il check-up diagnostico gli è inutile: sa già cosa gli manca. Va escluso.
3. **È di dimensione piccola o media.** Una grande impresa ha un ufficio compliance interno; una PMI no, ed è quella che compra una diagnosi a prezzo fisso.
4. **La leva è il cliente NIS, non il fornitore stesso.** L'email funziona se può dire: «il tuo cliente [X] ti sta elencando all'ACN con questi codici».

Il punto 2 è **nuovo** e ha eliminato due dei quattro bersagli precedenti. Va applicato a ogni candidato prima di scrivere: **una ricerca sul Portale Cloud ACN (`acn.gov.it/portale/catalogo-delle-infrastrutture-digitali-e-dei-servizi-cloud`) e una sul sito del fornitore per "ISO 27001"**. Dieci minuti che evitano l'email che brucia un contatto.

## Esclusi dalla verifica del 20 ottobre (documentati, non cancellati)

**EL.CO. (Padova) — ESCLUSO.** Piattaforma *Fenix* dichiarata «ACN — servizi SaaS qualificati di Livello 2 (QC2)» sul sito aziendale (<https://www.elco.it/>). Dispositivo Medico CE classe IIA. Ha già l'apparato; non comprerebbe una diagnosi. *Fatto che resta vero e utilizzabile:* serve 350+ strutture sanitarie, che sono soggetti NIS del settore sanitario — quindi **EL.CO. è un fornitore rilevante**, ma è il *cliente* del check-up, non il *destinatario dell'email*. Escluso dall'invio, non dalla mappa.

**MYS / WebQuality (Rovigo) — ESCLUSO.** Qualificazione **QC2** sul Portale Cloud ACN, scheda **SA-3784**, valida 30/07/2025–30/07/2028, con ISO 9001, **ISO 22301**, **ISO/IEC 20000**, CSA STAR L2, **ISO 27001** (<https://www.acn.gov.it/portale/w/sa-3784>). Stesso ragionamento: ha già la griglia che gli mostreremmo. Escluso dall'invio.

## Bersagli che restano dopo il criterio aggiornato

**MiPS Informatica S.p.A. (Genova + Firenze) — BERSAGLIO, con cautela.** Il punto forte: i suoi clienti documentati *sono* soggetti NIS e sono **nominati sulla sua stessa case history** (<https://mips-informatica.com/case-history>): **Gruppo Ansaldo Energia** (settore energia — Allegato I, settore altamente critico; gruppo >40 società, quindi *soggetto essenziale*), **Università di Genova** (PA/istruzione, Allegato III), **un primario istituto bancario nazionale** (settore bancario), e un *«ente pubblico che si affida a MiPS per la sicurezza informatica»*. Serve anche un broker marittimo (trasporti). Ha un servizio dedicato di «Consulenza GDPR» e «Sicurezza informatica»: è un MSP/fornitore rilevante per almeno **tre soggetti NIS con nome e cognome**.

  **Cautela — due problemi reali.** Primo: MiPS **organizza già eventi su NIS2** («Resilienza digitale senza confini», con un panel su *«Direttiva NIS2 e gestione delle vulnerabilità»*, <https://linkedin.com/company/mips-informatica-spa>). Non è un cliente ingenuo: è un **semi-concorrente** che sta presidiando lo stesso tema. Secondo: non risulta sul Portale Cloud ACN per un servizio di *managed services* (verificare prima dell'invio) — quindi il criterio 2 potrebbe comunque reggere, ma la leva dell'email va cambiata rispetto alla Versione B generica. A MiPS **non** si scrive «sai cosa fare al primo rinnovo»: lo sa. Gli si scrive da pari, con un fatto che gli serve operativamente.

**3MSOLUTIONS srl (Meda/Milano) — BERSAGLIO DEBOLE.** La case history (<https://www.3msolutions.it/case-history/>) nomina: **Else Solutions** (*«sfide del settore sanitario»* — il cliente più NIS-adiacente), *Liceo G. Parini* (istruzione), *Federazione Pugilistica Italiana*, e poi una serie di clienti **non NIS**: Oleodinamica Seguini, Lombarda Motori (auto), Limonta (tessile), Farmacia alla Porada, FiberTech, Akron (biotech). Cioè: **la maggior parte dei suoi clienti documentati non sono soggetti NIS.** L'unico aggancio solido è Else Solutions, che però 3M descrive genericamente come «sanitario» senza dimostrare che sia soggetto NIS. Serve una verifica su Else Solutions prima di scrivere. **Non è pronto per l'invio.**

## Versione 3 novembre 2026 — il criterio 3 era sbagliato, e ora lo so

**Cosa è cambiato.** Fino a ieri la lista si basava su case history e siti aziendali: indizi. Da oggi ho due **provvedimenti di affidamento pubblici** (F19) che nominano, con ragione sociale, P.IVA e CIG, **19 imprese** che hanno già un contratto in essere con **due** soggetti NIS sanitari (ASL Biella e ASL V.C.O.). Non sono più candidati scelti da me: sono fornitori *già scelti dal cliente NIS*.

**Il criterio 3 va riscritto.** Diceva: «È PMI. Tra 50 e 250 dipendenti». I dati di registro (F19.c) lo falsificano: i fornitori di software sanitario sono **micro-imprese** — SYSTEM TECHNOLOGY S.R.L. ha **2 dipendenti** e € 707.720 di fatturato, e manutiene l'applicativo MMG/PLS di una ASL. SHORR KAN: 11–50. METROPOLIS: 10–15. Il mercato reale è questo. Il criterio corretto è:

> **Il fornitore ha un contratto con un soggetto NIS (provato dall'atto) e non ha una funzione compliance interna (provata dai dipendenti).** Sotto i ~20 dipendenti la struttura non esiste; sopra i 250 c'è un ufficio interno, non serve una diagnosi a prezzo fisso.

Il resto del criterio (punti 1, 2, 4) regge: soggetto NIS riconoscibile, assenza di ISO 27001/qualifica ACN, leva del cliente NIS.

## Bersagli verificati — dalla fonte, non dall'ipotesi

Tutti sotto hanno **contratto in essere con un soggetto NIS sanitario**, documentato da una determinazione pubblica. La colonna "esito" è la verifica preliminare (dimensione da banche dati di registro; da completare con la ricerca sul sito per ISO 27001 prima dell'invio).

| # | Impresa | P.IVA | Sede | Dimensione (fonte) | Cliente NIS documentato | Esito preliminare |
|---|---|---|---|---|---|---|
| 1 | **AXIOS INFORMATICA S.R.L.** | 03166670244 | **Vicenza** | micro (da completare) | ASL Biella (mensa/Prandium) | **verificato** — sito axios.it attivo, prodotti Prandium |
| 2 | **GIADA PROGETTI S.R.L.** | 02248420263 | (da verificare) | (da verificare) | ASL Biella; ASL5 Spezzino (Det. 1039/2026); ATS Brianza | da completare |
| 3 | **LIZARD S.R.L.** | 01867040220 | (da verificare) | (da verificare) | ASL Biella (teledidattica) | da completare |
| 4 | **ME.S.I.S. S.R.L.** | 01252940430 | (da verificare) | (da verificare) | ASL Biella (TMM/Trasfusionale) | da completare |
| 5 | **METROPOLIS S.R.L.** | 10368880158 | Assago (MI) | **10–15 dipendenti**; € 2,76 M | ASL Biella (Punti Gialli); ULSS 4 Veneto, AOU Federico II, IRCC Candiolo | candidato forte |
| 6 | **REKORDATA S.R.L.** | 05185750014 | (da verificare) | (da verificare) | ASL Biella (FileMaker) | da completare |
| 7 | **SHORR KAN S.R.L.** | 07831320010 | Torino | **11–50 dipendenti** (22 su LinkedIn) | ASL Biella (Canopo, medicina del lavoro) | **ESCLUSO** — espone ISO 27001:2022 + 27017 + 27018 + 9001 (verificato 03/11/2026) |
| 8 | **SYSTEM TECHNOLOGY S.R.L.** | 02387320985 | Botticino (BS) | 2 dipendenti | ASL Biella (MMG/PLS) | **DATO INATTENDIBILE** — la P.IVA corrisponde a una ditta CAD/CAM omonima, non al fornitore MMG/PLS: da risolvere sull'atto |
| 9 | **BIM ITALIA / GPI S.P.A.** | 01944260221 | Trento | grande gruppo | ASL Biella, ASL V.C.O. | **ESCLUSO** — il check-up non è per un gruppo da migliaia di dipendenti |
| 10 | **DEDALUS ITALIA S.P.A.** | 05994810488 | Firenze/Milano | gruppo | ASL Biella, ASL V.C.O. | **ESCLUSO** — grande fornitore sanitario strutturato |
| 11 | **METEDA S.R.L.** (impresa IQVIA) | 01713290441 | Roma / S.B. del Tronto | >50 dichiarati; gruppo IQVIA | ASL Biella (MetaClinic) | **ESCLUSO** — controllata da multinazionale |
| 12 | **TINEXTA INFOCERT S.P.A.** | 07945211006 | Roma | grande | ASL Biella (firma remota) | **ESCLUSO** — gruppo quotato |
| 13 | **ZUCCHETTI AXESS S.P.A.** | 03537610960 | Brescia | grande | ASL Biella (timbratrici) | **ESCLUSO** — gruppo Zucchetti |
| 14 | **CITTÀ STUDI S.P.A.** | 01491490023 | Biella | società partecipata pubblica | ASL Biella, ATS | **ESCLUSO** — partecipata regionale, non è una PMI privata |
| 15 | **SINED S.R.L.** | 01757941206 | (da verificare) | (da verificare) | ASL Biella (Medware nefrologia) | da completare |
| 16 | **ALFAHEALTH S.P.A.** | — | Roma | n.d. | ASL V.C.O. | da verificare |

**Ordine di lavorazione consigliato:** #1 (AXIOS INFORMATICA — identificazione confermata), #5 (METROPOLIS — 10–15 dipendenti, cliente ASL Biella), #2 (GIADA PROGETTI — **tre** clienti NIS pubblici: ASL Biella, ASL5 Spezzino, ATS Brianza; da controllare se ha ISO 27001), #4 e #6 (ME.S.I.S., REKORDATA — da completare).

**Scartati nella verifica del 3 novembre:** #7 SHORR KAN (ISO 27001 esposta) e #8 SYSTEM TECHNOLOGY (omonimia: P.IVA non attribuibile). Come da metodo: verificare costa un nome, non verificare costa l'invio.

**Cosa manca prima dell'invio.** Per i candidati "da completare" servono, per ciascuno: sito aziendale (sede, persone, email diretta non `info@`), ricerca `ISO 27001` sul sito, ricerca sul Portale Cloud ACN. Sono 10 minuti a testa, ripetibili con la scheda `contatti/tools/verifica-bersaglio.md`. **Un nome senza quei tre controlli non entra in lista.**

## Restano in mappa (non destinatari)

**MiPS Informatica S.p.A.** e **3MSOLUTIONS srl**: invariati rispetto alla versione del 20 ottobre — MiPS è **semi-concorrente** (organizza eventi NIS2, ha case history con clienti NIS nominati) e 3MS resta **debole** (cliente sanitario non dimostrato). Nessuno dei due è pronto per l'invio.

**EL.CO. (Padova)** e **MYS / WebQuality (Rovigo)**: esclusi (QC2 + ISO 27001). Documentati, non cancellati.

## Cosa fare, concretamente, al prossimo giro

La lista è passata da **quattro nomi con leva già scritta** a **un nome solido (MiPS, da rifinire) più uno debole (3MSOLUTIONS, da verificare)**. Non è un passo indietro: è la conseguenza di aver verificato. L'alternativa era spedire a EL.CO. e MYS un'email che li avrebbe fatti sorridere.

Il criterio 2 è anche il modo per **trovarne di nuovi in fretta**: sul Portale Cloud ACN, i *non* presenti sono la lista dei candidati. La mossa del prossimo giro è prendere 10 MSP che servono ospedali/utility nel Nord Italia e passare ciascuno per il filtro dei quattro punti.

## Vincoli che non cambiano

- L'invio richiede il **titolare umano** e il suo account. Nessuna email parte da qui.
- **Nessun cliente esistente va dichiarato** in questi materiali.
- Prima di ogni invio: sostituire tutti i segnaposto e rileggere i fatti di `fonti.md` che l'email cita.
