# Traccia del Check-up — domande per la call

Uso interno. Non è un questionario da mandare al cliente: è la scaletta per condurre la **chiamata di inquadramento da 45 minuti** e per preparare la verifica.

**Regola della call:** non proporre soluzioni. Questa è una diagnosi. Se il cliente chiede "e quindi cosa dobbiamo fare", la risposta è "ve lo scrivo nel referto".

---

## Blocco 0 — Perimetro dell'impegno (5 min)

Scopo: fissare cosa è e cosa non è incluso, prima di raccogliere qualsiasi informazione. Evita la conversazione che finisce con "pensavo fosse compreso".

1. Conferma: il Check-up produce un referto di applicabilità e di adeguamento. **Non** comprende implementazione, **non** comprende piano di adeguamento con costi, **non** comprende attestazione di conformità. Confermato?
2. Chi è il referente tecnico e quante ore può dedicare? (Serve 2–3 ore totali. Se dice "nessuno", l'ambito va ridotto.)
3. C'è già qualcuno che vi segue su questo? Se sì, chi e con quale mandato? *(Non è una domanda di cortesia: se hanno un consulente attivo, cambia la natura del lavoro e può non esserci spazio.)*

---

## Blocco 1 — Applicabilità (10 min) → determina il resto

**Questa è la parte che non si può sbagliare: se salta, tutto il referto è inutile.**

### 1.1 Stato rispetto all'ACN
4. **In quale anno siete stati inseriti nell'elenco dei soggetti NIS?** (2025 o 2026, o non inseriti?)
5. **Avete ricevuto la comunicazione di inserimento al domicilio digitale?** In che data? *(Da qui decorre il termine: 18 mesi. Questa data va nel referto.)*
6. **La registrazione è stata presentata entro il 28 febbraio?** E per l'anno corrente?
7. Avete designato un **punto di contatto**? Chi è? Ha caricato il titolo giuridico che lo abilita?
8. La **dichiarazione NIS** è stata compilata in tutte e quattro le sezioni (contesto, caratterizzazione, tipologie di soggetto, autovalutazione)?
9. Avete aggiornato le informazioni nella finestra **15 aprile – 31 maggio** (contatti, organi, IP pubblici, domini, fornitori NIS rilevanti)?
10. Avete comunicato l'elenco di **attività e servizi** (categorizzazione) nella finestra **1º maggio – 30 giugno**?

> *Nota per il consulente: le voci 6, 9 e 10 sono adempimenti sanzionati in via autonoma (art. 38 c. 11), indipendentemente dall'adozione delle misure. Molti clienti li hanno saltati. Vanno verificati sempre, anche se il cliente si presenta come "già a posto".*

### 1.2 Settore e dimensione
11. Settore di attività e codice ATECO principale. *(Da incrociare con gli Allegati I e II del D.Lgs. 138/2024.)*
12. Dipendenti e fatturato/totale di bilancio dell'ultimo esercizio. *(Soglia: >50 dipendenti oppure >10 M€.)*
13. Siete fornitori di un soggetto NIS o di una PA? Con quali contratti e con quali date di rinnovo?

### 1.3 Esito intermedio da dichiarare in call
14. **Se non risulta soggetto NIS:** dirlo subito, in call. Il referto formalizzerà l'analisi, ma non far maturare un'aspettativa. Verificare comunque il lato fornitura: è lì che il rischio si materializza.
15. **Se soggetto:** essenziale o importante? Da quale criterio? *(Determina il termine, l'Allegato da usare per la verifica e il massimo sanzionatorio: 1,4% se importante.)*

---

## Blocco 2 — Matrice di adeguamento (20 min)

Verifica contro **Allegato 1** (importanti) o **Allegato 2** (essenziali) della **Determinazione ACN 379907/2025**, per cluster.

**Metodo:** per ogni misura, la domanda non è "lo fate?" ma **"esiste un documento o una configurazione che lo dimostra oggi?"**. La Determina richiede *evidenze documentali*, non buone intenzioni. La risposta "sì, ma non è scritto" equivale a un gap.

### 2.1 Governance (GV)
16. Chi ha **approvato** formalmente le modalità di implementazione delle misure di gestione del rischio? Esiste un verbale?
17. Gli organi di amministrazione hanno ricevuto **formazione specifica** sulla sicurezza informatica? Quando, e c'è un registro?
18. Esiste un **piano di gestione del rischio** documentato? Di quando è l'ultima revisione?
19. È identificato un **referente CSIRT** (ed eventuali sostituti) all'interno dell'organizzazione di sicurezza informatica?
20. Esiste un **elenco del personale** dell'organizzazione di sicurezza informatica?

### 2.2 Fornitori e catena di approvvigionamento (GV.SC)
21. Esiste un **inventario dei fornitori** e dei servizi erogati loro/dal loro?
22. Esiste un **elenco dei fornitori NIS rilevanti**?
23. I contratti in essere contengono **requisiti di sicurezza**? Ce ne sono in scadenza o in rinnovo nei prossimi 12 mesi? *(È il punto in cui si crea o si evita un'obbligazione.)*

### 2.3 Identificazione e governo degli asset (ID)
24. Esiste un **inventario di apparati, servizi, sistemi e applicazioni software**? È aggiornato? Chi lo tiene?
25. Esiste una mappatura dei **flussi di rete** (richiesta per i soggetti essenziali)?
26. I **sistemi ai quali è possibile accedere da remoto** sono elencati?

### 2.4 Protezione (PR)
27. **Autenticazione multifattore**: dove è attiva e dove no? *(Domanda operativa: sull'accesso VPN? sull'ERP? sulle caselle email? sull'amministrazione dei server? Elencare per sistema, non rispondere "sì".)*
28. Cifratura dei dati a riposo e in transito: dove?
29. **Gestione delle vulnerabilità**: esiste un piano documentato? Con quali tempistiche di remediation?
30. **Backup**: esiste un piano di continuità e ripristino? Le **verifiche di ripristino** vengono eseguite e registrate? Con quale periodicità? *(La verifica del backup è un requisito esplicito: un backup mai testato è un'assunzione, non un controllo.)*
31. **Configurazione dei sistemi perimetrali**: esiste una baseline documentata?
32. **Gestione degli endpoint**: c'è un inventario e un controllo?
33. Le **politiche** sono definite e **rese note** alle articolazioni competenti, tenendo conto del need-to-know?

### 2.5 Rilevamento (DE)
34. Cosa **registra log** e per quanto tempo? I log sono **conservati** e protetti?
35. Esiste un **monitoraggio** con chi guarda gli alert, e quando? C'è qualcuno di turno fuori orario?
36. Come si accorge l'azienda di un attacco? In pratica: chi se ne accorgerebbe, e dopo quanto?

### 2.6 Risposta (RS) — qui sta il rischio più immediato
37. Esiste un **piano di risposta agli incidenti** scritto?
38. **Chi decide cosa, in quale ordine, quando scatta un incidente?** C'è un elenco di contatti aggiornato?
39. Come si valuta se un incidente è "significativo" e va notificato? Chi applica i criteri delle fattispecie IS-1/IS-2/IS-3 (e IS-4 per gli essenziali)?
40. **Sapete scrivere e inviare una pre-notifica al CSIRT Italia entro 24 ore?** Chi la scrive, in che formato, se questa persona non c'è?
41. C'è un **registro degli incidenti** storici? Quanti negli ultimi 24 mesi, e come sono stati gestiti?

> *Il punto 40 è quello che produce più lavoro di remediation di qualunque altro. La finestra delle 24 ore decorre da quando il soggetto ha gli elementi oggettivi — "a valle di un'analisi anche sommaria". Un'organizzazione senza escalation scritta e senza registro eventi non riesce a rispettare 24 ore, indipendentemente da quanta tecnologia ha.*

### 2.7 Ripristino (RC)
42. Esistono piani di **continuità operativa** e **disaster recovery**? Sono stati provati? Quando?
43. Qual è il tempo di ripristino accettabile per il servizio principale? È scritto da qualche parte?
44. Esiste un **piano di adeguamento** documentato (richiesto dalla Determina)?

### 2.8 Formazione
45. Esiste un **piano di formazione** in materia di sicurezza informatica? A chi si applica?
46. Esiste un **registro delle attività di formazione** dei dipendenti? Quando è stata l'ultima?

---

## Blocco 3 — Chiusura (10 min)

47. Quali sono le **tre cose** che, se andassero giù oggi, fermerebbero l'azienda? *(Serve a ordinare le priorità nel referto: il rischio normativo va pesato contro il rischio operativo, e il cliente deve riconoscere la propria azienda nel documento.)*
48. C'è un budget o una finestra temporale per questo tema nell'anno? *(Non per vendere: per calibrare il tono del referto. Se non c'è budget, elencare azioni a costo quasi nullo.)*
49. Chi leggerà il referto, oltre al referente tecnico? **Il referto va scritto anche per chi firma**, non solo per chi amministra i sistemi.
50. Prima di chiudere: riepilogare cosa consegniamo, entro quando, e cosa serve da loro. Fissare la data di consegna del referto.

---

## Dopo la call: ordine delle priorità nel referto

1. **Gli adempimenti già scaduti e non fatti** (registrazione, aggiornamento, categorizzazione). Sono violazioni autonome, si cumulano con le altre, e si chiudono subito. Vanno in testa.
2. **La capacità di notificare entro 24 ore.** Rischio immediato e alta visibilità in caso di incidente.
3. **I gap di governance** (approvazione formale, formazione degli organi, referente CSIRT): costano poco, sono verificabili per primi da un'ispezione, e l'esposizione è personale per gli amministratori.
4. **Gli inventari** (apparati, servizi, software, accessi remoti): senza inventario nessuna delle misure successive è dimostrabile.
5. **I controlli tecnici** (MFA, gestione vulnerabilità, backup verificati, log): richiedono più tempo e più budget, vanno dopo.
6. **La catena di fornitura**: da coordinare con il calendario dei rinnovi contrattuali.

---

## Note sul tono del referto

- **Non gonfiare la paura.** Usare la cifra corretta per la categoria del cliente. Un soggetto importante ha un massimo di 1,4%, non 2%. Citare il 2% a un soggetto importante è un errore tecnico e si nota.
- **Dire quando va bene.** Se 20 misure su 30 sono a posto, il referto lo deve dire chiaramente. Un referto che elenca solo i problemi è inutilizzabile dal cliente e non gli permette di decidere.
- **Dichiarare i limiti.** Il referto è una valutazione documentale basata sulle informazioni e sulle evidenze fornite, alla data indicata. Non è un'ispezione tecnica e non certifica l'assenza di vulnerabilità. Va scritto nel referto, non solo pensato.
- **Nessuna promessa di conformità.** Il referto dice cosa risulta. Non dice "sarete conformi".
