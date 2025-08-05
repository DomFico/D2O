# D2O Surrogate Model

This repository provides a surrogate Ridge model for predicting HDX–MS deuterium uptake from AlphaFold structures. It includes a Colab notebook for Stage‑1 (per‑residue predictions) and optional Stage‑2 correction against experimental data.

## Features

- **Stage‑1**: compute residue features, predict rates & weights, output JSON and uptake plots.
- **Stage‑2**: load experimental CSV, map to peptides, apply correction model, output metrics and JSON.

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/YourUsername/D2O-surrogate.git
   cd D2O-surrogate
   ```
2. Upload the directory to Colab.
3. Open `D2O.ipynb`, install dependencies, and follow these steps:
   - Enter the PDB path, Stage‑1 JSON, output directory, system label, and simulation parameters.
   - (Optional) Enter experimental CSV, Stage‑2 JSON, state filter, and exposure times.
4. Run the notebook cells to generate JSON outputs and accuracy plots.

## Contributing

Issues and pull requests are welcome. 
Please do let me know how the results are for you!
