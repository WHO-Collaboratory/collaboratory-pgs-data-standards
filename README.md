# collaboratory-pgs-data-standards

Experimental project under development.

## Overview

This is the repository for the IPSN Pathogen-Genomics-Surveillance Data-Standards Catalogue. 

The catalogue is [catalogue.json](./catalogue.json).

The catalogue field names, types, permitted values, and definitions are defined in [catalogue_model.json](./catalogue_model.json). 

An empty template for catalogue entries is provided: [catalogue_entry_template.json](./catalogue_entry_template.json)

The catalogue is displayed here: https://who-collaboratory.github.io/collaboratory-pgs-data-standards-page/

## How to

Here are the recommended steps to edit the catalogue:
1. Edit the catalogue by hand in the dev branch. There are no quality checks, so make sure to stick to the [catalogue_model.json](./catalogue_model.json). Note that there is a comment field to add free text.
2. Once it is validated, merge it into the stable branch.

## License

All files within this repository, including the catalogue, are provided under a [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.
