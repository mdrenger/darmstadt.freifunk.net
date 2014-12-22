---
title: Firmware installieren
layout: page
permalink: /firmware-installieren/
---

Firmware installieren
=====================

Question: is it exactly like this for all router models? Besides, some users might have routers with other firmwares. Write something like "we assume that..." just in case.

1. Den Router anschließen
----------------------

1. Lade die passende Freifunk-Firmware für deinen Router [von unserer Seite](http://update.freifunk-darmstadt.de/) herunter.
2. Verbinde einen der gelben LAN-Anschlüsse des Routers mit einem Netzwerkkabel mit deinem Computer.
3.Dein Computer erhält automatisch eine IP-Adresse via DHCP.

2. Installiere die Freifunk-Firmware
--------------------------------

1. Öffne das Web-Interface ([http://192.168.0.1](http://192.168.0.1)) deines Routers in deinem Browser
2. Wenn du nach Zugangsdaten gefragt wirst, gib als Benutzername und Passwort jeweils "admin" ein
3. Öffne im linken Menü `system tools > firmware upgrade`
4. Wähle das heruntergeladene Firmware-image von deinem Rechner aus
5. Klicke auf `Upgrade` und warte, bis sich dein Router neugestartet hat.

3. Konfigurationsmodus
--------------------
Nach dem Neustart solltest du eine neue IP-Adresse zugwiesen bekommen haben. Der Konfigurationsmodus ist nun unter [http://192.168.1.1](http://192.168.1.1) in deinem Browser erreichbar.

4. Den Router konfigurieren
------------------------

1. Aktiviere die Option `Firmware automatisch aktualisieren`
2. Aktiviere die Option `Mesh-VPN aktivieren` / `Internet-Verbindung (Mesh-VPN)`
3. Füge GPS-Koordinaten des Standorts ein, z.B. von [http://map.freifunk-darmstadt.de](http://map.freifunk-darmstadt.de) (klicke auf *Koordinaten beim nächsten Klick anzeigen*)
4. Gib deine E-Mail Adresse als Kontaktmöglichkeit an. Deine Adresse wird zu nichts anderem als zur zweckmäßigen Kontaktaufnahme genutzt. Es erfolgt niemals eine Weitergabe außerhalb des Freifunk Darmstadt Projektes.
5. Klicke auf `Speichern und Neustarten`. Nun wird der Browser den von dir gewählten Namen erneut anzeigen, sowie seinen Schlüssel für den sicheren VPN-Zugang:
	> #node-name
	> key "node-key";
	
    Beide Zeilen sendest du bitte per E-Mail an [keys@freifunk-darmstadt.de](mailto:keys@freifunk-darmstadt.de).
    
Dein Schlüssel wird nun zeitnah eingetragen, woraufhin du eine Rückmeldung nach der Bearbeitung erhältst.

5. Verbinde den Router mit dem Internet (optional)
---------------------------------------------

Wenn du deinen Internetzugang zur Verfügung stellen möchtest, verbinde jetzt den blauen WAN-Anschluss von deinem Freifunk-Router mit deinem Heim-Router.

6. Fertig
--------
Super, du hast es geschafft. Dein Freifunk-Node funktioniert jetzt und sollte, wenn du GPS Koordinaten angegeben hast, in Kürze auf der [Karte](http://map.freifunk-darmstadt.de/) erscheinen.
