# README

Ref. 29 

## Creator

Madhav Raghavendra / Marjorie Romero

## Contact

Email: [rdave8224@gmail.com](rdave8224@gmail.com), [marjoriemromero@gmail.com](marjoriemromero@gmail.com)

## Reference

\[Reference Link\]\[https://inspirehep.net/literature/835694\]

## Notes

**THIS REFERENCE DOES NOT HAVE A CORRESPONDING EXCEL TABLE**

The lepton beam energy of the beam used in the experiment (measured at 27.6 GeV).  
The lepton type(s) used in this experiment were electrons and positrons.

The hadron used in the experiment was a proton, with a rest-energy constant of 0.938 GeV.

Collaboration was done with HERMES.

Since there is no table in this article, the cuts/kinematic requirements shall be included in slightly greater detail here.

## Cuts, Event Selection, and Requirements

**Kinematic Cuts**  
- Exactly one scattered lepton track with the same charge as the beam  
- At least one neutral cluster (photon) in the calorimeter with \(E_\gamma > 5\) GeV and no associated charged track  
- \(1.0 < Q^2 < 10.0\) GeV²  
- \(W > 3.0\) GeV²  
- \(v < 22.0\) GeV  
- \(0.03 < x_B < 0.35\)  
- Angle between virtual and real photon \(θ_{γ*γ}) between 2 mrad and 45 mrad  

**Particle Identification and Fiducial Cuts**  
- Leptons identified by combining tracking, calorimeter energy deposition, and Cherenkov detector response  
- Photons defined as neutral clusters with timing consistent
- Geometrical fiducial cuts applied to tracks and clusters to restrict to well-understood detector regions  

**Event Selection and Exclusivity**  
- Require exactly one lepton track and one photon cluster per event  
- Calculate missing-mass squared \(MM^2 = (q + p - q')^2\) and require 
  \[-\,(1.5\,\text{GeV})^2 < MM^2 < (1.7\,\text{GeV})^2\]  
- For \(M^2\), apply broad “cleanup” cuts then keep only events within of the exclusive peak

**Coherent vs. Incoherent Sample Enrichment**  
- Coherent-enriched: \(-t\) below the target-specific threshold  
- Incoherent-enriched: \(-t\) above that threshold  

**Corrections and Normalization**  
- Bin-by-bin radiative corrections applied to both BH and DVCS amplitudes  
- Semi-inclusive (\(\pi^0_{γ*γ}\)) background subtracted using Monte Carlo  
- Systematic uncertainties from beam polarization, background subtraction, acceptance, and fiducial cuts summed in quadrature

## Definitions & Units Table

| Symbol            | Meaning                                                                                    | Units             |
|:-----------------:|:------------------------------------------------------------------------------------------:|:-----------------:|
| `k, k'`           | Four-momenta of incoming and scattered lepton                                              | GeV/\(c\)         |
| `q = k – k'`      | Four-momentum of the virtual photon                                                        | GeV/\(c\)         |
| `q'`              | Four-momentum of the real (detected) photon                                                | GeV/\(c\)         |
| `p, p'`           | Four-momenta of initial target nucleon and recoiling system                                | GeV/\(c\)         |
| `Q²`              | Virtuality of the exchanged photon, \(Q^2 = -\,q^2\)                                       | GeV²              |
| `x_B`             | Bjorken scaling variable, \(x_B = Q^2 / (2\,p\cdot q)\)                                    | —                 |
| `ν`               | Virtual-photon energy                                                                      | GeV               |
| `W²`              | Squared invariant mass of the virtual-photon–nucleon system, \(W^2 = (p + q)^2\)           | GeV²              |
| `E_γ`             | Energy of the detected real photon                                                         | GeV               |
| `t`               | Squared four-momentum transfer to the nucleon, \(t = (p - p')^2\)                          | GeV²              |
| `x_N`             | Alternative Bjorken variable, \(x_N = Q^2 / (2\,M_N\,ν)\)                                  | —                 |
| `θ_{γ*γ}`         | Angle between virtual- and real-photon three-momenta                                       | mrad              |
| `MM²`             | Missing-mass squared of the detected lepton + X system, \((q + p - q')^2\)                 | GeV²              |
| `φ_C`             | Coplanarity angle among virtual photon, real photon, and recoil system                     | degrees (°)       |