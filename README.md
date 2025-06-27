[![Issues](https://img.shields.io/github/issues/open-data-product/open-data-product-berlin-lor-health-and-social-structure-atlas-source-aligned)](https://github.com/open-data-product/open-data-product-berlin-lor-health-and-social-structure-atlas-source-aligned/issues)

<br />
<p align="center">
  <a href="https://github.com/open-data-product/open-data-product-berlin-lor-health-and-social-structure-atlas-source-aligned">
    <img src="logo-with-text.png" alt="Logo"  style="height: 80px; ">
  </a>

  <h1 align="center">Berlin LOR Health and Social Structure Atlas (source-aligned)</h1>

  <p align="center">
    Source-aligned data product providing Berlin LOR health and social structure atlas
  </p>
</p>

## About The Project

See [data product canvas](docs/data-product-canvas.md) and [ODPS canvas](./docs/odps-canvas.md).

### Built With

* [Python](https://www.python.org/)
* [uv](https://docs.astral.sh/uv/)
* [ruff](https://docs.astral.sh/ruff/)

## Installation

Install uv, see https://github.com/astral-sh/uv?tab=readme-ov-file#installation.

```shell
# On macOS and Linux.
curl -LsSf https://astral.sh/uv/install.sh | sh
```

## Usage

Run this command to generate and activate a virtual environment.

```shell
uv venv
source .venv/bin/activate
```

Run this command to re-install the Open Data Product Python library.

```shell
uv pip install --no-cache-dir git+https://github.com/open-data-product/open-data-product-python-lib.git
```

Run this command to start the main script.

```shell
Usage: main.py [OPTIONS]

Options:
  --clean BOOLEAN  Regenerate results
  --quiet BOOLEAN  Do not log outputs
  --help           Show this message and exit.
```

## Roadmap

See the [open issues](https://github.com/open-data-product/open-data-product-berlin-lor-health-and-social-structure-atlas-source-aligned/issues) for a list of proposed features (and
 known issues).

## License

Source data distributed under [Creative Commons Namensnennung 3.0 Deutschland Lizenz](https://creativecommons.org/licenses/by/3.0/de/) by [Senatsverwaltung für Wissenschaft, Gesundheit, Pflege und Gleichstellung Berlin](https://www.berlin.de/sen/gesundheit/service/gesundheitsberichterstattung/gesundheit-und-sozialstruktur/).

Data product distributed under the [CC-BY 4.0 License](https://creativecommons.org/licenses/by/4.0/). See [LICENSE.md](./LICENSE.md) for more information.

## Contact

opendataproduct@gmail.com
