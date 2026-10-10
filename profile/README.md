# Terradue's OpenSource repository

Browse the [repositories](https://terradue.github.io/) or the [complete GitHub repository list](https://github.com/orgs/Terradue/repositories).

Repositories are grouped by purpose. **(fork)** identifies a GitHub fork; see each repository for its current maintenance status.

- [CLI tools](#cli-tools)
- [VS Code extensions](#vs-code-extensions)
- [STAC](#stac)
    - [API implementations](#api-implementations)
    - [Extensions Specification](#extensions-specification)
    - [pystac Extensions implementation](#pystac-extensions-implementation)
    - [STAC libraries and tools](#stac-libraries-and-tools)
- [pygeofilters Implementations](#pygeofilters-implementations)
- [Python reusable modules](#python-reusable-modules)
- [Reusable REST Clients](#reusable-rest-clients)
- [RFC Implementations](#rfc-implementations)
- [EarthCODE](#earthcode)
- [.NET Modules](#net-modules)
- [CWL and application packages](#cwl-and-application-packages)
- [Earth observation processing](#earth-observation-processing)
- [Geospatial services and clients](#geospatial-services-and-clients)
- [Cloud infrastructure and integrations](#cloud-infrastructure-and-integrations)
- [Build tools, templates, and containers](#build-tools-templates-and-containers)
- [Training and examples](#training-and-examples)
- [Platform documentation and websites](#platform-documentation-and-websites)
- [Developer Cloud Sandbox applications](#developer-cloud-sandbox-applications)
- [Archived repositories](#archived-repositories)

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

### API implementations

| Project | What it provides | Documentation |
| --- | --- | --- |
| [stac-transaction-api-client](https://github.com/Terradue/stac-transaction-api-client) | Python client for the [STAC API Transaction Extension](https://github.com/stac-api-extensions/transaction) | [Docs](https://terradue.github.io/stac-transaction-api-client/) |
| [stac-fastapi-geoparquet](https://github.com/Terradue/stac-fastapi-geoparquet) **(fork)** | A stac-fastapi server implementation with a stac-geoparquet backend | [Repository](https://github.com/Terradue/stac-fastapi-geoparquet) |

### Extensions Specification

| Project | What it provides |
| --- | --- |
| [aeronet-stac-extension](https://github.com/Terradue/aeronet-stac-extension) | Aeronet Extension Specification |
| [stac-extensions-disaster](https://github.com/Terradue/stac-extensions-disaster) | Disasters Charter Extension Specification |
| [order](https://github.com/Terradue/order) **(fork)** | Allows assets ordering management within STAC specification. |
| [osc-prov](https://github.com/Terradue/osc-prov) **(fork)** | STAC extension to experiment with using OSPD experience in describing provenance information in an EarthCODE OSC-like record |
| [product](https://github.com/Terradue/product) **(fork)** | Generic Product-related properties for STAC |
| [render](https://github.com/Terradue/render) **(fork)** | Provide consumers with the information required to view an asset properly (e.g. on a online map) |
| [stac-extensions-insar](https://github.com/Terradue/stac-extensions-insar) | STAC extension for InSAR |
| [stac-extensions-offset-tracking](https://github.com/Terradue/stac-extensions-offset-tracking) | Offset Tracking STAC extension proposal; specification still contains template placeholders. |
| [storage-stac-extension](https://github.com/Terradue/storage-stac-extension) **(fork)** | Provides additional fields relating to how the asset is stored in the cloud |

### pystac Extensions implementation

| Project | What it provides | Documentation |
| --- | --- | --- |
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

### STAC libraries and tools

| Project | What it provides | Documentation |
| --- | --- | --- |
| [pystac](https://github.com/Terradue/pystac) **(fork)** | Python library for working with any SpatioTemporal Asset Catalog (STAC) | [Repository](https://github.com/Terradue/pystac) |
| [sentinel1](https://github.com/Terradue/sentinel1) **(fork)** | stactools package for working with sentinel1 data | [Repository](https://github.com/Terradue/sentinel1) |
| [sentinel2](https://github.com/Terradue/sentinel2) **(fork)** | stactools package for Sentinel-2 | [Repository](https://github.com/Terradue/sentinel2) |
| [sentinel3](https://github.com/Terradue/sentinel3) **(fork)** | stactools package for Sentinel-3 data | [Repository](https://github.com/Terradue/sentinel3) |
| [sentinel5p](https://github.com/Terradue/sentinel5p) **(fork)** | Stactools package for Sentinel 5P | [Repository](https://github.com/Terradue/sentinel5p) |
| [stac-browser](https://github.com/Terradue/stac-browser) **(fork)** | A full-fledged UI in Vue for browsing and searching static STAC catalogs and STAC APIs | [Repository](https://github.com/Terradue/stac-browser) |
| [stac-resources](https://github.com/Terradue/stac-resources) | SpatioTemporal Asset Catalog (STAC) EO resources | [Repository](https://github.com/Terradue/stac-resources) |
| [template](https://github.com/Terradue/template) **(fork)** | Template repository for stactools packages | [Repository](https://github.com/Terradue/template) |

## pygeofilters Implementations

| Project | What it provides | Documentation |
| --- | --- | --- |
| [cql2json-pydantic](https://github.com/Terradue/cql2json-pydantic) | Pydantic v2 models for building CQL2-JSON filters | [Docs](https://terradue.github.io/cql2json-pydantic/) |
| [pygeofilter-aeronet](https://github.com/Terradue/pygeofilter-aeronet) | `pygeofilter-aeronet` provides a pygeofilter extension for querying NASA’s AERONET aerosol optical depth datasets through the AERONET Web Service v3 API. | [Docs](https://terradue.github.io/pygeofilter-aeronet/) |
| [pygeofilter-odata-cdse](https://github.com/Terradue/pygeofilter-odata-cdse) | CQL2 JSON filters to Copernicus Data Space Ecosystem (CDSE) OData queries translator | [Docs](https://terradue.github.io/pygeofilter-odata-cdse/) |
| [pygeofilter](https://github.com/Terradue/pygeofilter) **(fork)** | pygeofilter is a pure Python parser implementation of OGC filtering standards | [Repository](https://github.com/Terradue/pygeofilter) |
| [pygeofilter-duckdb](https://github.com/Terradue/pygeofilter-duckdb) **(fork)** | DuckDB SQL backend for pygeofilter | [Repository](https://github.com/Terradue/pygeofilter-duckdb) |

## Python reusable modules

| Project | What it provides | Documentation |
| --- | --- | --- |
| [stage-events-client](https://github.com/Terradue/stage-events-client) | Structured [CloudEvents](https://cloudevents.io/) for Stage Events API + Client | [Docs](https://terradue.github.io/stage-events-client/) |
| [session-adapters](https://github.com/Terradue/session-adapters) | `requests` transport adapters for `file://`, `s3://`, and `oci://` URLs. | [Docs](https://terradue.github.io/session-adapters/) |
| [schema-org-python](https://github.com/Terradue/schema-org-python) **(fork)** | Python models for schema.org | [Repository](https://github.com/Terradue/schema-org-python) |

## Reusable REST Clients

| Project | What it provides | Documentation |
| --- | --- | --- |
| [invenio-rest-api-client](https://github.com/Terradue/invenio-rest-api-client) | A client library for accessing [InvenioRDM REST API](https://inveniordm.docs.cern.ch/reference/rest_api_index/) | [Docs](https://terradue.github.io/invenio-rest-api-client/) |
| [keycloak-oidc-api-client](https://github.com/Terradue/keycloak-oidc-api-client) | A client library for accessing Keycloak OIDC API | [Docs](https://terradue.github.io/keycloak-oidc-api-client/) |
| [ogc-api-records-core-client](https://github.com/Terradue/ogc-api-records-core-client) | A client library for accessing [OGC API - Records - Part 1: Core ](https://docs.ogc.org/is/20-004r1/20-004r1.html) | [Docs](https://terradue.github.io/ogc-api-records-core-client/) |
| [terrapy](https://github.com/Terradue/terrapy) | TerrAPI Python Client | [Repository](https://github.com/Terradue/terrapy) |

## RFC Implementations

| Project | What it provides | Documentation |
| --- | --- | --- |
| [api-health-check](https://github.com/Terradue/api-health-check) | `application/health+json` [Internet-Draft](https://datatracker.ietf.org/doc/html/draft-inadarei-api-health-check-06) | [Docs](https://terradue.github.io/api-health-check/) |

## EarthCODE

| Project | What it provides | Documentation |
| --- | --- | --- |
| [transpiler-mate](https://github.com/Terradue/transpiler-mate) ARCHIVED | Python API + CLI to extract `Schema.org/SoftwareApplication` Metadata from an annotated CWL document. | [Docs](https://terradue.github.io/transpiler-mate/) |
| [osc-metadata-client](https://github.com/Terradue/osc-metadata-client) | Open Science Catalog client | [Docs](https://terradue.github.io/osc-metadata-client/) |
| [open-science-catalog-metadata](https://github.com/Terradue/open-science-catalog-metadata) **(fork)** | Metadata for themes, variables, projects, and products in the ESA Open Science Catalog. | [Repository](https://github.com/Terradue/open-science-catalog-metadata) |
| [open-science-catalog-metadata-staging](https://github.com/Terradue/open-science-catalog-metadata-staging) **(fork)** | Metadata for the ESA Open Science Catalog, held in a staging repository. | [Repository](https://github.com/Terradue/open-science-catalog-metadata-staging) |

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
| [xsp](https://github.com/Terradue/xsp) **(fork)** | Mono's ASP.NET hosting server. This module includes an Apache Module, a FastCGI module that can be hooked to other web servers as well as a standalone server used for testing (similar to Microsoft's Cassini) | [Repository](https://github.com/Terradue/xsp) |

## CWL and application packages

| Project | What it provides | Documentation |
| --- | --- | --- |
| [apex_algorithms](https://github.com/Terradue/apex_algorithms) **(fork)** | Hosted APEx algorithms | [Repository](https://github.com/Terradue/apex_algorithms) |
| [apex_dispatch_api](https://github.com/Terradue/apex_dispatch_api) **(fork)** | Implementation of the APEx Upscaling Service API | [Repository](https://github.com/Terradue/apex_dispatch_api) |
| [application-hub-context](https://github.com/Terradue/application-hub-context) **(fork)** | ApplicationHub context and container image | [Repository](https://github.com/Terradue/application-hub-context) |
| [calrissian](https://github.com/Terradue/calrissian) **(fork)** | CWL on Kubernetes | [Repository](https://github.com/Terradue/calrissian) |
| [cwltool](https://github.com/Terradue/cwltool) **(fork)** | Common Workflow Language reference implementation | [Repository](https://github.com/Terradue/cwltool) |
| [eoap-open-sar-toolkit](https://github.com/Terradue/eoap-open-sar-toolkit) | Earth Observation Application Package for the Open SAR Toolkit | [Repository](https://github.com/Terradue/eoap-open-sar-toolkit) |
| [proc-workflow-executor](https://github.com/Terradue/proc-workflow-executor) **(fork)** | Workflow executor server and command-line client configured for Kubernetes. | [Repository](https://github.com/Terradue/proc-workflow-executor) |

## Earth observation processing

| Project | What it provides | Documentation |
| --- | --- | --- |
| [acolite](https://github.com/Terradue/acolite) **(fork)** | ACOLITE: Atmospheric correction for aquatic applications of Landsat and Sentinel-2 | [Repository](https://github.com/Terradue/acolite) |
| [adore-doris](https://github.com/Terradue/adore-doris) **(fork)** | Automated DORIS Environment (adore) is a set of bash scripts to ease use of TU-DELFT's DORIS software. | [Repository](https://github.com/Terradue/adore-doris) |
| [eowb-cckp](https://github.com/Terradue/eowb-cckp) | Applications to enhance the Climate Change Knowledge Portal (CCKP) of the World Bank, by integration of EO-based datasets | [Repository](https://github.com/Terradue/eowb-cckp) |
| [esgf_ensemble_mean](https://github.com/Terradue/esgf_ensemble_mean) **(fork)** | Cloud-based processing (ensemble mean) of ESGF 2D/3D variables | [Repository](https://github.com/Terradue/esgf_ensemble_mean) |
| [gefolki](https://github.com/Terradue/gefolki) | Python packaging and maintenance of GeFolki for dense remote-sensing image coregistration. | [Repository](https://github.com/Terradue/gefolki) |
| [geowow-1](https://github.com/Terradue/geowow-1) | Ocean acidification and ESGF/CMIP5 ensemble-mean web services; README points to a migrated repository. | [Repository](https://github.com/Terradue/geowow-1) |
| [iris](https://github.com/Terradue/iris) **(fork)** | Semi-automatic tool for manual segmentation of multi-spectral and geo-spatial imagery. | [Repository](https://github.com/Terradue/iris) |
| [jlinda](https://github.com/Terradue/jlinda) **(fork)** | jLinda - Java Library for Interferometric Data Analysis | [Repository](https://github.com/Terradue/jlinda) |
| [modape](https://github.com/Terradue/modape) **(fork)** | MODIS Assimilation and Processing Engine | [Repository](https://github.com/Terradue/modape) |
| [py-snap-helpers](https://github.com/Terradue/py-snap-helpers) | Functions to build and process SNAP Graphs | [Repository](https://github.com/Terradue/py-snap-helpers) |
| [r-rLandsat8](https://github.com/Terradue/r-rLandsat8) | Example of a R conda package | [Repository](https://github.com/Terradue/r-rLandsat8) |
| [reactiv](https://github.com/Terradue/reactiv) | Python implementation of REACTIV for visualizing changes in SAR time series. | [Repository](https://github.com/Terradue/reactiv) |
| [rLandsat8](https://github.com/Terradue/rLandsat8) | R package to process USGS Landsat 8 data | [Repository](https://github.com/Terradue/rLandsat8) |
| [roi-pac-builder](https://github.com/Terradue/roi-pac-builder) | Build and package ROI_PAC for SAR interferometry on the Developer Cloud Sandbox. | [Repository](https://github.com/Terradue/roi-pac-builder) |
| [sar-calibration](https://github.com/Terradue/sar-calibration) | SAR calibration processor with a CLI, container image, and CWL examples. | [Repository](https://github.com/Terradue/sar-calibration) |
| [sar-helpers](https://github.com/Terradue/sar-helpers) | sar-helpers are a set of bash function to ease the extraction of information out of SAR data. | [Repository](https://github.com/Terradue/sar-helpers) |
| [sar-stack-coverage](https://github.com/Terradue/sar-stack-coverage) | Identify the best SAR coverage in a cycle based on a bounding box | [Repository](https://github.com/Terradue/sar-stack-coverage) |
| [sb-SARvatore](https://github.com/Terradue/sb-SARvatore) | Developer Cloud Sandbox integration for the SARvatore CryoSat toolkit; README points to a migrated repository. | [Repository](https://github.com/Terradue/sb-SARvatore) |
| [scombi-do](https://github.com/Terradue/scombi-do) | EO satellite RGB composites | [Repository](https://github.com/Terradue/scombi-do) |
| [snapista](https://github.com/Terradue/snapista) **(fork)** | SNAP GPT thin layer for Python | [Repository](https://github.com/Terradue/snapista) |
| [srtm-dem](https://github.com/Terradue/srtm-dem) | Digital elevation model generation to use with ROI_PAC, GAMMA and GMTSAR Synthetic Aperture Radar interferometry toolboxes | [Repository](https://github.com/Terradue/srtm-dem) |
| [titiler-eopf](https://github.com/Terradue/titiler-eopf) **(fork)** | TiTiler application for EOPF dataset | [Repository](https://github.com/Terradue/titiler-eopf) |
| [triangle](https://github.com/Terradue/triangle) **(fork)** | This is a mirror of the latest stable version of Triangle. | [Repository](https://github.com/Terradue/triangle) |
| [vam.whittaker](https://github.com/Terradue/vam.whittaker) **(fork)** | State-of-the art whittaker smoother for EO data | [Repository](https://github.com/Terradue/vam.whittaker) |

## Geospatial services and clients

| Project | What it provides | Documentation |
| --- | --- | --- |
| [FindThenFetch](https://github.com/Terradue/FindThenFetch) | OpenSearch client written in Perl | [Repository](https://github.com/Terradue/FindThenFetch) |
| [geowebcache](https://github.com/Terradue/geowebcache) **(fork)** | GeoWebCache is a tile caching server implemented in Java that provides various tile caching services like WMS-C, TMS, WMTS, Google Maps, MS Bing and more | [Repository](https://github.com/Terradue/geowebcache) |
| [jcatalogue-client](https://github.com/Terradue/jcatalogue-client) | Java client of the Catalogue Satellite products server | [Repository](https://github.com/Terradue/jcatalogue-client) |
| [jquery-wps-client](https://github.com/Terradue/jquery-wps-client) | A visual interactive webapp client to OGC Web Processing Service developed as jQuery plugin | [Repository](https://github.com/Terradue/jquery-wps-client) |
| [ogc-eo-snuggs-dashboards](https://github.com/Terradue/ogc-eo-snuggs-dashboards) | Streamlit dashboard with expressions for EO composites, classification, and change detection. | [Repository](https://github.com/Terradue/ogc-eo-snuggs-dashboards) |
| [ows-context-demo](https://github.com/Terradue/ows-context-demo) | OGC OWS Context demonstration | [Repository](https://github.com/Terradue/ows-context-demo) |
| [ows-context4j](https://github.com/Terradue/ows-context4j) | Java library for OGC OWS Context | [Repository](https://github.com/Terradue/ows-context4j) |
| [OWSLib](https://github.com/Terradue/OWSLib) **(fork)** | OWSLib is a Python package for client programming with Open Geospatial Consortium (OGC) web service (hence OWS) interface standards, and their related content models. | [Repository](https://github.com/Terradue/OWSLib) |
| [pydap-conda](https://github.com/Terradue/pydap-conda) | Pure Python Opendap/DODS client and server | [Repository](https://github.com/Terradue/pydap-conda) |
| [rGeoServer](https://github.com/Terradue/rGeoServer) | No description provided; README contains only a project title. | [Repository](https://github.com/Terradue/rGeoServer) |
| [rOpenSearch](https://github.com/Terradue/rOpenSearch) | R interface to OpenSearch | [Repository](https://github.com/Terradue/rOpenSearch) |
| [trax](https://github.com/Terradue/trax) | XSL transformations: from dclite4g-RDF to ATOM, OGC Web Services Capabilities to RDF, ATOM to JSON, ISO19115/19 to ATOM and much more | [Repository](https://github.com/Terradue/trax) |
| [warhol](https://github.com/Terradue/warhol) | A new generation of OpenSearch Geo and Temporal protocol server APIs | [Repository](https://github.com/Terradue/warhol) |
| [ws-itag](https://github.com/Terradue/ws-itag) **(fork)** | iTag - Semantic enhancement of Earth Observation data | [Repository](https://github.com/Terradue/ws-itag) |
| [ZOO-Project](https://github.com/Terradue/ZOO-Project) **(fork)** | Official ZOO-Project repository. Please submit pull requests to the 'main' branch. | [Repository](https://github.com/Terradue/ZOO-Project) |

## Cloud infrastructure and integrations

| Project | What it provides | Documentation |
| --- | --- | --- |
| [abiquo4One](https://github.com/Terradue/abiquo4One) | Abiquo driver for OpenNebula | [Repository](https://github.com/Terradue/abiquo4One) |
| [cloud-bursting4one](https://github.com/Terradue/cloud-bursting4one) | cloud-bursting4one is an OpenNebula add-on that implements hybrid Cloud computing | [Repository](https://github.com/Terradue/cloud-bursting4one) |
| [dask_k8](https://github.com/Terradue/dask_k8) **(fork)** | Create Dask clusters in Kubernetes easily | [Repository](https://github.com/Terradue/dask_k8) |
| [dsi4One](https://github.com/Terradue/dsi4One) | T-Systems DSI driver for OpenNebula | [Repository](https://github.com/Terradue/dsi4One) |
| [hue](https://github.com/Terradue/hue) **(fork)** | Let’s big data. Hue is a Web interface for analyzing data with Apache Hadoop. It supports a file and job browser, Hive, Pig, Impala, Spark, Oozie editors, Solr Search dashboards, HBase, Sqoop2, and more... | [Repository](https://github.com/Terradue/hue) |
| [jclouds](https://github.com/Terradue/jclouds) **(fork)** | Read-only mirror of ASF Git Repo for jclouds | [Repository](https://github.com/Terradue/jclouds) |
| [jclouds4One](https://github.com/Terradue/jclouds4One) | jclouds driver for OpenNebula | [Repository](https://github.com/Terradue/jclouds4One) |
| [jhsingle-native-proxy](https://github.com/Terradue/jhsingle-native-proxy) **(fork)** | Wrap an arbitrary webapp so it can be used in place of jupyter-singleuser in a JupyterHub setting | [Repository](https://github.com/Terradue/jhsingle-native-proxy) |
| [libcloud-cli](https://github.com/Terradue/libcloud-cli) | Libcloud command-line client adapted for the OpenStack provider. | [Repository](https://github.com/Terradue/libcloud-cli) |
| [minio](https://github.com/Terradue/minio) **(fork)** | High Performance, Kubernetes Native Object Storage | [Repository](https://github.com/Terradue/minio) |
| [one](https://github.com/Terradue/one) **(fork)** | OpenNebula | [Repository](https://github.com/Terradue/one) |
| [opennebula-occi-tsystems](https://github.com/Terradue/opennebula-occi-tsystems) | An OpenNebula extension to bridge OpenNebula to t-systems Dynamic Service for Infrastructure (DSI) via OCCI APIs | [Repository](https://github.com/Terradue/opennebula-occi-tsystems) |
| [openshift-ansible](https://github.com/Terradue/openshift-ansible) **(fork)** | OpenShift Installation and Configuration Management | [Repository](https://github.com/Terradue/openshift-ansible) |
| [redmine-java-api](https://github.com/Terradue/redmine-java-api) **(fork)** | Redmine Java API | [Repository](https://github.com/Terradue/redmine-java-api) |
| [redmine-slack](https://github.com/Terradue/redmine-slack) **(fork)** | Slack notification plugin for Redmine | [Repository](https://github.com/Terradue/redmine-slack) |
| [SSEGrid](https://github.com/Terradue/SSEGrid) | Java project with Ant build files, examples, and documentation; no repository description or root README provided. | [Repository](https://github.com/Terradue/SSEGrid) |

## Build tools, templates, and containers

| Project | What it provides | Documentation |
| --- | --- | --- |
| [app-template](https://github.com/Terradue/app-template) **(fork)** | Cookiecutter template for generating Python application packages. | [Repository](https://github.com/Terradue/app-template) |
| [ci-eoap-container](https://github.com/Terradue/ci-eoap-container) | CI container for validating CWL, transpiling metadata, and publishing OCI artifacts. | [Repository](https://github.com/Terradue/ci-eoap-container) |
| [cwl-cli-archetype](https://github.com/Terradue/cwl-cli-archetype) | Installable Python package; README provides installation instructions but no functional overview. | [Repository](https://github.com/Terradue/cwl-cli-archetype) |
| [docker-orfeotoolbox](https://github.com/Terradue/docker-orfeotoolbox) | Docker container for Orfeo ToolBox command-line applications and Python bindings. | [Repository](https://github.com/Terradue/docker-orfeotoolbox) |
| [docker-otb-python](https://github.com/Terradue/docker-otb-python) | Docker container providing Orfeo ToolBox and its Python environment. | [Repository](https://github.com/Terradue/docker-otb-python) |
| [github-release-plugin](https://github.com/Terradue/github-release-plugin) **(fork)** | uses the github release api to upload files | [Repository](https://github.com/Terradue/github-release-plugin) |
| [openfaas-fluentd](https://github.com/Terradue/openfaas-fluentd) | OpenFaaS Fluentd template for receiving logs over HTTP. | [Repository](https://github.com/Terradue/openfaas-fluentd) |
| [openfaas-python3-fastapi-conda-template](https://github.com/Terradue/openfaas-python3-fastapi-conda-template) | OpenFaaS template for Python FastAPI functions with conda-managed dependencies. | [Repository](https://github.com/Terradue/openfaas-python3-fastapi-conda-template) |
| [oss-java-parent](https://github.com/Terradue/oss-java-parent) | Terradue OSS Java parent POM | [Repository](https://github.com/Terradue/oss-java-parent) |
| [oss-parent](https://github.com/Terradue/oss-parent) | Terradue Open Source Software parent POM | [Repository](https://github.com/Terradue/oss-parent) |
| [python-project-template](https://github.com/Terradue/python-project-template) | Reusable Copier project archetype for Terradue-style Python packages. | [Repository](https://github.com/Terradue/python-project-template) |
| [shunit2](https://github.com/Terradue/shunit2) **(fork)** | Git mirror for shunit2 project | [Repository](https://github.com/Terradue/shunit2) |
| [taskfile-utils](https://github.com/Terradue/taskfile-utils) | Reusable Taskfile collection for common project tasks. | [Repository](https://github.com/Terradue/taskfile-utils) |

## Training and examples

| Project | What it provides | Documentation |
| --- | --- | --- |
| [ai4EM_MOOC](https://github.com/Terradue/ai4EM_MOOC) **(fork)** | Jupyter notebooks for the Artificial Intelligence for Earth Monitoring MOOC. | [Repository](https://github.com/Terradue/ai4EM_MOOC) |
| [app-package-training-bids23](https://github.com/Terradue/app-package-training-bids23) | BiDS23 tutorial on packaging Earth observation workflows with CWL. | [Repository](https://github.com/Terradue/app-package-training-bids23) |
| [calrissian-session](https://github.com/Terradue/calrissian-session) | From zero to CWL on K8s with Calrissian | [Repository](https://github.com/Terradue/calrissian-session) |
| [eo-application-package-hands-on](https://github.com/Terradue/eo-application-package-hands-on) | BiDS’23 Mastering Earth Observation Application Packaging with CWL tutorial event | [Repository](https://github.com/Terradue/eo-application-package-hands-on) |
| [ogc-eo-application-package-hands-on](https://github.com/Terradue/ogc-eo-application-package-hands-on) | OGC EO Application Package Hands-on | [Repository](https://github.com/Terradue/ogc-eo-application-package-hands-on) |
| [open-reproducible-app-package](https://github.com/Terradue/open-reproducible-app-package) | BiDS23 tutorial material for reproducible Earth observation application packages. | [Repository](https://github.com/Terradue/open-reproducible-app-package) |

## Platform documentation and websites

| Project | What it provides | Documentation |
| --- | --- | --- |
| [.github](https://github.com/Terradue/.github) | Organization profile and repository directory. | [Repository](https://github.com/Terradue/.github) |
| [api](https://github.com/Terradue/api) | Terradue Cloud Platform API | [Repository](https://github.com/Terradue/api) |
| [cloud-admin-doc](https://github.com/Terradue/cloud-admin-doc) | Guides for exporting and administering Developer Cloud Sandbox virtual machines across cloud environments. | [Repository](https://github.com/Terradue/cloud-admin-doc) |
| [cwl-website](https://github.com/Terradue/cwl-website) **(fork)** | www.commonwl.org | [Repository](https://github.com/Terradue/cwl-website) |
| [doc-challenges](https://github.com/Terradue/doc-challenges) | E-CEO Data Challenges platform documentation | [Repository](https://github.com/Terradue/doc-challenges) |
| [doc-developer-sandbox](https://github.com/Terradue/doc-developer-sandbox) | Developer Cloud Sandbox documentation | [Repository](https://github.com/Terradue/doc-developer-sandbox) |
| [doc-ellip](https://github.com/Terradue/doc-ellip) | No description provided; README contains only a project title. | [Repository](https://github.com/Terradue/doc-ellip) |
| [doc-tep-geohazards](https://github.com/Terradue/doc-tep-geohazards) | Geohazards Thematic Exploitation guide | [Repository](https://github.com/Terradue/doc-tep-geohazards) |
| [doc-terradue-platform](https://github.com/Terradue/doc-terradue-platform) | Terradue platform documentation project linking API and Developer Cloud Sandbox sources. | [Repository](https://github.com/Terradue/doc-terradue-platform) |
| [doc-virtual-archive](https://github.com/Terradue/doc-virtual-archive) | Source documentation for the Terradue Virtual Archive. | [Repository](https://github.com/Terradue/doc-virtual-archive) |
| [gitbook-oss-t2](https://github.com/Terradue/gitbook-oss-t2) | RGitBook functions for generating the Terradue Open Source guide. | [Repository](https://github.com/Terradue/gitbook-oss-t2) |
| [sphinx-coding-guidelines](https://github.com/Terradue/sphinx-coding-guidelines) | Style Guide to write documentation using Sphinx | [Repository](https://github.com/Terradue/sphinx-coding-guidelines) |
| [sphinx_rtd_theme](https://github.com/Terradue/sphinx_rtd_theme) **(fork)** | Sphinx theme for readthedocs.org | [Repository](https://github.com/Terradue/sphinx_rtd_theme) |
| [terradue.github.com](https://github.com/Terradue/terradue.github.com) | Terradue Open Source Software site | [Repository](https://github.com/Terradue/terradue.github.com) |

## Developer Cloud Sandbox applications

| Project | What it provides | Documentation |
| --- | --- | --- |
| [dcs-bash-sentinel2](https://github.com/Terradue/dcs-bash-sentinel2) | DCS Bash application example for Sentinel-2 Atmospheric Correction | [Repository](https://github.com/Terradue/dcs-bash-sentinel2) |
| [dcs-beam-algalbloom](https://github.com/Terradue/dcs-beam-algalbloom) | Developer Cloud Sandbox tutorial for MERIS algal bloom detection using BEAM. | [Repository](https://github.com/Terradue/dcs-beam-algalbloom) |
| [dcs-beam-flh-java](https://github.com/Terradue/dcs-beam-flh-java) | BEAM Java tutorial to implement a BEAM Operator to calculate the Fluorescence line height in Envisat MERIS Level 1b products on the Developer Cloud Sandbox | [Repository](https://github.com/Terradue/dcs-beam-flh-java) |
| [dcs-clip-envi](https://github.com/Terradue/dcs-clip-envi) | Developer Cloud Sandbox Envisat ASAR clipping | [Repository](https://github.com/Terradue/dcs-clip-envi) |
| [dcs-crop-dataset](https://github.com/Terradue/dcs-crop-dataset) | Developer Cloud Sandbox EarthObservation dataset subset tool | [Repository](https://github.com/Terradue/dcs-crop-dataset) |
| [dcs-doris-baseline](https://github.com/Terradue/dcs-doris-baseline) | No description provided; README contains only a project title. | [Repository](https://github.com/Terradue/dcs-doris-baseline) |
| [dcs-doris-ifg](https://github.com/Terradue/dcs-doris-ifg) | Developer Cloud Sandbox interferogram processing with ADORE DORIS. | [Repository](https://github.com/Terradue/dcs-doris-ifg) |
| [dcs-doris-l0-coseismic](https://github.com/Terradue/dcs-doris-l0-coseismic) | No description provided; README contains only a project title. | [Repository](https://github.com/Terradue/dcs-doris-l0-coseismic) |
| [dcs-doris-l0-stack](https://github.com/Terradue/dcs-doris-l0-stack) | No description provided; README contains only a project title. | [Repository](https://github.com/Terradue/dcs-doris-l0-stack) |
| [dcs-doris-l1-coseismic](https://github.com/Terradue/dcs-doris-l1-coseismic) | DORIS coseismic interferometry with Envisat ASA_IMS_1P | [Repository](https://github.com/Terradue/dcs-doris-l1-coseismic) |
| [dcs-doris-l1-stack](https://github.com/Terradue/dcs-doris-l1-stack) | No description provided; README contains only a project title. | [Repository](https://github.com/Terradue/dcs-doris-l1-stack) |
| [dcs-doris-tsx](https://github.com/Terradue/dcs-doris-tsx) | Developer Cloud Sandbox TerraSAR-X processing with ADORE DORIS | [Repository](https://github.com/Terradue/dcs-doris-tsx) |
| [dcs-hands-on](https://github.com/Terradue/dcs-hands-on) | Developer Cloud Sandbox Hands-On Exercises | [Repository](https://github.com/Terradue/dcs-hands-on) |
| [dcs-insar-diapason](https://github.com/Terradue/dcs-insar-diapason) **(fork)** | ERS / ENVISAT automated InSAR Module (CNES, ALTAMIRA) | [Repository](https://github.com/Terradue/dcs-insar-diapason) |
| [dcs-insar-gmtsar](https://github.com/Terradue/dcs-insar-gmtsar) | InSAR tutorials - GMTSAR | [Repository](https://github.com/Terradue/dcs-insar-gmtsar) |
| [dcs-landsat-ledaps](https://github.com/Terradue/dcs-landsat-ledaps) | Developer Cloud Sandbox Landsat LEDAPS processing | [Repository](https://github.com/Terradue/dcs-landsat-ledaps) |
| [dcs-nest-coregistration](https://github.com/Terradue/dcs-nest-coregistration) | Developer Cloud Sandbox NEST Coregistration tutorial - ERS Tandem | [Repository](https://github.com/Terradue/dcs-nest-coregistration) |
| [dcs-python-sentinel2](https://github.com/Terradue/dcs-python-sentinel2) | DCS Python application example for Sentinel-2 Atmospheric Correction Edit | [Repository](https://github.com/Terradue/dcs-python-sentinel2) |
| [dcs-r-gbifsst](https://github.com/Terradue/dcs-r-gbifsst) | No description provided; README contains only a project title. | [Repository](https://github.com/Terradue/dcs-r-gbifsst) |
| [dcs-r-geoserver](https://github.com/Terradue/dcs-r-geoserver) | No description provided; README contains only a project title. | [Repository](https://github.com/Terradue/dcs-r-geoserver) |
| [dcs-r-landsat8-thermal](https://github.com/Terradue/dcs-r-landsat8-thermal) | No description provided; README contains only a project title. | [Repository](https://github.com/Terradue/dcs-r-landsat8-thermal) |
| [dcs-roipac2doris](https://github.com/Terradue/dcs-roipac2doris) | Developer Cloud Sandbox ROI_PAC focussing in DORIS format | [Repository](https://github.com/Terradue/dcs-roipac2doris) |
| [dcs-sbas](https://github.com/Terradue/dcs-sbas) | Developer Cloud Sandbox SBAS integration software; README points to a migrated repository. | [Repository](https://github.com/Terradue/dcs-sbas) |
| [dcs-sentinel1-tbx](https://github.com/Terradue/dcs-sentinel1-tbx) | Developer Cloud Sandbox Sentinel-1 Toolbox example | [Repository](https://github.com/Terradue/dcs-sentinel1-tbx) |
| [dcs-stamps-ps](https://github.com/Terradue/dcs-stamps-ps) | Developer Cloud Sandbox for StaMPS PS processing | [Repository](https://github.com/Terradue/dcs-stamps-ps) |
| [dcs-template-insar-sentinel1](https://github.com/Terradue/dcs-template-insar-sentinel1) | Developer Cloud Sandbox template for InSAR with Sentinel-1 data | [Repository](https://github.com/Terradue/dcs-template-insar-sentinel1) |
| [dcs-tiger-wois](https://github.com/Terradue/dcs-tiger-wois) | No description provided; README contains only a project title. | [Repository](https://github.com/Terradue/dcs-tiger-wois) |
| [wfp-01-01-01-f](https://github.com/Terradue/wfp-01-01-01-f) | Developer Cloud Sandbox application repository; README still contains template placeholders. | [Repository](https://github.com/Terradue/wfp-01-01-01-f) |

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
