Das Verhalten eines Kondensators an einer Wechselspannung soll nun genauer betrachtet werden.

Die Strom- und Spannungsmessung an einem Kondensator mit Hilfe eines Zweikanal-Oszilloskops zeigt ein überraschendes Ergebnis, denn man sieht eine Phasenverschiebung von 90 Grad, wobei der Strom der Spannung vorauseilt.

Merke: Kondensatooor, Strom eilt vooor!

---
[question:AC101]
<margin>
[photo:268:a_I_eilt_vor:Phasenverschiebung am Kondensator zwischen Spannung und Strom]
</margin>

[picture:943:a_Blindleistung_Kondensator:Das Produkt von $U \cdot I$ ergibt die grüne Leistungskurve]

Die Phasenverschiebung zwischen Spannung und Strom beträgt $\qty{90}{\degree}$, wobei der Strom voreilend ist. Daraus ergibt sich eine Leistungskurve, die um die Nulllinie symmetrisch schwankt. Der Mittelwert der Leistungskurve ergibt Null, d.h. es wird keine Wirkleistung aufgenommen. Wir sprechen deshalb bei einem verlustfreien Kondensator von Blindleistung und Blindwiderstand.
% entfernt photo:258:a_Blindleistung:Blindleistung siehe grüne Sinuskurve

[question:AC111]
Diese Frage können wir ohne Rechnung beantworten: Nur ein ohmscher Widerstand nimmt Wirkleistung auf, denn bei ihm sind Spannung und Strom in Phase, d.h. es gibt keine Phasenverschiebung zwischen Spannung und Strom. Das bedeutet Strom und Spannung sind immer gleichzeitig positiv oder negativ und damit ist die Leistung $U\cdot I$ immer positiv. Ein Blindwiderstand nimmt keine Wirkleistung auf und deshalb wird er im Idealfall auch nicht warm. Sollte ein Kondensator bei Hochfrequenzanwendungen warm werden, dann hat er Verluste und muss durch einen Kondensator mit geringeren Verlusten ersetzt werden.

[question:AC103]

Wird ein Kondensator an Wechselspannung angeschlossen, dann fließt ein Wechselstrom, denn der Kondensator wird ständig geladen und entladen. Um diese Eigenschaft zu beschreiben sagen wir, der Kondensator hat einen Wechselstromwiderstand und nennen diesen Widerstand kapazitiver Blindwiderstand $X_C$.

1. Wenn die Frequenz der Wechselspannung an einem Kondesator erhöht wird, dann fließt mehr Strom. Dies bedeutet, der kapazitive Blindwiderstand ist kleiner geworden. 
2. Wenn die Kapazität des Kondensators erhöht wird, dann steigt auch der Strom, d.h. der Blindwiderstand wird auch kleiner.

Daraus ergibt sich die Berechnungsformel (siehe Formelsammlung: Kapazitiver Blindwiderstand):
$X_C = \frac{1}{\omega \cdot C} = \frac{1}{2\pi \cdot f \cdot C}$

Moderne, kostengünstige Messgeräte, die Funkamateure heutzutage gerne einsetzen, sind Antennenanalyzer oder vektorielle Network Analyzer (VNA). Sie messen die Veränderung des Blindwiderstandes $X_C$ in Abhängigkeit der Frequenz und können das Messergebnis auch grafisch darstellen.

[photo:248:a_kapazitiver_Blindwiderstand:Kapazitiver Blindwiderstand $X_C$]

Abbildung [ref:a_kapazitiver_Blindwiderstand] zeigt die Veränderung des kapazitiven Blindwiderstandes (blaue Linie) eines $\qty{1500}{\pico\farad}$ Styroflexkondensators im Frequenzbereich von $\qtyrange{1}{4,5}{\mega\hertz}$. Die rote Linie stellt die Phasenlage des kapazitiven Blindwiderstandes bei nahezu konstanten $\qty{-90}{\degree}$ dar.

[question:AC102]

Die blaue Linie von Abbildung [ref:a_kapazitiver_Blindwiderstand] hilft zur Lösung.

---

<tip>
Kennt man den kapazitiven Blindwiderstand und die Frequenz der Wechselspannung, dann kann auch die Kapazität des Kondensators berechnet werden. 
Betrachten wir das Beispiel genauer und verwenden die Formel:
$X_C = \frac{1}{\omega \cdot C} = \frac{1}{{2\pi \cdot f \cdot C}}$
umgestellt nach C:
$C =\frac{1}{{2\pi \cdot f \cdot X_C}}$
mit eingesetzten Werten aus der Abbildung [ref:a_kapazitiver_Blindwiderstand]: 

