# Die Nacht, in der das Netz stehen blieb

Am Abend des 2. November 1988 bemerken Administratoren an amerikanischen Universitäten etwas Merkwürdiges.

Ihre Unix-Rechner werden langsam.

Prozesse häufen sich.

Maschinen, die normalerweise viele Benutzer gleichzeitig bedienen, reagieren kaum noch oder überhaupt nicht mehr.

Anfangs sieht jedes Problem lokal aus.

Ein überlasteter Server.

Ein Softwarefehler.

Vielleicht irgendein Einbruch.

Dann telefonieren Administratoren miteinander.

Berkeley hat Probleme.

MIT hat Probleme.

Weitere Universitäten und Forschungseinrichtungen melden dasselbe.

Plötzlich ist klar:

Das sind nicht mehrere schlechte Abende.

Irgendetwas bewegt sich **zwischen den Rechnern**.

## Das Internet vor dem Web

1988 gibt es natürlich bereits das Internet.

Aber nicht das Internet, das wir heute kennen.

Kein World Wide Web.

Keine Milliarden normaler Endnutzer.

Das Netz verbindet vor allem Universitäten, Forschungslabore, Regierungsstellen und andere Institutionen.

Viele Systeme sind in einer Kultur entstanden, in der man anderen Netzteilnehmern wesentlich mehr Vertrauen entgegenbringt als heute.

Remote-Zugänge, E-Mail-Dienste und Vertrauensbeziehungen zwischen Maschinen sind bequem.

Und genau diese Bequemlichkeit wird jetzt zur Transportinfrastruktur für das Problem.

Administratoren versuchen zunächst herauszufinden, welche Prozesse ihre Systeme überlasten.

Wenn sie verdächtige Programme beenden, tauchen neue auf.

Wenn sie einen Rechner vom Netz trennen, schützen sie ihn zwar möglicherweise vor weiteren Verbindungen.

Aber dann verlieren sie auch den Kommunikationsweg zu anderen Administratoren, die gerade herausfinden, wie man das Problem stoppt.

Das Netzwerk trägt gleichzeitig die Krankheit und die Warnung davor.

Und die Krankheit ist schneller.

## Ein Programm, das sich selbst weiterkopiert

Technische Untersuchungen zeigen, dass sich ein **Wurm** verbreitet.

Anders als ein Virus, der oft an eine Datei oder Benutzeraktion gebunden ist, kann ein Wurm selbstständig von Rechner zu Rechner wandern.

Dieses Programm nutzt nicht nur eine einzelne Schwachstelle.

Es versucht mehrere Wege.

Fehler beziehungsweise Schwächen in Unix-Diensten.

Unsichere Passwörter.

Vertrauensbeziehungen zwischen Computern.

Wenn ein Rechner einem anderen automatisch vertraut und dieser andere kompromittiert ist, wird Vertrauen selbst zum Angriffsweg.

Der Wurm löscht nicht primär Forschungsdaten.

Das klingt zunächst fast beruhigend.

Ist es nicht.

Er startet Prozesse, kopiert sich weiter und verbraucht Ressourcen.

Ein Rechner kann jede Datei noch besitzen und trotzdem praktisch unbrauchbar sein.

Verfügbarkeit ist ebenfalls Teil dessen, was ein Computersystem leisten muss.

Und immer mehr Systeme verlieren genau diese.

Dann finden die Administratoren einen besonders interessanten Konstruktionsfehler.

## Der Wurm glaubte seinen Opfern nicht

Das Programm besitzt einen Mechanismus, um zu prüfen, ob ein Rechner bereits infiziert ist.

Das wäre sinnvoll.

Wenn schon eine Kopie vorhanden ist, braucht man keine zweite.

Nur hat der Entwickler ein mögliches Gegenmittel vorausgesehen.

Was, wenn Administratoren ihre Rechner einfach so antworten lassen, als seien sie bereits infiziert?

Dann könnte der Wurm leicht ausgesperrt werden.

Also programmiert er Misstrauen ein.

