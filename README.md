# USP <791> pH Electrode Slope & Offset Calculator

An open technical reference for evaluating pH electrode health in accordance with **USP <791>** and **ISO/IEC 17025 (NABL)** guidelines using the **Nernst equation**, electrode slope (%), and zero-point offset (mV).

👉 **Live Interactive Calculator (No Login, Instant PDF Report):**  
https://scispectrum.in/pages/ph-electrode-slope-offset-calculator

---

## 1. Nernst Equation & Slope Formula

At temperature $T$ (in Kelvin, $T = t(^\circ\text{C}) + 273.15$), the theoretical Nernstian slope $S_{\text{theoretical}}$ (in mV/pH) is:

$$S_{\text{theoretical}} = \frac{2.303 \cdot R \cdot T}{F} \times 1000$$

Where:
- $R = 8.3144626\ \text{J}\cdot\text{mol}^{-1}\cdot\text{K}^{-1}$ (Universal gas constant)
- $F = 96485.332\ \text{C}\cdot\text{mol}^{-1}$ (Faraday constant)
- At **25 °C (298.15 K)**, $S_{\text{theoretical}} = 59.16\ \text{mV/pH}$

### Measured Slope (%)
$$\text{Slope (\%)} = \left( \frac{|E_1 - E_2|}{|\text{pH}_1 - \text{pH}_2| \times S_{\text{theoretical}}(T)} \right) \times 100$$

### Zero-Point Offset (mV)
$$\text{Offset (mV)} = E_{\text{pH 7.00}}$$
*(Expected: $0 \pm 30\ \text{mV}$ in pH 7.00 buffer)*

---

## 2. Theoretical Nernst Slope Reference Table (15 °C – 35 °C)

| Temperature (°C) | Theoretical Slope (mV/pH) | 95% Limit (mV/pH) | 105% Limit (mV/pH) |
| :---: | :---: | :---: | :---: |
| 15 °C | 57.17 | 54.31 | 60.03 |
| 20 °C | 58.17 | 55.26 | 61.08 |
| 25 °C | 59.16 | 56.20 | 62.12 |
| 30 °C | 60.15 | 57.14 | 63.16 |
| 35 °C | 61.14 | 58.08 | 64.20 |

---

## 3. USP <791> & NABL Acceptance Criteria

- **Electrode Slope:** **95% – 105%** (or **90% – 105%** per specific SOP)
- **Zero-Point Offset (pH 7.00):** **±30 mV** (ideal: ±15 mV)

---

## 4. Open-Access Verification Sheets & DOIs

- **Interactive Calculator:** https://scispectrum.in/pages/ph-electrode-slope-offset-calculator
- **Zenodo (CERN) DOI:** https://doi.org/10.5281/zenodo.24368570
- **Figshare DOI:** https://doi.org/10.6084/m9.figshare.35060302
- **Published by:** [SciSpectrum](https://scispectrum.in)
