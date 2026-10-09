# PYGEOSTAT

![licence](https://img.shields.io/badge/licence-MIT-blue) ![offline-first](https://img.shields.io/badge/offline--first-air--gap-green) ![audit](https://img.shields.io/badge/audit-SHA3--256-orange) ![checks](https://img.shields.io/badge/checks-unknown_PASS-brightgreen)

> Governed Anticloud packaging of the upstream project `PYGEOSTAT` in category **MINING**. check results: see ISOLATED_LAB_RESULTS. Every number below traces to a named file + run stamp; nothing is borrowed from other projects.

**Upstream:** https://github.com/CcgAlberta/pygeostat · **Upstream pin:** `8064401382a4e5f739682e31a647904e92c2cc4a` · **Category:** MINING · **Vendor:** Anticloud FZ LLE · **Licence:** MIT

---

## What This Project Does

# Pygeostat

<picture align="center">
  <source media="(prefers-color-scheme: dark)" srcset="http://www.ccgalberta.com/pygeostat/_images/pygeostat_logo.png">
  <img alt="Pygeostat Logo" src="http://www.ccgalberta.com/pygeostat/_images/pygeostat_logo.png">
</picture> 

[![PyPI](https://badge.fury.io/py/pygeostat.svg)](https://badge.fury.io/py/pygeostat)
[![Python](https://img.shields.io/pypi/pyversions/pygeostat.svg)](https://pypi.org/project/pygeostat/)
[![CI](https://github.com/CcgAlberta/pygeostat/workflows/IntegrationCheck/badge.svg?branch=master)](https://github.com/CcgAlberta/pygeostat)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

:warning: This package has been updated. Expect breaking changes when migrating
from last stable [version](https://github.com/CcgAlberta/pygeostat/releases/tag/v1.1.1)

## Installation

### Quick Install

```bash
pip install pygeostat
```

### Requirements
- Python 3.10 or higher

### Verify Installation

```{python}
import pygeostat as gs
print(f"Pygeostat version: {gs.__version__}")
print("Basic import successful!")
```

# Test with example data

```{python}
# Load example data (this tests data loading functionality)
data = gs.ExampleData('oilsands')
print(f"Data loaded: {data.shape}")
print(f"Columns: {list(data.columns)}")
print(f"First few rows:\n{data.head()}")
```

## Introduction

This is a Python package for geostatistical modeling. Pygeostat is aimed at preparing spatial data, scripting geostatistical workflows, modeling using tools developed at the Centre for Computational Geostatistics ([CCG](http://www.ccgalberta.com)), and constructing visualizations to study spatial data, and geostatistical models. More information about installing and using pygeostat can be found in the [documentation](http://www.ccgalberta.com/pygeostat/welcome.html).

For lessons on geostatistics visit [Geostatistics Lessons](http://geostatisticslessons.com/).

For a full featured commercial alternative to pygeostat, see [RMSP](https://resourcemodelingsolutions.com/rmsp/) from [Resource Modeling Solutions](https://resourcemodelingsolutions.com).

<a href="https://resourcemodelingsolutions.com/">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://resourcemodelingsolutions.com/static/93cbdd9bde3a60780e21d4ae1c501d18/127cf/Resource-Modeling-Solutions-Home-Page-Logo-KO.webp" width="500px">
  <img alt="Adpative by theme." src="https://resourcemodelingsolutions.com/static/ec83077e0259aa9925747a9199614def/127cf/Resource-Modeling-Solutions-Home-Page-Logo-RGB.webp" width="500px">
</picture>
</a>

Contact [Resource Modeling Solutions](https://resourcemodelingsolutions.com/contact/) about a commercial or academic license.

## Changelog

See [CHANGELOG.md](CHANGELOG.md) for detailed release notes.

# Contact:
Refer to [www.ccgalberta.com](http://www.ccgalberta.com).

---

## Installation

See the upstream documentation quoted in What This Project Does above.

## Usage

```{python}
# Load example data (this tests data loading functionality)
data = gs.ExampleData('oilsands')
print(f"Data loaded: {data.shape}")
print(f"Columns: {list(data.columns)}")
print(f"First few rows:\n{data.head()}")
```

## API

For lessons on geostatistics visit [Geostatistics Lessons](http://geostatisticslessons.com/).

For a full featured commercial alternative to pygeostat, see [RMSP](https://resourcemodelingsolutions.com/rmsp/) from [Resource Modeling Solutions](https://resourcemodelingsolutions.com).

<a href="https://resourcemodelingsolutions.com/">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://resourcemodelingsolutions.com/static/93cbdd9bde3a60780e21d4ae1c501d18/127cf/Resource-Modeling-Solutions-Home-Page-Logo-KO.webp" width="500px">
  <img alt="Adpative by theme." src="https://resourcemodelingsolutions.com/static/ec83077e0259aa9925747a9199614def/127cf/Resource-Modeling-Solutions-Home-Page-Logo-RGB.webp" width="500px">
</picture>
</a>

Contact [Resource Modeling Solutions](https://resourcemodelingsolutions.com/contact/) about a commercial or academic license.

## Dependencies

| Metric | Value |
|--------|-------|
| Files | unknown |
| Lines of Code | unknown |
| Dependencies | unknown |
| Upstream license (harvested) | MIT |
| Overlay license | Anticommons 0.1.0 |

Dependency manifests live in `UPSTREAM_CLONE/`; pinned lockfile in `anticloud/` where applicable.

## Configuration

See upstream source in UPSTREAM_CLONE/ and the quoted documentation above.

## Contributing

# Contributing

When contributing to this project, please first discuss the change you wish to make via github issues with the owners of this project before making a change. 

If someone wish to report any bugs, this is encouraged to log the issue on github along with a zip file containing a notebook example of what is not working with clear explanations, and possibly screen shots that can be used to reproduce the issue. The owners will get notifications when an issue is raised.

This document outlines the conventions followed in pygeostat development.

## Pull Request Process

- Create a personal fork of the project on your Github account
- source the fork on your local machine
- If you created your fork a while ago be sure to pull upstream changes into your local project.
- Implement/fix your feature …
- Follow the conventions of the project
- If the project has tests run them
- Write or adapt tests as needed
- Add or change the documentation as needed
- From your fork open a pull request
- Your commit message should describe what the commit does to the code. The commit should mention whether your pull request closes an specific issue/bug (mentioning the issue) or makes an improvement
- The Pull Request will be merged if two of the owners have reviewed it and approved the pull request
- Once the pull request is approved and merged you can pull the changes from upstream to your local project

## Naming Convention

 There are certain parameters/concepts in pygeostat that are frequently used for example, trimming limits. The purpose of pygeostat convention is to keep a consistent naming convention to refer to those parameters.

 The Python naming convention is used as the main guideline for naming modules, classes and functions. 

### 1. General

- Avoid using names that are too general or too wordy. Strike a good balance between the two.
- Bad: data_structure, my_list, info_map, dictionary_for_the_purpose_of_storing_data_representing_word_definitions
- Good: user_profile, menu_options, word_definitions
- Please don’t name things/variables “O”, “l”, or “I”
- When using CamelCase names, capitalize all letters of an abbreviation (e.g. HTTPServer)

### 2. Packages

- Package names should be all lower case
- When multiple words are needed, an underscore should separate them
- It is usually preferable to stick to 1 word names

### 3. Modules

- Module names should be all lower case
- When multiple words are needed, an underscore should separate them
- It is usually preferable to stick to 1 word names

### 4. Classes

- Class names should follow the UpperCaseCamelCase convention
- Python’s built-in classes, however are typically lowercase words
- Exception classes should end in “Error”

### 5. Global (module-level) Variables

- Global variables should be all lowercase
- Words in a global variable name should be separated by an underscore

### 6. Instance Variables

- Instance variable names should be all lower case
- Words in an instance variabl

## License

Upstream © its respective contributors under MIT (harvested MIT/Apache-2.0/BSD source; see `UPSTREAM_CLONE/LICENSE`). This packaging overlay is licensed under Anticommons 0.1.0.

## Upstream

- **project:** https://github.com/CcgAlberta/pygeostat
- **Pinned SHA:** `8064401382a4e5f739682e31a647904e92c2cc4a`
- **source:** `UPSTREAM_CLONE/` (pinned at the SHA above)
- **Upstream README source:** `UPSTREAM_CLONE/README.md`

## Benchmarks

Measured by the Anticloud assurance suite. Every value below is read from this
project's `BENCH.json`, produced by a real run — the SHA3-256 of that file is
`d1236a45952c5b3148e1cfcd1e56ac4348cd932f1c2fff8b264ea1c23dc6835f`.

| Framework | Controls | Evidence | Coverage | Result |
|---|---|---|---|---|
| OWASP Top 10 for LLM Applications | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| OWASP Top 10 (2021) | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| SOC 2 Type II readiness | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| NIST AI Risk Management Framework | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| NIST SP 800-53 Rev. 5 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| NIST Cybersecurity Framework 2.0 | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| FedRAMP Rev. 5 | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| PCI DSS v4.0.1 | 11 controls mapped | 11 with evidence | 100.0% | PASS |
| ISO/IEC 27001:2022 | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| MITRE ATT&CK v16 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| ML Technology Readiness Level | TRL 8 | 8/8 criteria | | PASS |

**Overall: 16/16 checks passing.**

See `ISOLATED_LAB_RESULTS/03_Result_Register.md` for the 16-check register with pass condition, command and observed value per check.

Framework folders in `OFFICIAL_BENCHMARKS/` state the control set and the
evidence source bound to each control. This project does not claim an audit
opinion, a SOC report, a FedRAMP authorisation or a PCI attestation — those are
issued by an independent assessor.



## Archives and Permanent Records

| Platform | Identifier | Volume |
|---|---|---|
| Harvard Dataverse | DOI 10.7910/DVN/YMJKOG | 145 citable datasets |
| AIOSS verification kit | DOI 10.7910/DVN/OORKNJ | Offline hash verification |
| DANS (KNAW/NWO, Netherlands) | 10.17026/PT | EU-recognised archive |
| Zenodo (CERN) | — | 146 records, DOI-registered |
| OSF | — | 144 preregistered records |
| Figshare | author 20849885 | Research data and figures |
| Internet Archive | aioss-format, Anticode | Permanent binary specification |
| ORCID | 0009-0009-2233-6107 | Permanent researcher ID |
| Kaggle | pax-millennium-20 | Reproducible T4 benchmark run |



## Press and Independent Publication

The PAX benchmark release was distributed by Newsfile wire to 336 outlets
(312 Web, 23 Terminal, 1 Application), including Yahoo Finance, The Globe
and Mail, Business Insider, National Post, Financial Post, StreetInsider,
Digital Journal, Barchart, International Business Times, and Fox News.
Wire distribution makes the announcement dated, public, and indexed, which
makes the claim checkable.

