# Iridopy

**A Python toolkit for eye-tracking data inspection, processing, and analysis.**

Iridopy is an open-source Python project designed to make eye-tracking data easier to inspect, validate, process, and analyse.

The project aims to provide a modular workflow for working with eye-tracking recordings, including data quality assessment, visualisation, and advanced gaze analysis.

## Project Goals

- Inspect recording files and identify available data streams.
- Assess timestamp integrity and data quality.
- Examine channel values, metadata, and sampling characteristics.
- Visualise time-series data and recording events.
- Develop reproducible workflows for eye-tracking data processing.
- Support advanced gaze analysis, including three-dimensional gaze-ray analysis.

## Planned Features

| Feature | Description | Status |
| --- | --- | --- |
| XDF loading | Load recordings and access their data streams | In development |
| Stream inspection | Summarise stream metadata and sampling information | Planned |
| Timestamp validation | Detect duplicated timestamps, invalid ordering, and large gaps | Planned |
| Data quality assessment | Identify missing, non-finite, or suspicious channel values | Planned |
| Time-series visualisation | Plot data streams and recording events | Planned |
| Three-dimensional gaze analysis | Analyse gaze rays and spatial gaze distributions | Planned |
| Reproducible workflows | Record analysis parameters and processing metadata | Planned |

## Installation

Iridopy is currently under development.

Clone the repository and create a virtual environment:

```bash
git clone <repository-url>
cd iridopy

python -m venv .venv
source .venv/bin/activate
python -m pip install -e ".[dev,visualisation]"
```

Replace `<repository-url>` with the repository's actual Git URL once it is available.

## Development

Run the test suite with:

```bash
python -m pytest
```

## Project Structure

```text
iridopy/
├── src/
│   └── iridopy/
├── tests/
├── examples/
├── README.md
├── pyproject.toml
└── .gitignore
```

## Roadmap

1. Establish reliable XDF loading.
2. Implement stream and channel inspection.
3. Add timestamp validation and data quality checks.
4. Develop visualisation tools.
5. Introduce configurable preprocessing and gaze analysis.
6. Expand towards reproducible analysis workflows and reporting.

## Licence

This project is intended to be released under the MIT Licence. See `LICENSE` for the licence terms once the file has been added.