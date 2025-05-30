# Peak Analysis Tool

This Python project provides a GUI-assisted tool to analyze spectral peaks from CSV data files, with a focus on Raman spectroscopy peaks (D, G, 2D). It fits peaks using Lorentzian, Gaussian, Voigt, and double Lorentzian models and selects the best fit based on Bayesian Information Criterion (BIC).

## Features

- Load multiple CSV files containing spectral data
- Interactive prompt to specify which peaks to analyze (D, G, 2D)
- Automated peak fitting with multiple models and selection of best fit
- Calculation of peak area, intensity, and full width at half maximum (FWHM)
- Plotting of raw data and fitted peaks for visual inspection
- Summary of average peak parameters and intensity/area ratios via message boxes


## Tech Stack
- Python
- Tkinter (GUI dialogs)
- NumPy
- Pandas
- Matplotlib
- SciPy (peak detection and curve fitting)

## How to run

Run the main script:

```bash
python peak_analysis.py
