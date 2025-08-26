# README

Ref. 26 

## Creator

Madhav Raghavendra / Marjorie Romero

## Contact

Email: [rdave8224@gmail.com](rdave8224@gmail.com), [marjoriemromero@gmail.com](marjoriemromero@gmail.com)

## Reference

\[Reference Link\]\[https://inspirehep.net/literature/2801515\]

## Notes

**THIS REFERENCE DOES NOT HAVE A CORRESPONDING EXCEL TABLE**

The lepton beam energy of the beam used in the experiment (measured at 10.6 GeV).  
The lepton type(s) used in this experiment were electrons.

The hadron used in the experiment was a proton, with a rest-energy constant of 0.938 GeV.

Collaboration was done with the CEBAF large acceptance spectrometer (CLAS).

Since there is no table in this article, the cuts/kinematic requirements shall be included in slightly greater detail here.

## Particle Identification & Fiducial Cuts
- Electrons identified via high-threshold Cherenkov counter and electromagnetic calorimeters (ECAL) at polar angles 7° ≲ θ_e ≲ 36°; drift chambers measure kinematics.
- Photons reconstructed in ECAL for 5° ≲ θ_γ ≲ 35° and in the Forward Tagger for 2.5° ≲ θ_γ ≲ 4.5°.
- Fiducial cuts remove detector edges to ensure uniform acceptance across CLAS12.

## Kinematic Region Cuts
- Electron momentum p_e > 1 GeV/c
- Neutron momentum p_n > 0.35 GeV/c (suppresses spectator neutrons)
- Photon energy E_γ > 2 GeV
- Cone angles between the scattered electron and neutrals (θ_{eγ}, θ_{en}) > 5° (rejects radiative/debris clusters)
- Deep-inelastic regime: Q² > 1 GeV² and W > 2 GeV

## Exclusivity Cuts
- Missing-mass squared cuts on the undetected system X:
  - For e n → e′ n γ X: |MM²_X(en→e′nγX)| < 0.1 GeV²
  - For e n → e′ n X: |MM²_X(en→e′nX)| < 2.5 GeV²
- Missing-momentum in e d → e′ n γ X: P_X < 0.35 GeV/c
- Δφ cut (plane-angle consistency): –1.5° < Δφ < 0.75°, where Δφ is the difference between hadronic and photon-based determinations of φ
- Δt cut (momentum-transfer consistency): |Δt| < 0.5 GeV²
- Cone angle between detected photon and missing particle in e n → e′ n γ X: θ_{γX} < 3°

## Background Subtraction and Systematics
- Accidentals estimated via shifted time windows and subtracted
- π⁰ contamination (π⁰ → γγ with only one photon detected) estimated from GEANT4-tuned MC and subtracted bin-by-bin

After all cuts and subtractions, 77 580 exclusive e d → e′ n γ(p) events remained for the beam-spin asymmetry analysis.

## Definitions & Units Table

| Symbol                   | Meaning                                                                                                           | Units                 |
|:------------------------:|:-----------------------------------------------------------------------------------------------------------------:|:---------------------:|
| `k, k'`                  | Four-momenta of incoming and scattered electron                                                                   | GeV/\(c\)             |
| `q = k - k'`             | Four-momentum of the virtual photon                                                                               | GeV/\(c\)             |
| `q'`                     | Four-momentum of the real (detected) photon                                                                       | GeV/\(c\)             |
| `p, p'`                  | Four-momenta of initial and recoiling nucleon                                                                     | GeV/\(c\)             |
| `Q²`                     | Virtuality of the exchanged photon, \(Q^2 = -\,q^2\)                                                              | GeV²                  |
| `x_B`                    | Bjorken scaling variable, \(x_B = Q^2/(2\,M\,\nu)\)                                                               | —                     |
| `ν`                      | Virtual-photon energy                                                                                             | GeV                   |
| `W`                      | Invariant mass of the virtual-photon–nucleon system, \(W^2 = (p+q)^2\)                                            | GeV/\(c^2\)           |
| `t`                      | Squared four-momentum transfer to the nucleon, \(t = (p - p')^2\)                                                 | GeV²                  |
| `ξ`                      | Skewness variable, \(\xi \approx x_B/(2 - x_B)\)                                                                  | —                     |
| `φ`                      | Azimuthal angle between the lepton-scattering plane and the photon-production plane                               | degrees (°) or rad    |
| `Δφ`                     | Difference between the two determinations of φ (nucleon-based vs. photon-based)                                   | degrees (°)           |
| `Δt`                     | Difference between the two determinations of t (nucleon-based vs. photon-based)                                   | GeV²                  |
| `θ_{eγ}, θ_{en}`         | Cone angles between the scattered electron and the photon or neutron                                              | degrees (°)           |
| `θ_{γX}`                 | Cone angle between the detected photon and the missing particle \(X\) in \(e n → e' n γ X\)                       | degrees (°)           |
| `MM²_X(en→e'nX)`         | Squared missing mass of \(X\) in \(e n → e' n X\)                                                                 | GeV²                  |
| `MM²_X(en→e'nγX)`        | Squared missing mass of \(X\) in \(e n → e' n γ X\)                                                               | GeV²                  |
| `P_X`                    | Missing momentum of \(X\) in \(e d → e' n γ X\)                                                                   | GeV/\(c\)             |
| `E_e`                    | Scattered-electron momentum (selection cut: \(p_e > 1\) GeV/\(c\))                                                | GeV/\(c\)             |
| `E_γ`                    | Detected-photon energy (selection cut: \(E_γ > 2\) GeV)                                                           | GeV                   |
| `p_n`                    | Recoil-neutron momentum (selection cut: \(p_n > 0.35\) GeV/\(c\))                                                 | GeV/\(c\)             |
| `P`                      | Average beam polarization                                                                                         | —                     |
| `N⁺, N⁻`                 | Event yields for positive and negative beam helicity                                                              | counts                |
| `A_{LU}`                 | Beam-spin asymmetry, \(A_{LU} = \frac{1}{P}\,\frac{N^+ - N^-}{N^+ + N^-}\)                                        | —                     |
| `s`                      | Center-of-mass energy squared, \(s = (p + k)^2\)                                                                  | GeV²                  |
| `F1, F2`                 | Dirac and Pauli form factors of the nucleon                                                                       | —                     |
| `k_{\rm geom}`           | Kinematic factor in BSA fit, \(k = -\,t/(4\,M^2)\)                                                                | —                     |
| `M`                      | Nucleon mass                                                                                                      | GeV/\(c^2\)           |









