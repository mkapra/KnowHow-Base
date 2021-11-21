# USV

## Voltage and Frequency Dependent (VFD) Offline-USV

![Offline-USV](../img/offline_usv.png)

* Auch `Standby-` oder `Offline-USV` genannt
* Schützt nur vor totalem Netzausfall. Stromschwankungen können nicht ausgeglichen werden
* Bei Ausfall übernimmt ein Akku die Versorgung
* *Schaltzeiten*: Innerhalb weniger Millisekunden
* Aufladen des Akkus erfolgt im Normalbetrieb über den sogenannten `Ladegleichrichter`
* Wirkungsgrad: 95%
* Wird meist bei Kleinst-Verbrauchern oder nur für einzelne Computer eingesetzt

## Voltage Independent (VI) Line Interactive-USV

![Line Interactive-USV](../img/line_interactive_usv.png

* Auch `Netzinteraktive-USV` bezeichnet
* Schützt vor Totalausfall und gegen Schwankungen
* Spannungsregler zwischen `Netzeingang` und `Verbraucher`
* Eignet sich gut für Umgebungen mit vielen Spannungsschwankungen
* Wirkungsgrad: 95% - 98%
* Gut für
    - Einzelne Computersysteme
    - Netzwerke
    - größere `TK-Anlagen`[^1]
* Sollte **nicht** für hochsensible Systeme genutzt werden

## Voltage and Frequency Independent (VFI) Online-USV

![Online-USV](../img/online_usv.png)

* Auch `Dauerwandler-USV` genannt
* Bietet maximalen Schutz
* Gleicht Schwankungen der Spannung und auch der Netzfrequenz aus
* Verbraucher wird im `Normalbetrieb` dauerhaft über Akku versorgt. Daher braucht es auch keine
  Schaltzeiten bei einem Ausfall
* Arbeitet mit einem `Dauerwandlerprinzip`[^2]
* Durch das ständige Wandeln der Spannung entsteht Verlust und Wärme. Dadurch ist auch der
  Wirkungsgrad gering und liegt bei 90%
* Akku steht unter Dauerbelastung: Aus diesem Grund hält er im Schnitt zur drei bis vier Jahre
* Wird oft in der Server- und Datenkommunikation genutzt

[^1]: Telekommunikations-Anlagen
[^2]: Wandlung von Wechsel- in Gleichspannung und von Gleich- in Wechselspannung
