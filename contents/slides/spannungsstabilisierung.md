* Eingangsspannung kann variieren
* Beispielsweise bei durch Akku betriebenen Geräten
* Empfindliche Baugruppen (z.B. Oszillatoren) würden die Frequenz ändern
* Abhilfe: Spannungsstabilisierung

---
## Stabilisierung mit Z-Diode
<left>
[picture:323:a_Stabilisierung mit Z-Diode:Spannungsstabilisierung mit Z-Diode]
</left>
<right>
* Sehr einfache Schaltung
* Kann die Ausgangsspannung in Grenzen stabil halten
</right>
<note>
</note>
---
[question:AD321]
--- style="font-size: 0.7em;"
#### Lösungsweg
* gegeben: $R_L = \qty{470}{\ohm}$
* gegeben: $I_L = \qty{10}{\milli\ampere}$
* gegeben: $I_Z = \qty{15}{\milli\ampere}$
* gegeben: $U_{IN} = \qty{13,8}{\volt}$
* gesucht: $\eta = \frac{P_L}{P_{IN}}$

<fragment>
$P_L = I_L^2 \cdot R_L = (\qty{10}{\milli\ampere})^2 \cdot \qty{470}{\ohm} = \qty{47}{\milli\watt}$
</fragment>
<fragment>
$P_{IN} = U_{IN} \cdot I_{IN} = U_{IN} \cdot (I_Z + I_L) = \qty{13,8}{\volt} \cdot (\qty{15}{\milli\ampere} + \qty{10}{\milli\ampere}) = \qty{345}{\milli\watt}$
</fragment>
<fragment>
$\eta = \frac{P_L}{P_{IN}} = \frac{\qty{47}{\milli\watt}}{\qty{345}{\milli\watt}} \approx \num{0,14}$
</fragment>
---
## Linarer Spannungsregler

<left>
[picture:985:a_spannungsregler_linear:Schaltbild eines linearen Spannungsreglers]
</left>
<right>
* Leistungstransistor wird als veränderlicher Widerstand betrieben
* Bildet zusammen mit dem Lastwiderstand einen Spannungsteiler
* Wirkungsgrad ist oft sehr niedrig
</right>

---
[question:AD315]
---
[question:AD319]
---
#### Lösungsweg
* gegeben: $U_{zu} = \qty{13,8}{\volt}$
* gegeben: $U_{ab} = \qty{9}{\volt}$
* gegeben: $I = \qty{900}{\milli\ampere}$
* gesucht: $P_V$

<fragment>
$U_{IC1} = U_{zu} - U_{ab} = \qty{13,8}{\volt} - \qty{9}{\volt} = \qty{4,8}{\volt}$
</fragment>
<fragment>
$P_V = U_{IC1} \cdot I = \qty{4,8}{\volt} \cdot \qty{900}{\milli\ampere} = \qty{4,32}{\watt}$
</fragment>
---
[question:AD320]
---
#### Lösungsweg
* gegeben: $U_{zu} = \qty{13,8}{\volt}$
* gegeben: $U_{ab} = \qty{5}{\volt}$
* gegeben: $I_{zu} = \qty{455}{\milli\ampere}$
* gegeben: $I_{ab} = \qty{450}{\milli\ampere}$
* gesucht: $\eta$

<fragment>
$\eta = \frac{P_{ab}}{P_{zu}} = \frac{U_{ab} \cdot I_{ab}}{U_{zu} \cdot I_{zu}} = \frac{\qty{5}{\volt} \cdot \qty{450}{\milli\ampere}}{\qty{13,8}{\volt} \cdot \qty{455}{\milli\ampere}} \approx \num{0,36}$
</fragment>
---
## Festspannungsregler
<left>
[picture:200:a_Festspannungsregler:Festspannungsregler]
</left>
<right>
* Ausgelegt als IC
* Arbeiten wie linare Spannungsregler mit sehr genauer Spannungsreferenzquelle und optimaler elektronischer Regelung
* Auch bei starker Schwankung auf der Eingangsseite ist die Ausgangsseite sehr stabil
</right>

---
[question:AD317]
---
[question:AD316]
---
[question:AD318]
---
#### Lösungsweg
* gegeben: $U_{zu} = \qty{13,8}{\volt}$
* gegeben: $U_{ab} = \qty{5}{\volt}$
* gegeben: $R_L = \qty{10}{\ohm}$
* gesucht: $P_V$

<fragment>
$I = \frac{U_{zu}}{R_L} = \frac{\qty{5}{\volt}}{\qty{10}{\ohm}} = \qty{500}{\milli\ampere}$
</fragment>
<fragment>
$U_{IC1} = U_{zu} - U_{ab} = \qty{13,8}{\volt} - \qty{5}{\volt} = \qty{8,8}{\volt}$
</fragment>
<fragment>
$P_V = U_{IC1} \cdot I = \qty{8,8}{\volt} \cdot \qty{500}{\milli\ampere} = \qty{4,4}{\watt}$
</fragment>
