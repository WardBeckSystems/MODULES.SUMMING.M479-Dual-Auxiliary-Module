# M479 Dual Auxiliary Module · Summing

Ward-Beck Systems M479, 1978|11. Wiki page: [M479 on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/PAGES/M479.html)

| Folder | What is in it | Files |
|---|---|---|
| [SCHEMATICS/](SCHEMATICS/) | electrical drawings: schematics, functional diagrams, component layouts, wiring | 28 |
| [MECHANICAL/](MECHANICAL/) | front panels, cover plates, metalwork, assemblies; the front panel as vectors | 6 |
| [PINOUTS/](PINOUTS/) | the RTO-144 connector: connection sheets, connector layouts, rear views | 11 |
| [MANUALS/](MANUALS/) | manuals, manual pages, price lists, brochures, documents | 125 |
| [PHOTOS/](PHOTOS/) | photographs of the module | 2 |
| [SOFTWARE/](SOFTWARE/) | program listings, firmware, the plugin | 1 |
| [KICAD/](KICAD/) | KiCad schematics traced from the drawings, the symbol, PCB projects | 11 |
| [OCR/](OCR/) | the note of every file: date, origin, title block, OCR text | 30 |

<!-- module data: tools/module_specs.py, tools/forum_quotes.py -->

**On the WBSps forum (2006|39 - 2014|47):** [14 topics](FORUM.md): what owners and technicians said about it.

## Specifications

From the technical data sheet: [1978 - M479 - Dual Auxiliary Module.pdf](MANUALS/1978%20-%20M479%20-%20Dual%20Auxiliary%20Module.pdf) page 5 (read by OCR; check against the page). As data: [`Specifications.json`](Specifications.json).

| | |
|---|---|
| **Gain** | 18 dB ±0.5 dB |
| **Frequency response** | ±0.25 dB from 30 Hz to 20 kHz. |
| **Noise** | 70 dB be ]ow +8 dBm nomina ] output level, (with 20 inputs connected to summing terminals). (20 Hz Lo 20 kHz) |
| **Harmonic distortion** | Less than 0.25% ThD from 30 Hz to 20 kHz at +18 dBm output or Tess Less than 0.05% at kHz at +18 dBm output |
| **Source impedances** | External: Summing: 600 ohms or Less baLanced 30,000 ohms; baLanced |
| **Input impedances** | Externa]: Summing: 60,000 ohms balanced. Less than 5 ohms |
| **Output impedances** |  |
| &nbsp;&nbsp;Main | Monitor: 150 ohms at Pins 11/12 and 15/16 300 ohms at pins 13/14 and 17/18 |
| **Load impedances** | Main: Monitor: 600 ohms balanced, 4K ohms minimum, baLanced |
| **Output level** | +8 dBm nomina 1 +24 dBm maximum (+4 dBm nomina 1 by interna] strapping) |
| **Channel separation** | Phasing: 70 dB from 30 Hz to 15 kHz. Low numbered input and output terminals are in phase |
| **Power requirements** | +25 volts dc, 35 MA nomina 1, 80 mAmaximum |
| **Dimensions** | 1 6 &quot; wide X 7&quot; high X 6.5&quot; deep. (41 MM X 178 mm X 165 mm) |

## Circuit description

From [1978 - M479 - Dual Auxiliary Module.pdf](MANUALS/1978%20-%20M479%20-%20Dual%20Auxiliary%20Module.pdf) pages 6-8 (read by OCR; check against the pages). As data: [`CircuitDescription.json`](CircuitDescription.json).

<details><summary>Read it</summary>

