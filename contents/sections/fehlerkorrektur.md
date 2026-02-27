Erkennt der Empfänger einen Fehler, zum Beispiel durch Prüfbits, kann er den Sender um eine erneute Übertragung der Daten bitten, um den Fehler zu korrigieren. Bei der Vorwärtsfehlerkorrektur hingegen ist oft keine Neuübertragung nötig. Dazu wird weitere Redundanz zu den Daten hinzugefügt, z. B. mehrere Prüfbits. So wird nicht nur erkannt, dass ein Fehler vorliegt, sondern auch wo. Das Verfahren kann den Fehler somit korrigieren, indem es das als fehlerhaft erkannte Bit berichtigt. Wie das im Detail funktioniert, kannst du im Bonus-Kasten nachlesen. Es ist aber nicht prüfungsrelevant. Im Englischen wird von Forward Error Correction (FEC) gesprochen.

[question:AE413]
[question:AE414]

<indepth>

Der Hamming-Code ist ein Fehlerkorrekturverfahren, das mehrere Parity Bits verwendet. Nehmen wir an, wir wollen die folgenden 11 Bits übertragen:

[picture:683:hamming1: ]

Das Ziel soll es sein, dass ein Bitfehler nicht nur erkannt, sondern auch korrigiert werden kann. Dazu ist es hilfreich, wenn wir uns die Positionen der einzelnen Bits mal genauer anschauen. Dazu benennen wir die Positionen alphabetisch:

[picture:682:hamming2: ]

Nun ordnen wir die Bits etwas anders an und fügen noch einige zusätzliche Bits hinzu:

[picture:684:hamming3: ]

Anstatt eines einzelnen Prüfbits verwenden wir jetzt vier ($p_1$-$p_4$), die verschiedene Bereiche unserer Datenbits, ähnlich einem Kreuzworträtsel, abdecken:

[picture:685:hamming4: ]

Jedes Prüfbit sichert einen gewissen Bereich ab:

[picture:686:hamming5: ]

Schauen wir uns wieder das Ganze mit unseren Daten an. Für jeden Bereich berechnen wir das Prüfbit mit Even Parity:

[picture:687:hamming6: ]

Tritt bei der Übertragung ein Fehler auf, kann dieser durch die Kombination der verschiedenen Bereiche der Fehler lokalisiert und korrigiert werden. 

Wird zum Beispiel das Bit $k$ durch die Übertragung zu einer $\num{0}$, so werden alle Paritätsprüfungen fehlschlagen. Der Fehler muss also bei Bit $k$ liegen.
  
%TODO Wird das Bit ......... TODO
</indepth>
