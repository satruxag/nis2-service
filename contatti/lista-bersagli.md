# Lista bersagli — fornitori ICT di soggetti NIS

*Il pezzo che mancava: `contatti/README.md` descrive **come** costruire la lista; questo file ne è la **prima lista concreta**. Ogni riga ha un fornitore reale, il motivo per cui è un bersaglio, e il fatto specifico da citargli. **Nessuno è stato contattato** — l'invio richiede il titolare umano.*

Ultima compilazione: **13 ottobre 2026**. I dati di contatto sono quelli pubblicati dalle aziende sui propri siti; vanno riletti prima dell'invio.

---

## Come si legge una riga

- **Chi**: ragione sociale e sito (fonte del dato).
- **Perché è bersaglio**: la ragione verificabile per cui rientra nel profilo di `perdita-di-trattativa.md` — serve un soggetto NIS riconoscibile, ha dimensione da avere il problema, non ha un ufficio interno che se ne occupa.
- **Il gancio**: il fatto puntuale da mettere nell'email. Non "la NIS2 ti riguarda", ma "il tuo cliente deve dichiarare **questo**, su di te".
- **Criterio di rilevanza atteso**: a) fornitura ICT (Allegato I, punti 8-9) e/o b) non fungibilità. Serve a scegliere la formulazione.

---

## Fascia 1 — Fornitori software/sistemi per la sanità

Perché questa fascia per prima: gli ospedali, le case di cura e le RSA sono **soggetti NIS** (allegato I, sanità), sono **pieni di fornitori ICT non fungibili**, e — fatto decisivo — il fornitore **sa già di essere critico**, perché il suo software *è* il sistema informativo del cliente. È il segmento in cui la frase "il tuo cliente deve elencarti" è più imbarazzante da sentire.

| # | Chi | Perché è bersaglio | Il gancio (fatto da citare) |
|---|---|---|---|
| 1 | **EL.CO. Srl** — software clinico per strutture sanitarie, >350 installazioni, Padova, dal 1984 · elco.it | Fornisce il sistema informativo a centinaia di strutture sanitarie pubbliche e private: molte sono soggetti NIS. Ha la dimensione per avere il problema e la concentrazione (350 clienti) per averlo su larga scala. | Il suo prodotto è dichiarato **ACN SaaS qualificato Livello 2 (QC2)**. È già nel perimetro ACN come fornitore qualificato — ma la qualificazione ACN del *servizio* non è l'adeguamento NIS2 dell'*azienda*. Il suo cliente lo elenca con CPV **72500000-0 / 72510000-3** e deve indicare il **criterio di rilevanza**. |
| 2 | **MYS Srl** — suite WebQuality per aziende sanitarie, Rovigo, 11-50 dip., dal 2004 · mys.it · info@mys.it · tel. 0425.1560001 | Software gestionale per aziende sanitarie pubbliche e private. Dimensione (11-50) = nessun ufficio compliance interno. Dichiara ISO 27001 e CSA STAR — quindi **ha già capito il valore della sicurezza**, che è il terreno giusto per vendere una diagnosi, non un prodotto. | I suoi clienti sanitari devono elencarlo con i CPV dei **servizi gestiti** (72500000-0, 72510000-3, 72250000-2). Ha le certificazioni: il check-up qui non serve a "convincerlo che la sicurezza conta", ma a **mappare i gap rispetto agli Allegati ACN**, che sono un'altra cosa dall'ISO 27001. |

## Fascia 2 — MSP / system integrator con clientela multi-settore

Perché: un MSP che serve **più soggetti NIS** è nello stesso elenco di più clienti. Non è una spesa di compliance: è **ciò che gli permette di rispondere in una settimana e non perdere il contratto**.

