# README

Ref. 31 Table 1

## Creator

Madhav Raghavendra / Marjorie Romero

## Contact

Email: [rdave8224@gmail.com](rdave8224@gmail.com), [marjoriemromero@gmail.com](marjoriemromero@gmail.com)

## Reference

[Multi-Differential DVCS Cross Section Measurement on the Proton in the Valence Region with CLAS12](https://arxiv.org/abs/2608.20585)

S. Lee et al. (CLAS Collaboration), arXiv:2608.20585v1 [nucl-ex], 2026.

## Notes

`E_lepton` denotes the incident lepton beam energy used in the experiment, measured at **10.6 GeV**.

The lepton used in this experiment was an **electron (`e-`)**. The beam was longitudinally polarized.

The hadron target was a **proton (`p`)** in an unpolarized liquid-hydrogen target. In the supplied table, `E_hadron` is **0.938272088 GeV**, corresponding to the proton rest-energy value used for the dataset.

The measured exclusive reaction is:

$$
e p \rightarrow e' p' \gamma
$$

The measurement was performed with the **CLAS12 detector in Hall B at Jefferson Lab**. The data were collected in fall 2018.

The paper reports the four-fold differential unpolarized DVCS cross section

$$
\frac{d^4\sigma_{ep\rightarrow e'p'\gamma}}
{dx_B\,dQ^2\,d|t|\,d\phi}
$$

and provides **1312 differential cross-section data points**. The supplied `Ref_31_Table_1.csv` likewise contains 1312 rows.

The measured phase space reported in the paper is:

* 0.06 < \(x_B\) < 0.58
* 1.00 < \(Q^2\) < 5.76 GeV²
* 0.11 < \(|t|\) < 1.00 GeV²

The reconstructed final state contains the scattered electron (\(e'\)), recoil proton (\(p'\)), and real photon (\(\gamma\)).

DVCS event candidates were selected from events containing **at least one electron, one proton, and one photon**.

The deep-inelastic event requirements reported in the paper include:

* \(W > 2\) GeV
* \(Q^2 > 1\) GeV²
* \(E_{e'} > 2\) GeV
* \(E_{\gamma} > 2\) GeV

The scattered electron was detected in the CLAS12 forward detector. Protons were detected predominantly in the central detector, while photons were detected either in the forward calorimeters or the Forward Tagger.

The exclusivity of the \(ep\rightarrow e'p'\gamma\) reaction was enforced with \(3\sigma\) cuts on kinematic quantities including squared missing mass, missing energy, minimum missing transverse momentum, and the coplanarity angle.

The Bethe-Heitler collinear singularity was suppressed by requiring the angle between the scattered electron and real photon to be **greater than 8 degrees**.

A significant background to the exclusive DVCS channel comes from

$$
ep\rightarrow e'p'\pi^0,
$$

when only one of the \(\pi^0\) decay photons is detected. A dedicated CLAS12 Monte Carlo sample was used to estimate this residual background.

The experimental cross section is calculated as

$$
\frac{d^4\sigma_{ep\rightarrow e'p'\gamma}}
{dx_B\,dQ^2\,d|t|\,d\phi}
=
\frac{N_{ep\rightarrow e'p'\gamma}}
{\mathcal{L}\,V\,A\,\epsilon_{\mathrm{det}}\,F_{\mathrm{bin}}\,F_{\mathrm{rad}}},
$$

where \(N\) is the measured yield, \(\mathcal{L}\) is integrated luminosity, \(V\) is the physical phase-space volume, \(A\) is detector acceptance, \(\epsilon_{\mathrm{det}}\) is detector efficiency, \(F_{\mathrm{bin}}\) is the bin-centering correction factor, and \(F_{\mathrm{rad}}\) is the radiative correction factor.

The datasets correspond to integrated luminosities of **40.1 fb⁻¹** and **42.7 fb⁻¹** for the two CLAS12 torus polarities.

Systematic uncertainties include contributions from event selection, fiducial cuts, momentum resolution, background subtraction, acceptance-model dependence, radiative corrections, bin-centering corrections, and overall normalization.

The dominant reported bin-dependent systematic contributions are:

* Fiducial cuts: **10.1%**
* Event selection: **8.1%**
* Momentum resolution: **7.4%**
* Acceptance-model dependence: **5.8%**
* Total bin-by-bin systematic uncertainty: **18.6%**
* Radiative uncertainty: **below 3%**
* Normalization-factor uncertainty: **31%**
* Approximate total systematic uncertainty after combining bin-by-bin and normalization uncertainties in quadrature: **37%**

## Table 1 Overview

`Ref_31_Table_1.csv` contains the measured four-fold unpolarized cross-section data. Each row represents one measured \((x_B,t,Q^2,\phi)\) point.

The observable is stored as `d4SigUU`, representing the unpolarized four-fold differential cross section

$$
d4SigUU =
\frac{d^4\sigma_{UU}}
{dx_B\,dQ^2\,d|t|\,d\phi}.
$$

The cross-section values are given in **nb GeV⁻⁴**.

The supplied table contains the following columns:

|   Column   | Meaning                                                                    | Units / Values |
| :--------: | :------------------------------------------------------------------------- | :------------- |
|    `xB`    | Average Bjorken scaling variable \(x_B\) for the data point                | —              |
|     `t`    | Four-momentum transfer squared \(t\); the CSV stores negative \(t\) values | GeV²           |
|    `Q2`    | Photon virtuality \(Q^2\)                                                  | GeV²           |
|    `phi`   | Azimuthal angle \(\phi\) between the leptonic and hadronic/DVCS planes     | degrees (°)    |
|  `deg/rad` | Angular-unit indicator for `phi`                                           | `deg`          |
|    `bin`   | Kinematic-bin identifier                                                   | integer        |
|    `obs`   | Observable identifier                                                      | `d4SigUU`      |
|   `value`  | Measured four-fold differential cross section                              | nb GeV⁻⁴       |
|   `units`  | Units associated with `value`                                              | `nb GeV^-4`    |
|  `stat_u`  | Statistical uncertainty on `value`                                         | nb GeV⁻⁴       |
|  `syst_u`  | Systematic uncertainty on `value`                                          | nb GeV⁻⁴       |
|    `col`   | Experimental collaboration                                                 | `CLAS`         |
|  `lepton`  | Incident lepton species                                                    | `e-`           |
| `E_lepton` | Incident electron beam energy                                              | GeV            |
|  `hadron`  | Target hadron                                                              | `p`            |
| `E_hadron` | Proton rest-energy value recorded in the dataset                           | GeV            |

### Example Table Entry

The first entry in the supplied CSV is:

|  `xB` | `t` [GeV²] | `Q2` [GeV²] | `phi` [deg] | `bin` |   `obs`   | `value` [nb GeV⁻⁴] | `stat_u` | `syst_u` |
| :---: | :--------: | :---------: | :---------: | :---: | :-------: | :----------------: | :------: | :------: |
| 0.072 |   −0.130   |    1.091    |    157.5    |   0   | `d4SigUU` |       2.9603       |  0.55649 |   1.046  |

The table contains multiple \(\phi\) measurements within the multidimensional kinematic bins, allowing the azimuthal dependence of the DVCS cross section to be measured.

## Relation of the Paper to the CSV Table

The paper reports the multi-differential unpolarized DVCS cross section as a function of four kinematic variables:

$$
(x_B,Q^2,|t|,\phi).
$$

These quantities correspond to the CSV columns `xB`, `Q2`, `t`, and `phi`.

The paper generally expresses the momentum-transfer dependence using \(|t|\), whereas the CSV stores `t` as a negative value. Therefore, for the physical magnitude used in the paper,

$$
|t|=-t
$$

for the negative `t` values in this dataset.

The measured cross section corresponds to the CSV `value` column, while the associated statistical and systematic uncertainties are stored as `stat_u` and `syst_u`, respectively.

The paper presents representative cross sections graphically in Figures 4–6 and states that all measured cross-section data points are provided in the CLAS Physics Database. The supplied CSV contains the numerical data in a tabular format suitable for analysis.

## Definitions & Units Table

|  Symbol/CSV Name | Meaning                                                                                           | Units  |
|    `E_lepton`    | Incident electron beam energy                                                                     | GeV    |
|    `E_hadron`    | Proton rest-energy value recorded in the dataset                                                  | GeV    | 
|    `xB`/\(x_B\)  | Bjorken scaling variable, \(x_B = Q^2/(2p_N\cdot q)\)                                             | —      |
|    `Q2`/\(Q^2\)  | Photon virtuality, \(Q^2 = -(p_{e'}-p_e)^2\)                                                      | GeV²   |
|      `t`/\(t\)   | Four-momentum transfer squared to the proton, \(t=(p_N-p_{N'})^2\)|                               | GeV²   |
|       (|t|)      | Magnitude of the four-momentum transfer squared                                                   | GeV²   |
|   `phi`/\(\phi\) | Azimuthal angle between lepton scattering plane and plane spanned by virtual photon and recoil proton, using Trento convention | (°) |
|      \(W\)       |Invariant mass of the virtual-photon–proton system, \(W=\sqrt{(q+p_N)^2}\)                         | GeV    |
|    \(E_{e'}\)    | Energy of the scattered electron                                                                  | GeV    |
|   \(E_{\gamma}\) | Energy of the detected real photon                                                                | GeV    |
|    \(M_X^2\)     | Squared missing mass used as an exclusivity variable                                              | GeV²   |
|     `d4SigUU`    | Four-fold unpolarized \(ep\rightarrow e'p'\gamma\) differential cross section                     |nb GeV⁻⁴|
|     `value`      | Numerical value of `d4SigUU`                                                                      |nb GeV⁻⁴|
|     `stat_u`     | Statistical uncertainty on the measured cross section                                             |nb GeV⁻⁴|
|     `syst_u`     | Systematic uncertainty on the measured cross section                                              |nb GeV⁻⁴|
|  \(\mathcal{L}\) | Integrated luminosity                                                                             | fb⁻¹   | 
|      \(V\)       | Physical phase-space volume of a bin                                                              | —      |
|      \(A\)       | Detector acceptance for \(ep\rightarrow e'p'\gamma\)                                              | —      |
| \(\epsilon_{\mathrm{det}}\) | Detector efficiency                                                                    | —      | 
|     \(F_{\mathrm{bin}}\)    | Bin-centering correction factor                                                        | —      |   
|     \(F_{\mathrm{rad}}\)    | Radiative correction factor                                                            | —      |
|    \(T_{\mathrm{DVCS}}\)    | DVCS scattering amplitude                                                              | —      |
|     \(T_{\mathrm{BH}}\)     | Bethe-Heitler scattering amplitude                                                     | —      |
|            \(I\)            | DVCS–Bethe-Heitler interference term, \(T_{\mathrm{DVCS}}T_{\mathrm{BH}}^* + T_{\mathrm{BH}}T_{\mathrm{DVCS}}^*\)  | —   |
|            `col`            | Collaboration associated with the measurement                                          | `CLAS` |
|           `lepton`          | Incident lepton type                                                                   | `e-`   |    
|           `hadron`          | Target hadron                                                                          | `p`    |

## Physics Context

Deeply Virtual Compton Scattering (DVCS) provides access to generalized parton distributions (GPDs), which encode correlations between the longitudinal momentum and transverse spatial distributions of partons inside the proton.

The experimentally measured \(ep\rightarrow e'p'\gamma\) final state contains contributions from both DVCS and the Bethe-Heitler (BH) process. Their amplitudes interfere coherently:

$$
\frac{d^4\sigma}{dx_B\,dQ^2\,d|t|\,d\phi}
=
2\pi\Gamma
\left(
|T_{\mathrm{DVCS}}|^2
+
|T_{\mathrm{BH}}|^2
+
I
\right).
$$

The absolute DVCS cross section provides sensitivity to both the real and imaginary parts of Compton form factors (CFFs). The paper emphasizes that these measurements expand the available valence-region phase space and provide additional constraints for future CFF and GPD extractions.
