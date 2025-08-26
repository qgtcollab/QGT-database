# README

Ref. 20 

## Creator

Madhav Raghavendra / Marjorie Romero

## Contact

Email: [rdave8224@gmail.com](rdave8224@gmail.com), [marjoriemromero@gmail.com](marjoriemromero@gmail.com)

## Reference

\[Reference Link\]\[https://inspirehep.net/literature/1609452\]

## Notes

**THIS REFERENCE DOES NOT HAVE A CORRESPONDING EXCEL TABLE**

The lepton beam energy of the beam used in the experiment (measured at 6.00 GeV).  
The lepton type(s) used in this experiment were electrons and positrons.

The hadron used in the experiment was a proton, with a rest-energy constant of 0.938 GeV.

Collaboration was done with the CEBAF large acceptance spectrometer (CLAS).

Since there is no table in this article, the cuts/kinematic requirements shall be included in slightly greater detail here.

1. **Event Topology**  
   - Exactly one scattered **electron** in CLAS  
   - Exactly one recoiling **\(^4\)He** nucleus in the RTPC  
   - At least one real **photon** in the Inner Calorimeter (IC) or CLAS EC  
   - If multiple photons are found, only the **highest-energy** photon is used as the DVCS candidate  
2. **Primary Kinematic Cuts**  
   - `Q^2 > 1.0 GeV^2`  
   - (No explicit `W` or `x_B` cut; `x_B` is used later for binning)
3. **Background Vetoes**  
   - **π^0 rejection**: veto any event where two photons reconstruct `M_{γγ} ≃ m_{π^0}` within resolution  
4. **Exclusivity (Coherence) Cuts**  
   Applied to the reconstructed `e' ^4He' γ` system (all cuts typically at ±3σ or fixed bounds):  
   - **Coplanarity angle** `Δφ` between the (γ*,γ) and (γ*,^4He) planes  
   - **Missing energy** `E_miss` of the `e' ^4He' γ` system  
   - **Missing mass** `M_miss` of the `e' ^4He' γ` system  
   - **Missing transverse momentum** `pT_miss` of the `e' ^4He' γ` system  
   - **Missing mass squared** `MX^2` of the `e' ^4He'` system  
   - **Cone angle** `θ_{γX}` between the detected photon and the missing momentum of the `e' ^4He'` system  

   After all selections, ~3 200 coherent DVCS events remain for the asymmetry analysis.  

"A specially designed electromagnetic calorimeter [“inner calorimeter” (IC) [13]] was added to the CLAS detector and allowed the detection of photons for polar angles from about 5° to 16°, with full azimuthal coverage."


## Definitions & Units Table

| Symbol                 | Meaning                                                                                                      | Units                 |
|:----------------------:|:-------------------------------------------------------------------------------------------------------------|:---------------------:|
| `E_lepton`             | Incident lepton (electron or positron) beam energy                                                           | GeV                   |
| Lepton type            | Flavor of the beam lepton (e⁻ and e⁺)                                                                        | —                     |
| `M_p`                  | Proton (target hadron) rest mass                                                                             | 0.938 GeV/\(c^2\)     |
| Reaction               | Exclusive DVCS on \(^4\)He: \(e^\pm\,^4\)He → \(e' \, ^4\)He' γ\                                             | —                     |
| `Q^2`                  | Virtuality of the exchanged photon, \(Q^2 = -q^2\)                                                           | (GeV/\(c\))²          |
| `x_B`                  | Bjorken scaling variable, \(x_B = Q^2/(2\,M_p\,\nu)\)                                                        | —                     |
| `-t`                   | Four-momentum transfer squared to the recoil \(^4\)He nucleus, \(t = (p - p')^2\)                            | (GeV/\(c\))²          |
| `W`                    | Invariant mass of the virtual-photon–\(^4\)He system                                                         | GeV/\(c^2\)           |
| `E_γ`                  | Energy of the real photon detected in the Inner Calorimeter or CLAS EC                                       | GeV                   |
| `φ`                    | Azimuthal angle between the lepton-scattering plane and the photon–\(^4\)He production plane                 | degrees (°)           |
| `Δφ`                   | Coplanarity angle: difference between the (γ*,\(^4\)He') and (γ*,γ) planes                                   | degrees (°)           |
| `MM^2_{e'^{4}He'}`     | Squared missing mass of the \(e'\,^{4}\)He' X system                                                         | (GeV/\(c^2\))²        |
| `M_miss`               | Missing mass (√\(MM^2_{e'^{4}He'}\)) of the \(e'\,^{4}\)He' γ system                                         | GeV/\(c^2\)           |
| `E_miss`               | Missing energy of the \(e'\,^{4}\)He' γ system                                                               | GeV                   |
| `p_{T}^{miss}`         | Missing transverse momentum of the \(e'\,^{4}\)He' γ system                                                  | GeV/\(c\)             |
| `θ_{γX}`               | Cone angle between the measured photon and the missing momentum vector of the \(e'\,^{4}\)He' system         | milliradians (mrad)   |
| `IC coverage`          | Polar-angle acceptance of the Inner Calorimeter                                                              | 5°–16° (full φ)       |
| `N_events`             | Number of coherent DVCS events surviving all cuts                                                            | —                     |









