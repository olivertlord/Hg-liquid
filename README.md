# High-Pressure Structure of Liquid Mercury

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/YOUR_USERNAME/YOUR_REPO_NAME/main?filepath=Hg_melting.ipynb)

Jupyter notebook containing the code used for producing Figure 1 of the paper (the high-pressure phase diagram of mercury).

## Authors

James W. E. Drewitt, Benedict J. Heinen, Elena-Marie Rogmann, Oliver T. Lord, Francesco Turci, Adrian C. Barnes, Craig W. Wilson, Simon G. Macleod, and Annette K. Kleppe

**Notebook by:** Oliver T. Lord ([School of Earth Sciences, University of Bristol](http://www.bristol.ac.uk/earthsciences/))

## Description

This notebook produces Figure 1 of the paper by:
- Processing the experimental data from the *in situ* SXRD measurements made in an externally heated diamond anvil cell
- Fitting Simon-Glatzel and Kechin melting curve models to the new phase state data as well as to previous data found in the literature

## Running the Notebook

### Option 1: MyBinder (no installation required)

Click the "launch binder" badge above to run the notebook in your browser.

### Option 2: Local Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
   cd YOUR_REPO_NAME
   ```

2. **Create the conda environment:**
   ```bash
   conda env create -f environment.yml
   ```

3. **Activate the environment:**
   ```bash
   conda activate hg_melting
   ```

4. **Launch Jupyter:**
   ```bash
   jupyter notebook Hg_melting.ipynb
   ```

## Required Input Files

The notebook requires the following data files (included in repository):
- `Hg_data_summary_input.csv` - Experimental mercury data
- `literature_data.csv` - Literature comparison data
- `references.bib` - Bibliography in BibTeX format

## Output Files

The notebook generates:
- `Hg_PT.png` - Phase diagram figure
- `Hg_data_summary_output.csv` - Processed data with calibrated pressures
- `Hg_melting.py` - Python script version of the notebook (for code checking)

## License

Copyright © 2025 Oliver Lord

This notebook is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program. If not, see [https://www.gnu.org/licenses/](https://www.gnu.org/licenses/).

## Citation

If you use this notebook in your research, please cite:

[Add citation information here when published]

## Dependencies

See `environment.yml` for a complete list of dependencies.
