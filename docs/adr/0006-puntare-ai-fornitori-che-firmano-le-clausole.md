# 0006 — Il bersaglio si cerca dagli allegati contrattuali NIS2, non dai portali acquisti

- **Stato:** accettata
- **Data:** 27 ottobre 2026

## Contesto

Con l'ADR 0005 la lista bersagli era stata ristretta a un criterio a quattro punti, e restavano due nomi. Il 27 ottobre ho compilato la scheda di verifica (`contatti/tools/verifica-bersaglio.md`) su entrambi, leggendo direttamente i siti aziendali invece della sola case history:

- **MiPS Informatica** ha **33 dipendenti** (sotto la soglia dei 50) e vende essa stessa *«Legal & Compliance Service: GDPR, NIS2, ISO 27001»* con un SOC/NOC H24, oltre a organizzare eventi su NIS2. È un **concorrente attrezzato**, non un cliente.
- **3MSOLUTIONS** era già escluso: l'unico cliente sanitario nominato (Else Solutions) non è dimostrato soggetto NIS.

La lista dei destinatari è quindi **vuota**. Nella stessa giornata ho reperito, scaricato e letto un **documento primario nuovo** (`fonti.md` F18): un allegato contrattuale NIS2 pubblicato da **A.S.L. V.C.O.**, con 13 obblighi numerati e sette termini in giorni/ore imposti al fornitore (patch critiche a 7 giorni, notifica incidenti a 24 ore, log 12 mesi, SBOM, audit annuali).

## Decisione

Il metodo di ricerca dei destinatari cambia punto di partenza. Non più «dal portale acquisti di un soggetto NIS ai suoi avvisi generici», ma:

**Dagli allegati contrattuali NIS2 che le stazioni appaltanti pubblicano insieme ai bandi, ai fornitori ICT che quei bandi li eseguono.**

Il filtro in tre passi (dettagliato in `contatti/README.md`, addendum 27 ottobre): cercare gli allegati contrattuali che contengono NIS2 → risalire all'ente che li ha pubblicati → il bersaglio sono **i suoi fornitori ICT PMI**, che devono compilare la checklist di conformità allegata al contratto.

## Perché

F18 cambia la qualità del fatto citabile. Prima l'email poteva dire: «la norma prevede la sicurezza della catena di fornitura, e dal 15 aprile al 31 maggio il tuo cliente ti elenca». Vero, ma **astratto**: un fornitore può rispondere «me ne occupo al rinnovo».

Ora può dire: «la tua ASL ha allegato al contratto una clausola con **patch critiche a 7 giorni lavorativi** e **notifica incidenti a 24 ore**; ecco i 13 adempimenti». È un fatto che il destinatario **non può contestare**, perché è nel documento che gli verrà chiesto di firmare. E l'ente che ha pubblicato l'allegato **dichiara, con quel gesto, di essere soggetto NIS** — non serve più indovinarlo.

L'economia della ricerca migliora di conseguenza: il documento esiste, è pubblico, è datato, e porta con sé sia il fatto sia la prova che l'ente è in perimetro.

## Alternative considerate

- **Tenere il metodo dei portali acquisti e cercare dieci MSP «a mano».** Non scartata in sé, ma è ciò che ha prodotto due candidati sbagliati su due. Il nuovo metodo dà una fonte primaria da cui partire invece di un criterio da applicare alla cieca.
- **Cambiare prodotto: vendere la redazione delle clausole alle stazioni appaltanti.** Scartata per ora: l'ente ha già i suoi consulenti (la clausola ASL V.C.O., redatta da un ufficio QHSE esterno, lo dimostra), e il ciclo di vendita pubblico è lungo e a gara — l'opposto di ciò che serve a un incasso rapido.
- **Ammettere che il mercato è saturo e fermarsi.** Scartata perché F18 è un fatto *nuovo* che allarga il bacino: ogni allegato contrattuale NIS2 pubblicato è un insieme di fornitori già in obbligo, e ce ne sono quanti sono gli enti che hanno iniziato a imporlo.

## Conseguenze

- **La lista dei destinatari è vuota e va ricostruita col nuovo metodo.** Non è un arretramento del materiale: è l'esito di aver verificato. La prossima run deve aprire bandi con allegati NIS2 e nominare il fornitore.
- **La scheda di verifica è ora lo strumento operativo** (`contatti/tools/verifica-bersaglio.md`): nessun candidato entra in lista senza tutte e quattro le colonne a `OK`. La lezione registrata: dimensione e offerta concorrente si leggono su «chi siamo» e sulla pagina dei servizi, non sulla case history — e una fonte che sparisce (404) non è più una fonte.
- **Il referto guadagna un uso nuovo e verificabile**: è direttamente riusabile come risposta documentata alla *Checklist di Conformità ICT & Cybersecurity* allegata a contratti come quello di ASL V.C.O.
- **Cautela da mantenere:** l'allegato di ASL V.C.O. è l'atto di **una** stazione appaltante, non un modello nazionale. Va citato come esempio reale, non come obbligo generale.
