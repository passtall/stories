# 75 Cent

1986 bekommt Clifford Stoll am Lawrence Berkeley Laboratory in Kalifornien eine Aufgabe, die ungefähr so weit von internationaler Spionage entfernt klingt, wie man sich nur vorstellen kann.

In zwei Abrechnungssystemen des Labors stimmen die Zahlen nicht überein.

Die Differenz beträgt **75 Cent**.

Stoll ist eigentlich Astronom. Er ist eher zufällig in die Computeradministration gerutscht und soll nun herausfinden, warum die Nutzungsabrechnung eines Großrechners nicht aufgeht. Das Labor berechnet Rechenzeit, deshalb müssen verschiedene Protokolle am Ende dieselbe Summe ergeben. Ein paar fehlende Cent könnten alles Mögliche sein: ein Rundungsfehler, eine vergessene Buchung, ein Problem zwischen zwei Programmen.

Stoll sucht also nicht nach einem Hacker.

Er sucht nach Kleingeld.

Und findet stattdessen einen Benutzer, der dort überhaupt nicht existieren dürfte.

## Ein Besucher mit zu vielen Rechten

Beim Abgleichen der Protokolle fällt Stoll auf, dass jemand Rechenzeit verbraucht hat, ohne korrekt abgerechnet zu werden. Der Account passt nicht zu den normalen Benutzern. Als er tiefer gräbt, wird klar, dass da jemand im System unterwegs gewesen ist und sich weit mehr Rechte verschafft hat, als ein gewöhnlicher Nutzer haben sollte.

Der Eindringling nutzt eine Schwachstelle in einer Unix-Umgebung, die ihm weitreichenden Zugriff ermöglicht. Damit kann er nicht nur Dateien lesen, sondern auch Spuren verwischen. Genau deshalb ist die Abweichung von 75 Cent so interessant. Wer ein System vollständig kontrolliert, kann die offensichtlichen Logs verändern. Aber dazu muss er erst einmal wissen, **welche voneinander unabhängigen Aufzeichnungen überhaupt existieren**.

Offenbar hatte der Besucher fast alles bedacht.

Nur nicht die Buchhaltung.

Die naheliegende Reaktion wäre gewesen, die Sicherheitslücke sofort zu schließen, Passwörter zu ändern und den Eindringling auszusperren. Stoll entscheidet sich gegen die einfache Lösung. Er will wissen, wer da ist, woher die Verbindung kommt und was die Person eigentlich sucht.

Das ist riskant. Solange der Zugang offenbleibt, kann der Rechner des Labors als Sprungbrett zu anderen Systemen dienen. Schließt Stoll ihn aber sofort, verschwindet vermutlich die einzige Spur zum Täter.

Also beginnt er zuzusehen.

## Er druckt den Hacker aus

Heute würde man Netzwerkverkehr mitschneiden, Logs zentral sammeln und mit Analysewerkzeugen durchsuchen. 1986 sieht die Realität etwas weniger elegant aus.

Stoll baut sich eine Art improvisiertes Überwachungssystem aus Terminals und Druckern. Sobald der Eindringling aktiv wird, lässt er dessen Befehle auf Papier ausgeben.

Zeile für Zeile.

Meterweise.

Das wirkt beinahe absurd, hat aber einen entscheidenden Vorteil: Was bereits auf Papier steht, kann der Hacker nicht mehr aus dem kompromittierten Rechner löschen.

Stoll beginnt damit, die Bewegungen eines unbekannten Menschen zu beobachten, der vermutlich Tausende Kilometer entfernt sitzt. Der Eindringling durchsucht andere Rechner, probiert Accounts aus, sucht Passwörter und benutzt Berkeley als Zwischenstation. Dabei interessiert er sich auffällig oft für Systeme mit Bezug zum amerikanischen Militär, zu Forschungseinrichtungen und zu Rüstungsprojekten.

Das verändert die Bedeutung des Falls.

Ein neugieriger Student könnte versuchen, in irgendeinen berühmten Rechner einzubrechen. Ein Krimineller könnte Rechenzeit oder Daten stehlen. Dieser Besucher hingegen scheint systematisch nach Informationen mit militärischem Wert zu suchen.

Stoll beginnt, jede Sitzung zu protokollieren: Uhrzeiten, Befehle, Zielsysteme, Verbindungswege.

