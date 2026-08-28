# ACMC-OF-BUCK-CONVERTER-
ACMC OF BUCK CONVERTER 
# Average Current Mode Control (ACMC) of Buck DC-DC Converter

Design, small-signal modeling, and dual-loop control implementation of a DC-DC Buck Converter operating in Continuous Conduction Mode (CCM) using Average Current Mode Control (ACMC) with Type-II compensators.

---

## 📌 Project Overview

This project focuses on the modeling and feedback control of a synchronous/non-synchronous Buck Converter. It implements a dual-loop **Average Current Mode Control (ACMC)** architecture:
- **Inner Current Loop:** Uses a **Type-II compensator** to average and track the inductor current with high bandwidth, providing inherent overcurrent protection and high noise immunity.
- **Outer Voltage Loop:** Uses a **Type-II compensator** to regulate the output voltage against line and load transients.

---

## ⚙️ Specifications & Design Parameters

| Parameter | Symbol | Nominal Value | Unit |
| :--- | :---: | :---: | :---: |
| Input Voltage | $V_{in}$ | 24.0 | V |
| Output Voltage | $V_o$ | 12.0 | V |
| Rated Output Power | $P_o$ | 60.0 | W |
| Switching Frequency | $f_s$ | 100 | kHz |
| Current Ripple ($\Delta I_L$) | - | 20% of $I_o$ | A |
| Voltage Ripple ($\Delta V_o$) | - | 1% of $V_o$ | V |

---

## 📐 Control Architecture
