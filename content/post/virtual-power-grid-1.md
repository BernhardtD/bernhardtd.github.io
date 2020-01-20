---
title: "Virtual Power Grid #1"
date: 2020-01-20T12:00:00+01:00
draft: true
authors: [
    "Daniel Bernhardt",
]
description: "Showcase the image gallery feature."
tags: [
    "solar",
    "innovation"
]
images: [
    "vpg-solar.jpg",
]
---
Ein virtuelles Stromnetz (engl. virtual power grid, VPG) kann ein Puzzle-Teil sein, um unseren Energiebedarf zunehmend aus regenerativen Energiequellen zu decken.

Der Gedanke des virtuellen Stromnetzes geht auf den des VPN ([virtual private network][1]) zurück.
Dabei wird eine bestehende Netzwerkverbindung genutzt, um eine Verbindung zwischen mehreren Netzwerken herzustellen ohne eigene physische Verbindung.
Übertragen auf ein Stromnetz heißt das, ich stelle eine virtuelle Verbindung zwischen mehreren Standorten her, um so z.B. Strom aus einer PV-Anlage von einem Standort
für Verbraucher eines ganz anderen Standortes bereitstellen zu können. Die beiden Standorte sind dabei mit dem öffentlichen Stromnetz verbunden.
Nun kann man dem Stromfluss keine zusätzlichen Informationen mitgeben, woher der Strom stammt oder für wen der Strom bestimmt ist. Daher ist das
virtuelle Stromnetz eine rein bilanzielles Konstrukt.

