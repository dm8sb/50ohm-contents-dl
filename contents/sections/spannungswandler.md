% todo Bild von Spannungswandlervarianten
Einen Spannungswandler benötigen wir immer dann, wenn wir eine Spannung umwandeln müssen. In unserem Hobby kann das z.B. eine $\qty{5}{\volt}$ Spannung für einen Microcontroller aus $\qty{13,8}{\volt}$ sein oder aus einer Batterie mit $\qty{12}{\volt}$ eine Versorgungsspannung für einen Laptop mit $\qty{19}{\volt}$ zu generieren. Hierbei sprechen wir von DC/DC Wandlern als Step-UP (Hochsetzsteller) oder Step-DOWN (Tiefsetzsteller).
Durch die Spannungswandlung entstehen auch Verluste. Das Verhältnis der abgegebenen Leistung zur zugeführten Leistung nennt man Wirkungsgrad. Dieser berechnet sich aus $\eta=\frac{{P}_{AB}}{{P}_{ZU}}$.

Ein Spannungswandler setzt ${U}_{IN} = \qty{12}{\volt}$ auf $U_{OUT} = \qty{5}{\volt}$ um. Er nimmt ${I}_{IN} = \qty{2}{\ampere}$ auf und gibt ${I}_{OUT} = \qty{3}{\ampere}$ ab. Wie groß ist sein Wirkungsgrad? Dazu benötigen wir die Leistungen ${P}_{ZU}$ und ${P}_{AB}$. Diese berechnen sich wie bereits gelernt mit $P = U \cdot I$.
In unserem Beispiel also wie folgt:  
${P}_{ZU} = {U}_{IN} \cdot {I}_{IN} = \qty{12}{\volt} \cdot \qty{2}{\ampere} = \qty{24}{\watt}$
${P}_{AB} = {U}_{OUT} \cdot {I}_{OUT} = \qty{5}{\volt} \cdot \qty{3}{\ampere} = \qty{15}{\watt}$

somit ergibt sich:
$\eta = \frac{{P}_{AB}}{{P}_{ZU}} = \frac{\qty{15}{\watt}}{\qty{24}{\watt}} = \num{0,625}$
Um nun $\eta$ in $\%$ anzugeben, wird $\eta \cdot \qty{100}{\percent}$ genommen und somit ist der Wirkunggrad $\eta = \qty{62,5}{\percent}$

[question:AB213]
[question:AB214]
<indepth>
[photo:299:StepUpDownWandler: Abwärts- (Buck) Aufwärts- (Boost) Wandler]
Dieser Buck-Boost Converter kann von $\qty{0,5}{\volt}$ bis $\qty{25}{\volt}$ am Ausgang eingestellt werden. Die maximale Leistung beträgt $\qty{25}{\watt}$. Da der Wirkungsgrad sehr hoch ist, kommen die Schalttransistoren ohne Kühlkörper aus.  Die Betriebsart Abwärtswandler (Step Down = Buck Mode) oder Aufwärtswandler (Step Up = Boost Mode) kann mit dem rechten Minischalter aktiviert werden.
[photo:300:StepUpWandler: Aufwärtsspannungswandler von $\qty{7,2}{\volt}$ auf $\qty{24}{\volt}$]
</indepth>
  
<margin>
  Lösungshilfe
  AB 214: $\qty{80}{\percent}$
</margin>
