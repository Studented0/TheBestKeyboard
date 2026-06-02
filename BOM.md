# The BEST Keyboard AOT — Bill of Materials

## MCU & Wireless

| Component | Part | Source | LCSC # | Qty | Unit Cost | Total |
|---|---|---|---|---|---|---|
| nRF52840 module | E73-2G4M08S1C | JLCPCB | C356849 | 1 | $5.50 | $5.50 |
| ESD protection | PRTR5V0U2X | JLCPCB | C2827688 | 1 | $0.15 | $0.15 |
| 2.4GHz dongle | nRF52840 PCA10059 | Amazon | — | 1 | $12.00 | $12.00 |

## Power Management

| Component | Part | Source | LCSC # | Qty | Unit Cost | Total |
|---|---|---|---|---|---|---|
| LiPo charger | TP4056 | JLCPCB | C382139 | 1 | $0.20 | $0.20 |
| Battery protection IC | DW01A | JLCPCB | C82270 | 1 | $0.05 | $0.05 |
| Protection MOSFET | FS8205A | JLCPCB | C2830320 | 1 | $0.10 | $0.10 |
| 3.3V LDO | HT7333-A | JLCPCB |  | 1 | $0.15 | $0.15 |
| Boost converter | MT3608 | JLCPCB | C84500 | 1 | $0.25 | $0.25 |
| Boost inductor | CKCS5040-4.7uH/M | JLCPCB | C354606 | 1 | $0.30 | $0.30 |
| Boost diode | SS14 | JLCPCB | C2480 | 1 | $0.10 | $0.10 |
| Power path diode | BAT54S | JLCPCB | C8598 | 1 | $0.05 | $0.05 |
| LiPo battery 2000mAh | Generic | AliExpress | — | 1 | $8.00 | $8.00 |
| Qi receiver module | 5V 1A wireless module | AliExpress | — | 1 | $4.00 | $4.00 |
| JST-PH 2-pin connector | Battery connector | JLCPCB | — | 1 | $0.20 | $0.20 |

## Hall Effect Sensing

| Component | Part | Source | LCSC # | Qty | Unit Cost | Total |
|---|---|---|---|---|---|---|
| Hall effect sensor | SS49E | JLCPCB | C85697 | 90 | $0.26 | $23.40 |
| 16:1 analog mux | CD74HC4067 | JLCPCB | C9986 | 6 | $0.50 | $3.00 |
| Shift register (mux EN) | 74HC595 | JLCPCB | C5947 | 1 | $0.20 | $0.20 |

## RGB & Display

| Component | Part | Source | LCSC # | Qty | Unit Cost | Total |
|---|---|---|---|---|---|---|
| Per-key RGB LED | SK6812MINI-E | JLCPCB | C2890364 | 90 | $0.10 | $9.00 |
| Level shifter (RGB) | 74AHCT125 | JLCPCB | C7601 | 1 | $0.30 | $0.30 |
| OLED display | SSD1306 128×64 | Amazon | — | 1 | $7.00 | $7.00 |

## Connectors & Input

| Component | Part | Source | LCSC # | Qty | Unit Cost | Total |
|---|---|---|---|---|---|---|
| USB-C receptacle | HRO TYPE-C-31-M-12 | JLCPCB | C165948 | 1 | $0.50 | $0.50 |
| Rotary encoder | EC11 | AliExpress | — | 1 | $1.50 | $1.50 |
| Reset button | TS-1187A-B-A-B | JLCPCB | C318884 | 1 | $0.10 | $0.10 |

## Switches & Mechanical

| Component | Part | Source | LCSC # | Qty | Unit Cost | Total |
|---|---|---|---|---|---|---|
| Hall effect switches | Gateron Magnetic Jade | AliExpress | — | 90 | $0.60 | $54.00 |
| Hot-swap sockets | Gateron KS-33 | AliExpress | — | 90 | $0.10 | $9.00 |
| Stabilizers | PCB-mount stab set | AliExpress | — | 1 set | $12.00 | $12.00 |
| Keycaps | 75% PBT set | AliExpress | — | 1 set | $28.00 | $28.00 |

## Passives (JLCPCB assembled)

| Component | Qty | Total |
|---|---|---|
| 0402 resistors (various values) | ~30 | $1.50 |
| 0402 capacitors (various values) | ~25 | $1.50 |
| 0805 capacitors (22µF) | 2 | $0.30 |

## PCB Fabrication & Assembly

| Item | Cost |
|---|---|
| Keyboard PCB (315×105mm, 5 boards, JLCPCB) | $22.00 |
| SMT assembly (JLCPCB PCBA) | ~$20.00 |
| Extended part setup fees | ~$9.00 |
| IPEX 2.4GHz antenna (for E73) | $2.00 |

---

## Total Estimated Cost

| Category | Subtotal |
|---|---|
| MCU & Wireless | $17.65 |
| Power Management | $13.40 |
| Hall Effect Sensing | $26.60 |
| RGB & Display | $16.30 |
| Connectors & Input | $2.10 |
| Switches & Mechanical | $103.00 |
| Passives | $3.30 |
| PCB & Assembly | $53.00 |
| **Grand Total** | **~$235** |

All PCB-mounted components are ordered via JLCPCB with SMT assembly.
Hand-soldered items: SS49E sensors (×84), Gateron KS-33 sockets (×84), EC11 encoder, OLED module, battery connector, Qi module.
