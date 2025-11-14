
# Data Product Canvas - Berlin LOR Health and Social Structure Atlas (source-aligned)

## Metadata

* owner: Open Data Product
* description: Source-aligned data product combining Berlin LOR health and social structure data
* updated: 2025-10-28

## Input Ports

### Gesundheits- und Sozialstrukturatlas Berlin 2022

* owner: Senatsverwaltung für Wissenschaft, Gesundheit, Pflege und Gleichstellung Berlin
* url: https://www.berlin.de/sen/gesundheit/gesundheitsberichterstattung/gesundheits-und-sozialstruktur-1367182.php
* license: CC-BY-3.0-Namensnennung
* updated: 2022-03-29

**Files**

* [gssa_2022_planungsraeume.csv](https://www.berlin.de/sen/gesundheit/_assets/daten/gesundheits-und-sozialstrukturatlas/gssa_2022_planungsraeume.csv)
* [gssa_2022_bezirksregionen.csv](https://www.berlin.de/sen/gesundheit/_assets/daten/gesundheits-und-sozialstrukturatlas/gssa_2022_bezirksregionen.csv)
* [gssa_2022_prognoseraeume.csv](https://www.berlin.de/sen/gesundheit/_assets/daten/gesundheits-und-sozialstrukturatlas/gssa_2022_prognoseraeume.csv)
* [gssa_2022_bezirke.csv](https://www.berlin.de/sen/gesundheit/_assets/daten/gesundheits-und-sozialstrukturatlas/gssa_2022_bezirke.csv)

### Gesundheits- und Sozialstrukturatlas Berlin 2022

* owner: Senatsverwaltung für Wissenschaft, Gesundheit, Pflege und Gleichstellung Berlin
* url: https://www.berlin.de/sen/gesundheit/gesundheitsberichterstattung/gesundheits-und-sozialstruktur-1367182.php
* license: CC-BY-3.0-Namensnennung
* updated: 2022-03-29

**Files**

* [gssa_2022_planungsraeume.csv](https://www.berlin.de/sen/gesundheit/_assets/daten/gesundheits-und-sozialstrukturatlas/gssa_2022_planungsraeume.csv)
* [gssa_2022_bezirksregionen.csv](https://www.berlin.de/sen/gesundheit/_assets/daten/gesundheits-und-sozialstrukturatlas/gssa_2022_bezirksregionen.csv)
* [gssa_2022_prognoseraeume.csv](https://www.berlin.de/sen/gesundheit/_assets/daten/gesundheits-und-sozialstrukturatlas/gssa_2022_prognoseraeume.csv)
* [gssa_2022_bezirke.csv](https://www.berlin.de/sen/gesundheit/_assets/daten/gesundheits-und-sozialstrukturatlas/gssa_2022_bezirke.csv)

## Transformation Steps

* [Data extractor](https://github.com/open-data-product/open-data-product-python-lib/blob/main/opendataproduct/extract/data_extractor.py) extracts data from inout ports
* [Data copier](https://github.com/open-data-product/open-data-product-python-lib/blob/main/opendataproduct/transform/data_copier.py) copies and renames extracted data
* [Data CSV converter](https://github.com/open-data-product/open-data-product-python-lib/blob/main/opendataproduct/transform/data_csv_converter.py) converts Excel files to CSV format
* [Data aggregator](https://github.com/open-data-product/open-data-product-python-lib/blob/main/opendataproduct/transform/data_aggregator.py) aggregates data to be used as output ports

## Output Ports

### Berlin Lor Health And Social Structure Atlas 2013 00 Csv

* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-lor-health-and-social-structure-atlas-source-aligned/tree/main/data/03-gold/berlin-lor-health-and-social-structure-atlas-2013-00-csv
* updated: 2025-10-28

**Files**

* [berlin-lor-health-and-social-structure-atlas-2013-00-district-regions.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-health-and-social-structure-atlas-source-aligned/main/data/03-gold/berlin-lor-health-and-social-structure-atlas-2013-00-csv/berlin-lor-health-and-social-structure-atlas-2013-00-district-regions.csv)
* [berlin-lor-health-and-social-structure-atlas-2013-00-districts.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-health-and-social-structure-atlas-source-aligned/main/data/03-gold/berlin-lor-health-and-social-structure-atlas-2013-00-csv/berlin-lor-health-and-social-structure-atlas-2013-00-districts.csv)
* [berlin-lor-health-and-social-structure-atlas-2013-00-forecast-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-health-and-social-structure-atlas-source-aligned/main/data/03-gold/berlin-lor-health-and-social-structure-atlas-2013-00-csv/berlin-lor-health-and-social-structure-atlas-2013-00-forecast-areas.csv)
* [berlin-lor-health-and-social-structure-atlas-2013-00-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-health-and-social-structure-atlas-source-aligned/main/data/03-gold/berlin-lor-health-and-social-structure-atlas-2013-00-csv/berlin-lor-health-and-social-structure-atlas-2013-00-planning-areas.csv)

### Berlin Lor Health And Social Structure Atlas 2013 00 Parquet

* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-lor-health-and-social-structure-atlas-source-aligned/tree/main/data/03-gold/berlin-lor-health-and-social-structure-atlas-2013-00-parquet
* updated: 2025-10-28

**Files**

* [berlin-lor-health-and-social-structure-atlas-2013-00-district-regions.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-health-and-social-structure-atlas-source-aligned/main/data/03-gold/berlin-lor-health-and-social-structure-atlas-2013-00-parquet/berlin-lor-health-and-social-structure-atlas-2013-00-district-regions.parquet)
* [berlin-lor-health-and-social-structure-atlas-2013-00-districts.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-health-and-social-structure-atlas-source-aligned/main/data/03-gold/berlin-lor-health-and-social-structure-atlas-2013-00-parquet/berlin-lor-health-and-social-structure-atlas-2013-00-districts.parquet)
* [berlin-lor-health-and-social-structure-atlas-2013-00-forecast-areas.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-health-and-social-structure-atlas-source-aligned/main/data/03-gold/berlin-lor-health-and-social-structure-atlas-2013-00-parquet/berlin-lor-health-and-social-structure-atlas-2013-00-forecast-areas.parquet)
* [berlin-lor-health-and-social-structure-atlas-2013-00-planning-areas.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-health-and-social-structure-atlas-source-aligned/main/data/03-gold/berlin-lor-health-and-social-structure-atlas-2013-00-parquet/berlin-lor-health-and-social-structure-atlas-2013-00-planning-areas.parquet)

### Berlin Lor Health And Social Structure Atlas 2022 00 Csv

* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-lor-health-and-social-structure-atlas-source-aligned/tree/main/data/03-gold/berlin-lor-health-and-social-structure-atlas-2022-00-csv
* updated: 2025-10-28

**Files**

* [berlin-lor-health-and-social-structure-atlas-2022-00-district-regions.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-health-and-social-structure-atlas-source-aligned/main/data/03-gold/berlin-lor-health-and-social-structure-atlas-2022-00-csv/berlin-lor-health-and-social-structure-atlas-2022-00-district-regions.csv)
* [berlin-lor-health-and-social-structure-atlas-2022-00-districts.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-health-and-social-structure-atlas-source-aligned/main/data/03-gold/berlin-lor-health-and-social-structure-atlas-2022-00-csv/berlin-lor-health-and-social-structure-atlas-2022-00-districts.csv)
* [berlin-lor-health-and-social-structure-atlas-2022-00-forecast-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-health-and-social-structure-atlas-source-aligned/main/data/03-gold/berlin-lor-health-and-social-structure-atlas-2022-00-csv/berlin-lor-health-and-social-structure-atlas-2022-00-forecast-areas.csv)
* [berlin-lor-health-and-social-structure-atlas-2022-00-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-health-and-social-structure-atlas-source-aligned/main/data/03-gold/berlin-lor-health-and-social-structure-atlas-2022-00-csv/berlin-lor-health-and-social-structure-atlas-2022-00-planning-areas.csv)

### Berlin Lor Health And Social Structure Atlas 2022 00 Parquet

* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-lor-health-and-social-structure-atlas-source-aligned/tree/main/data/03-gold/berlin-lor-health-and-social-structure-atlas-2022-00-parquet
* updated: 2025-10-28

**Files**

* [berlin-lor-health-and-social-structure-atlas-2022-00-district-regions.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-health-and-social-structure-atlas-source-aligned/main/data/03-gold/berlin-lor-health-and-social-structure-atlas-2022-00-parquet/berlin-lor-health-and-social-structure-atlas-2022-00-district-regions.parquet)
* [berlin-lor-health-and-social-structure-atlas-2022-00-districts.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-health-and-social-structure-atlas-source-aligned/main/data/03-gold/berlin-lor-health-and-social-structure-atlas-2022-00-parquet/berlin-lor-health-and-social-structure-atlas-2022-00-districts.parquet)
* [berlin-lor-health-and-social-structure-atlas-2022-00-forecast-areas.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-health-and-social-structure-atlas-source-aligned/main/data/03-gold/berlin-lor-health-and-social-structure-atlas-2022-00-parquet/berlin-lor-health-and-social-structure-atlas-2022-00-forecast-areas.parquet)
* [berlin-lor-health-and-social-structure-atlas-2022-00-planning-areas.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-health-and-social-structure-atlas-source-aligned/main/data/03-gold/berlin-lor-health-and-social-structure-atlas-2022-00-parquet/berlin-lor-health-and-social-structure-atlas-2022-00-planning-areas.parquet)

## Classification

**The nature of the exposed data (source-aligned, aggregate, consumer-aligned)**

source-aligned


---
This data product canvas uses the template of [datamesh-architecture.com](https://www.datamesh-architecture.com/data-product-canvas).