# README

Ref. 6 Table 1 & 2

## Creator

Madhav Raghavendra / Marjorie Romero

## Contact

Email: [rdave8224@gmail.com](rdave8224@gmail.com), [marjoriemromero@gmail.com](marjoriemromero@gmail.com)

## Reference

\[Reference Link\]\[https://inspirehep.net/literature/717721\]

## Notes

E_lepton denotes the lepton beam energy of the beam used in the experiment (measured at 27.6 GeV).  
The lepton type(s) used in this experiment were both electrons and positrons.

The hadron used in the experiment was a proton, with a rest-energy constant of 0.938 GeV.

Both satisfy the ep → epγ condition.  
Collaboration was done with HERMES spectrometer, as well as using the HERA accelerator at DESY.

Cross section is based off 3 variables: x_B,-Q^2, phi and t. Details of variables are included in the table below.

Data are taken from Table 1, and Figures 3 & 4 (page 4) of the paper.  

Some Kinematic requirments were imposed:  
- 1 Gev² < Q2 < 10 (GeV/c)²  
- W > 3.0 GeV
- 0.03 < x_b < 0.35
- v < 22 GeV  

The recoiling proton was not detected. Hence exclusive, events are selected by requiring the missing mass M_X next to the reaction ep → eγX
- an angle cut 5mrad < theta_(γ*γ) < 45mrad  
- a missing-mass-squared cut –1.5 < M_X² < 1.7 (GeV/c²)²    

The beam-charge asymmetry is evaluated as:

$$A_C(\phi) \;=\;\frac{N^+(\phi)\;-\;N^-(\phi)}{N^+(\phi)\;+\;N^-(\phi)}$$

Variables are explained in the table below

Here is Table 1

| -t bin (GeV²) | ⟨-t⟩ (GeV²) | ⟨x_B⟩ | ⟨Q²⟩ (GeV²) | A_C^{cos φ} ± stat. ± sys.    |
|:-------------:|:----------:|:-----:|:----------:|:----------------------------:|
| `< 0.06`       | `0.03`     | `0.08`| `2.0`      | `0.024 ± 0.043 ± 0.022`      |
| `0.06–0.14`   | `0.09`     | `0.10`| `2.6`      | `0.020 ± 0.054 ± 0.022`      |
| `0.14–0.30`   | `0.20`     | `0.11`| `3.0`      | `0.071 ± 0.066 ± 0.028`      |
| `0.30–0.70`   | `0.42`     | `0.12`| `3.7`      | `0.377 ± 0.110 ± 0.081`      |
                                Last Row 
| `<0.70`       | `0.12`     | `0.10`| `2.5`      | `0.063 ± 0.029 ± 0.028`      |

The -t bin column in the table is not included in any of the excel sheets. However, these are restrictions places on -t to seperate the values into different bins, with the other values in the rows being the respective average kinematic values.

The 4 bins are included in Excel Table One, and the last row is meant to be the result after the background correction, included in Excel Table 2. All values in table 1 are included in either Excel Tables 1 & 2 under their respective column names.

The latter 3 Table one column names, designated as ⟨-t⟩ (GeV²)  ⟨x_B⟩,  ⟨Q²⟩ (GeV²), A_C^{cos φ} ± stat. ± sys, correspond to unit names in both excel tables.

| Table 1 Names | Excel Counterpart |
|:-------------:|:----------:|
|  ⟨-t⟩ (GeV²)   |     t    |
|  ⟨x_B⟩ | ⟨Q²⟩ (GeV²) |     xB    |
|  ⟨Q²⟩ (GeV²)   |    Q2    |
| A_C^{cos φ} ± stat. ± sys.    |  value, stat_u, syst_u     |

The function uses a cos(phi) modulation instead of a sin(phi) modulation, and is written in the Excel Sheets as ACCos1Phi.

The value of t in the exclusive region is calculated as

$$t \;=\;
\frac{-\,Q^2 \;-\; 2\,\nu\Bigl(\nu \;-\;\sqrt{\nu^2 + Q^2}\,\cos\theta_{\gamma^*\gamma}\Bigr)}{1 \;+\;\frac{1}{M_p}\Bigl(\nu \;-\;\sqrt{\nu^2 + Q^2}\,\cos\theta_{\gamma^*\gamma}\Bigr)}$$

---

## Definitions & Units Table

| Symbol                | Meaning                                                              | Units            |
|:---------------------:|:---------------------------------------------------------------------|:----------------:|
| E_lepton              | Incident electron beam energy                                        | GeV              |
| E_hadron              | Proton rest energy (mc²)                                             | GeV              |
| Q2                    | squaredvirtual-photon four-momentum (–Q²)                            | (GeV/c)²         |
| W                     | Invariant mass of the photon–nucleon system                          | GeV/c²           |
| t                     | Four-momentum transfer squared                                       | (GeV/c)²         |
| phi                   | Azimuthal angle between in/outcoming leptons and virtual-realphoton planes | degrees(°) |
| x_B                   |  the Bjorken scaling variable                                        | —                |
| v                     | virtual-photon energy in the target rest frame                       | GeV              |
| A_C(φ) | Beam-charge asymmetry in hard exclusive photon electroproduction                    |                  |
| N⁺(φ)  | Single-photon yield with the **positron** beam, normalized to the number of inclusive DIS events | counts  |
| N⁻(φ)  | Single-photon yield with the **electron** beam, normalized to the number of inclusive DIS events | counts  |
| θ_{γ*γ}| angle between the virtual‐photon momentum **q** and the real‐photon momentum **k**, i.e. (q·k)/(mag(q)·mag(k))| N/A |
