---
title: Router einrichten
layout: page
sub_menu: true
top_url: /mitmachen/
sub_weight: 4
permalink: /mitmachen/router-einrichten/
---


### Den Router anschließen


1. Lade das passende Freifunk Firmware-Image für deinen Router [von unserer Seite](http://update.freifunk-darmstadt.de/) herunter.
2. Verbinde einen der gelben LAN-Anschlüsse des Routers mit einem Netzwerkkabel mit deinem Computer.
3. Dein Computer erhält automatisch eine IP-Adresse via DHCP.

### Installiere das Freifunk-Image


1. Öffne das Web-Interface deines Routers in deinem Browser.
2. Folge den Anweisungen im Handbuch deines Routers um die Firmware upzudaten.
3. Nutze das von der Freifunk-Website heruntergeladene Firmware-Image.
4. Warte bis der Router wieder gestartet ist.

### Konfigurationsmodus

Nach dem Neustart solltest du eine neue IP-Adresse zugwiesen bekommen haben. Der Konfigurationsmodus ist nun unter http://192.168.1.1 in deinem Browser erreichbar.

### Den Router konfigurieren


1. Aktiviere die Option `Firmware automatisch aktualisieren`.
2. Aktiviere die Option `Mesh-VPN aktivieren` / `Internet-Verbindung (Mesh-VPN)`.
3. Füge GPS-Koordinaten des Standorts ein, z.B. von [http://map.freifunk-darmstadt.de](http://map.freifunk-darmstadt.de) (klicke auf *Koordinaten beim nächsten Klick anzeigen*).
4. Gib deine E-Mail Adresse als Kontaktmöglichkeit an. Deine Adresse wird zu nichts anderem als zur zweckmäßigen Kontaktaufnahme genutzt. Es erfolgt niemals eine Weitergabe außerhalb des Freifunk Darmstadt Projektes.
5. Klicke auf `Speichern und Neustarten`. Nun wird der Browser den von dir gewählten Namen erneut anzeigen, sowie seinen Schlüssel für den sicheren VPN-Zugang:  
	> #node-name 
	> key "node-key";
	
Beide Zeilen sendest du bitte per E-Mail an [keys@freifunk-darmstadt.de](mailto:keys@freifunk-darmstadt.de).
    
Dein Schlüssel wird nun zeitnah eingetragen, woraufhin du eine Rückmeldung erhältst.

### Den Router aufstellen
Als Standort empfehlen sich Fenster, Balkone oder Dächer. Je näher er der Außenwelt ist, desto wahrscheinlicher ist es, dass er für Passanten erreichbar ist und sich mit anderen Routern verbindet um das sogenannte Mesh zu bilden.


### Verbinde den Router mit dem Netzwerk

Wenn du deinen Internetzugang zur Verfügung stellen möchtest, verbinde jetzt den blauen WAN-Anschluss von deinem Freifunk-Router mit deinem Heim-Router. Andernfalls bist du auf andere Freifunker in der Nähe angewiesen um eine Verbindung zum Freifunk-Netzwerk und ins Internet herzustellen.

### Fertig

Super, du hast es geschafft. Dein Freifunk-Node funktioniert jetzt und sollte, wenn du GPS Koordinaten angegeben hast, in Kürze auf der [Karte](http://map.freifunk-darmstadt.de/) erscheinen.
