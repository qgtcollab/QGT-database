# README

Ref. 24 Tables 1-2

## Creator

Madhav Raghavendra / Marjorie Romero

## Contact

Email: [rdave8224@gmail.com](rdave8224@gmail.com), [marjoriemromero@gmail.com](marjoriemromero@gmail.com)

## Reference

\[Reference Link\]\[https://inspirehep.net/literature/2008816\]

## Notes

E_lepton denotes the lepton beam energy of the beam used in the experiment (measured at 7.38 GeV).  
The lepton type(s) used in this experiment were electrons

The hadron used in the experiment was a proton, with a rest-energy constant of 0.938 GeV.

Both satisfy the ep → epγ condition.  

Collaboration was done with Jefferson Lab Hall A.

Data is taken from the unpolarized (beam-unpolarized) and the beam-helicity–dependent cross sections (d4SigUU and d4SigLU respectively). It is based off of Table 1 (page 3) in the paper.


## Beam, target & detector requirements

- **Beam:** longitudinally polarized electron beam,  
  – Energy = E_b as above; current = 5–15 μA (to keep DAQ dead-time < 5%);  
  – Polarization = 86 ± 1% (Møller polarimeter).  
- **Target:** 15 cm liquid hydrogen cell.  
- **Electron detection:** left HRS, requiring coincidence between scintillators & Cerenkov, with offline Pb-glass calorimeter PID.  
- **Photon detection:** segmented PbF₂ calorimeter (208 channels, 1 GHz ARS sampling), with level-2 FPGA trigger at high rates (> 1 kHz) and programmable energy thresholds.  
- **Energy resolution:** ~ 3% at 7 GeV.  
- **Timing resolution:** < 1 ns between e′ and γ. :contentReference[oaicite:3]{index=3}


## Event selection & exclusivity

1. Missing-mass reconstruction of the undetected proton in  
   \[
     ep \;\to\; e\,\gamma\,X
   \]  
   is used to select exclusive DVCS.  
2. Background subtraction:  
   - Accidentals evaluated via shifted time windows;  
   - π⁰→γγ contamination estimated by GEANT4‐tuned MC and subtracted bin-by-bin. :contentReference[oaicite:4]{index=4}  
3. Multidimensional (“R-cut”) selection:  
   - Identical fiducial and exclusivity cuts applied to data and simulation (so-called “R cuts” [26]), to ensure consistent acceptance and background suppression. :contentReference[oaicite:5]{index=5}  
4. Binning: cross sections extracted in bins of (x_B, Q², t, ϕ) at fixed x_B and t, with simultaneous fits to φ-dependence using the BMMP formalism

## Tables 1

Modified version of table 1

| Setting   | x_B | E₆ (GeV) | Q² (GeV²) | E_γ (GeV) | −t_min (GeV²) | ∫ Q dt (C) | Number of data bins |
|:---------:|:---:|:--------:|:---------:|:---------:|:-------------:|:----------:|:------------------:|
| Kin-36-1  | 0.36|   7.38   |   3.20    |   4.7     |     0.16      |    1.2     |        672         |
| Kin-36-2  | 0.36|   8.52   |   3.60    |   5.2     |     0.17      |    1.7     |        672         |
| Kin-36-3  | 0.36|  10.59   |   4.47    |   6.5     |     0.17      |    1.3     |        672         |
| Kin-48-1  | 0.48|   4.49   |   2.70    |   2.8     |     0.32      |    2.2     |        912         |
| Kin-48-2  | 0.48|   8.85   |   4.37    |   4.7     |     0.34      |    2.2     |        912         |
| Kin-48-3  | 0.48|   8.85   |   5.33    |   5.7     |     0.35      |    3.7     |        912         |
| Kin-48-4  | 0.48|  10.99   |   6.90    |   7.5     |     0.36      |    5.7     |        912         |
| Kin-60-1  | 0.60|   8.52   |   5.54    |   4.6     |     0.66      |    6.4     |        480         |
| Kin-60-3  | 0.60|  10.59   |   8.40    |   7.1     |     0.70      |   18.5     |        480         |

## Relation of Tables to Excel Sheets

There are 2 Excel Sheets total, based on the different bins and functions present in Table 1. 

Each Excel Sheet is seperated based on 2 quantities: d4SigLU and d4SigUU. The definitions for these values are found below.

 **Table Column names and their corresponding Excel Sheet names**

average -t, x_B, or Q^2 values = t, xB, and Q2

 Describes **where** the measurements were taken and **how** they were binned:
  - Nine kinematic settings (`Kin-36-1` … `Kin-60-3`) defined by \((x_B, Q^2, E_b, E_\gamma, -t_{\min}, \int Q\,dt)\).  
  - Number of **t-bins** \(\times\) **ϕ-bins** specified for each setting.
 
Type of quantity used = obs

ϕ = phi

Amplitude of (corresponding quantity) = value

±δ(stat.) ±δ(syst.) are indicated as syst_u & stat_u 

## Definitions & Units Table

| Symbol      | Meaning                                                                                                              | Units               |
|:-----------:|:---------------------------------------------------------------------------------------------------------------------|:-------------------:|
| `W²`        | Squared invariant mass of the virtual-photon–proton system, \(W^2 = (q + p)^2\)                                      | GeV²                |
| `Q²`        | Virtual-photon four-momentum transfer squared, \(Q^2 = -\,q^2\)                                                      | GeV²                |
| `t`         | Squared momentum transfer to the proton, \(t = (p - p')^2\)                                                          | GeV²                |
| `x_B`       | Bjorken scaling variable, \(x_B = Q^2 / (2\,p\cdot q)\)                                                              | —                   |
| `ξ`         | DVCS skewness variable, \(\displaystyle \xi \approx \tfrac{x_B}{2 - x_B}\)                                           | —                   |
| `k, k'`     | Four-momenta of incoming (`k`) and scattered (`k'`) electrons                                                        | GeV/\(c\)           |
| `q, q'`     | Four-momenta of virtual (`q = k - k'`) and real (`q'`) photons                                                       | GeV/\(c\)           |
| `p, p'`     | Four-momenta of initial (`p`) and recoiling (`p'`) proton                                                            | GeV/\(c\)           |
| `E_b`       | Incident electron (beam) energy                                                                                      | GeV                 |
| `E_γ`       | Energy of the real photon detected in the calorimeter                                                                | GeV                 |
| `−t_min`    | Minimum kinematically allowed \(|t|\) for a photon emitted parallel to \(\mathbf{q}\)                                | GeV²                |
| `∫ Q dt`    | Total accumulated beam charge (corrected for DAQ dead time)                                                          | C                   |
| `φ`         | Azimuthal angle between the lepton-scattering plane and the photon-proton plane                                      | degrees (°)         |
| `d⁴σ_UU`    | Four-fold unpolarized DVCS cross section, \(\dfrac{d^4\sigma_{UU}}{dx_B\,dQ^2\,dt\,d\phi}\)                          | pb GeV⁻⁴            |
| `d⁴σ_LU`    | Four-fold beam-helicity–dependent cross section difference, \(\dfrac{d^4\sigma_{LU}}{dx_B\,dQ^2\,dt\,d\phi}\)        | pb GeV⁻⁴            |
| `s`         | Center-of-mass energy squared, \(s = (p + k)^2\)                                                                     | GeV²                |
| `H^{λ,λ'}`  | Compton form factors (CFFs) indexed by photon helicities \(\lambda,\lambda'\) (e.g.\ \(H^{++},\tilde H^{++}\))       | —                   |