The M479 15 designed to receive the auxiliary output feeds originating from the WBS M470 and M473 input and submaster modules combine them and permit Teve 1 adjustment of the comb inea output mix. Two AUXILIARY outputs are provided per module Input and_Summing Amplifier The signa 1 originating from the externa] mixing network is applied to the SUMMING current nodes of the input amplifier via pins 1/2 of the module edge connector An EXTERNAL 60,000 ohm input is provided at pins 6/7 which maybe used for talkback or cue input feed This input i5 designed to operate from 0 dBm, 600 ohm source 21 and 22 with their associated components form the inputs umming preamp] i fier for channe] 1 The s igna ] from the preamplifier output is coupled through c6 to Rll, the level contro] Similarly, the SUMMING input for channel 2 appears at pins 3/4 and the EXTERNAL bridging input at pins 8 /9 73 and 24 form the preampli fier. R2Z is the level contro] for channe] 2. Qutput_Amplifier The channe] signa] is routed through switch SWl to the actively baLanced output amplifier comprising 25 26, Q1 through 04 and their associated components The MAIn output for channel appears at pins 11/12 of the module edge connector The nomina ] Teve] at this point 15 +8 dBm into 600 ohm Toad If +4 dBm nomina 1 output i$ required the shorting ink J1 Maybe removed to reduce the gain of the output amplifier by dB The MoniToRING output for channc 1 1 appearing at Pins 13/14 of the mo du Te connector is intended to Teed VU meter and the required inputs to the monitoring circuitry The Tatter should have 30k ohm bridging impedance or higher

**CIRCUII_DESCRIPIION**

Sn2 i5 Lhe output switch for channe] 2 27, 28 and Q5 through Q8 comprise the output amplifier The channe] 2 Main output appears at pins 15/16 and the MonITOR output at Pins 17/18 For +4 dBm operation, J2 maybe removed Power Supply_Decoupling Power supply decoup] ing i5 provided by CR9 CR10, R7I through R74 and C23 through C26 R73 and R74 decouple the supply voltage and reduce it to +18 volts to operate 21 through 28

</details>

<!-- /module data -->

## Mechanical

_Mechanical drawings: front panels, cover plates, metalwork and hardware (-03- drawings), AutoCAD files, each with its `(EXTRACTED).svg` vectors; `<module> - front panel.svg` is the front panel as vectors._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRTJtLTkxOWtUcFk/view?resourcekey=0-zKTSwmgoGO2WsBVf6MsgYw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRTJtLTkxOWtUcFk&resourcekey=0-zKTSwmgoGO2WsBVf6MsgYw" width="240" alt="1978 - M479 - 479-04-003 - DUAL AUXILIARY MODULE FRONT PANEL.jpg"></a><br><sub>1978|11 · 479-04-003 - DUAL AUXILIARY MODULE FRONT PANEL · <a href="MECHANICAL/1978%20-%20M479%20-%20479-04-003%20-%20DUAL%20AUXILIARY%20MODULE%20FRONT%20PANEL%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

## 3-D model

[`MECHANICAL/M479.stl`](MECHANICAL/M479.stl) (GitHub turns it in 3-D) · [view, change and generate it on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/2026/stl.html?m=M479)

