# OpenGP

## Developer Guide

> OpenGP currently consists of the following three repos:

* [openmrs-module-gpconnect](https://github.com/Open-GP/openmrs-module-gpconnect)
  * An openmrs module which implements the GPConnect provider standard
* [opengp-distro](https://github.com/Open-GP/opengp-distro)
  * An openmrs distribution which builds and runs the module [openmrs-module-gpconnect](https://github.com/Open-GP/openmrs-module-gpconnect)
* [gpconnect-provider-testing](https://github.com/Open-GP/gpconnect-provider-testing)
  * Contains feature tests provided by GPConnect to check the [openmrs-module-gpconnect](https://github.com/Open-GP/openmrs-module-gpconnect) implmentation adheres to the GPConnect standard 
  * The feature tests are run against the bulit version of the module in the [opengp-distro](https://github.com/Open-GP/opengp-distro)

<img src="https://raw.githubusercontent.com/Open-GP/opengp-architecture/master/Diagrams/repo-overview.png" width="400"/>

## Architecture

> Please see the [diagrams](https://github.com/Open-GP/opengp-architecture/tree/master/Diagrams) in this repo to get more context on each repo.

## Backlog of items
See the list of issue for outstanding work for GPConnect implementation: https://github.com/Open-GP/opengp-architecture/issues
## Setup

### opengp-distro

Clone the repo:
```
git clone git@github.com:Open-GP/opengp-distro.git
```
Follow the [README](https://github.com/Open-GP/opengp-distro/blob/master/README.md) and the [On Boarding Developer Setup](https://github.com/Open-GP/opengp-distro/wiki/Onboarding-Developer-Setup).

### openmrs-module-gpconnect

Clone the repo:
```
git clone git@github.com:Open-GP/openmrs-module-gpconnect.git
```
Follow the [README](https://github.com/Open-GP/openmrs-module-gpconnect/blob/master/README.md)

### gpconnect-provider-testing

Clone the repo:
```
git clone git@github.com:Open-GP/gpconnect-provider-testing.git
```
Checkout the `opengp` branch.
Follow the [setup](https://github.com/Open-GP/gpconnect-provider-testing/blob/opengp/setup.md).
