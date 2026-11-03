# Fonti verificate — NIS2 Italia

**Ultima verifica: 22 settembre 2026.** Ogni voce ha un ID. I documenti consegnabili citano l'ID e l'atto.

Regola: quando una fonte primaria contraddice una fonte secondaria, vale la primaria. In questo file le voci marcate **[PRIMARIA]** sono state lette sul sito dell'atto o dell'autorità che lo emette.

---

## F1 — L'atto base [PRIMARIA]

**D.Lgs. 4 settembre 2024, n. 138**, "Recepimento della direttiva (UE) 2022/2555" (c.d. *decreto NIS*). Pubblicato in GU Serie Generale n. 230 del 01-10-2024, in vigore dal **16 ottobre 2024**.

- Fonte: <https://www.gazzettaufficiale.it/eli/id/2024/10/01/24G00155/SG>
- Testo vigente art. 38: <https://portalenormativo.it/articolo/dlgs-2024-09-04-138/art-38>
- Normattiva (atto completo): <https://www.normattiva.it/atto/caricaDettaglioAtto?atto.codiceRedazionale=24G00155&atto.dataPubblicazioneGazzetta=2024-10-01>

ACN è l'Autorità nazionale competente NIS e punto di contatto unico. CSIRT Italia è il team di risposta.

## F2 — Il termine per le misure di sicurezza NON è "il 31 ottobre 2026" [PRIMARIA]

Questa è la correzione più importante di questo file. La data "31 ottobre 2026", ripetuta da molte fonti secondarie e da molto materiale commerciale, è **un'approssimazione**, non la norma.

Il termine è **differenziato per coorte**, e decorre da un evento individuale (la ricezione della comunicazione di inserimento nell'elenco), non da una data di calendario comune:

- Soggetti inseriti nell'elenco **nel corso del 2025**: termine **18 mesi dalla ricezione della comunicazione di inserimento**. Poiché ACN ha notificato l'inserimento intorno ad aprile 2025, la scadenza ricade **intorno a ottobre 2026** — da qui nasce la data "31 ottobre 2026".
- Soggetti inseriti nell'elenco **per la prima volta nel 2026**: termine **31 luglio 2027**.

Fonte primaria — FAQ ACN "Misure di sicurezza e notifica di incidenti", risposta MSB.3:
<https://www.acn.gov.it/portale/en/faq/nis/misure-di-sicurezza-e-notifica-di-incidenti> (versione IT: <https://www.acn.gov.it/portale/faq/nis/misure-di-sicurezza-e-notifica-di-incidenti>)

> MSB.3: «per i soggetti inseriti nell'elenco dei soggetti NIS per la prima volta nel corso dell'anno solare 2026, il termine scade il 31 luglio 2027.»

e, per la coorte 2025: «il termine è fissato in diciotto mesi dalla ricezione da parte del soggetto della comunicazione di inserimento nell'elenco».

**Conseguenza operativa per la vendita:** la prima domanda da fare a un potenziale cliente non è "quando scade", ma **"in che anno siete stati inseriti nell'elenco, e avete ricevuto la comunicazione ACN?"**. Chi è stato inserito nel 2026 ha tempo fino a luglio 2027 — e questo va detto, anche se riduce l'urgenza, perché è vero. Chi è nella coorte 2025 ha il termine addosso adesso.

## F3 — Atto che fissa le misure: Determinazione ACN n. 379907/2025 [PRIMARIA]

**Determinazione ACN n. 379907 del 19 dicembre 2025**, applicabile dal **15 gennaio 2026**. Sostituisce e abroga la Determinazione n. 164179 del 14 aprile 2025. Fissa:
- le **misure di sicurezza di base**: **Allegato 1** per i soggetti importanti, **Allegato 2** per i soggetti essenziali — con le corrispondenti tabelle di policy in appendice;
- gli **incidenti significativi di base**: **Allegato 3** per i soggetti importanti, **Allegato 4** per i soggetti essenziali.

- Atto: <https://www.acn.gov.it/portale/documents/d/guest/detacn_obblighi_2511-v3_signed>
- Riferimento nella pagina ACN "Modalità e specifiche di base": <https://www.acn.gov.it/portale/nis/modalita-specifiche-base>
- Guida alla lettura delle specifiche di base (ACN, dicembre 2025): <https://www.acn.gov.it/portale/documents/d/guest/guida-alla-lettura-specifiche-di-base>

**Attenzione a due cose:**
1. **Allegato 1 ≠ Allegato 2.** Un'offerta che promette "verifica sull'Allegato 1" è sbagliata per un soggetto essenziale. L'applicabilità va determinata *prima* di scegliere l'allegato.
2. La Determina 379907/2025 è già un **rifacimento** della 164179/2025. ACN ha modificato la disciplina nel giro di pochi mesi e continuerà a farlo. Non congelare mai questi riferimenti in un documento senza data di verifica.

## F4 — Numero di misure e requisiti (fonte secondaria, usare con cautela)
Da ICT Security Magazine (fonte secondaria specializzata): l'Allegato 1 conterrebbe **37 misure / 87 requisiti**, l'Allegato 2 **43 misure / 116 requisiti**, strutturate sui cluster del Framework Nazionale per la Cybersecurity e Data Protection (**GV** Governance, **ID** Identificazione, **PR** Protezione, **DE** Rilevamento, **RS** Risposta, **RC** Ripristino).

- Fonte: <https://www.ictsecuritymagazine.com/notizie/nis2-adempimenti/> (22 settembre 2026)

**Da verificare direttamente sugli allegati della Determina prima di mettere questi numeri in un documento consegnabile al cliente.** I numeri sono coerenti con i due allegati distinti citati da ACN, ma la fonte è secondaria.

## F5 — Sanzioni: i massimi sono DIFFERENZIATI [PRIMARIA]

**Art. 38, comma 9, D.Lgs. 138/2024.** La formulazione corretta:

| Destinatario | Massimo edittale | Minimo |
|---|---|---|
| **Soggetti essenziali** (escluse le PA) | **10.000.000 EUR o 2%** del fatturato annuo mondiale dell'esercizio precedente, se superiore | 1/20 del massimo |
| **Soggetti importanti** (escluse le PA) | **7.000.000 EUR o 1,4%** del fatturato annuo mondiale dell'esercizio precedente, se superiore | 1/30 del massimo |

Il computo del fatturato segue la Raccomandazione 2003/361/CE. Le sanzioni colpiscono la violazione degli obblighi degli **artt. 23** (organi di amministrazione e direttivi), **24** (gestione del rischio) e **25** (notifica incidenti) — comma 8, lett. a).

