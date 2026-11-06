---
updatedAt: 2026-11-05T11:48:25.000Z
siteIndex: ./llms.txt
---

# Schichtenmodell und Modellierung

Bei der Umsetzung von IT-Grundschutz muss der betrachtete Informationsverbund mit Hilfe der vorhandenen Bausteine nachgebildet werden, es müssen also die relevanten Sicherheitsanforderungen aus dem IT-Grundschutz-Kompendium zusammengetragen werden. Dafür müssen alle Prozesse, Anwendungen und IT-Systeme erfasst sein, beziehungsweise die Strukturanalyse und in der Regel eine Schutzbedarfsfeststellung vorliegen. Darauf aufbauend wird ein IT-Grundschutz-Modell des Informationsverbunds erstellt, das aus verschiedenen, gegebenenfalls auch mehrfach verwendeten IT-Grundschutz-Bausteinen besteht und eine Abbildung zwischen den Bausteinen und den sicherheitsrelevanten Aspekten des Informationsverbunds beinhaltet.

Das erstellte IT-Grundschutz-Modell ist unabhängig davon, ob der Informationsverbund aus bereits im Einsatz befindlichen IT-Systemen besteht oder ob es sich um einen Informationsverbund handelt, der sich erst im Planungsstadium befindet. Das Modell kann daher unterschiedlich verwendet werden:

- Das IT-Grundschutz-Modell eines *bereits realisierten* Informationsverbunds identifiziert über die verwendeten Bausteine die relevanten Sicherheitsanforderungen. Es kann in Form eines Prüfplans benutzt werden, um einen Soll-Ist-Vergleich durchzuführen.
- Das IT-Grundschutz-Modell eines *geplanten* Informationsverbunds stellt hingegen ein Entwicklungskonzept dar. Es beschreibt über die ausgewählten Bausteine, welche Sicherheitsanforderungen bei der Realisierung des Informationsverbunds erfüllt werden müssen.

Typischerweise wird ein im Einsatz befindlicher Informationsverbund sowohl bereits realisierte als auch in Planung befindliche Anteile umfassen. Das resultierende IT-Grundschutz-Modell beinhaltet dann sowohl einen Prüfplan wie auch Anteile eines Entwicklungskonzepts. Alle im Prüfplan bzw. im Entwicklungskonzept vorgesehenen Sicherheitsanforderungen bilden gemeinsam die Basis für die Erstellung des Sicherheitskonzeptes.

Um einen im Allgemeinen komplexen Informationsverbund nach IT-Grundschutz zu modellieren, müssen die passenden Bausteine des IT-Grundschutz-Kompendiums ausgewählt und umgesetzt werden. Um diese Auswahl zu erleichtern, sind die Bausteine im IT-Grundschutz-Kompendium zunächst in Prozess- und System-Bausteine aufgeteilt und diese jeweils in einzelne Schichten untergliedert:

**Prozess-Bausteine:**

Die Prozess-Bausteine, die in der Regel für sämtliche oder große Teile eines Informationsverbunds gleichermaßen gelten, unterteilen sich in die folgenden Schichten, die wiederum aus weiteren Teilschichten bestehen können.

- Die Schicht ISMS enthält als Grundlage für alle weiteren Aktivitäten im Sicherheitsprozess den Baustein *Sicherheitsmanagement.*
- Die Schicht ORP befasst sich mit organisatorischen und personellen Sicherheitsaspekten. In diese Schicht fallen beispielsweise die Bausteine *Organisation* und *Personal*.
- Die Schicht CON enthält Bausteine, die sich mit Konzepten und Vorgehensweisen befassen. Typische Bausteine der Schicht CON sind unter anderem *Kryptokonzept* und *Datenschutz*.
- Die Schicht OPS umfasst alle Sicherheitsaspekte betrieblicher Art. Insbesondere sind dies die Sicherheitsaspekte des operativen IT-Betriebs, sowohl bei einem Betrieb im Haus, als auch bei einem IT-Betrieb, der in Teilen oder komplett durch Dritte betrieben wird. Ebenso enthält er die Sicherheitsaspekte, die bei einem IT-Betrieb für Dritte zu beachten sind. Beispiele für die Schicht OPS sind die Bausteine *Schutz vor Schadprogrammen* und *Outsourcing für Kunden.*
- In der Schicht DER finden sich alle Bausteine, die für die Überprüfung der umgesetzten Sicherheitsmaßnahmen, die Detektion von Sicherheitsvorfällen sowie die geeigneten Reaktionen darauf relevant sind. Typische Bausteine der Schicht DER sind *Behandlung von Sicherheitsvorfällen* und *Vorsorge für IT-Forensik*.

