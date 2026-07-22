# The Environmental Cost of Beef Exports

This repository contains datasets and reproducible resources for analyzing the environmental cost of Brazilian beef exports, with emphasis on the Legal Amazon.

The project integrates information on beef exports, wildfires, and land-use and land-cover change.

## Files

* `EXP_ANUAL_carne(2).xlsx`: annual beef export data.
* `historico_regiao_amazonia_legal queimadas(2).xlsx`: historical wildfire data for the Legal Amazon.
* `TABELA-GERAL-MAPBIOMAS-COL8.0-AMAZONIA_LEGAL-1(2).xlsx`: land-use and land-cover data from MapBiomas Collection 8.0.
* `metadados_arquivos.json`: basic metadata extracted from the Excel files.
* `inspecionar_planilhas.py`: Python script for inspecting worksheets, dimensions, columns, and initial rows.
* `requirements.txt`: Python dependencies required to run the script.
* `.gitignore`: files and folders that should not be tracked by Git.

## Research objective

The repository supports research on the relationship between beef exports and environmental degradation in the Brazilian Amazon.

Potential analyses include:

* beef export growth;
* wildfire occurrence;
* land-use and land-cover change;
* pasture expansion;
* deforestation;
* environmental impacts associated with agricultural commodity exports.

## How to use

Create a Python virtual environment:

```bash
python -m venv .venv
```

On Windows:

```bash
.venv\Scripts\activate
```

On Linux or macOS:

```bash
source .venv/bin/activate
```

Install the required packages:

```bash
pip install -r requirements.txt
```

Run the data inspection script:

```bash
python inspecionar_planilhas.py
```

## Data sources and citation

The files in this repository retain their original formats.

Users must verify and cite the original sources of each dataset, including their authorship, methodology, geographical coverage, temporal coverage, units of measurement, and conditions of use.

The inclusion of third-party datasets in this repository does not transfer ownership or grant a new license for those datasets.

## License

No general license is currently assigned to the datasets because some files originate from third-party sources.

Any future license should distinguish between:

* original scripts and documentation produced for this project;
* datasets governed by the terms and licenses of their original providers.