| # | Chi | Perché è bersaglio | Il gancio (fatto da citare) |
|---|---|---|---|
| 3 | **MiPS Informatica** — IT dal 1992, gestione infrastrutture IT + consulenza GDPR, Genova · mips-informatica.com · info@mips-informatica.com | System integrator storico con servizio esplicito di **gestione infrastrutture IT** (= servizi gestiti, criteri a) e b)) e **consulenza GDPR** — segno che vende già compliance e conosce la logica dei soggetti obbligati. Dimensione media = nessun ufficio NIS interno. | Chi lo ha in gestione infrastrutturale lo elenca con CPV **72500000-0** (servizi informatici) o **72510000-3** (servizi di gestione connessi all'informatica) — criteri a) e b) insieme, cioè "ICT non fungibile". Se gestisce anche il suo cliente, il criterio b) è quasi automatico. |
| 4 | **3MSOLUTIONS** — consulenza IT, reti, cloud, sicurezza, VoIP; Meda (MB) e Milano · 3msolutions.it | Fa **reti aziendali, cloud, sicurezza e VoIP** — tutto roba che ricade nei CPV dei servizi gestiti e delle infrastrutture digitali. Ha un case study nel **settore sanitario** (Else Solutions): quindi serve almeno un settore NIS. Dimensione piccola: il titolare risponde direttamente. | Un MSP che fornisce **connettività, cloud e sicurezza** al cliente è elencabile sotto **tre** famiglie di CPV (72500000-0 servizi informatici, 72400000-4 servizi di Internet, 64200000-8 telecomunicazioni). Tre righe in un file ACN = tre motivi per cui il cliente deve sapere cosa fai sulla sicurezza. |

## Fascia 3 — Dove cercare le righe successive (procedura, non indovinello)

Questa lista non va completata a intuito. Le righe successive si trovano così, in ordine di rendimento:

1. **Portali acquisti dei soggetti NIS.** Utility, trasporti locali, aziende sanitarie pubbliche e grandi manifatture pubblicano **informative ai fornitori** sull'obbligo di elencazione. La più nota: Gruppo IREN, *Informativa_NIS2.pdf* (`fonti.md` F12). Quei documenti **elencano le categorie di fornitura** che il soggetto considera rilevanti: è una lista di bersagli già pronta.
2. **Albi fornitori / elenchi aggiudicatari.** Chi compare come aggiudicatario di un soggetto NIS per forniture ICT (CPV 72xxxxxx, 642xxxxx) è un candidato con **prova documentale** del legame.
3. **Il criterio di conferma**: il fornitore ha **un solo cliente grande e riconoscibile**? Allora la non fungibilità (criterio b) è quasi certa, e l'email Versione B funziona meglio. Il fornitore con 300 clienti piccoli ha un problema diverso (scala) e va trattato dopo.

**Regola di conferma prima dell'invio** (dalla traccia in `contatti/README.md`): il fornitore serve un soggetto NIS **riconoscibile**? Se sì, si scrive. Se no, non si scrive — la versione B non ha aggancio.

---

## Cosa NON fare con questa lista

- **Non contattare i soggetti NIS direttamente per primi.** Hanno la scadenza addosso e hanno già cercato qualcuno: sono il canale secondario (`perdita-di-trattativa.md`). Il fornitore è il primo.
- **Non scrivere a un fornitore di cui non si conosce un cliente NIS.** L'email Versione B si regge su un fatto specifico: senza quel fatto, diventa una newsletter.
- **Non citare i 10 milioni.** A un fornitore ICT che non è ancora soggetto NIS quella cifra non si applica: si applica la logica dell'**individuazione ex art. 3, c. 13**, non la sanzione. Vedi `fonti.md` F5 e `CONTEXT.md` alla voce *Individuazione*.
- **Non promettere che "sarà individuato come soggetto NIS".** L'inserimento nell'elenco fornitori **non produce automaticamente** quell'effetto (`fonti.md` F12). Il fatto vero è più forte: *il tuo cliente ti sta dichiarando all'Autorità come dipendenza critica*.

---

*Fonti dei dati aziendali: siti aziendali (elco.it, mys.it, mips-informatica.com, 3msolutions.it) e profili LinkedIn pubblici, verificati il 13 ottobre 2026. Le ragioni di rilevanza rinviano a `fonti.md` F12 e F15. Nessun contatto è stato effettuato da questo repo.*
