# datasets

## hkbuildings.csv
#### Description
The five hundred tallest buildings in Hong Kong as of November 2019.
#### Usage
Illustrating that the heights of buildings follow a power law.

## memphis.csv
#### Description
The discography of the Memphis Jug Band, taken from a British Magazine, Blues-Link No.2, Oct/Nov '73, pages 17-18, Appendix B. The columns are:

`isBlues` : (indicated by  `+` after the song name in the original text)

`Vclm`    : male vocals<br/>
`Vclf`    : female vocals<br/>
`Hca`     : Harmonica<br/>
`Kaz`     : Kazoo<br/>
`Jug`     : Jug<br/>
`Mnd`     : Mandolin<br/>
`Bjo/Gts` : Banjo/guitars<br/>
`Vln`     : Violin<br/>
`Pno`     : Piano<br/>
`Perc`    : Percussion<br/>

Blank lines indicate a division between albums or recording sessions. The `XX`s in the table may be misprints.
#### Usage
Potentially various statistical clustering and visualization tasks. Predicting the `isBlues` variable.

## mongolia.tsv
#### Description
Cattle in Mongolian regions. Uploaded by user Jan on Stackoverflow. The source is called Хөвсгөл аймгийн статистикийн эмхэтгэл 2018 and can be found via www.1212.mn/. The area data is on p.13 and the lifestock count on p.55 and p. 61. [Link.](https://history.stackexchange.com/questions/63632/why-was-the-northern-boundary-of-the-mongol-empire-set-where-it-was)
#### Usage
Comparing probability distributions using chi-squared, KL divergence and other methods. Dealing with tab-separated data.

## swiss_avalance_data.csv
From [https://www.slf.ch/de/lawinen/unfaelle-und-lawinen/alle-lawinenunfaelle-20-jahre/](https://www.slf.ch/de/lawinen/unfaelle-und-lawinen/alle-lawinenunfaelle-20-jahre/)

### Hinweis zu Karte und Tabelle
Die Karte ist zoombar. Bei den dargestellten Punkten handelt es sich um den höchsten Punkt der Anrissfläche, eingefärbt entsprechend der prognostizierten Gefahrenstufe.

Die Tabelle ist sortierbar. Dazu auf den Tabellenkopf klicken.

### Hinweise zu den Daten
Es werden alle Lawinenunfälle dargestellt, bei welchen eine oder mehrere Personen von der Lawine mitgerissen wurden.

Nicht dargestellt sind Lawinenabgänge,

bei welchen niemand erfasst / mitgerissen wurde oder bei welchen alle Personen aus der Lawine ausfahren konnten,
welche zu Sachschäden oder zu Suchaktionen geführt haben, ohne dass Personen erfasst wurden,
mit sehr unsicheren / ungenauen Angaben zum Unfallort
Die dargestellten Lawinenereignisse werden von Beobachtern, der Polizei, den Rettungsdiensten, aber auch der Öffentlichkeit gemeldet. Diese Angaben werden von Mitarbeitern des SLF auf Plausibilität überprüft und ggf. korrigiert, können aber Ungenauigkeiten oder Lücken enthalten. Die Tabelle wird regelmässig, aber nicht täglich aufdatiert.

### Interpretation der Daten
Lawinenunfälle passieren vor allem dort, wo viele Wintersportler unterwegs sind. Dies widerspiegelt sich auch in dieser Darstellung der Lawinenunfälle. Die vorliegende Darstellung kann auf besonders unfallträchtige Regionen hinweisen. Orte, an denen in den letzten 20 Jahren keine Unfälle gemeldet worden sind, dürfen umgekehrt nicht als sicher betrachtet werden. Bei entsprechend kritischen Verhältnissen können auch dort im Steilgelände Lawinen ausgelöst werden oder spontan abgehen. Für die Tourenplanung oder die lokale Beurteilung der Lawinensituation sind diese Unfalldaten daher nicht geeignet.

### Unstimmigkeiten, Fehler?
Schicke ein Mail an accidents(at)slf.ch mit entsprechenden Zusatzinformationen, welche uns helfen, die Lawine zu korrigieren.

### Fehlt ein Unfall?
Melde uns diesen, möglichst mit Bildern der Lawine und einer kurzen Beschreibung des Unfallhergangs: Rückmeldeformular. Wir behandeln alle Rückmeldungen vertraulich.

### Koordinaten
Die Verortung der Lawine basiert auf den Angaben der Lawinenmeldungen. Diese werden von uns ggf. angepasst, können aber ungenau sein.

### Aktivität, Erfassungsort
1 Tourengelände
2 Variantengelände
3 Verkehrswege (z.B. Skipisten, Strassen)
4 Gebäude

### Gefahrenstufe
In der Tabelle ist die prognostizierte Gefahrenstufe angegeben. Folgende Bedeutungen:

(3) - Gefahrenstufe 3, aber Unfallort nicht in der im Bulletin angegebenen kritischsten Hang- und Höhenlage
2↗3 - Anstieg der Lawinengefahr im Tagesverlauf, wenn zweite Gefahrenstufe angegeben war (z.B. Doppelkarte mit Einschätzung für trockene und nasse Lawinengefahr)
In der Karte wird die für den Unfall relevante Gefahrenstufe des Tages dargestellt. Ein Link zum Bulletin findet sich im Popupfenster.

### Copyright: WSL-Institut für Schnee- und Lawinenforschung SLF

Diese Daten dürfen unter Angabe des Copyrights und des Bezugsdatums verwendet werden. Beispiel: *Quelle: WSL-Institut für Schnee- und Lawinenforschung SLF, Datenbezug: 26.02.2019*

## Xenon.txt
#### Description
Pressure, Temperature and Volume measurements for a sample of Xenon. Probably simulated using ideal gas law.
#### Usage
Demonstrate limits of linear regression on a non-linear problem.