## Die eigene PV-Anlage
Photovoltaik-Anlagen wurden bisher bevorzugt auf Einfamilienhäusern errichtet, um den Strombedarf dieses Hauses durch die installierte PV-Leistung zu decken.
Dementsprechend sieht auch das Erneuerbare-Energien-Gesetz ([EEG 2017][2] einige Vorteile für diese Anlagen vor,
z.B. sind Anlagen für die Eigenversorgung mit einer Gesamtleistung von 10kWp von der Zahlung der EEG-Umlage befreit.
Das spart bereits 20% (2020: 6,756 ct/kWh) des sonst fälligen Strompreises:
{{< figure src="/images/strompreis_2019.jpg" >}}

Laut Statistischem Bundesamt leben jedoch nur ca. [35% aller Haushalte][3] in Ein- bzw. Zweifamilienhäuser. Diese Haushalte können unmittelbar
von einer PV-Analge auf dem hauseigenen Dach profitieren, vorausgesetzt die Dachflächen sind hierfür geeignet. Die Haushalte, die in
Eigentumswohnungen oder in Wohngebäuden mit 3 und mehr Wohnungen leben, können Aufgrund von unterschiedlichen Eigentumsverhältnissen (Gemeinschaftseigentum),
Größe und Lage des Daches keine PV-Anlage installieren.

## Dezentrale Erzeugung
Wie kann eine PV-Anlage für die Mehrheit der deutschen Haushalte zur Verfügung gestellt werden?
Indem man eine PV-Anlage gekauft, gemietet oder gepachtet werden kann und der erzeugte Strom unmittelbar mit dem Strom verrechnet wird, den man in seiner
Wohnung benötigt:
{{< figure src="/images/vpg.png" >}}
In diesem Bespiel erzeugt eine PV-Anlage 1.200 W. In der dazugehörigen Wohnung werden zum gleichen Zeitpunkt 2.000 W Leistung benötigt. Wären PV-Anlage
und Verbraucher auf dem gleichen Grundstück, würden zu diesem Zeitpunkt lediglich 800 W aus dem öffentlichen Netz bezogen werden müssen. Das Konzept des
virtuellen Stromnetzes greift genau diesen Punkt auf: alle erzeugten und benötigten Leistungen eines Betreibers werden saldiert.
Rein rechnerisch steht so die erzeugte Leistung für den Leistungsbedarf der Wohnung zur Verfügung.

## Standorte
Wenn nun kein eigenes Dach zur Verfügung steht, auf welchen Flächen soll nun eine PV-Anlage errichtet werden?
Ich persönlich finde, dass eine PV-Anlage auf jedem Dach mit südlicher Ausrichtung installiert werden sollte.
So sollte auch auf jedem geeigneten DDR Wohnungsblock eine Anlage errichtet und diese Kapazitäten an Mieter des Hauses vermietet werden.
Eine weitere Möglichkeit besteht darin, weitere Freiflächen-Anlagen zu errichten und Kapazitäten dieser Anlagen zu vermieten.

#### Kleingärten
In Deutschland gibt es rund 910.000 Kleingärten. Wir haben selbst einen Kleingarten in dem wir Obst und Gemüse anbauen...
Warum nicht auch die Dachfläche der Laube nutzen, um Strom für den eigenen Bedarf zu erzeugen?
Nach [Abs. 2, §3 Bundeskleingartengesetz (BKleingG)][4] darf eine Laube maximal 24 m² groß sein. Je nach Modulleistung kann davon
ausgegangen werden, dass 5 - 7 m² pro kWp benötigt werden. Daraus ergibt sich eine PV-Anlage mit einer Leistung von 3 bis 4,5 kWp.
Eine Leistung von 3 kWp sollte nach dem [Unabhängigkeitsrechner der HTW Berlin][5] ausreichen, um unseren jährlichen Energiebedarf von 2.000 kWh
zu 34% aus der eigenen PV-Anlage zu decken.

## Mehrwert
Welchen Mehrwert kann uns ein virtuelles Stromnetz bringen?

#### für den eigenen Haushalt
- **Kostenreduktion:** langfristig können Stromkosten durch die eigene PV-Anlage ohne Batteriespeicher gespart werden, für mich ca. 33% des Strombedarfs.
- **Transparenz:** die notwendigen intelligenter Zähler schaffen mehr Transparenz mithilfe von Apps und Webportalen in die Erzeugung und Verbräuche.
  So kann ich meinen Verbrauch optimieren und z.B. die Waschmachine zum Mittag starten, wenn die PV-Anlage Strom liefert.
- **Energie-Bewusstsein:** die Auseinandersetzung mit dem eigenen Strombedarf schafft ein tieferes Energie-Bewusstsein. Das hilft dabei, Energie dauerhaft
  zu einzusparen und die Erfahrungen und Erkenntnisse auch an unser Kinder weiterzugeben.

#### für die Gesellschaft
- **Schaffung von Kapazitäten:** wir wollen nicht nur unseren Strom aus erneuerbaren Energiequellen beziehen, sondern auch möglichst
  umweltfreundlich mobil sein. Dafür müssen Kapazitäten geschaffen werden, um unsere E-Autos mit Strom aus erneuerbaren Quellen zu speisen.
- **Forschung und Entwicklung:** neue Verfahren zur Speicherung und Umwandlung von Strom müssen entwickelt, erprobt und zur marktreife
  gebracht werden, um unseren erneuerbare Energiequellen effizienter zu nutzen.

## Fortsetzung folgt
Vielleicht lässt sich daraus etwas Großes entwickeln. Ein nächster Schritt wird die Betrachtung der Wirtschaftlichkeit sein.
Ich kann jetzt schon verraten, dass die Gesetzlage einige Hürden bereit hält...

## Links
- https://de.wikipedia.org/wiki/Virtual_Private_Network
- https://www.gesetze-im-internet.de/eeg_2014/
- https://www.destatis.de/DE/Themen/Gesellschaft-Umwelt/Einkommen-Konsum-Lebensbedingungen/Vermoegen-Schulden/Tabellen/haus-grundbbesitz-evs.html
- https://www.gesetze-im-internet.de/bkleingg/__3.html
- https://pvspeicher.htw-berlin.de/unabhaengigkeitsrechner

[1]: https://de.wikipedia.org/wiki/Virtual_Private_Network
[2]: https://www.gesetze-im-internet.de/eeg_2014/
[3]: https://www.destatis.de/DE/Themen/Gesellschaft-Umwelt/Einkommen-Konsum-Lebensbedingungen/Vermoegen-Schulden/Tabellen/haus-grundbbesitz-evs.html
[4]: https://www.gesetze-im-internet.de/bkleingg/__3.html
[5]: https://pvspeicher.htw-berlin.de/unabhaengigkeitsrechner
