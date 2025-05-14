# PeriodicTable

## Overview
This repository provides structured data and explanations for key chemistry concepts including:
- Electron configurations
- Electronegativity values
- Ionization energies
- Standard electrode potentials

The data is presented in both human-readable and machine-readable formats for easy integration into educational materials, research projects, or software applications.

## Concepts Covered

### Electron Configuration
- Standard and noble gas notation formats
- Orbital filling rules and exceptions
- Examples for all elements

### Electronegativity
- Pauling scale values
- Periodic trends
- Comparison tables

### Ionization Energies
- Successive ionization energies
- Measurement units (eV and kJ/mol)
- Periodic trends

### Standard Electrode Potentials
- Redox half-reactions
- Measurement conditions
- Application in predicting reaction spontaneity

## Usage
To use the JSON data files:
```python
import json

with open('data/electron_configurations.json') as f:
    configs = json.load(f)
print(configs['Na'])
```

## Contributing
Contributions are welcome! Please:
1. Fork the repository
2. Create a new branch
3. Submit a pull request with your additions/corrections

## Sources
All data has been compiled from reputable chemistry references including:
- CRC Handbook of Chemistry and Physics
- NIST Chemistry WebBook
- Linus Pauling's electronegativity scale
