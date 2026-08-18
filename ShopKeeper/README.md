# ShopKeeper VR

### Serious game immersivo in realtà virtuale per l'allenamento della memoria spaziale

<p align="center">
  <img src="Foto-Video/Ex1.png" width="600">
</p>

## Overview

Il progetto, realizzato presso l'Università degli Studi di Udine, nasce con l'obiettivo di sviluppare un'esperienza coinvolgente per l'allenamento della memoria spaziale, ovvero la capacità di ricordare la posizione e la disposizione degli oggetti all'interno di un ambiente.

Il serious game è strutturato su più livelli a difficoltà crescente ed è stato sviluppato per essere utilizzato tramite un visore di realtà virtuale, rendendo l'esperienza più realistica e immersiva.

L'utente viene trasportato all'interno di un negozio di calzature virtuale, dove deve memorizzare la posizione delle scarpe presenti sugli scaffali e successivamente riposizionarle correttamente.

Come sistema di locomozione è stato implementato il **teletrasporto**, scelto per ridurre il rischio di motion sickness durante i frequenti spostamenti all'interno dell'ambiente virtuale.

## Gameplay

L'utente esplora l'ambiente tramite il visore VR e utilizza i controller per afferrare e rilasciare le scarpe e teletrasportarsi all'interno del negozio.

L'esperienza è composta da **5 livelli a difficoltà crescente**. Con l'aumentare del livello crescono sia la dimensione del negozio sia il numero di scarpe da memorizzare e riposizionare.

Ogni livello è suddiviso in due fasi:

### Fase 1: **Memorizzazione**

L'utente dispone di un tempo limitato per esplorare l'ambiente e memorizzare la posizione delle scarpe presenti sugli scaffali.

<p align="center">
  <img src="https://raw.githubusercontent.com/MarcoTateo/Portfolio-progetti/main/ShopKeeper/Foto-Video/Mem_GIF.gif" width="700">
</p>

### Fase 2: **Riposizionamento**

L'utente dispone di un tempo limitato per riposizionare sugli scaffali le scarpe che compaiono al centro della stanza. Dopo ogni posizionamento corretto viene mostrata una nuova scarpa da collocare.

Inizialmente sugli scaffali rimangono alcune scarpe che fungono da riferimento visivo. A intervalli regolari, queste scompaiono progressivamente in modo casuale, riducendo gli indizi disponibili.

Nella fase finale l'utente deve quindi affidarsi esclusivamente alla propria memoria per individuare le posizioni corrette.

Il sistema calcola inoltre il **punteggio dell'utente** sulla base del numero di scarpe riposizionate correttamente.

<p align="center">
  <img src="https://raw.githubusercontent.com/MarcoTateo/Portfolio-progetti/main/ShopKeeper/Foto-Video/Posizionamento_GIF.gif" width="700">
</p>

## Tecnologie utilizzate

Il progetto è stato sviluppato utilizzando il game engine ***Unity*** e il linguaggio ***C#***.

Per l'esperienza immersiva è stato utilizzato il visore ***Meta Quest 2***, mentre le interazioni e il sistema di locomozione sono stati implementati tramite ***XR Interaction Toolkit***.

## Test

Il sistema è stato testato con diversi utenti per valutarne l'usabilità e analizzare l'eventuale presenza di correlazioni tra le caratteristiche delle scarpe, come tipologia e colore, e la facilità di memorizzazione.

## Il mio ruolo

Mi sono occupato della progettazione e dello sviluppo dell'esperienza, implementando le principali meccaniche di gioco, le interazioni con gli oggetti, il sistema di locomozione tramite teletrasporto, la gestione dei livelli e il sistema di punteggio.

Mi sono inoltre occupato della raccolta dei dati ottenuti durante i test e della successiva analisi delle possibili correlazioni.