Fonte primaria (testo dell'articolo): <https://portalenormativo.it/articolo/dlgs-2024-09-04-138/art-38>

**Perché conta commercialmente:** l'errore più diffuso nel materiale commerciale è citare "10 milioni o 2%" come cifra *generale* della NIS2. Per un soggetto importante — cioè per buona parte delle imprese medie italiane — il massimo è **7M€ o 1,4%**. Usare la cifra giusta per la categoria giusta è, da solo, una dimostrazione di competenza che il materiale gonfiato non ha. Non gonfiare la paura: se il cliente è importante, dire 1,4%.

Sanzioni ulteriori di rilievo: art. 38 comma 11 punisce la **mancata registrazione, comunicazione o aggiornamento** delle informazioni (art. 7) e la mancata comunicazione dell'elenco di attività e servizi (art. 30, c. 1), con massimi dello **0,1%** (essenziali) e **0,07%** (importanti) del fatturato mondiale; l'art. 38 comma 13 prevede che in caso di mancata o tardiva registrazione si applichino *anche* le sanzioni dei commi 8 e 10 con aumento fino al triplo. Comma 15: strumenti deflativi — **invito a conformarsi** (se ottemperi nei termini, il procedimento non prosegue) e **pagamento in misura ridotta** pari a 1/3 del massimo (o doppio del minimo, se più favorevole) entro 60 giorni.

## F6 — Notifica incidenti: pre-notifica 24 ore, notifica completa 72 ore [PRIMARIA]

Fonte primaria — FAQ ACN, risposte ISB.G.3 e ISB.G.4.

> «I soggetti NIS sono tenuti a segnalare allo CSIRT Italia gli incidenti significativi trasmettendo una **pre-notifica** senza ingiustificato ritardo e comunque **non oltre 24 ore** da quando ne sono venuti a conoscenza.»

> «A seguito della pre-notifica, senza ingiustificato ritardo e comunque **non oltre 72 ore**, i soggetti NIS sono tenuti a trasmettere allo CSIRT Italia la **notifica completa** dell'incidente significativo.»

Il termine delle 24 ore decorre **dal momento in cui il soggetto dispone**, a valle di un'analisi anche sommaria, **degli elementi oggettivi** dai quali si evince che si è verificata una delle fattispecie. L'evidenza si acquisisce tipicamente da: segnalazioni esterne (es. CSIRT Italia), segnalazioni interne (es. utente che chiama l'help desk), eventi dai sistemi di monitoraggio.

Fonte: <https://www.acn.gov.it/portale/faq/nis/misure-notifiche-base> e <https://www.acn.gov.it/portale/en/faq/nis/misure-di-sicurezza-e-notifica-di-incidenti>

**Conseguenza operativa:** la finestra delle 24 ore si apre quando *si sa*, non quando si indaga. Un'organizzazione senza un canale di escalation definito e senza un registro degli eventi di sicurezza non riesce a rispettare 24 ore, qualunque sia la sua tecnologia. È uno dei gap più vendibili e più facili da chiudere.

Regime applicabile dal **15 gennaio 2026** (Determina 379907/2025, art. 3 c. 2). Per i soggetti inseriti nel 2025 l'obbligo di notifica è scattato a 9 mesi dalla comunicazione (per la prima coorte, intorno a metà gennaio 2026).

Quattro fattispecie di incidente significativo (Determina 379907/2025, All. 3 e 4):
- **IS-1** violazione della riservatezza dei servizi e attività;
- **IS-2** violazione dell'integrità;
- **IS-3** prevalentemente violazione della disponibilità;
- **IS-4** accesso non autorizzato o abuso dei privilegi concessi (fattispecie ulteriore, per i soli soggetti essenziali).

Fonte: <https://www.acn.gov.it/portale/faq/nis/misure-notifiche-base>

## F7 — Registrazione: finestra annuale, non una tantum [PRIMARIA]

La registrazione avviene **dal 1º gennaio al 28 febbraio di ogni anno** sulla piattaforma digitale ACN. Non è un adempimento una volta per tutte: si registra **o si aggiorna** la registrazione ogni anno.

- Fonte: <https://www.acn.gov.it/portale/nis/registrazione>
- Determinazione ACN n. 379887/2025 (funzionamento della Piattaforma NIS), applicabile dal 31 dicembre 2025: <https://www.acn.gov.it/portale/documents/d/guest/detacn_piattaformanis_251218-v9_signed>
- Piattaforma: <https://portale.acn.gov.it/>

Fasi: censimento del **punto di contatto** → associazione al soggetto (chiusa con invio di link di convalida al domicilio digitale del soggetto) → compilazione della **dichiarazione NIS** in 4 sezioni (contesto, caratterizzazione, tipologie di soggetto, autovalutazione). Il punto di contatto deve caricare il titolo giuridico che lo abilita (salvo sia il rappresentante legale o un procuratore generale).

Aggiornamento delle informazioni: **15 aprile – 31 maggio** (contatti, organi, Stati membri serviti, intervalli IP pubblici e nomi di dominio; dal 2026 anche l'elenco dei fornitori NIS rilevanti). Comunicazione di attività e servizi (categorizzazione, art. 30 c. 1): **1º maggio – 30 giugno**.

Vademecum ACN 2026: <https://www.acn.gov.it/portale/documents/20119/600993/VademecumNIS_2026_v1.pdf/9631c10d-9157-ae43-43b3-a353aa962d09>

## F8 — Chi è nell'ambito [PRIMARIA / normativo]

Criteri art. 3: **settore** (Allegati I e II del decreto) + **dimensione**. Soglia dimensionale di riferimento: oltre **50 dipendenti** oppure oltre **10 milioni EUR** di fatturato o totale di bilancio annuo. Alcune categorie rientrano a prescindere dalla dimensione (fornitori di reti pubbliche, DNS, registri TLD, certe PA).

**Il punto che riguarda le PMI sotto soglia:** una PMI può essere attratta nell'ambito come **fornitore di un soggetto essenziale o importante**, per effetto degli obblighi sulla sicurezza della catena di approvvigionamento (misura GV.SC-01 della Determina 379907/2025 richiede che il cliente NIS definisca requisiti di sicurezza sulle forniture). Questo è il canale di ingresso reale per le imprese piccole: *non* perché sono soggetti NIS, ma perché i loro clienti NIS glielo chiedono — o glielo chiederanno in sede di rinnovo contrattuale.

Fonte: <https://www.acn.gov.it/portale/nis/ambito> ; FAQ ACN sezione "Ambito" ; per GV.SC-01 e contratti: FAQ ACN MSB.16 e successiva, <https://www.acn.gov.it/portale/en/faq/nis/misure-di-sicurezza-e-notifica-di-incidenti>.

Nota utile per il contratto: dall'art. 4 della Determina, i requisiti di sicurezza vanno inseriti nei contratti **stipulati, rinnovati o prorogati** a partire dal termine di adozione delle misure; l'adeguamento retroattivo dei contratti già in essere non è richiesto. Quindi il momento in cui un fornitore riceve la richiesta è spesso **il rinnovo**.

## F9 — Governance: responsabilità degli organi [PRIMARIA / normativo]

Art. 23 del decreto: gli organi di amministrazione e direttivi approvano le modalità di implementazione delle misure di gestione del rischio, sovraintendono all'attuazione, **rispondono delle violazioni**, seguono formazione specifica. Art. 38 comma 9 e art. 20: la responsabilità degli amministratori è personale e non delegabile; sono previste misure interdittive (sospensione di certificazioni, divieto temporaneo di esercitare funzioni dirigenziali).

Fonte: art. 38 testo vigente (link F5); FAQ ACN sezione "Profili generali"/"Ruoli e procedure". Approfondimento secondario: <https://www.studiolegalestefanelli.it/it/approfondimenti/nis2-sanzioni>

**Perché conta commercialmente:** la leva di vendita più forte verso una PMI non è la multa all'azienda, è **l'esposizione personale dell'amministratore**. Ma va detta con precisione giuridica, senza trasformarla in una minaccia generica.

## F10 — Il 31 ottobre 2026 non chiude il percorso [PRIMARIA]

Dal 31 ottobre 2026 (per la coorte 2025) **inizia la fase di verifica**: ACN passa dall'accompagnamento alla vigilanza. Art. 37 (vigilanza ed esecuzione), art. 36 (poteri di verifica e ispezione). Per i soggetti essenziali la vigilanza è ex ante (ispezioni, audit, richieste di evidenze anche in assenza di incidente); per gli importanti è prevalentemente ex post.

- Fonte: art. 38 e art. 37 (link F5); FAQ ACN sezione "Monitoraggio, vigilanza ed esecuzione": <https://www.acn.gov.it/portale/faq/nis/monitoraggio-vigilanza-esecuzione>
- Determinazione ACN n. 155238 del 20 aprile 2026, modello di categorizzazione (art. 30): <https://www.acn.gov.it/portale/nis/categorizzazione>

## F11 — Domanda di mercato e prezzi (fonti secondarie — NON normative)

Vedi `mercato-prezzi.md` per il dettaglio e i link. Sintesi: l'accertamento dello stato di fatto ("gap analysis") è venduto nel mercato italiano in una **forbice grossolana 3.000–6.000 EUR** per una PMI, e in Spagna (mercato NIS2 più maturo) 3.000–6.000 EUR per la sola analisi dei gap sull'art. 21, 12.000–20.000 EUR per l'implementazione. Operatori italiani offrono pacchetti "NIS2 compliance chiavi in mano" a **5.000–15.000 EUR**. Il costo *totale* di conformità per un'entità importante è stimato da fonti di settore in **30.000–500.000 EUR**. Queste sono fonti secondarie commerciali: servono a posizionare il prezzo, non a sostenere un'affermazione normativa.

---

## Metodo di verifica usato

1. Ogni fatto normativo è stato ricondotto alla pagina ACN competente o al testo dell'atto.
2. Dove una fonte secondaria affermava una data, è stata cercata la formulazione primaria corrispondente. **Due casi hanno prodotto una correzione**: la data del 31 ottobre (F2) e il massimo sanzionatorio di 10M/2% applicato genericamente (F5).
3. Nessuna data in questo file deriva da una fonte secondaria non incrociata.
4. Da ri-verificare prima di ogni uso: il testo vigente della Determina 379907/2025 e le FAQ ACN (ACN le aggiorna senza preavviso), e la validità dell'art. 38 (potenziali modifiche).

---

## F12 — Il canale di vendita più forte: l'obbligo dei soggetti NIS di ELENCARE i fornitori rilevanti [PRIMARIA]

**Il fatto.** La **Determinazione ACN n. 127437 del 13 aprile 2026** (che sostituisce la n. 379887/2025, in applicazione dal 15 aprile 2026) introduce, tra le informazioni dell'aggiornamento annuale, l'**elencazione dei "fornitori rilevanti NIS"** (art. 18 della Determinazione). Per ciascun fornitore rilevante il soggetto NIS deve comunicare ad ACN: denominazione sociale, codice fiscale, Paese della sede legale, **codici CPV** delle forniture e **criterio di rilevanza** utilizzato.

**Finestra temporale:** **15 aprile – 31 maggio di ogni anno**, sul Portale Servizi ACN (servizio "NIS/Aggiornamento annuale informazioni"). Le modifiche rilevanti intervenute nel parco fornitori vanno comunicate entro **14 giorni** dalla modifica ("Aggiornamento continuo informazioni").

**I due criteri di rilevanza** (alternativi, non cumulativi — art. 1, c. 1, lett. ll)):
1. la fornitura è riconducibile alle attività o ai servizi dell'**Allegato I, punti 8 e 9, del D.Lgs. 138/2024**: infrastrutture digitali (data center, IXP, DNS, CDN, cloud, servizi fiduciari, reti pubbliche di comunicazione elettronica) e **fornitori di servizi di gestione TIC** (MSP e MSSP);
2. **l'interruzione o la compromissione della fornitura comporta un impatto significativo** sulla capacità del soggetto NIS di erogare le attività o i servizi per cui è nel perimetro — anche per effetto dell'indisponibilità di fornitori alternativi.

**Perché ACN lo chiede.** Le informazioni raccolte alimentano l'attività di individuazione: soggetti che **non raggiungono da soli le soglie** possono essere individuati come soggetti importanti o essenziali ai sensi dell'**art. 3, comma 13, del D.Lgs. 138/2024** — "su proposta delle Autorità di settore" — con **notifica di individuazione al domicilio digitale**. La facoltà vale anche per **piccole e micro-imprese** che operano nei settori degli allegati I, II, III e IV (ACN, FAQ Ambito; ACN, "La normativa").

**Come si cita (cautela).** Non è corretto affermare che "se sei nell'elenco dei fornitori rilevanti diventi automaticamente soggetto NIS": l'inserimento **non produce automaticamente** quell'effetto. L'affermazione verificabile è che **la comunicazione ad ACN della posizione di fornitore critico rende l'esposizione a individuazione ex art. 3, c. 13, concreta e documentata** — e che il fornitore scopre il problema quando ha già subito la richiesta, non prima.

**Fonti (verificate 29 settembre 2026):**
- ACN — "La normativa": <https://www.acn.gov.it/portale/nis/la-normativa> *(individuazione ulteriori soggetti critici ex art. 3, c. 13)*
- ACN — FAQ Ambito: <https://www.acn.gov.it/portale/en/faq/nis/ambito> *(piccole e microimprese individuabili; notifica al domicilio digitale)*
- Gruppo IREN — informativa ai fornitori che cita la Det. ACN 127437/2026 e la finestra 15/04–31/05: <https://portaleacquisti.gruppoiren.it/documenti/Informativa_NIS2.pdf> *(documento di un soggetto obbligato, che dimostra l'obbligo in essere)*
- Studio Legale Calzoni — Det. 127437/2026, art. 18: <https://www.studiolegalecalzoni.com/fornitori-rilevanti-nis2-2026/>
- Gruppo 2G — testo FAQ fornitori rilevanti e roadmap Det. 127434/2026: <https://www.gruppo2g.com/nis2-nuove-determine-acn-adempimenti-nuovi-soggetti-e-accesso-alla-piattaforma/>

**Nota di stato della fonte — AGGIORNATA IL 6 OTTOBRE 2026: la lacuna è chiusa.** Il PDF ufficiale della Determinazione è stato reperito sul sito ACN e letto riga per riga. Link diretto (HTTP 200, `application/pdf`, 573.995 byte):

<https://www.acn.gov.it/portale/documents/d/guest/detacn_piattaformanis_251218-v9_signed>

Copia archiviata nel repo (così che il fatto non dipenda dalla permanenza del link): `fonti/det-ACN-127437-2026.pdf`, SHA-256 `4a12bb3d728ea559ad1627dc5dcd61fc91b23b75f66d674281a8bd9aae8d5e1a`.

I passaggi qui sopra sono ora **citazioni verbatim del testo primario**, non ricostruzioni:

- **art. 16, c. 1:** «Dal **15 aprile al 31 maggio** di ogni anno, gli utenti aggiornano, tramite il "Servizio NIS/Aggiornamento annuale informazioni", le informazioni per conto del soggetto per cui operano, assicurandone la correttezza.» — l'art. 16, c. 3, lett. g) elenca tra le voci da verificare «l'elenco dei fornitori rilevanti NIS, ai fini dell'articolo 3, comma 9, lettera f), del decreto NIS».
- **art. 1, c. 1, lett. ll)** — definizione di «fornitori rilevanti NIS»: fornitore che soddisfa **almeno uno** dei due criteri; criterio 1) fornitura riconducibile alle attività/servizi di **Allegato I, punti 8 e 9** (fornitura ICT); criterio 2) «l'interruzione o la compromissione della fornitura comporta un impatto significativo sulla capacità del soggetto NIS, anche per effetto della **indisponibilità di fornitori alternativi**, di erogare le attività o i servizi per i quali rientra nell'ambito di applicazione del decreto NIS (**fornitura non fungibile**)».
- **art. 18** («Elencazione dei fornitori rilevanti NIS»): il soggetto NIS indica **denominazione, codice fiscale, Paese della sede legale, codici CPV** (Reg. CE 2195/2002) e **il criterio di rilevanza utilizzato**.
- **art. 33, c. 3:** la Determinazione «si applica a decorrere dal **15 aprile 2026**, fatte salve le disposizioni di cui al capo V la cui applicazione è differita al **1° maggio 2026**»; **art. 32** aggiorna e sostituisce la Det. n. 379887/2025.

