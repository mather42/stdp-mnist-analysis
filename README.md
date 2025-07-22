# STDP Energy Analysis

Biologically-inspired STDP network for MNIST classification with energy efficiency analysis.


## Current Issues

**Learning Problems:**
- 354/400 neurons biased to class 0, poor feature discrimination
- Energy paradox: 252K spikes/sample vs 200 for PyTorch (higher, not lower)
- Long training time? (1,989 seconds for 6K samples)


## Usage

Run the main notebook:
jupyter notebook stdp_analysis.ipynb

## Requirements

brian2, torch, numpy, matplotlib


***Note***: Work in progress for academic discussion. Energy framework is pretty solid, accuracy needs improvement.

### Acknowledgments
Thanks to **Mehul** for your mentorship and feedback :))

### License
MIT
