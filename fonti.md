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
