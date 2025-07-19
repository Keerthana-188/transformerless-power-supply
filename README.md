# transformerless-power-supply
This project is a PCB design for a **Transformerless Power Supply** created using KiCad.  
It provides a compact and cost-effective way to power low-current DC circuits directly from AC mains without using bulky transformers.

# Features
Compact PCB layout using through-hole components
- Converts AC to regulated DC using:
  - Capacitor dropper (C4)
  - Full-wave bridge rectifier (D1–D4)
  - Filtering and regulation using LM7805 or LM7812
  - Protection diodes and discharge resistors
  - Indicator LED for output status

## Comparison: Transformerless vs. Conventional Power Supply

| Feature                        | Transformerless Power Supply                        | Conventional Power Supply                            |
|-------------------------------|-----------------------------------------------------|------------------------------------------------------|
| **Size & Weight**             | Very compact and lightweight                        | Bulky due to iron-core transformer                   |
| **Cost**                      | Low cost – fewer and cheaper components             | Higher cost due to transformer and large components  |
| **Efficiency (Low Power Load)** | High for small loads                                 | Moderate (some loss in transformer)                  |
| **Power Output Capacity**     | Suitable only for **low current** applications      | Can provide high current based on transformer rating |
| **Safety**                    | Risky if not handled properly (AC mains exposed)    | Safer due to isolation, especially for beginners     |
| **Applications**              | LED drivers, small control circuits, chargers       | Audio amplifiers, adapters, regulated power supplies |


