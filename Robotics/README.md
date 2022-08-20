# Robotics

In den letzten Jahren ist das Thema Robotik (**Robotics**) immer populärer geworden. Die Programmierung von Roboter-Systemen wird immer zugänglicher und es hat einen besonderen Reiz, dass sich tatsächlich Dinge im wahrsten Sinne des Wortes "bewegen".

In diesem Jahr möchten wir Euch die Gelegenheit geben, dieses spannende Thema zu bearbeiten und Ideen zu entwickeln, die Ihr auf dem Hackathon verwirklichen könnt.

## Starter-Kits

Insbesondere der Hersteller Lego hat mit seinen [Mindstorm-Produkten](https://de.wikipedia.org/wiki/Lego_Mindstorms_NXT#Nachfolgesystem_Mindstorms_EV3) dafür gesorgt, dass der Zugang zu dieser Technologie einfacher wurde. Rund um diese Produkte hat sich ein ganzes "Ökosystem" an Erweiterungen, Sensoren, Programmiermodellen und Ideen entwickelt.

Um den Einstieg für den Hackathon zu vereinfachen und zu beschleunigen, haben wir uns dazu entschieden, mit dem "kleinen" Roboter-Set von Lego, dem [Lego Boost](https://www.lego.com/de-de/themes/boost), einzusteigen. Auch wenn die Mindstorm-Produkte noch mehr Möglichkeiten bieten, kann man bereits mit dem Lego Boost viele schöne Dinge "anstellen", da dieses Set bereits Motoren, Sensoren und eine farbige LED mitbringt, die sich programmieren und steuern lassen. So kann man unter anderem auch Farben und Licht-Intensität erkennen und darauf reagieren.

Diese Boost-Kits werden den interessierten Teilnehmern zur Verfügung gestellt; weitere Informationen dazu findet Ihr unten.

## Programmierung mit Python
Die Lego-Boosts lassen sich mittels einer App, die auf einem Tablet (oder Smartphone) installiert ist, nach Anleitung zusammenbauen und programmieren. Die "Programmierung" besteht in diesem Fall jedoch "nur" aus dem Zusammenschalten verschiedenster Bausteine, die Lego vorgibt. So ermöglicht Lego auch jüngeren Kindern den Einstieg in die Programmierung dieser Serie.

Da es beim Hackathon aber auch darum geht, Programmierkenntnisse zu erlernen und die bestmöglichen Ergebnisse zu erzielen, haben wir uns dazu entschlossen, Boost mit [Python](https://www.python.org/) zu programmieren.

Damit man bei der Programmierung mit Python nicht "bei Null" anfangen muss, greifen wir auf eine Bibliothek zurück, die als Open Source Komponente zur Verfügung steht. Mittels dieser Bibliothek kann man alle Komponenten des Boost-Systems mit Python bzw. MicroPython ansprechen.

## Erforderliche Hardware (wird den Teilnehmern zur Verfügung gestellt)
Um mit Lego Boost loslegen zu können, stellen wir interessierten Teilnehmern ein Lego-Boost-Kit zur Verfügung. Dieses Kit besteht zunächst einmal aus dem Lego Boost selbst, also den Lego-Bausteinen inkl. der Sensoren, Motoren usw. und dem sogenannten **Move Hub**, der als zentrale Steuereinheit für alle Lego-Boost-Projekte dient.

Um das Lego Boost Kit nicht über die (kostenlose) Lego Boost App auf dem Tablet programmieren zu müssen, braucht man weiterhin einen Computer (Laptop), der mittels [Bluetooth LE](https://de.wikipedia.org/wiki/Bluetooth_Low_Energy) eine Verbindung mit dem Move Hub aufbauen kann. Da viele Computer nicht über die entsprechende Schnittstelle verfügen, wird Euch dafür ein [USB Bluetooth Dongle](https://www.silabs.com/wireless/bluetooth/bluegiga-low-energy-legacy-modules/device.bled112) zur Verfügung gestellt, mit dem die Verbindung und Programmierung garantiert funktionieren wird, sowohl unter Windows als auch unter Linux.

## Vorbereitungen
Das von uns eingesetzte [Pybricks](https://pybricks.com/) benötigt im Prinzip nur einen Web Browser, der *Web Bluetooth Funktionalität* unterstützt. Diese sind **Google Chrome**, **Microsoft Edge** (aktuelle Version) bzw. **Chromium**, also Browser, die auf der Chromium-Engine basieren.

Bei der Verwendung unter Linux muss zusätzlich noch die Funktion *Experimental Web Platform features* unter `chrome://flags/`aktiviert werden, wie in der [Pybricks Installationsanleitung](https://pybricks.com/install/technic-boost-city/) beschrieben.

Viele Teilnehmer werden einen solchen Browser bereits installiert haben. Zusätzlich wird insbesondere **GIT** für die Versionsverwaltung Eurer Programme empfohlen. Die Installation in der Regel in wenigen Minuten erledigt und kann daher auch "vor Ort" bzw. zu Beginn des Hackathon erfolgen. Ohne die erforderliche Hardware (siehe oben) kann man als Teilnehmer sowieso noch nicht loslegen.

## Link-Sammlung
Hier noch ein paar weitere Links zum Thema, die man sich bei Interesse schon einmal ansehen kann, um sich auf die Programmierung des Lego Boost vorzubereiten:

* [Pybricks: Die MicroPython-Umgebung zur Boost-Programmierung](https://pybricks.com/)
* [Pybricks: Aktuelle (englische) Dokumentation](https://docs.pybricks.com/_/downloads/en/latest/pdf/)
* [Python Cheat Sheet](https://github.com/ehmatthes/pcc/releases/download/v1.0.0/beginners_python_cheat_sheet_pcc_all.pdf)
* [GIT für Windows](https://gitforwindows.org/)

Da Pybricks eine eigene "Entwicklungsumgebung" (im Browser) enthält, ist die separate Installation einer IDE, bspw. [Visual Studio Code](https://code.visualstudio.com/), nicht erforderlich. Wir empfehlen den Teilnehmern, dass sie ihren Programmcode in einer Versionsverwaltung wie **GIT** speichern.

## Änderungen im Vergleich zu 2021
Im Jahr 2021 hatten wir das Thema Robotics erstmalig im Angebot und haben dafür eine [andere Python-Bibliothek zur Boost-Programmierung](https://github.com/undera/pylgbst) verwendet. Diese Bibliothek funktioniert natürlich auch weiterhin und könnte als Alternative zum nun gewählten Pybricks verwendet werden. Allerdings hat sich Pybricks in unseren Tests als stabiler und verlässlicher erwiesen, weshalb wir 2022 auf Pybricks setzen. Daher ist auch keine weitere vorbereitende Installation erforderlich.