Neben den Prozess-Bausteinen beinhaltet das IT-Grundschutz-Kompendium auch System-Bausteine. Diese werden in der Regel auf einzelne Zielobjekte oder Gruppen von Zielobjekten angewendet. Die System-Bausteine unterteilen sich in die folgenden Schichten. Ähnlich wie die Prozess-Bausteine können auch die System-Bausteine aus weiteren Teilschichten bestehen.

**System-Bausteine:**

- Die Schicht APP beschäftigt sich mit der Absicherung von Anwendungen und Diensten, unter anderem in den Bereichen Kommunikation, Verzeichnisdienste, netzbasierte Dienste sowie Business- und Client-Anwendungen. Typische Bausteine der Schicht APP sind *Allgemeiner E-Mail-Client und -Server*, *Office-Produkte*, *Webserver* und *Relationale Datenbanken*.
- Die Schicht SYS betrifft die einzelnen IT-Systeme des Informationsverbunds, die gegebenenfalls in Gruppen zusammengefasst wurden. Hier werden die Sicherheitsaspekte von Servern, Desktop-Systemen, Mobile Devices und sonstigen IT-Systemen wie Druckern und TK-Anlagen behandelt. Zur Schicht SYS gehören beispielsweise Bausteine zu konkreten Betriebssystemen, *Allgemeine Smartphones und Tablets* sowie *Drucker, Kopierer und Multifunktionsgeräte*.
- Die Schicht IND befasst sich mit Sicherheitsaspekten industrieller IT. In diese Schicht fallen beispielsweise die Bausteine *Prozessleit- und Automatisierungstechnik*, *Allgemeine ICS-Komponente* und *Speicherprogrammierbare Steuerung (SPS)*.
- Die Schicht NET betrachtet die Vernetzungsaspekte, die sich nicht primär auf bestimmte IT-Systeme, sondern auf die Netzverbindungen und die Kommunikation beziehen. Dazu gehören zum Beispiel die Bausteine *Netz-Management*, *Firewall* und *WLAN-Betrieb*.
- Die Schicht INF befasst sich mit den baulich-technischen Gegebenheiten, hier werden Aspekte der infrastrukturellen Sicherheit zusammengeführt. Dies betrifft unter anderem die Bausteine *Allgemeines* *Gebäude* und *Rechenzentrum*.

## Modellierung

Die Modellierung nach IT-Grundschutz besteht darin, für die Bausteine jeder Schicht zu entscheiden, ob und wie sie zur Abbildung des Informationsverbunds herangezogen werden können. Je nach betrachtetem Baustein kann es sich um unterschiedliche Zielobjekte handeln, beispielsweise um Anwendungen, IT-Systeme, Gruppen von Komponenten, Räume und Gebäude.

In den einzelnen Bausteinen ist in Kapitel 1.3 „Abgrenzung und Modellierung“ detailliert beschrieben, wann ein Baustein eingesetzt werden soll und auf welche Zielobjekte er anzuwenden ist.

Bei der Modellierung eines Informationsverbunds nach IT-Grundschutz kann es Zielobjekte geben, die mit den vorliegenden Bausteinen nicht hinreichend abgebildet werden können. In diesem Fall muss eine Risikoanalyse durchgeführt werden, wie sie in der IT-Grundschutz-Methodik beschrieben ist.

In vielen Teilschichten gibt es allgemeine Bausteine, die grundlegende Aspekte übergreifend für die spezifischen Bausteine beschreiben. Beispielsweise enthält SYS.2.1 *Allgemeiner Client* Anforderungen für *alle* Client-Betriebssysteme, die dann für macOS-, Windows- und Unix/Linux-Clients in den entsprechenden Bausteinen konkretisiert und ergänzt werden. Weitere Beispiele sind APP.2.1 *Allgemeiner Verzeichnisdienst* oder SYS.3.2.1 *Allgemeine Smartphones und Tablets*. Spezifische Bausteine sind stets in Verbindung mit den allgemeinen Bausteinen anzuwenden. Weiterhin stellen allgemeine Bausteine eine gute Grundlage für die Modellierung und Risikoanalyse dar, wenn für ein konkretes Zielobjekt kein spezifischer Baustein existiert.

