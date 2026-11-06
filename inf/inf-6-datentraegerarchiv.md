---
updatedAt: 2026-11-05T11:48:25.000Z
id: INF.6
siteIndex: ../llms.txt
---

# Grundschutz Baustein INF.6

## INF.6 Datenträgerarchiv

### Beschreibung

#### Einleitung

Datenträgerarchive sind abgeschlossene Räumlichkeiten innerhalb einer Institution, in denen Datenträger jeder Art gelagert werden. Dazu gehören neben Datenträgern, auf denen digitale Informationen abgespeichert sind, auch Papierdokumente, Filme oder sonstige Medien.

#### Zielsetzung

In diesem Baustein werden die typischen Gefährdungen und Anforderungen bezüglich der Informationssicherheit für ein Datenträgerarchiv beschrieben. Ziel ist der Schutz der Informationen, die sich auf den dort archivierten Datenträgern und weiteren Medien befinden.

#### Abgrenzung und Modellierung

Der Baustein INF.6 *Datenträgerarchiv* ist für alle Räume anzuwenden, die als Archiv von Datenträgern genutzt werden.

Dieser Baustein betrachtet technische und nichttechnische Sicherheitsanforderungen für Datenträgerarchive. Empfehlungen zur korrekten Archivierung werden in diesem Baustein nicht behandelt. Hinweise dazu finden sich im Baustein OPS.1.2.2 *Archivierung*.

Im Rahmen des IT-Grundschutzes werden an die Archivräume hinsichtlich des Brandschutzes keine erhöhten Anforderungen gestellt. Zusätzliche Anforderungen an den Brandschutz können aber durch die Behältnisse erfüllt werden, in denen die Datenträger aufbewahrt werden.

### Gefährdungslage

Da IT-Grundschutz-Bausteine nicht auf individuelle Informationsverbünde eingehen können, werden zur Darstellung der Gefährdungslage typische Szenarien zugrunde gelegt. Die folgenden spezifischen Bedrohungen und Schwachstellen sind für den Baustein INF.6 *Datenträgerarchiv* von besonderer Bedeutung.

#### Unzulässige Temperatur und Luftfeuchtigkeit

Bei der Lagerung von digitalen Langzeitspeichermedien können Temperaturschwankungen oder zu hohe Luftfeuchtigkeit zu Datenfehlern und reduzierter Speicherdauer führen.

#### Fehlende oder unzureichende Regelungen

Wenn Mitarbeitende die Fenster und Türen nach Verlassen des Datenträgerarchivs nicht schließen oder verschließen, können Datenträger oder andere Informationen entwendet werden. Sensible Informationen könnten dann von unberechtigten Personen eingesehen oder weitergegeben werden. Wenn Mitarbeitenden die entsprechenden Regelungen nicht hinreichend bekannt sind, können Sicherheitslücken auftreten. Regelungen lediglich festzulegen ist nicht ausreichend. Sie müssen beachtet werden, damit der Betrieb störungsfrei ist. Viele Probleme entstehen, wenn Regelungen zwar vorhanden, aber nicht bekannt sind.

#### Unbefugter Zutritt zu schutzbedürftigen Räumen

Fehlen Zutrittskontrollen oder sind diese unzureichend, können unberechtigte Personen ein Datenträgerarchiv betreten und schützenswerte Informationen einsehen, entwenden oder manipulieren. Dadurch kann die Verfügbarkeit, Vertraulichkeit und Integrität der archivierten Informationen beeinträchtigt werden. Selbst wenn keine unmittelbaren Schäden zu erkennen sind, kann der Betriebsablauf gestört werden.

#### Diebstahl

Da viele Datenträger sehr handlich sind, ist es umso leichter, sie unbemerkt in eine Tasche oder unter die Kleidung zu stecken und mitzunehmen. Gibt es keine Kopien von den Informationen, sind die auf den gestohlenen Datenträgern abgespeicherten Informationen verloren. Darüber hinaus könnten die Personen, die Datenträger entwendet haben, vertrauliche Informationen einsehen und offenlegen. Dadurch können weitere Schäden entstehen. Diese wiegen in den meisten Fällen deutlich schwerer als die Kosten von ersatzweise angeschafften Datenträgern.

### Anforderungen

Im Folgenden sind die spezifischen Anforderungen des Bausteins INF.6 *Datenträgerarchiv*aufgeführt. Der oder die Informationssicherheitsbeauftragte (ISB) ist dafür zuständig, dass alle Anforderungen gemäß dem festgelegten Sicherheitskonzept erfüllt und überprüft werden. Bei strategischen Entscheidungen ist der oder die ISB stets einzubeziehen.

Im IT-Grundschutz-Kompendium sind darüber hinaus weitere Rollen definiert. Sie sollten besetzt werden, insofern dies sinnvoll und angemessen ist.

