Im Rahmen der digitalen Signalverarbeitung beschreibt das *Mapping* den Schritt, bei dem digitale Daten in spezifische Signalpunkte (Symbole) umgewandelt werden, die über das Übertragungssystem gesendet werden können. Dies ist ein entscheidender Prozess in der Modulation, insbesondere bei Quadraturamplitudenmodulationen (QAM) und Phasenumtastungen wie QPSK (Quadrature Phase Shift Keying).

Beispiel für schrittweises Mapping bei QPSK

1. *Binäre Daten in Symbole umwandeln*:

Bei QPSK werden jeweils zwei Bits zu einem Symbol zusammengefasst. Da wir zwei Bits pro Symbol haben, ergeben sich vier mögliche Kombinationen ($\num{00}$, $\num{01}$, $\num{10}$, $\num{11}$). Jede dieser Kombinationen wird einem spezifischen Signalpunkt zugeordnet, der durch eine bestimmte Phase repräsentiert wird.

2. *Phasenvergabe*:

Bei QPSK hat jedes Symbol eine eigene Phase. Die Phasen werden typischerweise in $\qty{90}{\degree}$-Schritten definiert:

- $\num{00}$ entspricht ($\qty{0}{\degree}$)
- $\num{01}$ entspricht ($\qty{90}{\degree}$)
- $\num{10}$ entspricht ($\qty{180}{\degree}$)
- $\num{11}$ entspricht ($\qty{270}{\degree}$)

3. *Mapping auf das Konstellationsdiagramm*:

% TODO Bessere Darstellung für das Beispiel mit QPSK
[picture:697:a_8qam:I-Q-Diagramm für ein 8QAM-Mapping]
Die Darstellung ist für ein 8QAM-Mapping. QPSK im Beispiel entspricht dem äußeren Kreis.

Ein *Konstellationsdiagramm* ist eine grafische Darstellung der möglichen Symbole in einem quadratischen Diagramm, wobei die X-Achse (In-Phase) und die Y-Achse (Quadratur-Phase) die Amplitude der Signalbestandteile darstellen. Bei QPSK befinden sich die vier Signalpunkte an den Enden eines Quadrats im Diagramm:

- Signalpunkt für $\num{00}$: auf der positiven X-Achse ($\qty{0}{\degree}$)
- Signalpunkt für $\num{01}$: auf der positiven Y-Achse ($\qty{90}{\degree}$)
- Signalpunkt für $\num{10}$: auf der negativen X-Achse ($\qty{180}{\degree}$)
- Signalpunkt für $\num{11}$: auf der negativen Y-Achse ($\qty{270}{\degree}$)

Jeder dieser Punkte repräsentiert ein Symbol, und der Empfänger kann anhand der Phasenlage bestimmen, welche Bitkombination gesendet wurde.

Beispielhafte Darstellung im Konstellationsdiagramm bei QPSK

Die vier Punkte im Konstellationsdiagramm bei QPSK lassen sich einfach darstellen:

- *$\num{00}$* bei $\qty{0}{\degree}$: Repräsentiert einen Punkt auf der positiven X-Achse.
- *$\num{01}$* bei $\qty{90}{\degree}$: Ein Punkt auf der positiven Y-Achse.
- *$\num{10}$* bei $\qty{180}{\degree}$: Ein Punkt auf der negativen X-Achse.
- *$\num{11}$* bei $\qty{270}{\degree}$: Ein Punkt auf der negativen Y-Achse.

%TODO: Bild zum Mapping am Beispiel von QPSK einfügen und die Punkte im Diagramm im Bezug zum Text setzen.

Das Konstellationsdiagramm bei QPSK hat also vier Signalpunkte im rechten Winkel zueinander, was die vier Phasen darstellt, die für die Übertragung verwendet werden. Die klare Trennung der Phasen hilft, die Symbole auch bei Rauschen gut auseinanderzuhalten.