Die nachfolgende Tabelle gibt einen ersten Überblick, auf welche Zielobjekttypen die Bausteine jeweils anzuwenden sind und in welcher Reihenfolge die Umsetzung der Bausteine erfolgen kann (Erläuterung zu R1, R2 und R3 in Kapitel 2.2 *Bearbeitungsreihenfolge der Bausteine*).

Dabei gibt es Bausteine, die eindeutig zu Zielobjekttypen wie IT-System, Anwendung oder Informationsverbund/übergeordnete Aspekte zuzuordnen sind, d. h. diese Aspekte *ausschließlich* oder *mehrheitlich* behandeln. Einige Bausteine, wie z. B. OPS.1.2.4 *Telearbeit* oder INF.9 *Mobiler Arbeitsplatz*, lassen sich *nicht* eindeutig zu Zielobjekttypen zuordnen, da sie verschiedene Aspekte behandeln. Telearbeit behandelt z. B. Aspekte von IT-Systemen, Kommunikationsverbindungen, Informationsfluss, Datensicherung usw. Diese Bausteine haben somit Auswirkungen auf den gesamten Informationsverbund und werden daher dem Zielobjekttyp „Informationsverbund/übergeordnete Aspekte“ zugeordnet.

Die Zuordnung zu den Zielobjekten ist exemplarisch und dient zur besseren Einordnung und einfacherem Verständnis. In der individuellen Umsetzung von IT-Grundschutz bedeutet z. B. eine Zuordnung eines Bausteins zu „Informationsverbund/übergeordnete Aspekte“ nicht, dass dieser Zielobjekttyp angelegt werden muss. Vielmehr ist damit gemeint, dass der Baustein Auswirkungen auf den gesamten Informationsverbund und damit gegebenenfalls mehrere Zielobjekte haben kann.

