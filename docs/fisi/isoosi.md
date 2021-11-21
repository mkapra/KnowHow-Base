# ISO/OSI-Referenzmodell

* Referenzmodell für Netzwerkprotokolle als Schichtenarchitektur

| Nr. | Schicht                      | TCP/IP-Referenzmodell | Protokollbeispiele       | Kopplungselement                              |
| -   | -                            | -                     | -                        | -                                             |
| 7   | Anwendungen (Application)    | Anwendung             | DHCP, DNS, SMTP, HTTP(s) | Gateway, Content-Switch, Proxy                |
| 6   | Darstellung (Presentation)   | Anwendung             |                          |                                               |
| 5   | Sitzung (Session)            | Anwendung             |                          |                                               |
| 4   | Transport                    | Transport             | TCP, UDP                 |                                               |
| 3   | Vermittlung-/Paket (Network) | Internet              | ICMP, IP, IPsec          | Router, Layer-3-Switch                        |
| 2   | Sicherung (Data Link)        | Netzzugriff           | MAC                      | Bridge, Layer-2-Switch, Wireless Access Point |
| 1   | Bitübertragung (Physical)    | Netzzugriff           | 1000BASE-T               | Repeater, Hub, Netzwerkkabel                  |

* Die Schichten 5-7 sind dabei als `anwendungsorientiert` einzuordnen
* Die Schichten 1-4 sind `transportorientiert`
