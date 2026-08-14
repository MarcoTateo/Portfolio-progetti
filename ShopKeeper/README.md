# ShopKeeper VR

### Serious game immersivo in realtà virtuale per l'allenamento della memoria spaziale

## Overview

Il progetto, realizzato presso l'Università degli Studi di Udine, nasce con l'obiettivo di sviluppare un'esperienza coinvolgente per l'allenamento della memoria spaziale, ovvero la capacità di ricordare la posizione e la disposizione degli oggetti all'interno di un ambiente.

Il serious game è strutturato su più livelli a difficoltà crescente ed è stato sviluppato per essere utilizzato tramite un visore di realtà virtuale, rendendo l'esperienza più realistica e immersiva.

L'utente viene trasportato all'interno di un negozio di calzature virtuale, dove deve inizialmente memorizzare la posizione delle scarpe presenti sugli scaffali e, successivamente, riposizionarle nelle corrette posizioni.

Come sistema di locomozione è stato implementato il teletrasporto. Questa scelta è stata adottata per ridurre il rischio di motion sickness, considerando la necessità dell'utente di spostarsi frequentemente all'interno dell'ambiente virtuale.

## Gameplay

L'utente esplora l'ambiente attraverso il visore VR e utilizza i controller per interagire con gli oggetti, afferrare e rilasciare le scarpe e teletrasportarsi all'interno del negozio virtuale.

L'esperienza è composta da **3 livelli a difficoltà crescente**. Con l'aumentare del livello cresce il numero di scarpe che l'utente deve memorizzare e successivamente riposizionare.

Ogni livello è suddiviso in due fasi:

### Fase 1: **Memorizzazione**

L'utente dispone di un tempo limitato per esplorare l'ambiente e memorizzare la posizione delle scarpe presenti sugli scaffali. Allo scadere del tempo, le scarpe scompaiono.

### Fase 2: **Riposizionamento**

Al centro della stanza compaiono le scarpe che l'utente deve riposizionare sugli scaffali. Il corretto o errato posizionamento viene segnalato attraverso la colorazione dello slot corrispondente: **verde** in caso di posizione corretta e **rosso** in caso di errore.

## Tecnologie utilizzate

Il progetto è stato sviluppato utilizzando il game engine ***Unity*** e il linguaggio ***C#***.

Per l'esperienza immersiva è stato utilizzato il visore ***Meta Quest 2***, mentre per la gestione delle interazioni e della locomozione in realtà virtuale è stato utilizzato il pacchetto ***XR Interaction Toolkit***.

## Test

Il sistema è stato testato con diversi utenti con l'obiettivo di valutarne l'usabilità e analizzare l'eventuale presenza di correlazioni tra le caratteristiche delle scarpe, come tipologia e colore, e la facilità con cui la loro posizione veniva memorizzata.
## Media

<p align="center">
  <img src="Foto-Video/Ex1.png" width="600">
</p>
