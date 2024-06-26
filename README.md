
# Flexible Manufacturing Simulation

## Overview

This repository contains the codebase for the Flexible Manufacturing Simulation platform, developed by the Center for Advanced Systems Research and Education (CASRE). This simulation tool provides a robust framework for modeling and analyzing manufacturing processes with various configurations, either using series or parallel line setups.
for a brief presentation, visit [this slides](https://liveutk-my.sharepoint.com/:p:/r/personal/ssharifn_vols_utk_edu/Documents/Sharing_Media(s)/Simulation.pptx?d=w3f972a9573294970ade6446deb5fb5d8&csf=1&web=1&e=PFxVN8). 

![Felx_man_2](https://github.com/ebrahimss/Flexible-Manufacturing-Simulation/assets/54449000/e12487ea-36f5-4c65-bc6c-27832ae31494)

## Features

- **Simulation Options**: Configure simulations with different buffer sizes to operate under pull or push system paradigms.
- **Stochastic, Deterministic, and Conditional Processes**: Model process bottlenecks with various categorizations to suit different industrial scenarios.
- **Optimization Engine**: Utilizes advanced algorithms to propose optimizations and future state scenarios for manufacturing processes.
- **Key Metrics Reporting**: Generate reports for single runs or multiple replications to analyze the consistency and efficiency of manufacturing operations.

## Getting Started

### Prerequisites

- Python 3.8 or later
- NumPy, pandas, matplotlib (for data handling and visualization)

### Installation

Clone the repository to your local machine:

```bash
git clone https://github.com/ebrahimss/Flexible-Manufacturing-Simulation.git
cd Flexible-Manufacturing-Simulation
```

Install the required Python packages:

```bash
pip install -r requirements.txt
```

### Running Simulations

To run a simulation, navigate to the source directory and execute the main script:

```bash
python run_simulation.py
```

Adjust the simulation settings in the configuration file `config.json` as needed.

## Documentation

For more detailed information about how to configure and use the simulation tool, check the `docs` folder in this repository.

## Contributing

We welcome contributions from the community. If you're interested in enhancing the features of the Flexible Manufacturing Simulation, please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- CASRE for supporting the development of this simulation tool.
- Contributors and community members who have participated in improving this platform.
