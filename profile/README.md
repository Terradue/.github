# Terradue's OpenSource repository

Browse the [repositories](https://terradue.github.io/).

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
- [EarthCODE](#earthcode)
- [.NET Modules](#net-modules)
- [Archived repositories]()

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
| [pystac-ext-osc](https://github.com/Terradue/pystac-ext-osc) | Pystac implementation of the Open Science Catalogue STAC extension | [Docs](https://terradue.github.io/pystac-ext-osc/) |
| [pystac-ext-processing](https://github.com/Terradue/pystac-ext-processing) | Python implementation of the STAC Processing Extension Specification | [Docs](https://terradue.github.io/pystac-ext-processing/) |
| [pystac-ext-product](https://github.com/Terradue/pystac-ext-product) | Python implementation of the STAC Product Extension Specification for pystac | [Docs](https://terradue.github.io/pystac-ext-product/) |
| [pystac-ext-sentinel-1](https://github.com/Terradue/pystac-ext-sentinel-1) | Python implementation of the STAC Sentinel-1 Extension Specification for pystac | [Docs](https://terradue.github.io/pystac-ext-sentinel-1/) |
| [pystac-ext-sentinel-2](https://github.com/Terradue/pystac-ext-sentinel-2) | Python implementation of the STAC Sentinel-2 Extension Specification for pystac | [Docs](https://terradue.github.io/pystac-ext-sentinel-2/) |
| [pystac-ext-theme](https://github.com/Terradue/pystac-ext-theme) | Python implementation of the STAC Theme Extension Specification for pystac | [Docs](https://terradue.github.io/pystac-ext-theme/) |

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

## EarthCODE

| Project | What it provides | Documentation |
| --- | --- | --- |
| [transpiler-mate](https://github.com/Terradue/transpiler-mate) ARCHIVED | Python API + CLI to extract `Schema.org/SoftwareApplication` Metadata from an annotated CWL document. | [Docs](https://terradue.github.io/transpiler-mate/) |
| [osc-metadata-client](https://github.com/Terradue/osc-metadata-client) | Open Science Catalog client | [Docs](https://terradue.github.io/osc-metadata-client/) |

> [!WARNING]
> ### Transpiler-Mate has moved
>
> What started as a CWL metadata conversion tool has evolved into a **modular, extensible ecosystem** under the [Transpiler-Mate organization](https://github.com/transpiler-mate).

## .NET Modules

| Project | What it provides | Documentation |
| --- | --- | --- |
| [DotNet4One](https://github.com/Terradue/DotNet4One) | .NET client for the OpenNebula XML-RPC API | [README](https://github.com/Terradue/DotNet4One#readme) |
| [DotNetEarthObservation](https://github.com/Terradue/DotNetEarthObservation) | .NET implementation of the OGC Earth Observation Metadata profile of Observations & Measurements | [README](https://github.com/Terradue/DotNetEarthObservation#readme) |
| [DotNetElasticCas](https://github.com/Terradue/DotNetElasticCas) | OpenSearch catalogue built on Elasticsearch | [README](https://github.com/Terradue/DotNetElasticCas#readme) |
| [DotNetGDALNative](https://github.com/Terradue/DotNetGDALNative) | .NET bindings for native GDAL functions on Linux and macOS | [README](https://github.com/Terradue/DotNetGDALNative#readme) |
| [DotNetGeoJson](https://github.com/Terradue/DotNetGeoJson) | GeoJSON serialization, deserialization, and conversion from GML and WKT | [README](https://github.com/Terradue/DotNetGeoJson#readme) |
| [DotNetGeoserver](https://github.com/Terradue/DotNetGeoserver) | .NET library for managing requests to GeoServer | [README](https://github.com/Terradue/DotNetGeoserver#readme) |
| [DotNetGithub](https://github.com/Terradue/DotNetGithub) | GitHub account integration for Terradue.Portal user profiles | [README](https://github.com/Terradue/DotNetGithub#readme) |
| [dotnetinteractive](https://github.com/Terradue/dotnetinteractive) | .NET notebooks in Docker | [README](https://github.com/Terradue/dotnetinteractive#readme) |
| [DotNetOgcModel](https://github.com/Terradue/DotNetOgcModel) | .NET classes for reading, writing, and manipulating XML documents based on OGC schemas | [README](https://github.com/Terradue/DotNetOgcModel#readme) |
| [DotNetOgcOmGml](https://github.com/Terradue/DotNetOgcOmGml) | .NET classes representing OGC Observations & Measurements and GML XML | [Docs](https://github.com/Terradue/DotNetOgcOmGml/tree/develop/doc) |
| [DotNetOgcOwsContext](https://github.com/Terradue/DotNetOgcOwsContext) | .NET model for creating and manipulating OGC OWS Context documents | [README](https://github.com/Terradue/DotNetOgcOwsContext#readme) |
| [DotNetOgcWebService](https://github.com/Terradue/DotNetOgcWebService) | .NET Standard base classes for working with OGC web services | [README](https://github.com/Terradue/DotNetOgcWebService#readme) |
| [DotNetOpenSearch](https://github.com/Terradue/DotNetOpenSearch) | .NET library for querying OpenSearch services with extensible result formats | [README](https://github.com/Terradue/DotNetOpenSearch#readme) |
| [DotNetOpenSearchClient](https://github.com/Terradue/DotNetOpenSearchClient) | Generic OpenSearch query client and catalogue data publisher tools | [README](https://github.com/Terradue/DotNetOpenSearchClient#readme) |
| [DotNetOpenSearchDataAnalyzer](https://github.com/Terradue/DotNetOpenSearchDataAnalyzer) | GDAL-based metadata harvester that exports spatial, temporal, and other metadata as Atom feeds | [README](https://github.com/Terradue/DotNetOpenSearchDataAnalyzer#readme) |
| [DotNetOpenSearchGeoJson](https://github.com/Terradue/DotNetOpenSearchGeoJson) | GeoJSON result format extension for the .NET OpenSearch library | [README](https://github.com/Terradue/DotNetOpenSearchGeoJson#readme) |
| [DotNetOpenSearchKml](https://github.com/Terradue/DotNetOpenSearchKml) | KML result format extension for the .NET OpenSearch library | [README](https://github.com/Terradue/DotNetOpenSearchKml#readme) |
| [DotNetOpenSearchRdfEO](https://github.com/Terradue/DotNetOpenSearchRdfEO) | RDF Earth Observation extension for the .NET OpenSearch library | [README](https://github.com/Terradue/DotNetOpenSearchRdfEO#readme) |
| [DotNetOpenSearchSuggestions](https://github.com/Terradue/DotNetOpenSearchSuggestions) | OpenSearch suggestions extension (empty repository) | — |
| [DotNetOpenSearchTumblr](https://github.com/Terradue/DotNetOpenSearchTumblr) | OpenSearch access to the Tumblr API | [README](https://github.com/Terradue/DotNetOpenSearchTumblr#readme) |
| [DotNetOpenSearchTwitter](https://github.com/Terradue/DotNetOpenSearchTwitter) | OpenSearch access to the Twitter API | [README](https://github.com/Terradue/DotNetOpenSearchTwitter#readme) |
| [DotNetPortalAuthUmsso](https://github.com/Terradue/DotNetPortalAuthUmsso) | EO-SSO authentication support for Terradue.Portal | [README](https://github.com/Terradue/DotNetPortalAuthUmsso#readme) |
| [DotNetPortalCore](https://github.com/Terradue/DotNetPortalCore) | Core CMS entities and interfaces for Terradue.Portal | [README](https://github.com/Terradue/DotNetPortalCore#readme) |
| [DotNetPortalNews](https://github.com/Terradue/DotNetPortalNews) | Multi-source news support (Atom/RSS, Twitter, and Tumblr) for Terradue.Portal | [README](https://github.com/Terradue/DotNetPortalNews#readme) |
| [DotNetSearch](https://github.com/Terradue/DotNetSearch) | Generic web API services and engines for implementing search functions | — |
| [DotNetSentinelSafe](https://github.com/Terradue/DotNetSentinelSafe) | .NET library and tools for Sentinel products and metadata in SAFE format | [README](https://github.com/Terradue/DotNetSentinelSafe#readme) |
| [DotNetStac](https://github.com/Terradue/DotNetStac) | .NET library for working with SpatioTemporal Asset Catalogs (STAC) | [Docs](https://terradue.github.io/DotNetStac/) |
| [DotNetStac.Api](https://github.com/Terradue/DotNetStac.Api) | .NET and ASP.NET Core SDK for building and querying STAC API services | [Docs](https://terradue.github.io/DotNetStac.Api/) |
| [DotNetSyndication](https://github.com/Terradue/DotNetSyndication) | Standalone Atom and RSS syndication library for .NET | [README](https://github.com/Terradue/DotNetSyndication#readme) |
| [DotNetTep](https://github.com/Terradue/DotNetTep) | .NET library providing Terradue TEP functionality | [README](https://github.com/Terradue/DotNetTep#readme) |
| [DotNetTerraduePortal](https://github.com/Terradue/DotNetTerraduePortal) | Placeholder repository containing a license only | — |
| [DotNetWebServiceModel](https://github.com/Terradue/DotNetWebServiceModel) | Web service interfaces and REST models for Terradue APIs | [README](https://github.com/Terradue/DotNetWebServiceModel#readme) |

## Archived repositories

| Project | What it provides |
|---|---|
| [abiquo-cli](https://github.com/Terradue/abiquo-cli) | jclouds-labs-cli is a command line tool that allows you to interact with jclouds LABS part of the library |
| [cdab-testsuite](https://github.com/Terradue/cdab-testsuite) | Copernicus Sentinels Data Access Worldwide Benchmark Test Suite |
| [dcs-insar-roipac](https://github.com/Terradue/dcs-insar-roipac) | Cloud processing with Envisat ASAR data and ROI_PAC |
| [dcs-pf-asar](https://github.com/Terradue/dcs-pf-asar) | *No description provided.* |
| [dcs-python-ndvi](https://github.com/Terradue/dcs-python-ndvi) | Developer Cloud Sandbox Python tutorial - Landsat NDVI |
| [dcs-testsuite](https://github.com/Terradue/dcs-testsuite) | *No description provided.* |
| [doc-tep-geohazards-arch](https://github.com/Terradue/doc-tep-geohazards-arch) | Geohazards Thematic Exploitation Platform architecture |
| [doc-tep-geohazards-v2](https://github.com/Terradue/doc-tep-geohazards-v2) | *No description provided.* |
| [DotNetHadoop](https://github.com/Terradue/DotNetHadoop) | *No description provided.* |
| [DotNetPortalCloud](https://github.com/Terradue/DotNetPortalCloud) | *No description provided.* |
| [dsi-tools](https://github.com/Terradue/dsi-tools) | Command Line Tools to interact with Zimory/T-Systems cloud REST server |
| [jCloudSigma](https://github.com/Terradue/jCloudSigma) | ONE driver for CloudSigma |
| [transpiler-mate](https://github.com/Terradue/transpiler-mate) | Python API + CLI to extract Schema.org/SoftwareApplication Metadata from an annotated CWL document and publish it as a Record on Invenio RDM |
