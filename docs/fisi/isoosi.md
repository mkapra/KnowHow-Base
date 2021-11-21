# ISO/OSI-Referenzmodell

* Referenzmodell für Netzwerkprotokolle als Schichtenarchitektur

# | Schicht                      | Einordnung           | TCP/IP-Referenzmodell | Protokollbeispiele       | Kopplungselement                              |
- | -                            | -                    | -                     | -                        | Gateway, Content-Switch, Proxy                |
7 | Anwendungen (Application)    | Anwendungsorientiert | Anwendung             | DHCP, DNS, SMTP, HTTP(s) |                                               |
6 | Darstellung (Presentation)   | Anwendungsorientiert | Anwendung             |                          |                                               |
5 | Sitzung (Session)            | Anwendungsorientiert | Anwendung             |                          |                                               |
4 | Transport                    | Transportorientiert  | Transport             | TCP, UDP                 |                                               |
3 | Vermittlung-/Paket (Network) | Transportorientiert  | Internet              | ICMP, IP, IPsec          | Router, Layer-3-Switch                        |
2 | Sicherung (Data Link)        | Transportorientiert  | Netzzugriff           | MAC                      | Bridge, Layer-2-Switch, Wireless Access Point |
1 | Bitübertragung (Physical)    | Transportorientiert  | Netzzugriff           | 1000BASE-T               | Repeater, Hub, Netzwerkkabel                  |
