Kondensatoren werden in vielen Anwendungen in Reihenschaltung, Parallelschaltung oder auch gemischter Schaltungstechnik eingesetzt. Die Parallelschaltung ist einfacher zu verstehen, deshalb betrachen wir sie zuerst.

Durch die Paralelschaltung stehen sich mehr Platten gegenüber und somit erhöht sich die Plattenoberfläche proportional. Entsprechend erhöht sich auch die Kapazität in der Gesamtschaltung.

<margin>
[picture:822:e_3C-parallel: Parallelschaltung von 3 Kondensatoren]
</margin>

---

Bei einer Parallelschaltung von gleich großen Kondensatoren verdoppelt sich die Kapazität, die Spannungsfestigkeit bleibt gleich. Selbstverständlich kann man die Gesamtkapazität berechnen. Die Formel finden wir in der Formelsammlung:

$C_{G} = C_{1} + C_{2} + C_{3} + \dots$

<tip>
Die Gesamtkapazität ist bei der Parallelschaltung immer größer als die kleinste Einzelkapazität.
</tip>

Bei der folgenden Aufgabe ist eine zusätzliche Schwierigkeit zu finden, da die Vorsilben der Kapazitätswerte unterschiedlich sind. Man muss zuerst alle Werte auf eine gemeinsame Vorsilbe umwandeln. Die Zahlen sollen  nicht zu groß und nicht zu klein werden, deshalb empfiehlt es sich, die Vorsilbe nano ($\unit{\nano}$) zu wählen. 

$\qty{0,1}{\mu\farad} = \qty{100}{\nano\farad}$

$\qty{50 000}{\pico\farad} = \qty{50}{\nano\farad}$

Jetzt muss man nur noch alle Werte Addieren in $\unit{\nano\farad}$ addieren.

[question:ED117]

<margin>
[photo:262:a_Netzteil BEKO PA 7 x 10000µF parallel: Parallelschaltung von 7 x 10 000 µF in einem Endstufennetzteil] 
</margin>

Als Verständnistest kann die nächste Aufgabe verwendet werden.

[question:ED118]


---

Bei einer Reihenschaltung von Kondensatoren, wie in Abbildung [ref:e_3C-parallel] gezeigt, erhöht sich die Spannungsfestigkeit, allerdings verringert sich die Kapazität. Selbstverständlich kann man wieder die Gesamtkapazität berechnen. Diese ist sehr ähnlich zur Parallelschaltung von Widerstanden:

$\frac{1}{C_{G}} = \frac{1}{C_{1}} + \frac{1}{C_{2}} + \frac{1}{C_{3}}$

<margin>
[picture:823:e_3C-parallel:Reihenschaltung von 3 Kondensatoren] 
</margin>

<tip>
Die Gesamtkapazität ist bei der Reihenschaltung immer kleiner als die kleinste Einzelkapazität.
</tip>

<tip>
Bei der Lösung der Aufgaben empiehlt sich folgende Vorgehensweise:
  
1. Skizziere die Schaltung
2. Schreibe die Kapazitätswerte zu den Bauteilen.
3. Wandle in gleiche Vorsilben um.
4. Vereinfache die Schaltung durch Zusammenführung von gleichartigen Schaltungsgruppen
5. Berechne schrittweise die Gesamtkapazität
</tip>

Wenn alle Kondensatoren gleiche Kapazitätswerte haben, dann kann man die Gesamtkapazität leicht berechnen, indem eine Einzelkapazität durch 3 dividiert wird. In der folgenden Aufgabe rechnet man $\qty{0,33}{\mu\farad} / 3 = \qty{0,11}{\mu\farad}$.

[question:ED119]

Bei der Reihenschaltung von Kondensatoren in der folgenden Aufgabe findet man $\unit{\mu\farad}$ und $\unit{\nano\farad}$ als Vorsilbe. Es ist sehr sinnvoll, $\qty{200000}{\nano\farad}$ zuerst in $\qty{200}{\mu\farad}$ umzuwandeln. Bei einer Reihenschaltung kann man nun die Formel aus der Formelsammlung anwenden.


$C_{G} = \frac{1}{\frac{1}{100 \  µF} + \frac{1}{50\  µF} + \frac{1}{100\  µF}}$

[question:ED120]

---
  
Bei der nächsten Frage werden 3 Kondensatoren in Reihen- und Parallelschaltung kombiniert. 

[question:ED121]

Welcher Schaltungsteil kann zuerst vereinfacht werden? Richtig: die Reihenschaltung.
Diese Teilgruppe hat als Gesamtkapazität die Hälfte von $\qty{10}{\nano\farad}$, also $\qty{5}{\nano\farad}$. Jetzt ist es einfacher weiterzurechnen, da bei einer Parallelschaltung die Kapazitätswerte addiert werden. Gratulation zum Ergebnis von $\qty{10}{\nano\farad}$.

Die weiteren Aufgaben ähnlich und leicht lösbar.

[question:ED122]
[question:ED123]
[question:ED124]

%<margin>
%
%Lösungshilfen:
%
%*ED 118:* Reihenschaltung von 22 nF, 0,033 µF = 33 nF und 15 000 pF = 15 nF.
%$\frac{1}{C_G} = \frac{1}{22} + \frac{1}{33} + \frac{1}{15}$
%Eigentlich muss man nicht rechnen, denn es gibt nur ein Ergebnis, das kleiner als 15 nF ist.
%*ED 120:* 50 µF 
%*ED 122:* $C_2$ = 1 µF und $C_3$ = 1 µF in Parallelschaltung ergibt zusammen 2 µF. Dazu $C_1$ = 2 µF in Reihe %ergibt die Hälfte , also 1 µF.
% 
%*ED 123:* $C_2$ = 4 nF und $C_3$ = 4 nF in Parallelschaltung ergibt zusammen 8 nF. Dazu $C_1$ = 8 nF in Reihe %ergibt die Hälfte , also 4 nF.
%  
%*ED 124:* $C_2$ = 100 nF und $C_3$ = 100 000 pF = 100 nF in Parallelschaltung ergibt zusammen 200 nF. Dazu %$C_1$ = 200 nF in Reihe ergibt die Hälfte , also 100 nF.
%</margin>