Il testo si chiude con la firma «IL DIRETTORE GENERALE — **Bruno Frattasi**».

**Nota di cautela sul secondo PDF.** Il link al documento 127434/2026 indicato dalla fonte secondaria (`.../2026_112335_detacn_comptavolo_signed`) risponde 200 ma **non contiene la roadmap dei nuovi soggetti 2026**: è un atto di aggiornamento della **composizione del Tavolo NIS** (art. 1 sostituisce il Gen. D. Virgilio Romponi con il Gen. B. Luigi Vinciguerra; art. 2 ridetermina i componenti). Copia archiviata come `fonti/det-ACN-tavolo-composizione.pdf` (SHA-256 `9c5280697c8a30ec10568196cb36aad42db5532612efe9cd732078e1f791c597`). **Conseguenza: i contenuti di F13 restano su fonte secondaria concordante** (Gruppo 2G + ACN FAQ MSB.3, F2) e vanno citati come tali — il riferimento 127434/2026 va mantenuto come "l'atto che fissa i termini per i nuovi soggetti", non come "il PDF qui linkato".

---

## F13 — Termini per i nuovi soggetti 2026 [PRIMARIA, via fonte secondaria concordante]

**Determinazione ACN n. 127434/2026 (13 aprile 2026, applicabile dal 30 aprile 2026)** — roadmap per i soggetti inseriti nell'elenco NIS **per la prima volta nel 2026**:
- designazione del **referente CSIRT**: entro **31 dicembre 2026**;
- **obbligo di notifica degli incidenti significativi**: dal **1° gennaio 2027**;
- **adozione delle misure di sicurezza di base** (allegati 1 e 2 della Det. ACN 379907/2025): entro **31 luglio 2027**.

