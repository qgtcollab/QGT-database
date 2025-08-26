# README

Ref. 4 Table 1 & 2

## Creator

Madhav Raghavendra / Marjorie Romero

## Contact

Email: [rdave8224@gmail.com](rdave8224@gmail.com), [marjoriemromero@gmail.com](marjoriemromero@gmail.com)

## Reference

\[Reference Link\]\[https://inspirehep.net/literature/715983\]

## Notes

E_lepton denotes the lepton beam energy of the beam used in the experiment (measured at 5.7 GeV). The lepton type used in this experiment was an electron.

The hadron used in the experiment was a proton, with a rest-energy constant of 0.938 GeV.

Both satisfy the ep → e′ p γ condition. Collaboration was done with the CEBAF Large Acceptance Spectrometer (CLAS) and HERMES, though only the CLAS colloboration is mentioned in the tables.

Data are taken from Figures 3 & 4 (pages 4 & 5) of the paper.  
These values were used to model the two asymmetry functions A_UL^exp(phi) and A_UL(phi).  
Deep-inelastic kinematic cuts:  
- Q2 > 1.0 (GeV/c)²  
- W > 2.0 (GeV/c²)  
- –t < 0.6 (GeV/c)²  

(pi)^0 is the neutral pion that can mimic a single-photon final state if one photon is undetected. To correct for this background, they apply:  
- an angle cut theta_(eγ) < 2.5°  
- a two-photon invariant-mass cut 0.05 < M_γγ < 0.18 GeV/c²  
- a missing-mass-squared cut –0.10 < M_X² < 0.14 (GeV/c²)²  

Dilution factor f = 0.782 ± 0.036  

The corrected target-spin asymmetry (for single-γ production) is written in the form:

    A_UL^exp(phi) = F_gamma(phi) * A_UL(phi)  +  F_(pi)^0(phi) * A_UL^(pi)^0(phi)

Here A_UL^exp(phi) and A_UL^(pi)^0(phi) are the measured asymmetries with and without the (pi)^0 background, respectively.

For the phi-dependence plot (Fig. 4), the bin-averaged values are:

| Symbol | Bin­-averaged value | Units        |
|:------:|:-------------------:|:------------:|
| <Q2>   | 1.82                | (GeV/c)²     |
| <-t>   | 0.31                | (GeV/c)²     |
| <xi>   | 0.16                | —            |

The phi dependence is then fitted with

    A(phi) = alpha * sin(phi)  +  beta * sin(2*phi)

- alpha·sin(phi) is the first harmonic (Table 1)  
- beta·sin(2*phi) is the second harmonic (Table 2)  
 
In Table 1, the amplitude of the sin(phi) modulation is 0.252, denoted under the column "value". The statistical uncertainty is 0.042, written in the table as "stat\_u". The systematic uncertainty is 0.020, written as "syst\_u". 
In Table 2, the amplitude of the sin(2φ) modulation is –0.022 , designated as "value" in the table, the statistical uncertainty is 0.045, written in the table as "stat\_u". The systematic uncertainty is 0.0021, written as "syst\_u". 
---

## Definitions & Units Table

| Symbol                | Meaning                                                              | Units            |
|:---------------------:|:---------------------------------------------------------------------|:----------------:|
| E_lepton              | Incident electron beam energy                                        | GeV              |
| E_hadron              | Proton rest energy (mc²)                                             | GeV              |
| Q2                    | Photon virtuality (–q²)                                              | (GeV/c)²         |
| W                     | Invariant mass of the photon–proton system                           | GeV/c²           |
| t                     | Four-momentum transfer squared                                       | (GeV/c)²         |
| phi                   | Azimuthal angle between electron-scattering and photon-proton planes  | degrees (°)      |
| f                     | Dilution factor (fraction of events from hydrogen in NH₃ target)     | —                |
| P_t⁻, P_t⁺            | Absolute target polarizations for helicity – / +                     | —                |
| N⁻(phi), N⁺(phi)      | Luminosity-normalized, acceptance-corrected counts for helicity – / + | counts           |
| F_gamma(phi)          | Fraction of single-photon (DVCS–BH) events in each phi bin           | —                |
| F_(pi)^0(phi)            | Fraction of (pi)^0 background events (one photon undetected)            | —                |
| A_UL^exp(phi)         | Measured asymmetry including (pi)^0 contamination                       | —                |
| A_UL(phi)             | DVCS–BH asymmetry after (pi)^0 subtraction                               | —                |
| A_UL^(pi)^0(phi)         | Measured asymmetry for identified (pi)^0 → γγ events                    | —                |
| M_X²                  | Missing-mass squared of the unobserved system X in ep→epX             | (GeV/c²)²        |
| theta_(eγ)            | Angle between measured and predicted photon directions               | degrees (°)      |
| M_γγ                  | Invariant mass of the two-photon system ((pi)^0 selection)              | GeV/c²           |
| alpha                 | First-harmonic amplitude (sin φ term)                                 | —                |
| beta                  | Second-harmonic amplitude (sin 2φ term)                               | —                |

---

## Table Structure & Captions

**Table 1.** Fit to first harmonic  
- Columns: value = alpha, stat_u, syst_u  
- values: <Q2>=1.82 (GeV/c)², <-t>=0.31 (GeV/c)², <xi>=0.16

**Table 2.** Fit to second harmonic  
- Columns: value = beta, stat_u, syst_u  
- Same values as Table 1