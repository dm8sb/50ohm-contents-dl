### Spannungsquelle
<left>
[picture:1018:a_vsource_schematic:Ersatzschaltbild Spannungsquelle]
</left>
<right>
* Reale Spannungsquelle wird mit $R_L$ belastet &rarr; Klemmenspannung $U_k$ sinkt
* Grund ist der Innenwiderstand
* Ohne Belastung / im Leerlauf: $U_q = U_L$
</right>
<note>
</note>

---
### Innenwiderstand

<left>
* Nicht messbar mit einem Multimeter
* Rechnerisch ermitteln: <br/>$R_i = \frac{\Delta U}{\Delta I}$
</left>
<right>
* Leerlauf: $I = \qty{0}{\ampere}$
* Belastung mit $R_L$: <br/>$I_L = \frac{U_L}{R_L}$
</right>

---
### Innenwiderstand Spannungsquelle

$(\Delta U = \qty{0}{\volt})$;  $R_i = \frac{\Delta U}{\Delta I} = \frac{0}{x} = \qty{0}{\ohm}$

<fragment>
Ideale Spannungsquellen sollen einen sehr niedrigen Innenwiderstand $R_i \ll R_L$ aufweisen, im Idealfall: 0 Ohm, dann bleibt die Ausgangsspannung bei Belastung unverändert.
</fragment>

---

### Strombegrenzung

* In Labornetzteilen eingebaut
* Laststrom übersteigt eine maximale Stromstärke
* &rarr; Klemmenspannung wird abgesenkt
* &rarr; Laststrom bleibt konstant
* Funktion der Konstantstromquelle

---
### Innenwiderstand Stromquelle

$R_i = \frac{\Delta U}{\Delta I}$; $(\Delta I = "\textrm{Null}" A)$;  $R_i = \frac{\Delta U}{"\textrm{Null}"} = "\textrm{unendlich}"\ \Omega$

<fragment>
Ideale Stromquellen sollen einen sehr hohen Innenwiderstand $R_i \gg R_L$ aufweisen. Idealfall: "unendlich" Ohm, dann bleibt der Laststrom bei Änderung des  Lastwiderstandes konstant, deshalb spricht man auch von Stromanpassung.
</fragment>

---
[question:AB201]
---
### Leistungsanpassung

* Optimale Leistungsabgabe von Sender zu Antenne
* $R_i = R_L$

--- style="font-size: 0.7em;"

|c: Zusammenfassung Innenwiderstand | c: Innenwiderstand |
| Spannungsanpassung bei einer Konstantspannungsquelle| $R_i$ =  "sehr niederhohmig" ; theoretisch $\qty{0}{\ohm}$; $R_i \ll R_L$ identisch mit $R_L \gg R_i$| 
|Stromanpassung bei einer Konstantstromquelle|$R_i$ =  "sehr hochohmig" ;  $R_i \gg R_L$ identisch mit $R_L \ll R_i$ |
| Leistungsanpassung bei Verstärkern| $R_L = R_i$|
[table:a_Innenwiderstand Zusammenfassung:Zusammenfassung zum Innenwiderstand]

---
[question:AG401]
---
[question:AB202]
---
[question:AB203]
---
[question:AB204]
---
[question:AB207]
---
#### Lösungsweg
* gegeben: $U_0 = \qty{13,5}{\volt}$
* gegeben: $U_{Kl} = \qty{13}{\volt}$
* gegeben: $I = \qty{2}{\ampere}$
* gesucht: $R_i$

<fragment>
$R_i = \frac{U_i}{I} = \frac{U_0-U_{Kl}}{I} = \frac{\qty{13,5}{\volt} - \qty{13}{\volt}}{\qty{2}{\ampere}} = \qty{0,25}{\ohm}$
</fragment>
---
[question:AB208]
---
#### Lösungsweg
* gegeben: $U_0 = \qty{13,8}{\volt}$
* gegeben: $U_{Kl} = \qty{13,6}{\volt}$
* gegeben: $I = \qty{20}{\ampere}$
* gesucht: $R_i$

<fragment>
$R_i = \frac{U_i}{I} = \frac{U_0-U_{Kl}}{I} = \frac{\qty{13,8}{\volt} - \qty{13,6}{\volt}}{\qty{20}{\ampere}} = \qty{10}{\milli\ohm}$
</fragment>
---
[question:AB206]
---
#### Lösungsweg
* gegeben: $U_0 = \qty{13,5}{\volt}$
* gegeben: $U_{Kl} = \qty{12,4}{\volt}$
* gegeben: $I = \qty{0,9}{\ampere}$
* gesucht: $R_i$

<fragment>
$R_i = \frac{U_i}{I} = \frac{U_0-U_{Kl}}{I} = \frac{\qty{13,5}{\volt} - \qty{12,4}{\volt}}{\qty{0,9}{\ampere}} = \qty{1,22}{\ohm}$
</fragment>
---
[question:AB205]
---
#### Lösungsweg
* gegeben: $U_0 = \qty{5,0}{\volt}$
* gegeben: $U_{Kl} = \qty{4,8}{\volt}$
* gegeben: $R_L = \qty{1,2}{\ohm}$
* gesucht: $R_i$

<fragment>
$I = \frac{U_{Kl}}{R_L} = \frac{\qty{4,8}{\volt}}{\qty{1,2}{\ohm}} = \qty{4}{\ampere}$
</fragment>
<fragment>
$R_i = \frac{U_i}{I} = \frac{U_0 - U_{Kl}}{I} = \frac{\qty{5,0}{\volt} - \qty{4,8}{\volt}}{\qty{4}{\ampere}} = \qty{0,05}{\ohm}$
</fragment>