Conferma F2: il termine dipende dalla coorte di inserimento, non è una data unica.

**Fonte:** Gruppo 2G, <https://www.gruppo2g.com/nis2-nuove-determine-acn-adempimenti-nuovi-soggetti-e-accesso-alla-piattaforma/> — concordante con ACN FAQ MSB.3 (F2) su "31 luglio 2027".

---

## F14 — Dimensione dell'elenco NIS: oltre 21.000 soggetti [PRIMARIA]

L'**ottava riunione del Tavolo NIS** (9 aprile 2026) ha reso noto che l'elenco provvisorio dei soggetti NIS 2026 ha consistenza simile a quello 2025: **oltre 21.000 soggetti, di cui almeno 5.000 essenziali**. Nella stessa sede è stata introdotta la finestra 15 aprile – 31 maggio per l'elencazione dei fornitori rilevanti e le licenze ENISA e-learning per le P.A. dell'allegato III.

**Fonte primaria:** ACN — "ACN convoca il Tavolo per l'attuazione della disciplina NIS": <https://www.acn.gov.it/portale/w/acn-convoca-il-tavolo-per-l-attuazione-della-disciplina-nis>

**Uso commerciale:** è il numero che dimensiona il mercato **senza contattare nessuno**. 21.000 soggetti obbligati producono, ciascuno, un elenco di fornitori rilevanti — quella è la popolazione raggiungibile per via indiretta.

