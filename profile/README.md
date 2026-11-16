```
 ____  _____    _    ____  ____  _   _  ____
|   \|  ___|  /_\  |   \|  _ \| | | |/ ___|
| |) |  __|  / _ \ | |) |  _ \| |_| | |  _
|___/|_____|/_/ \_\|___/|____/ \___/ \___|
              L  A  B  S
       D34DBUG L4BS // signal from the salvage pile
```

# Deadbug Labs

**IMP-1** — a Flipper-class portable hardware exploration device. No
commercial dev kits. The prototype was built from salvaged electronics —
donor boards, a salvaged shell, and new silicon only where salvage can't
go. Boards you buy are fabricated new. ESP32-S3 brain,
ST25R3916B NFC front-end, CC1101 Sub-GHz radio, a 172×320 colour display,
socketed SPI flash with a physical write-protect lock, and 25.9 Wh of 18650
cells in a multi-board stack — designed end-to-end on a phone.

## > status

`// 2026-11-16` — Firmware: clean build, 0 errors / 0 warnings, 12 tools.
Boards: in layout (main board in respin, NFC board in final routing, IR board
complete). Nothing fabricated yet — fabrication is gated on a clean
design-rule check.

## > links

- **Site:** https://deadbuglabs.github.io/
- **Firmware:** https://github.com/deadbuglabs/imp-1
- **Facebook:** https://www.facebook.com/profile.php?id=61591927232914

## > the tools

| Tool | Status |
|---|---|
| Sub-GHz | Real — FIFO capture; fine for OOK replay |
| NFC | Real — NTAG full; MIFARE Classic pending Crypto1 |
| IR | Real |
| BadUSB | Real |
| GPIO | Real |
| U2F | Compiles — host interop **unverified** |
| Archive | Real |
| Flash Lab | Real |
| Security Auto-Audit | Real — passive only (inventory + checklist) |
| RFID | Not fitted — stub; native on IMP-2 |
| iButton | Not fitted — stub; native on IMP-2 |
| 1-Wire | Not fitted — stub; native on IMP-2 |

Full detail lives on the [apps page](https://deadbuglabs.github.io/apps.html)
and in the firmware repo's build report.

---

Deadbug Labs

**Contact / orders:** imp-ai@muse.ai · [DeadbugLabs on Facebook](https://www.facebook.com/profile.php?id=61591927232914)
