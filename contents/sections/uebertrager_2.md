% todo Hinweis: Es gibt nur eine einzige Frage zur Stromdichte.
Da alle stromführenden Leitungen nicht zu warm werden dürfen, damit die Isolation nicht schmilzt oder der Leiter gar zu glühen anfängt, darf eine maximale Stromstärke bezogen auf den Leiterquerschnitt nicht überschritten werden.
Bildet man das Verhältnis von Stromstärke bezogen auf den Leiterquerschnitt in $\unit{\milli\meter\squared}$, dann erhält man einen Wert für die Stromdichte $S$.
Die Berechnungsformel lautet (siehe Formelsammlung -  Stichwort: Belastbarkeit von Wicklungen):
Stromdichte $S = \frac{I}{A} $ in  $\unit{\ampere\per\milli\meter\squared}$

Nach VDE ist für frei verlegte Leiter aus Kupfer die maximal zulässige Stromstärke mit $\qty{12}{\ampere}$ bei einer Querschnittsfläche von $\qty{0,75}{\milli\meter\squared}$ festgelegt.
Bei Schmelzsicherungen kann die Stromdichte bis zu $\qty{3000}{\ampere\per\milli\meter\squared}$ erreichen.

Bei Transformatoren muss eine maximale Stromdichte von ca. $\qty{2,5}{\ampere\per\milli\meter\squared}$  eingehalten werden, da die Wicklungen die Wärme nicht optimal abstrahlen können.

Zur Berechnung der Stromdichte ist aus dem Drahtdurchmesser die Querschnittsfläche in $\unit{\milli\meter\squared}$ zu ermitteln.
Querschnittsfläche (siehe Formelsammlung -  Stichwort: Widerstand von Drähten) $A = d^2 \cdot \frac{\pi}{4}$

Querschnittsfläche des Drahtes: $A = (\qty{0,5}{\milli\meter})^2 \cdot \frac{3,14}{4} = \qty{0,2}{\milli\meter\squared}$
Die Aufgabe kann nur mit der nach $I$ umgestellten Formel berechnet werden:
Strom $I = S \cdot A = \qty{2,5}{\ampere\per\milli\meter\squared} \cdot \qty{0,2}{\milli\meter\squared} = \qty{0,5}{\ampere}$
[question:AC307]

% todo Der Begriff Gegeninduktion sollte in das Kapitel Trafo 1 verschoben werden.
Das Trafo-Prinzip beruht auf einem besonderen physikalischen Effekt.
Wenn sich ein Magnetfeld in einer Spule ändert, und dies geschieht beim Anlegen einer Wechselspannung, dann wird in einer magnetisch gekoppelten Spule eine elektrische Spannung induziert, die der Ursache entgegengesetzt gerichtet ist. Deshalb spricht man von Gegeninduktion. Auch bei jedem Motor gibt es diesen Effekt, deshalb benötigt man eine Kraft, um den Motor zu drehen. Wäre es keine Gegeninduktion, dann hätten wir ein Perpetuum Mobile, der Motor wird ein Mal angestoßen und läuft dann ohne Kraftzuführung weiter.

*Anpassungsübertrager*

Transformatoren werden in der Hochfrequenztechnik auch als Anpassungsübertrager eingesetzt.
Dabei besteht der Transformatorkern nicht aus Eisen sondern aus gepresstem Eisen- oder Ferritpulver.
% todo Bild: Ferrit Ringkernübertrager mit Typenbezeichnung und Farbmarkierung
% todo Bild: Eisenpulver Ringkernübertrager mit Typenbezeichnung und Farbmarkierung
Ein Anpassungsübertrager hat die Aufgabe, eine Impedanz an eine andere anzupassen.
Als Beispiel betrachten wir eine endgespeiste Antenne, deren Eingangsimpedanz ca. $\qty{2450}{\ohm}$ beträgt.
Sie soll an einen Sender für $\qty{50}{\ohm}$ Lastimpedanz angepasst werden.

Die Berechnung der Impedanzübertragung lässt sich aus den TRAFO-Grundformeln ermitteln.
Die Formel für die Impedanzübertragung lautet:
$\frac {Z_p}{Z_s} = ü^2 = \left(\frac{N_p}{N_s}\right)^2 = \left(\frac{U_p}{U_s}\right)^2$
Merke: Das Impedanzverhältnis ist das Quadrat des Spannungsverhältnisses und damit auch das Quadrat des Windungszahlenverhältnisses.

Auflösen nach $ü$ ergibt $ü = \sqrt{\frac{Z_p}{Z_s}} = \frac{N_p}{N_s} = \frac{U_p}{U_s} = \frac{I_s}{I_p}$

% todo Bild: Anpassungsübertrager mit Lastimpedanz Z2

<indepth>
 Ableitung der Formel zur Impedanzübertragung:
 $ P_p = P_s$
  $U_p \cdot I_p = U_s \cdot I_s$
  Für $U$ das Ohmsche Gestz einsetzen: $U = I \cdot R$;
  $R$ wird durch $Z$ ersetzt
$(I_p \cdot Z_p) \cdot I_p = (I_s \cdot Z_s) \cdot I_s$
 Das Impedanzverhältnis auf einer Seite bilden:
 $ \frac{Z_p}{Z_s} = \frac{{I_s}^2}{{I_p}^2} = ü^2$
  Alternativ für $I$ das Ohmsche Gesetz einsetzen:
  $I = \frac{U}{R}$
  $R$ wird durch $Z$ ersetzt
$ \frac{U_p}{Z_p} \cdot U_p  = \frac{U_s}{Z_s} \cdot U_s$
 Das Impedanzverhältnis auf einer Seite bilden:
 $ \frac{Z_p}{Z_s} = \frac{{U_p}^2}{{U_s}^2} = ü^2$
</indepth>
Für die Impedanzübertragung von $\qty{50}{\ohm}$ auf $\qty{2450}{\ohm}$ ist das Verhältnis $Z_p:Z_s = \qty{50}{\ohm}:\qty{2450}{\ohm} = 1:49$. Das bedeutet $ü^2 =49$ und damit $ü=\sqrt{49}=7$.
% todo BILD: UNUN mit EndFED
%ToDo: Beispielrechnung Q1038:

[question:AC301]
[question:AC302]
[question:AC303]
[question:AC304]
[question:AC305]
[question:AC306]

<margin>
*Zusammenfassung*:

Formelsammlung - Stichwort Widerstand von Drähten

Querschnittsfläche $A = d^2 \cdot \frac{\pi}{4}$

Formelsammlung - Stichwort Transformator/ Übertrager

Stromdichte $S = \frac{I}{A}$

$\frac{Z_p}{Z_s} = ü^2 = \left(\frac{N_p}{N_s}\right)^2 = \left(\frac{U_p}{U_s}\right)^2$
$ü = \sqrt{\frac{Z_p}{Z_s}} = \frac{N_p}{N_s} = \frac{U_p}{U_s} = \frac{I_s}{I_p}$
</margin>