| Zuständigkeiten | Rollen |
|---|---|
| Grundsätzlich zuständig | Informationssicherheitsbeauftragte (ISB) |
| Weitere Zuständigkeiten | Mitarbeitende, Planende, Haustechnik, Brandschutzbeauftragte |

Genau eine Rolle sollte *Grundsätzlich zuständig* sein. Darüber hinaus kann es noch *Weitere Zuständigkeiten* geben. Falls eine dieser weiteren Rollen für die Erfüllung einer Anforderung vorrangig zuständig ist, dann wird diese Rolle hinter der Überschrift der Anforderung in eckigen Klammern aufgeführt. Die Verwendung des Singulars oder Plurals sagt nichts darüber aus, wie viele Personen diese Rollen ausfüllen sollen.

#### Basis-Anforderungen

Die folgenden Anforderungen MÜSSEN für diesen Baustein vorrangig erfüllt werden.

##### INF.6.A1 Handfeuerlöscher (B) [Brandschutzbeauftragte]

Im Brandfall MÜSSEN im Datenträgerarchiv geeignete Handfeuerlöscher leicht erreichbar sein. Diese Handfeuerlöscher MÜSSEN regelmäßig inspiziert und gewartet werden. Mitarbeitende, die in der Nähe eines Datenträgerarchivs tätig sind, MÜSSEN in die Benutzung der Handfeuerlöscher eingewiesen werden.

##### INF.6.A2 Zutrittsregelung und -kontrolle (B) [Haustechnik]

Der Zutritt zum Datenträgerarchiv DARF NUR für befugte Personen möglich sein. Der Zutritt MUSS auf ein Mindestmaß an Mitarbeitenden reduziert sein. Daher MUSS der Zutritt geregelt und kontrolliert werden. Für die Zutrittskontrolle MUSS ein Konzept entwickelt werden. Die darin festgelegten Maßnahmen für die Zutrittskontrolle SOLLTEN regelmäßig daraufhin überprüft werden, ob sie noch wirksam sind. Um es zu erschweren bzw. zu verhindern, dass eine Zutrittskontrolle umgangen wird, MUSS der komplette Raum einen dem Schutzbedarf genügenden mechanischen Widerstand aufweisen, der keinesfalls unter RC2 (gemäß DIN EN 1627) liegen darf.

##### INF.6.A3 Schutz vor Staub und anderer Verschmutzung (B)

Es MUSS sichergestellt werden, dass die Datenträger im Datenträgerarchiv ausreichend vor Staub und Verschmutzung geschützt sind. Die Anforderungen dafür MÜSSEN bereits in der Planungsphase analysiert werden. Es MUSS in Datenträgerarchiven ein striktes Rauchverbot eingehalten werden.

##### INF.6.A4 Geschlossene Fenster und abgeschlossene Türen (B) [Mitarbeitende]

In einem Datenträgerarchiv SOLLTEN, wenn möglich, keine Fenster vorhanden sein. Gibt es dennoch Fenster, MÜSSEN diese beim Verlassen des Datenträgerarchivs geschlossen werden. Ebenso MUSS beim Verlassen die Tür verschlossen werden. Auch Brand- und Rauchschutztüren MÜSSEN geschlossen werden.

#### Standard-Anforderungen

Gemeinsam mit den Basis-Anforderungen entsprechen die folgenden Anforderungen dem Stand der Technik für diesen Baustein. Sie SOLLTEN grundsätzlich erfüllt werden.

##### INF.6.A5 Verwendung von Schutzschränken (S) [Mitarbeitende]

Die Datenträger und Medien in Datenträgerarchiven SOLLTEN in geeigneten Schutzschränken gelagert werden.

##### INF.6.A6 Vermeidung von wasserführenden Leitungen (S) [Haustechnik]

In Datenträgerarchiven SOLLTEN unnötige wasserführende Leitungen generell vermieden werden. Sind dennoch Wasserleitungen durch das Datenträgerarchiv hinweg verlegt, SOLLTEN diese regelmäßig daraufhin überprüft werden, ob sie noch dicht sind. Zudem SOLLTEN Vorkehrungen getroffen werden, um frühzeitig erkennen zu können, ob dort Wasser austritt. Für ein Datenträgerarchiv mit Hochverfügbarkeitsanforderungen SOLLTE es Reaktionspläne geben, die genau vorgeben, wer im Fall eines Lecks informiert werden muss und wie grundsätzlich vorzugehen ist.

##### INF.6.A7 Einhaltung von klimatischen Bedingungen (S) [Haustechnik]

