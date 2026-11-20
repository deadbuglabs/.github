```
 ____  _____    _    ____  ____  _   _  ____
|   \|  ___|  /_\  |   \|  _ \| | | |/ ___|
| |) |  __|  / _ \ | |) |  _ \| |_| | |  _
|___/|_____|/_/ \_\|___/|____/ \___/ \___|
              L  A  B  S
       D34DBUG L4BS // signal from the salvage pile
```

# Deadbug Labs

**IMP-1** — a portable hardware exploration device. No
commercial dev kits. The prototype was built from salvaged electronics —
donor boards, a salvaged shell, and new silicon only where salvage can't
go. Boards you buy are fabricated new. ESP32-S3 brain,
ST25R3916B NFC front-end, CC1101 Sub-GHz radio, a 172×320 colour display,
socketed SPI flash with a physical write-protect lock, and 25.9 Wh of 18650
cells in a multi-board stack — designed end-to-end on a phone.

Deadbug Labs is a board company: open-platform boards for DIY builders.
Cases are optional accessories; assembled devices are the done-for-you
option.

## > status

`// 2026-11-19` — Firmware: clean build, 0 errors / 0 warnings, 12 tools.
Boards: main board v10 routing — braid re-lay pass complete (23 → 20
unconnected nets, 0 clearance violations, 0 shorts); NFC board DRC-clean,
IR board routing done. Gate 3 (PCB integrity) has not passed yet: the 20
remaining nets are sealed at placement level, and a targeted hand
micro-work pass is next. Nothing fabricated yet.

Sponsorship: PCBWay has granted Deadbug Labs a USD 30 3D-print credit
(no expiry; it can split across two orders). It is held until the boards
are fabricated and fit-checked.

## > new: IMP-VISION

AI smart glasses — glasses + phone, no hub. The companion app v0 is built
and running on a phone: a model picker over a 1,242-model Hugging Face
catalog (Eyes / Brain / Ears / Voice), ready-made Light / Balanced / Max
model sets, and questions answered by a local model on the phone. Primary
lineup: the Qwen model family across all four roles. A Deadbug Labs house
model is planned — a fine-tuned Brain that ships only after an eval
harness and five quality gates are in place.

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
