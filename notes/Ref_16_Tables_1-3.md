# README

Ref. 16 Tables 1-3

## Creator

Madhav Raghavendra / Marjorie Romero

## Contact

Email: [rdave8224@gmail.com](rdave8224@gmail.com), [marjoriemromero@gmail.com](marjoriemromero@gmail.com)

## Reference

\[Reference Link\]\[https://inspirehep.net/literature/1341608\]

## Notes

E_lepton denotes the lepton beam energy of the beam used in the experiment (measured at 5.932 GeV).  
The lepton type(s) used in this experiment were electrons and positrons.

The hadron used in the experiment was a proton, with a rest-energy constant of 0.938 GeV.

Both satisfy the ep⟶e′p′γ condition.  

Collaboration was done with the CEBAF large acceptance spectrometer (CLAS).

Data is taken from Figures and Table 5 (page 23-26) of the paper.

Electrons were selected among all the negative tracks with momenta above 0.8 GeV/c, by requiring that their energy deposited in the inner layers of the EC be greater than 0.06 GeV

Some Kinematic requirments were imposed:  
- Q² < 1 (GeV)²   
- -t < Q²
- W > 2 GeV
- Eγ > 1 GeV GeV
- 3σ cut around the mean of MM^2(ep) to eliminate from the experimental data the background from channels other than epγ or epπ0

This region was shifted by 0.18 GeV2 for the exclusive events from e−(electron) data.

## Table I. Definition of the bins in \(x_B\) and \(\theta_e\), and average kinematics

| Bin | \(x_B\) bin       | \(\theta_e\) bin     | ⟨\(x_B\)⟩ | ⟨\(Q^2\)⟩ [(GeV/\(c\))²] |
|:---:|:------------------|:---------------------|:---------:|:-----------------------:|
|  1  | 0.10 – 0.20       | 15° – 48°            |   0.179   |         1.52            |
|  2  | 0.20 – 0.30       | 15° – 34°            |   0.255   |         1.97            |
|  3  | 0.20 – 0.30       | 34° – 48°            |   0.255   |         2.41            |
|  4  | 0.30 – 0.40       | 15° – 45°            |   0.345   |         2.60            |
|  5  | \(x_B > 0.40\)    | 15° – 45°            |   0.453   |         3.31            |

## Table II. Definition of the bins in \(-t\) and average kinematics

| Bin | \(-t\) range [(GeV/\(c\))²] | ⟨\(-t\)⟩ [(GeV/\(c\))²] |
|:---:|:---------------------------:|:----------------------:|
|  1  | 0.08 – 0.18                 |        0.137           |
|  2  | 0.18 – 0.30                 |        0.234           |
|  3  | 0.30 – 0.70                 |        0.467           |
|  4  | 0.70 – 2.00                 |        1.175           |

## Table 5 Overview

Table 5 is too large to be included in this document.

## Included in document but not in Excel Sheet*

**Virtual‐Photon vs. Lab‐Frame Asymmetries**

In order to express the target‐spin (TSA) and double‐spin (DSA) asymmetries with respect to the virtual-photon direction rather than the beam direction, two small correction terms are introduced.

1. **c_AUT**  
   Converts the lab-frame single-spin asymmetry A_UL^lab into the photon-frame asymmetry A_UL  

   
2. **c_ALT**  
Converts the lab-frame double-spin asymmetry A_LL^lab into the photon-frame asymmetry A_LL  

 theta_gamma_star is the angle between the virtual-photon direction and the beam axis in the lab frame.  
 A_UT(0) and *A_LT(0)* are the purely transverse asymmetries at φ=0, estimated from a GPD model.

## Relation of Table(s) to Excel Sheets

There are 3 Excel Sheets total, functions present in Table 5. 

Each Excel Sheet is seperated based off of each respective Fourier coefficients/amplitudes. The definitions for these values are found in the table below.

 **Table Column names and their corresponding Excel Sheet names**

average -t, x_B, or Q^2 values = t, xB, and Q2

ϕ = phi

 obs values and their table counterparts.

| Asymmetry | Beam Polarization | Target Polarization | Observable Modulation | Physical Sensitivity                                     |
|:---------:|:-----------------:|:-------------------:|:---------------------:|:---------------------------------------------------------:|
| `A_LU`    | Longitudinal      | Unpolarized         | sin φ                 | Imaginary part of DVCS–BH interference                   |
| `A_UL`    | Unpolarized       | Longitudinal        | sin φ, sin 2φ         | Imaginary parts of DVCS Compton Form Factors             |
| `A_LL`    | Longitudinal      | Longitudinal        | cos φ                 | Real part of DVCS amplitude, CFF combinations            |

| Asymmetry | Beam Polarization | Target Polarization | Typical Notation | Leading Modulation | Physical Sensitivity                                |
|:---------:|:-----------------:|:-------------------:|:----------------:|:------------------:|:--------------------------------------------------:|
| BSA       | Longitudinal      | Unpolarized         | `A_LU`           | sin φ             | Imaginary part of DVCS–BH interference             |
| TSA       | Unpolarized       | Longitudinal (or Transverse)| `A_UL`, `A_UT` | sin φ, sin 2φ (UL); sin(φ−φ_S), … (UT) | Imaginary parts of various CFF combinations |
| DSA       | Longitudinal      | Longitudinal        | `A_LL`           | cos φ             | Real part of DVCS amplitude and CFF combinations    |

Amplitude = value

±δ(stat.) ±δ(syst.) are indicated as syst_u & stat_u 

## Definitions & Units Table

| Symbol / Column        | Meaning                                                                                                            | Units                  |
|:----------------------:|:-------------------------------------------------------------------------------------------------------------------|:----------------------:|
| `E_lepton`             | Incident lepton beam energy (electrons or positrons)                                                               | GeV                    |
| Lepton type            | Flavor of the beam lepton                                                                                          | —                      |
| `M_p`                  | Proton rest mass                                                                                                   | 0.938 GeV/\(c^2\)      |
| Reaction               | Exclusive radiative process                                                                                       | e± p → e′ p′ γ          |
| `Q^2`                  | Photon virtuality, \(Q^2\equiv -q^2\)                                                                               | (GeV/\(c\))²           |
| `-t`                   | Four-momentum transfer squared to the proton, \((p - p')^2\)                                                         | (GeV/\(c\))²           |
| `W`                    | Invariant mass of the photon–nucleon system                                                                         | GeV/\(c^2\)            |
| `E_γ`                  | Energy of the real photon in the lab frame                                                                          | GeV                    |
| `M_X^2`                | Missing-mass squared \((q + p - q')^2\) of the undetected system \(X\)                                               | (GeV/\(c^2\))²         |
| `θ_e`                  | Polar angle of the scattered electron                                                                               | degrees (°)            |
| `θ_{γ*γ}`              | Angle between the virtual-photon direction **q** and the real-photon **q′**                                         | milliradians (mrad)    |
| `x_B`                  | Bjorken scaling variable, \(x_B=Q^2/(2\,p\cdot q)\)                                                                 | —                      |
| `φ_{pγ}`               | Azimuthal angle between the lepton-scattering plane and the photon–proton production plane                          | degrees (°)            |
| `φ_e`, `φ_p`           | Azimuthal angles of scattered electron/proton (used in exclusivity cut \(|φ_e - φ_p|\))                             | degrees (°)            |
| `P_e`                  | Average longitudinal polarization of the lepton beam                                                               | —                      |
| `N^+_γ(φ)`, `N^-_γ(φ)` | Single-photon yields in bin φ for **positive** / **negative** beam helicity                                         | counts                 |
| `%norm_c`              | Relative normalization uncertainty (beam-polarization scale)                                                        | %                      |
| `value`                | Fitted amplitude of the given asymmetry harmonic                                                                   | —                      |
| `stat_u`               | Statistical uncertainty on `value`                                                                                  | —                      |
| `syst_u`               | Systematic uncertainty on `value`                                                                                   | —                      |
| `obs`                  | Identifier for which asymmetry/ harmonic is being tabulated (e.g. A_LU, A_UL, A_LL, A_C, etc.)                       | —                      |
| `A_LU(φ)`              | Beam-spin asymmetry (longitudinal beam, unpolarized target): \((1/P_e)\,(N^+_γ−N^-_γ)/(N^+_γ+N^-_γ)\)                | —                      |
| `A_UL(φ)`              | Target-spin asymmetry (unpolarized beam, longitudinal target)                                                       | —                      |
| `A_LL(φ)`              | Double-spin asymmetry (longitudinal beam & longitudinal target)                                                     | —                      |
| **BSA**                | Beam-Spin Asymmetry = `A_LU`                                                                                        | —                      |
| **TSA**                | Target-Spin Asymmetry = `A_UL` (or transverse-target `A_UT`)                                                         | —                      |
| **DSA**                | Double-Spin Asymmetry = `A_LL` (or `A_LT`, `A_TL` for mixed polarisations)                                          | —                      |
| `c_AUT`                | Photon-frame correction: \(A_{UL} - A_{UL}^{\mathrm{lab}}\) (lab→virtual-photon frame)                              | —                      |
| `c_ALT`                | Photon-frame correction: \(A_{LL} - A_{LL}^{\mathrm{lab}}\)                                                          | —                      |
| `A_UT(0)`, `A_LT(0)`   | Purely transverse asymmetry at φ=0, estimated from a GPD model                                                       | —                      |