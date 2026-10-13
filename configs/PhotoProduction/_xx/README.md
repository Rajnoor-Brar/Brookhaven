# Parked: other generators

High-Energy's `configs/PhotoProduction/xx/`: the chain checks of Herwig, Sherpa, Whizard and MadGraph
(with a Delphes card), migrated to the run TOML's v3 form. `hep check` skips this folder. To run one,
move it and its cards up into `configs/PhotoProduction/`, where its `card = "…"` names are found.
Herwig and Sherpa need the lab PC's stack rebuilt first (`hep stack build --rebuild-broken`).
