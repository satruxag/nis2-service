# Email pronta all'invio — SINED S.r.l. (Bologna)

**Stato: PRONTA. Non inviata.** L'invio richiede il titolare umano e il suo account (vincolo non negoziabile). Questa è la versione compilata della Versione A adattata a un fornitore che ha già clienti NIS multipli.

## Perché questo destinatario (tutto verificato, non ipotizzato)

| Campo | Valore | Fonte |
|---|---|---|
| Ragione sociale | SINED S.r.l. — *Medical Computer Systems* | <https://www.sined.it/> |
| P.IVA | **01757941206** (C.F. 04226120378, REA BO 357596) | **letta sull'atto** ASL Biella 680/2026 e 642/2026; identica nel footer del sito |
| Sede | Via Ferrarese 219/7, 40128 Bologna | sito aziendale |
| Dimensione | **11–50 dipendenti** (LinkedIn: 53 profili); ~900.000 follower LinkedIn; 300+ centri installati | <https://linkedin.com/company/sined-srl>, sito aziendale |
| Gruppo | Gruppo **THÉRADIAL** (Francia), dal 2019 | sito aziendale |
| Cliente NIS | **ASL Biella** — due atti distinti del 2026: Det. 642 (Medware Nefrologia e dialisi, € 70.000) e Det. 680 (CCA/OE con Medware per la Dialisi, € 10.000) | `fonti.md` F19.a, F19.e |
| Certificazioni esposte | **ISO 9001:2015 e ISO 13485:2016 soltanto** — nessuna ISO 27001, nessuna 22301, nessuna Information Security Policy pubblica | <https://www.sined.it/certificazioni/>, Politica Qualità rev. 27/01/2026 |
| Qualifica ACN | Nessuna | Portale Cloud ACN, verifica 17/11/2026 |
| Contatto | `info@sined.it` · `giulia.marchi@sined.it` · +39 051 604 88 11 | portale Unione Terre di Pianura / sito |

**Esito dei quattro punti:** (1) cliente NIS sì, **due contratti** con ASL Biella; (2) nessuna ISO 27001 né qualifica ACN → il check-up gli serve; (3) 11–50 dipendenti, nessun CISO interno, ma un ufficio qualità abituato ai requisiti documentali; (4) leva = ASL Biella, con numero di atto e importo. **Quattro su quattro.**

**Nota che va letta prima dell'invio.** SINED espone **ISO 13485**, che per una software house sanitaria *sembra* un sistema di gestione della sicurezza. Non lo è: l'13485 certifica i processi del **dispositivo medico**, non la sicurezza delle informazioni. L'email lo dice esplicitamente — è il punto di attacco del messaggio, non un dettaglio.

## Email

**A:** info@sined.it
**Cc (se raggiungibile):** giulia.marchi@sined.it
**Oggetto:** il rinnovo Medware con ASL Biella: cosa vi chiederà la NIS2

---

Buongiorno,

scrivo a proposito del contratto che avete in essere con ASL Biella per **Medware** (nefrologia e dialisi) — affidamento del 19 giugno 2026, € 70.000, e la successiva integrazione CCA da € 10.000. Una nota su un effetto della NIS2 che riguarda voi in quanto fornitori, non ASL Biella.

Un'ASL è soggetto NIS2 di Allegato I. Fra i suoi obblighi c'è inserire **requisiti di sicurezza informatica nei contratti con i propri fornitori** (sicurezza della catena di approvvigionamento). Non è retroattivo: si attiva al primo **rinnovo o proroga** dopo la scadenza delle loro misure di sicurezza obbligatorie. Il vostro affidamento è di giugno 2026, quindi è il prossimo rinnovo il punto in cui la richiesta arriverà.

Al rinnovo vi verranno chiesti, tipicamente: gestione degli accessi e autenticazione a più fattori, processo di gestione degli aggiornamenti e delle vulnerabilità, continuità operativa documentata, e un canale di **notifica degli incidenti entro termini precisi**. Chi le ha già documentate risponde in una settimana; chi no rischia di perdere il contratto per una questione amministrativa.

Su questo una precisazione che vale la pena fare: **ISO 9001 e ISO 13485 non coprono questi requisiti**. Certificano la qualità dei processi e la conformità del dispositivo medico, non la sicurezza dei sistemi informativi. Non è una critica alla vostra certificazione — è che non è la griglia che ASL Biella vi applicherà.

Offro un check-up a prezzo fisso, **1.490 EUR**, che produce un referto scritto: quali di questi requisiti vi mancano davvero, quali il vostro sistema qualità copre già, e in che ordine affrontarli. Il referto è utilizzabile come allegato alla risposta ad ASL Biella, e come base se in futuro decideste di andare su un sistema di gestione della sicurezza certificato.

Se vi interessa, rispondo con due righe di dettaglio. Se avete già chi vi segue su questo, ignorate il messaggio.

[FIRMA TITOLARE]
[telefono] — [email]

---

## Controlli prima di premere invio

- [ ] Sostituire `[FIRMA TITOLARE]`, `[telefono]`, `[email]` con i dati reali della firma.
- [ ] Rileggere che nessuna frase dichiari clienti o esperienze non autorizzate.
- [ ] Verificare che `giulia.marchi@sined.it` sia ancora il referente attuale (la fonte è un portale pubblico: potrebbe essere datata). In caso di dubbio, inviare a `info@sined.it` e chiedere in calce «con chi posso parlare del rinnovo Medware?».
- [ ] Se non si riceve risposta entro 7 giorni, un solo follow-up di 3 righe; poi stop.

## Perché questo è il secondo invio e non il primo

ME.S.I.S. è pronta da giorni e resta il **primo** destinatario (messaggio più semplice, decisione più rapida: 7 dipendenti, un solo contratto). SINED è il **secondo**, e vale più di ME.S.I.S. in valore atteso — due contratti NIS, struttura più grande — ma è anche un contatto più delicato: ha un ufficio qualità che potrebbe rispondere «siamo certificati». L'email è scritta per neutralizzare quella risposta in anticipo. **Ordine consigliato: ME.S.I.S. prima, SINED 2–3 giorni dopo.**

---
*Preparata il 17 novembre 2026. Fatti: `fonti.md` F19.a, F19.e; scheda 3 e screening in `contatti/tools/verifica-bersaglio.md`. Vincolo: l'invio lo fa il titolare umano.*
