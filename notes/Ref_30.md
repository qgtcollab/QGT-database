# README

Ref. 30 

## Creator

Madhav Raghavendra / Marjorie Romero

## Contact

Email: [rdave8224@gmail.com](rdave8224@gmail.com), [marjoriemromero@gmail.com](marjoriemromero@gmail.com)

## Reference

\[Reference Link\]\[https://inspirehep.net/literature/866047\]

## Notes

**THIS REFERENCE DOES NOT HAVE A CORRESPONDING EXCEL TABLE**

The lepton beam energy of the beam used in the experiment (measured at 27.6 GeV).  
The lepton type(s) used in this experiment were electrons.

The hadron used in the experiment was a proton, with a rest-energy constant of 0.938 GeV.

Collaboration was done with HERMES.

Since there is no table in this article, the cuts/kinematic requirements shall be included in slightly greater detail here.

## Kinematic Cuts
- Exactly one scattered lepton track with the same charge as the beam  
- At least one real photon with energy \(E_\gamma > 5\) GeV  
- \(1.0 < Q^2 < 10.0\) GeV²  
- \(W^2 > 9.0\) GeV²  
- \(\nu < 22.0\) GeV  
- \(0.03 < x_N = \tfrac{Q^2}{2\,M_N\,\nu} < 0.35\)  
- Angle between virtual and real photon \(\theta_{\gamma^*\gamma}\) between 5 mrad and 45 mrad  

## Particle Identification and Fiducial Cuts
- Leptons identified by combining tracking, calorimeter energy deposition, and Cherenkov response  
- Photons required to have no associated track and time-of-flight consistent with \(\beta \approx 1\)  
- Geometrical fiducial cuts applied to restrict tracks and clusters to well-understood detector regions  

## Event Selection and Exclusivity
- Define exclusivity variables:
  - Missing-mass squared \(MM^2_{eX}\) of the lepton + X system  
  - Missing energy \(E_X\) in the \(e\,X\,\gamma\) channel  
  - Transverse missing momentum \(p_T\) in the \(e\,X\,\gamma\) channel  
  - Photon angle difference \(\theta_{\gamma X}\)  
  - Coplanarity angle \(\phi_C\)  
- For each variable, apply broad “cleanup” cuts to remove backgrounds, then require the value to lie within \(\pm 3\sigma\) of the exclusive peak  
- Exclusive region defined by  
  \[
    - (1.5\ \text{GeV})^2 \;<\; MM^2_{eX} \;<\; (1.7\ \text{GeV})^2
  \]  

## Corrections and Normalization
- Energy-loss and kinematic corrections applied via detailed Monte Carlo (impact \(\lesssim 2\%\))  
- Bin-by-bin radiative corrections (leading and next-to-leading order)  
- Beam polarization uncertainty (\(\approx 2.2\%\)) and other detector systematics included in final errors  
- Total systematic uncertainty \(\lesssim 10\%\)    

## Definitions & Units Table

| Symbol             | Meaning                                                                             | Units             |
|:------------------:|:-----------------------------------------------------------------------------------:|:-----------------:|
| `k, k'`            | Four-momenta of incoming and scattered lepton                                       | GeV/\(c\)         |
| `q = k - k'`       | Four-momentum of the virtual photon                                                 | GeV/\(c\)         |
| `q'`               | Four-momentum of the real (detected) photon                                         | GeV/\(c\)         |
| `p, p'`            | Four-momenta of initial target and recoiling nucleon                                | GeV/\(c\)         |
| `Q²`               | Virtuality of the exchanged photon, \(Q^2 = -q^2\)                                  | GeV²              |
| `x_N`              | Bjorken scaling variable, \(x_N = \dfrac{Q^2}{2\,M_N\,\nu}\)                        | —                 |
| `ν`                | Energy of the virtual photon                                                        | GeV               |
| `W²`               | Squared invariant mass of the virtual-photon–nucleon system, \(W^2 = (p + q)^2\)    | GeV²              |
| `E_γ`              | Energy of the detected real photon                                                  | GeV               |
| `θ_{γ*γ}`          | Angle between virtual- and real-photon three-momenta                                | mrad              |
| `MM²_{eX}`         | Missing-mass squared of the detected lepton + X system                              | GeV²              |
| `E_X`              | Missing energy in the \(e\,X\,γ\) channel                                           | GeV               |
| `p_T`              | Transverse missing momentum in the \(e\,X\,γ\) channel                              | GeV/\(c\)         |
| `θ_{γX}`           | Difference between calculated and measured photon polar angle                       | degrees (°)       |
| `φ_C`              | Coplanarity angle of virtual photon, real photon, and recoil system                 | degrees (°)       |










