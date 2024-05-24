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
Questo modello è strutturato a strati ed è composto da una pila di protocolli di comunicazione di rete suddivisa in 7 livelli.

| *N°* | *Livello*                                                          | *Descrizione*                                                              | *Unità di dato* |
| :--: | ------------------------------------------------------------------ | -------------------------------------------------------------------------- | --------------- |
|  7   | [Applicazione](Livello%20di%20applicazione.md)                     | Supporta applicazioni network                                              | Dati            |
|  6   | Presentazione                                                      | Trasforma i dati di un applicazione in un formato standard                 | Dati            |
|  5   | Sessione                                                           | Instaura, mantiene e chiude le connessioni tra applicazioni cooperanti     | Dati            |
|  4   | [Trasporto](Livello%20di%20trasporto.md)                           | Trasferimento dati tra due host (end-to-end)                               | Segmenti        |
|  3   | [Rete](Livello%20di%20rete.md)                                     | Instradamento pacchetto da mittente a destinatario (indirizzamento logico) | Pacchetti       |
|  2   | [Data Link](Livello%20di%20collegamento%20dati%20(data%20link).md) | Trasferimento dati a livello fisico (indirizzamento fisico)                | Frame           |
|  1   | [[Fisico]]                                                         | Mezzo trasmissivo                                                          | Bit             |
Protocolli utilizzati dai vari layer:
1. Livello fisico: 
	- [Bluetooth](Bluetooth.md)
2. Livello link:
	- [Ethernet](Ethernet.md)
	- [Wi-Fi](Wi-Fi.md)
3. Livello rete:
	- [IP](IP.md)
4. Livello trasporto:
	- [TCP](Transmission%20Control%20Protocol%20(TCP).md)
	- [UDP](User%20Datagram%20Protocol%20(UDP).md)
5. Livello sessione:
6. Livello presentazione:
	- [ASCII](ASCII.md)
7. Livello applicazione:
	- [DHCP](Dynamic%20Host%20Configuration%20Protocol%20(DHCP).md)
	- [DNS](Domain%20Name%20System%20(DNS).md)
	- [HTTP](Hypertext%20Transfer%20Protocol%20(HTTP).md)
	- [SSH](Secure%20Shell%20(SSH).md)
#### References
- [Modello TCP/IP](Modello%20TCP-IP.md)