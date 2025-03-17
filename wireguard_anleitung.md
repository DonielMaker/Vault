---
id: 1742239347-CSVB
aliases:
  - wireguard_anleitung
tags: []
---

# wireguard_anleitung

## Installation

- Kommandozeile öffnen
- Den Kommand `> winget install wireguard` eingeben
![[./Images/wireguard_winget_install.png]]
- Ausführen lassen ggf. mit yes oder y zustimmen
- Anschließend `NAME.conf` herunterladen (von mir)
- Das Programm **wireguard** über windows-taste oder anders öffnen
![[./Images/wireguard_öffnen.png]]
- Entweder in der mitte oder unten links auf **Import Tunnel** oder **Add Tunnel** klicken
![[./Images/wireguard_add_tunnel.png]]
- `NAME.conf` als Datei auswählen
- Anschließend auf **activate** drücken
![[./Images/wireguard_activate.png]]

## Fehlerbehebung

- **wireguard** öffnen
![[./Images/wireguard_ddns.png]]
- Auf `Endpoint` ip schauen
- Einmal **Deactivate** und **Activate** drücken
- Schauen ob sich `Endpoint` geändert hat
- Ansonsten mir bescheid sagen
