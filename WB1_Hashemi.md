# Wochenbereicht 10.09.26

Ich habe mich heute mit dem Thema Matter befasst, da es ein esseentielles Teil unserer Diplomarbeit ist.
Unten habe ich dazu eine kurz Zusammenfassung geschrieben mit meinen Notizen

1. Was ist Matter?

        Matter ist ein herstellerübergreifender Kommunikationsstandard für Smart-Home-Geräte. Er fungiert wie ein Übersetzer, 
        damit Geräte verschiedener Marken problemlos miteinander funktionieren und über eine gemeinsame App oder Sprachassistenten gesteuert werden können.
        Entwickelt wurde der Standard von Branchenriesen wie Apple, Google, Amazon und Samsung, um die Zukunftssicherheit und
        Kompatibilität im Smart Home zu gewährleisten.

2. Was ist Matter nicht?
   
        Es ist weder ein physisches Produkt noch ein neues Betriebssystem, das installiert werden muss.
        Matter ist auch kein eigener Funkstandard, sondern ein Anwendungsprotokoll.

4. Welche Funkstandards werden genutzt?
    Da Matter selbst kein Funksystem ist, greift es auf bestehende Standards zurück:
        - Wi-Fi: Für Geräte mit hohem Datenbedarf (z. B. Kameras, Lautsprecher).
        - Thread: Für kleine, energieeffiziente Geräte (z. B. Glühbirnen, Sensoren).
        - Ethernet: Für kabelgebundene Geräte wie Smart-Home-Hubs.
        - Bluetooth: Hauptsächlich für die schnelle und einfache Ersteinrichtung.
        Ältere Z-Wave- und Zigbee-Geräte können zudem über entsprechende Hubs in ein Matter-Netzwerk eingebunden werden.

# Weekly Report – Hardwareentwicklung 17.09.2026

Projekt: SmartDevice Diplomarbeit
Durchgeführte Arbeiten
In dieser Woche stand die Planung der Hardware und der Gehäuse für das SmartDevice-System im Mittelpunkt.
Für das Projekt wurden insgesamt drei getrennte Gehäuse vorgesehen:
1. Funkstation / Basisstation
   - Aufnahme für einen XIAO ESP32-C6
   - USB-C-Anschluss soll von außen erreichbar sein
   - Platz für Statusanzeigen und weitere Elektronik
2. Fernbedienung
   - ebenfalls mit XIAO ESP32-C6
   - mehrere Taster zur Steuerung
   - Platz für Akku und USB-C-Anschluss
   - kompaktes, handliches Gehäuse
3. Lampeneinheit
   - XIAO ESP32-C6 als Mikrocontroller
   - Platz für die Elektronik zur Ansteuerung der Lampe
   - Kabeldurchführungen und ausreichend Platz für die Leistungsbauteile
Gehäuseentwicklung
Zusammen mit dem Lehrer entstand eine erste Skizze für das Gehäuse. Danach haben wir verschiedene Wege für die 3D-Konstruktion geprüft.
Dabei wurden unter anderem folgende Programme verglichen:
- Onshape
- FreeCAD
- Fusion 360
- Tinkercad
Weil es bei der Anmeldung bei Onshape Probleme gab, wählten wir FreeCAD als mögliche Alternative. FreeCAD passt gut zum Projekt, weil man damit technische Gehäuse mit genauen Maßen erstellen und STEP-Dateien bearbeiten kann.
Ein erster digitaler Prototyp für das Gehäuse der Fernbedienung ist schon fertig. Dieser enthält zum Beispiel:
- Unterteil und Deckel
- Ausschnitt für USB-C
- vier Tasteröffnungen
- Befestigungspunkte
- Aufnahme für den XIAO ESP32-C6
Die genauen Maße muss man später noch an die tatsächlich verwendeten Taster, den Akku und andere Bauteile anpassen.
Erkenntnisse
Bei der Planung stellte sich heraus, dass die Gehäuse so einfach und praktisch wie möglich für den 3D-Druck gebaut werden müssen. Besonders wichtig sind dabei:
- ausreichende Wandstärke
- gut erreichbarer USB-C-Anschluss
- genügend Platz für Kabel und Elektronik
- stabile Befestigung des ESP32-C6
- einfache Montage durch Deckel und Schrauben

# Weekly Report – 3D-Modellierung und Softwareauswahl 27.09.26
Woche: letzte Woche
Projekt: SmartDevice Diplomarbeit
Durchgeführte Arbeiten
In der letzten Woche habe ich mich hauptsächlich mit der 3D-Modellierung und der Vorbereitung der Gehäuse für den 3D-Druck beschäftigt.
Zuerst habe ich verschiedene Programme und Webseiten verglichen, mit denen sich die Gehäuse für die einzelnen SmartDevice-Komponenten erstellen lassen. Dabei habe ich besonders darauf geachtet, welche Programme einfach zu bedienen, kostenlos oder günstig und für technische 3D-Modelle geeignet sind.
Ich habe mich unter anderem mit folgenden Programmen beschäftigt:
- Onshape
- FreeCAD
- Fusion 360
- Tinkercad
- SelfCAD
Dabei habe ich die verschiedenen Vor- und Nachteile verglichen. Wichtig war für mich vor allem, dass die Software leicht verständlich ist und Dateien wie STL oder STEP unterstützt, damit die Modelle später für den 3D-Druck verwendet werden können.
Anschließend habe ich mich mit SelfCAD näher beschäftigt, da es direkt im Browser verwendet werden kann und eine übersichtliche Benutzeroberfläche bietet. Dort habe ich begonnen, ein neues Projekt für die Fernbedienung mit dem XIAO ESP32-C6 anzulegen und die ersten 3D-Dateien vorzubereiten beziehungsweise zu importieren.
Erkenntnisse
Ich habe gelernt, dass für technische Gehäuse eine CAD-Software notwendig ist, mit der genaue Maße, Aussparungen und Befestigungen erstellt werden können. Außerdem habe ich mich mit den Dateiformaten STL und STEP beschäftigt und verstanden, dass STEP besser für die Bearbeitung geeignet ist, während STL häufig direkt für den 3D-Druck verwendet wird.

  