---

## F15 — Le FAQ ACN sui fornitori rilevanti (FRN.1–FRN.9): il fatto verificabile da mettere nell'email [PRIMARIA]

**Aggiornamento del 13 ottobre 2026.** L'ACN ha pubblicato una sezione FAQ dedicata ai fornitori rilevanti, che dà corpo operativo all'art. 18 della Det. 127437/2026. È il pezzo che mancava per rendere **concreto e citabile** il fatto che l'email Versione B usa come leva.

**Fonte primaria:** ACN — "Domande frequenti NIS — Aggiornamento delle informazioni", sezione *Fornitori rilevanti* (FRN.1–FRN.9): <https://www.acn.gov.it/portale/faq/nis/aggiornamento-delle-informazioni> (verificata 13 ottobre 2026).

I passaggi verbatim che contano commercialmente:

- **FRN.4 — il fatto più utile.** ACN fornisce una **tabella di corrispondenza tra tipologia di fornitura e codice CPV**. Tra i codici esplicitamente elencati per la categoria «Servizi gestiti e servizi gestiti di sicurezza»: *Servizi informatici* [**72500000-0**], *Servizi di gestione connessi all'informatica* [**72510000-3**], *Servizi di manutenzione e assistenza sistemi* [**72250000-2**], *Servizi di consulenza e assistenza informatica* [**72600000-6**], *Servizi di audit e collaudo informatico* [**72800000-8**]. Per «Infrastrutture digitali»: *Servizi di elaborazione dati* [72300000-8], *Servizi di Internet* [72400000-4], *Servizi di data center* [72000000-5], *Servizi di telecomunicazione* [64200000-8].
- **FRN.3 — cosa il cliente deve dichiarare su di te.** Cinque campi per fornitore: denominazione, codice fiscale, Paese della sede legale, **codici CPV**, **criterio di rilevanza** utilizzato. Cioè: il tuo cliente scrive nero su bianco *quanto è dipendente da te* e *perché*.
- **FRN.2 — i criteri, e le tre casistiche.** I criteri possono valere «in alternativa tra loro o congiuntamente»: la fornitura può essere *ICT*, *non fungibile*, o *ICT non fungibile*. Un fornitore ICT non ridondato è, per definizione, nella terza casistica.
- **FRN.4, test operativo (fornitura non fungibile).** La dipendenza non è solo digitale: ACN cita esplicitamente la **corrente elettrica** (CPV 65310000-9, 65300000-6) come esempio di fornitura non fungibile. Il test implicito: *«se il fornitore si ferma domani, quanto ci mettiamo a sostituirlo senza impatto?»*.
- **FRN.6–FRN.9 — le risposte che alzano la posta.** Il fornitore **extra-UE** va elencato («la maggior parte di questi fornitori, anche se extra-UE, è soggetta alla Direttiva NIS»); i **fornitori infragruppo non sono automaticamente esclusi** (una capogruppo che gestisce il data center delle controllate è elencabile); per una filiera A→B va segnalato **il fornitore che eroga davvero** la fornitura, non il mero broker.
- **FRN.9 / accordi di condivisione.** Sono oggetto di notifica all'ACN i contratti di fornitura di servizi di sicurezza — **NOC, MDR, SOC, CSOC, CERT, VA/PT, Red Teaming, Cyber Threat Intel**. Questi fornitori sono, per doppia via, dentro il perimetro informativo di ACN.

