# Elixir-SystemsBiology

Repository holding the contributions of the Systems Biology members of WP5 of ELIXIR 3

## Overview

### GEM modules
1. **gem_extract_exchange**: Extracts the exchange reactions of the provided gem as a CSV, which can then be modified and used as an input to modify the environment for the other GEM modules
2. **gem_check_memote**: Runs memote on provided GEM, returning snapshot report
3. **gem_escher_visualization**: Runs Escher with specified parameters, giving a modifiable html file with an overview of the metabolic network
4. **gem_flux_distribution**: Performs FBA to solve the provided model with the provided parameters, returning a flux distribution in the form of a CSV
5. **gem_flux_variability_analysis**: Performs FVA to return the reachable flux ranges for the proivded model and parameters
6. **gem_phenotype_phase_plane**: Runs a phenotype phase plane analysis for the provided model and parameters, showing how the model objective scales with the specified reactions
7. **gem_knockout**: Performs single or double knockout analysis for the provided model and parameters, returning all flux values for WT and KO for every (combination of) gene knockout
