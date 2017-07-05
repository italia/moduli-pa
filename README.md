# Semplificazione Amministrativa

Nell'ambito delle attività in corso del **Tavolo tecnico interoperabilit&agrave;� per la semplificazione amministrativa**, il presente progetto è stato reso disponibile come area di condivisione per le attività del Gruppo di Lavoro denominato **XSD Schema** per dare seguito alla linea d'azione **Formalizzazione Moduli PA**.

L’obiettivo del GdL di *formalizzare i moduli approvati dalla Conferenza Unificata del 4 maggio 2017* attraverso l’utilizzo dello standard XSD mantenute dal XML Schema Working Group del W3C, usando i seguenti standard: 

- *W3C XML Schema Definition Language (XSD) 1.1 Part 1: Structures* 
- *W3C XML Schema Definition Language (XSD) 1.1 Part 2: Datatypes*

Si intende definire un data model che organizza i data entity attraverso l’implementazione in maniera gerarchica degli opportuni XSD.

Una prima analisi realizzata da AgID ha evidenziato la possibilità di procedere alla definizione di: 

- un core vocabulary che definisce tutti i data entity comuni a tutti i moduli, suddiviso in data entity elementari (come ad esempio: nome, cognome, …) e data entity aggregati (come ad esempio: persona costituito da nome, cognome, …);
-	eventuali scope vocabulary che a partire dai data entity presenti nel core vocabulary definisce i data entity comuni ad uno dei specifici ambiti di interesse: Attività commerciali e assimilabili, Edilizia e Ambiente.
-	la definizione di specifici XSD per ogni modulo che assicuri la formalizzazione dei moduli a partire dal core vocabulary e scope vocabulary.

L’azione di definizione del data model oggetto dovrà tener presente le specifiche tecniche emesse in ottemperanza all’art. 3 - Pubblicazione delle specifiche di formato del DPR 160/2010.
