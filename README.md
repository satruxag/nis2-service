# nis2-service

Materiale commerciale per un servizio di **Check-up NIS2** a prezzo fisso, rivolto a imprese italiane medie che ricadono (o potrebbero ricadere) nel D.Lgs. 138/2024.

Il prodotto è **una diagnosi**, non un adeguamento: dice se l'organizzazione è soggetto NIS e come (essenziale o importante), quali misure di base le mancano, e in che ordine intervenire.

## Documenti

| File | Cos'è |
|---|---|
| `offerta-checkup.md` | **Scheda servizio, una pagina.** Cosa consegniamo, tempi, cosa non è compreso, prezzo. |
| `email-primo-contatto.md` | **Due bozze di email a freddo** (una per soggetto NIS, una per fornitore di soggetto NIS) + note d'uso. *Da inviare solo dal titolare umano.* |
| `traccia-checkup.md` | **Scaletta della call** di inquadramento: 50 domande in 3 blocchi, e l'ordine delle priorità nel referto. |
| `fonti.md` | **Fatti normativi verificati** su fonti primarie, con URL e data di verifica. È il documento portante: tutto il resto cita questo. |
| `perdita-di-trattativa.md` | **Perché il materiale pronto non basta.** La domanda che blocca la firma, le trappole in ordine di frequenza, e l'ordine dei destinatari (il fornitore viene prima). |
| `dopo-il-checkup.md` | **La risposta alla domanda che blocca la firma:** cosa costa l'adeguamento, e cosa potete fare a costo zero. Da consegnare dopo il referto, non al posto del referto. |
| `mercato-prezzi.md` | Riferimenti di prezzo di mercato e lettura della saturazione del mercato. |
| `contatti/lista-bersagli.md` | **La lista dei destinatari, ristretta e verificata.** Criterio di conferma a quattro punti (serve un cliente NIS; **non** già qualificato ACN/ISO 27001; PMI; leva = cliente NIS). Documenta anche i due bersagli scartati dopo la verifica. |
| `contatti/README.md` | Il metodo per costruire le righe successive della lista. |
| `CONTEXT.md` | Glossario del dominio. |
| `AGENTS.md` | Istruzioni per agenti: regole, errori da non rifare, vincoli commerciali. |
| `docs/adr/` | Decisioni di prodotto (perché solo diagnosi; perché questo prezzo). |

## Il punto centrale

Le due affermazioni più ripetute sul mercato NIS2 italiano sono **imprecise**, e la differenza è verificabile:

1. **"La scadenza è il 31 ottobre 2026."** Il termine è 18 mesi dalla ricezione della comunicazione individuale di inserimento: per la coorte 2025 cade intorno a ottobre 2026, per chi è stato inserito nel 2026 è il **31 luglio 2027**. (ACN, FAQ MSB.3)
2. **"Sanzioni fino a 10 milioni o il 2%."** Vale per i **soggetti essenziali**. Per i **soggetti importanti** — dove ricade gran parte delle imprese medie — il massimo è **7 milioni o l'1,4%**. (art. 38 c. 9, D.Lgs. 138/2024)

Chi vende NIS2 citando le cifre sbagliate è riconoscibile da chi compra. Questo repo esiste anche per non essere quel fornitore.

3. **"I fornitori restano fuori dalla NIS2."** Dal 2026 i soggetti NIS — oltre **21.000**, di cui almeno 5.000 essenziali — devono comunicare all'ACN l'elenco dei propri **fornitori rilevanti** (Determinazione ACN 127437/2026, art. 18), con finestra **15 aprile – 31 maggio**. Da quell'elenco l'ACN individua ulteriori soggetti obbligati, anche piccole e micro-imprese (art. 3, c. 13). Il fornitore però **non diventa soggetto NIS automaticamente**: la formulazione corretta è che l'esposizione diventa concreta e documentata. Chi scrive la versione forte sta vendendo paura, non la norma.

## Da dove parte la vendita

Il materiale è pronto; ciò che mancava era la risposta alla domanda *"e dopo il check-up quanto mi costa tutto?"*, senza la quale la diagnosi non si vende. È in `perdita-di-trattativa.md` (il meccanismo) e `dopo-il-checkup.md` (la risposta operativa).

L'ordine dei destinatari è invertito rispetto alla prima stesura: **il fornitore di soggetto NIS viene contattato prima del soggetto NIS**. Il soggetto obbligato ha già la scadenza addosso e ha già cercato qualcuno; il fornitore scopre il rischio quando il cliente glielo comunica, ed è costretto **dal cliente** — quindi ha fretta oggi.

## Vincoli

- **Nessun contatto viene fatto da qui.** Firma, invio e incasso richiedono il titolare umano.
- **Nessun cliente viene dichiarato.** Niente case study o loghi non autorizzati per iscritto.
- **Nessun fatto normativo viene inventato.** Ogni affermazione consegnabile cita un atto e una fonte primaria in `fonti.md`.

## Stato

Materiale pronto per la vendita. Aggiornato il **20 ottobre 2026**.

**Chiuso il 20 ottobre — due cose, entrambe dal testo primario.** (1) Le cifre «**37 misure, 87 requisiti**» dell'Allegato 1 non sono più su fonte secondaria: sono contate direttamente sul documento ACN ufficiale (`fonti.md` **F16**), quindi citabili con sicurezza nel referto. (2) La lista bersagli è stata **verificata contro il Portale Cloud ACN** e **ristretta**: EL.CO. e MYS, che erano i due candidati migliori, sono risultati **già qualificati QC2 con ISO 27001** (`fonti.md` **F17**) — non comprerebbero una diagnosi, perché l'hanno già subita in sede di qualifica. La lista passa così a **un bersaglio solido (MiPS Informatica) e uno debole (3MSOLUTIONS)**, con un criterio di conferma a quattro punti che esclude i già-qualificati (ADR 0005).

Non è un passo indietro: è il passo che evita di spedire a un fornitore QC2 un'email che afferma il falso.

Manca, e richiede il titolare umano: dati di fatturazione nella scheda servizio (P.IVA, email, telefono), e l'invio delle email.
