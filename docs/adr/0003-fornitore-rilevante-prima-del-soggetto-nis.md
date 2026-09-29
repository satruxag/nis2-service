# 0003 — Il destinatario primario del primo contatto è il fornitore di soggetto NIS, non il soggetto NIS

**Data:** 29 settembre 2026
**Stato:** Accettata

## Contesto

Il materiale di vendita era costruito attorno a due destinatari: la PMI che sospettiamo essere soggetto NIS (Versione A dell'email) e il fornitore di un soggetto NIS (Versione B). La nota d'uso le presentava come alternative, con la Versione B indicata come "il canale più concreto" senza una ragione verificata.

La verifica del 29 settembre 2026 (`fonti.md`, F12) ha portato un fatto nuovo: la **Determinazione ACN n. 127437/2026** impone ai soggetti NIS di comunicare ad ACN, nella finestra **15 aprile – 31 maggio** di ogni anno, l'elenco dei propri **fornitori rilevanti** — con denominazione sociale, codice fiscale, Paese, codici CPV e criterio di rilevanza. La soglia è larga (forniture ICT/Allegato I punti 8-9, oppure non fungibilità della fornitura).

L'elenco alimenta l'individuazione da parte di ACN di ulteriori soggetti importanti o essenziali, anche **piccole e micro-imprese**, ai sensi dell'art. 3, comma 13, del D.Lgs. 138/2024.

## Decisione

L'ordine di priorità nell'invio è **invertito**: il fornitore di soggetto NIS viene contattato **per primo**, il soggetto NIS direttamente obbligato per secondo.

La Versione B dell'email viene modificata per includere la finestra 15 aprile – 31 maggio e l'effetto di individuazione.

## Perché

Il fornitore e il soggetto obbligato non hanno lo stesso rapporto con il tempo:

- Il **soggetto obbligato** ha già ricevuto la PEC di inserimento, conosce la propria scadenza e ha già avuto modo di cercare un consulente. La sua urgenza è già stata monetizzata da qualcun altro.
- Il **fornitore** scopre il rischio per via indiretta — da un cliente che lo inserisce in un elenco, o da una richiesta di garanzie al rinnovo — tipicamente **dopo** che il problema si è materializzato. È costretto **dal cliente**, non dalla legge, e la richiesta del cliente ha una data, mentre la sua scadenza è invisibile. Ha fretta *oggi*.
- Un fornitore ICT che serve **più** soggetti NIS compare nell'elenco di ciascuno: la stessa richiesta di garanzie gli arriva da più clienti, e il check-up è la risposta una volta sola a tutte.

## Alternative considerate

- **Contattare prima il soggetto obbligato.** Scartata: è il destinatario con l'urgenza più consumata e la probabilità più alta di avere già un fornitore.
- **Contattare i fornitori senza citare la finestra 15/04–31/05.** Scartata: la finestra è il fatto concreto che rende l'email non generica. Un'email senza un fatto verificabile e non ovvio è indistinguibile da una campagna.
- **Affermare che l'inserimento nell'elenco rende il fornitore automaticamente soggetto NIS.** Scartata: **non è vero**. L'inserimento non produce automaticamente quell'effetto; l'affermazione corretta è che rende concreta e documentata l'esposizione a individuazione ex art. 3, c. 13. Scrivere la versione forte sarebbe un falso normativo — esattamente quello che questo repo esiste per non fare.

## Conseguenze

- Tutta la comunicazione verso i fornitori poggia su un fatto la cui fonte primaria **non è stata reperita direttamente** (il PDF della Det. 127437/2026 dava 404 sul sito ACN il 29/09/2026). Prima di usarlo in una trattativa: scaricare e leggere il testo. La cautela è registrata in `fonti.md` F12.
- Il foglio `dopo-il-checkup.md` diventa un allegato necessario della Versione B: il fornitore, più del soggetto obbligato, chiede "quanto mi costa tutto" prima di firmare.
- Resta invariato il vincolo: nessun contatto parte da qui, nessun cliente viene dichiarato.
