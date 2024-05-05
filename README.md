![Tests](https://github.com/slincoln-aiq/pySigma-backend-stix2/actions/workflows/test.yml/badge.svg)
![Coverage Badge](https://img.shields.io/endpoint?url=https://gist.githubusercontent.com/slincoln-aiq/997152ea6266fea4f2e0c25e24986b4f/raw/slincoln-pySigma-backend-stix2.json)
![Status](https://img.shields.io/badge/Status-pre--release-orange)

# Note

This is a forked version of the original pySigma stix backend. The original version can be found [here](https://github.com/barvhaim/pySigma-backend-stix) via user barvhaim.
The original repository has not been updated and is incompatible with the latest version of pySigma. This forked version has been updated to be compatible with the latest version of pySigma, and released on PyPI,
so it can be installed with `pip`/`poetry`.  If the original repository is updated, this fork will be removed and the original repository should be used.


# Original README
# pySigma stix Backend
This is the stix backend for pySigma. It provides the package `sigma.backends.stix` with the `stixBackend` class.
Further, it contains the following processing pipelines in `sigma.pipelines.stix`:

* stix_2_0
* stix_shifter

It supports the following output formats:

* default: plain stix queries

This backend is currently maintained by:
* [Cyber-center of Excellence](https://github.com/barvhaim/)