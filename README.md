[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/olivertlord/Hg-liquid/main?filepath=Hg_melting.ipynb)

### Supplementary information for

## High-Pressure Structure of Liquid Mercury

#### James W. E. Drewitt<sup>a</sup>, Benedict J. Heinen<sup>a</sup>, Elena-Marie Rogmann<sup>a</sup>, Oliver T. Lord<sup>a</sup>, Francesco Turci<sup>a</sup>, Adrian C. Barnes<sup>a</sup>, Craig W. Wilson<sup>b</sup>, Simon G. Macleod<sup>b</sup>, and Annette K. Kleppe<sup>c</sup>

<sup>a</sup> School of Earth Sciences, University of Bristol, Wills Memorial Building, Queens Road, BS8 1RJ, United Kingdom

<sup>b</sup> AWE, Aldermaston, Reading, UK

<sup>c</sup> Diamond Light Source, Rutherford Appleton Laboratory, Didcot, UK

#### Jupyter Notebook Written by</a> [Oliver T Lord](mailto:oliver.lord@bristol.ac.uk), [(School of Earth Sciences, University of Bristol)](http://www.bristol.ac.uk/earthsciences/people/person/oliver-t-lord/overview.html)</a>

### Description

This notebook produces Figure 1 of the paper by:
- Processing the experimental data from the *in situ* SXRD measurements made in an externally heated diamond anvil cell
- Fitting Simon-Glatzel and Kechin melting curve models to the new phase state data as well as to previous data found in the literature

### Running the Notebook

#### Option 1: MyBinder (no installation required)

Click the "launch binder" badge above to run the notebook in your browser.

#### Option 2: Local Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/olivertlord/Hg-liquid.git
   cd Hg-liquid
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

### Required Input Files

The notebook requires the following data files (included in repository):
- `Hg_data_summary_input.csv` - Experimental mercury data
- `literature_data.csv` - Literature comparison data
- `references.bib` - Bibliography in BibTeX format

### Output Files

The notebook generates:
- `Hg_PT.png` - Phase diagram figure
- `Hg_data_summary_output.csv` - Processed data with calibrated pressures
- `Hg_melting.py` - Python script version of the notebook (for code checking)

### License

Copyright © 2025 Oliver Lord

This notebook is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program. If not, see [https://www.gnu.org/licenses/](https://www.gnu.org/licenses/).

### Citation

If you use this notebook in your research, please cite:

[Add citation information here when published]

## Dependencies

See `environment.yml` for a complete list of dependencies.