Manchmal ignoriert der Wurm die Meldung, dass bereits eine Kopie existiert, und infiziert den Rechner trotzdem erneut.

Die Idee soll verhindern, dass Verteidiger ihn austricksen.

In der Realität sorgt sie dafür, dass auf demselben Rechner immer mehr Kopien gleichzeitig laufen.

Der Wurm verbreitet sich also nicht nur horizontal auf neue Systeme.

Er stapelt sich auf bereits infizierten Maschinen.

Und genau das beschleunigt den Zusammenbruch.

Eine kleine Entscheidung, die den Wurm robuster machen sollte, macht ihn außer Kontrolle.

Damit deutet sich auch etwas über den Autor an.

Das Programm stammt offensichtlich von jemandem, der Unix und Netzwerke sehr gut versteht.

Aber nicht gut genug, um das reale Verhalten seiner eigenen Verbreitungslogik korrekt einzuschätzen.

Dann versucht der Entwickler offenbar selbst, die Katastrophe zu stoppen.

## Die Warnung, die das Netz nicht mehr transportieren kann

Nach Darstellung des FBI erkennt der Urheber, dass der Wurm erheblich mehr Schaden verursacht als beabsichtigt.

Er kontaktiert Freunde und versucht, anonym eine Warnung sowie Informationen zur Bekämpfung des Programms zu verbreiten.

Nur kommt diese Warnung teilweise nicht schnell genug an.

Warum?

Weil der Wurm bereits genau das Netzwerk überlastet, über das die Warnung verschickt werden soll.

Das ist vielleicht die eleganteste Ironie des gesamten Falls.

Der Entwickler veröffentlicht ein Programm, das sich selbstständig durch ein Kommunikationsnetz bewegt.

Dann merkt er, dass es außer Kontrolle ist.

Er möchte dasselbe Netz benutzen, um allen zu sagen, wie man es stoppt.

Aber sein Programm hat das Netz inzwischen schlechter darin gemacht, Nachrichten zu transportieren.

Eine Kopie lässt sich zurückrufen.

Tausende autonome Kopien nicht.

Während Techniker versuchen, den Wurm zu analysieren, führt auch eine menschliche Spur zum Urheber.

Ein Freund spricht mit der *New York Times* und verrät dabei unbeabsichtigt die Initialen:

**RTM**.

Bald fällt ein Name.

**Robert Tappan Morris.**

23 Jahre alt.

Doktorand an Cornell.

## Der Entwickler

Morris hatte den Wurm nicht direkt von Cornell aus gestartet.

Er nutzte einen Rechner am MIT, wodurch der Ursprung weniger offensichtlich wirken sollte.

Er besitzt das technische Profil, das zum Programm passt.

Sein Vater ist selbst ein bekannter Computersicherheitsexperte.

Morris hatte in Harvard studiert und versteht genau jene Systeme, die der Wurm nun quer durch Forschungseinrichtungen beschäftigt.

Später wird intensiv darüber gestritten, was er eigentlich beabsichtigt hatte.

Morris behauptet, nicht vorgehabt zu haben, das Netz lahmzulegen.

Vielleicht wollte er die Größe des Internets messen.

Vielleicht die Möglichkeiten selbstständiger Verbreitung testen.

Seine Absicht spielt moralisch und bei der Strafe eine Rolle.

Sie ändert aber einen technischen Fakt nicht.

Das Programm ging ohne Erlaubnis auf fremde Rechner.

Und sobald es dort war, machte es Dinge, die die Besitzer nicht autorisiert hatten.

## Der erste große Fall unter einem jungen Computergesetz

Das FBI ermittelt.

Morris wird nach dem **Computer Fraud and Abuse Act** angeklagt, einem damals noch jungen Bundesgesetz.

1990 wird er verurteilt.

Er muss nicht ins Gefängnis, erhält aber Bewährung, gemeinnützige Arbeit und eine Geldstrafe.

Die Verurteilung übersteht auch die Berufung.

