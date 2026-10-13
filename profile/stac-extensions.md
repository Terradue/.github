# STAC Extensions

Terradue's STAC extension specifications and PySTAC implementations, selected from the [repository directory](README.md#stac).

- [Extensions Specification](#extensions-specification)
- [pystac Extensions implementation](#pystac-extensions-implementation)

## Extensions Specification

This alphabetical list includes the specifications in [the profile README](README.md#extensions-specification), excluding repositories marked as forks. The columns follow the [STAC Extensions directory](https://stac-extensions.github.io/).

### Alphabetical list

| Title | Field Name Prefix | Scope | Maturity | Version | Release Date | Description |
| --- | --- | --- | --- | --- | --- | --- |
| [Aeronet](https://github.com/Terradue/aeronet-stac-extension) | aeronet | Item | Proposal | Unreleased | N/A | Describes AERONET ground-based aerosol observation stations. |
| [Disasters Charter](https://github.com/Terradue/stac-extensions-disaster) | disaster | Collection, Item | Proposal | 1.1.0 | 2024-06-05 | Describes disaster events and International Charter activations, areas, and acquisitions. |
| [InSAR](https://github.com/Terradue/stac-extensions-insar) | insar | Item | Proposal | 1.0.0 | 2024-03-11 | Describes interferograms and related products from interferometric synthetic aperture radar processing. |
| [Offset Tracking](https://github.com/Terradue/stac-extensions-offset-tracking) | offset-tracking | Item | Proposal | Unreleased | N/A | Offset Tracking extension proposal; the specification still contains template placeholders. |

Metadata follows the linked specification READMEs; released versions and dates follow the [STAC Extensions directory](https://stac-extensions.github.io/). Unreleased entries have no published GitHub release; version numbers in template schema identifiers are not treated as releases. This is a manually maintained snapshot, reviewed on 2026-10-13.

### By maturity

All four specifications currently declare **Proposal** maturity:

- [Aeronet](https://github.com/Terradue/aeronet-stac-extension)
- [Disasters Charter](https://github.com/Terradue/stac-extensions-disaster)
- [InSAR](https://github.com/Terradue/stac-extensions-insar)
- [Offset Tracking](https://github.com/Terradue/stac-extensions-offset-tracking)

## pystac Extensions implementation

Alphabetical list of all projects in [the profile's PySTAC section](README.md#pystac-extensions-implementation), including the extension generator and OGC API Records adapter. Documentation links lead to each project's usage guidance.

| Title | Description | Documentation |
| --- | --- | --- |
| [pystac-ext-access](https://github.com/Terradue/pystac-ext-access) | Python implementation of the STAC Access Extension Specification for pystac | [Docs](https://terradue.github.io/pystac-ext-access/) |
| [pystac-ext-aeronet](https://github.com/Terradue/pystac-ext-aeronet) | Pystac implementation of the aeronet-stac-extension STAC extension | [Docs](https://terradue.github.io/pystac-ext-aeronet/) |
| [pystac-ext-earthquake](https://github.com/Terradue/pystac-ext-earthquake) | Pystac implementation of the earthquake STAC extension | [Docs](https://terradue.github.io/pystac-ext-earthquake/) |
| [pystac-ext-generator](https://github.com/Terradue/pystac-ext-generator) | Python CLI that generates an independently importable, typed PySTAC extension module from a STAC Extension JSON Schema | [Doc](https://terradue.github.io/pystac-ext-generator/) |
| [pystac-ext-insar](https://github.com/Terradue/pystac-ext-insar) | Pystac implementation of the insar STAC extension | [Docs](https://terradue.github.io/pystac-ext-insar/) |
| [pystac-ext-ogc-record](https://github.com/Terradue/pystac-ext-ogc-record) | OGC API Records adapter for PySTAC | [Docs](https://terradue.github.io/pystac-ext-ogc-record/) |
| [pystac-ext-osc](https://github.com/Terradue/pystac-ext-osc) | Pystac implementation of the Open Science Catalogue STAC extension | [Docs](https://terradue.github.io/pystac-ext-osc/) |
| [pystac-ext-processing](https://github.com/Terradue/pystac-ext-processing) | Python implementation of the STAC Processing Extension Specification | [Docs](https://terradue.github.io/pystac-ext-processing/) |
| [pystac-ext-product](https://github.com/Terradue/pystac-ext-product) | Python implementation of the STAC Product Extension Specification for pystac | [Docs](https://terradue.github.io/pystac-ext-product/) |
| [pystac-ext-sentinel-1](https://github.com/Terradue/pystac-ext-sentinel-1) | Python implementation of the STAC Sentinel-1 Extension Specification for pystac | [Docs](https://terradue.github.io/pystac-ext-sentinel-1/) |
| [pystac-ext-sentinel-2](https://github.com/Terradue/pystac-ext-sentinel-2) | Python implementation of the STAC Sentinel-2 Extension Specification for pystac | [Docs](https://terradue.github.io/pystac-ext-sentinel-2/) |
| [pystac-ext-themes](https://github.com/Terradue/pystac-ext-themes) | Python implementation of the STAC Themes Extension Specification for pystac | [Docs](https://terradue.github.io/pystac-ext-themes/) |