**Conseguenza commerciale (perché aggiorna l'email).** La Versione B non deve più limitarsi a dire «il tuo cliente deve elencarti». Ora può dire **con quali codici, e cosa deve scrivere di te**: è un fatto puntuale, verificabile sul sito ACN, che il destinatario può controllare in tre minuti — e che, controllato, gli mostra che chi scrive ha letto la fonte, non il riassunto. È la differenza tra un'email di consulenza e un'email di vendita.

**Nota di cautela.** Le FAQ FRN sono una fonte primaria *interpretativa*: ACN le aggiorna senza preavviso (la numerazione FRN.5–FRN.9 è recente). Le citazioni vanno datate; i codici CPV vanno riletti sulla pagina prima di ogni uso in un documento consegnabile.

## F16 — Le misure dell'Allegato 1 sono 37, i requisiti 87: conteggio sul testo primario [PRIMARIA]

**Aggiornamento del 20 ottobre 2026.** La cifra «37 misure / 87 requisiti» per i soggetti importanti girava finora su **fonte secondaria** (rassegne specializzate). È ora **verificata per conteggio diretto** sul testo ufficiale dell'Allegato 1.

**Fonte primaria:** ACN — *Allegato 1 — Misure di sicurezza di base per i soggetti importanti*, documento allegato alla Determinazione ACN 379907/2025: <https://www.acn.gov.it/portale/documents/d/guest/allegato-1-v2> (letto 20 ottobre 2026).

Metodo: il documento è organizzato in funzione → categoria (es. `GV.OC`, `GV.RM`, `PR.AA`) → sottocategoria con codice requisito (`GV.OC-04`, `GV.RM-03`, …) → punti numerati. Contando i **codici requisito distinti** nelle intestazioni delle sottocategorie si ottengono **37**; contando i **punti numerati** nel corpo di ciascun requisito si ottengono **87**. Entrambi i valori confermano la cifra che circolava, che da ora può essere citata come primaria.

Struttura del documento: 6 funzioni (`GOVERN`, `IDENTIFY`, `PROTECT`, `DETECT`, `RESPOND`, `RECOVER`), più un'**Appendice** con la *Tabella 1* (requisiti di cui al punto 2 della misura `GV.PO-01`, cioè i requisiti minimi obbligatori di politica per 16 ambiti) e la *Tabella 2* (requisiti di cui al punto 2 della misura `ID.RA-06`).

**Conseguenza commerciale.** Il referto di check-up può citare «37 misure, 87 requisiti» con la sicurezza di una fonte primaria, e può citare anche la struttura a 16 ambiti della Tabella 1 — che è la griglia con cui si presenta il gap per ambito in una pagina sola.

## F17 — I fornitori di software sanitario sono già qualificati ACN: perché non sono buoni bersagli [PRIMARIA]

**Aggiornamento del 20 ottobre 2026.** Verifica dei primi bersagli contro il **Portale Cloud ACN** (catalogo ufficiale delle infrastrutture digitali e dei servizi cloud qualificati). Il risultato ribalta l'ipotesi della lista precedente.

**Fonte primaria:** Portale Cloud ACN, scheda **SA-3784 — "WEBQUALITY", fornitore *Mys srl***: <https://www.acn.gov.it/portale/w/sa-3784> (letta 20 ottobre 2026). La scheda attesta: **Livello di qualificazione 2 (QC2)**, validità **30/07/2025 – 30/07/2028**, con certificazioni obbligatorie già possedute: **ISO 9001:2015, ISO 22301 (continuità), ISO/IEC 20000 (service management), CSA STAR Level 2, ISO 27001**.

**Fonte primaria:** sito EL.CO. — la piattaforma *Fenix* è dichiarata «ACN — servizi SaaS qualificati di Livello 2 (QC2)» oltre che Dispositivo Medico CE classe IIA (MDR) e conforme GDPR: <https://www.elco.it/> (letto 20 ottobre 2026).

**Il punto.** Per ottenere una qualificazione QC2 sul Portale Cloud ACN, un fornitore è già passato per un processo che richiede ISO 27001 e la conformità a misure di sicurezza documentate. Cioè: **possiede già gran parte dell'apparato che il Check-up NIS2 andrebbe a verificare**. Mandargli «non sapete se siete NIS2 / quali misure vi mancano» è un errore di credibilità immediato: chi legge sa che non è vero, e risponde solo se vuole.

Questo **non** squalifica EL.CO. e MYS come *soggetti NIS* — un fornitore di software sanitario può ben essere a sua volta soggetto NIS (servizi gestiti TIC). Ma li squalifica come **destinatari dell'offerta di diagnosi**: hanno già il Mago che dice loro cosa manca, e non è lui.

**Conseguenza operativa.** Il criterio di conferma della lista bersagli va ristretto. Non basta «il fornitore serve un soggetto NIS riconoscibile»: serve che il fornitore **non abbia già una qualificazione ACN o una certificazione equivalente recente**. Un MSP che serve un ospedale ma non è sul Portale Cloud ACN, e non espone ISO 27001, è il bersaglio giusto; un fornitore QC2 con ISO 27001 no.

---

## F18 — La clausola NIS2 che i fornitori firmano davvero: un allegato contrattuale pubblico [PRIMARIA]

**Aggiornamento del 27 ottobre 2026.** Il repo finora sosteneva la leva commerciale con la norma (art. 24 D.Lgs. 138/2024: i soggetti NIS devono inserire requisiti di sicurezza nei contratti con i fornitori). Ora esiste un documento primario che mostra **cosa quel requisito contiene, cifre alla mano**: un allegato contrattuale pubblicato da una **Azienda Sanitaria Locale** e allegato a un bando/contratto di fornitura.

**Fonte primaria:** A.S.L. V.C.O. (Azienda Sanitaria Locale del Verbano-Cusio-Ossola) — *Allegato 01 — Obblighi di cybersecurity, supply chain e notifica degli incidenti* (Allegato C, "Clausole di gestione della compliance NIS2"), documento allegato al Bando/Contratto di fornitura, rev. 01: <https://www.aslvco.it/wp-content/uploads/2026/08/All.-C-Clausole-di-gestione-della-compliance-NIS2-2.pdf> (letto e scaricato il 27 ottobre 2026; il PDF è pubblico, 5 pagine).

**Contenuto verificato — gli obblighi che ricadono sul Fornitore.** Il documento è un allegato contrattuale che diventa "parte integrante e sostanziale del Contratto di Fornitura", con il mancato rispetto equiparato a inadempimento contrattuale (art. 1453 c.c.). Impone al fornitore:

| Obbligo | Termine o soglia | Riferimento interno al documento |
|---|---|---|
| **Notifica di Incidente ICT che impatta il Committente** | **entro 24 ore** dall'accertamento | §3.1 |
| Rapporto intermedio | **entro 72 ore** | §3.2 |
| Rapporto finale | **entro 1 mese** dall'evento | §3.2 |
| **Patch critiche / zero-day** | **entro 7 giorni lavorativi** | §4.2 |
| Patch alte | entro 15 giorni lavorativi | §4.2 |
| Patch medie/basse | entro 60 giorni lavorativi | §4.2 |
| **Piano di remediation** dopo un audit | entro 10 giorni lavorativi; azioni chiuse **entro 30 giorni** | §2.2 |
| Conservazione **log di sicurezza** accessibili al Committente | almeno **12 mesi** | §OBBLIGHI lett. d |
| **Informazione scritta** su modifiche sostanziali della catena di subfornitura | almeno **30 giorni prima** | §1.2 |
| **Audit del Committente** sui sistemi del Fornitore | preavviso 5 giorni lavorativi, salvo emergenze; **audit annuali programmati obbligatori** | §2.1, §2.3 |
| **SBOM** (Software Bill of Materials) aggiornato, per le forniture software | continuativo | §4.3 |
| **SDLC sicuro** (threat modelling, code review, SAST/DAST) | per software sviluppato o personalizzato | §5.1 |
| **Formazione** del personale assegnato | almeno **annuale** | §6.1 |
| SGSI conforme **ISO/IEC 27001:2022**, controlli A.5.19–A.5.23 | "ove applicabile" | §OBBLIGHI lett. a |

Il Fornitore è inoltre **responsabile diretto** dei propri subfornitori e deve inserire nei contratti a valle clausole "almeno equivalenti" (§1.1, §1.3). **Prefiltro obbligatorio:** compilare e sottoscrivere una *Checklist di Conformità ICT & Cybersecurity* (Allegato D), le cui dichiarazioni valgono come **dichiarazione sostitutiva di certificazione** (D.P.R. 445/2000) e sono parte integrante dell'offerta.

**Perché questo fatto vale più di tutti gli altri per la vendita.** È la differenza tra «la norma prevede la sicurezza della catena di fornitura» (affermazione vera ma astratta, che il fornitore può rimandare) e **«ecco il modulo che dovrai firmare per continuare a fornire a questa ASL, con 13 adempimenti numerati e sette termini in giorni»**. Il fornitore non deve decidere se la NIS2 lo riguarda: la clausola è già nel contratto, e il primo termine (patch critiche a 7 giorni) è verificabile solo da chi ha un processo scritto — cioè da chi ha fatto, o ha fatto fare, la valutazione che il Check-up produce.

**Cautela sull'uso.** Il documento è un atto di **una** stazione appaltante, non un modello nazionale obbligatorio: ACN non impone quel testo. Va citato come **esempio reale e pubblico di clausola in uso, non come testo di legge**. La formulazione da usare nell'email è: «questa ASL ha già allegato ai suoi contratti le clausole NIS2; ecco cosa contengono», non «tutti i vostri clienti vi chiederanno questo».

**Conseguenza operativa sul prodotto.** La Checklist di Conformità ICT & Cybersecurity allegata a quel contratto è, in sostanza, **il questionario che il cliente del fornitore somministrerà**. Il referto del Check-up NIS2 diventa quindi direttamente riusabile come risposta documentata a quella checklist — e questo è un argomento di vendita verificabile, non una promessa: le voci della checklist attengono alle stesse aree delle misure di base (analisi dei rischi, controllo accessi, patch, continuità, incidenti, formazione, subfornitori).

**Contesto di mercato rilevante (fonte secondaria, da non citare al cliente come normativa).** Lo stesso schema di richiesta al fornitore è descritto come prassi corrente per le PMI che forniscono la sanità: questionari, clausole contrattuali e richieste di evidenze (LORAN, 7 ottobre 2026, <https://www.loransrl.eu/nis2-pmi-fornitori-sanita/>). Segnale di saturazione da registrare: LORAN è **ISO/IEC 27001, presente nel registro CSA STAR e nel Marketplace cloud ACN**, e vende lo stesso tipo di percorso (analisi dei rischi, accessi, backup, formazione). Cioè: anche il segmento "fornitore PMI della sanità" ha già operatori attrezzati e qualificati.

---

## F19 — Il listino degli obblighi NIS2 che i fornitori ICT pubblici hanno già firmato: due determine, 29 aziende, P.IVA e CIG reali [PRIMARIA]

**Perché è un fatto nuovo e diverso da F18.** F18 documenta *una* clausola NIS2 (ASL V.C.O.). F19 documenta **la stessa famiglia di obblighi diffusa**, con l'elenco nominativo dei fornitori che li hanno già accettati e i loro identificativi fiscali: non serve più *ipotizzare* quali PMI serviranno un soggetto NIS — si legge il provvedimento di affidamento.

### F19.a — ASL Biella: un affidamento diretto unico per 16 fornitori di software sanitario

**Fonte primaria:** A.S.L. di Biella, *Determinazione n. 642 in data 19/06/2026* — oggetto: «Affidamenti dei servizi di assistenza e manutenzione software applicativi in uso presso le strutture aziendali di ASL Biella – anni 2026/2027 – Fornitori vari – CIG vari – importo totale € 829.595,61 IVA inclusa». PDF pubblico, 14 pagine, letto integralmente il 3 novembre 2026.
URL: <https://trasparenza.aslbi.piemonte.it/media/8520/download> (lo stesso atto è anche su <https://aslbi.piemonte.it/wp-content/uploads/2026/06/Determinazione_n_642_del_9062026.pdf>).

**Procedura.** Manifestazione di interesse su piattaforma Sintel (ID **209745897**), apertura della documentazione il **02.12.2025**; per ciascun software è pervenuta **una sola** manifestazione, quindi accertata la condizione di **esclusività** ai sensi dell'art. 76, co. 2, lett. b), punto 3 del D.Lgs. 36/2023 (tutela dei diritti d'autore sul software) e proceduto ad **affidamento diretto**. I fornitori REKORDATA s.r.l. e ZUCCHETTI AXESS S.P.A. sono stati ricontattati dopo una prima scadenza; nuova scadenza **18.01.2026**.

**Tabella dei fornitori e dei trattamenti (trascritta dall'atto: ragione sociale, P.IVA, software, importo soggetto a ribasso).** Questi dati identificano un'impresa reale e verificabile, non un profilo ipotetico:

| Fornitore (ragione sociale + P.IVA) | Software / applicativo | Imponibile € | CIG |
|---|---|---|---|
| AXIOS INFORMATICA S.R.L. — 03166670244 | Cucina/Prandium – Mensaweb | 12.200 | 5981193 |
| BIM ITALIA S.R.L. (diventa **GPI S.P.A.** — 01944260221 dal 01.01.2026) | Quany/SdO | 57.120 | 5981194 |
| CITTA' STUDI S.P.A. — 01491490023 | Gestione applicativi Corso di Laurea in Scienze Infermieristiche | 51.000 | 5981195 |
| DEDALUS ITALIA S.P.A. — 05994810488 | Punti Azzurri Multifunzione (PAM) | 40.800 | 5981196 |
| GIADA PROGETTI S.R.L. — 02248420263 | Applicativo Concorsi | 20.400 | 5981197 |
| **GPI S.P.A. — 01944260221** | DWH — database CdG | 102.000 | 5981198 |
| LIZARD S.R.L. — 01867040220 | Apparati di teledidattica (Corso di Laurea) | 12.000 | 5981154 |
| ME.S.I.S. S.R.L. — 01252940430 | TMM / Servizio Trasfusionale | 16.320 | 5981199 |
| METEDA S.R.L. — 01713290441 | MetaClinic | 32.640; ribasso fino a 45.969,60 IVA incl. | 5981447 |
| METROPOLIS S.R.L. — 10368880158 | Punti Gialli | 51.000 | 5981200 |
| REKORDATA S.R.L. — 05185750014 | FileMaker | 12.240 | 5981201 |
| SHORR KAN S.R.L. — 07831320010 | Canopo — Medicina del lavoro | 22.440 | 5981202 |
| SINED S.R.L. — 01757941206 | Medware Nefrologia e dialisi | 70.000 | 5981788 |
| SYSTEM TECHNOLOGY S.R.L. — 02387320985 | Applicativo MMG e PLS | 95.000 | 5981203 |
| TINEXTA INFOCERT S.P.A. — 07945211006 | Firma remota/automatica ProxiSign | 52.000 | 5981204 |
| ZUCCHETTI AXESS S.P.A. — 03537610960 | Timbratrici | 40.800 | 5981205 |

*(I CIG riportati sono quelli letti nell'atto per le singole trattative; le righe dove il PDF spezzava il campo vanno ricontrollate sul documento originale prima di citarle a un cliente.)*

**Il fatto che conta per la vendita.** In un **unico** provvedimento, una ASL soggetto NIS ha messo in capo a **16 fornitori** — di cui almeno **8 sono PMI italiane a conduzione tecnica, alcune con 2 o 10 dipendenti** (dati di registro, sotto) — l'obbligo di garantire l'assistenza su software sanitario critico per due anni. Nessuno di questi fornitori può esibire un processo perché nessun documento pubblico lo attesta.

### F19.b — ASL V.C.O.: la terza procedura, il RIS-PACS

Un secondo ente sanitario piemontese, ASL V.C.O., ha indetto nell'agosto 2026 **tre** procedure negoziate senza bando per l'assistenza applicativa e sistemica sui software aziendali (ID Sintel **221622294 / 221622589 / 221623573**), durata 36 mesi, aggiudicazione al **minor prezzo**, inviti a **Alfahealth S.p.A., Dedalus Italia S.p.A. e GPI S.p.A.** (CIG **BCAE3CE6D5** per GPI; base d'asta lotto GPI **1.668.464,00 EUR**). Lo schema di contratto (All. B, Det. n. 1042 del 07.08.2026) include, tra le attività a carico dell'appaltatore, la **«Gestione dei servizi di compliance NIS2»**.

**Elemento ulteriore da verificare (non ancora confermato sul testo primario):** la **Det. n. 1006 del 03.08.2026** riguarderebbe i servizi per il sistema **RIS-PACS**, con importo presunto **2.368.800,00 EUR** e fornitore uscente di area **NEC/Synapse**. Se confermato, è un quarto contratto della stessa famiglia e un fornitore diverso (NEC) da mettere nella mappa. **Stato: da leggere sul PDF, non citare finché non verificato.**

### F19.c — La conseguenza scomoda: il criterio «PMI 50–250» è FALSO per questo mercato

I dati di registro (Camera di Commercio, via banche dati pubbliche, letti il 3 novembre 2026) sulle imprese nominate nell'atto di cui sopra **falsificano** la regola scritta nel criterio a 4 punti di `contatti/lista-bersagli.md` («È PMI. Tra 50 e 250 dipendenti»):

| Impresa | P.IVA | Dipendenti | Fatturato | Fonte |
|---|---|---|---|---|
| SYSTEM TECHNOLOGY S.R.L. (Botticino, BS) | 02387320985 | **2** | € 707.720 (2024) | <https://www.aziende.it/system-technology-srl-BS>, <https://www.visurissima.it/aziende/SYSTEM-TECHNOLOGY-SRL_02387320985.html> |
| SHORR KAN S.R.L. (Torino) | 07831320010 | **11–50** (22 su LinkedIn) | ~€ 1 M (ultimo bilancio pubblico) | <https://italy.globaldatabase.com/company/shorr-kan-s-r-l>, <https://linkedin.com/company/shorr-kan> |
| METROPOLIS S.R.L. (Assago, MI) | 10368880158 | **10–15** | € 2,76 M (2025) | <https://www.ufficiocamerale.it/3703/metropolis-srl>, <https://www.fatturatoazienda.it/azienda/metropolis-srl-10368880158> |
| METEDA S.R.L. (Roma/S. Benedetto del Tronto) — «un'impresa IQVIA» | 01713290441 | **>50 dichiarati sul sito** | n.d. | <https://meteda.it/en/chisiamo> |

Le imprese che forniscono la sanità pubblica italiana — e che quindi stanno dentro la catena di fornitura di un soggetto NIS — sono in larghissima parte **micro e piccole imprese (2–20 dipendenti)**, non PMI da 50–250. Una software house da 2 dipendenti che manutiene l'applicativo MMG/PLS di una ASL **ha lo stesso obbligo contrattuale** di una da 200, e nessuna capacità interna di assolverlo. Il criterio 3 va quindi **sostituito**: la dimensione giusta non è «PMI 50–250», è **«il fornitore è troppo piccolo per avere compliance interna, ma abbastanza grande da avere un contratto in essere con un soggetto NIS che vale più del costo del check-up»**. Nota: METEDA è controllata da **IQVIA** — un gruppo multinazionale sanitario: il check-up diagnostico non è il suo prodotto, e va esclusa dall'invio (criterio 2/3).

**Cautela sull'uso.** Le determinazioni citate sono atti di **due** stazioni appaltanti piemontesi, non un modello nazionale. Le citazioni di registro sono banche dati commerciali: la P.IVA è affidabile, il conteggio dipendenti è quello dichiarato e va riverificato sul sito del fornitore prima dell'invio. **Nessuna** delle imprese nominate è un cliente: è un elenco di destinatari *possibili*, ricavato da un atto che le riguarda.

### F19.d — Rettifica metodologica: due candidati scartati per *verifica*, e la trappola dell'omonimia

Il metodo della scheda di verifica ha prodotto, il 3 novembre 2026, due **esclusioni** che valgono più di due inclusioni:

- **SHORR KAN S.R.L. (P.IVA 07831320010) — ESCLUSO.** Il sito aziendale espone le certificazioni **ISO/IEC 27001:2022, ISO 27017:2015, ISO 27018:2019 e ISO 9001:2015** come PDF scaricabili (rev. 2024), più una *Information Security Policy* pubblica: <https://www.shorr-kan.com/>. Ha già la griglia che il Check-up venderebbe. Criterio 4 soddisfatto → fuori.
- **SYSTEM TECHNOLOGY S.R.L. (P.IVA 02387320985) — Omonimia, dato inaffidabile.** La ricerca di registro associa quella P.IVA a una società di **Botticino (BS), Via Giosuè Carducci 12/C**, che sul proprio sito (<https://systemt.it/>) si presenta come **distributore italiano del CAD/CAM Go2CAM per la meccanica** («fresatura, tornitura, erosione»), nata nel 1997 come CN Service; contatto unico `info@systemt.it`. Nulla in comune con l'«Applicativo MMG e PLS» affidato da ASL Biella: **sono due imprese distinte con ragione sociale quasi identica** (una Srl in provincia di Brescia e una in Piemonte/Lombardia). *La P.IVA va letta sull'atto, non dedotta dalla ragione sociale.* Questo è il primo errore di attribuzione che la scheda ha intercettato: una ragione sociale comune non identifica un'impresa.

**Rettifica di F19.c.** La riga «SYSTEM TECHNOLOGY S.R.L. — 2 dipendenti, € 707.720» va **depennata come candidato**: descrive l'impresa sbagliata. Il criterio sostituito (micro-impresa < 20 addetti, contratto NIS provato dall'atto) **resta valido** — è confermato da METROPOLIS (10–15 dipendenti) e, in direzione opposta, falsificato da SHORR KAN (11–50 dipendenti *con* ISO 27001): la dimensione da sola non basta, la variabile discriminante è **avere o non avere un sistema di gestione della sicurezza certificato**.

**Correzione di sede.** **AXIOS INFORMATICA S.R.L.** (P.IVA 03166670244, già confermata) ha sede a **Vicenza** — «n° Registro Imprese di Vicenza» sul sito <https://www.axios.it/>, prodotti *Prandium*/*Prandium Portale* per la ristorazione collettiva. Coerente col software di mensa affidato da ASL Biella: **identificazione confermata**, sito aziendale attivo e specializzato.
