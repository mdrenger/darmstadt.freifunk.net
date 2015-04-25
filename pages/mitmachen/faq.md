---
title: Häufige Fragen
layout: page
sub_menu: true
top_url: /mitmachen/
sub_weight: 6
permalink: /mitmachen/faq/
---

### Wo stehen schon Freifunk-Router?

Schau mal auf der [Netzkarte](../../zugangspunkte/) nach. Wenn es bei dir noch keinen Freifunk-Router in der Nachbarschaft gibt, dann sei die oder der Erste!

### Warum ist das alles kostenlos? Wo ist der Haken?

Freifunk ist eine gemeinschaftliche Bewegung, die einen freien Netzzugang als gesellschaftlichen Grundstein sieht. Wir möchten zudem den derzeitigen rechtlichen (Störerhaftung) sowie datenschutzrechtlichen (Kundendaten sammeln) Problematiken aus dem Weg gehen. Die Infrastruktur wird ausschließlich über Spenden finanziert.

### Benötige ich einen Router für 2,4 GHz oder 5 GHz?

Jedes Endgerät heutzutage funkt mindestens auf dem 2,4 GHz Band, modernere Modelle können außerdem das 5 GHz Band nutzen, auf dem, wenn nicht allzu viel Sichtbehinderung vorliegt, höhere Datenraten erreicht werden können.

Beachte: Damit sich ein Freifunk-Router mit einem anderen Freifunk-Router über WLAN verbinden kann, müssen beide Router im gleichen Frequenzband (2,4 GHz oder 5 GHz) arbeiten.

### Können mehrere Freifunk-Router an einem Ort miteinander verbunden werden?

Mehrere Freifunk-Router können sowohl über Funk meshen, als auch über den WAN-Port. Hierzu gibt es die Mesh-on-WAN-Funktion, welche sich in den Experteneinstellungen aktivieren lässt. Natürlich können die Router auch völlig unabhängig voneinander eine Verbindung zum Rest der Freifunk-Wolke herstellen.

### Kann ich den Freifunk-Router auch über ein existierendes privates WLAN anbinden?

Dies ist aus verschiedenen Gründen mit der Standard-Freifunk-Firmware nicht möglich:

 - Das im Router verbaute WLAN-Modul kann meist nur auf einer Frequenz gleichzeitig funken. Somit wäre allein technisch eine Verbindung nur dann möglich, wenn das Uplink-WLAN auf der gleichen Frequenz wie Freifunk sendet.
 - In diesem Fall würde die "Airtime" (also die Zeit, die der Funkkanal belastet wird) doppelt beansprucht, zum Senden im Freifunk-Netz und zum Weiterreichen ins Uplink-WLAN.
 - Zwei WLAN-Radios an einem Freifunkrouter könnten einen Uplink theoretisch auch auf einem anderen Kanal ermöglichen, dies erfordert jedoch manuelle Konfiguration, welche bei aktivem Autoupdater kaputt gehen könnte.
 - Ein USB-WLAN-Stick, welcher das 2. Radio bereitstellen könnte, kostet auch ~15€, ungefähr so viel wie schon ein kleiner vollständiger Freifunk-Router (TP-Link WR841N).

Unsere Empfehlung wäre daher, einen Freifunk-Router an der Quelle hinzustellen (dort, wo es ein Netzwerkkabel gibt), und am zweiten Standort einen zweiten Freifunk-Router, welcher mit dem ersten meshen würde und so den Zugang zum Rest des Netzes bereitstellt. Diese Lösung ist auch updatesicher und erfordert keine manuelle Konfiguration.