$X_C = \qty{50}{\ohm} \text{ bei } \qty{2}{\mega\hertz}$
$C = \frac{1}{6,28 \cdot 2 \cdot 10^6 \cdot 50}$
Bei der Berechnung mit dem Taschenrechner ist die Zehnerpotenz für Megahertz einzugeben.
Das Ergebnis lautet: $\qty{0,000000001592}{\farad}$
$C = \qty{1592}{\pico\farad}$
</tip>

[question:AC104]
Bei den folgenden Berechnungen von $X_C$ müssen immer die Zehnerpotenzen beachtet werden. Die Berechnungsformel lautet:
$X_C = \frac{1}{\omega \cdot C} = \frac{1}{{2\pi \cdot f \cdot C}}$

Folgende Werte müssen eingesetzt werden: $C = \qty{10}{\pico\farad} = \qty{10e-12}{\farad}$ und $f = \qty{100}{\mega\hertz} = \qty{100e6}{\hertz}$

So könnte eine schrittweise Berechnung mit diesen Werten aussehen, wenn wir der Einfachheit halber für $2\pi$ den Wert $\num{6,28}$ einsetzen:

$\begin{split} 6,28 \cdot 10 \cdot 100 &= 6280 \\ 10^{-12} \cdot 10^6 &= 10^{-6} \\ \num{6280} \cdot 10^{-6} &= \num{0,00628} \\ 1/\num{0,00628} &= \num{159} \end{split}$

Bei den folgenden Fragen verwenden wir die gleiche Formel und ändern nur die eingesetzten Werte.
[question:AC105]

[question:AC106]

[question:AC107]

[question:AC108]
Bei der Frage AC108 muss die Kapazität aus dem kapazitiven Blindwiderstand $X_C$ und der Frequenz berechnet werden:
* Zuerst wird $X_C$ berechnet:
  $X_C = \frac{U}{I} = \frac{\qty{16}{\volt}}{\qty{32}{\milli\ampere}} = \qty{500}{\ohm}$
* Danach wird die Formel für $C$ angewendet:
  $C = \frac{1}{2\pi \cdot f \cdot X_C} = \frac{1}{6,28 \cdot \qty{50}{\hertz} \cdot \qty{500}{\ohm}} \approx 6,37\cdot \qty{10^{-6}}{\farad} = \qty{6,37}{\micro\farad}$
* Im Ergebnis taucht die Zehnerpotenz $10^{-6}$ auf, die in eine Vorsilbe umgewandelt werden muss.

*Kondensatorverluste*

Die vielfältigen Kondensatorarten unterscheiden sich auch hinsichtlich ihrer unerwünschten Verluste bei der Belastung durch Hochfrequenzströme. Die technische Beurteilung geschieht über den Begriff der Güte $Q$ (Quality) und dem sogenannten "Tangens delta" (kurz $\tan\delta$).

Merke: Hohe Verluste ergeben eine niedrige Güte und damit ein großes $\tan\delta$.

---
[photo:259:a_tan_delta:$\tan\delta$ verschiedener Kondensatorarten]

Wenn man die $\tan\delta$ Kurven der Kondensatoren in Abbildung [ref:a_tan_delta] betrachtet, sieht man, dass Glimmerkondensatoren die kleinsten $\tan\delta$-Werte besitzen und damit die höchste Güte und die niedrigsten Verluste aufweisen.
%todo TAN Delta Kurven neu zeichnen ???

[question:AC109]

[question:AC110]

<indepth>
Erklärung des $\tan\delta$ mit Hilfe eines Zeigerdiagramms:

[photo:261:a_tan_delta_Zeigerdiagramm:Veranschaulichung des $\tan\delta$ an Hand des Zeigerdiagramms für einen verlustbehafteten Kondensator.]

In Datenblättern wird statt des $\tan\delta$ manchmal auch der serielle Verlustwiderstand (engl. Equivalent Series Resistance, ESR) des Kondensators bei einer bestimmten Betriebsfrequenz angegeben.

[photo:260:a_Kondensator_Ersatzschaltbild:Ersatzschaltbild eines realen Kondensators mit einem seriellen Verlustwiderstand (ESR).]

In linear geregelten Netzteilen und in Schaltnetzteilen müssen Elektrolytkondensatoren mit sehr niedrigem ESR verwendet werden.
</indepth>
<margin>
| l:Zusammenfassung Kondensator 2 | l: |
| *MERKE: Kondensatooor, Strom eilt vooor!* | |
| Formelsammlung: Kapazitiver Blindwiderstand| $X_C = \frac{1}{\omega \cdot C} = \frac{1}{2\pi \cdot f \cdot C}$|
| Umgestellt nach C: | $C =\frac{1}{{2\pi \cdot f \cdot X_C}}$|
| Hohe Kondensatorverluste bewirken: | niedrige Güte; großer $\tan\delta$; großer ESR|
[table:a_Kondensator_2_Zusammenfassung:Zusammenfassung kapazitiver Blindwiderstand und Güte]
</margin>