- **Size:** 41 × 178 mm panel, 165 mm deep, 3.2 mm plate (TECHNICAL DATA: 1 6 " wide X 7" high X 6.5" deep. (41 MM X 178 mm X 165 mm))
- **From the drawing:** 9 holes and cut-outs, 0 knobs (front panel: `MECHANICAL/M479 - front panel.svg`)
- Made by `tools/module_models.py` (→ `MECHANICAL/M479.model.json`) and `tools/stl/make_stl.mjs` in [WBSps.ca](https://github.com/WardBeckSystems/WBSps.ca); the site makes the same STL from the same JSON.

## Schematics

_Electrical drawings: schematics (-02-), functional diagrams (-01-), component layouts (-06-), wiring (-09-), PCB files (.pcb .dsn), and beside each scan its `(EXTRACTED).svg`: the vectors traced from it._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKN3Bfa1A2Qk44T2s/view?resourcekey=0-eQtzlSlM2FMkJdysRTqAKw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKN3Bfa1A2Qk44T2s&resourcekey=0-eQtzlSlM2FMkJdysRTqAKw" width="240" alt="1978 - M479 - 479-01-001 - DUAL AUXILIARY MODULE FUNCTIONAL DIAGRAM.jpg"></a><br><sub>1978|11 · 479-01-001 - DUAL AUXILIARY MODULE FUNCTIONAL DIAGRAM · <a href="SCHEMATICS/1978%20-%20M479%20-%20479-01-001%20-%20DUAL%20AUXILIARY%20MODULE%20FUNCTIONAL%20DIAGRAM%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRFZzUC16bzBLUE0/view?resourcekey=0-E3PoddyBiGUC4cdL-KzaQQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRFZzUC16bzBLUE0&resourcekey=0-E3PoddyBiGUC4cdL-KzaQQ" width="240" alt="1978 - M479 - P15 - Schematic.jpg"></a><br><sub>1978|11 · P15 - Schematic · <a href="SCHEMATICS/1978%20-%20M479%20-%20P15%20-%20Schematic%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1dzQuhcHLqZHYuCyZf_ADrXlexs0zpLmo/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1dzQuhcHLqZHYuCyZf_ADrXlexs0zpLmo" width="240" alt="1992 - M479 - DOC - 920477-01-001 - OHMS SWTCHED SSUE REMSION FUTURE FUTURE.jpg"></a><br><sub>1992|25 · DOC - 920477-01-001 - OHMS SWTCHED SSUE REMSION FUTURE FUTURE · <a href="SCHEMATICS/1992%20-%20M479%20-%20DOC%20-%20920477-01-001%20-%20OHMS%20SWTCHED%20SSUE%20REMSION%20FUTURE%20FUTURE%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1dqPu6J43zNGBeDMsvZeY4CjtPV4IQksJ/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1dqPu6J43zNGBeDMsvZeY4CjtPV4IQksJ" width="240" alt="19xx - M479 - DOC - 479-02-001 - DUAL AUXILIARY MODULE SCHEMATIC.jpg"></a><br><sub>19xx - M479 - DOC - 479-02-001 - DUAL AUXILIARY MODULE SCHEMATIC · <a href="SCHEMATICS/19xx%20-%20M479%20-%20DOC%20-%20479-02-001%20-%20DUAL%20AUXILIARY%20MODULE%20SCHEMATIC%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/109KQyA72uuIDv0gHiqS2qh5Zof3KCBMs/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=109KQyA72uuIDv0gHiqS2qh5Zof3KCBMs" width="240" alt="2017 - M479 - DOC - 920170-01-001 - SWTCHED DIRECT MONITOR OUTPUTS DDZME.jpg"></a><br><sub>2017|50 · DOC - 920170-01-001 - SWTCHED DIRECT MONITOR OUTPUTS DDZME · <a href="SCHEMATICS/2017%20-%20M479%20-%20DOC%20-%20920170-01-001%20-%20SWTCHED%20DIRECT%20MONITOR%20OUTPUTS%20DDZME%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

Not on Google Drive yet: `1982 - 479-06-001 - DUAL AUXILIARY MODULE LAYOUT - DRN GEB - ENG GEB - ISS 4.jpg`

## Pinouts

_Pinouts: the RTO-144 edge connector (connection sheets, connector layouts and rear views, strapping), and the pinout / connections drawings made from them. The module root `RTO.json` lists every contact._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKY19pQkl5NlliZEE/view?resourcekey=0-jOGmoCmG0w_p3zZ8oxRmsg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKY19pQkl5NlliZEE&resourcekey=0-jOGmoCmG0w_p3zZ8oxRmsg" width="240" alt="1978 - M479 - P17 - Pin Out.jpg"></a><br><sub>1978|11 · P17 - Pin Out · <a href="PINOUTS/1978%20-%20M479%20-%20P17%20-%20Pin%20Out%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

Not on Google Drive yet: `M479 - RTO-144 Connections.pdf`

## RTO-144 pinout

Read from 1 pinout picture (each its own `.pinout.json` beside it); the RTO-144 sheet agrees on 11 of 11 contacts. Every contact, with where it was read: [`RTO.json`](RTO.json). How a picture becomes this table: [the pinout decision tree](https://github.com/WardBeckSystems/WBSps.ca/blob/main/2026/Engineering/PINOUTS.md).

| Pin | Signal | Kind | Port | Confidence |
|---|---|---|---|---|
| 1 | SUMMING INPUT 1 | in | SUMMING INPUT 1 | high |
| 2 | SUMMING INPUT 1 | in | SUMMING INPUT 1 | high |
| 3 | SUMMING INPUT 2 | in | SUMMING INPUT 2 | high |
| 4 | SUMMING INPUT 2 | in | SUMMING INPUT 2 | high |
| 5 | SHIELD (INPUTS 1-4) | shield | shield | high |
| 6 | EXTERNAL INPUT 1 | in | EXTERNAL INPUT 1 | high |
| 7 | EXTERNAL INPUT 1 | in | EXTERNAL INPUT 1 | high |
| 8 | EXTERNAL INPUT 2 | in | EXTERNAL INPUT 2 | high |
| 9 | EXTERNAL INPUT 2 | in | EXTERNAL INPUT 2 | high |
| 10 | SHIELD (INPUTS 6-9) | shield | shield | high |
| 11 | AUX OUTPUT 1 | out | AUX OUTPUT 1 | high |
| 12 | AUX OUTPUT 1 | out | AUX OUTPUT 1 | high |
| 13 | MONITOR OUTPUT 1 | out | MONITOR OUTPUT 1 | high |
| 14 | MONITOR OUTPUT 1 | out | MONITOR OUTPUT 1 | high |
| 15 | AUX OUTPUT 2 | out | AUX OUTPUT 2 | high |
| 16 | AUX OUTPUT 2 | out | AUX OUTPUT 2 | high |
| 17 | MONITOR OUTPUT 2 | out | MONITOR OUTPUT 2 | high |
| 18 | MONITOR OUTPUT 2 | out | MONITOR OUTPUT 2 | high |
| 19 | -25 V | power |  | high |
| 20 | ±25 V COMMON | ground |  | high |
| 21 | +25 V | power |  | high |
| 22 | CHASSIS GROUND | ground |  | high |

## Manuals and documents

_Manuals and manual pages, price lists, RTO-144 connection sheets, brochures, ads and other document scans._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKY3FvUzFPXzJnYUE/view?resourcekey=0-dM8c5HugluPK0Hz63ZTFtg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKY3FvUzFPXzJnYUE&resourcekey=0-dM8c5HugluPK0Hz63ZTFtg" width="240" alt="1978 - M479 - Dual Auxiliary Module (2).pdf"></a><br><sub>1978|11 · Dual Auxiliary Module (2)</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKelpQX2tudlFOaDg/view?resourcekey=0-Tn020EwbSjVzAQYiJqZe0A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKelpQX2tudlFOaDg&resourcekey=0-Tn020EwbSjVzAQYiJqZe0A" width="240" alt="1978 - M479 - Dual Auxiliary Module.pdf"></a><br><sub>1978|11 · Dual Auxiliary Module</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTTRzNHdiNUtUTU0/view?resourcekey=0-5GK8UndNLRGzRKTHpT2AxA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTTRzNHdiNUtUTU0&resourcekey=0-5GK8UndNLRGzRKTHpT2AxA" width="240" alt="1978 - M479 - P01 - Cover.jpg"></a><br><sub>1978|11 · P01 - Cover</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKaUZ6QjNnZFNrSk0/view?resourcekey=0-5ze3FscTcngcs0f3xemjfg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKaUZ6QjNnZFNrSk0&resourcekey=0-5ze3FscTcngcs0f3xemjfg" width="240" alt="1978 - M479 - P02.jpg"></a><br><sub>1978|11 · P02</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZGMxTE5vZEtiS2c/view?resourcekey=0-TiZ9OZqCYsQvvTeWRbnODg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZGMxTE5vZEtiS2c&resourcekey=0-TiZ9OZqCYsQvvTeWRbnODg" width="240" alt="1978 - M479 - P03 - TOC.jpg"></a><br><sub>1978|11 · P03 - TOC</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKR3pUZ2s3OXFwMUE/view?resourcekey=0-krpm4wXq5Ck1Pm9wjYCScQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKR3pUZ2s3OXFwMUE&resourcekey=0-krpm4wXq5Ck1Pm9wjYCScQ" width="240" alt="1978 - M479 - P04.jpg"></a><br><sub>1978|11 · P04</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNGJoZU5lTEcyWWs/view?resourcekey=0-1-NmSQYfmIpMQ1W3-H_IaA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNGJoZU5lTEcyWWs&resourcekey=0-1-NmSQYfmIpMQ1W3-H_IaA" width="240" alt="1978 - M479 - P05 - 1-1.jpg"></a><br><sub>1978|11 · P05 - 1-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKS3QxRkdtd0hSODQ/view?resourcekey=0-p011iyMQ3-8nEj9tj3I4ZQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKS3QxRkdtd0hSODQ&resourcekey=0-p011iyMQ3-8nEj9tj3I4ZQ" width="240" alt="1978 - M479 - P06 - 2-1.jpg"></a><br><sub>1978|11 · P06 - 2-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKcTNLUkMyX3p5YXc/view?resourcekey=0-D6_3NR4m0-nXI56etcWRmg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKcTNLUkMyX3p5YXc&resourcekey=0-D6_3NR4m0-nXI56etcWRmg" width="240" alt="1978 - M479 - P07 - 2-2.jpg"></a><br><sub>1978|11 · P07 - 2-2</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKcWNncUo1b2NhZUU/view?resourcekey=0-x4zEkBGqjVRyLPc8pdIbaA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKcWNncUo1b2NhZUU&resourcekey=0-x4zEkBGqjVRyLPc8pdIbaA" width="240" alt="1978 - M479 - P08 - 3-1.jpg"></a><br><sub>1978|11 · P08 - 3-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKakVOa2VDN1hTVlU/view?resourcekey=0-s9aIpwiqU_Ra6tt7Jwqbgw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKakVOa2VDN1hTVlU&resourcekey=0-s9aIpwiqU_Ra6tt7Jwqbgw" width="240" alt="1978 - M479 - P09 - 3-2.jpg"></a><br><sub>1978|11 · P09 - 3-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKaFBENXUxc0hFeEU/view?resourcekey=0-Yog5tk8-QPil8fsArh-vsg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKaFBENXUxc0hFeEU&resourcekey=0-Yog5tk8-QPil8fsArh-vsg" width="240" alt="1978 - M479 - P10 - 3-3.jpg"></a><br><sub>1978|11 · P10 - 3-3</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKU29VcUhLZGl3Zk0/view?resourcekey=0-4-aDwc88cgUy3O78bTBU2w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKU29VcUhLZGl3Zk0&resourcekey=0-4-aDwc88cgUy3O78bTBU2w" width="240" alt="1978 - M479 - P11 - 3-4.jpg"></a><br><sub>1978|11 · P11 - 3-4</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTEZ2dDlHSkR2Nnc/view?resourcekey=0-0cqrwuTFFc5OdYEZeRXWYA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTEZ2dDlHSkR2Nnc&resourcekey=0-0cqrwuTFFc5OdYEZeRXWYA" width="240" alt="1978 - M479 - P12 - 3-5.jpg"></a><br><sub>1978|11 · P12 - 3-5</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1I9lRAj6XxlnLgAq29r-o81hOi7Ej1v1k/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1I9lRAj6XxlnLgAq29r-o81hOi7Ej1v1k" width="240" alt="19xx - M479 - DOC - 2021-3-16-22-34-19.jpg"></a><br><sub>19xx - M479 - DOC - 2021-3-16-22-34-19</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWkhXLWEwUTljVXM/view?resourcekey=0-b9n2IVef2O4jjW76Rkhzkg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWkhXLWEwUTljVXM&resourcekey=0-b9n2IVef2O4jjW76Rkhzkg" width="240" alt="19xx - M479 - DOC - L2042 - P04.jpg"></a><br><sub>19xx - M479 - DOC - L2042 - P04</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdks3aXNVdTdOQkE/view?resourcekey=0-9EY_Jtwlj02gqh9vOxuOww" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdks3aXNVdTdOQkE&resourcekey=0-9EY_Jtwlj02gqh9vOxuOww" width="240" alt="19xx - M479 - DOC - L2042 - P09.jpg"></a><br><sub>19xx - M479 - DOC - L2042 - P09</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKa1RnVXFCRU9UeDA/view?resourcekey=0-HstK7E0Mu-VZp59Y7Wdh1w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKa1RnVXFCRU9UeDA&resourcekey=0-HstK7E0Mu-VZp59Y7Wdh1w" width="240" alt="19xx - M479 - DOC - L3242 - P04.jpg"></a><br><sub>19xx - M479 - DOC - L3242 - P04</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVG9HMUgyMUxBRGs/view?resourcekey=0-idNETBR0mGSulBuEaczYvg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVG9HMUgyMUxBRGs&resourcekey=0-idNETBR0mGSulBuEaczYvg" width="240" alt="19xx - M479 - DOC - L3242 - P09.jpg"></a><br><sub>19xx - M479 - DOC - L3242 - P09</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1-kteFUrteyg5A3w0Il1sCShPPiVRsT2Z/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1-kteFUrteyg5A3w0Il1sCShPPiVRsT2Z" width="240" alt="19xx - M479 - DOC - MCNLIOR MODULE OHMS SSUEI REMSION DIRECT.jpg"></a><br><sub>19xx - M479 - DOC - MCNLIOR MODULE OHMS SSUEI REMSION DIRECT</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVFBmX2RsU3ZpMmM/view?resourcekey=0-HxddTfJi3Ix3Fjzk54EIdQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVFBmX2RsU3ZpMmM&resourcekey=0-HxddTfJi3Ix3Fjzk54EIdQ" width="240" alt="19xx - M479 - DOC - R1400-R2400 - 007.jpg"></a><br><sub>19xx - M479 - DOC - R1400-R2400 - 007</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMmxvZGRGcWFZV0E/view?resourcekey=0-RFjMOyC4g8PP7m1AatUkNg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMmxvZGRGcWFZV0E&resourcekey=0-RFjMOyC4g8PP7m1AatUkNg" width="240" alt="19xx - M479 - DOC - R1400-R2400 - 012.jpg"></a><br><sub>19xx - M479 - DOC - R1400-R2400 - 012</sub></td></tr>
</table>

## KiCad

_KiCad: a schematic (`.kicad_sch`) traced from each electrical drawing, the module symbol (`.kicad_sym`) and its PCB projects. Traced schematics are the line work only: redraw with symbols over them._

- [1978 - M479 - 479-01-001 - DUAL AUXILIARY MODULE FUNCTIONAL DIAGRAM.kicad_sch](KICAD/1978%20-%20M479%20-%20479-01-001%20-%20DUAL%20AUXILIARY%20MODULE%20FUNCTIONAL%20DIAGRAM.kicad_sch)
- [1978 - M479 - Dual Auxiliary Module (2) p14.kicad_sch](KICAD/1978%20-%20M479%20-%20Dual%20Auxiliary%20Module%20(2)%20p14.kicad_sch)
- [1978 - M479 - Dual Auxiliary Module (2) p3.kicad_sch](KICAD/1978%20-%20M479%20-%20Dual%20Auxiliary%20Module%20(2)%20p3.kicad_sch)
- [1978 - M479 - Dual Auxiliary Module p14.kicad_sch](KICAD/1978%20-%20M479%20-%20Dual%20Auxiliary%20Module%20p14.kicad_sch)
- [1978 - M479 - Dual Auxiliary Module p15.kicad_sch](KICAD/1978%20-%20M479%20-%20Dual%20Auxiliary%20Module%20p15.kicad_sch)
- [1978 - M479 - P15 - Schematic.kicad_sch](KICAD/1978%20-%20M479%20-%20P15%20-%20Schematic.kicad_sch)
- [1992 - M479 - DOC - 920477-01-001 - OHMS SWTCHED SSUE REMSION FUTURE FUTURE.kicad_sch](KICAD/1992%20-%20M479%20-%20DOC%20-%20920477-01-001%20-%20OHMS%20SWTCHED%20SSUE%20REMSION%20FUTURE%20FUTURE.kicad_sch)
- [19xx - M479 - DOC - 479-02-001 - DUAL AUXILIARY MODULE SCHEMATIC.kicad_sch](KICAD/19xx%20-%20M479%20-%20DOC%20-%20479-02-001%20-%20DUAL%20AUXILIARY%20MODULE%20SCHEMATIC.kicad_sch)
- [2017 - M479 - DOC - 920170-01-001 - SWTCHED DIRECT MONITOR OUTPUTS DDZME.kicad_sch](KICAD/2017%20-%20M479%20-%20DOC%20-%20920170-01-001%20-%20SWTCHED%20DIRECT%20MONITOR%20OUTPUTS%20DDZME.kicad_sch)
- [M479.kicad_sym](KICAD/M479.kicad_sym)
- [index.html](KICAD/index.html)

## Software

- [index.html](SOFTWARE/index.html)

---
Archive: Anthony Peter Kuzub · [WBSps.ca](https://WBSps.ca) · [WBSps.Kuzub.com](https://WBSps.Kuzub.com)
