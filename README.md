## Overview

This project was developed during an REU at UW-Madison in Summer 2026 under the mentorship of Prof. Christy Tremonti and graduate student Marissa Perry. The goal of this project is to identify Very Massive Star (VMS) candidates in nearby galaxies using data from DESI DR1.

## Structure

- `01_query_DESI_for_VMS_candidates.ipynb`
- `02_inspect_VMS_candidates.ipynb`
- `plots/` - visualizations (not tracked in git)
- `data/` - queried dataframes (not tracked in git)

## Setup

A conda environment for this project can be set up by running:
```bash
conda env create -f desi_env.yml
```

Activate this environment with
```bash
conda activate desi_env
```

## Acknowledgements

This project utilizes resources provided by

- DESI: 

citation: DESI Collaboration et al. (2026) “Data Release 1 of the Dark Energy Spectroscopic Instrument”

acknowledgement:
This research used data obtained with the Dark Energy Spectroscopic Instrument (DESI). DESI construction and operations is managed by the Lawrence Berkeley National Laboratory. This material is based upon work supported by the U.S. Department of Energy, Office of Science, Office of High-Energy Physics, under Contract No. DE–AC02–05CH11231, and by the National Energy Research Scientific Computing Center, a DOE Office of Science User Facility under the same contract. Additional support for DESI was provided by the U.S. National Science Foundation (NSF), Division of Astronomical Sciences under Contract No. AST-0950945 to the NSF’s National Optical-Infrared Astronomy Research Laboratory; the Science and Technology Facilities Council of the United Kingdom; the Gordon and Betty Moore Foundation; the Heising-Simons Foundation; the French Alternative Energies and Atomic Energy Commission (CEA); the National Council of Humanities, Science and Technology of Mexico (CONAHCYT); the Ministry of Science and Innovation of Spain (MICINN), and by the DESI Member Institutions: www.desi.lbl.gov/collaborating-institutions. The DESI collaboration is honored to be permitted to conduct scientific research on I’oligam Du’ag (Kitt Peak), a mountain with particular significance to the Tohono O’odham Nation. Any opinions, findings, and conclusions or recommendations expressed in this material are those of the author(s) and do not necessarily reflect the views of the U.S. National Science Foundation, the U.S. Department of Energy, or any of the listed funding agencies.

- SPARCL and Astro Data Lab:

citation: Juneau et al., "SPARCL: SPectra Analysis and Retrievable Catalog Lab", Conference Proceedings for ADASS XXXIII, 2024 https://doi.org/10.48550/arXiv.2401.05576

keywords: \facility{Astro Data Lab} and \software{SPARCL (Juneau et al. 2024)} 

acknowledgement:
This research uses services or data provided by the SPectra Analysis and Retrievable Catalog Lab (SPARCL) and the Astro Data Lab, which are both part of the Community Science and Data Center (CSDC) program at NSF National Optical-Infrared Astronomy Research Laboratory. NOIRLab is operated by the Association of Universities for Research in Astronomy (AURA), Inc. under a cooperative agreement with the National Science Foundation.