| Baustein | Reihenfolge | Anzuwenden auf Zielobjekt**typ** |
|---|---|---|
| ISMS.1 Sicherheitsmanagement | R1 | Informationsverbund/übergeordnete Aspekte |
| ORP.1 Organisation | R1 | Informationsverbund/übergeordnete Aspekte |
| ORP.2 Personal | R1 | Informationsverbund/übergeordnete Aspekte |
| ORP.3 Sensibilisierung und Schulung zur Informationssicherheit | R1 | Informationsverbund/übergeordnete Aspekte |
| ORP.4 Identitäts- und Berechtigungsmanagement | R1 | Informationsverbund/übergeordnete Aspekte |
| ORP.5 Compliance Management (Anforderungsmanagement) | R3 | Informationsverbund/übergeordnete Aspekte |
| CON.1 Kryptokonzept | R3 | Informationsverbund/übergeordnete Aspekte |
| CON.2 Datenschutz | R2 | Informationsverbund/übergeordnete Aspekte |
| CON.3 Datensicherungskonzept | R1 | Informationsverbund/übergeordnete Aspekte |
| CON.6 Löschen und Vernichten | R1 | Informationsverbund/übergeordnete Aspekte |
| CON.7 Informationssicherheit auf Auslandsreisen | R3 | Informationsverbund/übergeordnete Aspekte |
| CON.8 Software-Entwicklung | R3 | Informationsverbund/übergeordnete Aspekte |
| CON.9 Informationsaustausch | R3 | Informationsverbund/übergeordnete Aspekte |
| CON.10 Entwicklung von Webanwendungen | R2 | Informationsverbund/übergeordnete Aspekte |
| CON.11.1 Geheimschutz VS-NUR FÜR DEN DIENSTGEBRAUCH (VS-NfD) | R3 | Informationsverbund/übergeordnete Aspekte |
| OPS.1.1.1 Allgemeiner IT-Betrieb | R1 | Informationsverbund/übergeordnete Aspekte |
| OPS.1.1.2 Ordnungsgemäße IT-Administration | R1 | Informationsverbund/übergeordnete Aspekte |
| OPS.1.1.3 Patch- und Änderungsmanagement | R1 | Informationsverbund/übergeordnete Aspekte |
| OPS.1.1.4 Schutz vor Schadprogrammen | R1 | Informationsverbund/übergeordnete Aspekte |
| OPS.1.1.5 Protokollierung | R1 | Informationsverbund/übergeordnete Aspekte |
| OPS.1.1.6 Software-Tests und -Freigaben | R1 | Informationsverbund/übergeordnete Aspekte |
| OPS.1.1.7 Systemmanagement | R2 | Informationsverbund/übergeordnete Aspekte |
| OPS.1.2.2 Archivierung | R3 | Informationsverbund/übergeordnete Aspekte |
| OPS.1.2.4 Telearbeit | R2 | Informationsverbund/übergeordnete Aspekte |
| OPS.1.2.5 Fernwartung | R3 | Informationsverbund/übergeordnete Aspekte |
| OPS.1.2.6 NTP -Zeitsynchronisation | R2 | Anwendung |
| OPS.2.2 Cloud-Nutzung | R2 | Informationsverbund/übergeordnete Aspekte |
| OPS.2.3 Nutzung von Outsourcing | R2 | Informationsverbund/übergeordnete Aspekte |
| OPS.3.2 Anbieten von Outsourcing | R3 | Informationsverbund/übergeordnete Aspekte |
| DER.1 Detektion von sicherheitsrelevanten Ereignissen | R1 | Informationsverbund/übergeordnete Aspekte |
| DER.2.1 Behandlung von Sicherheitsvorfällen | R1 | Informationsverbund/übergeordnete Aspekte |
| DER.2.2 Vorsorge für die IT-Forensik | R3 | Informationsverbund/übergeordnete Aspekte |
| DER.2.3 Bereinigung weitreichender Sicherheitsvorfälle | R3 | Informationsverbund/übergeordnete Aspekte |
| DER.3.1 Audits und Revisionen | R3 | Informationsverbund/übergeordnete Aspekte |
| DER.3.2 Revisionen auf Basis des Leitfadens IS-Revision | R3 | Informationsverbund/übergeordnete Aspekte |
| DER.4 Notfallmanagement | R3 | Informationsverbund/übergeordnete Aspekte |
| APP.1.1 Office-Produkte | R2 | Anwendung |
| APP.1.2 Webbrowser | R2 | Anwendung |
| APP.1.4 Mobile Anwendungen (Apps) | R2 | Anwendung |
| APP.2.1 Allgemeiner Verzeichnisdienst | R2 | Anwendung |
| APP.2.2 Active Directory Domain Services | R2 | Anwendung |
| APP.2.3 OpenLDAP | R2 | Anwendung |
| APP.3.1 Webanwendungen und Webservices | R2 | Anwendung |
| APP.3.2 Webserver | R2 | Anwendung |
| APP.3.3 Fileserver | R2 | Anwendung |
| APP.3.4 Samba | R2 | Anwendung |
| APP.3.6 DNS-Server | R2 | Anwendung |
| APP.4.2 SAP-ERP-System | R2 | Anwendung |
| APP.4.3 Relationale Datenbanken | R2 | Anwendung |
| APP.4.4 Kubernetes | R2 | Anwendung |
| APP.4.6 SAP ABAP-Programmierung | R2 | Anwendung |
| APP.5.2 Microsoft Exchange und Outlook | R2 | Anwendung |
| APP.5.3 Allgemeiner E-Mail-Client und -Server | R2 | Anwendung |
| APP.5.4 Unified Communications und Collaboration (UCC) | R2 | Anwendung |
| APP.6 Allgemeine Software | R2 | Anwendung |
| APP.7 Entwicklung von Individualsoftware | R3 | Informationsverbund/übergeordnete Aspekte |
| SYS.1.1 Allgemeiner Server | R2 | IT-System |
| SYS.1.2.2 Windows Server 2012 | R2 | IT-System |
| SYS.1.2.3 Windows Server | R2 | IT-System |
| SYS.1.3 Server unter Linux und Unix | R2 | IT-System |
| SYS.1.5 Virtualisierung | R2 | IT-System |
| SYS.1.6 Containerisierung | R2 | IT-System |
| SYS.1.7 IBM Z | R2 | IT-System |
| SYS.1.8 Speicherlösungen | R2 | IT-System |
| SYS.1.9 Terminalserver | R2 | IT-System |
| SYS.2.1 Allgemeiner Client | R2 | IT-System |
| SYS.2.2.3 Clients unter Windows | R2 | IT-System |
| SYS.2.3 Clients unter Linux und Unix | R2 | IT-System |
| SYS.2.4 Clients unter macOS | R2 | IT-System |
| SYS.2.5 Client-Virtualisierung | R2 | IT-System |
| SYS.2.6 Virtual Desktop Infrastructure | R2 | IT-System |
| SYS.3.1 Laptops | R2 | IT-System |
| SYS.3.2.1 Allgemeine Smartphones und Tablets | R2 | IT-System |
| SYS.3.2.2 Mobile Device Management (MDM) | R2 | Informationsverbund/übergeordnete Aspekte |
| SYS.3.2.3 iOS (for Enterprise) | R2 | IT-System |
| SYS.3.2.4 Android | R2 | IT-System |
| SYS.3.3 Mobiltelefon | R2 | IT-System |
| SYS.4.1 Drucker, Kopierer und Multifunktionsgeräte | R2 | IT-System |
| SYS.4.3 Eingebettete Systeme | R2 | IT-System |
| SYS.4.4 Allgemeines IoT-Gerät | R2 | IT-System |
| SYS.4.5 Wechseldatenträger | R2 | IT-System |
| NET.1.1 Netzarchitektur und -design | R2 | Netz |
| NET.1.2 Netzmanagement | R2 | IT-System |
| NET.2.1 WLAN-Betrieb | R2 | Netz |
| NET.2.2 WLAN-Nutzung | R2 | IT-System |
| NET.3.1 Router und Switches | R2 | IT-System |
| NET.3.2 Firewall | R2 | IT-System |
| NET.3.3 VPN | R2 | IT-System |
| NET.3.4 Network Access Control | R2 | IT-System |
| NET.4.1 TK-Anlagen | R2 | IT-System |
| NET.4.2 VoIP | R2 | Netz |
| NET.4.3 Faxgeräte und Faxserver | R2 | IT-System |
| IND.1 Prozessleit- und Automatisierungstechnik | R2 | Informationsverbund/übergeordnete Aspekte |
| IND.2.1 Allgemeine ICS-Komponente | R2 | IT-System |
| IND.2.2 Speicherprogrammierbare Steuerung (SPS) | R2 | IT-System |
| IND.2.3 Sensoren und Aktoren | R2 | IT-System |
| IND.2.4 Maschine | R2 | IT-System |
| IND.2.7 Safety Instrumented Systems | R2 | IT-System |
| IND.3.2 Fernwartung im industriellen Umfeld | R2 | IT-System |
| INF.1 Allgemeines Gebäude | R2 | Gebäude/Raum |
| INF.2 Rechenzentrum sowie Serverraum | R2 | Gebäude/Raum |
| INF.5 Raum sowie Schrank für technische Infrastruktur | R2 | Gebäude/Raum |
| INF.6 Datenträgerarchiv | R2 | Gebäude/Raum |
| INF.7 Büroarbeitsplatz | R2 | Gebäude/Raum |
| INF.8 Häuslicher Arbeitsplatz | R2 | Gebäude/Raum |
| INF.9 Mobiler Arbeitsplatz | R2 | Informationsverbund/übergeordnete Aspekte |
| INF.10 Besprechungs-, Veranstaltungs- und Schulungsräume | R2 | Gebäude/Raum |
| INF.11 Allgemeines Fahrzeug | R3 | Gebäude/Raum |
| INF.12 Verkabelung | R2 | Gebäude/Raum |
| INF.13 Technisches Gebäudemanagement | R2 | Gebäude/Raum |
| INF.14 Gebäudeautomatisierung | R2 | Gebäude/Raum |

