# AGENTS.md — nis2-service

Istruzioni per agenti che lavorano su questo repo.

## Regola numero uno
**Non inventare mai un fatto normativo.** Questo repo vende una diagnosi su una norma sanzionatoria. Una data sbagliata o un articolo citato male distrugge la credibilità dell'offerta e può indurre il cliente in errore.

Ogni affermazione normativa in un documento consegnabile deve avere:
1. L'atto esatto (es. "Determinazione ACN n. 379907/2025, art. 4").
2. Una data o un periodo di riferimento.
3. Una fonte verificabile (URL a fonte primaria: ACN, Normattiva, Gazzetta Ufficiale).

Le fonti già verificate sono in `fonti.md`, con la data di ultima verifica. **Se una fonte in `fonti.md` ha più di 3 mesi, ri-verificarla prima di riusarla**: ACN ha già sostituito una Determina (164179/2025 → 379907/2025) e modificato i termini sostanziali tra il 2025 e il 2026.

## Errori da non rifare
Questi sono errori già commessi o intercettati in questo repo. Non reintrodurli.

- **"La scadenza NIS2 è il 31 ottobre 2026" come data unica.** È falso come affermazione generale. Il termine è *18 mesi dalla ricezione della comunicazione individuale di inserimento nell'elenco*: per la coorte iscritta nel 2025 cade intorno a ottobre 2026, ma la data esatta è individuale, e per i soggetti inseriti per la prima volta nel 2026 il termine è **31 luglio 2027**. Vedi `fonti.md` F2.
- **"Fino a 10 milioni o 2% del fatturato" come sanzione per le PMI.** Il massimo di 10M/2% vale per i soggetti *essenziali*. Per i soggetti *importanti* — dove ricadono gran parte delle imprese medie — il massimo è **7M€ o 1,4%**. Vedi `fonti.md` F5.
- **"La certificazione NIS2".** La NIS2 non prevede uno schema di certificazione. Si parla di adeguamento a misure di base e, in prospettiva, di schemi di certificazione di cui all'art. 27. Non usare la parola "certificazione" per descrivere il prodotto.
- **"Sanatoria" o "regolarizzazione" a scadenza.** Non esistono nella norma. Non prometterle.
- **Promettere l'attestazione di conformità come esito del check-up.** L'attestazione dichiara che le misure *sono implementate*. Una diagnosi non implementa nulla. Vedi `CONTEXT.md`.

## Vincoli commerciali
- **Non dichiarare clienti esistenti.** Non usare loghi, nomi o case study che non siano autorizzati per iscritto dal titolare.
- **Non contattare nessuno.** L'invio di email di primo contatto, la firma dei contratti e l'incasso richiedono il titolare umano e i suoi account. L'agente produce materiale, non vende.
- **Non fissare prezzi senza confronto di mercato.** I prezzi in `offerta-checkup.md` derivano dai riferimenti in `mercato-prezzi.md`. Se si cambia prezzo, aggiornare il confronto e spiegare perché.
- **Non inventare credenziali professionali.** Il titolare ha 20+ anni di esperienza reale in infrastrutture Linux enterprise, hardening, Kubernetes, PostgreSQL, NIS2/ISO 27001. Non aggiungere certificazioni, partner, o accreditamenti ACN che non ha.

## Cosa dire apertamente se è vero
Se il mercato dell'"adeguamento NIS2 chiavi in mano" è saturo di offerte a basso costo, dirlo. Non gonfiare la proposta. L'angolo difendibile di questa offerta non è il prezzo più basso: è la diagnosi tecnica rigorosa fatta da chi amministra davvero infrastrutture, e la disponibilità a dire "non sei soggetto NIS" quando è vero.

## Lingua
Italiano, registro tecnico-professionale. "Lei". Nessun gergo marketing, nessun superlativo.
