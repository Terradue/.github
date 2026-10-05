# Terradue's OpenSource repository

- [CLI Tools](#cli-tools)
- [VS Code extensions](#vs-code-extensions)
- STAC
    - [API implementations](#api-implementations)
    - [Extensions Specification](#extensions-specification)
    - [pystac Extensions implementation](#pystac-extensions-implementation)
- [pygeofilters Implementations](#pygeofilters-implementations)
- [Python reusable modules](#python-reusable-modules)
- [Reusable REST Clients](#reusable-rest-clients)
- [RFC Implementations](#rfc-implementations)

## CLI tools

| Project | What it provides | Documentation |
| --- | --- | --- |
| [asyncapi-mate](https://github.com/Terradue/asyncapi-mate) | Generates Markdown documentation and PlantUML source diagrams from an AsyncAPI document | [Docs](https://terradue.github.io/asyncapi-mate/) |
| [click2cwl](https://github.com/Terradue/click2cwl) | From a Python Click context to a CWL document | [Docs](https://terradue.github.io/click2cwl/) |
| [ref-bundle](https://github.com/Terradue/ref-bundle) | Turns a modular JSON, YAML, or XML configuration into a self-contained document. It starts from one root document, follows its JSON References ($ref), and serializes the collected result as JSON, YAML, or XML. | [Docs](https://terradue.github.io/ref-bundle/) |
| [state-mate](https://github.com/Terradue/state-mate) | Generates [python-statemachine](https://python-statemachine.readthedocs.io/en/latest/) source code from a constrained [Sismic](https://sismic.readthedocs.io/) YAML statechart. | [Docs](https://terradue.github.io/state-mate/) |

## VS Code extensions

| Project | What it provides | Documentation |
| --- | --- | --- |
| [conventional-commits-extension](https://github.com/Terradue/conventional-commits-extension) | https://www.conventionalcommits.org/ editor | [Docs](https://terradue.github.io/conventional-commits-extension/) |
| [changelog-studio](https://github.com/Terradue/changelog-studio) | https://keepachangelog.com/ editor | [Docs](https://terradue.github.io/changelog-studio/) |

## STAC

## API implementations

| Project | What it provides |
| --- | --- |
| [stac-transaction-api-client](https://github.com/Terradue/stac-transaction-api-client) | Python client for the [STAC API Transaction Extension](https://github.com/stac-api-extensions/transaction) | [Docs](https://terradue.github.io/stac-transaction-api-client/) |

## Extensions Specification

| Project | What it provides |
| --- | --- |
| [aeronet-stac-extension](https://github.com/Terradue/aeronet-stac-extension) | Aeronet Extension Specification |
| [stac-extensions-disaster](https://github.com/Terradue/stac-extensions-disaster) | Disasters Charter Extension Specification |

## pystac Extensions implementation

| Project | What it provides | Documentation |
| --- | --- | --- |
| [pystac-ext-aeronet](https://github.com/Terradue/pystac-ext-aeronet) | Pystac implementation of the aeronet-stac-extension STAC extension | [Docs](https://terradue.github.io/pystac-ext-aeronet/) |
| [pystac-ext-earthquake](https://github.com/Terradue/pystac-ext-earthquake) | Pystac implementation of the earthquake STAC extension | [Docs](https://terradue.github.io/pystac-ext-earthquake/) |
| [pystac-ext-insar](https://github.com/Terradue/pystac-ext-insar) | Pystac implementation of the insar STAC extension | [Docs](https://terradue.github.io/pystac-ext-insar/) |
| [pystac-ext-processing](https://github.com/Terradue/pystac-ext-processing) | Python implementation of the STAC Processing Extension Specification | [Docs](https://terradue.github.io/pystac-ext-processing/) |
| [pystac-ext-product](https://github.com/Terradue/pystac-ext-product) | Python implementation of the STAC Product Extension Specification for pystac | [Docs](https://terradue.github.io/pystac-ext-product/) |
| [pystac-ext-sentinel-1](https://github.com/Terradue/pystac-ext-sentinel-1) | Python implementation of the STAC Sentinel-1 Extension Specification for pystac | [Docs](https://terradue.github.io/pystac-ext-sentinel-1/) |

## pygeofilters Implementations

| Project | What it provides | Documentation |
| --- | --- | --- |
| [pygeofilter-aeronet](https://github.com/Terradue/pygeofilter-aeronet) | `pygeofilter-aeronet` provides a pygeofilter extension for querying NASA’s AERONET aerosol optical depth datasets through the AERONET Web Service v3 API. | [Docs](https://terradue.github.io/pygeofilter-aeronet/) |
| [pygeofilter-odata-cdse](https://github.com/Terradue/pygeofilter-odata-cdse) | CQL2 JSON filters to Copernicus Data Space Ecosystem (CDSE) OData queries translator | [Docs](https://terradue.github.io/pygeofilter-odata-cdse/) |

## Python reusable modules

| Project | What it provides | Documentation |
| --- | --- | --- |
| [stage-events-client](https://github.com/Terradue/stage-events-client) | Structured [CloudEvents](https://cloudevents.io/) for Stage Events API + Client | [Docs](https://terradue.github.io/stage-events-client/) |
| [session-adapters](https://github.com/Terradue/session-adapters) | `requests` transport adapters for `file://`, `s3://`, and `oci://` URLs. | [Docs](https://terradue.github.io/session-adapters/) |

## Reusable REST Clients

| Project | What it provides | Documentation |
| --- | --- | --- |
| [invenio-rest-api-client](https://github.com/Terradue/invenio-rest-api-client) | A client library for accessing [InvenioRDM REST API](https://inveniordm.docs.cern.ch/reference/rest_api_index/) | [Docs](https://terradue.github.io/invenio-rest-api-client/) |
| [keycloak-oidc-api-client](https://github.com/Terradue/keycloak-oidc-api-client) | A client library for accessing Keycloak OIDC API | [Docs](https://terradue.github.io/keycloak-oidc-api-client/) |
| [ogc-api-records-core-client](https://github.com/Terradue/ogc-api-records-core-client) | A client library for accessing [OGC API - Records - Part 1: Core ](https://docs.ogc.org/is/20-004r1/20-004r1.html) | [Docs](https://terradue.github.io/ogc-api-records-core-client/) |

## RFC Implementations

| Project | What it provides | Documentation |
| --- | --- | --- |
| [api-health-check](https://github.com/Terradue/api-health-check) | `application/health+json` [Internet-Draft](https://datatracker.ietf.org/doc/html/draft-inadarei-api-health-check-06) | [Docs](https://terradue.github.io/api-health-check/) |
