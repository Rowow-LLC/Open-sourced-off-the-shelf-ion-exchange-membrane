# Contributing to the Open-Source Ion Exchange Membrane Project

Thank you for your interest in this project. Everything here is released under CERN-OHL-S, and community builds, test data, and improvements are what move it forward.

## Ways to Contribute

### 1. Report a Build (most valuable)
If you made the membrane, we want to hear about it whether it worked or not. Open a [Build Report issue](../../issues/new?template=build-report.yml) with your materials, process, and results. Verified builds are added to [BUILDS.md](BUILDS.md), the public replication log.

### 2. Submit Characterization Data
Measured something? Ion exchange capacity, resistance, selectivity, durability, anything. Add a row to `data/membrane_characterization.csv` via pull request, or attach your numbers to a Build Report issue and we will enter them. See [data/README.md](data/README.md) for the measurement protocol and column definitions.

### 3. Improve the Process
Found a better resin, solvent ratio, drying method, or application technique? Open an issue describing what you changed and what you observed. Side-by-side comparisons with the baseline recipe are especially useful.

### 4. Improve Documentation
Typos, unclear steps, translations, better diagrams: open an issue or a pull request.

### 5. Ask Questions
Use the [Question template](../../issues/new?template=question.yml) or join the [Discord](https://discord.gg/e7CmU2ekky). Check the FAQ on the docs site first.

## Pull Request Guidelines

- One topic per PR.
- For data PRs: add rows to the CSV, never modify or delete existing rows. Include units exactly as the column headers specify.
- For document changes: explain the reasoning in the PR description.
- By submitting, you agree your contribution is released under CERN-OHL-S, the same as the rest of the project.

## Reporting Results Honestly

Negative results are contributions. A membrane that cracked, leaked, or showed poor selectivity teaches the community as much as a success. Report what actually happened.

## Safety

This project involves solvents (THF, MEK, cyclohexanone), fine resin dust, and electrochemical cells that can generate chlorine and hydrogen gas. Read the safety video and documentation before building anything. Work ventilated, wear PPE, and follow your local regulations. Nothing in this repository is a substitute for chemical safety training.

## Licensing

CERN-OHL-S v2, the CERN Open Hardware Licence (Strongly Reciprocal). You can use, make, sell, and improve the work, including commercially, as long as you pass on your complete design source under the same license. Contributions are accepted under the same license.
