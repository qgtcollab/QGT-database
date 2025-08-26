# README

Ref. 28 Tables 1-2

## Creator

Madhav Raghavendra / Marjorie Romero

## Contact

Email: [rdave8224@gmail.com](rdave8224@gmail.com), [marjoriemromero@gmail.com](marjoriemromero@gmail.com)

## Reference

\[Reference Link\]\[https://inspirehep.net/literature/1697033\]

## Notes

E_lepton denotes the lepton beam energy of the beam used in the experiment (measured at 5.88 GeV).  
The lepton type(s) used in this experiment were electrons

The hadron used in the experiment was a proton, with a rest-energy constant of 0.938 GeV.

Both satisfy the ep → e'p'γ condition.  

Collaboration was done with CEBAF large acceptance spectrometer (CLAS).

Data is taken from the unpolarized (beam-unpolarized) and the beam-helicity–dependent cross sections (d4SigUU and d4SigLU respectively). 

## Cuts, Event Selection, and Reuqirements

**Kinematic Cuts**
- 1.0 < Q² < 4.8 (GeV)²   
- 0.10 < x_b < 0.58
- 0.09 < -t < 2.00 GeV^2
- W > 2 GeV
- The polar angular acceptance of electrons was from 21◦ to 45◦
- The scattered electron minimum energy was 0.8 GeV.
- cut at θγ > 4.77 deg for two reasons:
- (a) To avoid any low angle area not covered by the IC.
- (b) Additionally, since the BH cross section is nearly singular at θγ → 0 deg, this cut allowed us to avoid relying only on the event generator whose cross sections varied rapidly in this region.


**Particle Identification & Fiducial Cuts**
- Electrons identified by CC + EC coincidence, sampling fraction within ±3σ of momentum-dependent mean, and geometrical fiducial cuts to avoid detector edges  
- Protons selected as positive tracks with |Δβ| < 0.05 between TOF and DC β, plus DC/TOF fiducial cuts  
- Photons reconstructed in EC (θ > 20°) or IC (θ < 20°), requiring β_rec > 0.9 and small-angle/low-energy cuts to remove Møller background  

**Event selection & exclusivity**
- Clean-up cuts on five variables (MM²_e′p′, E_X, p_T, θ_γX, φ_C), then final ±3σ cuts around fitted peaks  
- MM²_e′p′ within ±3σ of exclusive DVCS peak  
- Missing energy E_X and transverse momentum p_T within ±3σ of zero  
- Cone angle θ_γX and coplanarity φ_C within ±3σ of expectations 

**Corrections & Normalization**
- Energy-loss and kinematic corrections via GSIM (≤ 2%)  
- Bin-by-bin radiative corrections (~15% increase)  
- Overall elastic normalization factor ε = 0.926  
- Systematic uncertainties: global norm 5%, exclusivity 5.5%, fiducial 4.2%, radiative 3% (total ≈10%)  

## Relation of Tables to Excel Sheets

There are 2 Excel Sheets total, based on the different bins and functions present the article. 

**Note: There is no table in the article that matches with the Excel Sheets**

Each Excel Sheet is seperated based on 2 quantities: d4SigLU and d4SigUU. The definitions for these values are found below.

 **Table Column names and their corresponding Excel Sheet names**

average -t, x_B, or Q^2 values = t, xB, and Q2
 
Type of quantity used = obs

ϕ = phi

Amplitude of (corresponding quantity) = value

±δ(stat.) ±δ(syst.) are indicated as syst_u & stat_u 

## Definitions & Units Table

| Symbol           | Meaning                                                                                               | Units               |
|:----------------:|:------------------------------------------------------------------------------------------------------|:-------------------:|
| `k, k'`          | Four-momenta of the incoming (`k`) and scattered (`k'`) electron                                      | GeV/\(c\)           |
| `q = k – k'`     | Four-momentum of the virtual photon                                                                   | GeV/\(c\)           |
| `q'`             | Four-momentum of the real (detected) photon                                                           | GeV/\(c\)           |
| `p, p'`          | Four-momenta of the initial (`p`) and recoiling (`p'`) proton                                         | GeV/\(c\)           |
| `Q²`             | Virtuality of the exchanged photon, \(Q^2 = –\,q^2\)                                                  | GeV²                |
| `x_B`            | Bjorken scaling variable, \(x_B = Q^2 / (2\,p\cdot q)\)                                               | —                   |
| `ν`              | Virtual-photon energy                                                                                 | GeV                 |
| `W`              | Invariant mass of the virtual-photon–proton system, \(W^2 = (p + q)^2\)                               | GeV/\(c^2\)         |
| `t`              | Squared four-momentum transfer to the proton, \(t = (p – p')^2\)                                      | GeV²                |
| `ξ`              | DVCS skewness variable, \(\xi \approx x_B/(2 – x_B)\)                                                 | —                   |
| `φ`              | Azimuthal angle between the lepton-scattering plane and the photon-proton plane                       | degrees (°)         |
| `Δφ`             | Difference between hadronic- and photon-based determinations of φ                                     | degrees (°)         |
| `Δt`             | Difference between hadronic- and photon-based determinations of t                                     | GeV²                |
| `θ_{eγ}, θ_{en}` | Cone angles between the scattered electron and the photon or neutron                                  | degrees (°)         |
| `θ_{γX}`         | Cone angle between the detected photon and the missing-system direction                               | degrees (°)         |
| `MM²_{e'p'}`     | Missing-mass squared of the \(e p \to e' p' X\) system                                                | GeV²                |
| `E_X`            | Missing energy in the \(e p \to e' p' γ X\) system                                                    | GeV                 |
| `p_T`            | Transverse missing momentum in the \(e p \to e' p' γ X\) system                                       | GeV/\(c\)           |
| `φ_C`            | Coplanarity angle among virtual photon, real photon, and recoil proton                                | degrees (°)         |
| `E'`             | Scattered-electron energy                                                                             | GeV                 |
| `E_γ`            | Detected-photon energy                                                                                | GeV                 |
| `P_X`            | Missing momentum of the undetected system \(X\) in exclusivity cuts                                   | GeV/\(c\)           |
| `d⁴σ_UU`         | Four-fold unpolarized DVCS cross section, \(\dfrac{d^4\sigma_{UU}}{dx_B\,dQ^2\,dt\,d\phi}\)           | pb GeV⁻⁴            |
| `d⁴σ_LU`         | Four-fold beam-helicity–dependent cross section difference,                                           | pb GeV⁻⁴            |






