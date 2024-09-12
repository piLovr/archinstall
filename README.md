Installing Arch: [Installing Arch](https://wiki.archlinux.org/title/Installation_guide)

Vorbereiten:
===========

- GGF in Linux die Partition verkleinern (Datentraegerverwaltung)
- Herunterladen: [Download Seite](https://archlinux.org/download/) | [Direkter Download](https://geo.mirror.pkgbuild.com/iso/2024.09.01/)
- Bootstick erstellen

Mit Wlan verbinden:
==========
`iwctl`

Netzwerk module anzeigen (Wlan, lan) : `device List`

Netzwerke anzeigen (wlan0 ggf. durch device ersetzen) : `station wlan0 get-networks`

Verbinden: `station wlan0 connect` *netzwerkname*

Wenn verbunden, *Strg+C*

Verbindung testen: `ping 3 google.com`

Arch Installieren:
===========

