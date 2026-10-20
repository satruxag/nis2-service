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

## Cosa fare, concretamente, al prossimo giro

La lista è passata da **quattro nomi con leva già scritta** a **un nome solido (MiPS, da rifinire) più uno debole (3MSOLUTIONS, da verificare)**. Non è un passo indietro: è la conseguenza di aver verificato. L'alternativa era spedire a EL.CO. e MYS un'email che li avrebbe fatti sorridere.

Il criterio 2 è anche il modo per **trovarne di nuovi in fretta**: sul Portale Cloud ACN, i *non* presenti sono la lista dei candidati. La mossa del prossimo giro è prendere 10 MSP che servono ospedali/utility nel Nord Italia e passare ciascuno per il filtro dei quattro punti.

## Vincoli che non cambiano

- L'invio richiede il **titolare umano** e il suo account. Nessuna email parte da qui.
- **Nessun cliente esistente va dichiarato** in questi materiali.
- Prima di ogni invio: sostituire tutti i segnaposto e rileggere i fatti di `fonti.md` che l'email cita.