Und dann versucht er herauszufinden, wo die Person tatsächlich sitzt.

Das ist 1986 erheblich schwieriger, als eine IP-Adresse anzusehen und irgendeine Geo-Datenbank zu befragen. Eine Verbindung kann über mehrere Rechner, Telefonnetze und Datenleitungen laufen. Der Rechner, von dem eine Sitzung in Berkeley eintrifft, muss nicht der Rechner sein, an dem der Täter sitzt.

Jede Spur endet bei einer Organisation, die nur ihren eigenen Abschnitt sehen kann.

Ein Betreiber erkennt, wo eine Verbindung sein Netz betreten hat. Ein Telefonanbieter kann eine Leitung innerhalb seines Systems verfolgen. Eine Behörde benötigt möglicherweise eine rechtliche Grundlage, um überhaupt etwas zu tun.

Niemand sieht den gesamten Weg.

## Das Problem ist offiziell fast nichts wert

Stoll wendet sich an amerikanische Behörden.

Und stößt auf ein Problem, das im Rückblick fast komisch wirkt.

Der unmittelbar nachweisbare finanzielle Schaden?

75 Cent.

Für manche Stellen ist das kein Fall, bei dem sofort alle verfügbaren Ermittler aufspringen. Zuständigkeiten sind unklar. Das Labor ist zivil. Die verdächtigen Zielsysteme liegen teilweise bei anderen Institutionen. Computereinbrüche passen noch nicht sauber in die damaligen bürokratischen Kategorien.

Stoll versucht immer wieder zu erklären, dass die 75 Cent nicht der Schaden sind.

Sie sind nur der Fußabdruck.

Mit der Zeit helfen einzelne Personen beim FBI, bei Telefongesellschaften und in Sicherheitsbehörden. Aber die Zusammenarbeit muss praktisch von Hand zusammengesetzt werden. Das Netzwerk ist längst international. Die Ermittlungsstrukturen funktionieren noch so, als würden Verbrechen höflich innerhalb organisatorischer Grenzen bleiben.

Eine Zeit lang scheint die Spur zu einem amerikanischen Verteidigungsunternehmen in Virginia zu führen. Doch auch dort zeigt sich, wie leicht man einen Zwischenrechner mit dem Ursprung verwechseln kann. Der Eindringling benutzt fremde Systeme, um weitere Systeme zu erreichen.

Der Ort, an dem die Spur auftaucht, ist nicht der Ort, an dem der Mensch sitzt.

Dann fällt Stoll etwas an den Uhrzeiten auf.

## Die Arbeitszeiten passen nicht zu Kalifornien

Der Besucher kommt regelmäßig zurück. Über Monate sammelt Stoll genug Sitzungen, um Gewohnheiten zu erkennen.

Bestimmte Aktivitätszeiten passen merkwürdig schlecht zu einem Menschen an der amerikanischen Westküste. Was in Kalifornien tagsüber passiert, würde anderswo am Abend stattfinden.

Allein beweist das nichts. Menschen schlafen zu merkwürdigen Zeiten, und Hacker sind historisch nicht gerade für ihren geregelten Büroalltag berühmt.

Aber die technischen Spuren führen ebenfalls über den Atlantik.

Nach und nach verengt sich die Route auf **Westdeutschland**.

Nun taucht ein neues Problem auf. Deutsche Telefontechniker können eine aktive Verbindung zurückverfolgen, aber dafür brauchen sie Zeit. Wenn der Eindringling sich nur kurz einloggt, ein paar Dateien abholt und wieder verschwindet, ist die Sitzung vorbei, bevor alle beteiligten Stellen die Spur bis zum nächsten Knoten verfolgen können.

Stoll muss also einen unbekannten Hacker dazu bringen, freiwillig länger online zu bleiben.

Er kann ihm schlecht schreiben: „Bitte noch zehn Minuten, die Bundespost ist fast fertig.“

Also baut er etwas, das der Besucher unbedingt haben möchte.

## Das erfundene Büro

Aus den bisherigen Sitzungen weiß Stoll, dass der Eindringling nach militärisch interessantem Material sucht. Besonders reizvoll ist damals die amerikanische **Strategic Defense Initiative**, Reagans geplantes Raketenabwehrprogramm, meist unter dem Spitznamen „Star Wars“ bekannt.