## Bearbeitungsreihenfolge der Bausteine

Um grundlegende Risiken abzudecken und eine ganzheitliche Informationssicherheit aufzubauen, müssen die essenziellen Sicherheitsanforderungen frühzeitig erfüllt und entsprechende Sicherheitsmaßnahmen umgesetzt werden. Daher wird im IT-Grundschutz mit R1, R2 und R3 eine Reihenfolge für die umzusetzenden Bausteine vorgeschlagen (siehe Kapitel 2.1 *Modellierung*).

- R1: Diese Bausteine sollten vorrangig umgesetzt werden, da sie die Grundlage für einen effektiven Sicherheitsprozess bilden.
- R2: Diese Bausteine sollten als nächstes umgesetzt werden, da sie in wesentlichen Teilen des Informationsverbundes für nachhaltige Sicherheit erforderlich sind.
- R3: Diese Bausteine werden zur Erreichung des angestrebten Sicherheitsniveaus ebenfalls benötigt und müssen umgesetzt werden. Es wird empfohlen, diese erst nach den anderen Bausteinen zu betrachten.

Diese Kennzeichnung zeigt eine sinnvolle zeitliche Reihenfolge für die Umsetzung der Anforderungen des jeweiligen Bausteins auf und stellt keine Gewichtung der Bausteine untereinander dar. Grundsätzlich müssen alle für den jeweiligen Informationsverbund relevanten Bausteine des IT-Grundschutz-Kompendiums umgesetzt werden.
