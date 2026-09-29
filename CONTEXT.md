# Contesto — nis2-service

Glossario dei termini usati in questo repo. Solo linguaggio: nessun dettaglio implementativo, nessun prezzo, nessuna procedura operativa.

## Soggetto NIS
Organizzazione pubblica o privata che rientra nell'ambito del D.Lgs. 138/2024 (settore + dimensione). Non è un titolo che si riceve: si è "soggetto NIS" per effetto della legge, e la registrazione annuale su piattaforma ACN è la dichiarazione che lo rende noto all'Autorità.

## Soggetto essenziale (EE)
Soggetto NIS classificato come essenziale in base a settore e dimensione. Determina un regime di vigilanza ex ante e il tetto sanzionatorio più alto. Distinto da:

## Soggetto importante (IE)
Soggetto NIS classificato come importante. Regime di vigilanza ex post, tetto sanzionatorio inferiore a quello degli essenziali. La maggior parte delle imprese medie italiane fuori dai settori ad alta criticità ricade qui, non tra gli essenziali.

Termini volutamente NON usati in questo repo: "scadenza NIS2 del 31 ottobre 2026" come data unica (esiste un termine differenziato per coorte: usare "termine di 18 mesi dalla comunicazione di inserimento"), "certificazione NIS2" (la NIS2 non è uno schema di certificazione), "sanatoria" (non esiste nella norma).

## Fornitore rilevante
Fornitore di prodotti o servizi a un soggetto NIS che soddisfa almeno uno dei criteri di rilevanza della Determinazione ACN 127437/2026 (fornitura ICT riconducibile all'Allegato I punti 8 e 9, oppure non fungibilità della fornitura). È una **qualifica comunicata dall'ACN**, non un titolo che il fornitore possiede: il soggetto NIS lo elenca annualmente, e da quell'elenco l'ACN può individuare ulteriori soggetti obbligati. Distinto da:

## Elencazione dei fornitori rilevanti
L'adempimento con cui il soggetto NIS comunica all'ACN i propri fornitori rilevanti, nella finestra annuale 15 aprile – 31 maggio. È il meccanismo per cui il fornitore scopre di essere rilevante *dal cliente*, non da sé stesso. Da non confondere con l'individuazione del fornitore come soggetto NIS, che è un atto distinto e non automatico.

## Individuazione (art. 3, c. 13)
Atto con cui l'ACN, su proposta dell'Autorità di settore, include nell'ambito NIS un'organizzazione che non raggiunge da sola le soglie — anche una piccola o micro-impresa. Si manifesta come notifica al domicilio digitale. Termine da usare al posto di "diventa soggetto NIS per effetto dell'elenco", che è un'affermazione non vera.

## Check-up NIS2
Il prodotto di questo repo: una valutazione a prezzo fisso e a scope chiuso che risponde alla domanda "siamo soggetti NIS, e cosa ci manca?". È un prodotto di *diagnosi*, non di remediation.

## Prospettiva di costo
La forchetta di spesa delle fasi successive al check-up, consegnata in `dopo-il-checkup.md` insieme al referto. Non è un preventivo e non è parte del Check-up NIS2: è l'antidoto alla *perdita di trattativa*, cioè al rifiuto di comprare la diagnosi per timore di ciò che la segue.

## Referto di check-up
L'output del Check-up NIS2: un documento consegnabile con esito di applicabilità e, se applicabile, posizione misure per misura rispetto all'Allegato 1 o 2 della Determinazione ACN 379907/2025. Distinguere sempre due asserzioni separate: applicabilità dell'obbligo (questione giuridica) e adeguatezza tecnica (questione tecnica).

Deliverable **non** compreso nel Check-up NIS2 — da non confondere:
- **Piano di adeguamento**: roadmap con costi e tempi per chiudere i gap.
- **Attestazione di conformità**: dichiarazione all'ACN che le misure sono effettivamente implementate. È un atto del soggetto NIS: richiede prima la chiusura dei gap tecnici, quindi non è un esito possibile di una diagnosi.

## Misure di base
Le misure di sicurezza del primo periodo di applicazione (art. 42 decreto NIS), elencate nell'Allegato 1 (importanti) e nell'Allegato 2 (essenziali) della Determinazione ACN 379907/2025.

## Incidente significativo di base
Le fattispecie di incidente notificabili allo CSIRT Italia, definite negli Allegati 3 e 4 della medesima Determina. La notifica è composta da fasi con termini propri (pre-notifica a 24 ore, notifica completa a 72 ore).

## Punto di contatto
Persona designata dal rappresentante legale che opera la registrazione e intrattiene i rapporti con l'ACN. È un ruolo giuridico, non un ruolo tecnico: può coincidere con il tecnico, ma non è definito dalle competenze tecniche.
