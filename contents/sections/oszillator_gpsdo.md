Zur Erzielung einer sehr hohen Stabilität eines Oszillators gibt es zwei Möglichkeiten, diesen zu stabilisieren (oder auch zu disziplinieren).
1. Temperaturstabilisierung des Oszillators durch festgelegte und geregelte Umgebungsparameter. Hierdurch ergibt sich eine gute Kurzzeitstabilität des Oszillators.
2. Anbindung des Oszillators an ein externes, hochgenaues Referenzsignal. Hierdurch ergibt sich eine gute Langzeitstabilität des Oszillators.

Beim GPSDO wird für den Oszillator ein OCXO (Oven Controlled Crystal Oscillator nach 1.) als Primäroszillator verwendet, der mittels eines hochgenauen Referenzsignals (nach 2.), das über das GPS-Satellitennavigationssystem gewonnen wird, langzeitstabilisiert wird. Die Kurzzeitstabilität des GPSDO wird hierbei durch die Temperaturstabilisierung des Primäroszillators (OCXO) erreicht.
Ein GPSDO besitzt somit eine hohe Kurz- und Langzeitstabilität.

<tip>
GPSDO-Oszillatoren werden vor allem dann verwendet, wenn es auf hochgenaue Frequenzerzeugung ankommt. Dies ist insbesondere beim Betrieb auf höheren Frequenzbändern im $\unit{\giga\hertz}$-Bereich wichtig, da hier bereits kleinste Abweichungen des Referenzoszillators zu großen Frequenzdrifts führen können. Grund hierfür ist, dass die Sende- und Empfangsfrequenzen mittels Vervielfachung aus der Referenzfrequenz erzeugt werden und sich Fehler somit multiplikativ auswirken.
</tip>

[question:AD606]