Stoll richtet auf dem System ein fiktives Projekt ein.

Es sieht aus wie ein ganz normales Forschungsprojekt. Es gibt Dateien, Verwaltungsunterlagen, Namen und genügend langweiligen institutionellen Papierkram, um glaubwürdig zu wirken. Nichts davon enthält echte geheime Informationen. Der Zweck besteht nur darin, jemanden neugierig genug zu machen, dass er Zeit investiert.

Das ist der eigentliche Köder.

Nicht irgendeine blinkende Datei mit dem Namen TOP_SECRET_NUCLEAR_PLANS.

Sondern glaubwürdige Bürokratie.

Der Eindringling findet das Material.

Und bleibt.

Er liest. Er durchsucht Dateien. Er lädt Informationen herunter.

Die längeren Sitzungen geben den deutschen Technikern endlich genug Zeit, die Verbindungen weiterzuverfolgen.

Die Spur endet in **Hannover**.

Bei einem Mann namens **Markus Hess**.

Zum ersten Mal ist aus den abstrakten Leitungswegen ein konkreter Mensch geworden.

Dann passiert noch etwas, das Stolls künstliches Projekt plötzlich viel interessanter macht.

Aus Ungarn trifft eine Anfrage ein, die sich auf Informationen aus genau diesem erfundenen Projekt bezieht.

Das ist ein bemerkenswerter Moment. Stoll hat Material erfunden, das nur deshalb existiert, um den Eindringling zu beobachten. Nun reagiert jemand auf der anderen Seite Europas darauf.

Die Information hat Berkeley verlassen.

Sie wird weitergegeben.

Damit stellt sich eine neue Frage: Wenn Hess die Daten sammelt, **für wen sammelt er sie?**

## Der Kunde hinter dem Hacker

Die deutschen Ermittlungen ergeben schließlich, dass Hess nicht allein aus sportlichem Ehrgeiz durch amerikanische Rechner wandert.

Er gehört zu einer Gruppe westdeutscher Hacker, die erbeutete Informationen an den **sowjetischen KGB** verkaufen.

Plötzlich ergeben die vorherigen Suchmuster Sinn. Das Interesse an Militärsystemen, Verteidigungsunternehmen und Forschungsprojekten war nicht einfach nur Hacker-Neugier. Die Daten hatten für einen Geheimdienst einen tatsächlichen Wert.

Stoll reist später nach Deutschland und sagt aus.

1990 werden Hess und weitere Beteiligte verurteilt.

Aus einer Abweichung von 75 Cent ist eine internationale Spionageermittlung geworden.

Der berühmteste Bericht darüber stammt von Stoll selbst: *The Cuckoo's Egg*. Deshalb sollte man bei manchen besonders farbigen Details im Kopf behalten, dass wir die Geschichte zu einem erheblichen Teil durch die Augen des Mannes kennen, der sie erlebt und später darüber geschrieben hat. Die technischen und gerichtlichen Kernelemente des Falls sind davon allerdings nicht abhängig.

Und gerade der Anfang bleibt deshalb so gut.

Der Eindringling war technisch wesentlich besser als Stoll darin, fremde Computer zu kontrollieren. Er konnte sich Administratorrechte verschaffen, Logs manipulieren und über mehrere Systeme hinweg seine Herkunft verschleiern.

Aber vollständige Unsichtbarkeit verlangt, dass man jedes System kennt, das einen beobachtet.

Das tat er nicht.

Er hatte fast alle digitalen Spuren beseitigt.

Und dann stolperte ein Astronom über **75 Cent, die in einer Rechnung fehlten**.

## Quellen und Beleglage

- [Wikipedia, „The Cuckoo's Egg“](https://en.wikipedia.org/wiki/The_Cuckoo%27s_Egg), genutzt für Ablauf, technische Eckpunkte und die Zusammenfassung von Stolls eigener Darstellung.
- Clifford Stoll, *The Cuckoo's Egg* (1989), ist die zentrale Teilnehmerquelle für viele operative Details der Überwachung, die improvisierten Drucker-Logs und den aufgebauten Köder. Solche Szenen werden deshalb als Stolls Darstellung behandelt und nicht so, als wären sie von einer neutralen Kamera aufgezeichnet worden.
