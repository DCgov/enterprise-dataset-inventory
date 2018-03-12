<p align="center"><img width=100% src="https://github.com/JoyOfTech/test-open-data-issues/blob/master/media/Open-Data-Banner.png"></p>

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/DCgov/enterprise-dataset-inventory/master)

## Enterprise Dataset Inventory

This repository contains the the Jupyter Notebook and datasets that were used to generate the results of the Enterprise Dataset Inventory (EDI) in the [Chief Data Officer's Annual Report](http://opendata.dc.gov/pages/cdo-annual-report) published March 11, 2018. The EDI and Annual Report fulfill the requirements of the [District of Columbia Data Policy](https://octo.dc.gov/page/district-columbia-data-policy) enacted by Mayor Muriel Bowser on April 27, 2017. 

The repository includes two Jupyter Notebooks. The [first](https://github.com/DCgov/enterprise-dataset-inventory/blob/master/fy18-annual-report/report-final.ipynb) uses [archived data](https://github.com/DCgov/enterprise-dataset-inventory/tree/master/fy18-annual-report/data) to replicate the results of the EDI analysis from the Chief Data Officer's Annual Report. The [second](https://github.com/DCgov/enterprise-dataset-inventory/blob/master/report-updated.ipynb) pulls from the [continually-updated EDI data](http://opendata.dc.gov/datasets/enterprise-dataset-inventory) on DC's [Open Data Portal](http://opendata.dc.gov) to provide a version of the report that can be updated to reflect changes in the data inventory.

This repository is also available on [Binder](https://mybinder.org/) which will allow you to run the Jupyter Notebooks online without installing anything on your local system. Just [click here](https://mybinder.org/v2/gh/DCgov/enterprise-dataset-inventory/master) to access the Binder.

## Archived Data

### [Agency Participant List](https://github.com/DCgov/enterprise-dataset-inventory/blob/master/fy18-annual-report/data/agency_participants_archived.csv)
This dataset contains a list of all agencies that were asked to participate in the 2017-18 Enterprise Dataset Inventory. 

#### Columns: 
AGENCY_NAME: The name of the agency
AGENCY_ACRONYM: An abbreviation of the agency's name
TYPE_OF_AGENCY: Whether the agency is Mayoral or Non-Mayoral (Independent) according to statute
PARTICIPATING: Whether (Yes) or not (No) the agency participated in the 2017-18 Enterprise Dataset Inventory

### [Archived Dataset Inventory Data](https://github.com/DCgov/enterprise-dataset-inventory/blob/master/fy18-annual-report/data/dataset_inventory_2018_03_11.csv) 
This dataset is an archived version of the data used to generate the EDI analysis in the Chief Data Officer's Annual Report published on March 11, 2018. The metadata for this dataset is available [here](https://www.arcgis.com/sharing/rest/content/items/76a28737a6f84b3c92a421114acccca2/info/metadata/metadata.xml?format=default&output=html).

## Public Domain
This project is in the public domain within the United States, and copyright and related rights in the work worldwide are waived through the CC0 1.0 Universal public domain dedication. For more information, see [LICENSE.md](LICENSE.md).

All contributions to this project will be released under the CC0 dedication. By submitting a pull request, you are agreeing to comply with this waiver of copyright interest.

## Contributing
See [CONTRIBUTING.md](CONTRIBUTING.md)
