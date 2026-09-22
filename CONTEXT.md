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
Soggetto che fornisce prodotti o servizi a un soggetto NIS e che rischia di essere attratto nell'ambito NIS2 come fornitore critico, anche senza superare le soglie dimensionali. È il canale di ingresso più frequente per le PMI piccole.

## Check-up NIS2
Il prodotto di questo repo: una valutazione a prezzo fisso e a scope chiuso che risponde alla domanda "siamo soggetti NIS, e cosa ci manca?". È un prodotto di *diagnosi*, non di remediation.

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
