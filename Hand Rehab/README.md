# Haptic Hand Rehab

Sistema interattivo in realtà virtuale per la riabilitazione della mano mediante guanti aptici.

## Overview

Questo progetto è stato realizzato presso l'Università degli Studi di Udine con l'obiettivo di sviluppare un sistema di riabilitazione della mano basato sulla realtà virtuale e sull'utilizzo di guanti aptici.

La riabilitazione avviene attraverso esercizi e task virtuali che ripropongono movimenti della mano utilizzati nella riabilitazione tradizionale, con particolare attenzione alle prese utilizzate nelle **Activities of Daily Living (ADL)**.

L'utilizzo di un visore VR e dei guanti aptici **SenseGlove Nova** rende l'esperienza più immersiva e interattiva, con l'obiettivo di aumentare il coinvolgimento e la motivazione del paziente durante esercizi riabilitativi che, se ripetuti nel tempo, possono risultare monotoni.

Una caratteristica particolare del sistema è l'**amplificazione del movimento delle dita**: il movimento della mano virtuale può essere amplificato rispetto a quello effettivamente eseguito dalla mano reale. Questa funzionalità è stata pensata per pazienti con mobilità delle dita limitata, permettendo loro di interagire più facilmente con gli oggetti virtuali e di visualizzare movimenti più ampi rispetto a quelli fisicamente eseguiti.

## Gameplay

All'interno dell'ambiente virtuale l'utente rimane in una posizione fissa e interagisce con gli oggetti attraverso le proprie mani utilizzando i guanti aptici.

All'avvio del sistema, l'utente si trova nella stanza principale, dove l'obiettivo è completare un puzzle composto da cubi. I cubi vengono sbloccati progressivamente completando quattro differenti task.

L'immagine raffigurata dal puzzle può essere personalizzata da un operatore esterno.

<p align="center">
  <img src="" width="600">
</p>

### Task 1: Stanza dei cubi

L'utente deve costruire una torre di mattoncini cercando di renderla il più stabile e precisa possibile. La precisione nel posizionamento dei mattoncini viene rilevata dal sistema e utilizzata per calcolare e aggiornare progressivamente il punteggio.

<p align="center">
  <img src="Media/Cube_GIF.gif" width="600">
</p>

### Task 2: Stanza dei colori

L'utente deve riprodurre un colore mostrato dal sistema utilizzando delle bombolette spray virtuali contenenti i colori primari **rosso, verde e blu**, oltre a bianco e nero.

L'obiettivo è individuare la corretta combinazione dei colori per avvicinarsi il più possibile al colore richiesto. Al termine, il sistema calcola un punteggio sulla base della somiglianza tra il colore ottenuto e quello mostrato.

<p align="center">
  <img src="Media/Color_GIF.gif" width="600">
</p>

### Task 3: Garage

Il task è ambientato in un garage, dove l'utente deve costruire una sedia di legno partendo da alcune tavole.

Le tavole devono essere tagliate utilizzando una sega circolare e successivamente assemblate per ottenere la struttura finale della sedia.
<br>
<p align="center">
  <img src="Media/Cut_GIF.gif" width="50%">
  <em>Fase di taglio</em>
</p>
<br>
<p align="center">
  <img src="Media/Assemble_GIF.gif" width="50%">
  <em>Fase di assemblaggio</em>
</p>
<br>

### Task 4: Laboratorio

L'utente si trova in un laboratorio di chimica e ha il compito di preparare diverse sostanze seguendo delle ricette.

Per completare il task deve inizialmente sbloccare le sostanze necessarie aprendo un armadietto, per poi prelevarle e versarle nei contenitori appropriati seguendo le quantità e le combinazioni indicate.

<p align="center">
  <img src="" width="600">
</p>

## Test

Il sistema è stato testato da diversi esperti nell'ambito della riabilitazione dell'**Istituto di Medicina Fisica e Riabilitazione Gervasutta**.

Il test svolto è stato di tipo qualitativo e aveva lo scopo di ottenere una prima valutazione preliminare del sistema e della sua possibile applicazione in ambito riabilitativo.

Le valutazioni degli esperti sono risultate complessivamente positive, evidenziando interesse verso una possibile integrazione di sistemi di questo tipo all'interno di percorsi riabilitativi.

## Tecnologie utilizzate

Il sistema è stato sviluppato utilizzando **Unity** e **C#**.

L'hardware utilizzato comprende:

- **Meta Quest 2**
- **SenseGlove Nova**

Per l'integrazione e la gestione dei guanti aptici all'interno dell'ambiente virtuale è stato utilizzato e modificato il **SenseGlove SDK**.

## Il mio ruolo

Il sistema è stato interamente progettato e sviluppato da me.

Mi sono occupato della progettazione degli esercizi riabilitativi, dello sviluppo degli ambienti virtuali e delle interazioni, dell'integrazione dei guanti aptici **SenseGlove Nova** e della personalizzazione del relativo SDK.

Mi sono inoltre occupato della progettazione e dello svolgimento della fase di test con gli esperti in riabilitazione.

