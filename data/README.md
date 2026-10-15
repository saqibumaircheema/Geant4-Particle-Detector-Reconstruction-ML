# Data

The raw Geant4 event CSV files are not included in this public repository.

The analysis expects files under `data/raw/` for five particle species:

- gamma
- electron
- pi-
- neutron
- muon-

at beam energies of 100 MeV, 1 GeV, 4 GeV and 10 GeV.

Each event contains the true beam energy followed by detector-response values for five ECAL layers, five HCAL layers, five silicon-tracker layers and one muon-gas response.

The exact expected filenames are documented in the notebook.
