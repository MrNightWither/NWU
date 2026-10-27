# Stream-PC

Stand: 27.10.2026

| Komponente | Details |
|---|---|
| CPU | AMD Ryzen 5 3400G, 4 Kerne / 8 Threads, bis 3,7 GHz |
| Grafik | AMD Radeon RX Vega 11 (in der CPU integriert, ca. 2 GB VRAM). Keine separate Grafikkarte. |
| Mainboard | ASUS PRIME A320M-K |
| RAM | 16 GB (2 × 8 GB G.Skill F4-3000C16-8GISB) |
| SSD | Kingston SA2000M8 (500 GB, NVMe) |
| Festplatte | Seagate ST2000DL003 (2 TB, HDD) |
| USB-Stick | General UDisk (7 GB) |
| BIOS | AMI, Version 6254 |
| Betriebssystem | Windows 10 Home |

## Offene Punkte

- [ ] **RAM-Takt:** Die Riegel sind für 3000 MHz ausgelegt, laufen aber nur mit 2133 MHz.
      Im BIOS XMP/DOCP aktivieren, dann laufen sie mit vollem Takt. Bringt vor allem bei
      der integrierten Grafik spürbar mehr Leistung.

## Was das für Projekte heißt

- Keine separate Grafikkarte: Overlays (vor allem `NWU-Avatars`) sparsam halten und auf
  diesem PC testen. Der Performance-Test aus `NWU-Avatars` (Paket 0) ist noch offen.
