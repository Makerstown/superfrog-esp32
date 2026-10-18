# Makerstown Superfrog Arcade Edition — ESP32-P4

**Versione 1.0.0 · Validata su hardware · 18 ottobre 2026**

Progetto Makerstown indipendente per il porting tecnico del gioco Amiga *Superfrog* (1993) su cabinet arcade **ESP32-P4**, con menu grafico e musica di avvio.

Due modalità operative, entrambe verificate dall'autore su hardware reale:

- **GIOCO DIRETTO** — avvio autonomo dal Disc 1, senza elaborare lo Story Disc.
- **STORIA COMPLETA** — riproduzione dell'introduzione originale e cambio automatico al Disc 1, fino al gameplay.

![Anteprima del menu Makerstown Arcade Edition](media/menu-preview.svg)

## Hardware

ESP32-P4 con display ST7701 MIPI, audio ES8311, joystick e pulsanti collegati direttamente ai GPIO. Il progetto utilizza emulazione 68000, chipset Amiga e gestione dei media Extended ADF.

## Stato e miglioramenti futuri

La v1.0.0 è la prima **milestone stabile approvata sull'ESP32-P4**. Rimane un difetto grafico noto: alcune fasi del lampeggio del personaggio, nate dalla cadenza PAL50, non sono rappresentate fedelmente dalla cattura ottimizzata a circa 25 fps. La correzione è rinviata a una futura manutenzione.

È prevista inoltre una **valutazione per ESP32-S3** come porting separato, senza presupporre che il firmware P4 sia compatibile. La cattura video USB/OBS rimane un'idea futura indipendente.

## Materiali e distribuzione

Questo repository è una **vetrina pubblica del progetto**. Non distribuisce il motore universale privato, immagini ADF, ROM, loader estratti dai dischi, firmware comprendenti contenuti commerciali o altri asset proprietari. Non costituisce una distribuzione del gioco né una pubblicazione open source del tool privato.

## Makerstown

- **Autore:** Massimiliano Palombo — Makerstown
- **HUB e diario:** https://www.makerstown.cloud/hub/
- **GitHub:** https://github.com/Makerstown
- **Social:** consultare i riferimenti ufficiali dal Makerstown HUB.
- *Superfrog*: Team17, 1993. Progetto indipendente e non affiliato.

[Note della release v1.0.0](docs/RELEASE_NOTES_v1.0.0.md) · [English README](README.md)
