# Wochenbericht 10.09.26

1. Ich habe heute nach einem Video, das sich unserer Diplomarbeit eignet gesucht, gefunden und angesehen. 
2. Den Link zum Video habe ich dem Profesoor Wörndl über Outlook gesendet. 
3. Nichtsdestotrotz sende ich ihn hier auch einmal rein. 
4. https://www.youtube.com/watch?v=x7xpsx6dfj8

# Wochenbericht – 17.09.2026

Heute habe ich mich über das **ABA-Portal** mit **ID Austria** angemeldet und weitere Details zu meiner Diplomarbeit ergänzt.

Dabei habe ich folgende Punkte ausgearbeitet bzw. eingetragen:

1. **Themenstellung**

   * Linux-Server aufsetzen
   * Funkhardware integrieren
   * Mikrocontroller programmieren

2. **Ausgangslage**

   * Beschreibung der aktuellen Situation und der technischen Voraussetzungen des Projekts.

3. **Untersuchungsanliegen der individuellen Themenstellungen**

   * Festlegung der Fragestellungen und technischen Bereiche, die im Rahmen meiner individuellen Aufgaben untersucht werden.

4. **Zielsetzung**

   * Definition der Ziele, die mit der Diplomarbeit erreicht werden sollen.

5. **Geplantes Ergebnis der individuellen Themenstellungen**

   * Beschreibung der erwarteten Ergebnisse meiner technischen Aufgabenbereiche.

6. **Meilensteine**

   * Festlegung von insgesamt **fünf Meilensteinen** für die Planung und Umsetzung der Diplomarbeit.
  
# Wochenbericht - 24.09.2026

## Tätigkeiten

1. Ich habe nach einem geeigneten Rechner gesucht, der als Linux-Server für unsere Diplomarbeit verwendet werden kann.
2. Anschließend habe ich den Rechner mit Strom versorgt und an einen alten Monitor angeschlossen.
3. Danach habe ich die Ubuntu-ISO-Datei heruntergeladen und auf einen USB-Stick geflasht, um ein bootfähiges Installationsmedium zu erstellen.
4. Abschließend habe ich den vorbereiteten USB-Stick in den Rechner gesteckt, um die Installation von Ubuntu vorzubereiten.

## Ergebnis

Der Rechner wurde angeschlossen und der bootfähige USB-Stick erfolgreich vorbereitet. Damit sind die Voraussetzungen für die Installation von Ubuntu geschaffen.

## Nächste Schritte

- Ubuntu auf dem Rechner installieren.
- Die grundlegende Konfiguration des Linux-Servers durchführen.
- Die Netzwerkverbindung einrichten.
  
# Wochenbericht – 08.10.2026

## Ubuntu Desktop und Ubuntu Server

Heute habe ich Ubuntu Desktop erfolgreich auf dem Linux-Rechner installiert und die Internetverbindung über Firefox getestet.

Anschließend habe ich festgestellt, dass Ubuntu Server ohne grafische Oberfläche (Headless) für unsere Diplomarbeit besser geeignet ist.

Deshalb habe ich die Ubuntu-Server-ISO heruntergeladen und mit **Rufus** erneut auf den USB-Stick geflasht. Dafür habe ich in Rufus den USB-Stick und die ISO-Datei ausgewählt und den Flash-Vorgang gestartet.

Danach habe ich den Linux-Rechner erneut vom USB-Stick gebootet, die notwendigen Einstellungen wie Sprache, Tastatur, Netzwerk und Installationsart vorgenommen und mit der **Installation von Ubuntu Server** begonnen.

# Wochenbericht – 15.10.2026

## Ubuntu Server einrichten und Home Assistant vorbereiten

Heute habe ich mich mit der Installation und Konfiguration vom Ubuntu Server (headless) beschäftigt.

Zuerst habe ich den Rechner über den geflashten USB-Stick gestartet und die Installation von Ubuntu Server ohne grafische Benutzeroberfläche (Headless) begonnen. Dabei habe ich die notwenidgen Einstellungen vorgenommen.

- Deutsche Sprache und Tastaturbelegung ausgewählt.
- Die normale Ubuntu-Server-Installation ausgewählt.
- Die LAN-Netzwerkverbindung überprüft und eine IP-Adresse über DHCP erhalten.
- Die Proxy-Einstellungen und Ubuntu-Paketquellen überprüft.
- Die interne BIWIN SSD mit ungefähr 15 GB als Installationslaufwerk ausgewählt und die Partitionierung konfiguriert.
- Ein Benutzerkonto für die spätere Anmeldung eingerichtet.
- Installation des OpenSSH-Servers ausgewählt, damit der Rechner später über das Netzwerk verwaltet werden kann.
- Auf zusätzliche Softwarepakete verzichtet, um Speicherplatz zu sparen.

Während der Installation trat ein Fehler auf, nach Nachfrage hat mich der Professor Wörndl unterstützt und wir  haben den Fehler beseitigt und somit den Server fertiggestellt.
Danach habe ich den Professor Zatl danach gefragt, die DHCP Adresse zu fixieren, was auch geklappt hat.

Anschließend habe ich mich über die Installation von **Home Assistant auf Ubuntu Server** informiert. Dabei habe ich die verschiedenen Installationsmethoden untersucht und erfahren, dass Home Assistant als Docker-Container betrieben werden kann, ohne ein eigenes Betriebssystem oder eine virtuelle Maschine installieren zu müssen.

## Ergebnis und nächste Schritte

Ich möchte Home Assistant auf Ubuntu Server installieren und über die Weboberfläche aufrufen. Langfristig soll der Server für die Kommunikation mit dem ESP32-C6 über Thread verwendet werden.
