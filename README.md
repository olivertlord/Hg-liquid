<div align="center">

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/olivertlord/Hg-liquid/main?filepath=Hg_melting.ipynb)

</div>

<div style="line-height:1.6; font-size:1.1em;">

<p align="center"><i>Supplementary information for</i></p>

<h1 align="center" style="font-size:2.4em; margin-bottom:0.4em;">
Structure of Liquid Mercury at High Pressure
</h1>

<p align="center" style="font-size:1.15em; font-weight:600;">
James W. E. Drewitt<sup>a</sup>,
Benedict J. Heinen<sup>b</sup>,
Elena-Marie Rogmann<sup>b</sup>,
Oliver T. Lord<sup>b</sup>,
Francesco Turci<sup>a</sup>,
Adrian C. Barnes<sup>a</sup>,
Craig W. Wilson<sup>c</sup>,
Simon G. Macleod<sup>c</sup>,
and Annette K. Kleppe<sup>d</sup>
</p>

<p align="center">
<sup>a</sup> School of Physics, University of Bristol, H.H. Wills Physics Laboratory, Tyndall Avenue, Bristol, BS8 1TL, United Kingdom
<br>
<sup>b</sup> School of Earth Sciences, University of Bristol, Wills Memorial Building, Queens Road, Bristol, BS8 1RJ, United Kingdom
<br>
<sup>c</sup> Atomic Weapons Establishment, Aldermaston, Reading RG7 4PR, United Kingdom
<br>
<sup>d</sup> Diamond Light Source Ltd, Diamond House, Harwell Science and Innovation Campus, Chilton OX11 0DE, United Kingdom
</p>

<p align="center" style="font-size:1.05em;">
Published in <i>Physical Review B</i> (2026)
<br>
DOI: <a href="https://doi.org/10.1103/nffz-z1g8"><b>10.1103/nffz-z1g8</b></a>
</p>

<p align="center">
Jupyter Notebook written by
<a href="mailto:oliver.lord@bristol.ac.uk">Oliver T. Lord</a>
(<a href="http://www.bristol.ac.uk/earthsciences/people/person/oliver-t-lord/overview.html">School of Earth Sciences, University of Bristol</a>)
</p>

</div>

---

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
- `Hg_data_summary_input.csv` — Experimental mercury data
- `literature_data.csv` — Literature comparison data
- `references.bib` — Bibliography in BibTeX format

### Output Files

The notebook generates:
- `Hg_PT.png` — Phase diagram figure
- `Hg_data_summary_output.csv` — Processed data with calibrated pressures
- `Hg_melting.py` — Python script version of the notebook (for code checking)

### Citation

If you use this notebook in your research, please cite:

> Drewitt, J. W. E., Heinen, B. J., Rogmann, E.-M., Lord, O. T., Turci, F., Barnes, A. C., Wilson, C. W., Macleod, S. G., and Kleppe, A. K. *Structure of Liquid Mercury at High Pressure*, **Physical Review B** (2026). [doi.org/10.1103/nffz-z1g8](https://doi.org/10.1103/nffz-z1g8)

### License

Copyright © 2026 Oliver Lord

This notebook is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program. If not, see [https://www.gnu.org/licenses/](https://www.gnu.org/licenses/).

### Dependencies

See `environment.yml` for a complete list of dependencies.
