In Parallelschwingkreisen werden Spulen und Kondensatoren kombiniert. Zur genauen Berechnung der Resonanzfrequenz, müssen "unsichtbare" Kapazitäten, wie Wicklungskapazität und Schaltungskapazität,  berücksichtigt werden. Die folgende Aufgabe beschreibt die wirksamen Kapazitäten sehr praxisnah.

[question:AD103]
Das Hauptproblem bei der Lösung der Aufgaben ist die Beachtung und Umwandlung der unterschiedlichen Vorsilben auf eine einheitliche, sinnvolle Vorsilbe, um nicht zu große oder zu kleine Zahlenwerte zu bekommen. Im Abschnitt "Kondensatoren  in Reihen- und Parallelschaltung "   der Klasse E wurde dies schon ausführlich erklärt. 
Als gemeinsame Vorsilbe sollten bei der folgenden Frage alle Kapazitätswerte in Picofarad (pF) umgewandelt werden, da auch das Ergebnis in Picofarad angegeben ist. Die Eigenkapazität der Spule (Kapazität der Windungen gegeneinander) muss zusätzlich addiert werden.

Schwieriger ist die Berechnung einer Reihenschaltung von 3 Kondensatoren.

Bei der folgenden Aufgabe hat die kleinste Kapazität den Wert 22 pF.
Die Gesamtkapazität muss deshalb kleiner als 22 pF sein. Da in der Lösung zwei Ergebnisse unter 22pF zu finden sind, ist keine Abschätzung möglich, sondern es ist eine Rechnung notwendig.
$\frac{1}{C_{G}} = \frac{1}{C_{1}} + \frac{1}{C_{2}} + \frac{1}{C_{3}}$
(siehe Formelsammlung Seite 236 unten -  Stichwort: Kondensatoren in Reihenschaltung )


---
[question:AD101]

<tip>
 Man gibt die Kapazitätswerte immer mit der 1/x - Taste in den Taschenrechner ein und muss am Schluss nochmals 1/x drücken.
</tip>
C1 mit 0,1 nF muss in Picofarad umgewandelt werden. Dies ergibt 100pF.
$\frac{1}{C_{G}} = \frac{1}{100} + \frac{1}{47} + \frac{1}{22}$

---
[question:AD104]
<indepth>
% Widerstandsdreieck R - XC in Latex erstellen
[photo:301:a_R-C Widerstandsdreieck:Widerstandsdreieck für die Reihenschaltung von R und $X_C$]
Das Widerstandsdreieck für die Reihenschaltung von R und $X_C$ veranschaulicht grafisch die Berechnung mit der Formel $|Z| = \sqrt{R^2 + {X_C}^2} = \sqrt{(100\Omega)^2 + (159\Omega)^2}$
  Zusätzlich sieht man auch den Phasenverschiebungswinkel $\varphi$ zwischen U und I und das I voreilend ist.
</indepth>


Zur Berechnung eines Scheinwiderstandes benutzen wir die Formel
$|Z| = \sqrt{R^2 + X^2}$
(siehe Formelsammlung Seite 235 unten rechts - Stichwort: Wechselspannung -> Scheinwiderstand)
Zur Anwendung dieser Formel muss der Blindwiderstand Xc des Kondensators bei 1 MHz zuerst berechnet werden.
Die Formel für $X_{\textrm{C}}$ lautet:
$X_{\textrm{C}} = \frac{1}{\omega \cdot C}$
(siehe Formelsammlung Seite 236 unten links - Stichwort: Kapazität -> kapazitiver Blindwiderstand )

Bei der Eingabe der Bauteilwerte in den Taschenrechner müssen die Zehnerpotenzen sorgfältig hinzugefügt werden.
1 MHz = 1 x $10^6$ Hz; 1 nF = 1 x $10^{-9}$ F
$X_C$ ergibt sich dann für den 1 nF Kondensator bei 1 MHz zu  $159\Omega$.
Nun kann der Scheinwiderstand  |Z| berechnet werden.
$|Z| = \sqrt{R^2 + {X_C}^2}$

---
[question:AD105]
Der Rechenweg ist der Gleiche wie vorher beschrieben und die Zehnerpotenzen sind wieder zu beachten:
100 µH =  100 x $10^{-6}$ H
1 MHz = 1 x $10^6$ Hz
$X_{\textrm{L}}$ muss mit der Formel  $X_{\textrm{L}} = \omega \cdot L$ zuerst  berechnet werden, danach kann die Berechnung des Scheinwiderstandes  |Z|  mit der Formel $|Z| = \sqrt{R^2 + {X_L}^2}$ erfolgen.

<indepth>
% Widerstandsdreieck R - XL in Latex erstellen

[photo:302:a_R-L Widerstandsdreieck:Widerstandsdreieck für die Reihenschaltung von R und $X_L$]
Das Widerstandsdreieck für die Reihenschaltung von R und $X_L$ veranschaulicht grafisch die Berechnung mit der Formel $|Z| = \sqrt{R^2 + {X_L}^2} = \sqrt{(100\Omega)^2 + (628\Omega)^2} $
Zusätzlich sieht man auch den Phasenverschiebungswinkel $\varphi$ zwischen U und I und das I nacheilend ist.
</indepth>


<margin>
Lösungshilfe
AD 103: 100 pF + 1500 pF + 220 pF + 1 pF = 1821 pF
AD 101: 13 pF
AD 104: $X_C$ = $ \frac{1}{{6,28 \cdot 1 \  {10^6} Hz} \cdot 1 \ 10^{-9}\  F}$ = 159 Ohm
$|Z| = \sqrt{R^2 + {X_C}^2} = \sqrt{(100\Omega)^2 + (159\Omega)^2} \approx 188\Omega$ 
AD 105: 636 Ohm
$X_{\textrm{L}} = \omega \cdot L = 2 \cdot \pi \cdot f \cdot L = 2 \cdot \pi \cdot 1MHz \cdot 100\mu H = 628\Omega$
$|Z| = \sqrt{R^2 + {X_L}^2} = \sqrt{(100\Omega)^2 + (628\Omega)^2} \approx 636\Omega$
</margin>