# README

Ref. 25 Table 01 & 02

## Creator

Marjorie Romero / Madhav Raghavendra

## Contact

Email: [rdave8224@gmail.com](rdave8224@gmail.com), [marjoriemromero@gmail.com](marjoriemromero@gmail.com)

## Reference

\[Reference Link\]\[https://arxiv.org/abs/0812.2517]

## Notes

This study provides first measurements of the beam-spin asymmetry in DVCS with a lepton beam energy of over 10 GeV.

Experiment Overview

- Facility: Thomas Jefferson National Accelerator Facility (JLab), Hall B  
- Spectrometer: CLAS12  
- Process: Deeply Virtual Compton Scattering (DVCS): ep ----> e'p'γ 
- Data Periods:  
  - Fall 2018: 10.6 GeV beam  
  - Spring 2019: 10.2 GeV beam  
- Target: Unpolarized liquid hydrogen (\( \mathrm{H}_2 \))  
- Beam Polarization: ~86% longitudinal polarization  
- Statistics: ~1600 new data points, 64 bins in Q², x_B , and t 

Central Detector
- Polar angle coverage: 35°–125°
- Tracking: Silicon and Micromegas trackers
- Particle ID: Time-of-flight scintillators

Forward Detector
- Magnetic field: Toroidal
- Tracking: Drift chambers
- Electron ID: High-threshold Čerenkov + Electromagnetic calorimeter
- Hadron ID: Scintillator time-of-flight

Photon Detection
- Standard electromagnetic calorimeter
- Forward tagger: 2°–5° polar angle coverage

Event Selection and Experimental Cuts

   Final State Requirements
    - One high-energy electron
    - One proton
    - ≥1 photon with energy > 2 GeV

Exclusivity Cuts
To isolate \( ep ---> e'p'γ \), the following cuts were applied:

| Variable                 | Description                                                                                     | Cut Value          |
|------------------------  |-------------------------------------------------------------------------------------------------|--------------------|
|  \theta_{γγ}             | Cone angle between detected photon and expected photon direction                                | \( < 0.6^\circ \)   |
|  E_{\text{miss}}         | Missing energy in ep ----> e'p'γ                                                                |  < 0.5  GeV     |
|  p_{T,\text{miss}}       | Missing transverse momentum                                                                     |  < 0.125  MeV   |
|  M^2_{e'γ X}             | Squared missing mass in ep ----> e'γ X ; should peak at proton mass                             |  < 1.25 GeV²  |

π⁰ Contamination Correction
- Main background: ep ---> e'p'π⁰  (π⁰ mimics single photon)
- Used 1500 simulated π⁰ ---> γγ  decays per real π⁰

Kinematic Binning

- 16 Q² –\( x_B \) bins (see Fig. 3 in paper)
- Each bin subdivided into 4 bins in t
- Variable-width binning in ϕ to optimize stats and minimize acceptance effects

Radiative Corrections and Bin Migration

- Radiative effects (e.g., soft photon emission, QED loops) corrected using DVCSGEN with radiative modules
- Bin migration matrix applied from simulation based on Akushevich and Ilyichev (2018)


Table 01 Excel file:

- Fall 2018
- 10.6 GeV Beam
- Number of entries: 1006 beam-spin asymmetry (BSA) measurements
- Purpose: BSA data for DVCS process collected with a 10.6 GeV electron beam
- Columns include:
  - `xB`: Bjorken scaling variable
  - `t`: Mandelstam variable (momentum transfer)
  - `Q2`: Photon virtuality
  - `phi`: Azimuthal angle between scattering planes
  - `obs`: Observable measured (e.g., BSA)
  - `value`: Measured value
  - `stat+syst_u`: Combined statistical and systematic uncertainty
  - `lepton`, `E_lepton`: Detected lepton and energy
  - `hadron`, `E_hadron`: Detected hadron and energy

Table 02 Excel file:
- Spring 2019
- 10.2 GeV Beam

- Number of entries: 529 beam-spin asymmetry (BSA) measurements
- Purpose: BSA data for DVCS process collected with a 10.2 GeV electron beam
- Same column structure as Ref_25_01.xlsx

Each row corresponds to a specific kinematic bin defined by (Q², x_B, t, ϕ), and reports the beam-spin asymmetry measurement used in Figures 4 and 5 of the published article.
