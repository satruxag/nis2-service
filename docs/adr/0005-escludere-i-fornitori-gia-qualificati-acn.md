# ADR 0005 — Escludere i fornitori già qualificati ACN dai bersagli del Check-up

*Data: 20 ottobre 2026*

## Stato

Accettato.

## Contesto

Il repo era arrivato al 13 ottobre con una lista di quattro bersagli, scelti col criterio «il fornitore serve un soggetto NIS riconoscibile». Due di quei quattro — EL.CO. (software clinico, 350+ strutture sanitarie) e MYS (suite WebQuality per la sanità) — sembravano i migliori di tutti: settore sanitario, cliente finale palesemente NIS, dimensione PMI.

La verifica del 20 ottobre, fatta contro il Portale Cloud ACN e i siti dei due, ha mostrato che **entrambi sono già qualificati QC2** — MYS con la scheda ACN **SA-3784** (valida 2025–2028, con ISO 27001, ISO 22301, ISO/IEC 20000, CSA STAR L2), EL.CO. con la sua piattaforma *Fenix* dichiarata «ACN — servizi SaaS qualificati di Livello 2 (QC2)». Cioè: sono passati per un processo che, per definizione, richiede ISO 27001 e misure di sicurezza documentate.

Dettaglio in `fonti.md` F17.

## Decisione

Si adotta un **criterio di conferma a quattro punti** per i bersagli, che sostituisce il criterio precedente. Il punto aggiunto è: *il fornitore non deve avere già una qualificazione ACN né una certificazione ISO 27001/22301 recente*. EL.CO. e MYS sono esclusi dalla lista di invio — restano nella mappa come fornitori rilevanti di soggetti NIS, non come destinatari dell'offerta.

## Perché

Il Check-up NIS2 è un prodotto di **diagnosi**: risponde a «cosa ci manca?». Un'organizzazione che ha superato la qualificazione QC2 **ha già la risposta a quella domanda** — le è stata chiesta, con rigore, per ottenere la qualifica. Scrivere a un QC2 «non sapete quali misure vi mancano» significa affermare qualcosa che il destinatario sa essere falso, e la reazione non è la curiosità: è la chiusura del contatto.

Il costo di questa decisione è la rinuncia a due bersagli apparentemente ideali. Il beneficio è che ogni email che parte non può essere smentita dal destinatario con un fatto che lui conosce meglio di noi. In un'offerta di compliance venduta a freddo, la credibilità della prima riga è tutta la trattativa.

## Alternative considerate

- **Tenere EL.CO. e MYS con un'email riformulata** («so che siete QC2; il check-up copre il *vostro* perimetro NIS, diverso dalla qualifica del servizio cloud»). Scartata: l'argomento è difendibile in teoria — la qualifica del *servizio cloud* e l'obbligo del *soggetto NIS* sono cose distinte — ma è un'arringa, non un fatto verificabile dal destinatario in tre minuti. Le email del repo funzionano perché il fatto è controllabile; questa non lo sarebbe.
- **Smetttere di targettizzare i fornitori di software verticale e passare ai clienti NIS diretti.** Non esclusa, ma rimandata: il canale fornitore-rilevante resta il più concreto perché la leva (l'elencazione ACN) esiste già e ha una finestra annuale; il canale cliente diretto va valutato in un ADR separato.
- **Non verificare, spedire ai quattro e vedere le risposte.** Scartata di principio: le email di questo repo non vanno inviate con un fatto smentibile dentro.

## Conseguenze

- La lista dei bersagli passa da quattro nomi a **uno solido (MiPS Informatica, da rifinire) e uno debole (3MSOLUTIONS, da verificare su Else Solutions)**.
- Ogni nuovo candidato passa ora per una ricerca sul Portale Cloud ACN e una per «ISO 27001» sul sito del fornitore prima di entrare in lista. Circa dieci minuti per candidato.
- MiPS solleva una cautela ulteriore, registrata in `contatti/lista-bersagli.md`: organizza già eventi su NIS2, quindi l'email per lui va riscritta da pari, non da consulente che spiega.
