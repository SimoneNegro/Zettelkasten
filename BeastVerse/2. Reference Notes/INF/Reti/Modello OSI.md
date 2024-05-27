---
id: INF-00001
tags:
  - Informatica
  - Reti
  - Modello
data: 2024-05-24
author: Negro Simone
status: Work In Progress
---
Il modello OSI (_Open Systems Interconnection_, conosciuto come "modello ISO/OSI") è uno standard per la comunicazione di messaggi in una rete di calcolatori. 
Questo modello è strutturato a strati ed è composto da una pila di [protocolli](Protocollo%20di%20rete.md) di comunicazione di rete suddivisa in 7 livelli.

| *N°* | *Livello*                                                          | *Descrizione*                                                              | *Unità di dato* |
| :--: | ------------------------------------------------------------------ | -------------------------------------------------------------------------- | --------------- |
|  7   | [Applicazione](Livello%20di%20applicazione.md)                     | Supporta applicazioni network                                              | Dati            |
|  6   | Presentazione                                                      | Trasforma i dati di un applicazione in un formato standard                 | Dati            |
|  5   | Sessione                                                           | Instaura, mantiene e chiude le connessioni tra applicazioni cooperanti     | Dati            |
|  4   | [Trasporto](Livello%20di%20trasporto.md)                           | Trasferimento dati tra due host (end-to-end)                               | Segmenti        |
|  3   | [Rete](Livello%20di%20rete.md)                                     | Instradamento pacchetto da mittente a destinatario (indirizzamento logico) | Pacchetti       |
|  2   | [Data Link](Livello%20di%20collegamento%20dati%20(data%20link).md) | Trasferimento dati a livello fisico (indirizzamento fisico)                | Frame           |
|  1   | [Fisico](Livello%20fisico.md)                                      | Mezzo trasmissivo                                                          | Bit             |

![Elenco protocolli di rete](Elenco%20protocolli%20di%20rete.md)

#### References
- [Modello TCP/IP](Modello%20TCP-IP.md)
- [Protocollo di rete](Protocollo%20di%20rete.md)
- [Elenco protocolli di rete](Elenco%20protocolli%20di%20rete.md)