<left>
[photo:299:StepUpDownWandler: Abwärts- (Buck) Aufwärts- (Boost) Wandler]
</left>
<right>
* Wandelt Gleichspannungen um &rarr; DC/DC-Wandler
* z.B. von $\qty{13,8}{\volt}$ auf $\qty{5}{\volt}$ &rarr; Step-DOWN (Tiefsetzsteller)
* z.B. von $\qty{12}{\volt}$ auf $\qty{19}{\volt}$ &rarr; Step-UP (Hochsetzsteller)
</right>
<note>
Der Buck-Boost Converter im Bild kann von $\qty{0,5}{\volt}$ bis $\qty{25}{\volt}$ am Ausgang eingestellt werden. Die maximale Leistung beträgt $\qty{25}{\watt}$.
</note>
---
### Wirkungsgrad

* Es entstehen Verluste durch die Bauteile in der Schaltung
* Wirkungsgrad $\eta$, meistens in $\%$ angegeben

<fragment>
$\eta = \frac{P_{\textrm{AB}}}{P_{\textrm{ZU}}}$
</fragment>

---
[question:AB213]
---
#### Lösungsweg
* gegeben: $U_{\textrm{zu}} = \qty{12}{\volt}$
* gegeben: $U_{\textrm{ab}} = \qty{5}{\volt}$
* gegeben: $I_{\textrm{zu}} = \qty{2}{\ampere}$
* gegeben: $I_{\textrm{ab}} = \qty{3}{\ampere}$
* gesucht: $\eta$

<fragment>
$\begin{split} \eta &= \frac{P_{\textrm{ab}}}{P_{\textrm{zu}}} = \frac{U_{\textrm{ab}} \cdot I_{\textrm{ab}}}{U_{\textrm{zu}} \cdot I_{\textrm{zu}}}\\ &= \frac{\qty{5}{\volt} \cdot \qty{3}{\ampere}}{\qty{12}{\volt} \cdot \qty{2}{\ampere}} = \frac{\qty{15}{\watt}}{\qty{24}{\watt}} = \num{0,625} = \qty{62,5}{\percent} \end{split}$
</fragment>
---
[question:AB214]
---
* gegeben: $U_{\mathrm{zu}} = \qty{5}{\volt}$
* gegeben: $U_{\mathrm{ab}} = \qty{12}{\volt}$
* gegeben: $I_{\mathrm{zu}} = \qty{3}{\ampere}$
* gegeben: $I_{\mathrm{ab}} = \qty{1}{\ampere}$
* gesucht: $\eta$

<fragment>
$\begin{split} \eta &= \frac{P_{\textrm{ab}}}{P_{\textrm{zu}}} = \frac{U_{\textrm{ab}} \cdot I_{\textrm{ab}}}{U_{\textrm{zu}} \cdot I_{\textrm{zu}}}\\ &= \frac{\qty{12}{\volt} \cdot \qty{1}{\ampere}}{\qty{5}{\volt} \cdot \qty{3}{\ampere}} = \frac{\qty{12}{\watt}}{\qty{15}{\watt}} = \num{0,8} = \qty{80}{\percent} \end{split}$
</fragment>