Es SOLLTE sichergestellt werden, dass die zulässigen Höchst- und Tiefstwerte für Temperatur und Luftfeuchtigkeit sowie der Schwebstoffanteil in der Raumluft im Datenträgerarchiv eingehalten werden. Die Werte von Lufttemperatur und -feuchte SOLLTEN mehrmals im Jahr für die Dauer von einer Woche aufgezeichnet und dokumentiert werden. Dabei festgestellte Abweichungen vom Sollwert SOLLTEN zeitnah behoben werden. Die eingesetzten Klimageräte SOLLTEN regelmäßig gewartet werden.

##### INF.6.A8 Sichere Türen und Fenster (S) [Planende]

Sicherungsmaßnahmen wie Fenster, Türen und Wände SOLLTEN bezüglich Einbruch, Brand und Rauch gleichwertig und angemessen sein. Abhängig vom Schutzbedarf SOLLTE eine geeignete Widerstandsklasse gemäß der DIN EN 1627 erfüllt werden. Alle Sicherheitstüren und -fenster SOLLTEN regelmäßig daraufhin überprüft werden, ob sie noch entsprechend funktionieren. Der komplette Raum SOLLTE einen dem Schutzbedarf genügenden mechanischen Widerstand aufweisen, der keinesfalls unter RC3 (gemäß DIN EN 1627) liegt.

#### Anforderungen bei erhöhtem Schutzbedarf

Im Folgenden sind für diesen Baustein exemplarische Vorschläge für Anforderungen aufgeführt, die über dasjenige Schutzniveau hinausgehen, das dem Stand der Technik entspricht. Die Vorschläge SOLLTEN bei erhöhtem Schutzbedarf in Betracht gezogen werden. Die konkrete Festlegung erfolgt im Rahmen einer individuellen Risikoanalyse.

##### INF.6.A9 Gefahrenmeldeanlage (H) [Haustechnik]

Es SOLLTE in Datenträgerarchiven eine angemessene Gefahrenmeldeanlage eingerichtet werden. Diese Gefahrenmeldeanlage SOLLTE regelmäßig geprüft und gewartet werden. Es SOLLTE sichergestellt sein, dass diejenigen Personen, die Gefahrenmeldungen empfangen in der Lage sind, auf Alarmmeldungen angemessen zu reagieren.

### Weiterführende Informationen

#### Wissenswertes

Das Deutsche Institut für Normung macht in seiner Norm „DIN EN 1627:2021-11“ Vorgaben zur physischen Sicherheit von Gebäuden und Räumen.

## Zuordnung zu elementaren Gefährdungen (KRT)

Die Anforderungen dieses Bausteins sind hier den elementaren Gefährdungen (G 0.x) zugeordnet, wie sie in den [elementaren Gefährdungen](../elementare-gefaehrdungen.md) beschrieben sind. „Abwehrt" = die Anforderung trägt zur Abwehr der Gefährdung bei. „CIA" = Bezug zu den Schutzzielen C (Vertraulichkeit), I (Integrität) und A (Verfügbarkeit). Anforderungen, die in dieser Edition entfallen sind (Name „ENTFALLEN"), besitzen keine Zuordnung.

- **INF.6.A1** Handfeuerlöscher — Abwehrt: G 0.1 (Feuer)
- **INF.6.A2** Zutrittsregelung und -kontrolle — Abwehrt: G 0.18 (Fehlplanung oder fehlende Anpassung), G 0.44 (Unbefugtes Eindringen in Räumlichkeiten)
- **INF.6.A3** Schutz vor Staub und anderer Verschmutzung — Abwehrt: G 0.4 (Verschmutzung, Staub, Korrosion), G 0.18 (Fehlplanung oder fehlende Anpassung)
- **INF.6.A4** Geschlossene Fenster und abgeschlossene Türen — Abwehrt: G 0.1 (Feuer), G 0.4 (Verschmutzung, Staub, Korrosion), G 0.44 (Unbefugtes Eindringen in Räumlichkeiten)
- **INF.6.A5** Verwendung von Schutzschränken — Abwehrt: G 0.3 (Wasser), G 0.16 (Diebstahl von Geräten, Datenträgern oder Dokumenten)
- **INF.6.A6** Vermeidung von wasserführenden Leitungen — Abwehrt: G 0.3 (Wasser), G 0.18 (Fehlplanung oder fehlende Anpassung)
- **INF.6.A7** Einhaltung von klimatischen Bedingungen — Abwehrt: G 0.2 (Ungünstige klimatische Bedingungen), G 0.18 (Fehlplanung oder fehlende Anpassung)
- **INF.6.A8** Sichere Türen und Fenster — Abwehrt: G 0.1 (Feuer), G 0.3 (Wasser), G 0.44 (Unbefugtes Eindringen in Räumlichkeiten)
- **INF.6.A9** Gefahrenmeldeanlage — Abwehrt: G 0.1 (Feuer), G 0.3 (Wasser), G 0.18 (Fehlplanung oder fehlende Anpassung), G 0.44 (Unbefugtes Eindringen in Räumlichkeiten) — CIA: CIA
