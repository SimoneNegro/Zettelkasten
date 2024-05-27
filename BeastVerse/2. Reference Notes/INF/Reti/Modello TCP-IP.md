---
id: INF-00002
tags:
  - Informatica
  - Reti
  - Modello
data: 2024-05-27
author: Negro Simone
status: Work In Progress
---
Il modello TCP/IP (Transmission Control Protocol/Internet Protocol) è uno standard per la comunicazione di messaggi in una rete di calcolatori. Questo modello è strutturato a strati ed è composto da una pila di [protocolli](Protocollo%20di%20rete.md) di comunicazione di rete suddivisa in 5 livelli.

| *N°* | *Livello*                                                          | *Descrizione*                                                              | *Unità di dato* |
| :--: | ------------------------------------------------------------------ | -------------------------------------------------------------------------- | --------------- |
|  5   | [Applicazione](Livello%20di%20applicazione.md)                     | Supporta applicazioni network                                              | Dati            |
|  4   | [Trasporto](Livello%20di%20trasporto.md)                           | Trasferimento dati tra due host (end-to-end)                               | Segmenti        |
|  3   | [Rete](Livello%20di%20rete.md)                                     | Instradamento pacchetto da mittente a destinatario (indirizzamento logico) | Pacchetti       |
|  2   | [Data Link](Livello%20di%20collegamento%20dati%20(data%20link).md) | Trasferimento dati a livello fisico (indirizzamento fisico)                | Frame           |
|  1   | [Fisico](Livello%20fisico.md)                                      | Mezzo trasmissivo                                                          | Bit             |

![Elenco protocolli di rete](Elenco%20protocolli%20di%20rete.md)
#### References
- [Modello OSI](Modello%20OSI.md)
- [Protocollo di rete](Protocollo%20di%20rete.md)
- [Elenco protocolli di rete](Elenco%20protocolli%20di%20rete.md)
https://www.ibm.com/docs/en/aix/7.2?topic=protocol-tcpip-protocols