Der Fall gilt als erste Verurteilung nach dem 1986 verabschiedeten Gesetz und wird zu einem Meilenstein des amerikanischen Computerstrafrechts.

Dabei sollte man den Fall nicht in die platte Aussage verwandeln:

„Programmierfehler sind Verbrechen.“

Das waren sie nicht.

Der entscheidende Punkt war, dass Morris' Software ohne Erlaubnis fremde Systeme betrat und benutzte.

Dass der tatsächliche Schaden größer wurde als angeblich geplant, macht den ursprünglichen Zugriff nicht rückwirkend autorisiert.

Wie viele Rechner betroffen waren, ist weniger exakt, als populäre Darstellungen oft suggerieren.

Häufig wird von ungefähr **6.000 Systemen** gesprochen, teilweise mit der Behauptung, das sei etwa ein Zehntel des damaligen Internets gewesen.

Diese Zahl ist eine historische Schätzung, keine vollständige Inventur.

Aber die genaue Zahl ändert nichts am Kern.

Die Störung war groß genug, dass zahlreiche wichtige Forschungs- und Universitätssysteme gleichzeitig mit demselben Problem kämpften.

Und sie zeigte, dass eine vernetzte Welt eine neue Art von Notfall braucht.

## Aus dem Chaos entsteht CERT

Administratoren arbeiten institutionenübergreifend zusammen, um den Wurm zu verstehen und zu beseitigen.

Dabei wird ein organisatorisches Problem offensichtlich.

Ein Vorfall breitet sich über viele Einrichtungen aus.

Jede sieht nur einen Teil.

Es fehlt ein zentraler Ort, an dem technische Erkenntnisse schnell gesammelt und weitergegeben werden können.

Kurz nach dem Vorfall wird deshalb mit Unterstützung des US-Verteidigungsministeriums am Carnegie Mellon University das **Computer Emergency Response Team Coordination Center**, CERT/CC, aufgebaut.

Nicht der Wurm allein „erfindet“ damit moderne Cybersicherheit.

Aber er macht sehr sichtbar, warum koordinierte Incident Response notwendig ist.

Denn das Internet hat 1988 gleichzeitig zwei gegensätzliche Eigenschaften gezeigt.

Verbindungen zwischen Rechnern lassen ein Problem rasend schnell wandern.

Verbindungen zwischen Menschen lassen die Lösung ebenfalls wandern.

Nur muss die zweite schneller werden als die erste.

Das ist auch der schönste Schlusspunkt des Falls.

Morris hatte ein Programm geschrieben, das unabhängig von ihm weiterarbeitete.

Als er begriff, was er ausgelöst hatte, war seine persönliche Entscheidung längst nicht mehr entscheidend.

Er konnte sich entschuldigen.

Er konnte Hinweise verschicken.

Er konnte Freunde um Hilfe bitten.

Aber er konnte das Programm nicht zurückholen.

Die Software besaß keine Bosheit.

Sie besaß etwas für diesen Moment viel Gefährlicheres:

**Autonomie plus einen schlechten Parameter.**

Und als ihr Autor das Netz benutzen wollte, um seinen Fehler zu erklären, war sein Fehler bereits damit beschäftigt, genau dieses Netz unbrauchbar zu machen.

## Quellen und Beleglage

- [FBI, „Morris Worm“](https://www.fbi.gov/history/cases-and-criminals/morris-worm), genutzt für Chronologie, betroffene Institutionen, Identifizierung des Urhebers, Ermittlung, Verurteilung und die Entstehung einer koordinierten Notfallstruktur.
- [Wikipedia, „Morris worm“](https://en.wikipedia.org/wiki/Morris_worm), genutzt für die verschiedenen Eintrittswege, den Mechanismus wiederholter Infektionen, Berufung und die Unsicherheit rund um die oft zitierte Zahl betroffener Hosts.
- Die Geschichte trennt Morris' behauptete Absicht klar vom tatsächlichen Verhalten der Software und von der rechtlichen Feststellung des unautorisierten Zugriffs.
