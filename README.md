# Semplificazione Amministrativa: Moduli PA

Nell&apos;ambito delle attivit&agrave;  in corso del **Tavolo tecnico interoperabilit&agrave;  per la semplificazione amministrativa**, il presente progetto &egrave; stato reso disponibile come area di condivisione per le attivit&agrave;  del Gruppo di Lavoro denominato **XSD Schema** per dare seguito alla linea d&apos;azione **Formalizzazione Moduli PA**.

L&apos;obiettivo del GdL &egrave; di *formalizzare i moduli approvati dalla Conferenza Unificata del 4 maggio 2017* attraverso l&apos;utilizzo delle specifiche dello standard XSD mantenute dal XML Schema Working Group del W3C, utilizzando nel dettaglio: 

- *W3C XML Schema Definition Language (XSD) 1.1 Part 1: Structures* 
- *W3C XML Schema Definition Language (XSD) 1.1 Part 2: Datatypes*

Si intende definire un data model che organizza i data entity attraverso l&apos;implementazione in maniera gerarchica degli opportuni XSD.

Una prima analisi realizzata da AgID ha evidenziato la possibilit&agrave;  di procedere alla definizione di: 

- un core vocabulary che definisce tutti i data entity comuni a tutti i moduli, suddiviso in data entity elementari (come ad esempio: nome, cognome, etc.) e data entity aggregati (come ad esempio: persona costituito da nome, cognome, etc.);
- eventuali scope vocabulary che a partire dai data entity presenti nel core vocabulary definisce i data entity comuni ad uno dei specifici ambiti di interesse: Attivit&agrave;  commerciali e assimilabili, Edilizia e Ambiente.
- la definizione di specifici XSD per ogni modulo che assicuri la formalizzazione dei moduli a partire dal core vocabulary e scope vocabulary.

L'attività svolta dal **GdL XML Shema** assicura la formalizzazione dei moduli approvati in Conferenza Unificata (Accordo del 04/05/2017, Accordo del 06/07/2017) attraverso un processo incrementale.
