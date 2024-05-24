---
id: INF-00001
tags:
  - Informatica
  - Reti
  - Modello
  - WIP
data: 2024-05-24
author: Negro Simone
status: Work In Progress
---
Il modello OSI (_Open Systems Interconnection_, conosciuto come "modello ISO/OSI") è uno standard per la comunicazione di messaggi in una rete di calcolatori. 
Questo modello è strutturato a strati ed è composto da una pila di protocolli di comunicazione di rete suddivisa in 7 livelli.

| *N°* | *Livello*                       | *Descrizione*                                              | *Unità di dato* |
| :--: | ------------------------------- | ---------------------------------------------------------- | --------------- |
|  7   | [Applicazione](Applicazione.md) | Supporta applicazioni network                              | Dati            |
|  6   | Presentazione                   | Trasforma i dati di un applicazione in un formato standard | Dati            |
|  5   | Sessione                        |                                                            | Dati            |
|  4   | [Trasporto](Trasporto.md)       |                                                            | Segmenti        |
|  3   | [[Rete]]                        |                                                            | Pacchetti       |
|  2   | [[Data Link]]                   |                                                            | Frame           |
|  1   | [[Fisico]]                      |                                                            | Bit             |

#### References
