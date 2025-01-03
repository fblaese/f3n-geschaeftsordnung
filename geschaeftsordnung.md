# Geschäftsordnung des Vorstandes des F3 Netze e.V.

## Präambel
Diese Geschäftsordnung regelt die Arbeit des Vorstandes des F3 Netze e.V.

Sie ist nicht abschließend, bindet die Vorstandsmitglieder jedoch als Sollvorschrift. Bei Beschlussfassungen mit Wirkungen gegenüber Dritten ist darauf zu achten, dass die satzungsgemäßen Anforderungen an Beschlüsse und der Regelungen dieser Geschäftsordnung (GOV) eingehalten werden.

## 1. Aufgabenverteilung
1. Der erste Vorsitzende ist in enger Abstimmung mit dem zweiten Vorsitzenden für die allgemeine Geschäftsführung, die Einberufung des Vorstandes und die Leitung der Vorstandssitzungen zuständig. Grundsätzlich repräsentieren die Vorsitzenden den Verein nach außen.
2. Der erste Vorsitzende wird gegebenenfalls durch den zweiten Vorsitzenden vertreten.
3. Der Schatzmeister und ggf. der stellvertretende Schatzmeister sind für die Buchhaltung, das Inventar, die Bedienung und den Einzug von Forderungen sowie für die Vorbereitung steuerlicher Erklärungen zuständig.
4. Sonstige Aufgaben des Vorstandes können nach Bedarf und Eignung intern durch Beschluss delegiert werden.
    1. Delegationen von Aufgaben sollen in einer jeweils aktuellen Liste im Protokoll der Vorstandssitzungen aufgeführt werden.

## 2. Vorstandssitzungen
1. Die Vorstandssitzungen sind öffentlich
2. Vertrauliche Themen werden in einem geschlossenen Teil besprochen
3. Die Sitzungen des Vorstandes können in persönlicher Gegenwart der beteiligten Vorstandsmitglieder oder durch Nutzung von Nahezuechtzeitkommunikationsmitteln abgehalten werden. Sie sollen möglichst frühzeitig angekündigt werden bzw. regelmäßig stattfinden.
4. Die (nicht abschließende) Tagesordnung soll etwa 3 Tage vorher durch den ersten oder zweiten Vorsitzenden mitgliederöffentlich bekannt gemacht werden.
5. Wenn Vorstände nicht anwesend sein können, sollen die Vorstände so früh wie möglich der Sitzung absagen und den aktuellen Stand ihrer Tätigkeiten/Arbeitspaketen vorstandsöffentlich bekannt machen.
6. Über die Vertraulichkeit von Vorstandssitzungen wird jeweils am Ende einer Sitzung abgestimmt.

## 3. Protokolle
1. Über die Sitzungen ist mindestens ein Ergebnisprotokoll zu fertigen.
2. Das Protokoll ist von dem Protokollführer zu unterschreiben oder zu signieren. Die Signatur ist spätestens im Laufe der nächsten Sitzung zu kontrollieren.
3. Soweit das Protokoll unmittelbar rechtliche Außenwirkungen entfalten soll, gelten für die Form die allgemeinen Rechtsvorschriften, soweit diese strengere Anforderungen stellen.
4. Die Protokolle sind in der allgemeinen Ablage des Vereins (https://oc.f3netze.de/) als PDF mit dem Dateinamen `YYYY-MM-TT_"inhaltliche Erörterung".pdf` ggfs. einschließlich Signatur abzulegen.
    1. Nicht vertrauliche Protokolle werden unter `Vorstand/Protokolle` gespeichert. Dieser Ordner wird den Vereinsmitgliedern zugänglich gemacht
    2. Protokolle mit vertraulichen inhalten werden getrennt unter `Vorstand/Protokolle_vertraulich` gespeichert. Ein um die vertraulichen Inhalte gekürztes Protokoll wird mitgliederzugänglich unter `Vorstand/Protokolle` gespeichert.

## 4. Beschlüsse
1. Beschlüsse werden mit einfacher Mehrheit der inhaltlich abgegebenen Ja/Nein Stimmen gefasst.
2. Bei Beschlussfassungen in Sitzungen ist das Ergebnis zu protokollieren.
3. Beschlüsse können durch Umlauf gefasst werden. Dabei ist sicherzustellen, dass alle Vorstandsmitglieder die Möglichkeit zur Äußerung und Stimmabgabe hatten. Die Umlaufzeit soll 24 Stunden bis 7 Tage betragen. Für die Wirksamkeit eines Beschlusses im Umlaufverfahren genügt es, dass die Annahmebedingung erreicht ist.
4. Die Stimmabgabe ist zu protokollieren. Diese soll in Textform erfolgen, bevorzugt signiert. Die abgegebenen Stimmen sind in einem Unterordner "Beschlüsse" des im Abschnitt Protokolle gefassten Verzeichnisses abzulegen, gekennzeichnet mit Datum und abstrahiertem Inhalt des Beschlusses.

## 5. Signaturen
1. Signaturen erfolgen mittels OpenPGP.
2. Die öffentlichen Schlüssel der Vorstandsmitglieder sind untereinander bekannt zu machen und sollen wechselseitig nach Identitätsfeststellung signiert werden.
3. Folgende GPG Befehle sollen zur Signaturerzeugung verwendet werden:
    1. Signatur anlegen: `gpg --output <filename>.sig --detach-sign <filename>`
    2. Signatur prüfen: `gpg --verify <filename>.sig <filename>`
4. Die Signaturen werden neben der signierten Datei abgelegt. Bei mehr als einer Signatur wird aufsteigend nummeriert: .sig, .sig.2, .sig.3, ..

## 6. Datenhaltung
1. Die unter https://oc.f3netze.de/ gespeicherten Daten sind regelmäßig räumlich getrennt vom Server zu sichern.
